# Ionic - Exercício 1 - Alô Mundo

## Configuração e avaliação

Configuração:

- Clone o repositório do projeto
- Abra o terminal no diretório do projeto
- Rode o comando `npm install` para instalar as dependências

Avaliação:

- Rode o comando `ionic server` para rodar a aplicação
- Rode o comando `npm run e2e` para rodar os testes
- O resultado dos testes aparece no terminal

## Especificação

<!-- http://asciiflow.com/ -->

```
+---------------------+
|                     |
|    Fulano           |
|  +---------------+  |
|                     |
|  +---------------+  |
|  | Cumprimentar  |  |
|  +---------------+  |
|                     |
|    Alô, Fulano!     |
|                     |
+---------------------+

```

Seu app deve consistir de uma única página, `page1`, que deve conter os três elementos a seguir:

- uma caixa de texto, inicialmente vazia, com id `editNome`
- um botão, com id `btnCumprimentar` e texto `Cumprimentar`
- um rótulo, com id `labelMensagem` e texto inicial "Alô, Mundo!"

(edite a página `Page1` que está na)

Comportamento esperado:

- Ao digitar um texto na caixa de texto e clicar no botão, o texto do rótulo deve mudar para "Alô, X!", trocando X pelo texto digitado na caixa de texto.
- O texto do rótulo e da caixa de texto não deve se alterar quando a tela é rotacionada.
