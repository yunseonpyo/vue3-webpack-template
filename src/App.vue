<template>
  <h1> {{ message }} </h1>
  <HelloWolrd />
</template>

<script>
import HelloWolrd from "~/components/HelloWorld"

export default {
  components: {
    HelloWolrd
  },
  data() {
    return{
      message : "Hello Vue!!!"
    }
  }
}
</script>