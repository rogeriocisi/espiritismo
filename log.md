# Log do Wiki Espírita

Log cronológico de todas as operações: ingestões, queries arquivadas e revisões de saúde.
Formato de cada entrada: `## [YYYY-MM-DD] tipo | Descrição`

Para listar as últimas entradas rapidamente:
```
grep "^## \[" log.md | tail -10
```

---

## [2026-05-04] criação | Ingestão em lote — 41 novas páginas (raw/ completo)

**Operação**: Geração de páginas wiki para todas as obras adicionadas ao diretório raw/ desde a última sessão. Abrangeu entidades, obras de múltiplos autores e atualizações do índice.

**Páginas de entidades criadas** (4):
- `wiki/autores/Manoel Philomeno de Miranda.md` — fontes:2; mentor de Divaldo Franco; psiquiatria espiritual; obras: Transtornos, Transição, Loucura
- `wiki/autores/Yvonne Pereira.md` — fontes:1; médium vidente/auditiva; *Memórias de um Suicida* (FEB, 1955)
- `wiki/autores/Herculano Pires.md` — fontes:1; filósofo; PAIDEIA; *O Espírito e o Tempo* (7° melhor livro espírita séc. XX)
- `wiki/autores/Humberto de Campos.md` — fontes:1; escritor ABL (†1934); ditou obras a Chico Xavier; processo com herdeiros; pseudônimo "Irmão X"

**Páginas de obras criadas** (37):
- Léon Denis: *No Invisível*, *O Problema do Ser*, *O Porquê da Vida*, *Espíritos e Médiuns*, *Socialismo e Espiritismo*
- Divaldo Franco: *O Homem Integral*, *Jesus e Atualidade*, *Em Busca da Verdade*, *Calvário de Libertação*, *Transtornos Psiquiátricos e Obsessivos*, *Transição Planetária*
- André Luiz: *Entre Irmãos de Outras Terras* (bimediunidade Waldo/Chico, 1965)
- Humberto de Campos: *Brasil Coração do Mundo Pátria do Evangelho*, *Boa Nova*
- Manoel Philomeno: *Loucura e Obsessão*
- Bezerra de Menezes: *A Loucura sob um Novo Prisma* (pseudônimo MAX)
- Emmanuel: *Vida e Sexo*
- Chico Xavier: *Parnaso de Além-Túmulo*
- Yvonne Pereira: *Memórias de um Suicida*
- Herculano Pires: *O Espírito e o Tempo*, *Vampirismo*, *Espiritismo Dialético*
- Allan Kardec: *Discursos Pronunciados*
- Gabriel Delanne: *O Espiritismo perante a Ciência*
- Alexandre Aksakof: *Animismo e Espiritismo*
- Gustave Geley: *Do Inconsciente ao Consciente*
- Albert de Rochas: *Exteriorização da Sensibilidade*
- Paul Gibier e Ernesto Bozzano: *Materializações de Espíritos*
- Henri Sausse: *Biografia de Allan Kardec*
- Arthur Conan Doyle: *História do Espiritismo*
- Dora Incontri: *Pedagogia Espírita*
- Marcel Souto Maior: *As Vidas de Chico Xavier*
- Francisco Valdomiro Lorenz: *O Esperanto como Revelação*
- André Luiz: *Agenda Cristã*, *Sinal Verde*, *Conduta Espírita*, *Respostas da Vida* (indexadas)

**Atualizações**:
- `index.md` — reescrito: 58→99 páginas; 37→65 fontes; novas seções por autor/tema; raw/ atualizado
- `wiki/overview.md` — contadores atualizados; prioridades revisadas

**Método**: pdftotext extraindo páginas 1–12 de cada PDF; leitura de índice, prefácio, abertura, temas; página criada em seguida.

---

## [2026-05-04] criação | Obras Emmanuel sem página + Desobsessão como obra

**Operação**: Criação de 5 novas páginas de obras Emmanuel até então sem entrada no wiki, e criação da página de *Desobsessão* como obra (separada da página de conceito já existente).

