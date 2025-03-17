# Sorteio de Amigo Secreto

Este projeto consiste em um programa simples de sorteio de nomes para um amigo secreto, desenvolvido como parte do aprendizado dos fundamentos de lógica de programação no Programa Alura One.

## Funcionalidades

* **Adicionar Amigos:** Permite adicionar nomes à lista de participantes do amigo secreto.
* **Listar Amigos:** Exibe a lista de amigos adicionados na tela.
* **Sortear Amigo:** Realiza o sorteio aleatório de um dos participantes e exibe o resultado.
* **Limpar Lista:** Limpa a lista de amigos após o sorteio.

## Lógica de Programação

O programa foi desenvolvido utilizando JavaScript, com foco na manipulação de arrays e elementos HTML. A lógica principal pode ser dividida nas seguintes etapas:

1.  **Adicionar Amigos:**
    * A função `adicionarAmigo()` é chamada quando o usuário insere um nome no campo de texto e clica no botão "Adicionar".
    * O nome é obtido do campo de texto e armazenado em uma variável.
    * É realizada uma verificação para garantir que o nome não esteja vazio.
    * O nome é adicionado ao array `amigos`.
    * O campo de texto é limpo e recebe o foco para a próxima adição.
    * A função `atualizarLista()` é chamada para exibir a lista atualizada de amigos.

2.  **Listar Amigos:**
    * A função `atualizarLista()` é responsável por exibir a lista de amigos na tela.
    * Ela obtém o elemento HTML da lista (`listaAmigos`).
    * A lista é limpa para remover os itens anteriores.
    * Um loop é executado para percorrer o array `amigos`.
    * Para cada amigo, um novo elemento `li` é criado e seu conteúdo é definido como o nome do amigo.
    * O elemento `li` é adicionado à lista (`listaAmigos`).

3.  **Sortear Amigo:**
    * A função `sortearAmigo()` é chamada quando o usuário clica no botão "Sortear".
    * É realizada uma verificação para garantir que haja pelo menos um amigo na lista.
    * A função `Math.random()` é utilizada para gerar um índice aleatório dentro do intervalo do array `amigos`.
    * O amigo sorteado é obtido do array usando o índice gerado.
    * O resultado do sorteio é exibido na tela, no elemento HTML `resultado`.
    * A lista de amigos é limpa da tela.

## Estrutura do Projeto

* **index.html:** Contém a estrutura HTML da página, incluindo os campos de entrada, botões e elementos para exibir a lista e o resultado.
* **script.js:** Contém o código JavaScript com a lógica do programa.
* **style.css**: Contém o código CSS com a estilização da página.

## Como Executar

1.  Clone o repositório ou faça o download dos arquivos.
2.  Abra o arquivo `index.html` em um navegador web.
3.  Utilize a interface para adicionar amigos e realizar o sorteio.

## Observações

* Este projeto foi desenvolvido com o objetivo de aprendizado e pode ser aprimorado com funcionalidades adicionais, como a possibilidade de remover amigos da lista ou realizar múltiplos sorteios.
* A interface gráfica é básica e pode ser melhorada com estilos CSS.
  
