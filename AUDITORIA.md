# Auditoria das fontes — 09/10/2026

Método: `pdftotext -enc UTF-8 -layout` nos dois PDFs do TSE (texto extraído localmente, uma página por bloco), leitura integral dos dois planos e conferência de cada opção do banco antigo (36 perguntas, 71 opções) contra o texto.

- **Numeração:** nos dois PDFs a página impressa é igual à página do PDF, então `#page=N` aponta para o lugar certo. O PL tem 75 páginas com texto e o PT, 83.
- **Legenda:** ✔ conferido sem mudança · ✎ página ou rótulo corrigido · ⚠ paráfrase corrigida (o texto antigo não batia com o plano) · ↻ substituído.

## Problemas encontrados no banco antigo

| id | lado | status | o que estava errado | correção (página verificada) |
|---|---|---|---|---|
| es2 | F | ⚠ | "**acabar** com as decisões monocráticas" | O plano propõe **limitar** essas decisões e acabar com o foro criminal originário no STF (p.65) |
| es3 | F | ⚠ | "fim da reeleição para cargos **executivos**" | O fim da reeleição é só **para presidente da República** (p.66) |
| es5 | F | ✎⚠ | fonte vaga ("Valores, p.9; Brasil que Cumpre a Constituição") | Tesouraço na Censura, p.66–67; texto refeito com a proposta concreta |
| eco2 | L | ✎ | "Diretriz 1 (p.11)" | A p.11 é a seção "Compromisso com o Projeto de Nação" (a Diretriz 1 começa na p.15) |
| eco3 | L | ⚠ | Isenção de IR até R$ 5 mil e tributação dos super-ricos apresentadas como propostas | As duas **já foram aprovadas** (p.11 e 19); a proposta futura é manter e seguir com a "justiça tributária" (p.49) |
| eco5 | L | ⚠ | Novo Desenrola como proposta | Aparece como ação de 2026 já feita (p.12); as propostas são fundos garantidores, controle de apostas e regras de crédito (p.49) |
| ca2 | L | ⚠ | Estoques reguladores e salário-mínimo como propostas para baratear comida | São balanço do mandato (p.58); as propostas são PAA, merenda e Plano Safra da Agricultura Familiar (p.59–60) |
| so1 | L | ⚠ | Bolsa Família e benefícios para crianças como propostas | São balanço; a proposta é "manter, aperfeiçoar e ampliar" a proteção social, o SUAS e os Cuidados (p.18, 25–26) |
| ed4 | L | ⚠ | "manter ProUni" | O ProUni só aparece como balanço (p.33); a proposta é um novo ciclo de expansão e interiorização, com assistência estudantil |
| cu1 | L | ⚠ | "manter o Ministério da Cultura" | Não há essa proposta (a recriação é balanço); removido |
| am1 | F | ⚠ | Faltava a meta central do plano | Incluída a meta de zerar o desmatamento ilegal até 2029 (p.58) |
| am1 | L | ✎ | "p.69–73 (índice TSE)" | Meta de desmatamento líquido zero até 2030: p.70; fundos: p.56 e 70–71 |
| am2 | L/F | ↻ | Comparava a "transição" (L) com o fracking (F), mas o plano de Lula **também** expande petróleo e gás via Petrobras (p.66–67) | Nova pergunta sobre o papel da Petrobras e do capital privado em energia |
| tr1 | L | ✎ | "p.73–77 (índice TSE)" | p.75: fim da 6x1 e 40 h **sem redução salarial** |
| tr2 | L | ✎ | "índice TSE" | p.74–75 e 77 |
| ex1 | L | ✎ | "p.77–82 (índice TSE)" | p.80–81 |
| ex1 | F | ⚠ | "soberania sem viés ideológico" | O plano fala em "profissionalismo e pragmatismo" (p.62) |
| ca1 | L | ✎ | "p.58–63 (índice TSE)" | Reforma agrária p.60; Pronaf/Plano Safra p.59 |
| eco4 | F | ⚠ | "programa de desestatização" sem ressalva | O plano diz "com critério, avaliando caso a caso" (p.70) |
| tr3 | F | ⚠ | Faltava a ressalva | "sem retirar direitos" (p.43) |
| tr3 | L | ✎ | Salário-mínimo citado da p.19 (balanço) | A proposta de continuidade está na p.74 |
| sa2 | B | ↻ | Uma opção só, igual para os dois lados | Prontuário único foi para "Onde os dois planos concordam" (fora do cálculo); a nova sa2 trata de remédios para doentes crônicos |

## Conferidos sem mudança de conteúdo (✔, às vezes com página mais precisa)

seg1–seg6, eco1, es1, es4, sa1, ed1, ed2, ed3, so2, di1, di2, dg1 nos dois lados, além de todas as opções F não listadas acima. Termos como "narcoterroristas" e "doutrinação político-partidária" agora aparecem entre aspas, como palavras do plano.

## Perguntas novas (15, contando a nova sa2), todas com página conferida

