# Schema do Wiki Espírita

Este arquivo define como o Claude deve operar e manter este wiki. Leia-o integralmente no início de cada sessão.

## Propósito

Este é um wiki pessoal sobre **Espiritismo** — a doutrina codificada por Allan Kardec, com ênfase no movimento espírita brasileiro, na literatura mediúnica, nas práticas e nos desdobramentos filosóficos e científicos da doutrina. O objetivo é acumular conhecimento de forma estruturada e interligada, não apenas arquivar fontes.

## Estrutura de Diretórios

```
wiki/
  entidades/     → Pessoas (codificadores, médiuns, pesquisadores) e espíritos mentores
  conceitos/     → Doutrinas, princípios, fenômenos, terminologia
  obras/         → Livros, palestras, séries mediúnicas
  temas/         → Temas transversais (reencarnação, mediunidade, caridade, etc.)
  centros/       → Organizações, federações, centros espíritas relevantes
  overview.md    → Síntese geral e estado atual do wiki
raw/
  assets/        → Imagens e arquivos de mídia (não modificar)
  (fontes brutas — imutáveis, nunca editar)
index.md         → Índice de todas as páginas do wiki
log.md           → Log cronológico de operações
CLAUDE.md        → Este arquivo (schema)
```

## Convenções de Páginas

### Frontmatter obrigatório
Toda página do wiki deve começar com:

```yaml
---
title: "Nome da Página"
type: entidade | conceito | obra | tema | centro | overview
tags: [lista, de, tags]
fontes: 0          # número de fontes que contribuíram para esta página
atualizado: YYYY-MM-DD
---
```

### Formatação
- Títulos com `#` para o título principal, `##` para seções
- Links internos com `[[Nome da Página]]` (formato Obsidian)
- Citações de fontes com `> "trecho"` seguido de `— *Fonte*, Autor`
- Contradições explicitadas em bloco `> [!warning] Contradição` 
- Lacunas de conhecimento em bloco `> [!question] Lacuna`

### Tamanho das páginas
- Entidades: 300–800 palavras
- Conceitos: 400–1000 palavras
- Obras: 300–700 palavras
- Temas: 500–1200 palavras
- Overview: sem limite, atualizar a cada ingestão significativa

## Operações

### INGESTÃO de nova fonte

Quando o usuário pedir para ingerir uma fonte:

1. **Ler** a fonte completa
2. **Discutir** com o usuário os pontos principais antes de escrever
3. **Escrever** página de resumo em `wiki/obras/` ou na categoria adequada
4. **Identificar** todas as entidades, conceitos e temas mencionados
5. **Atualizar** páginas existentes que sejam afetadas (adicionar informação, corrigir, anotar contradições)
6. **Criar** novas páginas para entidades/conceitos que ainda não existem
7. **Atualizar** `index.md` com todas as páginas novas ou modificadas
8. **Atualizar** `wiki/overview.md` com a síntese revisada
9. **Registrar** em `log.md` com formato: `## [YYYY-MM-DD] ingestão | Título da Fonte`

Ao final: listar todos os arquivos criados/modificados.

### QUERY (pergunta)

Quando o usuário fizer uma pergunta:

1. Ler `index.md` para identificar páginas relevantes
2. Ler as páginas relevantes
3. Sintetizar resposta com citações (`[[Página]]`)
4. **Oferecer ao usuário** a opção de arquivar a resposta como nova página no wiki
5. Se arquivado: registrar em `log.md`

### LINT (manutenção)

Quando o usuário pedir `/lint` ou revisão de saúde do wiki:

1. Verificar páginas órfãs (sem links de entrada)
2. Verificar contradições não resolvidas entre páginas
3. Verificar afirmações desatualizadas por fontes mais recentes
4. Identificar conceitos mencionados em múltiplas páginas que merecem página própria
5. Sugerir novas fontes a buscar para preencher lacunas
6. Registrar em `log.md`

## Domínio: Espiritismo

### Categorias de entidades a rastrear
- **Codificadores e pioneiros**: Allan Kardec, Leon Denis, Gabriel Delanne, Camille Flammarion
- **Médiuns brasileiros**: Chico Xavier, Divaldo Franco, Hercílio Maes, Mirabelli
- **Espíritos ditantes**: Emmanuel, André Luiz, Joanna de Ângelis, Bezerra de Menezes
- **Pesquisadores**: William Crookes, Oliver Lodge, Charles Richet

### Categorias de conceitos centrais
- Trilogia: Deus, Imortalidade da Alma, Comunicação dos Espíritos
- Fenomenologia: mediunidade, passes, desobsessão, cura espiritual
- Doutrina: reencarnação, carma, Lei de Causa e Efeito, Pluralidade dos Mundos
- Filosofia: evolucionismo espiritual, pluralidade das existências, escala espírita

### Obras de referência prioritárias (Obras Básicas do Espiritismo)
- *O Livro dos Espíritos* — Allan Kardec (1857)
- *O Livro dos Médiuns* — Allan Kardec (1861)
- *O Evangelho Segundo o Espiritismo* — Allan Kardec (1864)
- *O Céu e o Inferno* — Allan Kardec (1865)
- *A Gênese* — Allan Kardec (1868)

### Obras mediúnicas brasileiras de destaque
- Série *Nosso Lar* / André Luiz — psicografadas por Chico Xavier
- Série Emmanuel — psicografadas por Chico Xavier
- Série *Humberto de Campos* — Chico Xavier
- Série *Joanna de Ângelis* — Divaldo Franco

## Notas de estilo
- Escrever sempre em **português brasileiro**
- Usar "espírito" (minúsculo) para a entidade, "Espiritismo" (maiúsculo) para a doutrina
- Ao citar Kardec, preferir a tradução da FEB quando disponível
- Manter tom enciclopédico e neutro nas páginas do wiki; opiniões do usuário vão no log
- Não conflatar Espiritismo com Umbanda, Candomblé ou New Age — são distintos; se houver comparação, criar página de tema específica
