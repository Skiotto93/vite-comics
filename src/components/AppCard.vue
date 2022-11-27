<script>
export default {
  name: "AppCard",
  props: {
    img: String,
    title: String,
  },
};</script>

<template>
    <div class="card">
        <img :src="img" :alt="title" />
        <h3>{{ title }}</h3>
    </div>
</template>

<style>
h3 {
    color: #fff;
}
</style>