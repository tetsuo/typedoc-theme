# typedoc-theme

my custom typedoc theme.

```
npm install @tetsuo/typedoc-theme
```

# usage

Generate single-page documentation with `typedoc`:

```
typedoc \
	--name '$NAME' \
	--theme $TYPEDOC_THEME_DIR \
	--out $OUTDIR \
	--readme $README_FILE \
	--mode file \
	--jsx react \
	--includeDeclarations \
	--excludePrivate \
	--excludeNotExported \
	--excludeExternals \
	--exclude '**/test/**' \
	$SRCDIR"
```