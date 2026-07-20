# Convenções editoriais e normativas do Livro I

## Estado deste documento

Estas convenções foram aprovadas expressamente pelo editor-chefe em 20 de julho de 2026. São obrigatórias para a organização editorial e normativa do Livro I até que nova decisão aprovada as substitua. O primeiro estado editorial regido por elas recebe o identificador `AFF-L1-2026.07.20-R1`.

## Estrutura e autoridade

A **Carta Magna do AFF** corresponde ao **Título I — Da Identidade e dos Fundamentos** como um todo:

- Preâmbulo;
- Capítulo I — A Missão do Analista de Finanças Familiares;
- Capítulo II — Dos Objetivos Estratégicos;
- artigos 1º a 40.

O Capítulo II não constitui sozinho a Carta Magna. Essa definição segue a hierarquia encontrada nas versões incrementais recuperadas: `Carta Magna → Título I → Capítulos I e II`.

O **Título II — Do Modelo Mental do Investidor** desenvolve a forma de pensar do AFF e está subordinado aos princípios da Carta Magna.

O editor-chefe é a autoridade final de aprovação. A existência de arquivo, versão ou commit não equivale, por si só, à aprovação editorial.

## Carta Magna como documento autônomo

O Título I constitui a fonte canônica única da Carta Magna do AFF. Poderá existir uma versão autônoma para publicação ou consulta, desde que:

- seja derivada do Título I aprovado;
- identifique a versão de origem;
- não seja mantida como segunda fonte normativa independente;
- seja atualizada a partir do texto canônico.

Em caso de divergência, prevalecerá o Título I aprovado no repositório.

## Identificação editorial canônica

Cada estado aprovado do Livro I receberá identificador no formato `AFF-L1-AAAA.MM.DD-RN`, em que `RN` representa a revisão aprovada na data. O identificador será registrado no documento principal, no changelog e em toda versão autônoma derivada.

A versão autônoma da Carta Magna deverá informar:

- identificador editorial de origem;
- estado de aprovação;
- data de geração;
- commit de origem para verificação de integridade.

O commit identifica o conteúdo técnico, mas não substitui a decisão expressa de aprovação do editor-chefe.

## Escopo patrimonial

O projeto distingue:

- **Patrimônio Familiar:** conjunto de ativos, reservas, direitos, obrigações, fluxos de renda e objetivos da família;
- **Carteira Permanente AFF:** componente societário de longo prazo do patrimônio, composto por Empresas AFF e orientado à geração de renda real crescente;
- **Empresa AFF:** empresa aprovada pelos critérios qualitativos, financeiros, distributivos, de governança, risco e valuation da metodologia.

A Carteira Permanente AFF não representa necessariamente a totalidade do patrimônio familiar. Reservas de liquidez, obrigações, outras classes de ativos e necessidades de curto prazo integram a política patrimonial mais ampla.

## Proveniência editorial

Cada texto deverá receber uma das classificações:

1. **Transcrição:** reprodução fiel do documento-fonte, limitada a correções tipográficas, codificação e Markdown.
2. **Consolidação editorial:** combinação de duas ou mais fontes, com harmonização terminológica e aprofundamento sem mudança deliberada da tese central.
3. **Reconstrução editorial:** novo texto produzido quando há evidência de que um original existiu, mas seu conteúdo integral não foi localizado.
4. **Redação editorial inédita:** texto novo produzido para preencher parte da estrutura aprovada que ainda não possuía texto histórico conhecido.

Os textos atualmente incorporados ao Título I para os artigos 1º a 6º, 14º e 20º são **consolidações editoriais**, não transcrições. Seu estado de aprovação deverá ser controlado separadamente. Os arquivos em `legacy/fontes-recuperadas/` preservam as fontes para auditoria.

## Estado editorial

Proveniência e estado editorial são classificações independentes. Um texto deverá receber um dos seguintes estados:

1. **Minuta:** primeira redação ainda não submetida ao editor-chefe.
2. **Em revisão:** texto submetido para avaliação e ajustes.
3. **Aprovado:** texto validado expressamente pelo editor-chefe.
4. **Substituído:** versão preservada no histórico, mas que deixou de ser canônica.
5. **Histórico:** fonte documental que não integra diretamente o texto vigente.

Os arquivos em `legacy/fontes-recuperadas/` são históricos. Os Artigos 5º e 6º do Título II são redações editoriais inéditas aprovadas.

## Precedência documental

1. prevalece o texto expressamente aprovado pelo editor-chefe;
2. um original posteriormente recuperado não substitui automaticamente texto aprovado;
3. o original recuperado deverá ser preservado no acervo histórico e comparado com o texto vigente;
4. divergências materiais serão apresentadas ao editor-chefe;
5. consolidações e reconstruções manterão rastreabilidade para suas fontes;
6. a aprovação de nova versão tornará a anterior substituída, sem apagá-la do histórico;
7. resumos, índices e listas de títulos nunca prevalecerão sobre texto integral;
8. existência de arquivo, versão ou commit não equivalerá, isoladamente, a aprovação editorial.

## Identificadores normativos

Os identificadores deverão informar o domínio da norma:

