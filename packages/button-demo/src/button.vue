<template>
    <div class="wrapper">
        <div class="button">{{btnText}}</div>
    </div>
</template>

<script>
export default {
    name: "button",
    props:{
        btnText:{
            default: '按钮',
            type: String
        }
    }
}
</script>

