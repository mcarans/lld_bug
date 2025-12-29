These commands produce working executable that can be run in a shell with `./oolite`:

```
ld.bfd @response.txt
mold @response.txt
```

This one gives a Segmentation fault:

```
ld.lld @response.txt
```
# lld_bug
