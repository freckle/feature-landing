# Make variant

- In Google Web Designer, use `File > New from template`
- Select `IBL` in `My templates`
- Edit as desired
- When satisfied, `File > Publish > Publish locally`
- Make sure to uncheck `Flatten Files` and to check `Minify`
- Name according to desired URL in `output` folder
- Publish

# Commit to git

```sh
git commit -am "Message goes here"
```

# Expose to the world

```sh
git subtree push --prefix output origin gh-pages
```
