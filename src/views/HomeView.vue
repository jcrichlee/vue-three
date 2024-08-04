<template>
  <div>
    <h1>Welcome Home!</h1>
    <h2>My name is {{ name }}</h2>
    <h3>You can also call me {{ student.name }}</h3>
    <h3>You can always find me at {{ student.school }}</h3>
    <button @click="changeName">Use My Middle Name</button>
  </div>
</template>

<script setup>
import { ref, reactive } from "@vue/reactivity";
const name = ref("Richard");

const student = reactive({
  name: "JCRichLee",
  school: "Alt School",
});

const changeName = () => {
  name.value = "Olorunsogo";
};
</script>
