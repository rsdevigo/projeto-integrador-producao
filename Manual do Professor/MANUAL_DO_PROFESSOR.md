# Manual do Professor — Projeto Integrador – Produção

> Guia operacional de consulta durante o semestre. Alinhado ao `COURSE_CONTEXT.md`, ao `PEDAGOGICAL_RULES.md`, ao Plano de Ensino, ao Cronograma e à Rubrica de Avaliação. Permite que qualquer professor conduza a disciplina com consistência, mesmo sem ter acompanhado a turma na Pré-Produção.

---

## 1. Apresentação

**Projeto Integrador – Produção** conduz a execução de um projeto de jogo digital já planejado na disciplina de Pré-Produção. A disciplina tem natureza prática: o aprendizado ocorre pela produção do jogo, não por aulas expositivas.

- O professor atua como mentor, producer, facilitador e avaliador contínuo — nunca como transmissor de conteúdo.
- As equipes funcionam como pequenos estúdios de desenvolvimento, responsáveis pelo próprio projeto de ponta a ponta.
- O objetivo do semestre é a entrega de um **Vertical Slice** — não de um jogo completo.

---

## 2. Objetivos da Disciplina

**Objetivo geral:** conduzir a execução, por equipes organizadas como pequenos estúdios, de um Vertical Slice jogável, estável e coerente com o projeto planejado na Pré-Produção.

**Competências esperadas:** produção de jogos em equipe; gestão de projeto; colaboração interdisciplinar; comunicação profissional; documentação; controle de escopo; resolução de problemas reais; desenvolvimento iterativo; apresentação de projetos.

**Resultado esperado ao final do semestre:** cada equipe entrega um Vertical Slice completo em funcionalidade (gameplay, identidade visual, fluxo completo, áudio e interface consistentes), um pitch de apresentação e um postmortem crítico do processo.

---

## 3. Papel do Professor

O professor atua simultaneamente como:

| Papel | Na prática, significa... |
|---|---|
| Mentor | Orientar decisões técnicas e de design sem tomá-las pela equipe. |
| Producer | Acompanhar a saúde geral do projeto e sinalizar riscos de produção. |
| Facilitador | Criar condições para que a equipe avance com autonomia. |
| Avaliador | Registrar evidências de progresso ao longo do semestre, não apenas no final. |
| Orientador | Fazer perguntas que ajudem a equipe a encontrar a própria solução. |

**Regra central:** o professor não desenvolve o projeto pelos estudantes. Se uma equipe traz um problema técnico ou de design, a resposta padrão é uma pergunta orientadora, não uma solução pronta.

---

## 4. Papel das Equipes

Cada equipe é responsável por:

- planejamento do próprio trabalho e das entregas;
- execução das tarefas do backlog;
- organização interna de papéis;
- comunicação entre membros e com o professor;
- documentação contínua do projeto;
- testes e validação de qualidade;
- apresentação de progresso e do resultado final.

O professor acompanha e orienta; a responsabilidade pelo projeto — incluindo suas falhas — é da equipe.

---

## 5. Organização do Semestre — Resumo dos Milestones

| Milestone | Semanas | Objetivo | Entregáveis Esperados | Principais Riscos | Critério para Avançar |
|---|---|---|---|---|---|
| Kickoff | 1 | Reativar o projeto e alinhar a equipe. | GDD revisado; papéis definidos. | Equipe desalinhada sobre o escopo herdado. | Escopo compreendido por todos. |
| Planejamento da Produção | 2–3 | Transformar o planejamento em um plano executável. | Backlog priorizado; ferramenta de gestão e repositório configurados. | Backlog genérico ou não priorizado. | Backlog priorizado e ferramentas em uso (**Gate — Semana 3**). |
| Produção Inicial | 4–6 | Implementar e integrar a mecânica principal. | Build com mecânica principal integrada. | Mecânica principal instável ou isolada. | Build estável com elementos integrados. |
| Alpha | 7 | Entregar o núcleo de gameplay funcional. | Build Alpha jogável do início ao fim. | Loop principal incompleto. | Loop principal integrado e jogável (**Gate — Semana 7**). |
| Produção Intermediária | 8–10 | Expandir conteúdo, UX e identidade visual. | Build com escopo do Vertical Slice completo. | Escopo cresce além do combinado. | Escopo do Vertical Slice implementado. |
| Beta | 11 | Congelar escopo e estabilizar. | Build Beta funcionalmente completa. | Escopo ainda não congelado. | Escopo congelado, build sem falhas críticas (**Gate — Semana 11**). |
| Vertical Slice | 12–13 | Fechar a versão final do recorte. | Vertical Slice fechado e estável. | Instabilidade residual não resolvida. | VS completo em funcionalidade (**Gate — Semana 13**). |
| Polimento | 14–15 | Elevar qualidade percebida sem reabrir escopo. | Build final de demonstração. | Polimento usado para compensar atraso de implementação. | Build de demonstração estável. |
| Pitch Final | 16 | Apresentar o projeto profissionalmente. | Pitch ensaiado; documentação final. | Ensaio malfeito ou build instável no dia. | Ensaio aprovado (**Gate — Semana 16**). |
| Encerramento e Postmortem | 17 | Refletir sobre o processo. | Postmortem concluído. | Postmortem genérico, sem reflexão real. | Postmortem concreto e específico (**Gate — Semana 17**). |

