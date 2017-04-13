docker-ubuntu-xfce-vnc-desktop
=========================

### From Docker Repository

``
$ docker pull welkineins/ubuntu-xfce-vnc-desktop
``

### Build yourself

```bash
$ git clone git@github.com:acsalu/docker-ubuntu-xfce-vnc-desktop.git
$ docker build --rm -t acsalu/docker-ubuntu-xfce-vnc-desktop docker-ubuntu-xfce-vnc-desktop
```

### Run

```bash
$ docker run -d -t -p 5900:5900 4022:22 acsalu/ubuntu-xfce-vnc-desktop
```

Use vnc viewer to <YOUR IP>:5900 or ssh into <YOUR IP>:4022


Trobleshooting
==================
You can find logs under /var/log/ in container.

