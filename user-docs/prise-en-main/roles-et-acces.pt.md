# Funções e acessos

O Shoes Pilot distingue quatro perfis. A função determina os ecrãs acessíveis
e as ações autorizadas.

| Função | Painéis de controlo | Terminal de registo | Configuração |
|------|:---:|:---:|:---:|
| **Administrador** | ✅ | ✅ | ✅ |
| **Administrador funcional** | ✅ | — | ✅ (dados de negócio) |
| **Supervisor** | ✅ | ✅ | — |
| **Operador** | — | ✅ | — |

## O que faz cada função

=== "Operador"

    Trabalha exclusivamente no **terminal tátil**. Lê os contentores,
    regista o início e o fim das operações, declara as rejeições e reintegra
    os sapatos órfãos. Início de sessão por **crachá**.

=== "Supervisor"

    Acompanha a produção em tempo real através dos **painéis de controlo** (por
    operação, equipa, modelo, linha, operador) e pode utilizar o
    **terminal**. Não acede à configuração de negócio.

=== "Administrador funcional"

    Configura os **dados de negócio**: operações, linhas, postos, equipas,
    modelos, motivos de rejeição, modelos de etiquetas. Acede aos painéis de
    controlo mas **não ao terminal**.

=== "Administrador"

    Acesso completo: configuração, painéis de controlo, terminal e gestão dos
    **utilizadores**.

!!! info "Autenticação"
    As contas Administrador / Supervisor iniciam sessão com **identificador +
    palavra-passe** (token válido por 24 h). Os operadores iniciam sessão com
    **crachá** no terminal (token válido por 12 h).

## Contas de demonstração

| Identificador | Palavra-passe | Função |
|-------------|--------------|------|
| `admin` | `demo123` | Administrador |
| `functional` | `demo123` | Administrador funcional |
| `superviseur` | `demo123` | Supervisor |
| `operateur` | `demo123` | Operador |

Crachás de operadores de demonstração: `OP001` a `OP008`.
