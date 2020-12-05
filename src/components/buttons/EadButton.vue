<template>
    <div>
        <EadButton :type="type" :name="name" :id="id" >{{value}}</EadButton>
    </div>
</template>
<script>

    import {EadButton} from './ButtonSubmit';    
    export default {
        name: 'ButtonSubmit',
        components: {
            EadButton
        },
        props: {
            type: String,
            name: String,
            id: String,
            value: String,
        }
    }
</script>