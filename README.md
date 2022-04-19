# These are the commands to clear the config - to save your config - and if you want to enter your config
This is how you clear the config
```
erase startup-config
reload
```
This is how you save your config in flash
```
wr
copy running-config flash:/"name" 
```
And this is how you enter your config
```
copy flash:/"name" start-up config
reload
```
