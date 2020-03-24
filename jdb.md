# JDB

## start
```
jdb -attach localhost:port -sourcepath sourceDirectory 
```

## Control Flow
### Set breakpoint
```
stop in package.ClassName.method
```
```
stop at package.ClassName:lineNumber
```
### List breakpoints
```
clear
```
### Remove breakpoint
```
clear package.ClassName.method
```
```
clear package.ClassName:lineNumber
```

### Continue execution until next breakpoint
```
cont
```

### Display local variabies
```
locals
```

### Display object
```
print expression
```
### Display full object properties
```
dump expression
```
