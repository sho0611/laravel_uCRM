

<script setup>
import { Link } from '@inertiajs/vue3';
</script>

<template>
  <Head title="Inertia Test" />
  Inertiaテストです。 <br>
  <!-- HTMLのaタグ -->
  <a href="/">aタグ経由です</a> <br>
  <!-- Inertia.jsのLinkコンポーネント -->
  <Link href="/">Linkコンポーネント経由です</Link>
</template>
