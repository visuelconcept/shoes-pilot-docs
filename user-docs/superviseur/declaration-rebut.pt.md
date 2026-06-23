# Declarar uma sucata

<span class="role-badge">Supervisor</span>

Regra geral, o **supervisor** retoma a operação em curso no terminal para
registar as rejeições. Três tipos:

| Tipo | Código | Significado |
|------|:----:|---------------|
| Par | **P** | Ambos os sapatos estão defeituosos |
| Esquerdo | **G** | Esquerdo defeituoso → o direito vai para o stock de reintegração |
| Direito | **D** | Direito defeituoso → o esquerdo vai para o stock de reintegração |

!!! note "Quem declara as rejeições?"
    Por defeito, só o **supervisor** (ou o admin) regista as rejeições. Nas
    operações configuradas para tal, o **operador** pode declará-las ele próprio,
    diretamente a partir do seu apontamento.

## Adicionar a sucata

1. Secção **Sucatas** → **Adicionar**.

    <figure class="screenshot terminal" markdown>
    ![Secção Sucatas](../assets/screenshots/pt/rebut-section.png)
    <figcaption>Secção Sucatas durante o apontamento</figcaption>
    </figure>

2. Escolha o **tipo** (G / D / P).

    <figure class="screenshot terminal" markdown>
    ![Tipo de sucata](../assets/screenshots/pt/rebut-type.png)
    <figcaption>Tipo: esquerdo, direito ou par</figcaption>
    </figure>

3. Defina a **quantidade** e escolha o **motivo**.

    <figure class="screenshot terminal" markdown>
    ![Quantidade e motivo](../assets/screenshots/pt/rebut-motif.png)
    <figcaption>Quantidade e motivo</figcaption>
    </figure>

4. Toque em **Adicionar a sucata**. Os contadores são atualizados.

    <figure class="screenshot terminal" markdown>
    ![Sucata adicionada](../assets/screenshots/pt/rebut-ajoute.png)
    <figcaption>Contadores atualizados</figcaption>
    </figure>

!!! info "Recuperação automática"
    Para uma sucata **G** ou **D**, o sapato válido oposto vai automaticamente
    para o stock de reintegração: poderá reconstituir um par mais tarde (mesmo
    OF, mesmo tamanho). A saída mantém-se sempre em **pares completos**.
