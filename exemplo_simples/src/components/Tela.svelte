<script lang="ts">
  export let valor : string 

  $: tamanhoFonte = valor.length > 20 ? `pequena` : `s-${valor.length}`
</script>

<div class={`tela ${tamanhoFonte}`}>
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
    text-align: center;
    overflow: hidden;

    font-size: 1.7rem;

    padding: 0px 5px;
    margin: 2px 1px;

    border-radius: 5px 5px 0px 0px;

    background-color: aliceblue;
  }

  .s-10{ font-size: 1.5rem;  }
  .s-11{ font-size: 1.4rem;  }
  .s-12{ font-size: 1.33rem; }
  .s-13{ font-size: 1.24rem; }
  .s-14{ font-size: 1.15rem; }
  .s-15{ font-size: 1.06rem; }
  .s-16{ font-size: 0.99rem; }
  .s-17{ font-size: 0.94rem; }
  .s-18{ font-size: 0.89rem; }
  .s-19{ font-size: 0.84rem; }
  .s-20{ font-size: 0.8rem; }
  .pequena{ font-size: 0.5rem; }


</style>