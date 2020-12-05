<template>
    <form>
        <div class="login">
           <InputText type="text" name="user_login" id="user_login" placeholder="Login" />
        </div>
        <div class="password">
            <InputText type="password" name="user_password" id="user_password" placeholder="Senha" />
        </div>
        <div class="button">
            <ButtonSubmit type="submit" name="btn_submit" id="btn_submit" value="Entrar"/>
        </div>
    </form>
</template>
<script> 
    import InputText from '../inputs/EadInput';
    import ButtonSubmit from '../buttons/EadButton';

    export default {
    name: 'EadForm',
     components: {
         InputText,
         ButtonSubmit
     }
    } 
</script>
