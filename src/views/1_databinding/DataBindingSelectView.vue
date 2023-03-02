<template>
  <div>
    <select name="" id="" v-model="selectedCity" @change="fnCityName">
      <option value=""></option>
      <option value="02">서울</option>
      <option value="051">부산</option>
      <option value="064">제주</option>
    </select>
    <div>Are you select {{ cityName }}??</div>
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {
      selectedCity: '051',
      cityName: '부산'
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {
    fnCityName() {
      const cityNameMap = {
        '02': '서울',
        '051': '부산',
        '064': '제주'
      }
      this.cityName = cityNameMap[this.selectedCity]
    }
  }
}
</script>
