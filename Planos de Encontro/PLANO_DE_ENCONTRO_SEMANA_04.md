# Plano de Encontro — Semana 4

**Projeto Integrador – Produção | Curso Superior de Tecnologia em Jogos Digitais**

---

## 1. Identificação

| Campo | Conteúdo |
|---|---|
| **Semana** | 4 de 17 |
| **Milestone** | Produção Inicial |
| **Tipo de encontro** | 🔵 Checkpoint regular — Início da implementação |
| **Duração** | 2h15 |
| **Objetivo do encontro** | Acompanhar o início da implementação da mecânica principal do jogo e identificar riscos técnicos logo na primeira iteração de produção. |

---

## 2. Relação com o Cronograma

Segundo o `CRONOGRAMA.md`, a Semana 4 abre a Unidade II — Produção Inicial e Alpha — e é a primeira semana em que a equipe efetivamente implementa. Ela só ocorre em condições plenas se o Gate da Semana 3 (Entrada em Produção Inicial) tiver sido atendido; caso contrário, parte deste encontro deve ser redirecionada para concluir a organização pendente (ferramenta de gestão, repositório Git, fluxo de build) antes de cobrar avanço de implementação.

**Entregáveis previstos para esta semana (Cronograma):**
- Build com a mecânica principal implementada, ainda que incompleta.

**Preparação exigida para a Semana 5:** lista de ajustes da mecânica principal registrada no backlog.

---

## 3. Objetivos do Encontro

1. Verificar se as pendências do Gate da Semana 3, quando existirem, foram resolvidas antes de cobrar avanço de implementação.
2. Acompanhar o início da implementação da mecânica principal de cada equipe.
3. Confirmar a existência de uma build executável, mesmo que rudimentar.
4. Identificar riscos técnicos que possam comprometer o ritmo da Produção Inicial.
5. Orientar o registro, no backlog, dos ajustes já identificados na mecânica principal.

---

## 4. Preparação do Professor

Antes do encontro, revisar:

- Resultado do Gate da Semana 3 por equipe (aprovado ou com pendências).
- Recorte do Vertical Slice e backlog priorizado, para confirmar que a mecânica em implementação corresponde ao que foi validado.
- Registro de riscos e decisões acumulado até a Semana 3.
- Diretrizes de controle de escopo e gestão de riscos do `PEDAGOGICAL_RULES.md` (Seções 6 e 7), especialmente para equipes com Gate pendente.
- Critérios de avaliação da Rubrica aplicáveis à fase de implementação inicial.

---

## 5. Preparação das Equipes

Cada equipe deve chegar ao encontro com:

- Build executável contendo a implementação inicial da mecânica principal.
- Repositório Git atualizado com o histórico de commits da semana.
- Ferramenta de gerenciamento de projeto atualizada com o progresso das tarefas de implementação.
- Lista de impedimentos técnicos encontrados durante a implementação.
- Pendências do Gate da Semana 3 resolvidas, se aplicável.

---

## 6. Estrutura do Encontro (2h15)

### Abertura (10 min)
Alinhamento do objetivo da semana: passar da organização para a implementação real. Verificação rápida de pendências do Gate da Semana 3.

### Checkpoints por equipe (35 min)
Cada equipe apresenta:
- estado atual da build;
- o que da mecânica principal já está implementado;
- dificuldades técnicas encontradas.

### Demonstração das Builds (25 min)
Cada equipe executa a build ao vivo, mostrando a mecânica principal em funcionamento, ainda que rudimentar.

### Mentorias (35 min)
Sessões individuais por equipe, focadas em riscos técnicos identificados na implementação e em decisões de design/programação que impactam o restante da Produção Inicial.

### Planejamento (15 min)
Cada equipe registra no backlog os ajustes pendentes da mecânica principal e define as prioridades até a Semana 5.

### Encerramento (5 min)
Síntese dos riscos técnicos identificados e reforço da meta da Semana 5.

*Os tempos podem ser ajustados conforme o número de equipes e a gravidade dos impedimentos técnicos relatados.*

---

## 7. Perguntas de Mentoria

- A mecânica principal implementada corresponde ao que foi definido no recorte do Vertical Slice?
- Existe uma build executável, mesmo que rudimentar? Se não, qual é o impedimento?
- Quais decisões técnicas já tomadas nesta implementação podem gerar retrabalho mais adiante?
- O escopo da mecânica principal está sendo respeitado, ou já há sinais de expansão não planejada?
- A equipe está registrando os ajustes necessários no backlog, ou apenas acumulando problemas informalmente?
- Há algum risco técnico que, se não tratado agora, pode travar a integração prevista para a Semana 6?

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

