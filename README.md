# 🪟 Windows Command Notes
> 🪟 Fun fact: The new Windows logo looks like an actual window — finally living up to its name!
## Use of `findstr`

- `findstr` is similar to Linux's `grep` — it searches for strings or substrings in output.
- It works well with pipelines.

```cmd
tasklist | findstr office
