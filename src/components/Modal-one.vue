<template>
  <div>
    <button @click="toggle">Modal</button>
    <teleport to="body">
      <div v-show="show" class="Modal">
        <h1>Titulo</h1>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora,
          repudiandae provident! Id, dolore eaque ea vitae quasi numquam ipsa et
          cupiditate? Ducimus obcaecati autem optio ad placeat quidem aliquam
          porro!
        </p>
        <button @click="toggle">Cerrar</button>
      </div>
    </teleport>
  </div>
</template>

<script>
export default {
  data() {
    return {
      show: false,
    };
  },
  methods: {
    toggle() {
      this.show = !this.show;
    },
  },
};
</script>
