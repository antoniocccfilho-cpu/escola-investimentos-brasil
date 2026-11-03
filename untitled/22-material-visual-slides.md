# 22 material visual slides

## Projeto A3 Exploração Digital e Fundamentos Tecnológicos

**Prof. Mario Sergio Caldas Teixeira | Turma da Manhã – 2º Sem. 2026**

Caio Roque · Bernardo Veloso · Vinicius Noman · Antonio Caldas · Jackson

## Problema e Oportunidade

Conteúdos financeiros dispersos em múltiplas fontes e linguagens técnicas dificultam o aprendizado. A ausência de sequência didática torna difícil distinguir educação de propaganda.

A nota média de 59,6 pontos na Pesquisa de Letramento Financeiro do Banco Central (a validar) evidencia a lacuna.

A oportunidade: uma plataforma com aprendizagem progressiva, interativa e estruturada.

## Público-Alvo e Necessidades

| Perfil dos Usuários                                                                                                             | Linguagem e Didática                                                                                                                                 |
| ------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| Jovens e adultos iniciantes em finanças pessoais e estudantes intermediários que buscam aprendizagem progressiva e estruturada. | Necessidade de linguagem simples, prática e acessível, sem jargões técnicos e com estrutura didática progressiva e exemplos do cotidiano financeiro. |

| Acompanhamento do Progresso                                                                                                     | Acesso e Tecnologia                                                                                                                |
| ------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| Desejo por visualização clara do próprio avanço, sem recomendação personalizada de investimentos ou promessas de rentabilidade. | Perfil tecnológico básico a intermediário, com acesso via navegador em dispositivos diversos: computadores, tablets e smartphones. |

## Jornada do Usuário

[escoladeinvestimentosbrasil.app](/broken/pages/4d877aebbe51d5a5a4ac4a5a0970617c0b881c57)

{% stepper %}
{% step %}
## Cadastro e Login
{% endstep %}

{% step %}
## Escolha da Trilha
{% endstep %}

{% step %}
## Estudo das Aulas
{% endstep %}

{% step %}
## Práticas e Quizzes
{% endstep %}

{% step %}
## Progresso
{% endstep %}
{% endstepper %}

Fluxo completo desde o cadastro até o acompanhamento do progresso, com aprendizagem progressiva e estruturada em cada etapa da plataforma.

## Arquitetura Funcional

| Componentes Ativos                                                                                                                                                                              | Planejados / Futuros                                                                                                                                                                                 |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p>✅ Autenticação (e-mail e Google)<br>✅ Catálogo de trilhas e módulos<br>✅ Aulas visuais e quizzes<br>⚠️ Progresso mockado<br>⚠️ Práticas parcialmente liberadas<br>⚠️ 6 aulas placeholder</p> | <p>🔲 Assistente de IA educacional<br>🔲 Simulador financeiro<br>🔲 Dashboard evoluído<br>🔲 Área para professores<br>🔲 Persistência real de progresso<br>🔲 Práticas executáveis ponta a ponta</p> |

## Funcionalidades e Situação Real

| ✅ Implementadas                                                                                                                                                                                | ⚠️ Parciais / Planejadas                                                                                                                                                                                                                                                 |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <p>• Autenticação por e-mail e Google<br>• Aulas visuais (17 + 1 checkpoint)<br>• Quizzes (18 quizzes, 31 questões)<br>• Proteção de rotas<br>• Catálogo de trilhas<br>• Layout responsivo</p> | <p>• Progresso mockado (sem persistência real)<br>• Práticas parcialmente liberadas<br>• 6 aulas placeholder pendentes<br>• Assistente de IA educacional (planejado)<br>• Simulador financeiro (planejado)<br>• Dashboard evoluído e área de professores (planejado)</p> |

## Conteúdo e Práticas

| Aulas e Checkpoint                                                                                                                          | Quizzes e Questões                                                                                                      |
| ------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| <p>17 aulas + 1 checkpoint completos.<br><br>6 aulas placeholder ainda a finalizar.<br><br>Auditoria de código prevista até 28/09/2026.</p> | <p>18 quizzes disponíveis com 31 questões no total.<br><br>Cobertura progressiva dos temas de cada trilha e módulo.</p> |

| Blocos Didáticos                                                                                             | Categorias de Prática                                                                                         |
| ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------- |
| 12 tipos de blocos por aula: objetivos, conceito, exemplos, quiz, glossário, dica, atenção, resumo e outros. | Quatro categorias: Quizzes, Estudos de Caso, Simulações e Desafios. Execução real pendente para próxima fase. |

