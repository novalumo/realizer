<template>
  <div>
    <!-- hero -->
    <section class="hero">
      <h1>A Community</h1>
      <div class="flex flex-row">
        <a href="#about" class="btn">About</a>
        <a href="#join" class="btn">Join</a>
      </div>
    </section>
    <!-- about -->
    <section id="about">
      <div>
        <h2 class="text-2xl mb-1">What is “Realizer”?</h2>
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Cum in, officia quaerat at quidem commodi labore facilis obcaecati voluptate sapiente a optio itaque vero suscipit voluptatibus eum numquam unde deleniti.
        </p>
      </div>
      <div>
        <img src="~/assets/img/header.jpg" alt="" class="w-1/2">
        <small>Cover image by:</small>
      </div>
    </section>
    <!-- join -->
    <section id="join">
      <div>
        <h2 class="text-2xl mb-1">Join us</h2>
        <p>
          Realizer is now available on Facebook Group.
        </p>
        <a href="https://www.facebook.com/groups/2863739030397691/" class="btn">Join us on Facebook</a>
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
  background-image: url(https://source.unsplash.com/random);
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
    font-size: 3.5rem;
    margin: 0 0 .5rem 0;
  }

  .btn {
    background: #003a5c;
    color: #fff;
    padding: .75rem 1.5rem;
    margin: 0 1rem;
  }
}

#about, #join {
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 3rem;
}

#about {
  background: #000030;
  color: #fff;
  justify-content: center;
  flex-wrap: wrap;

  div {
    width: 480px;
  }
}

#join {
  background: #005780;
  color: #fff;
}
</style>
