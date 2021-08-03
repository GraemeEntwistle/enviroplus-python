To run the Enviro to streamr feed:

```
python streamr-feed.py
```

Note only every second or third reading is streamed.

If you get a bunch of HTTP errors check that the publisher JS script is running.

Note also that CTRL/C does not appearto stop the pyhon script as advertised I have had to:

```
CTRL/Z
ps
kill -9 nnnnn
```
where nnnnn is the PID of the python script as displayed by the ps command.