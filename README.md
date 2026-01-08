# Steam_Deck
Repositório para ajudar quem tem Steam Deck e quer usar o modo desktop.

# Códigos
Instalar Distrobox+Podman:
```sh
bash -c "$(curl -fsSL https://raw.githubusercontent.com/victoraalm/steam_deck/refs/heads/main/setup_distrobox%2Bpodman)"
```
Criar uma distro Arch (padrão ouro):
```sh
distrobox create --image docker.io/library/archlinux:latest --name arch --init --volume /:/hostos --home /home/deck/.local/share/podman-static/share/containers/homes/arch/ --hostname arch
```

Configurar rápidamente uma distro arch:
```sh
bash -c "$(curl -fsSL https://raw.githubusercontent.com/victoraalm/steam_deck/refs/heads/main/setup_distroArch)"
```
Recuperar/destravar podman (geralmente após atualizações da steamos):
```sh
bash -c "$(curl -fsSL https://raw.githubusercontent.com/victoraalm/steam_deck/refs/heads/main/recover_podman)"
```

