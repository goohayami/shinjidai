<template>
  <section>
    <nav>
      <ul>
        <router-link to="/"><li>ホーム</li></router-link>

        <router-link to="/about"><li>イントロ</li></router-link>

        <router-link to="/shintwo"><li>Aメロ1</li></router-link>
      </ul>
    </nav>
    <router-view />
  </section>
</template>

<style>
#app {
  font-family: "M PLUS Rounded 1c", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 0;
  list-style: none;
  text-decoration: none;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
  text-decoration: none;
}

nav a.router-link-exact-active {
  color: #de1414;
  background-color: pink;
  border-radius: 8px;
  text-decoration: none;
}

ul {
  display: flex;
  text-align: center;
  justify-content: center;
  text-decoration: none;
  padding: 0;
}

li {
  font-size: 1rem;
  list-style: none;
  text-decoration: none;
  margin-left: 1rem;
  margin-right: 1rem;
}
</style>
