# Alias in bash terminal

## Creation
To create a alias it is simple:
Add to your ~/.bash_aliases:
```
alias myAlias="longStuffToReplace"
```

## Duplication
In the case we created an alias over an already existing cmd, we can use '\' to not use the alias.
Example:
```
alias top="htop"

...

$top --> result to htop
$\top --> result to top