Consulte o `CRONOGRAMA.md` para o detalhamento semana a semana, incluindo atividades e checkpoints específicos.

---

## 6. Estrutura Recomendada dos Encontros (2h15)

| Etapa | Duração sugerida | Propósito |
|---|---|---|
| Abertura e alinhamento | 10 min | Retomar o combinado da semana anterior e o foco do dia. |
| Checkpoint das equipes | 40–50 min | Reunião rápida com cada equipe (ver Seção 7). |
| Demonstração das builds | 20–30 min | Ver o jogo rodando, não apenas ouvir relatos. |
| Revisão dos entregáveis | 15 min | Confirmar o que foi de fato produzido contra o planejado. |
| Mentoria | 20–30 min | Aprofundar decisões técnicas, de design ou de processo com equipes que precisam de mais suporte. |
| Planejamento da próxima semana | 15 min | Cada equipe sai com uma meta clara para o próximo encontro. |
| Encerramento | 5–10 min | Sintetizar riscos e combinados gerais da turma. |

Ajuste o tempo de cada etapa conforme o número de equipes e o momento do semestre — em semanas de Gate (3, 7, 11, 13, 16, 17), reserve mais tempo para demonstração e validação e menos para mentoria aberta.

---

## 7. Condução dos Checkpoints

Cada checkpoint deve ser objetivo — o objetivo não é uma conversa aberta, mas obter respostas claras. Perguntas orientadoras recomendadas:

1. O que foi concluído desde o último encontro?
2. O que mudou desde o último encontro?
3. Quais são os principais riscos no momento?
4. O cronograma continua viável?
5. O escopo permanece adequado ao tempo restante?
6. Existe alguma dependência bloqueando o projeto?
7. Qual é a meta até o próximo encontro?

Peça sempre para **ver a build rodando** — relatos verbais de progresso não substituem a demonstração.

---

## 8. Feedback

O feedback deve ser:

- **específico** — referenciar a build, o documento ou a decisão observada, não impressões gerais;
- **respeitoso** — dirigido ao trabalho, nunca à pessoa;
- **baseado em evidências** — o que foi visto na build, no repositório ou na documentação;
- **orientado para ações** — deixar claro o que fazer até o próximo checkpoint.

**Equilíbrio:** comece reconhecendo um avanço real e específico, em seguida aponte o problema mais relevante (evite listar todos os problemas de uma vez) e termine com uma ação concreta para a próxima semana. Isso mantém a equipe motivada sem esconder os riscos.

---

## 9. Uso da Rubrica

A Rubrica de Avaliação (`RUBRICA_DE_AVALIACAO.md`) não deve ser aplicada apenas ao final do semestre. Recomendações:

- Após cada checkpoint, registre uma anotação curta por equipe associada ao critério da rubrica mais relevante naquele momento (ex.: "Gestão da Produção — backlog desatualizado desde a Semana 5").
- Use os critérios de **Gestão da Produção** e **Evolução do Projeto** desde as primeiras semanas — eles não dependem da existência de um Vertical Slice pronto.
- Priorize evidências verificáveis: build rodando, repositório, ferramenta de gestão, documentação — não impressões subjetivas do andamento.
- Ao chegar na avaliação final, os registros acumulados evitam que a nota dependa exclusivamente da apresentação do último dia.
- Use a rubrica também como roteiro do próprio feedback: ao apontar um problema, situe-o no critério e no nível de desempenho correspondente, para que a equipe entenda exatamente a distância até o próximo nível.

