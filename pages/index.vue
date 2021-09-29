<template>
  <div>
    <!-- hero -->
    <section class="hero">
      <h1 class="text-3xl sm:text-4xl md:text-4xl lg:text-5xl xl:text-7xl">
        <span class="inline-block">“実現”する</span><br><span class="inline-block">起業家の</span><span class="inline-block">コミュニティー</span>
      </h1>
      <div class="flex flex-row">
        <a href="#about" class="btn">
          Realizerとは
        </a>
        <a href="#join" class="btn">
          参加する
        </a>
      </div>
    </section>
    <!-- about -->
    <section id="about">
      <div class="mb-3">
        <h2
          class="text-3xl font-bold mb-1"
        >
          Realizerとは?
        </h2>
        <p class="text-lg">
          起業家同士のつながりを深め、お互いにシナジーを生み出すことができるようなコミュニティを目指して立ち上げられたグループです。宣伝や事業紹介、経営などについてわからないことがあれば相談などができる場です。
        </p>
      </div>
      <div>
        <h2
          class="font-bold text-lg mb-1"
        >
          参加事業者
        </h2>
        <section class="bizs">
          <p>
            <span><ruby>Novalumo<rt>ノバルーモ</rt></ruby>合同会社</span> <span>代表社員 CEO 白澤賢斗</span>
          </p>
        </section>
      </div>
    </section>
    <!-- join -->
    <section id="join">
      <div>
        <h2
          class="text-3xl font-bold mb-1"
        >
          参加する
        </h2>
        <p class="text-lg">
          RealizerはFacebookグループとして運営されています。参加をご希望の方は以下から申請が可能です。
        </p>
        <a href="https://www.facebook.com/groups/2863739030397691/" class="btn">Facebookから参加する →</a>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  head () {
    return {
      title: 'Realizer | 起業家のためのコミュニティ',
      titleTemplate: ''
    }
  }
}
</script>

<style lang="scss" scoped>
.hero {
  background-image: url(/bg.jpg);
  background-size: cover;
  background-position: center center;
  height: 100vh;
  padding: 0 3rem;
  font-weight: bold;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  position: relative;

  &::after {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, .75);
  }

  > * {
    z-index: 20;
  }

  h1 {
    color: #fff;
    margin: 0 0 1.75rem 0;
    text-align: center;
    line-height: 1.1;
  }

  .btn {
    background: #0062a2;
    color: #fff;
    padding: .75rem 2rem;
    margin: 0 1rem;
  }
}

#about, #join {
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 5rem 3rem;
}

#about {
  background: #000030;
  color: #fff;
  justify-content: space-around;
  flex-wrap: wrap;

  div {
    width: 480px;
    margin-left: .5rem;
    margin-right: .5rem;
  }
}

#join {
  background: #005780;
  color: #fff;
  justify-content: space-around;

  .btn {
    background: #000;
    color: #fff;
    margin: 1rem 0 0 0;
    padding: 1rem 1.25rem;
    display: inline-block;
    font-weight: bold;
  }
}

.bizs {
  /* no break on span */
  span {
    display: inline-block;
  }
}
</style>