**Páginas criadas** (5 novas):
- `wiki/obras/Emmanuel/Emmanuel.md` — fontes:1; dissertações filosófico-morais; prefácio "Pedro Leopoldo, 16 set. 1937"; apresentação de Emmanuel como padre católico no Brasil; lugar inaugural na série
- `wiki/obras/Emmanuel/Fonte Viva.md` — fontes:1; mensagens de moral e orientação espiritual; nota sobre extração parcial do PDF
- `wiki/obras/Emmanuel/Boa Nova.md` — fontes:1; mensagens evangélicas; o *euangélion* na perspectiva espírita
- `wiki/obras/André Luiz/Desobsessão.md` — fontes:1; manual prático; 73 caps.; bimediunidade Xavier (pares) + Waldo Vieira (ímpares); estrutura em 5 blocos; método de desobsessão; prefácio Emmanuel; cena de Gádara (Lc 8:30)

**Páginas atualizadas**:
- `index.md` — 5 novas linhas; contador 54→59
- `wiki/overview.md` — contador 54→59 páginas; 38→42 enriquecidas; lista Emmanuel expandida; prioridades atualizadas

**Critério fontes**:
- `fontes: 1` — PDF lido na sessão de ingestão de 2026-05-03; conteúdo identificado mesmo que extração parcial
- `fontes: 0` — PDF digitalizado (imagem); extração de texto mínima; conteúdo não verificável sem OCR

---

## [2026-05-04] manutenção | Indexação romances Emmanuel + enriquecimento Chico Xavier

**Operação**: Retomada da sessão anterior — indexação das 5 páginas de romances históricos de Emmanuel que existiam mas estavam ausentes do índice; enriquecimento substantivo da página de Chico Xavier.

**Páginas atualizadas**:
- `index.md` — 5 novas linhas (romances históricos Emmanuel); contador 49→54; data 2026-05-04
- `wiki/overview.md` — contador páginas 50→54; enriquecidas 34→38; prioridades atualizadas; lista Emmanuel expandida; data 2026-05-04
- `wiki/autores/Chico Xavier.md` — reescrita completa (fontes:0→2): cronologia Pedro Leopoldo/Uberaba com datas dos prefácios; tabela dos 13 volumes com anos e locais; bimediunidade com Waldo Vieira; relação com FEB; séries Emmanuel filosófica e histórica; controvérsias detalhadas

**Páginas já existentes confirmadas como completas** (fontes: 1, não estavam no índice):
- `wiki/obras/Emmanuel/Há Dois Mil Anos.md` — índice dos 20 caps. em 2 partes; Públio Lentulus; Galileia até Pompeia
- `wiki/obras/Emmanuel/50 Anos Depois.md` — Nestório; Célia; 14 caps.; carta ao leitor
- `wiki/obras/Emmanuel/Paulo e Estêvão.md` — 20 caps.; Estêvão protomártir + Paulo de Tarso; Damasco
- `wiki/obras/Emmanuel/Ave, Cristo!.md` — 14 caps.; cena pré-encarnação; Quinto Varro; mártires séc. III
- `wiki/obras/Emmanuel/Renúncia.md` — 14 caps.; Alcione e Pólux; karma afetivo; véu da memória

**Próximas prioridades** (atualizadas no overview):
1. Enriquecer Divaldo Franco (fontes: 0)
2. Criar páginas obras Emmanuel sem página: *Emmanuel* (1937), *Fonte Viva*, *Boa Nova*, *Santa Marina*
3. Criar página *Desobsessão* como obra (separado do conceito)
4. Enriquecer stubs: Carma, Passes, Pluralidade dos Mundos, Evolucionismo Espiritual, FEB

---

## [2026-05-03] criação | Páginas individuais volumes 2–13 da Série André Luiz

**Operação**: Criação de 12 páginas individuais para os volumes 2–13 da *Coleção A Vida no Mundo Espiritual*, a partir dos textos extraídos anteriormente em `/tmp/al_02_*` a `/tmp/al_13_*`.

**Fontes consultadas**: textos extraídos via pdftotext de todos os 13 PDFs da série André Luiz (já ingeridos em sessão anterior). Leitura de índices completos, prefácios de Emmanuel, capítulo 1, temas centrais.

