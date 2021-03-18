<script lang="ts">
  import { Component, Vue } from "vue-property-decorator";

  import Container from "../components/Container.vue";

  @Component({
    components: {
      Container
    },
  })

  export default class Home extends Vue {}
</script>

<style scoped>

</style>
