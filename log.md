# Log do Wiki Espírita

Log cronológico de todas as operações: ingestões, queries arquivadas e revisões de saúde.
Formato de cada entrada: `## [YYYY-MM-DD] tipo | Descrição`

Para listar as últimas entradas rapidamente:
```
grep "^## \[" log.md | tail -10
```

---

## [2026-05-03] criação | Páginas individuais volumes 2–13 da Série André Luiz

**Operação**: Criação de 12 páginas individuais para os volumes 2–13 da *Coleção A Vida no Mundo Espiritual*, a partir dos textos extraídos anteriormente em `/tmp/al_02_*` a `/tmp/al_13_*`.

**Fontes consultadas**: textos extraídos via pdftotext de todos os 13 PDFs da série André Luiz (já ingeridos em sessão anterior). Leitura de índices completos, prefácios de Emmanuel, capítulo 1, temas centrais.

**Páginas criadas** (12 novas):
- `wiki/obras/Os Mensageiros.md` — vol. 2; 51 caps.; prefácio Emmanuel (Pedro Leopoldo, 26 fev. 1944); Aniceto; obsessão; prece
- `wiki/obras/Missionários da Luz.md` — vol. 3; 20 caps.; prefácio (13 mai. 1945); psicógrafo, epífise, vampirismo, obsessão, passes
- `wiki/obras/Obreiros da Vida Eterna.md` — vol. 4; 20 caps.; prefácio (25 mar. 1946); zonas de erraticidade; Jerônimo
- `wiki/obras/No Mundo Maior.md` — vol. 5; 20 caps.; prefácio (25 mar. 1947); Eusébio; psiquiatria iluminada; Calderaro
- `wiki/obras/Libertação.md` — vol. 6; 20 caps.; parábola do peixinho vermelho; perseguidores invisíveis
- `wiki/obras/Entre a Terra e o Céu.md` — vol. 7; 40 caps.; prefácio (23 jan. 1954); Irmã Clara; reencarnação (caps. 29–31)
- `wiki/obras/Nos Domínios da Mediunidade.md` — vol. 8; 30 caps.; prefácio (3 out. 1954); Áulus; psicofonia; possessão; fascinação
- `wiki/obras/Ação e Reação.md` — vol. 9; 20 caps.; prefácio (1 jan. 1957); karma; Mansão Paz; Druso
- `wiki/obras/Evolução em Dois Mundos.md` — vol. 10; 40 itens em 2 partes; prefácio (21 jul. 1958); Chico Xavier + Waldo Vieira; perispírito
- `wiki/obras/Mecanismos da Mediunidade.md` — vol. 11; Chico Xavier + Waldo Vieira; física quântica e ondulatória aplicada à mediunidade
- `wiki/obras/Sexo e Destino.md` — vol. 12; 28 caps. em 2 partes; prefácio (4 jul. 1963 Uberaba); Waldo Vieira (pt.1) + Chico Xavier (pt.2)
- `wiki/obras/E a Vida Continua.md` — vol. 13; 26 caps.; prefácio (18 abr. 1968 Uberaba); Evelina Serpa; centenário de A Gênese

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
- `wiki/entidades/Allan Kardec.md` — enriquecida (fontes:2→3): SPEE fundada 1º abril 1858, link para Revistas, comunicação póstumo, estatística de 1869
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
- `wiki/entidades/Emmanuel.md` — reescrita: identidade, obras filosóficas e históricas, estilo e perspectiva, citação do prefácio de 1937
- `wiki/obras/A Caminho da Luz.md` — NOVA: tabela de dados, índice completo de 25 caps., tese central, Jesus como Divino Escultor, Kardec na história universal, papel da América
- `wiki/obras/O Consolador.md` — NOVA: tabela de dados, estrutura em 2 partes, questão inicial (3 aspectos), Q&As selecionados (Q.1, Q.2, Q.9, Q.20, Q.21), comparação com *O Livro dos Espíritos*

**Arquivos copiados para raw/**: todos os 12 PDFs

---

## [2026-05-03] ingestão | 18 obras de André Luiz (G:\Meu Drive\_Espiritismo\Andre-Luiz)

**Operação**: Ingestão da Série André Luiz completa + obras complementares.

**Fontes processadas** (18 PDFs):
- Série principal: Nosso Lar, Os Mensageiros, Missionários da Luz, Obreiros da Vida Eterna, No Mundo Maior, Libertação, Entre a Terra e o Céu, Nos Domínios da Mediunidade, Ação e Reação, Evolução em Dois Mundos, Mecanismos da Mediunidade, Sexo e Destino, E a Vida Continua...
- Obras complementares: Desobsessão, Agenda Cristã, Sinal Verde, Conduta Espírita, Respostas da Vida

**Método**: Extração com pdftotext -enc UTF-8 → /tmp/andreluiz_txt/ (43.497 linhas total). Leitura de prefácios, índices e seções-chave de: Nosso Lar, Os Mensageiros, Missionários da Luz, Desobsessão, Mecanismos da Mediunidade, Nos Domínios da Mediunidade.

**Páginas atualizadas/criadas**:
- `wiki/obras/Nosso Lar.md` — enriquecida: cap.1 (umbrais), prefácio Emmanuel, mensagem André Luiz, tabela de capítulos, temas
- `wiki/obras/Série André Luiz.md` — reescrita: tabela corrigida com obras complementares, arco narrativo, volumes Waldo Vieira
- `wiki/entidades/André Luiz.md` — enriquecida: identidade, narrativa do personagem, citações diretas
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
- `wiki/obras/O Evangelho Segundo o Espiritismo.md` — Três Revelações, pluralidade dos mundos, a caridade
- `wiki/obras/O Livro dos Médiuns.md` — estrutura completa dos 32 capítulos, classificação dos médiuns, obsessão
- `wiki/obras/O Céu e o Inferno.md` — doutrina vs. penas eternas; "o porvir e o nada"; exemplos mediúnicos
- `wiki/obras/A Gênese.md` — teoria dos fluidos, cosmogonia, milagres
- `wiki/obras/Obras Póstumas.md` — criada (nova); biografia, Flammarion, comunicações da missão
- `wiki/entidades/Allan Kardec.md` — enriquecida com dados biográficos das Obras Póstumas
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
- Estrutura de diretórios: `wiki/entidades/`, `wiki/conceitos/`, `wiki/obras/`, `wiki/temas/`, `wiki/centros/`
- Páginas stub para todas as entidades, conceitos, obras, temas e centros listados no índice

**Estado**: Wiki inicializado com estrutura base. Nenhuma fonte externa ingerida ainda. Todas as páginas são stubs com conteúdo inicial baseado no conhecimento do modelo.

**Próximos passos sugeridos**:
1. Ingerir as Obras Básicas de Kardec (especialmente O Livro dos Espíritos)
2. Ingerir obras mediúnicas brasileiras prioritárias
3. Adicionar fontes de pesquisa acadêmica sobre o Espiritismo no Brasil
