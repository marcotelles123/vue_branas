<template>
  <div>
    <div id="slogan" class="text-center">
      <h1>NameGator</h1>
      <br />
      <h6 class="text-secondary">Gerador de nomes usao Vue.js, GraphQl e Node</h6>
    </div>
    <AppItemList></AppItemList>
    <div id="main">
      <DomainList></DomainList>
    </div>
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";
import "font-awesome/css/font-awesome.css";
import DomainList from "../src/components/DomainList";
export default {
  name: "app",
  components: {
    DomainList
  },
};
</script>

<style>
#slogan {
  margin-bottom: 30px;
  margin-top: 30px;
}
#main {
  background-color: #f1f1f1;
  padding-bottom: 30px;
  padding-top: 30px;
}
</style>
