# regex

This code matches all lines that don't begin with ECHO and REM:

```
^(?!(?:ECHO|REM)).*\s*
```
