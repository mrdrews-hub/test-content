<script setup lang="ts"></script>
<template>
  <section class="flex flex-col gap-2">
    <h2 class="font-bold text-2xl">
      <slot name="title"></slot>
    </h2>
    <h3>
      <slot name="description"></slot>
    </h3>
  </section>
</template>