---

## 10. Gestão do Escopo

**Sinais de que uma equipe está assumindo mais escopo do que consegue entregar:**

- o backlog cresce em vez de diminuir conforme o semestre avança;
- a equipe fala em "funcionalidades futuras" com frequência maior do que em "o que falta terminar";
- builds sucessivas mostram features novas, mas as anteriores continuam incompletas;
- a equipe evita cortar qualquer ideia do GDD original.

**Estratégias de intervenção:**

- **Reduzir funcionalidades:** pedir para a equipe classificar o backlog em "essencial ao Vertical Slice" e "desejável" — e cortar o desejável sem culpa.
- **Priorizar o essencial:** reforçar que o Vertical Slice avalia profundidade, não abrangência (ver `COURSE_CONTEXT.md`, Seção 9).
- **Proteger o Vertical Slice:** em caso de conflito entre qualidade e quantidade, a rubrica já prioriza qualidade — deixe isso explícito para a equipe.
- **Evitar retrabalho:** desencorajar reescrever sistemas já funcionais para "melhorá-los" quando o essencial do escopo ainda não está pronto.

A resposta padrão a um projeto atrasado é sempre **reduzir escopo**, nunca aumentar a carga de trabalho da equipe.

---

## 11. Situações Comuns e Como Agir

| Situação | Sinais de Alerta | Possíveis Causas | Estratégia de Intervenção |
|---|---|---|---|
| Equipe atrasada | Metas não cumpridas em checkpoints consecutivos. | Escopo excessivo; falta de priorização; problemas técnicos não resolvidos. | Revisar backlog junto à equipe; cortar escopo não essencial; verificar se há um impedimento técnico específico travando o avanço. |
| Conflitos internos | Comunicação truncada; membros falando por cima uns dos outros; tarefas não distribuídas. | Papéis mal definidos; sobrecarga desigual; falta de combinados de comunicação. | Mediar uma conversa objetiva sobre papéis e expectativas; sugerir rotina de comunicação (ex.: check-in diário curto). |
| Excesso de escopo | Backlog crescente; funcionalidades incompletas se acumulando. | Ambição além do tempo disponível; dificuldade em abrir mão de ideias do GDD. | Aplicar a estratégia da Seção 10: classificar e cortar o não essencial. |
| Documentação desatualizada | GDD não reflete a build atual; registro de decisões parado há semanas. | Documentação tratada como tarefa de última hora. | Reforçar que a rubrica avalia aderência entre documentação e projeto real; pedir atualização pontual no próprio checkpoint. |
| Projeto sem builds jogáveis | Só há relatos verbais de progresso, sem demonstração. | Integração nunca foi priorizada; trabalho fragmentado entre membros. | Exigir build executável já no próximo encontro, mesmo que mínima; tratar como risco crítico de produção. |
| Problemas de integração | Sistemas funcionam isoladamente, mas quebram quando combinados. | Falta de testes de integração; pouca comunicação entre quem trabalha em partes diferentes. | Recomendar builds mais frequentes e menores; reforçar testes de integração antes de builds de checkpoint. |
| Ausência de planejamento | Equipe não sabe responder "qual é a meta desta semana". | Backlog inexistente ou não utilizado na prática. | Retomar a Semana 2–3 do Cronograma com a equipe: reconstruir backlog priorizado antes de seguir adiante. |
| Dificuldades técnicas persistentes | Mesmo problema aparece em checkpoints sucessivos sem solução. | Lacuna de conhecimento técnico não resolvida sozinha pela equipe. | Orientar (não resolver) com perguntas direcionadas; se necessário, indicar recursos externos ou colegas com experiência na área. |
| Equipe que termina antes do previsto | Vertical Slice pronto com folga de tempo. | Escopo conservador; boa execução. | Direcionar o tempo extra para polimento adicional, testes com jogadores externos ou aprofundamento da documentação — nunca para expandir o escopo já congelado. |

---

## 12. Acompanhamento das Equipes

