# Plano de Encontro — Semana 11

**Projeto Integrador – Produção | Curso Superior de Tecnologia em Jogos Digitais**

---

## 1. Identificação

| Campo | Conteúdo |
|---|---|
| **Semana** | 11 de 17 |
| **Milestone** | Beta |
| **Tipo de encontro** | 🔴 GATE — Aprovação do Beta |
| **Duração** | 2h15 |
| **Objetivo do encontro** | Validar formalmente se a build Beta está funcionalmente completa, com escopo congelado, e jogável do início ao fim sem falhas críticas — decidindo se a equipe está apta a avançar para o fechamento do Vertical Slice. |

---

## 2. Relação com o Cronograma

Segundo o `CRONOGRAMA.md`, a Semana 11 encerra a Unidade III — Produção Intermediária e Beta, consolidando o trabalho de estabilização iniciado na Semana 10, quando a equipe verificou a presença de todo o escopo planejado na build, ainda que com defeitos. Esta semana é o momento de confirmar que esses defeitos foram tratados e que o escopo, agora, está congelado.

Este é um encontro de **Gate formal**: a equipe só avança para a Unidade IV (Vertical Slice, Semanas 12–13) se a build Beta atender aos critérios de aprovação definidos no Cronograma. Não se trata de uma verificação preparatória, como na semana anterior, mas da decisão objetiva de avanço de fase.

**Entregáveis previstos para esta semana (Cronograma):**
- Build Beta, funcionalmente completa.

**Gate de Aprovação (Cronograma):** 🔴 GATE — Aprovação do Beta. A equipe só avança para o fechamento do Vertical Slice se o escopo estiver funcionalmente completo e congelado (nenhuma funcionalidade nova é adicionada a partir deste ponto) e a build for jogável do início ao fim sem falhas críticas. Caso o gate não seja aprovado, a semana seguinte prioriza completar o escopo faltante em vez de iniciar a estabilização final.

**Preparação exigida para a Semana 12:** plano de estabilização final do Vertical Slice definido.

---

## 3. Objetivos do Encontro

1. Verificar, por meio de demonstração ao vivo e completa, se a build Beta é jogável do início ao fim sem falhas críticas.
2. Confirmar que o escopo está congelado — nenhuma funcionalidade nova foi adicionada além do que já estava definido no recorte do Vertical Slice.
3. Avaliar se os defeitos consolidados na Semana 10 foram corrigidos, priorizando os que impactam a jogabilidade central.
4. Emitir uma decisão objetiva de Gate: aprovado, aprovado com ressalvas ou não aprovado.
5. Orientar a equipe na definição do plano de estabilização final que conduzirá ao fechamento do Vertical Slice nas Semanas 12 e 13.

---

## 4. Preparação do Professor

Antes do encontro, revisar:

- Plano de estabilização definido ao final da Semana 10, para comparar o que foi planejado com o que foi de fato executado.
- Lista de defeitos conhecidos consolidada na Semana 10, verificando quais itens foram corrigidos.
- Registro de acompanhamento das Semanas 9–10 (progresso, riscos, decisões), conforme `MANUAL_DO_PROFESSOR.md`, Seção 12.
- Recorte do Vertical Slice validado na Semana 2, como referência definitiva do que compõe o escopo congelado.
- Critérios de aprovação do Gate (`CRONOGRAMA.md`), para conduzir a decisão de forma objetiva e consistente entre as equipes.
- Critérios do Gate da Semana 13 (Vertical Slice completo), para já sinalizar à equipe o próximo patamar de exigência.

---

## 5. Preparação das Equipes

Cada equipe deve chegar ao encontro com:

- Build Beta executável, contendo o escopo completo do Vertical Slice, sem funcionalidades adicionais não planejadas.
- Backlog atualizado, mostrando o fechamento dos itens que compunham o plano de estabilização da Semana 10.
- Lista de defeitos conhecidos atualizada, com status de cada item (corrigido, pendente, aceito como risco conhecido).
- Repositório Git atualizado, com histórico de commits referente à estabilização da semana.
- Registro de riscos atualizado, destacando qualquer risco remanescente que possa comprometer o fechamento do Vertical Slice.
- Percurso de demonstração definido pela equipe, cobrindo o fluxo completo do recorte jogável, do início ao fim.

---

## 6. Estrutura do Encontro (2h15)

### Abertura (10 min)
Alinhamento sobre a natureza do encontro: trata-se de um Gate formal de avaliação, não de um checkpoint regular. A decisão de aprovação será registrada objetivamente para cada equipe.

### Demonstração das Builds — verificação de Gate (50 min)
Cada equipe conduz um percurso completo pela build Beta, do início ao fim do recorte jogável, sem interrupções para ajustes. O professor registra falhas críticas, desvios de escopo em relação ao recorte validado na Semana 2 e a estabilidade geral da experiência.

### Checkpoints por equipe (20 min)
Cada equipe apresenta o comparativo entre o plano de estabilização da Semana 10 e o que foi efetivamente corrigido, incluindo justificativas para eventuais itens não resolvidos.

### Mentoria e decisão de Gate (25 min)
Sessões individuais por equipe, nas quais o professor comunica a decisão do Gate (aprovado, aprovado com ressalvas ou não aprovado) e as justifica com base em evidências observadas na demonstração.

