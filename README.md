Example cookiecutter template demonstrating different handling of directories with `_copy_without_render`.

Expected behavior:

```
TBD/my_file.txt
TBD/so-good/not_rendered/not-rendered-file.txt
TBD/so-good/something.raw
```

Actual behavior:

```
TBD/{{ cookiecutter.app }}/not_rendered/not-rendered-file.txt
TBD/my_file.txt
TBD/so-good/something.raw
```
