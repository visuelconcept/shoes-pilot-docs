# Configurar uma ordem de fabrico

<span class="role-badge">Admin</span> <span class="role-badge">Admin funcional</span>

Um **OF** é uma ordem de produção (modelo/cor, quantidades por tamanho).
Divide-se em **sub-OF** (os caixotes seguidos no terminal).

!!! info "OF importados do ERP"
    Em produção, os OF chegam do ERP (ficheiros XML PRIOS). A criação manual
    faz-se a partir de **Artigos** ou **Ordens de fabrico**.

## 1. Lista dos OF

Estado, prioridade e prazo de cada OF.

<figure class="screenshot" markdown>
![Lista dos OF](../assets/screenshots/pt/of-liste.png)
<figcaption>Ordens de fabrico</figcaption>
</figure>

## 2. Detalhe de um OF

Produto, distribuição por tamanho e lista dos sub-OF.

<figure class="screenshot" markdown>
![Detalhe de um OF](../assets/screenshots/pt/of-detail.png)
<figcaption>Detalhe: produto, tamanhos, sub-OF</figcaption>
</figure>

## 3. Gerar os sub-OF

Abra o detalhe e toque em **Gerar os sub-OF**: os lotes são criados de acordo com
a configuração de subdivisão.

<figure class="screenshot" markdown>
![Sub-OF gerados](../assets/screenshots/pt/of-sous-of.png)
<figcaption>Sub-OF gerados</figcaption>
</figure>

## Referenciais de negócio

A administração define o fluxo e os referenciais: **operações**, **linhas**,
**postos**, **equipas**, **modelos**, **motivos de sucata**, **etiquetas**…

<div class="grid" markdown>

<figure class="screenshot" markdown>
![Operações](../assets/screenshots/pt/admin-operations.png)
<figcaption>Operações</figcaption>
</figure>

<figure class="screenshot" markdown>
![Linhas de produção](../assets/screenshots/pt/admin-lignes.png)
<figcaption>Linhas de produção</figcaption>
</figure>

</div>
