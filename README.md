# forms-angular-pond-s4m9
Atividade de desenvolvimento de formulário dinâmico com Angular.
## Tecnologia e conceitos aprendidos
### tecnologias utilizadas
- Angulare
- TypeScript
- HTML5
### Formulários dinâmicos
- Formulários dinâmicos são muito úteis em situações em que gostaríamos de reutilizar o template de um formulário, mas para diferentes contextos, mas com um conteúdo diferente.
- O esqueleto do formulário deve permanecer o mesmo, mas as perguntas podem mudar, sem que o código precise.
- os campos de perguntas podem ser personalizados, e adicionados ou removidos de forma dinâmica.
- no exemplo desenvolvido:
  
  os dados são passados de forma mockada, mas esse template poderia estar integrado a um backend que envia dados de um db;
  
  possui uma validação simples de obrigatoriedade dos campos para enviar o formulário, mas poderíamos ir além no quesito validação dos campos (criar diferentes regras), pois o Angular oferece grande suporte.
### Angular app
- é uma SPA (single-page app)

- Passo-a-passo:

1.     atualizar npm e instalar Angular CLI
2.     criar app: npx ng new forms-angular-app
3.       rodar app: npx ng serve

