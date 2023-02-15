# FRONT-END BÁSICO
Repositório para armazenar meus estudos e para futuras consultas de vários assuntos que eu for vendo ao longo da minha formação como **Desenvolvedor Front-end**. Além de me permitir revisar o que tenho aprendido, consigo colocar em prática conhecimentos de terminal Linux, comandos do Git utilizando o terminal integrado do VS Code, trabalhar com branches e versionamento do meu código e a própria utilização do VS Code com seus atalhos e recursos.
## COMO ESCREVER UMA BOA MENSAGEM DE COMMIT
Uma boa mensagem de commit deve conter a descrição do que foi feito, dessa forma fica mais fácil identificar as mudanças sem que tenha que ver o código. Mesmo em um projeto pessoal, uma boa mensagem de commit é importante. Ainda mais se for um projeto que você não trabalha com frequência.

## BOAS PRÁTICAS DE COMMIT
[Task] – Quando adicionar uma tarefa ou pequenas alterações que não são novas funcionalidades;
Ex.: git c "[Task] Iniciando os trabalhos nesse projeto."

[Feature] – Quando adicionar uma nova funcionalidade. Pode-se usar [Feat] como forma abreviada;
Ex.: git c "[Feature] Add os scripts de tipografia, animação e layout para tablet."

[Fix] – Quando se tratar de uma correção de bug;
Ex.: git c "[Fix] Resolvido o problema com as imagens em dispositivos móveis."

[Docs] – Quando se tratar somente de uma alteração na documentação, como uma atualização no README;
Ex.: git c "[Docs] Incluindo no README a seção BOAS PRÁTICAS DE COMMIT."

[Style] – Quando mudar somente folhas de estilo;
Ex.: git c "[Style] Implementada a funcionalidade de Dark Mode do site."

[Refactor] – Quando refatorar completamente um trecho de código. Pode-se usar [Ref] como forma abreviada;
Ex.: git c "[Refactor] Alteração no método de autenticação que agora utilizará um token JWT."

[Test] - Quando mudar a estrutura ou a forma de testar o projeto;
Ex.: git c "[Test] Adicionando testes de contrato para todos o endpoints de gato de cachorro."

[Private] - Quando se tratar de uma mensagem de commit privada, ou seja, que não será enviado ao repositório remoto e nem pro projeto ou p/ branch master/main;
Ex.: git c "[Private] Parei no instante 16:22 da aula 65."
## EXEMPLO DE DESCRIÇÃO CURTA
Aqui como o próprio nome diz, coloque uma curta descrição do que foi feito e tente manter no máximo 50 caracteres, mantendo dessa forma somente como um assunto, como nos exemplos de BOAS PRÁTICAS DE COMMIT acima.
## EXEMPLO DE DESCRIÇÃO DETALHADA
Em casos de códigos mais complexos, recomenda-se descrever melhor as alterações realizadas. Mas vale lembrar, nada substitui uma documentação bem escrita! Uma refatoração ou uma implementação nova pedem uma boa descrição.
Por exemplo, como descrever o seguinte problema no commit: O desenvolvedor criou uma função que vai adicionar um produto no carrinho e vai retornar o carrinho. Aplicando o commit semântico, será assim:

```bash
  git c "Criada função de adição de produto [remover o fecha aspas e dar enter p/ pular linha]
  [linha em branco]
  - A função foi criada para os novos clientes, não cadastrados, conseguirem adicionar produtos ao carrinho antes
  do login" [p/ encerrar, coloca-se o fecha aspas e aperta Enter p/ confirmar o commit]
```
