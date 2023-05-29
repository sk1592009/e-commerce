<template>Dashboard</template>

<script>
export default {
  created() {
    const token = document.cookie.replace(
      /(?:(?:^|.*;\s*)hexToken\s*=\s*([^;]*).*$)|^.*$/,
      "$1"
    );
    console.log(token);
    //this.$http.defaults.headers.common.Authorization = `${token}`;
  },
};
</script>
