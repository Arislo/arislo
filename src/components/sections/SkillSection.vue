<template>
  <h2 id="skill">Skills</h2>
  <p class="subtitle">スキル</p>
  <section>
    <div>
      <h3>フロントエンド</h3>
      <ul>
        <li>CSS / Tailwind CSS</li>
        <li>Vue</li>
        <li>Astro</li>
      </ul>
    </div>
    <div>
      <h3>データサイエンス</h3>
      <ul>
        <li>R</li>
        <li>Python</li>
        <li>Excel</li>
      </ul>
    </div>
    <div>
      <h3>ツール</h3>
      <ul>
        <li>Git / GitHub</li>
        <li>Figma</li>
        <li>Cloud flare</li>
      </ul>
    </div>
  </section>
</template>

<style scoped>
#skill {
  font-size: 3rem;

  display: flex;
  justify-content: center;
}

.subtitle {
  font-size: 1rem;

  display: flex;
  justify-content: center;
}

section {
  padding: 2rem;
  display: flex;
  justify-content: center;
  gap: 200px;
}

li {
  padding-top: 0.8rem;
  list-style: none;
}

@media screen and (max-width: 650px) {
  section {
    display: block;
    text-align: center;
  }

  section div {
    margin-bottom: 2rem;
  }
}
</style>
