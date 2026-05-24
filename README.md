# CLEAR × TCE-ES · Mini-guia de práticas em M&A

> **Convênio nº 00017/2024-4C** · FGV CLEAR e Tribunal de Contas do Estado do Espírito Santo
> *Mapeamento de experiências nacionais e internacionais em monitoramento e avaliação de políticas públicas*

Versão web navegável do mapeamento produzido por **Cecília Florentino e Lorena Figueiredo** (FGV CLEAR, dezembro/2025). Reúne 17 experiências — brasileiras e internacionais — organizadas em cinco categorias analíticas, pensado para inspirar a construção de sistemas de M&A em municípios capixabas.

🔗 **Site:** https://caiodesouzacastro.github.io/clear-mini-guia-ma/

## As cinco categorias analíticas

| # | Categoria | Casos |
|---|---|---|
| **01** | Institucionalização e governança | Belo Horizonte, Recife, São Paulo, Sobral, Minas Gerais |
| **02** | Planejamento, desenho e qualidade | Minas Gerais, Rio Grande do Sul, Austrália |
| **03** | Capacidades e cultura de M&A | Ceará, Espírito Santo, Reino Unido, Portugal |
| **04** | Produção, gestão e acesso a dados | Florianópolis, Fortaleza, São Paulo, Bahia, França |
| **05** | Uso de evidências na tomada de decisão | Brasil (federal), Canadá, Chile |

## Como o conteúdo se distribui

- **Home** com manifesto, cards das 5 categorias e tabela síntese dos 17 casos
- **5 páginas de categoria**, cada uma com introdução editorial (`insight box`) + fichas estruturadas dos casos
- **Página de metodologia** com fontes, glossário e referências
- **PDF original** disponível para download em todas as páginas

A versão web acrescenta moldura editorial em torno do conteúdo original (introduções, linha de leitura, síntese comparativa) sem alterar o conteúdo das fichas, que reproduzem fielmente o produto da Cecília e da Lorena.

## Estrutura do repositório

```
clear-mini-guia-ma/
├── index.html                    ← portal + tabela comparativa
├── institucionalizacao/index.html
├── planejamento/index.html
├── capacidades/index.html
├── dados/index.html
├── uso/index.html
├── sobre/index.html              ← metodologia e referências
├── assets/
│   ├── css/style.css
│   ├── js/
│   └── pdf/mapeamento-completo.pdf
├── README.md
└── LICENSE
```

## Como rodar localmente

```bash
git clone https://github.com/caiodesouzacastro/clear-mini-guia-ma.git
cd clear-mini-guia-ma
python3 -m http.server 8000
# abra http://localhost:8000
```

## Como publicar no GitHub Pages

1. Suba o repositório para o GitHub.
2. Settings → Pages → Source: `main` / `(root)`.
3. Aguarde alguns minutos e acesse `https://<usuario>.github.io/clear-mini-guia-ma/`.

## Créditos

- **Autoria do mapeamento:** Cecília Florentino e Lorena Figueiredo · FGV CLEAR · Dezembro/2025
- **Desenvolvimento web:** FGV CLEAR
- **Referências fundamentais:**
  - OCDE (2025) — *Implementation Toolkit for the OECD Recommendation on Public Policy Evaluation*
  - FGV CLEAR (2025) — *Diagnóstico dos sistemas de avaliação de políticas públicas no Brasil*

## Licença

- **Código:** MIT — veja [LICENSE](LICENSE).
- **Conteúdo do mapeamento e textos editoriais:** CC BY 4.0 — atribuição obrigatória ao FGV CLEAR / TCE-ES.

---

*Para mais protótipos e bens públicos do FGV CLEAR:*
- [Painel CLEAR](https://caiodesouzacastro.github.io/painel-clear/)
- [Radar de Políticas Municipais](https://caiodesouzacastro.github.io/radar-politicas-municipais/)
- [Teorias de Mudança Setoriais](https://caiodesouzacastro.github.io/clear-tdms-municipais/)
- [CLEAR Lab Prototypes](https://caiodesouzacastro.github.io/clear-lab-prototypes/)
