<template>
  <header>
    <h1>{{ this.$store.state.headerText }}</h1>
  </header>
</template>

<style scoped>
/* 컴포넌트 안에서만 유효한 스타일이 됨 */
h1 {
  color: #2f3b52;
  font-weight: 900;
  margin: 2.5rem 0 1.5rem;
}
</style>
