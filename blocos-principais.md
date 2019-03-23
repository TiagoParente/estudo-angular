# Blocos Principais
Breve resumo do que será usado para desenvolver as aplicações com *Angular*, logo abaixo segue o exemplo de como podemos organizar nossa aplicação usando Angular.

<img src="https://user-images.githubusercontent.com/9920715/54869426-e847a580-4d76-11e9-840d-3c6555231a16.png" width=50%>


## Componentes
Além de mostrar dados, é responsável por mostrar os dados na view, é algo importanto no Angular a utilização do mesmo, as aplicações são orientadas a componentes, dentro de um componente eu posso ter outros dentro dele, exemplo de utilização:

<img src="https://user-images.githubusercontent.com/9920715/54869099-afa5cd00-4d72-11e9-9051-106a67f1253b.png" width=70%>

**O que é encapsulado dentro de um componente?**

* Template
* Metadata
* Data-binding

## Diretivas
> A diretiva é responsável pela manipulação do meu elemento DOM, e lembrando que o componente também é uma diretiva, já que ele modifica o meu elemento DOM. Exemplo de diretiva para crescer meu campo de input:
				
	<input type="text" **autoGrow**>

## Roteamento (Router)
> Angular trabalhar com o conceito SPA (*Single Page Application*), com isso para ir de uma tela para a outra eu usaria o **Router**. (Basicamente segue a mesma ideia do Laravel).

## Serviços
> O serviço é responsável pela integração do meu componente com o meu back-end, esse meu back-end pode ser em qualquer linguaguem, ex: *Node.JS*, *PHP*, *Java*, *.NET*.

## Templates
> Resumidamente é o meu código HTML, pode ser um formulário, uma table ou até mesmo uma div.

## Metadata
> Ele esta presente dentro dos componentes, ele permite que o Angular ler e processar as classes.

## Data Bindings
> É basicamente a ponte entre o componente e o meu template, com os data binging é possível exibir algo do meu componente no meu template.

## Injeção de Dependências
> Pode ser usado por exemplo para a injeção de serviços em outras classe. (*Isso será estudado mais pra frente*)
.




