# Projeto original

Esse projeto é um fork do CID: https://sourceforge.net/projects/c-i-d/ 

Agradecimentos pelo excelente trabalho ao Eduardo Moraes https://sourceforge.net/u/emoraes25/profile/


# Features
1. Lixeira.
2. Vetos para arquivos.
3. Auditoria samba.

# Instalar CID + Customização.
- Debian
```
    sudo apt-get update && \
        apt-get install wget -y && \
        [ -d /etc/apt/keyrings ] || sudo mkdir -m0755 -p /etc/apt/keyrings && \
        wget -O /etc/apt/keyrings/cid-archive-keyring.pgp https://c-i-d.sourceforge.io/keys/cid-archive-keyring.pgp && \
        wget -O /etc/apt/sources.list.d/cid.sources https://c-i-d.sourceforge.io/repo/apt/debian/cid.sources && \
        apt update && \
        apt install cid -y && \
        wget https://github.com/auguzsto/cid/archive/refs/tags/1.05.tar.gz && \
        sudo tar -xvf 1.05.tar.gz && \
        sudo cp -r cid-1.05/* /usr/share/cid/ && \
        sudo systemctl restart cid
```

# Instalar customização.
```
    sudo apt-get install wget && \
        wget https://github.com/auguzsto/cid/archive/refs/tags/1.05.tar.gz && \
        tar -xvf 1.05.tar.gz && \
        sudo cp -r cid-1.05/* /usr/share/cid/ && \
        sudo systemctl restart cid
```