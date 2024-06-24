<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    <section id="greeting">Hello world!</section>
    <br />
    <button @click="podbij">Podbij</button>
    {{ licznik }}
  </main>
</template>

<script>
export default {
  data() {
    return {
      licznik: 0
    }
  },
  methods: {
    podbij() {
      this.licznik++;
    }
  }
}
</script>