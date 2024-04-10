<template>
  <div>
    <NuxtLayout>
      <header>
        <ul class="flex gap-2 bg-amber-400 w-1/6">
          <li>
            <NuxtLink to="/">Home</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/events">Events</NuxtLink>
          </li>
        </ul>
      </header>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>
<script setup>

</script>