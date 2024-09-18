<template>
    <h2>Simple Form (22)</h2>
    <ul>
        <li v-for="item in error" v-bind:key="item">
            {{item}} not valid
        </li>
    </ul>

    <form class="border">
        <label>Email: </label>
        <input type="text" placeholder="Enter email" v-model="form.email" />
        <br><br>
        <label>Password: </label>
        <input type="password" placeholder="Enter password" v-model="form.password" />
        <br><br>
        <select v-model="form.country">
            <option>India</option>
            <option>China</option>
            <option>USA</option>
        </select>
        <br><br>
        <h3>Technology</h3>
        <label>Java</label>
        <input type="checkbox" value="java" v-model="form.technology" />
        <br><br>
        <label>.Net</label>
        <input type="checkbox" value=".net" v-model="form.technology" />
        <br><br>

        <h3>Gender</h3>
        <label>Male</label>
        <input type="radio" value="male" name="gender" v-model="form.gender" />
        <br><br>
        <label>Female</label>
        <input type="radio" value="female" name="gender" v-model="form.gender" />
        <br><br>
        <button v-on:click="login()" type="button">Login</button>
    </form>
    <br><br>
</template>

<script>
    export default {
        name: "SimpleForm",

        data() {
            return {
                form: {
                    email: "",
                    password: "",
                    country: "",
                    technology: [],
                    gender: "",
                },
                error: [],
            }
        },

        methods: {
            login() {
                this.error = [];

                for (const item in this.form) {
                    if (this.form[item] === "" || this.form[item].length === 0) {
                        this.error.push(item)
                    }
                }

                if (this.error.length === 0) {
                    alert("data has been submitted");
                }

                console.warn(this.form, this.error)
            }
        }
    }
</script>

<style scoped>
h2 {
    color: rgb(0, 187, 255)
}

.border{
    border: 1px solid;
    padding: 5px;
    margin-left: 500px;
    margin-right: 500px;
}
</style>
