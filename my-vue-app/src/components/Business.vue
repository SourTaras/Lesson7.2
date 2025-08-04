<template>
<div>
<ul>
<li>{{ name }} </li>
<li>{{ phone }} </li>
<li>{{ email }} </li>
</ul>
</div>
</template>
<script>
export default {
    name: "BusinessComponent",
    props: {
        name: {
            type: String,
            required: true
        },
        phone: {
            type: Number,
            required: true
        },
        email: {
            type: String,
            required: true
        }
    }
}
</script>
