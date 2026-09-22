# Teoria de Controle Fractal (FCT)

## Sobre Este Projeto

> **Nota:** Estes trabalhos sao estudos de ideias desenvolvidos com ferramentas de inteligencia artificial. O autor e um estudante, entusiasta e pesquisador com um brinquedo nas maos.

**Ferramentas utilizadas:** Gemini MiMo V2.5, GPT 5.6 Copilot, Opencode

**Autor:** Euzébio Soares dos Santos — Estudante, entusiasta e pesquisador


**Autor:** EuzÃ©bio Soares dos Santos
**Email:** euambiente@gmail.com

## Resumo

Esta pesquisa estabelece uma **ponte analÃ­tica** entre obstruÃ§Ãµes algÃ©bricas em grupos finitos e latÃªncia de cauda em sistemas de filas, atravÃ©s de quatro eixos interconectados.

## Os Quatro Eixos

### Eixo 1: A Ponte AnalÃ­tica
- **Resultado:** $P_{99} = P_{99}^{\text{ideal}} \cdot (1 + \frac{\rho}{1-\rho} \cdot p^2)$
- **Insight:** ObstruÃ§Ã£o algÃ©brica em $\mathbb{Z}_2^3$ determina penalidade de desempenho

### Eixo 2: Efeito Bullwhip AlgÃ©brico
- **Resultado:** $P_{99}^{(n)} = P_{99}^{(0)} \cdot \prod_{k=1}^{n} (1 + \frac{\rho_k}{1-\rho_k} \cdot p_k^2)$
- **Insight:** Erros se amplificam multiplicativamente em cascata

### Eixo 3: ExpansÃµes NÃ£o-Abelianas
- **Resultado:** $E_{S_n}^* = \frac{n!-2}{n!(n-1)} \to \frac{1}{n-1}$
- **Insight:** Grupos nÃ£o-abelianos sÃ£o 2Ã— mais destrutivos que abelianos

### Eixo 4: Relaxamento EstocÃ¡stico
- **Resultado:** $P_{99}(\text{PFA}) = P_{99}^{\text{ideal}} \cdot (1 + \sqrt{\rho} \cdot p^2)$
- **Insight:** RandomizaÃ§Ã£o destrÃ³i rigidez algÃ©brica e protege o sistema

## Estrutura do RepositÃ³rio

```
fractal-control-theory/
â”œâ”€â”€ ponte_analitica/           # Paper 1
â”‚   â”œâ”€â”€ main.tex
â”‚   â””â”€â”€ references.bib
â”œâ”€â”€ bullwhip_effect/           # Paper 2
â”‚   â”œâ”€â”€ main.tex
â”‚   â””â”€â”€ references.bib
â”œâ”€â”€ nonabelian_expansion/      # Paper 3
â”‚   â”œâ”€â”€ main.tex
â”‚   â””â”€â”€ references.bib
â”œâ”€â”€ stochastic_relaxation/     # Paper 4
â”‚   â”œâ”€â”€ main.tex
â”‚   â””â”€â”€ references.bib
â”œâ”€â”€ PonteAnalitica4Eixos.md    # Documento consolidado (portuguÃªs)
â”œâ”€â”€ email_prof_francisco.md    # Resumo para email
â””â”€â”€ README.md                  # Este arquivo
```

## Como Compilar os Papers

1. Acesse [Overleaf](https://www.overleaf.com)
2. Crie um novo projeto
3. FaÃ§a upload dos arquivos `main.tex` e `references.bib`
4. Compile â†’ PDF gerado

## Contato

**EuzÃ©bio Soares dos Santos**  
Pesquisador Independente  
euambiente@gmail.com
