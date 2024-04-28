<script lang="ts">
  export let valor : string 
</script>

<div class="tela">
  <span>
    {valor}
  </span>
</div>

<style>
  .tela{
    display: flex;
    flex: 1;
    justify-content: flex-end;
    align-items: center;
    overflow: hidden;

    font-size: 1.7rem;

    padding: 0px 5px;
    margin: 2px 1px;

    border-radius: 5px 5px 0px 0px;

    background-color: aliceblue;


  }
</style>