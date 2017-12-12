## Vim

Delete all lines which contain the string `log`

```
:g/log/d
```

- `g` global command
- `log` pattern
- `d` the ex command delete

Delete all lines which not contain the string `log`

```
:g!/log/d
```