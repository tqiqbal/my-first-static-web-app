<template>
  <div>
    <p>Hello {{ value }}</p>
    <p>This is an example of Azure Web app</p>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value: "World"
    };
  }
};
</script>
