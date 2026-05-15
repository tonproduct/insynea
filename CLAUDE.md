# Insynea — Contexto do Projeto

## O que é

Insynea é uma plataforma de aulas particulares online fundada por uma professora, para professores. O objetivo é resolver o problema que as plataformas atuais (Superprof, Preply, TutorMundi) não resolvem: professores pagam comissão alta, ficam expostos ao calote, não têm controle sobre agenda/preço e recebem em datas fixas sem flexibilidade.

**Proposta de valor central:** aluno encontra professor, agenda e paga — com segurança para os dois lados.

---

## Modelo de Negócio

| Regra | Detalhe |
|---|---|
| Comissão | 25% por aula **concluída e confirmada** |
| Mínimo de preço | R$30 por hora-aula (50 min de aula efetiva) |
| Repasse | Automático após confirmação. Sem datas fixas. |
| Taxa de cadastro | Nenhuma |

**Fluxo de pagamento (exemplo com R$70):**
1. Professor define o valor (ex: R$70)
2. Aluno agenda e paga dentro da plataforma — valor fica retido
3. Aula acontece
4. Aluno confirma a aula
5. Divisão automática: R$17,50 (Insynea, 25%) + R$52,50 (professor, 75%)
6. Valor entra no saldo do professor — saque disponível a qualquer momento

---

## Aula Diagnóstica

- **Duração:** 25 minutos (metade da hora-aula)
- **Preço:** metade do valor normal do professor
- **Oferta:** opcional, ativada pelo professor
- **Professor recebe** — ao contrário de outras plataformas que usam a primeira aula como "teste gratuito"
- **Propósito:** aluno conhece a metodologia ao vivo; professor avalia dificuldades e ritmo do aluno; juntos definem o plano de trabalho
- **Risco mapeado:** mecanismo de confirmação pode ser abusado (aluno não confirma para não pagar)

---

## Personas

### Sofia Mendes, 34 — Professora
Pedagogia + Matemática · São Paulo · 5 anos de experiência · 8–12 aulas/sem · R$80–120/h  
Ferramentas: WhatsApp, Google Meet, Notion, iPhone + MacBook

**Objetivos:** agenda cheia sem depender de uma plataforma só, receber com segurança, construir reputação, controle total sobre preço e disponibilidade, usar aula diagnóstica para filtrar alunos sérios, sacar o saldo quando quiser.

**Frustrações:** comissão de 30–33% em outros lugares, plataformas que cobram para aparecer mas não entregam alunos, aluno some após combinar horário, repasse só em datas fixas, sem portabilidade, suporte inexistente em conflitos.

---

### Lucas Carvalho, 23 — Aluno
Estudante de Engenharia · Campinas · 1ª vez buscando professor particular · Alta urgência

**Objetivos:** encontrar professor que saiba explicar (não só saber o conteúdo), usar aula diagnóstica para testar antes de se comprometer, pagar com segurança sem surpresas.

**Frustrações:** não sabe como avaliar qualidade do professor antes de pagar, medo de pagar e não receber, processo de agendamento confuso em outras plataformas.

---

### Rafael Costa, 40 — Fundador em Potencial
Professor experiente que quer construir dentro da plataforma. Perfil "Professor Fundador": primeiros professores que entram e ajudam a moldar o produto. Vê a plataforma como oportunidade de negócio, não só de renda.

---

## Jobs to Be Done (resumo)

**Aluno — Funcional:** encontrar professor certo rapidamente, pagar com segurança, confirmar qualidade antes de se comprometer.  
**Aluno — Emocional:** sentir que não vai ser enganado, ter confiança na aula antes de gastar mais.  
**Aluno — Social:** mostrar que está se preparando, não parecer despreparado.

**Professor — Funcional:** ter agenda cheia, receber no prazo, ter ferramentas para gerenciar alunos e pagamentos.  
**Professor — Emocional:** sentir que o trabalho é valorizado, ter autonomia e segurança financeira.  
**Professor — Social:** construir reputação profissional verificável, ser reconhecido pela qualidade.

