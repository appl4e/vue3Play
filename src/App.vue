<template>
  <header class="flex items-center px-4 py-3 bg-blue-400">
    <div class="logo">
      <h1 class="font-bold text-3xl text-white">Logo</h1>
    </div>
    <ul class="ml-auto flex items-center space-x-3 font-medium text-white">
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Blog</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </header>
  <div class="content">
    <aside class="sidebar-1">
      <h2 class="title-1">Sidebar -1</h2>
    </aside>
    <section class="main">
      <h2 class="title-1">Main Content Area</h2>
      <h1 class="text-3xl text-sky-300 mb-4">Hello {{ count }}</h1>
    <button class="bg-pink-500 rounded px-6 py-3" @click="count++">++</button>
    </section>
    <aside class="sidebar-2">
      <h2 class="title-1">Sidebar -2</h2>
    </aside>
    
  </div>

  
</template>

<script>
  export default{
    data() {
      return {name: 'Apple', count: 0}
    }
  }
</script>