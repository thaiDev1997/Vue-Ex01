<template>
    <div class="about">
        <h1>Hello {{their_name}}, This is an about page</h1>
        <p> Lorem ipsum dolor sit, amet consectetur adipisicing elit. Autem quod veritatis reprehenderit quibusdam. Quisquam fuga culpa veniam ad aliquid quas ipsa ullam, provident expedita totam officia incidunt rem fugiat nobis? </p>
    </div>
</template>


<script>
export default {
  name: "Skill",
  data() {
    return {
      their_name: this.$route.params.name
    };
  }
};
</script>

