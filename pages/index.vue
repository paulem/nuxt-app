<template>
  <div class="flex justify-center mt-6 space-x-2">
    <Button @click="goToDashboard">Go to Dashboard</Button>
    <Button variant="outline" @click="goToMain">Go to Main</Button>
  </div>
</template>

<script>
export default {
  methods: {
    goToDashboard() {
      this.$router.push('/dashboard');
    },
    goToMain() {
      this.$router.push('/main');
    }
  }
};
</script>