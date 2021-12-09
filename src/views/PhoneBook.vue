<template>
  <div class="about">
    <h1>This is PhoneBook</h1>
    <p>typeScript Vuex Example</p>
    <ListInput />
    <PhoneBook />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import PhoneBook from "@/components/phonebook/body.vue";
import ListInput from "@/components/phonebook/listInput.vue"
export default defineComponent({
  components: { PhoneBook,ListInput },
});
</script>

<style lang="scss" scoped>
div.about{
  margin-top: 20px;
  max-width: 767px;
  width: 100%;
  display: flex;
  flex-direction: column;
  gap: 20px;
}
</style>