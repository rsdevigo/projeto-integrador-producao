# Plano de Encontro — Semana 10

**Projeto Integrador – Produção | Curso Superior de Tecnologia em Jogos Digitais**

---

## 1. Identificação

| Campo | Conteúdo |
|---|---|
| **Semana** | 10 de 17 |
| **Milestone** | Produção Intermediária |
| **Tipo de encontro** | 🔵 Checkpoint regular |
| **Duração** | 2h15 |
| **Objetivo do encontro** | Verificar se toda a implementação prevista para o Vertical Slice está presente na build — ainda que com defeitos — e orientar a equipe na definição do plano de estabilização a ser executado antes do Gate do Beta, na Semana 11. |

---

## 2. Relação com o Cronograma

Segundo o [CRONOGRAMA.md](https://rsdevigo.github.io/projeto-integrador-producao/#/Cronograma/CRONOGRAMA.md), a Semana 10 encerra a Unidade III — Produção Intermediária e Beta, sucedendo o checkpoint da Semana 9, no qual a equipe consolidou UX e identidade visual sobre o conteúdo já expandido. Nesta semana, o foco desloca-se para a conclusão de todo o escopo restante: não se trata de polir, mas de garantir que **nada do que foi planejado para o Vertical Slice fique de fora da build**, mesmo que existam defeitos conhecidos.

Esta semana funciona como uma verificação preparatória direta para o Gate da Semana 11 (Beta): o gate formal só é aprovado se o escopo estiver congelado e completo, e essa condição começa a ser construída agora.

**Entregáveis previstos para esta semana (Cronograma):**
- Build com todo o escopo do Vertical Slice implementado.

**Gate de Aprovação (Cronograma):** verificação preparatória para o Gate da Semana 11 — todo o escopo definido para o Vertical Slice está presente na build, ainda que com defeitos.

**Preparação exigida para a Semana 11:** plano de estabilização para a semana de Beta definido.

---

## 3. Objetivos do Encontro

1. Verificar, por meio de demonstração ao vivo, se todas as funcionalidades previstas para o recorte do Vertical Slice estão presentes na build, mesmo que com defeitos.
2. Identificar lacunas de escopo ainda não implementadas e avaliar o risco real de não fechá-las a tempo do Gate da Semana 11.
3. Consolidar a lista de defeitos conhecidos (herdada da Semana 9) com os novos problemas identificados nesta etapa final de implementação.
4. Orientar a equipe na elaboração do plano de estabilização que será executado na semana do Beta.
5. Reforçar o congelamento de escopo: nenhuma funcionalidade nova deve ser iniciada a partir deste ponto.

---

## 4. Preparação do Professor

Antes do encontro, revisar:

- Lista de defeitos conhecidos priorizada, entregue como preparação ao final da Semana 9.
- Registro de acompanhamento das Semanas 8–9 (progresso, riscos, decisões), conforme [MANUAL_DO_PROFESSOR.md](https://rsdevigo.github.io/projeto-integrador-producao/#/Manual%20do%20Professor/MANUAL_DO_PROFESSOR.md), Seção 12.
- Recorte do Vertical Slice validado na Semana 2, para conferência item a item do escopo presente na build.
- Registro de riscos acumulado, com atenção a qualquer funcionalidade que já tenha sido sinalizada como em risco de não ser concluída.
- Critério de aprovação do Gate da Semana 11 ([CRONOGRAMA.md](https://rsdevigo.github.io/projeto-integrador-producao/#/Cronograma/CRONOGRAMA.md)), para antecipar à equipe o que será exigido no próximo encontro.

---

## 5. Preparação das Equipes

Cada equipe deve chegar ao encontro com:

- Build executável contendo, no mínimo, uma versão funcional de todas as funcionalidades previstas para o recorte do Vertical Slice.
- Backlog atualizado, mostrando claramente quais itens do escopo já foram concluídos e quais ainda restam.
- Lista de defeitos conhecidos atualizada, incluindo os problemas identificados durante a implementação das últimas funcionalidades.
- Repositório Git atualizado com o histórico de commits da semana.
- Registro de riscos atualizado, com destaque para qualquer item de escopo em risco de não ser entregue.
- Um levantamento preliminar do que será necessário para estabilizar a build até o Gate da Semana 11.

---

## 6. Estrutura do Encontro (2h15)

### Abertura (10 min)
Alinhamento do foco da semana: fechar todo o escopo restante do Vertical Slice, sem introduzir novas funcionalidades além do já planejado.

### Checkpoints por equipe (40 min)
Cada equipe apresenta o que foi concluído desde a Semana 9, confrontando a implementação atual item a item com o recorte do Vertical Slice validado na Semana 2. Identificam-se lacunas remanescentes.

### Demonstração das Builds — verificação de completude de escopo (35 min)
Percurso completo pela build, verificando presença (não qualidade) de cada funcionalidade prevista. O professor registra o que está ausente, o que está presente mas quebrado, e o que está presente e funcional.

### Mentoria (30 min)
Sessões individuais focadas em: equipes com lacunas de escopo definem como fechá-las até o Gate; equipes com escopo completo começam a estruturar o plano de estabilização.

### Planejamento (15 min)
Cada equipe redige o plano de estabilização para a semana de Beta, priorizando os defeitos consolidados por impacto na jogabilidade.

### Encerramento (5 min)
Reforço do congelamento de escopo e do que será avaliado no Gate da Semana 11.

---

## 7. Perguntas de Mentoria

- Todas as funcionalidades definidas no recorte do Vertical Slice estão presentes na build, mesmo que com defeitos?
- Existe algum item de escopo que a equipe já sabe que não vai conseguir implementar a tempo? O que fazer com ele?
- A lista de defeitos conhecidos reflete o estado real da build ou está desatualizada?
- Qual defeito, se não corrigido, impede a build de ser jogada do início ao fim?
- A equipe está tentada a adicionar algo além do escopo já validado? Por quê?
- O plano de estabilização para a próxima semana é realista dentro de 2h15 de encontro mais o tempo de trabalho fora da sala?

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

*Nesta semana, o indicador de Escopo é o mais crítico: a pergunta central é se tudo o que foi prometido está presente na build. Um indicador vermelho em Escopo nesta etapa é um sinal de alerta direto para o Gate da Semana 11 e deve gerar intervenção imediata, conforme [MANUAL_DO_PROFESSOR.md](https://rsdevigo.github.io/projeto-integrador-producao/#/Manual%20do%20Professor/MANUAL_DO_PROFESSOR.md), Seção 10.*

---

## 9. Critérios de Verificação

- [ ] Build foi demonstrada ao vivo com percurso completo pelo recorte do Vertical Slice.
- [ ] Todas as funcionalidades previstas no recorte validado estão presentes na build, mesmo com defeitos.
- [ ] Lacunas de escopo remanescentes, se houver, foram identificadas e possuem plano de fechamento.
- [ ] Lista de defeitos conhecidos foi consolidada e priorizada por impacto.
- [ ] Backlog e repositório Git estão atualizados com o progresso da semana.
- [ ] Plano de estabilização para a semana de Beta foi definido.

---

## 10. Problemas Esperados

- Funcionalidades do escopo original ainda não implementadas às vésperas do Gate do Beta.
- Lista de defeitos subestimada, sem refletir problemas reais da build.
- Equipe tentada a adicionar funcionalidades não planejadas para "aproveitar o embalo" da produção.
- Build instável ao ponto de dificultar a própria verificação de completude do escopo.
- Plano de estabilização vago, sem priorização clara dos defeitos mais críticos.

---

## 11. Estratégias de Intervenção

| Problema | Ação recomendada |
|---|---|
| Funcionalidades do escopo ainda não implementadas | Avaliar com a equipe se cabe no tempo restante; se não couber, recomendar remoção ou simplificação drástica do item, nunca aumento de carga de trabalho. |
| Lista de defeitos subestimada | Repetir o percurso completo pela build durante o encontro, registrando cada problema encontrado ao vivo. |
| Tentativa de ampliar escopo fora do planejado | Retomar o recorte do Vertical Slice validado na Semana 2; reforçar que o momento é de fechamento, não de expansão. |
| Build instável dificultando verificação | Tratar estabilidade básica como pré-requisito; priorizar correções mínimas antes de continuar a checagem de escopo. |
| Plano de estabilização vago | Exigir lista objetiva de defeitos priorizados por impacto na jogabilidade, com responsável e prazo definidos até o Gate da Semana 11. |

---

## 12. Evidências para Avaliação

- Build demonstrada ao vivo, com percurso completo pelo recorte do Vertical Slice.
- Backlog refletindo o estado real de conclusão do escopo.
- Lista de defeitos conhecidos, consolidada e priorizada.
- Histórico de commits no repositório Git referente à semana.
- Plano de estabilização definido para a semana de Beta.
- Registro de riscos e de decisões atualizado até esta semana.

---

## 13. Encaminhamentos

**Entregar até a Semana 11:**
- Build Beta, com escopo funcionalmente completo e congelado.
- Plano de estabilização executado, priorizando os defeitos de maior impacto.

**Riscos a monitorar:**
- Funcionalidades de escopo não concluídas a tempo do Gate do Beta.
- Volume de defeitos conhecidos maior do que a equipe consegue corrigir em uma semana.
- Pressão para adicionar escopo novo às vésperas do congelamento exigido pelo Gate.

**Prioridades da equipe até o próximo encontro:**
- Fechar qualquer lacuna remanescente de escopo identificada no encontro.
- Executar o plano de estabilização, priorizando defeitos que impedem o jogo de ser jogado do início ao fim.
- Congelar o escopo: nenhuma funcionalidade nova deve ser iniciada a partir de agora.

---

*Plano de Encontro gerado automaticamente a partir do [CRONOGRAMA.md](https://rsdevigo.github.io/projeto-integrador-producao/#/Cronograma/CRONOGRAMA.md), [COURSE_CONTEXT.md](https://rsdevigo.github.io/projeto-integrador-producao/#/COURSE_CONTEXT.md), [PEDAGOGICAL_RULES.md](https://rsdevigo.github.io/projeto-integrador-producao/#/PEDAGOGICAL_RULES.md), [PLANO_DE_ENSINO.md](https://rsdevigo.github.io/projeto-integrador-producao/#/Plano%20de%20Ensino/PLANO_DE_ENSINO.md), [RUBRICA_DE_AVALIACAO.md](https://rsdevigo.github.io/projeto-integrador-producao/#/Plano%20de%20Ensino/RUBRICA_DE_AVALIACAO.md) e [MANUAL_DO_PROFESSOR.md](https://rsdevigo.github.io/projeto-integrador-producao/#/Manual%20do%20Professor/MANUAL_DO_PROFESSOR.md). Nenhuma informação do Cronograma foi alterada.*
