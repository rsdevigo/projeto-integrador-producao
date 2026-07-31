# Game Design Document (GDD) Evolutivo — [Nome do Jogo]

> **O que é este documento**
> Este é um GDD vivo ("Living GDD"). Ele não é escrito uma única vez: é atualizado a cada checkpoint semanal, acompanhando as decisões reais de produção. Um GDD desatualizado é tão problemático quanto a ausência de um GDD.
>
> **Como usar este template**
> - Preencha todas as seções, mesmo que de forma resumida, já no Kickoff.
> - Revise este documento antes de cada encontro presencial.
> - Toda mudança relevante deve ser registrada em "Mudanças Recentes" e no "Histórico de Revisões".
> - Textos em itálico entre colchetes são orientações de preenchimento e devem ser removidos ou substituídos pelo conteúdo real da equipe.

---

## 1. Informações Gerais do Projeto

*Preencher com os dados de identificação do projeto e da equipe. Esta seção muda pouco ao longo do semestre.*

| Campo | Descrição |
|---|---|
| Nome do jogo | *[Título de trabalho ou final]* |
| Equipe | *[Nome da equipe/estúdio fictício]* |
| Integrantes e funções | *[Nome — função na equipe]* |
| Gênero | *[Ex.: plataforma 2D, puzzle, roguelike]* |
| Versão do documento | *[v0.1, v0.2...]* |
| Data da última atualização | *[dd/mm/aaaa]* |
| Responsável pela atualização | *[Nome]* |

---

## 2. Elevator Pitch

*Descreva o jogo em no máximo 3 a 4 frases, como se fosse apresentado a um investidor ou publisher em 30 segundos. Deve comunicar gênero, fantasia central e diferencial. Evite detalhes técnicos aqui.*

> *[Escreva o pitch]*

---

## 3. Visão Geral

*Expanda o pitch com uma descrição mais completa do jogo: contexto, tema, tom, referências de mercado (jogos similares) e o que torna a experiência única. Esta seção serve como orientação geral para qualquer pessoa que entre no projeto.*

- **Tema/fantasia central:** *[...]*
- **Tom/atmosfera:** *[...]*
- **Referências (jogos similares):** *[...]*
- **Diferencial competitivo:** *[o que este jogo tem que os outros não têm]*

---

## 4. Público-alvo

*Defina para quem o jogo é feito. Isso orienta decisões de dificuldade, tema, interface e comunicação visual.*

- **Faixa etária:** *[...]*
- **Perfil de jogador:** *[casual, hardcore, ambos]*
- **Classificação indicativa pretendida:** *[...]*
- **Contexto de consumo:** *[sessão curta, maratona, mobile em trânsito etc.]*

---

## 5. Plataformas

*Liste as plataformas de lançamento previstas para o Vertical Slice e, se aplicável, para uma futura versão completa. Justifique a escolha considerando a capacidade real da equipe.*

| Plataforma | Prioridade | Observações |
|---|---|---|
| *[PC / Web / Mobile / Console]* | *[Alta/Média/Baixa]* | *[requisitos, engine, restrições]* |

---

## 6. Core Gameplay Loop

*Descreva o ciclo de ações que o jogador repete continuamente durante o jogo (o "loop" minuto a minuto). Use um diagrama simples ou lista sequencial. Esta é uma das seções mais importantes do documento — o Vertical Slice deve comprovar que este loop é divertido.*

**Loop principal:**
1. *[Ação 1]*
2. *[Ação 2]*
3. *[Ação 3]*
4. *[Retorno ao passo 1 ou progressão]*

**O que torna este loop divertido:** *[justifique brevemente]*

---

## 7. Mecânicas Principais

*Detalhe cada mecânica de gameplay individualmente. Adicione uma subseção por mecânica. Priorize as mecânicas que efetivamente estarão no Vertical Slice — não descreva mecânicas fora de escopo.*

### 7.1 [Nome da mecânica]
- **Descrição:** *[como funciona]*
- **Inputs do jogador:** *[teclas, botões, gestos]*
- **Regras/condições:** *[...]*
- **Status:** *[Planejada / Em desenvolvimento / Implementada / Testada]*

*(Repita a subseção para cada mecânica adicional)*

---

## 8. Progressão

*Explique como a experiência do jogador evolui ao longo do tempo: dificuldade, desbloqueios, narrativa, upgrades, curva de aprendizado. Indique claramente o que faz parte do recorte do Vertical Slice.*

