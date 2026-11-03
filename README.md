# silence-is-golden

A Raku program that prints `Silence is golden` when standard input is empty.
If any input is provided, including spaces or newlines, it prints nothing.

```sh
# No input: prints Silence is golden
raku silence-is-golden.raku < /dev/null

# With input: prints nothing
printf 'Hello\n' | raku silence-is-golden.raku
```
