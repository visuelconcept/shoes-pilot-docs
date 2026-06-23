# Declarar uma rejeição

<span class="role-badge">Operador</span>

Durante um registo, o operador pode declarar uma ou várias peças não conformes.
O sistema distingue **três tipos** de rejeição e desencadeia automaticamente a
recuperação do sapato válido sempre que possível.

## Os três tipos de rejeição

| Tipo | Código | Significado |
|------|:----:|---------------|
| **Par completo** | P | Ambos os sapatos (esquerdo + direito) estão defeituosos — sem recuperação |
| **Esquerdo** | G | Apenas o sapato esquerdo está defeituoso → o **direito** vai para o stock de reintegração |
| **Direito** | D | Apenas o sapato direito está defeituoso → o **esquerdo** vai para o stock de reintegração |

## Declarar a rejeição

1. Durante o registo, na secção **Rejeições**, clique em **Adicionar**.

    <figure class="screenshot terminal" markdown>
    ![Secção Rejeições](../assets/screenshots/pt/rebut-section.png)
    <figcaption>Secção Rejeições durante o registo</figcaption>
    </figure>

2. Selecione o **tipo**: G, D ou P.

    <figure class="screenshot terminal" markdown>
    ![Escolha do tipo de rejeição](../assets/screenshots/pt/rebut-type.png)
    <figcaption>Escolha do tipo de rejeição (esquerdo, direito, par)</figcaption>
    </figure>

3. Ajuste a **quantidade** com os botões +/− e selecione o **motivo**.

    <figure class="screenshot terminal" markdown>
    ![Quantidade e motivo](../assets/screenshots/pt/rebut-motif.png)
    <figcaption>Quantidade e motivo de não conformidade</figcaption>
    </figure>

4. Clique em **Adicionar a rejeição**.

    <figure class="screenshot terminal" markdown>
    ![Rejeição adicionada](../assets/screenshots/pt/rebut-ajoute.png)
    <figcaption>Contadores atualizados após a adição da rejeição</figcaption>
    </figure>

## Recuperação automática

Quando é declarada uma rejeição **Esquerdo** ou **Direito**:

- o sapato defeituoso é contabilizado como rejeição;
- **o sapato oposto (válido) é automaticamente adicionado ao stock de
  reintegração**;
- poderá servir mais tarde para reconstituir um par (mesma OF / mesmo tamanho).

!!! example "Exemplo"
    Declara **1 rejeição Esquerdo** (motivo: defeito no couro) num lote de
    10 pares. O sapato **direito** correspondente vai para o stock de
    reintegração. Noutro lote, uma rejeição Direito poderá ser compensada
    reintegrando esse direito — reconstituindo assim um par completo.

## Cálculo das quantidades

O sistema garante que a **quantidade de saída está sempre em pares
completos**:

```text
Entrada : 10 pares
- Rejeições de pares   : -2
- Rejeições esquerdos  : -1  (→ 1 direito ao stock)
- Rejeições direitos   : -1  (→ compensado por reintegração)
+ Reintegrações        : +1 direito
= Saída : 7 pares
→ Stock de reintegração : +1 direito restante
```

> A reintegração dos sapatos órfãos é objeto de um percurso dedicado,
> adicionado posteriormente.
