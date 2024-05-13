README - Desafio Back-end para Fintech
📌 Avisos Antes de Começar
Repositório: Crie um repositório no seu GitHub sem mencionar nada relacionado à empresa.
Commits: Faça seus commits no seu repositório.
Submissão: Envie o link do seu repositório para o local informado pelo recrutador.
Consulta: Você poderá consultar o Google, Stackoverflow ou algum projeto particular na sua máquina.
Entrevista: Dê uma olhada em como será a entrevista.
🖥️ Sobre o Ambiente da Aplicação
Tecnologias: Utilize o framework Fastify em um projeto com Node.JS & TypeScript.
Código: Evite métodos mágicos ou atalhos prontos, como bibliotecas e boilerplates.
Containerização: Valorizamos uma boa estrutura de containers criada por você.
📅 Para o Dia da Entrevista Técnica
Demonstração: Tenha sua aplicação rodando na sua máquina local para execução dos testes e demonstração.
Code Review: Faremos um code review como se você já fosse parte do nosso time. Explique suas escolhas de arquitetura, implementação e possíveis evoluções do projeto.
🎯 Objetivo do Desafio
Transferência entre Contas Simplificada

Usuários: Dois tipos de usuários - comuns e lojistas. Ambos com carteira e capacidade de realizar transferências.
Fluxo: Foco no fluxo de transferência entre dois usuários.
📋 Requisitos
Dados do Usuário: Nome Completo, CPF, e-mail e Senha. CPF/CNPJ e e-mails devem ser únicos.
Transferências:
Usuários podem enviar dinheiro para lojistas e entre usuários.
Lojistas só recebem transferências, não podem enviar dinheiro.
Saldo: Validar saldo antes da transferência.
Autorização: Consultar um serviço autorizador externo antes de finalizar a transferência.
URL do Mock Autorizador: Mock Authorizer
Notificação: No recebimento, enviar notificação via e-mail ou SMS.
URL do Mock Notificador: Mock Notifier
🧐 Avaliação
Documentação: Inclua diagramas UML e arquivo OpenAPIv3.
Código: Foco em código limpo, organizado e padrões de projeto.
Modelagem de Dados e Manutenibilidade: Estruture bem seu banco de dados e código para fácil manutenção.
Tratamento de Erros e Segurança: Atenção especial para estes itens.
Arquitetura: Desacoplamento de componentes e clareza na estrutura.
🚫 O que NÃO Será Avaliado
Frontend: Apenas a API Restful será avaliada.
Autenticação: Não será parte deste desafio.
✨ Diferenciais
Docker: Uso de Docker no projeto.
Testes: Implementação de testes de integração e unitários.
Design Patterns: Aplicação de padrões de design.
Documentação Adicional: Qualquer documentação extra que melhore a compreensão do projeto.
Propostas de Melhoria: Sugestões para evolução da arquitetura.
Faça uma proposta de payload para as transações:

json
Copiar código
POST /transaction
{
  "value": 100.0,
  "payer": "uuid-do-remetente",
  "payee": "uuid-do-destinatário"
}
Boa sorte e estamos ansiosos para ver sua implementação! 🚀
