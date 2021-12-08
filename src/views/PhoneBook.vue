<template>
  <div class="about">
    <h1>This is PhoneBook</h1>
    <p>typeScript Vuex Example</p>
    <PhoneBook />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import PhoneBook from "@/components/phonebook/body.vue";
export default defineComponent({
  components: { PhoneBook },
});
</script>

<style lang="scss" scoped>
div.about{
  max-width: 767px;
  width: 100%;
}
</style>