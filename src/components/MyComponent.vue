<template>
    <div id="myComponent">
        <h1>Este es mi componente</h1>
    <h2>{{ subtle }}</h2>
    </div>
</template>

<script>
export default {
    name: 'MyComponent',
    data() {
        return {
            subtle: 'I´m the subtle in h2'
        }
    }
}

</script>