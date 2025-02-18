[View code on GitHub](https://dune.com/docs/query/DuneSQL-reference/SQL-statement-syntax/update.md)

## Update

The `UPDATE` section of the app technical guide covers the syntax, description, examples, and limitations of updating selected columns values in existing rows in a table. The `UPDATE` statement is used to modify the existing records in a table. 

The `Synopsis` section provides the syntax of the `UPDATE` statement, which includes the table name, the columns to be updated, and the `WHERE` clause to specify the rows to be updated. 

The `Description` section explains how the `UPDATE` statement works. It mentions that the columns named in the `column = expression` assignments will be updated for all rows that match the `WHERE` condition. It also explains that when the type of the expression and the type of the column differ, the usual implicit CASTs, such as widening numeric fields, are applied to the `UPDATE` expression values.

The `Examples` section provides some examples of how to use the `UPDATE` statement. The first example updates the status of all purchases that haven't been assigned a ship date. The second example updates the account manager and account assign date for all customers. The third example updates the manager to be the name of the employee who matches the manager ID.

The `Limitations` section mentions that some connectors have limited or no support for `UPDATE`. It advises users to see connector documentation for more details.

Overall, the `UPDATE` section of the app technical guide provides a comprehensive guide on how to use the `UPDATE` statement to modify the existing records in a table. It covers the syntax, description, examples, and limitations of the `UPDATE` statement.
## Questions: 
 1. What is the purpose of the `UPDATE` command in the context of this app?
- The `UPDATE` command is used to update selected columns values in existing rows in a table.

2. How are column update expressions evaluated when the type of the expression and the type of the column differ?
- When the type of the expression and the type of the column differ, the usual implicit CASTs, such as widening numeric fields, are applied to the `UPDATE` expression values.

3. Are there any limitations to the `UPDATE` command in this app? If so, where can the details be found?
- Yes, some connectors have limited or no support for `UPDATE`. Details can be found in the connector documentation.