*Na Semana 4, o indicador de Build refere-se à existência de uma versão executável com a mecânica principal em implementação, ainda que incompleta. O indicador de Integração normalmente ainda é limitado, pois a integração entre áreas só é formalmente esperada a partir da Semana 6.*

---

## 9. Critérios de Verificação

- [ ] Build executável com a mecânica principal em implementação foi apresentada.
- [ ] Mecânica principal é jogável, mesmo que rudimentar.
- [ ] Repositório Git foi atualizado com commits relativos à implementação da semana.
- [ ] Ferramenta de gerenciamento de projeto reflete o progresso real da equipe.
- [ ] Pendências do Gate da Semana 3, se existirem, foram resolvidas ou têm plano claro de resolução.
- [ ] Ajustes identificados na mecânica principal foram registrados no backlog.

---

## 10. Problemas Esperados

- Ausência de build executável até o encontro.
- Mecânica principal implementada de forma isolada, sem testes internos.
- Escopo da mecânica principal maior do que o combinado no recorte do Vertical Slice.
- Impedimentos técnicos não resolvidos, gerando atraso em cadeia.
- Equipe avançando implementação sem atualizar backlog ou repositório.

---

## 11. Estratégias de Intervenção

| Problema | Ação recomendada |
|---|---|
| Ausência de build executável | Priorizar, na mentoria, a identificação do menor obstáculo técnico que impede a geração de uma build, mesmo mínima, antes de discutir novas funcionalidades. |
| Mecânica sem testes internos | Orientar a equipe a testar a mecânica ao vivo durante o encontro, com o professor como primeiro "jogador" externo ao time. |
| Escopo maior que o combinado | Retomar o recorte do Vertical Slice validado na Semana 2 e recomendar a remoção do excedente, reforçando a proteção de escopo. |
| Impedimentos técnicos não resolvidos | Direcionar a mentoria individual para desbloquear o impedimento antes de tratar qualquer outro tópico da equipe. |
| Backlog ou repositório desatualizados | Reservar tempo da mentoria para atualizar backlog e repositório junto com a equipe, reforçando que esses registros são evidência de progresso real. |

---

## 12. Evidências para Avaliação

- Build executável com a mecânica principal em implementação.
- Histórico de commits no repositório Git referente à semana.
- Ferramenta de gerenciamento de projeto atualizada com o progresso das tarefas.
- Backlog atualizado com os ajustes identificados na mecânica principal.
- Registro de riscos técnicos identificados durante o checkpoint.

---

## 13. Mini-Aula (Opcional)

**Tema sugerido:** "Testes internos rápidos como parte do ciclo de implementação" (até 15 min).

Conteúdo sugerido: como estruturar pequenos testes internos de jogabilidade desde a primeira versão da mecânica principal, evitando que problemas de design ou de controle só sejam percebidos em fases avançadas da produção.

Aplicável apenas se a maioria das equipes chegar ao encontro sem ter testado a mecânica principal antes da apresentação — caso contrário, priorizar o tempo de mentoria individual.

---

## 14. Encaminhamentos

**Entregar até a Semana 5:**
- Mecânica principal ajustada a partir dos problemas identificados nesta semana.
- Backlog atualizado com as tarefas de integração de arte e áudio.

**Riscos a monitorar:**
- Equipes sem build executável, que podem comprometer o ritmo da Produção Inicial.
- Sinais de expansão de escopo além do recorte definido para o Vertical Slice.
- Impedimentos técnicos recorrentes que possam se repetir nas próximas semanas.

**Prioridades da equipe até o próximo encontro:**
- Estabilizar a mecânica principal com base nos testes realizados no encontro.
- Manter backlog e repositório atualizados a cada avanço relevante.
- Preparar a integração dos primeiros assets de arte e áudio prevista para a Semana 5.

---

*Plano de Encontro gerado automaticamente a partir do `CRONOGRAMA.md`, `COURSE_CONTEXT.md`, `PEDAGOGICAL_RULES.md`, `PLANO_DE_ENSINO.md`, `RUBRICA_DE_AVALIACAO.md` e `MANUAL_DO_PROFESSOR.md`. Nenhuma informação do Cronograma foi alterada.*
