<template>
  <DateCustom v-model="year" _date=26 _month=6 _year=2021 :_activeDateList="listActiveDateInit" />
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
      // date : "",
      // month: "",
      // year: ""
    }
  },

  methods: {
    changeData() {}
  }

})
</script>