## Evidências Visuais do Protótipo

As imagens abaixo são capturas reais da interface do protótipo "Aula de Investimentos". Evidenciam o design e a navegação — não comprovam execução integral de funcionalidades, persistência de dados ou conclusão de todas as aulas.

## Limitações e Auditoria

### ⚠️ Limitações Identificadas

* Progresso e estatísticas mockados — sem persistência real por usuário.
* Botão de práticas parcialmente funcional.
* Telas de autenticação exibidas em inglês.
* Seis aulas placeholder, com conteúdo ainda não finalizado.

### 🔍 Status da Auditoria Técnica (até 28/09/2026)

* Execução real das práticas: pendente.
* Fluxos ponta a ponta: ainda a realizar.
* Testes visuais e de regressão: pendentes.
* Código auditado parcialmente — entrega confirmada dentro do escopo do protótipo navegável.

## Inteligência Artificial

* 🔴 Nenhuma integração de IA no código atual.
* 🤖 Assistente educacional planejado para explicações, dúvidas e revisões.
* ⚠️ Restrições: sem recomendação de investimentos, sem operações financeiras, sem promessa de rentabilidade.
* ✅ Benefícios previstos: maior engajamento e aprendizagem personalizada.

## Dados, Ética e Segurança

| Dados e LGPD                                                                                                                                                                                     | Ética e Limites                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p>Dados coletados: e-mail, credencial protegida, login Google, progresso e respostas (parcial/futuro).<br><br>Coleta mínima e proteção conforme a LGPD. Sem compartilhamento com terceiros.</p> | <p>Revisão humana e avisos de caráter estritamente educacional em todo o conteúdo.<br><br>A plataforma não é consultoria financeira nem oferece recomendação de investimentos.</p> |

## Tecnologias e Unidades Curriculares

| IA e Automação                                                                                                                  | No-Code e IA Generativa                                                                                                                                 |
| ------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p>IA generativa como apoio ao desenvolvimento.<br><br>Planejamento de assistente educacional com restrições éticas claras.</p> | <p>Base44 (plataforma no-code), GitBook (documentação), shadcn-ui, lucide-react (a confirmar).<br><br>Prototipagem ágil sem infraestrutura própria.</p> |

| Ecossistemas de Inovação Digital                                                                                                  | Ética e Segurança Digital                                                                                                        |
| --------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| React, Vite, Tailwind CSS. Stack moderna de desenvolvimento front-end, integrada a ecossistema open-source e fintech educacional. | Autenticação por e-mail e Google, proteção de rotas, conformidade com LGPD. Plataforma educacional — sem consultoria financeira. |

## MVP e Roadmap

| Entrega Confirmada                                                                                                                                                                    | Próximos Passos                                                                                                                                                                       |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p>✔ Autenticação (e-mail e Google)<br>✔ Catálogo de trilhas e módulos<br>✔ Aulas visuais e quizzes<br>✔ Proteção de rotas<br>✔ Layout responsivo<br>✔ Progresso mockado (visual)</p> | <p>→ Persistência real de progresso<br>→ Práticas executáveis<br>→ Conclusão das aulas restantes<br>→ Dashboard completo<br>→ Simulador financeiro<br>→ Assistente IA educacional</p> |

## Cronograma e Requisitos Acadêmicos

| RT01       | RT02       | RT03       | RT04       | Bancas        |
| ---------- | ---------- | ---------- | ---------- | ------------- |
| 08/09/2026 | 29/09/2026 | 27/10/2026 | 17/11/2026 | 24/11 e 01/12 |

Entregas: documentação, plano de trabalho, testes e ensaio da banca.

Bancas finais: 24/11/2026 e 01/12/2026.

## Conclusão

O projeto demonstra que é possível estruturar uma plataforma de educação financeira progressiva, acessível e ética. Limitações identificadas serão endereçadas nas próximas fases.

Acesse o protótipo e conheça a Escola de Investimentos Brasil:

[🔗 Investimentos Brasil. smart-wealth-pragmatic-path.base44.app](/broken/pages/cd126fe624189b160a7c8d1872517cdabc12c6e8)

***

## Escola de Investimentos Brasil

**Obrigado!**

Projeto A3 – Exploração Digital e Fundamentos Tecnológicos\
Turma da Manhã – 2º Semestre de 2026

### Acesse o protótipo

[smart-wealth-pragmatic-path.base44.app](/broken/pages/cd126fe624189b160a7c8d1872517cdabc12c6e8)

Escaneie o QR Code ao lado para acessar.
