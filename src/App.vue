<template>
  <header>
    <router-link :to="{ name: 'home' }"> Home |</router-link>
    <router-link to="/categorias"> Categorias |</router-link>
    <router-link to="/autoras"> Autor </router-link>
  </header>
  <main>
    <RouterView />
  </main>
</template>
