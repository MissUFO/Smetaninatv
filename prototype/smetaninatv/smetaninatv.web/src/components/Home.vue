<template>
  <div id="content" class="sixteenbit-content" role="main">
    <section id="post-7" class="post-7 post type-post status-publish format-standard hentry category-uncategorized">
      <header class="site-hero">
        <a href="http://smetaninatv.com/">
          <img class="site-logo" src="img/avatar.png" alt="Татьяна Сметанина" />
        </a>
        <h1>{{ msg }}</h1>
        <h3 style="line-height:1.4;">
          Консультант, веб и мобильный разработчик<br />
          <a href="https://medium.com/@smetaninatv" style="color:#f26925;">
            Пишу @ Medium<br />
          </a>
          <br />
          <a href="mailto:smetaninatv@yandex.ru" style="color:#888888;">smetaninatv@yandex.ru</a>
        </h3>
        <div class="link-buttons-wrapper">
          <div class="col-3">
            <a href="http://linkedin.com/in/smetaninatv">
              <img src="img/linkedin-icon.png" class="link-icon" alt="LinkedIn logo" />
              <h4>Профиль</h4>
            </a>
          </div>
          <div class="col-3">
            <a href="http://behance.net/smetaninate23e">
              <img src="img/behance-icon.png" class="link-icon" alt="Behance logo" />
              <h4>Проекты</h4>
            </a>
          </div>
          <div class="col-3">
            <a href="https://medium.com/@smetaninatv">
              <img src="img/medium-icon.png" class="link-icon" alt="LinkedIn logo" />
              <h4>Статьи</h4>
            </a>
          </div>
        </div>
      </header>
    </section>
  </div>
</template>

<script lang="ts">
    import { Component, Prop, Vue } from 'vue-property-decorator';

    @Component
    export default class Home extends Vue {
        @Prop() private msg!: string;
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
