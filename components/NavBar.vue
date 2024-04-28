<template>
  <header
class="sticky top-0 z-50 flex justify-between items-center space-x-1 border-b bg-white p-4 shadow-md"
>
<NuxtLink class="text-2xl font-mono" to="/">cartrader</NuxtLink>
  </header>
</template>

<script setup>

const router = useRouter();

const HomePage = () => {
  router.push("/");
}


</script>