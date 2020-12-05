<template>
    <header>
        <div class="box">
            <a href="" class="">
                <img src="../../assets/images/logo.png" alt="" srcset="">
            </a>
            <EadFrom /> 
        </div>
    </header>
</template>
<script>
    import EadFrom from '../forms/EadForm';
    export default {
        components: {
            EadFrom
        }
    }
</script>
<style scoped>
   header{
        display: flex;
        justify-content: center;
        margin-top:8.5625em;
        align-items: center;
        flex-direction: column;
    }
    .box{
        align-items: center;
        max-width: 20.4375em;
        width: 100%;
    }
    .box a{
        display: flex;
        justify-content: center;
        margin-bottom: 3.5625em;
    }
</style>