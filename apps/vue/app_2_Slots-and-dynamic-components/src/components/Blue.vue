<template>
    <div>
        <slot name="title">title</slot>
        <hr />
        <slot name="content">content</slot>
    </div>
</template>

<script></script>

<style scoped>
div {
    border: 1px solid blue;
    background-color: lightblue;
    padding: 30px;
    margin: 20px auto;
    text-align: center;
}
</style>
