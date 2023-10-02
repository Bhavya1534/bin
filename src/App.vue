<template>
  <div>
    <header>
      <h1>Your SAMRAAT</h1>
      <nav>
        <ul>
          <li><router-link to="/aboutme">About</router-link></li>
          <li><router-link to="/Projects">Projects</router-link></li>
          <li><router-link to="/Contact">Contact</router-link></li>
        </ul>
      </nav>
    </header>

    <router-view></router-view>

    <footer>
      <p>&copy; 2023 SAMRAAT</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style scoped>
body {
  font-family: Arial, sans-serif;
  background-color: #f0f0f0;
  color: #333;
  line-height: 1.6;
}

header {
  background-color: #333;
  color: #fff;
  padding: 20px 0;
  text-align: center;
}

header h1 {
  font-size: 2rem;
  margin-bottom: 10px;
}

nav ul {
  list-style: none;
}

nav ul li {
  display: inline;
  margin-right: 20px;
}

nav a {
  text-decoration: none;
  color: #fff;
  font-weight: bold;
}

nav a:hover {
  border-bottom: 2px solid #fff;
}

footer {
  text-align: center;
  padding: 20px 0;
  background-color: #333;
  color: #fff;
}
</style>