**Páginas criadas** (12 novas):
- `wiki/obras/André Luiz/Os Mensageiros.md` — vol. 2; 51 caps.; prefácio Emmanuel (Pedro Leopoldo, 26 fev. 1944); Aniceto; obsessão; prece
- `wiki/obras/Missionários da Luz.md` — vol. 3; 20 caps.; prefácio (13 mai. 1945); psicógrafo, epífise, vampirismo, obsessão, passes
- `wiki/obras/André Luiz/Obreiros da Vida Eterna.md` — vol. 4; 20 caps.; prefácio (25 mar. 1946); zonas de erraticidade; Jerônimo
- `wiki/obras/André Luiz/No Mundo Maior.md` — vol. 5; 20 caps.; prefácio (25 mar. 1947); Eusébio; psiquiatria iluminada; Calderaro
- `wiki/obras/Libertação.md` — vol. 6; 20 caps.; parábola do peixinho vermelho; perseguidores invisíveis
- `wiki/obras/Entre a Terra e o Céu.md` — vol. 7; 40 caps.; prefácio (23 jan. 1954); Irmã Clara; reencarnação (caps. 29–31)
- `wiki/obras/Nos Domínios da Mediunidade.md` — vol. 8; 30 caps.; prefácio (3 out. 1954); Áulus; psicofonia; possessão; fascinação
- `wiki/obras/Ação e Reação.md` — vol. 9; 20 caps.; prefácio (1 jan. 1957); karma; Mansão Paz; Druso
- `wiki/obras/Evolução em Dois Mundos.md` — vol. 10; 40 itens em 2 partes; prefácio (21 jul. 1958); Chico Xavier + Waldo Vieira; perispírito
- `wiki/obras/André Luiz/Mecanismos da Mediunidade.md` — vol. 11; Chico Xavier + Waldo Vieira; física quântica e ondulatória aplicada à mediunidade
- `wiki/obras/André Luiz/Sexo e Destino.md` — vol. 12; 28 caps. em 2 partes; prefácio (4 jul. 1963 Uberaba); Waldo Vieira (pt.1) + Chico Xavier (pt.2)
- `wiki/obras/André Luiz/E a Vida Continua.md` — vol. 13; 26 caps.; prefácio (18 abr. 1968 Uberaba); Evelina Serpa; centenário de A Gênese

**Páginas atualizadas**:
- `wiki/obras/Coleção A Vida no Mundo Espiritual.md` — links internos adicionados a todos os 13 volumes
- `index.md` — 12 novas linhas na seção Literatura Mediúnica Brasileira; contador 37→49 páginas
- `wiki/overview.md` — páginas 37→49; enriquecidas 21→33; lista André Luiz expandida

---

## [2026-05-03] ingestão | Revistas Espíritas — Tradutor Salvador Gentile (G:\Meu Drive\_Espiritismo\Kardec)

**Operação**: Ingestão do periódico mensal de Kardec, 12 anos completos (1858–1869).

**Fonte processada** (1 PDF, 12 MB, 37.675 linhas extraídas):
- *Revistas Espíritas — Jornal de Estudos Psicológicos*, tradução de Salvador Gentile, revisão Elias Barbosa, Instituto de Difusão Espírita (Araras, SP)
- Cobre: volumes 1–12 (1858–1869); conteúdo: artigos doutrinários, boletins da SPEE, evocações, dissertações espíritas, correspondência internacional, bibliografias

**Método**: Extração com pdftotext -enc UTF-8 → /tmp/revistas_espiritismo.txt. Leitura da Introdução (jan. 1858), índices anuais, estudo dos Possessos de Morzine (1862–1863), artigos de Flammarion, número memorial de maio de 1869 (biografia de Kardec, discurso de Flammarion, comunicação póstumo de Kardec, estatística do Espiritismo).

