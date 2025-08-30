<template>
    <div class="hello-test">
        <p>Hello Test</p>
        <h1>{{ msg }}</h1>    
    </div>
</template>

<script>
    export default {
        name: 'HelloTest',
        props: {
            msg: String
        }
    }
</script>