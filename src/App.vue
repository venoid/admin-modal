<template>
  <div id="app">
    <h1>Venoid-admin modal</h1>
    <a href="https://bitbucket.org/venoid/admin-modal#readme">
      <b-icon icon="link" />
      DOCS
    </a>
    <hr>
    <b-button @click="isActive = true">Show modal</b-button>
    <venoid-modal
      :active="isActive"
      :actions="actions"
      header="Modal header"
      :close-button="true"
      @close="isActive = false"
    >
      Content here :)
    </venoid-modal>
  </div>
</template>

<script>
import VenoidModal from './Modal.vue';

export default {
  name: 'app',
  components: {
    VenoidModal,
  },
  data() {
    return {
      isActive: false,
      actions: [
        {
          label: "cancel",
          onclick: () => this.isActive = false
        }
      ]
    }
  },
  methods: {
  }
};
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
