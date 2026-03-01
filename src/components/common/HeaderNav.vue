<template>
  <header>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#work">Work</a></li>
        <li><a href="#skill">Skill</a></li>
      </ul>
    </nav>
  </header>
</template>

<style scoped>
header {
  display: flex;
  align-items: center;

}

header ul {
  list-style: none;
  display: flex;
  padding: 1rem;
  gap: 16px;
}

header a {
  color: #333;
  text-decoration: none;
}
</style>