- `AFF-CM-NNN`: norma da Carta Magna;
- `AFF-MM-NNN`: norma do Modelo Mental;
- outras séries somente poderão ser criadas quando o respectivo módulo existir.

As normas históricas da Carta Magna mantêm a sequência localizada:

- Artigo 3º → `AFF-CM-001`;
- Artigo 4º → `AFF-CM-002`;
- Artigo 5º → `AFF-CM-003`;
- Artigo 6º → `AFF-CM-004`;
- Artigo 14º → `AFF-CM-012`;
- Artigo 20º → `AFF-CM-018`.

Os artigos 1º e 2º permanecem com princípios operacionais sem número porque nenhuma numeração aprovada foi localizada. O “Princípio Operacional nº 1” da versão incremental 0.1 foi absorvido pelo princípio operacional da missão, sem adoção de seu número histórico.

No Modelo Mental, a sequência acompanhará os artigos: Artigo 1º → `AFF-MM-001`, Artigo 2º → `AFF-MM-002` e assim sucessivamente.

## Hierarquia normativa

A hierarquia do projeto será:

1. princípios e enunciados normativos canônicos da Carta Magna do AFF;
2. normas operacionais da Carta Magna — `AFF-CM`;
3. normas do Modelo Mental — `AFF-MM`;
4. normas de módulos futuros;
5. protocolos e critérios operacionais;
6. comentários técnicos, exemplos e estudos de caso.

Dentro de cada artigo:

- o enunciado principal em destaque e a Norma Operacional possuem força normativa;
- protocolos e critérios determinam a execução;
- comentários técnicos explicam fundamentos e limites;
- exemplos são ilustrativos e não criam obrigação universal;
- referências sustentam afirmações, mas não se tornam automaticamente normas AFF.

Em caso de conflito, prevalecerá a norma hierarquicamente superior. Norma específica poderá detalhar norma geral, mas não contrariá-la. Conflito que não possa ser solucionado por interpretação será submetido ao editor-chefe.

Comentários, exemplos, estudos de caso e referências contidos no Título I não ocupam o primeiro nível apenas por integrarem fisicamente a Carta Magna; sua força será a definida pela função editorial indicada acima.

## Referências cruzadas

Referências internas deverão usar, sempre que necessário, a sequência:

> Livro → Título → Capítulo → Artigo → Norma.

Exemplo: `Livro I, Título II, Capítulo III, Artigo 3º, Norma AFF-MM-003`.

Elementos desnecessários poderão ser omitidos quando não houver ambiguidade.

## Referências externas

As referências bibliográficas e documentais deverão observar:

1. preferência por fonte primária, oficial ou acadêmica original quando disponível;
2. uso de fonte secundária para contexto, síntese ou crítica, sem substituir indevidamente a fonte original;
3. identificação de autor ou instituição, título, publicação ou editora, data e edição quando pertinentes;
4. inclusão de DOI para trabalhos acadêmicos e URL estável para documentos digitais quando disponíveis;
5. indicação de página, seção ou trecho quando necessária para localizar afirmação específica;
6. registro da versão ou data de consulta quando o conteúdo digital puder ser alterado;
7. distinção explícita entre atribuição direta a um autor e inferência ou aplicação editorial do AFF;
8. identificação de tradução própria e preservação do sentido do texto original;
9. identificação expressa de material de referência local que não possua endereço público verificável;
10. revisão de atualidade quando norma, dado, instituição ou conteúdo citado puder ter mudado.

Citações e paráfrases não poderão atribuir ao autor conclusão mais ampla do que a sustentada pela fonte consultada.

## Níveis de evidência

- **Nível A:** forte consenso acadêmico ou ampla evidência empírica reproduzida em contextos pertinentes.
- **Nível B:** evidência relevante, mas dependente de contexto, amostra, horizonte ou método.
- **Nível C:** hipótese plausível ou evidência limitada, com restrições significativas.
- **Nível D:** filosofia, preferência metodológica ou regra normativa adotada pelo AFF.

Classificações deverão registrar o objeto avaliado. Aplicam-se ainda as seguintes regras:

- um artigo não receberá um único nível global;
- diferentes afirmações do mesmo artigo poderão receber níveis distintos;
- uma regra normativa poderá ser Nível D mesmo quando se apoiar em evidências de Níveis A ou B;
- uma identidade matemática poderá ser Nível A, enquanto sua aplicação com parâmetros estimados poderá ser Nível B ou C;
- ausência de classificação não será interpretada como evidência forte.

## Títulos oficiais recuperados

Quando houver divergência entre títulos:

1. prevalecerá o título do texto integral aprovado;
2. na ausência de aprovação, prevalecerá o título mais completo encontrado na fonte histórica;
3. títulos provisórios serão identificados como tais;
4. original posteriormente localizado e divergente será submetido a comparação editorial.

Os títulos históricos recuperados do **Título I** incluem:

- Título I, Artigo 3º — Da Preservação Permanente do Capital;
- Título I, Artigo 4º — Da Construção de Renda Passiva Crescente;
- Título I, Artigo 12º — Da Relação entre Risco e Retorno.

Os demais títulos seguirão o mapa documental do índice até que o original integral seja recuperado ou que redação inédita seja aprovada.
