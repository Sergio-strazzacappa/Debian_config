# Configuración de debian

## Indice

1. Git

## Git

### Instalar git

```bash
$ sudo apt install git
```

```bash
$ sudo apt install git-all
```

```bash
$ sudo apt install gcm
```

```bash
$ sudo apt install pass
```

### Configuración

Ver todas las configuraciones:

```bash
$ git config --list --show-origin
```

Configurar:

```bash
$ git config --global user.name "Sergio Strazzacappa"
$ git config --global user.email sergio.strazzacappa@est.fi.uncoma.edu.ar
$ git config --global credential.credentialStore gpg
$ git config --global init.defaultBranch=main
$ git config --global color.ai=auto
$ gpg --gen-key
$ pass init <gpg-id>
$ git config --global core.editor vim
```

Verificar la configuración:

```bash
$ git config --list
```
