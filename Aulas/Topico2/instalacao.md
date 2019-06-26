# Instalação e Configuração do Git


<img src="config.jpg " alt="Resumo" width=500 height=265>


## Instalando

Para fazer a instalação do Git, basta acessar o site: https://git-scm.com/ e seguir os passos para instalação de acordo com o seu sistema operacional. 

## Configurando o Git

### Configuração Inicial

Após a instalação do Git, é necessário configurar as suas informações pessoais definindo seu username e email. Abra o terminal e digite: 

``` $ git config --global user.name "Seu Nome" ```

**Clique Enter**

Digite: 

``` $ git config --global user.email "seu.nome@example.com" ```

**Clique Enter**

Pronto! A configuração inicial foi feita e podemos prosseguir.

### Definindo um Editor de Texto

O Git utiliza como editor padrão o Vim ou o Vi, mas podemos definir o editor de texto que desejamos usar. 

No terminal, basta digitar: 

**Para utilizar o VSCode:**

``` $ git config --global core.editor "code --wait"  ```

**Para utilizar o Sublime:**

``` $ git config --global core.editor subl  ```

### Verificando minha configuração

É possível verificar as configurações utilizando o comando: 

``` $ git config --list ```

Dessa forma, será exibido no terminal todas as configurações que o Git encontrar naquele momento. 

<br>Mais informações em: [Git-SCM](https://git-scm.com/book/pt-br/v1/Primeiros-passos-Configura%C3%A7%C3%A3o-Inicial-do-Git)



