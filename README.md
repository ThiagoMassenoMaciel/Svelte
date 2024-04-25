# Svelte é um compilador [docs](https://svelte.dev/)
#### vai compilar o meu código e transformar em um javaScript pura (Vanila Js) 
#### código sem dependências, e não usa DOM  virtual

### `npx degit sveltejs/template exemplo_simples`
### `cd exemplo_simples`
### extensão svelt for vs code id `svelte.svelte-vscode`
## Se quiser deixar setado para TypeScript 
![alt text](./assents/image.png)
![alt text](./assents/image-1.png)
### volte para pasta raiz do projeto e executa `npm i`
### dentro da pasta `node_modules/@tsconfig/svelte/ tsconfig.json`  copie a linha do target e cole dentro da pasta raiz do projeto dentro do campo buildOptions no tsconfig.json 
![alt text](./assents/image-2.png)
### agora execute da pasta raiz do projeto `npm run dev`

# Criando um componente
### é um arquivo do tipo .svelte que tem pradrozinado pedaço `script`  `<main>` `<style/>`
### e quando ele for usado como componente é o nome do arquivo que vai funcionar como se fosse uma tag html `<Nome_do_arquivo/>`
### como é possivel passar a propriedade para um componente botão ?

### dentro do arquivo `App.svelte` colocar componente dentro da tag html `<main> <main/>`
# Passando valor para o componente
### e se eu quiser passar valores para o componente pela propriedade , como faço isso ?
#### 1. cria a propriedade = criar uma variavel no pedaço script dentro do arquivo do componente
#### Qual tipo de dado desta propriedade ? vai depender se for um dado imutável  ou dado mutável ( const , let )
#### 2.                    = agora deixar a variavel visivel usando export  `export let variavel = ''`
#### Agora esta variavel que esta dentro do script do arquivo do componente pode ser usado como propriedade do componente , quando for usar o componente na pagina princiap `App.svelte`
#### 3. fazer o valor da variavel dentro do script aparecer no html . Basta somente colocar o nome da variável entre chaves dentro da tag html `variavel` . isso é o mesmo que interpolar variavel


###### 23 - 15' assisti 10' do tutorial
###### 24 - 30' pratiquei até 4'44" do tutorial
###### 24 - 50' pratiquei até 11" do tutorial



# parei 4:44
https://youtu.be/SVNTizLyuvo
