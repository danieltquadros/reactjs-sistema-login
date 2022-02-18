B7Daily #6 - Sistema de Login com React (ContextAPI, Router, Token e Persistência)

OBJETIVO:

- O objetivo deste projeto é desenvolver um sistema em que haja um sistema de acesso com validações, com processos de Logar e Deslogar.

PROPOSTA DO DESENVOLVIMENTO LÓGICO DO PROJETO:

VALIDAR ACESSO:

- 1. Saber que tem um usuário logado.
- 2. Se tiver, eu tenho que VALIDAR este usuário.
- 3. Se sim, liberar acesso.

LOGAR:

- 1. Receber os dados de login.
- 2. Envia uma requisição para o BACKEND validar estes dados no banco de dados.
- 3. Estando correto, salva-se alguma referência do usuário no browser.
- 4. Se estiver errado, avisa que está errado.

DESLOGAR:

- 1. Apago a referência que existir no browser.
- 2. Enviar uma requisição ao BACKEND avisando para destruir aquela referência.
- 3. Atualizo a página.

OBSERVAÇÕES:

- 1. Não temos disponível para o desenvolvimento deste projeto aula nenhum banco de dados ou API com informações de usuário e senha para trabalharmos as validações, por este motivo, apesar de termos desenvolvido um sistema da forma como se houvesse um banco de dados, fizemos com que qualquer coisa que seja digitado no campo de e-mail e senha libere o acesso.

- 2. Link da vídeo aula utilizada: https://www.youtube.com/watch?v=iD94avNeoXM
