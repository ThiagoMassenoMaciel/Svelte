<script lang="ts">
    import Botao from "./Botao.svelte";
    import Linha from "./Linha.svelte";
    import Tela from "./Tela.svelte";
</script>

<div class="calculadora">
  <Tela valor="00000001234567890"/>
  <Linha>
    <Botao destaque triplo texto = "AC"/> <!--   ou   triplo={true}-->
    <Botao operacao texto = "/"/>
  </Linha>

  <Linha>
    <Botao texto = "7"/>
    <Botao texto = "8"/>
    <Botao texto = "9"/>  
    <Botao operacao texto = "*"/>  
  </Linha>

  <Linha>
    <Botao texto = "4"/>
    <Botao texto = "5"/>
    <Botao texto = "6"/>  
    <Botao operacao texto = "+"/>
  </Linha>

  <Linha>
    <Botao texto = "1"/>
    <Botao texto = "2"/>
    <Botao texto = "3"/>  
    <Botao operacao texto = "-"/>
  </Linha>

  <Linha>
    <Botao duplo texto = "0"/>
    <Botao texto = ","/>
    <Botao destaque texto = "="/>  
  </Linha>
</div>

<style>
  .calculadora{

    background-color: var(--cor-fundo);

    height: 220px;
    width: 150px;
    padding: 10px;

    border-radius: 10px;

    display: flex;
    flex-direction: column;
  }
</style>