# Supervisionar a produção

<span class="role-badge">Supervisor</span> <span class="role-badge">Admin</span>

Os painéis de controlo oferecem uma vista em tempo real da produção. Atualizam-se
automaticamente (a cada 15 a 30 segundos) e organizam-se em vários eixos de
análise.

## Vista global

O painel de controlo principal resume o dia: sub-OF **em curso**, operações
**concluídas hoje**, **pares produzidos** e **rejeições**, bem como um gráfico
de produção horária.

<figure class="screenshot" markdown>
![Painel de controlo global](../assets/screenshots/pt/dash-global.png)
<figcaption>Visão geral da produção do dia</figcaption>
</figure>

## Por operação

Acompanhamento de cada etapa do fluxo: sub-OF em espera e em curso em cada
operação.

<figure class="screenshot" markdown>
![Painel por operação](../assets/screenshots/pt/dash-operation.png)
<figcaption>Produção por operação</figcaption>
</figure>

## Por equipa

Desempenho de cada equipa e classificação dos operadores.

<figure class="screenshot" markdown>
![Painel por equipa](../assets/screenshots/pt/dash-equipe.png)
<figcaption>Desempenho por equipa</figcaption>
</figure>

## Por modelo

Estado da produção para cada modelo de calçado.

<figure class="screenshot" markdown>
![Painel por modelo](../assets/screenshots/pt/dash-modele.png)
<figcaption>Produção por modelo</figcaption>
</figure>

## Por linha

Desempenho de cada linha de produção, com filtros temporais.

<figure class="screenshot" markdown>
![Painel por linha](../assets/screenshots/pt/dash-ligne.png)
<figcaption>Desempenho por linha de produção</figcaption>
</figure>

**Filtros temporais disponíveis:**

| Filtro | Período abrangido |
|--------|------------------|
| Equipa em curso | Desde o início da equipa atual |
| Equipa anterior | A equipa anterior |
| Últimas 24 h | As últimas 24 horas |

**Indicadores por linha:** sub-OF ativas, em curso, concluídas, pares
produzidos, **eficiência** (saída / entrada × 100) e **taxa de rejeições**.

## Por operador

Classificação e indicadores individuais: pares produzidos, taxa de eficiência,
taxa de rejeições e comparação com a média da equipa.

<figure class="screenshot" markdown>
![Painel por operador](../assets/screenshots/pt/dash-operateur.png)
<figcaption>Desempenho por operador</figcaption>
</figure>

!!! info "Atualização em tempo real"
    Os painéis de controlo atualizam-se automaticamente via WebSocket. Em caso
    de ausência de atualização, verifique a ligação de rede do posto.