Mantenha, por equipe, um registro curto e objetivo após cada encontro, contendo:

- **Progresso:** o que mudou na build desde o último checkpoint.
- **Riscos:** riscos identificados e se aumentaram, diminuíram ou seguem os mesmos.
- **Decisões importantes:** decisões de design ou produção tomadas pela equipe.
- **Mudanças de escopo:** o que entrou ou saiu do backlog e por quê.
- **Utilização do feedback:** se o feedback do checkpoint anterior foi incorporado.

Prefira registros de 3 a 5 linhas por equipe a relatórios longos — o objetivo é consultar rapidamente antes do próximo encontro, não produzir documentação extensa.

---

## 13. Preparação para a Avaliação Final

Antes da Semana 16 (Pitch Final), organize:

- **Demonstrações dos projetos:** defina ordem de apresentação, tempo por equipe e formato (presencial, com projeção da build).
- **Pitch Final:** confirme que cada equipe ensaiou dentro do tempo previsto (ver Cronograma, Semana 15–16).
- **Avaliação do Vertical Slice:** tenha a Rubrica em mãos durante a demonstração, avaliando ao vivo os critérios de Vertical Slice e Qualidade Técnica.
- **Aplicação da rubrica:** reúna os registros de acompanhamento (Seção 12) para compor os critérios de Gestão da Produção e Evolução do Projeto, que não dependem apenas do dia da apresentação.
- **Coleta da documentação:** confirme que GDD, backlog e registros estão acessíveis e atualizados antes do dia da apresentação.
- **Avaliação do Postmortem:** reserve tempo específico, na Semana 17, para leitura e discussão do postmortem de cada equipe.

---

## 14. Encerramento da Disciplina

Na Semana 17, conduza o fechamento do semestre com:

- **Discussão coletiva dos projetos:** um momento em que as equipes comentam brevemente os projetos umas das outras — não apenas apresentam o próprio.
- **Compartilhamento de aprendizados:** peça que cada equipe compartilhe uma lição aprendida que outras equipes possam aproveitar.
- **Valorização dos resultados alcançados:** reconheça publicamente as entregas concretas de cada equipe, independentemente do tamanho do projeto.
- **Reflexão sobre o processo:** direcione a conversa final para o processo de produção em si — gestão, comunicação, decisões — e não apenas para o produto entregue, reforçando a filosofia da disciplina de valorizar processo e produto.

---

## 15. Checklists

### Antes de cada encontro

- [ ] Revisar as metas combinadas com cada equipe no encontro anterior.
- [ ] Verificar se há builds novas disponíveis para revisão prévia.
- [ ] Consultar os registros de acompanhamento (Seção 12) de cada equipe.
- [ ] Identificar quais equipes exigem maior atenção neste encontro.
- [ ] Verificar em qual milestone/Gate do Cronograma a turma se encontra.

### Durante o encontro

- [ ] Passar por todas as equipes, sem exceção.
- [ ] Pedir demonstração da build em execução, não apenas relato verbal.
- [ ] Registrar observações objetivas durante os checkpoints.
- [ ] Validar entregáveis previstos para a semana no Cronograma.
- [ ] Fornecer feedback específico, respeitoso e orientado a ações.
- [ ] Confirmar a meta de cada equipe para o próximo encontro.

### Após o encontro

- [ ] Registrar pendências identificadas por equipe.
- [ ] Atualizar o acompanhamento (progresso, riscos, decisões, mudanças de escopo).
- [ ] Planejar intervenções específicas para equipes em risco.
- [ ] Revisar riscos gerais da turma antes do próximo encontro.

### Antes da apresentação final

Para cada equipe, verificar se possui:

- [ ] Vertical Slice funcional e testado.
- [ ] Documentação organizada e atualizada (GDD, backlog, registros).
- [ ] Pitch preparado e ensaiado dentro do tempo.
- [ ] Build testada em condições semelhantes às do dia da apresentação.
- [ ] Materiais de apoio prontos (slides, vídeo de backup, se aplicável).
- [ ] Postmortem concluído.

---

*Manual do Professor — Projeto Integrador – Produção. Documento de consulta permanente, alinhado ao `COURSE_CONTEXT.md`, `PEDAGOGICAL_RULES.md`, Plano de Ensino, Cronograma e Rubrica de Avaliação.*
