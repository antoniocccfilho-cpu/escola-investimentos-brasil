---
description: "Escopo mínimo viável, limites, riscos e critérios de entrega."
icon: scale-balanced
---

# Viabilidade, escopo e limitações

## Recorte do MVP acadêmico

O objetivo é demonstrar **uma jornada educacional que realmente funcione** e uma documentação capaz de explicar como foi construída e validada. A aplicação já existe: o escopo é **evolução, integração de aulas e preparação da apresentação**, sem reescrever toda a infraestrutura.

### Dentro do escopo

- Biblioteca organizada por cursos independentes.
- Saga do Dinheiro como curso introdutório, com aulas e elementos interativos já produzidos.
- Explicação do funcionamento do app e de seus limites.
- Correção de rotas e inconsistências prioritárias quando aprovadas.
- Demonstração verificável de pelo menos um percurso completo.
- Documentação acadêmica, plano de trabalho, fontes e evidências de testes.

### Fora do escopo inicial

- Consultoria financeira personalizada ou recomendação de ativos.
- Execução de ordens de compra/venda ou movimentação financeira.
- Promessa de rentabilidade.
- Reconstrução total do aplicativo e de sua infraestrutura.
- Assistente autônomo de investimentos ou funcionalidades ainda não validadas.

## Riscos e mitigação

| Risco | Efeito possível | Resposta planejada |
| --- | --- | --- |
| Link de aula quebrado | Impede demonstração do percurso | Corrigir mapeamento de IDs e retestar |
| Aulas incompletas | Jornada termina sem conclusão | Delimitar demonstração a conteúdo funcional |
| Métricas fictícias sem rótulo | Induz banca e usuário ao erro | Exibir “demonstração” ou persistir dados reais |
| Falha de internet/plataforma | Interrompe a apresentação | Preparar vídeo e capturas de contingência |
| Resposta equivocada de IA | Conteúdo didático incorreto | Revisão humana e testes de fórmulas |
| Falta de rastreabilidade | Dificulta comprovar entregas | GitBook, GitHub e Drive com datas/versões |

## Critério de pronto para a banca

1. Abrir a plataforma sem impedimentos no ambiente definido.
2. Navegar da biblioteca até uma aula e concluir uma interação.
3. Explicar **o que está implementado, parcial, demonstrativo e futuro**.
4. Mostrar plano acadêmico com atividades e responsáveis.
5. Exibir evidências de testes, revisão humana e decisões.
6. Dispor de roteiro ensaiado e material de contingência.

## Limitações atuais

As observações de 03/11 registram navegação quebrada, métricas demonstrativas e fluxos parciais em determinadas áreas. Esses achados precisam de **reteste**, não de uma simples mudança de etiqueta documental.

**Viabilidade econômica:** não há orçamento consolidado ou custos reais validados. Registrar valores quando houver comprovantes e planos das ferramentas utilizadas.

{% hint style="warning" %}
“Funciona no preview” e “está aprovado para apresentar” são estados diferentes. A última classificação requer validação do grupo, evidências e ensaio da banca.
{% endhint %}
