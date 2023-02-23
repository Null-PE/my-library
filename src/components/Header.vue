<template>
  <header class="header">
    <nav>
      <ul class="header-nav">
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/books">Books</router-link></li>
        <li><router-link to="/about">About</router-link></li>
      </ul>
    </nav>
    <div class="search-box">
      <input type="text" placeholder="Search...">
      <button>Search</button>
    </div>
  </header>
</template>

<style>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 80px;
  padding: 0 20px;
  background-color: #fff;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.header-nav {
  display: flex;
  list-style: none;
  margin: 0;
  padding: 0;
}

.header-nav li {
  margin-right: 20px;
}

.header-nav li:last-child {
  margin-right: 0;
}

.header-nav a {
  text-decoration: none;
  color: #333;
  font-size: 16px;
}

.search-box {
  display: flex;
  align-items: center;
  height: 40px;
  border: 1px solid #ccc;
  border-radius: 20px;
  padding: 0 10px;
}

.search-box input {
  flex: 1;
  border: none;
  outline: none;
  font-size: 16px;
}

.search-box button {
  background-color: #1abc9c;
  color: #fff;
  border: none;
  border-radius: 20px;
  padding: 8px 16px;
  font-size: 16px;
  cursor: pointer;
  margin-left: 10px;
}

.search-box button:hover {
  background-color: #148f77;
}
</style>
