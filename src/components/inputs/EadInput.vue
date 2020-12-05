<template>
    <div>
        <EadInput :type="type" :name="name" :id="id" :placeholder="placeholder"></EadInput>
    </div>
</template>
<script>
    import {EadInput} from './InputText';
    
    export default {
        name: 'InputText',
        components: {
            EadInput
        },
        props: {
            type: String,
            name: String,
            id: String,
            placeholder: String
        }
    }
</script>