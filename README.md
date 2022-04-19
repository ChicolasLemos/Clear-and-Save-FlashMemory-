# These are the commands to clear the config - to save your config - and if you want to enter your config
This is how you clear the memory
```
erase startup-config
reload
```
Save your config in flash
```
wr
copy running-config flash:/"nome" (guardar)
```
If you want to enter your config
```
copy flash:/"nome" start-up config (abrir)
reload
```
