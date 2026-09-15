# Fractal Control Theory

Teoria de Controle Fractal - Conectando álgebra abstrata, teoria de filas e criptografia.

## Papers Publicados (Zenodo)

| # | Paper | DOI | Licença |
|---|-------|-----|---------|
| 1 | Algebraic Side-Channel: Queue-Based Cryptanalysis of Finite-State Tracking Hardware | [10.5281/zenodo.22776445](https://doi.org/10.5281/zenodo.22776445) | CC BY-NC 4.0 |
| 2 | The Analytic Bridge: Connecting Abstract Algebra to Queueing Performance | [10.5281/zenodo.22776554](https://doi.org/10.5281/zenodo.22776554) | CC BY-NC 4.0 |
| 3 | The Algebraic Bullwhip Effect: Cascaded Queueing Networks with Algebraic Obstructions | [10.5281/zenodo.22777185](https://doi.org/10.5281/zenodo.22777185) | CC BY-NC 4.0 |
| 4 | Non-Abelian Expansions: Extending Fractal Control Theory to S_n | [10.5281/zenodo.22777334](https://doi.org/10.5281/zenodo.22777334) | CC BY-NC 4.0 |
| 5 | Simple Analytic Bridge: An Accessible Introduction to Fractal Control Theory | [10.5281/zenodo.22777446](https://doi.org/10.5281/zenodo.22777446) | CC BY-NC 4.0 |

## Sobre

Este projeto estabelece uma conexão formal entre:
- **Álgebra Abstrata** (grupos quocientes, Z₂³)
- **Teoria de Filas** (M/M/1)
- **Criptografia** (ataques de canal lateral)
- **Monitoramento de Silício** (diagnóstico de microchips)

A "Ponte Analítica" é o teorema central: obstruções algébricas causam inflação de latência mensurável através do fator de amplificação ρ/(1-ρ).

## Eixos de Pesquisa

| Eixo | Título | Foco |
|------|--------|------|
| 1 | Ponte Analítica | Fundação matemática |
| 2 | Bullwhip Algébrico | Amplificação em cascata |
| 3 | Não-Abelianos | Grupos simétricos S_n |
| 4 | Canal Lateral | Ataques baseados em latência |
| 5 | Relaxamento Estocástico | Comportamento sob saturação |
| **6** | **Silício** | **Monitoramento de microchips** |

## Resultados Principais

1. Qualquer mapeamento de Z₂³ para 6 estados produz erro mínimo E ≥ 1/12
2. O erro dinâmico E₆* = 1/6 devido ao Teorema de Lagrange
3. Sob carga ρ = 0.99, erro amplifica para 93.65% de atraso
4. Oráculo de inversão extrai taxa de erro interna
5. **Aplicação em Silício:** Protocolo de monitoramento não destrutivo para microchips

## Aplicação em Silício (Eixo 6)

O Eixo 6 extende a Ponte Analítica para **monitoramento de microchips**:

- **Detecção de defeitos** em fabricação
- **Monitoramento de envelhecimento** do chip
- **Segurança de hardware** contra comprometimento

**Fórmula Central:**
$$P_{99}^{chip}(\rho) = P_{99}^{ideal} \cdot \left(1 + \frac{\rho}{1-\rho} \cdot \epsilon^2\right) + O(\epsilon^4)$$

## Direitos Autorais

© 2026 Euzébio Soares. Todos os direitos reservados.

Este projeto é licenciado sob CC BY-NC 4.0.
Uso comercial requer autorização escrita.
Contato: euambiente@gmail.com

## Contato

- **Autor:** Euzébio Soares
- **Email:** euambiente@gmail.com
- **GitHub:** ebiossanto
