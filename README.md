Test
====

```csharp
string sqlCommandString = "exec storedProcedureName";
if (parameter1 == "NULL")
  sqlCommandString = sqlCommandString + " @parameter1 = NULL";
else
  sqlCommandString = sqlCommandString + " @parameter1 = N'" + parameter1 + "'";
if (parameter2 == "NULL")
  sqlCommandString = sqlCommandString + ",  @parameter2 = NULL";
else
  sqlCommandString = sqlCommandString + ",  @parameter2 = N'" + parameter2 + "'";
    .
    .
    .
```

Test
