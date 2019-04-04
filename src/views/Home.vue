<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import { RpcClient } from "tendermint";

export default {
  name: "home",
  components: {
    HelloWorld
  },
  mounted() {
    const client = RpcClient("wss://rpc.nylira.net:443");
    client.subscribe({ query: "tm.event = 'NewBlock'" }, event => {
      console.log(event.block);
    });
  }
};
</script>
