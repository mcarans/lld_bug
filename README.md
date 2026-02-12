# lld bug reproduce

These commands produce working executable that can be run in a shell with `./oolite`:

```
ld.bfd @response.txt
mold @response.txt
```

This one produces a binary that gives a Segmentation fault:

```
ld.lld @response.txt
```
