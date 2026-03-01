<template>
  <h2 id="work">Works</h2>
  <p class="subtitle">作品</p>
  <div class="works">
    <article>
      <img src="../../assets/blog.png">
      <a target="_blank" href="https://arislo-blog.pages.dev/">
        <h3>Arislo | ブログサイト</h3>
      </a>
      <p>Astro + Viteで制作をしました。</p>
    </article>
    <article>
      <img src="../../assets/data.png">
      <a target="_blank" href="https://r-to-python.pages.dev/">
        <h3>Py-R | データ分析サイト</h3>
      </a>
      <p>Astro Starlightで制作をしました。</p>
    </article>
    <article>
      <img src="../../assets/edu.png">
      <a target="_blank" href="https://kosenobi.pages.dev/">
        <h3>こせのび | 教育サービスデモサイト</h3>
      </a>
      <p>Vue + viteで制作しました。</p>
    </article>
  </div>
  <h2 class="comment">Thank you for coming!</h2>


</template>

<style scoped>
img {
  width: 300px;
}

#work {
  font-size: 3rem;

  display: flex;
  justify-content: center;
}

.subtitle {
  font-size: 1rem;

  display: flex;
  justify-content: center;
  margin-bottom: 1rem;
}

.works {
  display: flex;
  justify-content: center;
  gap: 80px;
}

article {
  display: flex;
  flex-direction: column;
}

a {
  color: #222;
}
.comment{
  text-align: center;
  font-size: 2rem;
  padding: 1rem;
  margin-top: 2rem;
}

@media screen and (max-width: 650px) {
  .works {
    display: block;
    text-align: center;
  }

  article {
    margin-bottom: 3rem;
  }

  img {
    width: 80%;
    display: block;
    margin: 0 auto;
  }
}
</style>
