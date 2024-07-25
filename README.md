# Validações
Site que valida CPF e E-mails.

## Descrição 
O site tem uma proposta simples, feito apenas com o intuito de testar e aprender coisas do JavaScript, como validar certas coisas, nesse caso E-mais e CPFs.

## Funções
O site tem diversas funções do JavaScript que foram aprendidas durante a aula.

``CPF``

- GetElementById tem a função de criar um identificador para uma palavra, para a encontrar depois.
- A função será executada quando o formulário for enviado.
- event.preventDefault(); impede que o formulário seja enviado para o servidor, permitindo que a validação seja feita no próprio JavaScript.
- msg.textContent tem a função altera a cor da fonte dependendo do resultado. Caso seja válido fica verde, caso seja invalido fica vermelho.
- cpf.replace tem a função de anular os caracteres indesejados.
- if(cpf.length) tem a função de ver se o CPF tem o tanto de digitos necessarios.

``E-mail``

- if(document.forms[0].email.value == "" || ...) verifica se o campo está vazio, se for o caso ele diz como inválido
- document.forms[0].email.value.indexOf('@') == -1 verifica se existe o @ no campo, como processo de um E-mail válido


## Sobre o site
O site apenas tem a função de mascarar o seu real significado que é aprofundar alguns elementos do JavaScript. Tendo um css simples.

## Tecnologias utilizadas 

* ``HTML 5``
* ``CSS 3``
* ``Github``
* ``VsCode``
* ``Microsoft Teams``