- **Curva de dificuldade:** *[...]*
- **Sistema de progressão (se houver):** *[pontos, níveis, upgrades, itens]*
- **Estrutura narrativa (se houver):** *[linear, ramificada, ausente]*
- **Recorte do Vertical Slice:** *[qual trecho da progressão será demonstrado]*

---

## 9. Interface

*Descreva a UI/UX do jogo: HUD, menus, telas de transição, feedback visual e sonoro ao jogador. Anexe wireframes ou referências visuais quando disponíveis.*

- **Elementos de HUD:** *[...]*
- **Menus necessários:** *[...]*
- **Fluxo de telas:** *[diagrama ou lista de telas e transições]*
- **Referências visuais:** *[links ou imagens anexadas]*

---

## 10. Direção de Arte

*Defina a identidade visual do jogo: estilo, paleta de cores, referências, pipeline de produção de assets visuais. A coerência visual é um critério de qualidade do Vertical Slice.*

- **Estilo visual:** *[pixel art, low poly, cartoon, realista...]*
- **Paleta de cores:** *[...]*
- **Referências visuais:** *[moodboard, links]*
- **Ferramentas de produção:** *[...]*

---

## 11. Direção de Áudio

*Defina a identidade sonora: trilha, efeitos sonoros, referências. Indique o que é essencial para o Vertical Slice e o que pode ser placeholder.*

- **Estilo musical/sonoro:** *[...]*
- **Referências de áudio:** *[...]*
- **Efeitos sonoros necessários:** *[lista mínima para o Vertical Slice]*
- **Ferramentas/fontes:** *[bibliotecas, softwares, assets de terceiros]*

---

## 12. Arquitetura Técnica

*Descreva as decisões técnicas do projeto: engine/framework, linguagem, principais sistemas de código, dependências externas. Não é necessário detalhar implementação, apenas as decisões estruturais relevantes para a produção.*

- **Engine/Framework:** *[...]*
- **Linguagem(ns):** *[...]*
- **Principais sistemas:** *[ex.: sistema de input, save/load, IA, física]*
- **Dependências/plugins de terceiros:** *[...]*
- **Riscos técnicos conhecidos:** *[...]*

---

## 13. Estrutura de Cenas

*Liste as cenas/fases/telas do jogo e como se conectam. Indique quais fazem parte do Vertical Slice.*

| Cena | Descrição | Faz parte do Vertical Slice? |
|---|---|---|
| *[Ex.: Menu Principal]* | *[...]* | *[Sim/Não]* |
| *[Ex.: Fase 1]* | *[...]* | *[Sim/Não]* |

---

## 14. Organização dos Assets

*Descreva como os assets (arte, áudio, código, documentos) estão organizados no repositório/projeto. Isso facilita a colaboração e a avaliação da organização da equipe.*

- **Estrutura de pastas:** *[...]*
- **Convenção de nomenclatura:** *[...]*
- **Local do repositório:** *[link do Git]*
- **Política de versionamento de assets:** *[...]*

---

## 15. Cronograma Resumido

*Sincronize esta seção com o cronograma oficial da disciplina. Liste os milestones e o status atual. Não duplique o cronograma completo aqui — apenas um resumo de referência rápida.*

| Milestone | Semana | Entrega esperada | Status |
|---|---|---|---|
| Kickoff | *[...]* | *[...]* | *[Concluído/Em andamento/Pendente]* |
| Alpha | *[...]* | *[...]* | *[...]* |
| Beta | *[...]* | *[...]* | *[...]* |
| Apresentação Final | *[...]* | *[...]* | *[...]* |

---

## 16. Mudanças Recentes

*Registre, a cada checkpoint, o que mudou no design desde a última revisão. Serve como resumo rápido para o professor/mentor no início de cada encontro. Manter apenas as últimas 3-5 mudanças; mudanças mais antigas migram para o Histórico de Revisões.*

- **[dd/mm/aaaa]** — *[o que mudou e por quê]*

---

## 17. Pendências

*Liste decisões em aberto, riscos identificados e itens que dependem de definição. Útil para orientar a mentoria e priorizar a próxima sessão de trabalho.*

| Pendência | Responsável | Prioridade | Prazo |
|---|---|---|---|
| *[...]* | *[...]* | *[Alta/Média/Baixa]* | *[...]* |

---

## 18. Histórico de Revisões

*Registro cronológico de todas as versões do documento. Toda alteração relevante deve gerar uma nova linha.*

| Versão | Data | Autor | Alterações |
|---|---|---|---|
| v0.1 | *[dd/mm/aaaa]* | *[Nome]* | *[Criação do documento]* |
| v0.2 | *[dd/mm/aaaa]* | *[Nome]* | *[...]* |
