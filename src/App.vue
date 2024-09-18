<template>
<!--<img alt="Vue logo" src="./assets/logo.png">-->
<!--5--><HelloWorld msg="Welcome to Code" />
<!--6--><HomeComponent />
<!--7--><InterpolationnAndData />
<!--8--><MethodsComp />
<!--9--><EventVOnClick />
<!--10--><TwoWayBinding />
<!--11--><GetInputFieldValue />
<!--12--><GetCheckboxRadioButtonValue />
<!--13--><IfElseCondition />
<!--14--><ForLoopInVueJs />
<!--15--><PassDataChildComp />
<!--16--><ReuseComponent />
<!--17--><HTMLBinding />
<!--18--><CSSBinding />
<!--19--><PropsInVueJs />
<!--20--><SendDataChildParent />
<!--21--><RefInVueJs />
<!--22--><!--23--><!--24--><SimpleForm />
<!--25--><FormModifiers />
<!--26--><NonPropsData />
<!--27--><ComputedProperty />
<!--28--><WhatchersComp />
<!--29--><!--30--><SlotsInVueJs />
<!--31--><DynamicComponent />

<!--33--><!--34--><BeforeCreateAndCreated />
<!--35--><BeforeMountAndMounted />
<!--36--><BeforeUpdateAndUpdated />
<!--36--><BeforeUnmountAndUnmounted />

<!--32--><TeleportComponent />
</template>

<script>
import EventVOnClick from './components/EventVOnClick.vue';
import HelloWorld from './components/HelloWorld.vue'
import HomeComponent from './components/HomeComponent.vue';
import InterpolationnAndData from './components/InterpolationnAndData.vue';
import MethodsComp from './components/MethodsComp.vue';
import TwoWayBinding from './components/TwoWayBinding.vue';
import GetInputFieldValue from './components/GetInputFieldValue.vue';
import GetCheckboxRadioButtonValue from './components/GetCheckboxRadioButtonValue.vue';
import IfElseCondition from './components/IfElseCondition.vue';
import ForLoopInVueJs from './components/ForLoopInVueJs.vue';
import PassDataChildComp from './components/PassDataChildComp.vue';
import ReuseComponent from './components/ReuseComponent.vue';
import HTMLBinding from './components/HTMLBinding.vue';
import CSSBinding from './components/CSSBinding.vue';
import PropsInVueJs from './components/PropsInVueJs.vue';
import SendDataChildParent from './components/SendDataChildParent.vue';
import RefInVueJs from './components/RefInVueJs.vue';
import SimpleForm from './components/SimpleForm.vue';
import FormModifiers from './components/FormModifiers.vue';
import NonPropsData from './components/NonPropsData.vue';
import ComputedProperty from './components/ComputedProperty.vue';
import WhatchersComp from './components/WhatchersComp.vue';
import SlotsInVueJs from './components/SlotsInVueJs.vue';
import DynamicComponent from './components/DynamicComponent.vue';
import TeleportComponent from './components/TeleportComponent.vue';
import BeforeCreateAndCreated from './components/BeforeCreateAndCreated.vue';
import BeforeMountAndMounted from './components/BeforeMountAndMounted.vue';
import BeforeUpdateAndUpdated from './components/BeforeUpdateAndUpdated.vue';
import BeforeUnmountAndUnmounted from './components/BeforeUnmountAndUnmounted.vue';

export default {
    name: 'App',
    components: {
        HelloWorld,
        HomeComponent,
        InterpolationnAndData,
        MethodsComp,
        EventVOnClick,
        TwoWayBinding,
        GetInputFieldValue,
        GetCheckboxRadioButtonValue,
        IfElseCondition,
        ForLoopInVueJs,
        PassDataChildComp,
        ReuseComponent,
        HTMLBinding,
        CSSBinding,
        PropsInVueJs,
        SendDataChildParent,
        RefInVueJs,
        SimpleForm,
        FormModifiers,
        NonPropsData,
        ComputedProperty,
        WhatchersComp,
        SlotsInVueJs,
        DynamicComponent,
        TeleportComponent,
        BeforeCreateAndCreated,
        BeforeMountAndMounted,
        BeforeUpdateAndUpdated,
        BeforeUnmountAndUnmounted,
    }
}
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
