# Log do Wiki Espírita

Log cronológico de todas as operações: ingestões, queries arquivadas e revisões de saúde.
Formato de cada entrada: `## [YYYY-MM-DD] tipo | Descrição`

Para listar as últimas entradas rapidamente:
```
grep "^## \[" log.md | tail -10
```

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
