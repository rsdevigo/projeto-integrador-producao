# Decision Log — Projeto Integrador (Produção)

## O que é este documento

O Decision Log registra as decisões relevantes tomadas ao longo da produção do Vertical Slice. Funciona como a "memória" oficial do estúdio: qualquer pessoa da equipe (ou o professor) deve conseguir entender, meses depois, por que uma escolha foi feita.

Cada equipe mantém **um único arquivo**, atualizado incrementalmente durante todo o semestre.

---

## Quando registrar uma decisão

Nem tudo precisa virar um registro. Use este critério: **se a decisão afeta escopo, cronograma, arquitetura do jogo, pipeline de produção ou a experiência final do jogador, ela deve ser registrada.**

Registre quando a decisão envolver:

* corte, adição ou alteração de escopo (features, mecânicas, conteúdo);
* mudança de ferramenta, engine, plugin ou pipeline de trabalho;
* redefinição de prioridades ou de milestones;
* resolução de um risco identificado no Registro de Riscos;
* escolhas de design que impactam a identidade do Vertical Slice (arte, áudio, UX, narrativa);
* divisão de responsabilidades relevante dentro da equipe;
* qualquer decisão que gerou discordância na equipe antes de um consenso.

**Não é necessário registrar:**

* tarefas rotineiras do backlog;
* ajustes técnicos menores sem impacto em escopo ou prazo;
* decisões reversíveis e triviais (ex.: nome de uma variável, cor de um botão de teste).

Na dúvida, pergunte: *"se essa decisão for questionada depois, alguém vai precisar saber por quê?"* Se sim, registre.

---

## Template de registro

Copie o bloco abaixo para cada nova decisão e preencha todos os campos.

```markdown
### DEC-XX — [Título curto da decisão]

**Data:** DD/MM/AAAA

**Decisão:**
[O que foi decidido, de forma direta e objetiva.]

**Contexto:**
[Situação que motivou a decisão. Qual problema, risco ou oportunidade estava em jogo.]

**Alternativas consideradas:**
1. [Alternativa 1 — breve descrição]
2. [Alternativa 2 — breve descrição]
3. [Alternativa 3, se houver]

**Justificativa:**
[Por que a opção escolhida foi a melhor diante do contexto e das alternativas. Critérios usados: tempo, viabilidade técnica, impacto no jogador, capacidade da equipe, etc.]

**Responsável:**
[Nome de quem tomou ou aprovou a decisão. Se foi decisão coletiva, indicar "Equipe" e quem conduziu a discussão.]

**Impacto esperado:**
[Efeito previsto sobre escopo, cronograma, qualidade ou experiência do jogo.]

**Consequências futuras:**
[O que essa decisão exige da equipe daqui para frente: dependências criadas, riscos assumidos, revisões necessárias em outros documentos (GDD, backlog, cronograma).]

---
```

---

## Numeração

Use a sequência `DEC-01`, `DEC-02`, `DEC-03`... na ordem cronológica em que as decisões forem tomadas. Não reutilize números de decisões removidas ou substituídas — em vez disso, registre uma nova decisão referenciando a anterior (ex.: "Substitui a DEC-04").

---

## Boas práticas

* Registrar a decisão o quanto antes, idealmente no mesmo encontro em que foi tomada.
* Escrever de forma objetiva — o Decision Log não é um relatório narrativo.
* Revisar o log no início de cada milestone para verificar se decisões antigas ainda são válidas.
* Vincular decisões relacionadas quando fizer sentido (ex.: "Relacionado à DEC-02").
* Em caso de decisão tomada em mentoria com o professor, registrar isso no campo Responsável.

---

## Registros

*(Adicione os registros abaixo, seguindo o template acima)*
