<template>
  <div class="row_position">
    <ApplicationForm/>
  </div>
</template>

<script>
import ApplicationForm from "~/components/ApplicationComponent/ApplicationForm";
export default {
  name: "request-form",
  components: {
    ApplicationForm
  }
}
</script>

<style scoped>
.row_position{
  justify-content: center;
}
</style>
