<script lang="ts">
  export let texto : string
  export let triplo : boolean = false
  export let duplo  : boolean = false 
</script>

<button class= "botao" class:triplo class:duplo> <!--  class:triplo= {triplo} -->
  {texto}
</button>

<style>
  .botao{

    flex-basis: 25%;
  }

  .duplo{
    flex-basis: 50%;
  }
  .triplo{
    flex-basis: 75%;
  }

</style>