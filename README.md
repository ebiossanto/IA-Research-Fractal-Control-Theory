# Teoria de Controle Fractal (FCT)

**Autor:** Euzébio Soares dos Santos
**Email:** euambiente@gmail.com

## Resumo

Esta pesquisa estabelece uma **ponte analítica** entre obstruções algébricas em grupos finitos e latência de cauda em sistemas de filas, através de quatro eixos interconectados.

## Os Quatro Eixos

### Eixo 1: A Ponte Analítica
- **Resultado:** $P_{99} = P_{99}^{\text{ideal}} \cdot (1 + \frac{\rho}{1-\rho} \cdot p^2)$
- **Insight:** Obstrução algébrica em $\mathbb{Z}_2^3$ determina penalidade de desempenho

### Eixo 2: Efeito Bullwhip Algébrico
- **Resultado:** $P_{99}^{(n)} = P_{99}^{(0)} \cdot \prod_{k=1}^{n} (1 + \frac{\rho_k}{1-\rho_k} \cdot p_k^2)$
- **Insight:** Erros se amplificam multiplicativamente em cascata

### Eixo 3: Expansões Não-Abelianas
- **Resultado:** $E_{S_n}^* = \frac{n!-2}{n!(n-1)} \to \frac{1}{n-1}$
- **Insight:** Grupos não-abelianos são 2× mais destrutivos que abelianos

### Eixo 4: Relaxamento Estocástico
- **Resultado:** $P_{99}(\text{PFA}) = P_{99}^{\text{ideal}} \cdot (1 + \sqrt{\rho} \cdot p^2)$
- **Insight:** Randomização destrói rigidez algébrica e protege o sistema

## Estrutura do Repositório

```
fractal-control-theory/
├── ponte_analitica/           # Paper 1
│   ├── main.tex
│   └── references.bib
├── bullwhip_effect/           # Paper 2
│   ├── main.tex
│   └── references.bib
├── nonabelian_expansion/      # Paper 3
│   ├── main.tex
│   └── references.bib
├── stochastic_relaxation/     # Paper 4
│   ├── main.tex
│   └── references.bib
├── PonteAnalitica4Eixos.md    # Documento consolidado (português)
├── email_prof_francisco.md    # Resumo para email
└── README.md                  # Este arquivo
```

## Como Compilar os Papers

1. Acesse [Overleaf](https://www.overleaf.com)
2. Crie um novo projeto
3. Faça upload dos arquivos `main.tex` e `references.bib`
4. Compile → PDF gerado

## Contato

**Euzébio Soares dos Santos**  
Pesquisador Independente  
euambiente@gmail.com
