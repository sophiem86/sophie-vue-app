<template>
  <main style="max-width:860px;margin:40px auto;padding:0 16px;font-family:system-ui">
    <h1>🎉 Deployed from GitHub Actions</h1>
    <p>If you can see this at <code>https://sophiem86.github.io/sophie-vue-app/</code>, CI/CD works.</p>
    <ul>
      <li>BASE_URL = <code>{{ base }}</code></li>
      <li>MODE = <code>{{ mode }}</code></li>
    </ul>
  </main>
</template>

<script setup>
const base = import.meta.env.BASE_URL
const mode = import.meta.env.MODE
</script>
