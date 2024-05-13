## Desafio Back-end Doopay

### Avisos antes de começar

- Crie um repositório no seu GitHub.
- Faça seus commits no seu repositório.
- Envie o link do seu repositório para o local informado pelo recrutador.

### Requisitos téncino

- Você deve utilizar o framework Fastify em um projeto com Node.JS & TypeScript para implementação deste desafio.
- Tente evitar usar muito métodos mágicos ou atalhos já prontos, como bibliotecas, boilerplates e trechos de códigos pronto. Sabemos que essas facilidades aumentam a produtividade no dia-a-dia mas aqui queremos ver o seu código e a sua forma de resolver problemas.
- Valorizamos uma boa estrutura de containeres criada por você.


## Objetivo: Transferência entre Contas Simplificada
Temos 2 tipos de usuários, os comuns e lojistas, ambos têm carteira com dinheiro e realizam transferências entre eles. Vamos nos atentar somente ao fluxo de transferência entre dois usuários.

### Requisitos:

- Para ambos tipos de usuário, precisamos do Nome Completo, CPF, e-mail e Senha. CPF/CNPJ e e-mails devem ser únicos no sistema. Sendo assim, seu sistema deve permitir apenas um cadastro com o mesmo CPF e endereço de e-mail;
- Usuários podem enviar dinheiro (efetuar transferência) para lojistas e entre usuários;
- Lojistas só recebem transferências, não enviam dinheiro para ninguém;
- Validar se o usuário tem saldo antes da transferência;
- Transações podem ser negadas.
- A operação de transferência deve ser uma transação (ou seja, revertida em qualquer caso de inconsistência) e o dinheiro deve voltar para a carteira do usuário que envia;
- Este serviço deve ser RESTFul.


## O que será avaliado e valorizamos ❤️

- Documentação;
- Código limpo e organizado (nomenclatura, etc);
- Conhecimento de padrões (PSRs, design patterns, SOLID);
- Ser consistente e saber argumentar suas escolhas;
- Apresentar soluções que domina;
- Manutenibilidade do Código;
- Tratamento de erros;
- Cuidado com itens de segurança;
- Arquitetura (estruturar o pensamento antes de escrever);
- Carinho em desacoplar componentes (outras camadas, service, repository).

De acordo com os critérios acima, iremos avaliar seu teste para avançarmos para a próxima fase técnica.


## O que será um Diferencial

- Uso de Docker;
- Testes de integração;
- Testes unitários;
- Uso de Design Patterns;
- Proposta de melhoria na arquitetura.


*Boa sorte ;)*
