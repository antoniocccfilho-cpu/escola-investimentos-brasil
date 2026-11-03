---
description: "Responsabilidade educacional, privacidade, segurança e controles a verificar."
icon: shield-check
---

# Ética, privacidade e segurança

## Compromissos do projeto

A Escola de Investimentos deve ensinar conceitos e pensamento crítico, sem se apresentar como consultoria de investimentos. Simulações mostram cenários **hipotéticos**, sem garantia de retorno.

A [CVM explica a diferença entre educação financeira e atividades profissionais reguladas](https://www.gov.br/investidor/pt-br/investir/como-investir/profissionais-do-mercado/a-diferenca-entre-educacao-financeira-e-o-exercicio-profissional-de-atividade-regulamentada). Essa separação deve estar clara no conteúdo e na demonstração.

## Proteção de dados e LGPD

A [ANPD disponibiliza orientações de segurança da informação](https://www.gov.br/anpd/pt-br/centrais-de-conteudo/materiais-educativos-e-publicacoes/guia-orientativo-sobre-seguranca-da-informacao-para-agentes-de-tratamento-de-pequeno-porte). Para este projeto, a equipe deve verificar ao menos:

- **Finalidade:** por que cada dado é necessário para a experiência.
- **Minimização:** coletar o mínimo indispensável.
- **Transparência:** explicar o uso de dados ao aluno.
- **Acesso:** restringir dados individuais ao perfil apropriado.
- **Segurança:** não expor tokens, credenciais, e-mails, matrículas ou capturas com sessão aberta.
- **Retenção/exclusão:** definir prazos e mecanismos compatíveis com os serviços utilizados.
- **Terceiros:** identificar serviços externos e suas responsabilidades.

{% hint style="warning" %}
Não afirmamos que o aplicativo está “100% em conformidade com a LGPD”: os fluxos de autenticação, armazenamento, retenção e exclusão **ainda precisam de inspeção técnica**.
{% endhint %}

## Riscos educacionais e de IA

| Risco | Cuidado necessário |
| --- | --- |
| Exemplo financeiro confundido com recomendação | Aviso educativo e ausência de sugestão personalizada de ativo |
| Erro de cálculo | Fórmulas conferidas e cenários de teste |
| Explicação falsa gerada por IA | Fonte, revisão humana e possibilidade de correção |
| Discriminação ou exclusão | Linguagem inclusiva e testes de acessibilidade |
| Manipulação por promessa de lucro | Proibir mensagens de rentabilidade garantida |
| Divulgação de dados acadêmicos | Publicar apenas informações necessárias e autorizadas |

## Plano de verificação

1. Mapear os dados efetivos do app e seus responsáveis.
2. Testar cadastro, login e permissões com contas de demonstração.
3. Revisar os avisos educacionais de cursos e simuladores.
4. Verificar se a documentação pública não contém dados pessoais desnecessários.
5. Registrar achados, correções e aceites no diário técnico.

**Fontes:** requisitos do Projeto A3, ANPD, CVM e inventário documentado no [capítulo de dados](08-dados-utilizados.md).
