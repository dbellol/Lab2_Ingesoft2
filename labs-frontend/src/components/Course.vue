<template>
  <div class="d-flex justify-content-center align-items-center h-100">
    <div class="col-12 col-md-6 col-lg-4 text-center">
        <h1><b>Nombre Curso:</b>{{ enrolled.courseName }}</h1>
        <h3>{{ enrolled.courseDurationHours }}</h3>
        <h6>{{ enrolled.role.roleName }}</h6>
    </div>
</div>

</template>

<script>
export default {
  name: "Course",
  props: {
    enrolled: Object
  }
}
</script>

<style scoped>
body, html {
  height: 100%;
  margin: 0;
}

</style>