---

## Pain Points com Evidência de Mercado

- **Comissão alta:** Superprof e Preply cobram 33% ou mais (fonte: Reclame Aqui, Trustpilot)
- **Calote:** aluno combina, some, professor não tem como recorrer
- **Repasse lento:** datas fixas, sem visibilidade do saldo em tempo real
- **Suporte inexistente:** plataformas não mediam conflitos
- **Sem portabilidade:** professor sai e perde histórico de avaliações

---

## Escopo do Produto

| Fase | Mercado | Matérias |
|---|---|---|
| Agora | Brasil | Reforço escolar: Matemática, Português, Física, etc. + ENEM, Vestibular, Concurso, Inglês |
| Em breve | Brasil | Idiomas em geral |
| Futuro | Global | Qualquer habilidade ensinável online |

---

## Arquivos do Projeto

| Arquivo | Conteúdo |
|---|---|
| `resumo.html` | Entendimento do produto — para validação com a cliente |
| `definicoes.html` | Definições de produto: modelo, fluxo de pagamento, aula diagnóstica, professor fundador |
| `personas.html` | 3 personas com comportamento, objetivos e frustrações |
| `jtbd.html` | Jobs to Be Done, jornada do usuário e pain points com evidência |
| `cronograma.html` | Cronograma do projeto de design |
| `sitemap-flowchart.html` | Sitemap da plataforma |
| `index.html` | Página principal do portfólio — navega para todos os artefatos |

---

## Design System

**Stack:** HTML puro + CSS inline. Para protótipos mobile no Figma.

### Tipografia (decisão final)

| Uso | Família | Peso |
|---|---|---|
| Títulos / headings | DM Serif Display | Regular (serifado elegante, quente) |
| Corpo / UI / botões / labels | DM Sans | 400 / 500 / 600 |

Combinação escolhida pela tensão entre autoridade (serif em headings) e clareza (sans em UI). Alinha com o tom da marca: humana, profissional, brasileira — sem frieza de tech puro, sem formalidade excessiva.

Registrada no Figma como variáveis na coleção "Insynea — Design Tokens".

### Paleta de marca (tokens Figma — coleção "Insynea — Design Tokens", modo "Light")

Primitivos: Verde 900=#2D4A1E · 700=#3A5E1C · 500=#5A7E2E · 100=#D4E8C0 | Cream 50=#F5F0E4 · 100=#EDE5D5 · 200=#D8C8AC · 400=#C4A87A | Ouro 700=#B89018 · 600=#C8A820 · 500=#9E7A14 · 400=#D4A800 | Marrom 900=#3B1A06 · 700=#6B3C14 · 500=#8C6848 · 100=#E8D5B8

Semânticos principais:
- `marca/primary` → Verde/700 (#3A5E1C)
- `marca/accent` → Ouro/700 (#B89018)
- `fundo/default` → Cream/50 (#F5F0E4)
- `fundo/invert` → Verde/900 (#2D4A1E)
- `texto/primary` → Texto Principal/900 (#1C1A12)
- `ui/header-bg` → Verde/900

**Padrões visuais:**
- Nav + hero com `background: #2D4A1E`, texto branco
- Cards brancos (`#FFFFFF`) com borda `var(--line)` e `border-radius: 14–16px`
- Números grandes (52–56px, weight 900) como âncora visual
- Sem sombras pesadas — `box-shadow: 0 1px 4px rgba(0,0,0,0.05)`

---

## Contexto da Usuária (Cliente)

A fundadora da Insynea é professora particular. O produto nasceu da própria experiência de ser explorada por plataformas existentes. Decisões de produto são pessoais e carregadas de opinião — tratar com respeito e precisão. Validar entendimentos com ela antes de avançar.