### Planejamento (15 min)
Equipes aprovadas iniciam o plano de estabilização final rumo ao fechamento do Vertical Slice (Semanas 12–13). Equipes não aprovadas priorizam, junto ao professor, o que precisa ser corrigido antes de reapresentar.

### Encerramento (5 min)
Registro formal da decisão de Gate de cada equipe e reforço do que será exigido no Gate da Semana 13.

---

## 7. Perguntas de Mentoria

- A build Beta é jogável do início ao fim do recorte definido, sem travamentos críticos?
- O escopo presente na build corresponde exatamente ao recorte validado na Semana 2 — sem adições nem remoções não combinadas?
- Quais defeitos do plano de estabilização da Semana 10 permanecem não corrigidos, e qual o impacto real deles na experiência?
- Existe algum risco que ainda ameaça a estabilidade da build entre agora e o Gate da Semana 13?
- Caso o Gate não seja aprovado hoje, o que precisa mudar de prioridade na equipe até a reavaliação?
- O que a equipe aprendeu no processo de estabilização que pode ser aplicado ao fechamento final do Vertical Slice?

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

*Nesta semana, os indicadores de Build e Escopo determinam diretamente a decisão de Gate. Um indicador vermelho em qualquer um dos dois é incompatível com a aprovação do Gate e deve ser tratado como não aprovação, com plano de correção imediato, conforme `MANUAL_DO_PROFESSOR.md`, Seção 10.*

---

## 9. Critérios de Verificação

- [ ] Build Beta foi demonstrada ao vivo, do início ao fim, sem interrupções para correções.
- [ ] Nenhuma falha crítica impediu a conclusão do percurso jogável.
- [ ] Escopo presente na build corresponde ao recorte do Vertical Slice validado na Semana 2, sem adições não planejadas.
- [ ] Defeitos priorizados no plano de estabilização da Semana 10 foram corrigidos ou tratados como risco aceito e documentado.
- [ ] Backlog, repositório Git e registro de riscos estão atualizados.
- [ ] Decisão de Gate foi comunicada e registrada objetivamente para a equipe.

---

## 10. Problemas Esperados

- Build ainda apresenta falhas críticas que interrompem o percurso jogável.
- Escopo foi alterado informalmente durante a estabilização, divergindo do recorte validado.
- Defeitos priorizados na Semana 10 não foram corrigidos por falta de tempo ou má priorização.
- Equipe pressiona por aprovação do Gate mesmo com pendências relevantes.
- Dificuldade da equipe em aceitar a necessidade de retrabalho quando o Gate não é aprovado.

---

## 11. Estratégias de Intervenção

| Problema | Ação recomendada |
|---|---|
| Falhas críticas no percurso jogável | Não aprovar o Gate; direcionar a semana seguinte exclusivamente para estabilização, sem novo conteúdo. |
| Escopo divergente do recorte validado | Confrontar com o recorte da Semana 2; exigir remoção de qualquer adição não planejada antes de nova avaliação. |
| Defeitos priorizados não corrigidos | Avaliar impacto real na jogabilidade; se crítico, condicionar a aprovação à correção; se secundário, registrar como risco aceito. |
| Pressão por aprovação indevida | Manter a decisão baseada exclusivamente em evidências observadas na demonstração, não em esforço declarado pela equipe. |
| Resistência ao retrabalho | Reforçar que a resposta a um Gate não aprovado é redirecionar prioridades, não acumular carga de trabalho; apoiar a equipe na repriorização. |

---

## 12. Evidências para Avaliação

- Build Beta demonstrada ao vivo, com percurso completo do recorte jogável.
- Comparativo entre o plano de estabilização da Semana 10 e o que foi de fato corrigido.
- Backlog refletindo o estado real de conclusão e congelamento do escopo.
- Histórico de commits no repositório Git referente à estabilização da semana.
- Registro de riscos e de decisões atualizado até esta semana.
- Decisão de Gate registrada, com justificativa baseada em evidências.

---

## 13. Encaminhamentos

**Entregar até a Semana 12:**
- Para equipes aprovadas: início da estabilização final rumo à versão candidata ao Vertical Slice.
- Para equipes não aprovadas: correção das pendências críticas identificadas no Gate, sem adição de novo escopo.

**Riscos a monitorar:**
- Defeitos remanescentes que podem se acumular até o Gate final da Semana 13.
- Tentativa de reabrir escopo já congelado durante a estabilização final.
- Equipes não aprovadas perderem tempo de produção por dificuldade em repriorizar rapidamente.

**Prioridades da equipe até o próximo encontro:**
- Manter o escopo congelado conforme validado neste Gate.
- Priorizar estabilidade e fluxo completo de jogo sobre qualquer ajuste cosmético.
- Preparar a versão candidata ao Vertical Slice a ser testada na Semana 12.

---

*Plano de Encontro gerado automaticamente a partir do `CRONOGRAMA.md`, `COURSE_CONTEXT.md`, `PEDAGOGICAL_RULES.md`, `PLANO_DE_ENSINO.md`, `RUBRICA_DE_AVALIACAO.md` e `MANUAL_DO_PROFESSOR.md`. Nenhuma informação do Cronograma foi alterada.*
