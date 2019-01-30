<template>
  <div id="search-ip">
    <div>
      <p v-text="ip">ここにIPが表示されます</p>
      <div>
        <input @click="getIp" type="button" value="IPを取得">
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'SearchIp',
    data() {
      return {
        ip: ''
      }
    },
    methods: {
      getIp() {
        this.ip = '111.111.111.111';
      }
    }
  }
</script>
