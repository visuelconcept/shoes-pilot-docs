# Exportar os relatórios de produtividade

<span class="role-badge">Admin</span>

Exporte o desempenho dos operadores num período, em formato CSV.

## 1. Abrir o dashboard de operadores

Menu **Dashboard → Por operador**. Escolha o **período** no topo da página
(por defeito: últimos 7 dias).

<figure class="screenshot" markdown>
![Dashboard por operador](../assets/screenshots/pt/export-dashboard.png)
<figcaption>Desempenho por operador e seletor de período</figcaption>
</figure>

## 2. Exportar

Toque em **Exportar CSV**. O ficheiro
`performance_operateurs_<de>_<até>.csv` é descarregado.

<figure class="screenshot" markdown>
![Botão Exportar CSV](../assets/screenshots/pt/export-bouton.png)
<figcaption>Exportação CSV do período selecionado</figcaption>
</figure>

!!! info "Conteúdo do ficheiro"
    O CSV contém dois níveis:

    - **Síntese por operador**: pares bons, rejeições, taxa de rejeição,
      rentabilidade.
    - **Detalhe diário**: por dia, operador, posto, operação e equipa.

!!! tip "Filtrar antes de exportar"
    O campo de pesquisa (crachá, nome, posto, equipa) filtra a apresentação no
    ecrã; a exportação considera o **período** selecionado.
