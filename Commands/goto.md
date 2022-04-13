# Goto

#### Goes to the line specified and carries on the script from there

## Info

#### Status: Added
#### Values: 1
#### Returns: *null*
###### *!before:* `value1`
###### *!gotoline:* The line after the goto command

## Code

### Usage
```qut
goto {value1}
```
### Example
```qut
INPUT:
goto "3"
print "This line will never be executed!"
print "Skipped line 2"

OUTPUT:
Skipped line 2
```