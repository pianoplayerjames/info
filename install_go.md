```cd ~```

```curl -OL https://golang.org/dl/go1.22.1.linux-amd64.tar.gz```

```sha256sum go1.22.1.linux-amd64.tar.gz```

```sudo tar -C /usr/local -xvf go1.22.1.linux-amd64.tar.gz```

```sudo nano ~/.profile```

```export PATH=$PATH:/usr/local/go/bin```

```source ~/.profile```
