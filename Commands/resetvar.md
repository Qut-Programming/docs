# Resetvar

#### Resets a variable's contents

## Info

#### Status: Deprecated
#### Values: 1
#### Returns: *[Deprecation Message](/Commands/resetvar.md?id=deprecation)*
###### *!before:* Value of variable before reset

## Code

### Usage
```qut
resetvar {value1}
```
### Example
```qut
INPUT:
set test\"test"
resetvar test
print test

OUTPUT:
You are not allowed to set Important Variables! (Line {line}, File '{filename}')
undefined
```

## Deprecation

#### This command will be removed in a future release as there is no purpose of the command

### Alternatives

```qut
(do nothing with the variable)
set {value1}\"undefined"
```