| id | tema | L | F |
|---|---|---|---|
| seg7 | dinheiro federal da segurança | Diretriz 3, p.27–28 | Brasil sem Medo, p.13 e 15 |
| seg8 | roubo de celular | Diretriz 3, p.29 | Brasil sem Medo, p.16 |
| tr4 | sindicatos | Diretriz 12, p.75–76 | Brasil que Prospera, p.44–45 |
| pr1 | Previdência/INSS | Diretriz 12, p.77 | Brasil sem Fila p.26; p.72–73 |
| es6 | corrupção | Diretriz 1, p.18 | Brasil que Não Volta Atrás, p.69–70 |
| sa2 | remédios/doença crônica | Diretriz 5, p.36 | Brasil que Prepara, p.38 |
| ed5 | ensino técnico | Diretriz 4, p.33 | Brasil que Prepara, p.36 |
| am3 | licenciamento ambiental | Diretriz 11, p.70 e 72 (sem proposta de prazo) | Brasil que Cresce, p.49–50 |
| mu1 | violência contra a mulher | Diretriz 2, p.21 | p.14; Brasil por Elas, p.17–19 |
| mu2 | renda das mulheres | Diretriz 12, p.75 | Brasil por Elas, p.18–20 |
| rg1 | desigualdade regional | Diretriz 8, p.55–56 | Brasil que Cresce, p.52 e 60 |
| rg2 | infraestrutura | Diretriz 8, p.52–53 | Brasil que Cresce, p.50–51 |
| ex2 | defesa | Diretriz 13, p.78–79 | p.13–14; Brasil que Cresce, p.63 |
| dg2 | regulação da IA | Diretriz 6 p.42; Diretriz 8 p.55 | Brasil que Cresce, p.56–57 |
| cu2 | esporte | Diretriz 6, p.43–44 | Brasil que Prepara, p.40 |

(am2 também foi reescrita; ver acima.)

## Checagens automáticas (rodadas em 09/10/2026)

- 50 perguntas, 12 no modo rápido e 16 temas; cada pergunta tem exatamente uma opção L e uma F, e todas as páginas citadas existem no PDF.
- Tamanho das opções: em nenhum par a mais longa passa de 1,6× a mais curta (4 pares foram ajustados).
- Viés de posição: em 9.000 sementes × 50 perguntas, a opção de Lula aparece primeiro em 50,0% dos casos.
- Teste no navegador (modo rápido, uma pulada): a % bate com a conta manual (8 de 11 = 73%, 3 de 11 = 27%), há 38 links de fonte com `#page=N` e não há rolagem horizontal em 375 px.

## Pontos ainda abertos para revisão humana

- **seg2 e seg4:** a opção L descreve o que o plano propõe no lugar; o plano não diz explicitamente "não mudar a maioridade". A observação na fonte deixa isso claro.
- **am3:** o plano de Lula não trata de prazo de licenciamento; a opção L traz a abordagem dele para o tema (fiscalização e Código Florestal), com observação.
- **ex2:** o plano do PL fala pouco de defesa; a opção F junta a tropa nas fronteiras (p.13–14) com o parágrafo sobre Forças Armadas (p.63).
- A categoria feminina no esporte (PL p.40–41) ficou de fora, porque o plano do PT não trata do tema e não haveria contraponto fiel.

## Perguntas adicionadas em 09/10/2026 (segunda leva, 8), com página conferida no texto

| id | tema | L | F |
|---|---|---|---|
| eco6 | preço dos combustíveis | Diretriz 10, p.66 | Brasil Mais Barato p.31; Brasil que Cresce p.53 |
| eco7 | minerais críticos | Diretriz 8, p.52 | Brasil que Cresce, p.55–56 |
| tr5 | abrir o próprio negócio | Diretriz 8, p.57–58 | Brasil que Prospera, p.45 |
| so3 | idosos e cuidado | Diretriz 2, p.22 | Brasil por Elas p.21; Brasil que Prepara p.39 |
| di3 | pessoas com deficiência | Diretriz 2, p.23 | Brasil que Prepara, p.39–40 |
| rg3 | saneamento | Diretriz 7, p.46 | Brasil que Prospera, p.47 |
| rg4 | transporte nas cidades | Diretriz 7, p.46 | Brasil que Cresce, p.51 |
| rg5 | turismo | Diretriz 8, p.57 | Brasil que Cresce, p.59–60 |

Observações: em **eco7**, os dois planos falam em agregar valor no Brasil, e a diferença está no papel do Estado e do capital estrangeiro. Em **rg4** e **rg5** o contraste é menor que nas outras perguntas.

O modo rápido deixou de ter 12 perguntas fixas: a cada teste, sorteia 12 dos 16 temas e uma pergunta de cada. Validação: 58 perguntas, uma opção L e uma F em cada, páginas dentro do PDF; em 10 mil sorteios, todos tiveram 12 temas distintos, e todas as 58 perguntas apareceram.
