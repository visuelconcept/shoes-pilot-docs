# Configurar uma ordem de fabrico

<span class="role-badge">Admin</span> <span class="role-badge">Admin funcional</span>

Uma **ordem de fabrico (OF)** representa uma encomenda de produção para um
modelo/cor, com quantidades por tamanho. Subdivide-se em **sub-OF** (lotes)
para um acompanhamento granular no terminal.

!!! info "OF importadas do ERP"
    Em produção, as OF são **importadas do ERP** (ficheiros XML PRIOS,
    pasta monitorizada) e associadas ao respetivo artigo do catálogo. A criação
    manual faz-se a partir da página **Artigos** ou **Ordens de fabrico**.

## 1. Lista das ordens de fabrico

A página **Ordens de fabrico** lista as OF com o respetivo estado, prioridade e
prazo.

<figure class="screenshot" markdown>
![Lista das ordens de fabrico](../assets/screenshots/pt/of-liste.png)
<figcaption>Lista das ordens de fabrico</figcaption>
</figure>

## 2. Detalhe de uma OF

A página de detalhe apresenta as **informações do produto** (com fotografia), a
**distribuição por tamanho** e a lista das **sub-OF** com o respetivo estado.

<figure class="screenshot" markdown>
![Detalhe de uma ordem de fabrico](../assets/screenshots/pt/of-detail.png)
<figcaption>Detalhe de uma OF: produto, tamanhos e sub-OF</figcaption>
</figure>

## 3. Gerar as sub-OF

Se estiver definida uma **configuração de subdivisão**, abra o detalhe da OF e
clique em **Gerar as sub-OF**: o sistema cria automaticamente os lotes
segundo as regras (pares por sub-OF, pontos de rutura, etc.).

<figure class="screenshot" markdown>
![Sub-OF geradas](../assets/screenshots/pt/of-sous-of.png)
<figcaption>Sub-OF geradas a partir da OF</figcaption>
</figure>

## Ecrãs de configuração de negócio

A administração permite definir o fluxo de produção e os referenciais.

=== "Operações"

    Defina as etapas do fluxo (código, sequência, duração estimada, controlo
    de qualidade obrigatório).

    <figure class="screenshot" markdown>
    ![Administração das operações](../assets/screenshots/pt/admin-operations.png)
    <figcaption>Configuração das operações</figcaption>
    </figure>

=== "Linhas de produção"

    Agrupe as operações por zona física, defina a ordem e a linha
    predefinida.

    <figure class="screenshot" markdown>
    ![Administração das linhas](../assets/screenshots/pt/admin-lignes.png)
    <figcaption>Configuração das linhas de produção</figcaption>
    </figure>

## Outros referenciais

A configuração de negócio abrange também: **postos de trabalho**, **equipas**,
**operadores**, **modelos**, **configurações de subdivisão**, **motivos de
rejeição**, **impressoras** e **modelos de etiquetas**. Cada um segue a mesma
lógica: lista, criação, edição, desativação (eliminação suave).
