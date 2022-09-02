<template>
   <form action="">
        <div>
            <InputText/>
        </div>
        <div>
            <InputText/>
        </div>
        <div>
            <Submit/>
        </div>
        <div>
            <InputPassword/>
        </div>
    </form> 
</template>
<script>
import InputPassword from './form/InputPassword.vue'
    import InputText from './form/InputText.vue'
    import Submit from './form/Submit.vue'

    export default {
        components: { InputText, Submit, InputPassword },
        name: 'Form',
        InputText,
        Submit
    }
</script>