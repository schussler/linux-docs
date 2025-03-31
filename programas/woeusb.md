# WoeUSB

## Programa para criar pendrive bootaveis do windows utilizando o linux

### Intalação

```bash
yay -S woeusb-ng
```

# Erro no WoeUSB

## Mensagem:

`A instalação falhou! Erro: Incapaz de criar /media/woeusb_source...`

## Solução:

1.Verifique qual dispositivo deseja usar

```
  lsblk
```

2.Execute com `sudo`:

```bash
sudo woeusb --device /path/to/iso /dev/sdX
```
