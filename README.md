
**Websploit**
====
<p align="center">
  <img width="410" height="410" src="https://github.com/websploit/images/raw/master/websploit.png">
</p>


Websploit is a high level MITM framework


Installation
------------

Manual install via git :

```bash
$ git clone https://github.com/websploit/websploit.git
$ cd websploit
$ python -m pip install requirements.txt
$ python websploit.py
```

install via `apt` coming soon ...

Menu


Select module :

```bash
wsf > use arp_spoof
```

with `options` command you can see options of current module:

```bash
wsf > arp_spoof > options
```

Change options with `set` command:

```bash
wsf > arp_spoof > set target 192.168.1.24
```


Finally run module via `execute` command:

```bash
wsf > arp_spoof > execute
```

Meta
----

