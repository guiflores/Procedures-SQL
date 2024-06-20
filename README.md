# README - Procedures em SQL

## Introdução
As procedures (ou procedimentos armazenados) em SQL são conjuntos de comandos SQL que podem ser executados como uma única unidade. Elas permitem a automação de tarefas repetitivas, encapsulamento de lógica de negócio e melhoria de performance através de compilação antecipada.

## Benefícios das Procedures
- **Reutilização de Código:** Procedures podem ser chamadas repetidamente sem a necessidade de reescrever o código.
- **Segurança:** Permitem o controle de acesso aos dados.
- **Performance:** Compilação antecipada e cache de planos de execução.
- **Manutenção:** Facilita a manutenção e atualização do código SQL.

## Sintaxe Básica

### Criar uma Procedure
```sql
CREATE PROCEDURE nome_da_procedure (parâmetros)
BEGIN
    -- Corpo da procedure
    -- Comandos SQL
END;
```

### Chamar uma Procedure
```sql
CALL nome_da_procedure(parâmetros);

