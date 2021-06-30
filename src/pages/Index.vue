<template>
  <DateCustom date=30 month=6 year=2021 :activeDateList="listActiveDateInit" />
</template>

<script>
import { defineComponent } from 'vue';
import DateCustom from "../components/date.vue"

export default defineComponent({
  name: 'PageIndex',
  components: {
    DateCustom,
  },
  data() {
    return {
      listActiveDateInit: ["26-6-2021", "28-6-2021"],
    }
  },

  methods: {
    changeData() {}
  }

})
</script>
