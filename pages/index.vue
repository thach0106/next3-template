<template>
  <div>
    <Head>
      <Title>{{ title }}</Title>
      <Meta name="description" :content="title" />
    </Head>
    <card/>
  </div>
</template>

<script setup lang="ts">
  const title = "title";
</script>