<template>
  <header>
    <nav>
      <div class="logo">
        <router-link to="/">Thecno</router-link>
      </div>
      <ul>
        <li>
          <router-link to="/cursos">Cursos</router-link>
        </li>
        <li>
          <router-link to="contato">Contato</router-link>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: "TheHeader"
};
</script>

<style scoped>
a.router-link-active {
  color: #4b8;
}

.logo {
  flex: 1;
}

.logo a {
  color: white;
  font-size: 1.2rem;
}

header {
  background: #234;
}

nav {
  max-width: 800px;
  margin: auto;
  display: flex;
  align-content: space-between;
  padding: 20px;
}

header a {
  color: white;
}

ul li {
  display: inline-block;
}
li a {
  padding: 0 10px;
  margin-left: 10px;
}
</style>
