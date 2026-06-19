# Manual de Boas Práticas do Docente da FEUP

Proposta de **Manual de Boas Práticas do Docente da FEUP** — listas de verificação
(*checklists*) para apoiar regentes e docentes na gestão e lecionação de unidades
curriculares.

A versão publicada está disponível em:
**https://feup-mc.github.io/manual-docente/**

## Estrutura do repositório

```
docs/
├── _config.yml            # configuração do GitHub Pages (Jekyll)
├── index.md               # o manual (fonte em Markdown)
└── assets/media/          # imagens (figura PDCA, logótipo)
```

## Como está publicado

O site é gerado automaticamente pelo **GitHub Pages** a partir da pasta `docs/`
na *branch* `main`. Para (re)ativar, caso necessário:

1. **Settings → Pages**
2. Em **Source**, escolher `Deploy from a branch`
3. *Branch*: `main` · pasta: `/docs`
4. Guardar. O site fica disponível em poucos minutos.

## Como editar

O conteúdo está em [`docs/index.md`](docs/index.md), em Markdown. Pode ser
editado diretamente no GitHub (botão ✏️) ou localmente. Cada item de *checklist*
usa a sintaxe `- [ ]`, que o GitHub apresenta como caixa de verificação.

Sugestões e correções podem ser propostas via *Issues* ou *Pull Requests*.

## Controlo de versões

A versão do documento está indicada no topo de `index.md` (atualmente **v0.10**).
Recomenda-se criar uma *tag*/*release* por versão aprovada (ex.: `v0.10`), para
manter um histórico claro de versões submetidas ao Conselho Pedagógico.
