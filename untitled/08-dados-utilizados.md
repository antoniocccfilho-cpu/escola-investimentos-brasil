---
description: "Inventário de dados, classificação, finalidade e regras de tratamento."
icon: database
---

# Dados utilizados

## Princípio orientador

O protótipo deve trabalhar com **dados mínimos e necessários** para aprendizagem. É essencial separar o que foi **observado**, o que foi **descrito no material técnico** e o que pertence a uma **proposta de arquitetura futura**.

## Inventário inicial

| Informação | Finalidade | Situação identificada | Cuidados |
| --- | --- | --- | --- |
| Conteúdo de cursos, aulas e exercícios | Exibir a jornada didática | Conteúdo observado/inventariado | Versionar, revisar pedagogicamente |
| E-mail e identidade de acesso | Cadastro/autenticação | Relatado na documentação de setembro; testar novamente | Evitar exposição e divulgar política apropriada |
| Respostas e tentativas de quiz | Feedback educacional | Interações observadas; armazenamento não confirmado | Não presumir persistência |
| Progresso e porcentagens | Acompanhar estudo | Números demonstrativos encontrados | Identificar demo até haver dados reais |
| Dados numéricos de simuladores | Explorar cenários hipotéticos | Simuladores relatados e observados na Aula 4 | Não tratar como orientação financeira |
| Capturas e diagnósticos | Provar comportamento do protótipo | 11 imagens arquivadas no Drive | Verificar dados de sessão antes de publicar |
| Registro de decisões e prompts | Rastreabilidade do Projeto A3 | Drive e GitBook/GitHub | Não expor informação pessoal ou segredos |

## Modelo conceitual, não prova de banco de dados

`Curso → Módulo → Aula → Tela` descreve uma **estrutura de conteúdo**. Caso o grupo implemente progresso persistente no futuro, será preciso definir usuários, sessões, matrículas, conclusão de aulas e respostas com regras de acesso, retenção e exclusão.

**Não há evidência suficiente neste diagnóstico para declarar qual banco de dados guarda o progresso ou como os provedores de autenticação armazenam credenciais.**

## Classificação e publicação

- **Público:** descrição do projeto, conteúdos didáticos, documentação técnica sem credenciais e resultados agregados não identificáveis.
- **Interno:** prompts de trabalho, relatórios de bugs, links de pré-visualização e gravações de teste.
- **Restrito:** dados pessoais, matrícula acadêmica, e-mails individuais, informações de autenticação e permissões.

## Perguntas obrigatórias antes da banca

1. Quais dados são efetivamente coletados na versão apresentada?
2. Onde são armazenados e por quanto tempo?
3. O aluno pode visualizar ou apagar seus dados?
4. Há integração com serviços de terceiros? Quais?
5. O que é dado fictício, demonstrativo ou real?

{% hint style="warning" %}
Responder às perguntas com **teste, configuração ou documento verificável**. Não afirmar conformidade com a LGPD sem a verificação correspondente.
{% endhint %}

**Fonte:** Documento 07; documentação do protótipo de setembro; [orientações da ANPD](https://www.gov.br/anpd/pt-br/centrais-de-conteudo/materiais-educativos-e-publicacoes/guia-orientativo-sobre-seguranca-da-informacao-para-agentes-de-tratamento-de-pequeno-porte).
