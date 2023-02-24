<template>
  <NuxtLayout>
    <home-page/>
  </NuxtLayout>
</template>
<script>
import Navbar from "./components/navbar";
import HomePage from "./pages/home";
export default {
  components: {HomePage, Navbar}
}

</script>