**Páginas criadas/atualizadas**:
- `wiki/obras/Revistas Espíritas.md` — NOVA: 12 volumes, tipos de conteúdo, caso Morzine, número memorial de 1869, discurso de Flammarion, comunicação de Kardec como espírito
- `wiki/autores/Allan Kardec.md` — enriquecida (fontes:2→3): SPEE fundada 1º abril 1858, link para Revistas, comunicação póstumo, estatística de 1869
- `wiki/temas/Espiritismo e Ciência.md` — enriquecida (fontes:0→1): Flammarion no túmulo; citação do discurso; posição de Kardec sobre ciência x doutrina
- `index.md` — nova linha para Revistas Espíritas; fontes: 37/37; 37 páginas

**Arquivo copiado para raw/**: Revistas_Espíritas_-_Tradutor_SALVADOR_GENTILE.pdf

---

## [2026-05-03] ingestão | 12 obras de Emmanuel (G:\Meu Drive\_Espiritismo\Emmanuel)

**Operação**: Ingestão da Série Emmanuel — romances históricos + obras filosófico-doutrinárias.

**Fontes processadas** (12 PDFs):
- Filosóficas/doutrinárias: *A Caminho da Luz* (1938), *O Consolador* (1940), *Emmanuel* (1937), *Fonte Viva*, *Boa Nova*, *Vida e Sexo*
- Romances históricos: *Há Dois Mil Anos* (séc. I), *50 Anos Depois*, *Paulo e Estêvão*, *Ave, Cristo!*, *Renúncia*, *Santa Marina*

**Método**: Extração com pdftotext -enc UTF-8 → /tmp/emmanuel_txt/. Leitura de prefácios, índices e seções-chave de: *A Caminho da Luz* (25 caps.), *O Consolador* (2 partes, Q&As selecionados), *Emmanuel* (dissertações), *Há Dois Mil Anos* (contexto romano séc. I). Nota: *Santa Marina* (23 MB) e *Vida e Sexo* extraídos com baixo volume de texto (provável PDF digitalizado).

**Páginas atualizadas/criadas**:
- `wiki/autores/Emmanuel.md` — reescrita: identidade, obras filosóficas e históricas, estilo e perspectiva, citação do prefácio de 1937
- `wiki/obras/Emmanuel/A Caminho da Luz.md` — NOVA: tabela de dados, índice completo de 25 caps., tese central, Jesus como Divino Escultor, Kardec na história universal, papel da América
- `wiki/obras/Emmanuel/O Consolador.md` — NOVA: tabela de dados, estrutura em 2 partes, questão inicial (3 aspectos), Q&As selecionados (Q.1, Q.2, Q.9, Q.20, Q.21), comparação com *O Livro dos Espíritos*

**Arquivos copiados para raw/**: todos os 12 PDFs

---

## [2026-05-03] ingestão | 18 obras de André Luiz (G:\Meu Drive\_Espiritismo\Andre-Luiz)

**Operação**: Ingestão da Série André Luiz completa + obras complementares.

**Fontes processadas** (18 PDFs):
- Série principal: Nosso Lar, Os Mensageiros, Missionários da Luz, Obreiros da Vida Eterna, No Mundo Maior, Libertação, Entre a Terra e o Céu, Nos Domínios da Mediunidade, Ação e Reação, Evolução em Dois Mundos, Mecanismos da Mediunidade, Sexo e Destino, E a Vida Continua...
- Obras complementares: Desobsessão, Agenda Cristã, Sinal Verde, Conduta Espírita, Respostas da Vida

**Método**: Extração com pdftotext -enc UTF-8 → /tmp/andreluiz_txt/ (43.497 linhas total). Leitura de prefácios, índices e seções-chave de: Nosso Lar, Os Mensageiros, Missionários da Luz, Desobsessão, Mecanismos da Mediunidade, Nos Domínios da Mediunidade.

**Páginas atualizadas/criadas**:
- `wiki/obras/André Luiz/Nosso Lar.md` — enriquecida: cap.1 (umbrais), prefácio Emmanuel, mensagem André Luiz, tabela de capítulos, temas
- `wiki/obras/Série André Luiz.md` — reescrita: tabela corrigida com obras complementares, arco narrativo, volumes Waldo Vieira
- `wiki/autores/André Luiz.md` — enriquecida: identidade, narrativa do personagem, citações diretas
- `wiki/conceitos/Desobsessão.md` — enriquecida: fundamento evangélico, estrutura do livro (73 caps.), citações de André Luiz
- `wiki/conceitos/Mediunidade.md` — enriquecida: teoria das ondas (André Luiz/Waldo Vieira), tipos de psicofonia, perspectiva histórica

**Arquivos copiados para raw/**: todos os 18 PDFs

---

## [2026-05-03] ingestão | 6 obras de Kardec (G:\Meu Drive\_Espiritismo\Kardec)

**Operação**: Ingestão em lote das Obras Básicas de Kardec + Obras Póstumas.

**Fontes processadas**:
- `Allan Kardec - o-livro-dos-espiritos.pdf` (3,6 MB, 17.257 linhas extraídas)
- `Allan Kardec - o-evangelho-segundo-o-espiritismo.pdf` (3,4 MB, 14.129 linhas)
- `Allan Kardec - lmed_br.pdf` (1,1 MB, 14.996 linhas)
- `Allan Kardec - o-ceu-e-o-inferno.pdf` (1,1 MB, 13.792 linhas)
- `Allan Kardec - gen_br.pdf` (1,1 MB, 14.539 linhas)
- `Allan Kardec - Obras Póstumas.pdf` (2,9 MB, 11.019 linhas)
- ⏳ `Revistas_Espíritas_-_Tradutor_SALVADOR_GENTILE.pdf` (12 MB) — pendente (processar separadamente)

**Método**: Extração de texto com pdftotext (UTF-8), leitura de seções-chave, atualização das páginas do wiki.

**Páginas atualizadas com conteúdo real das fontes**:
- `wiki/obras/O Livro dos Espíritos.md` — estrutura completa, Q.1, Q.76–95, Q.97–101, Q.166–196, Q.873–889
- `wiki/obras/Allan Kardec/O Evangelho Segundo o Espiritismo.md` — Três Revelações, pluralidade dos mundos, a caridade
- `wiki/obras/O Livro dos Médiuns.md` — estrutura completa dos 32 capítulos, classificação dos médiuns, obsessão
- `wiki/obras/O Céu e o Inferno.md` — doutrina vs. penas eternas; "o porvir e o nada"; exemplos mediúnicos
- `wiki/obras/A Gênese.md` — teoria dos fluidos, cosmogonia, milagres
- `wiki/obras/Obras Póstumas.md` — criada (nova); biografia, Flammarion, comunicações da missão
- `wiki/autores/Allan Kardec.md` — enriquecida com dados biográficos das Obras Póstumas
- `wiki/conceitos/Reencarnação.md` — Q.166–196 completos com citações diretas
- `wiki/conceitos/Escala Espírita.md` — Q.97–101 completos com subdivisões
- `wiki/conceitos/Perispírito.md` — Q.93–95 completos + fluido universal (A Gênese)
- `wiki/temas/Caridade como Lei.md` — Q.886–893 com citações; São Vicente de Paulo; lema espírita

**Arquivos copiados para raw/**: todos os 7 PDFs

---

## [2026-05-03] setup | Inicialização do wiki

**Operação**: Configuração inicial do LLM Wiki para Espiritismo.

**Arquivos criados**:
- `CLAUDE.md` — schema e instruções para o Claude
- `index.md` — índice de páginas
- `log.md` — este arquivo
- `wiki/overview.md` — síntese geral inicial
- Estrutura de diretórios: `wiki/autores/`, `wiki/conceitos/`, `wiki/obras/`, `wiki/temas/`, `wiki/centros/`
- Páginas stub para todas as entidades, conceitos, obras, temas e centros listados no índice

**Estado**: Wiki inicializado com estrutura base. Nenhuma fonte externa ingerida ainda. Todas as páginas são stubs com conteúdo inicial baseado no conhecimento do modelo.

**Próximos passos sugeridos**:
1. Ingerir as Obras Básicas de Kardec (especialmente O Livro dos Espíritos)
2. Ingerir obras mediúnicas brasileiras prioritárias
3. Adicionar fontes de pesquisa acadêmica sobre o Espiritismo no Brasil
