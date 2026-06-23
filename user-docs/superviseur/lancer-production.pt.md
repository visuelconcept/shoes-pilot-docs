# Lançar a produção de um OF

<span class="role-badge">Supervisor</span> <span class="role-badge">Admin</span>

Lançar um OF desencadeia a **impressão das etiquetas de caixote** e disponibiliza
os caixotes ao **primeiro posto** da linha. A fazer depois de gerar os sub-OF do
OF.

```mermaid
graph LR
  A[Abrir o OF] --> B[Iniciar o OF]
  B --> C[Impressão das etiquetas de caixote]
  C --> D[Caixotes disponíveis no 1.º posto]
```

## 1. Abrir o OF

Na administração, abra as **Ordens de fabrico** e selecione o OF a lançar.

<figure class="screenshot" markdown>
![Lista dos OF](../assets/screenshots/pt/of-liste.png)
<figcaption>Ordens de fabrico</figcaption>
</figure>

## 2. Iniciar o OF

No detalhe do OF, toque em **Iniciar o OF**. Os sub-OF passam a produção e as
**etiquetas de caixote são impressas** automaticamente.

<figure class="screenshot" markdown>
![Detalhe de um OF](../assets/screenshots/pt/of-detail.png)
<figcaption>Detalhe do OF: ação Iniciar</figcaption>
</figure>

!!! warning "Sub-OF necessários"
    Se ainda não existir nenhum sub-OF, gere-os primeiro a partir do detalhe do
    OF (ação **Gerar os sub-OF**).

## 3. Disponibilização no primeiro posto

Coloque em cada caixote a respetiva etiqueta impressa. Os caixotes ficam então
**disponíveis no primeiro posto de trabalho**: o operador pode
[iniciar a primeira operação](../operateur/demarrer-operation.md).

<figure class="screenshot" markdown>
![Sub-OF gerados](../assets/screenshots/pt/of-sous-of.png)
<figcaption>Caixotes (sub-OF) prontos para a produção</figcaption>
</figure>
