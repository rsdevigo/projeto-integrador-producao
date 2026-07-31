# Plano de Encontro — Semana 12

**Projeto Integrador – Produção | Curso Superior de Tecnologia em Jogos Digitais**

---

## 1. Identificação

| Campo | Conteúdo |
|---|---|
| **Semana** | 12 de 17 |
| **Milestone** | Vertical Slice |
| **Tipo de encontro** | 🔵 Checkpoint regular — preparação para o Gate da Semana 13 |
| **Duração** | 2h15 |
| **Objetivo do encontro** | Verificar se a build Beta foi estabilizada em uma versão candidata ao Vertical Slice, testando o fluxo completo de jogo e consolidando a lista final de ajustes antes do Gate de fechamento da Semana 13. |

---

## 2. Relação com o Cronograma

Segundo o [CRONOGRAMA.md](https://rsdevigo.github.io/projeto-integrador-producao/#/Cronograma/CRONOGRAMA.md), a Semana 12 abre a Unidade IV — Vertical Slice, dando sequência ao Gate do Beta aprovado (ou redirecionado) na Semana 11. O escopo já está congelado desde aquele Gate: nenhuma funcionalidade nova deve ser adicionada a partir deste ponto. O trabalho desta semana é exclusivamente de estabilização e correção sobre o escopo existente.

Este é um checkpoint de verificação preparatória, não um Gate formal: seu papel é confirmar que a versão candidata roda do início ao fim sem falhas críticas de fluxo, para que a equipe chegue ao Gate da Semana 13 com segurança.

**Entregáveis previstos para esta semana (Cronograma):**
- Versão candidata ao Vertical Slice.

**Gate de Aprovação (Cronograma):** Verificação preparatória para o Gate da Semana 13 — a versão candidata deve rodar do início ao fim sem falhas críticas de fluxo.

**Preparação exigida para a Semana 13:** lista final de ajustes antes do fechamento do Vertical Slice.

---

## 3. Objetivos do Encontro

1. Verificar, por meio de teste conjunto, se a versão candidata roda do início ao fim do recorte jogável sem falhas críticas de fluxo.
2. Confirmar que o escopo permanece congelado desde o Gate do Beta (Semana 11), sem adições não planejadas.
3. Consolidar a lista de defeitos remanescentes, priorizando os que comprometem o fluxo completo de jogo.
4. Avaliar a coerência entre gameplay, identidade visual, áudio e interface na experiência de ponta a ponta.
5. Orientar cada equipe na definição da lista final de ajustes a serem resolvidos antes do Gate de fechamento da Semana 13.

---

## 4. Preparação do Professor

Antes do encontro, revisar:

- Resultado do Gate da Semana 11 (aprovado, aprovado com ressalvas ou não aprovado) e as pendências registradas para cada equipe.
- Registro de acompanhamento das Semanas 10–11, conforme [MANUAL_DO_PROFESSOR.md](https://rsdevigo.github.io/projeto-integrador-producao/#/Manual%20do%20Professor/MANUAL_DO_PROFESSOR.md), Seção 12.
- Recorte do Vertical Slice validado na Semana 2, como referência do escopo congelado.
- Critérios de aprovação do Gate da Semana 13 ([CRONOGRAMA.md](https://rsdevigo.github.io/projeto-integrador-producao/#/Cronograma/CRONOGRAMA.md)), para orientar a equipe sobre o próximo patamar de exigência.
- Lista de riscos remanescentes registrada ao final da Semana 11.

---

## 5. Preparação das Equipes

Cada equipe deve chegar ao encontro com:

- Versão candidata ao Vertical Slice, executável, cobrindo o fluxo completo do recorte jogável do início ao fim.
- Backlog atualizado, mostrando apenas itens de estabilização e correção — sem novas funcionalidades.
- Lista de defeitos conhecidos atualizada, com status de cada item.
- Repositório Git atualizado, com histórico de commits referente à estabilização.
- Registro de riscos atualizado, destacando qualquer risco que ainda ameace o fechamento na Semana 13.
- Percurso de teste definido, cobrindo início, meio e fim do recorte jogável.

---

## 6. Estrutura do Encontro (2h15)

### Abertura (10 min)
Alinhamento sobre o objetivo da semana: consolidar a versão candidata ao Vertical Slice e preparar a equipe para o Gate formal da Semana 13. Reforço de que o escopo permanece congelado.

### Checkpoints por equipe (25 min)
Cada equipe relata o que foi corrigido desde o Gate do Beta e o que ainda está pendente, com base na lista de defeitos consolidada na Semana 11.

### Teste conjunto do fluxo completo (45 min)
Cada equipe conduz um percurso completo pela versão candidata, do início ao fim do recorte jogável, sem interrupções para ajustes. O professor e a equipe registram falhas críticas de fluxo, inconsistências de identidade visual, áudio ou interface.

### Mentorias (30 min)
Sessões individuais por equipe, priorizando a lista final de ajustes com base nos problemas observados no teste conjunto.

### Planejamento (10 min)
Cada equipe define a lista final de ajustes a resolver antes do Gate da Semana 13.

### Encerramento (5 min)
Resumo dos principais pontos de atenção por equipe e reforço dos critérios do Gate da Semana 13.

---

## 7. Perguntas de Mentoria

- A versão candidata roda do início ao fim do recorte jogável sem falhas críticas de fluxo?
- Algum item de escopo foi adicionado ou removido informalmente desde o Gate do Beta?
- Quais defeitos remanescentes têm maior impacto na experiência de ponta a ponta?
- A identidade visual, o áudio e a interface se mantêm coerentes ao longo de todo o percurso, ou há quebras pontuais?
- O que ainda falta para que esta versão seja considerada pronta para o Gate de fechamento da Semana 13?
- Existe algum risco técnico que pode comprometer a estabilidade entre agora e o próximo encontro?

---

## 8. Indicadores de Saúde do Projeto

| Indicador | Status | Observações |
|---|---|---|
| Cronograma | | |
| Escopo | | |
| Build | | |
| Integração | | |
| Documentação | | |
| Comunicação da Equipe | | |
| Riscos | | |

*Nesta semana, o indicador de Build reflete diretamente a proximidade do Gate da Semana 13. Um indicador vermelho em Build ou Integração deve gerar uma lista final de ajustes objetiva e priorizada, conforme [MANUAL_DO_PROFESSOR.md](https://rsdevigo.github.io/projeto-integrador-producao/#/Manual%20do%20Professor/MANUAL_DO_PROFESSOR.md), Seção 10.*

---

## 9. Critérios de Verificação

- [ ] Versão candidata foi testada do início ao fim do recorte jogável, sem interrupções para correções.
- [ ] Nenhuma falha crítica impediu a conclusão do percurso.
- [ ] Escopo presente na build corresponde ao recorte validado na Semana 2, sem adições não planejadas desde o Gate do Beta.
- [ ] Defeitos remanescentes foram listados e priorizados para a semana final antes do Gate.
- [ ] Backlog, repositório Git e registro de riscos estão atualizados.
- [ ] Lista final de ajustes para a Semana 13 foi definida com cada equipe.

---

## 10. Problemas Esperados

- Falhas críticas de fluxo ainda presentes no percurso completo do recorte jogável.
- Escopo divergente do recorte validado, com pequenas adições feitas "de última hora".
- Inconsistências entre gameplay, arte, áudio e interface quando testados em conjunto pela primeira vez.
- Equipe subestima o tempo necessário para os ajustes finais antes do Gate.
- Acúmulo de defeitos menores que, somados, comprometem a experiência de ponta a ponta.

---

## 11. Estratégias de Intervenção

| Problema | Ação recomendada |
|---|---|
| Falhas críticas no percurso completo | Priorizar exclusivamente a correção do fluxo bloqueante antes de qualquer ajuste cosmético na semana final. |
| Escopo divergente do recorte validado | Confrontar com o recorte da Semana 2; remover qualquer adição não planejada antes do Gate. |
| Inconsistências entre áreas (arte, áudio, interface) | Recomendar uma passada de revisão cruzada entre os membros responsáveis por cada área, com checklist simples de coerência. |
| Subestimação do tempo restante | Ajudar a equipe a reduzir a lista de ajustes ao mínimo necessário para o Gate, adiando melhorias não críticas para o Polimento. |
| Acúmulo de defeitos menores | Classificar defeitos por impacto real na experiência; tratar apenas os que comprometem o fluxo ou a legibilidade do jogo. |

---

## 12. Evidências para Avaliação

- Versão candidata testada ao vivo, com percurso completo do recorte jogável.
- Comparativo entre pendências do Gate da Semana 11 e o que foi de fato corrigido.
- Backlog refletindo apenas tarefas de estabilização.
- Histórico de commits no repositório Git referente à estabilização da semana.
- Registro de riscos e de decisões atualizado até esta semana.
- Lista final de ajustes definida para cada equipe, priorizada para a Semana 13.

---

## 13. Encaminhamentos

**Entregar até a Semana 13:**
- Lista final de ajustes resolvida ou reduzida ao mínimo necessário para o Gate.
- Versão candidata estável, sem falhas críticas de fluxo, pronta para validação formal.

**Riscos a monitorar:**
- Defeitos remanescentes que podem não ser resolvidos a tempo do Gate final.
- Tentativa de reabrir escopo já congelado sob o pretexto de "pequenos ajustes".
- Inconsistências entre áreas (arte, áudio, interface) não tratadas a tempo.

**Prioridades da equipe até o próximo encontro:**
- Manter o escopo congelado conforme validado no Gate do Beta.
- Concentrar esforços na estabilidade e na coerência do fluxo completo, não em novas melhorias.
- Preparar a versão final a ser validada no Gate da Semana 13.

---

*Plano de Encontro gerado automaticamente a partir do [CRONOGRAMA.md](https://rsdevigo.github.io/projeto-integrador-producao/#/Cronograma/CRONOGRAMA.md), [COURSE_CONTEXT.md](https://rsdevigo.github.io/projeto-integrador-producao/#/COURSE_CONTEXT.md), [PEDAGOGICAL_RULES.md](https://rsdevigo.github.io/projeto-integrador-producao/#/PEDAGOGICAL_RULES.md), [PLANO_DE_ENSINO.md](https://rsdevigo.github.io/projeto-integrador-producao/#/Plano%20de%20Ensino/PLANO_DE_ENSINO.md), [RUBRICA_DE_AVALIACAO.md](https://rsdevigo.github.io/projeto-integrador-producao/#/Plano%20de%20Ensino/RUBRICA_DE_AVALIACAO.md) e [MANUAL_DO_PROFESSOR.md](https://rsdevigo.github.io/projeto-integrador-producao/#/Manual%20do%20Professor/MANUAL_DO_PROFESSOR.md). Nenhuma informação do Cronograma foi alterada.*
