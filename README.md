# CheckUser GL

*CheckUser* E um verificador de usuários.

# Modo de instalação
```
apt-get update && apt-get install git -y
```
```
python3 -m pip install git+https://github.com/asas-dev-web/CheckUser/CheckUser.git
```
```
checkuser --create-service --config-port 5000 --start
```

### Ou
```
curl -sL https://raw.githubusercontent.com/CheckUser/install.sh > install.sh; chmod a+x install.sh; ./install.sh
```
 *Opcao 1*

# Atualização
```
python3 -m pip install --upgrade git+https://github.com/asas-dev-web/CheckUser.git
```

### Ou
```
curl -sL https://raw.githubusercontent.com/asas-dev-web/CheckUser/master/install.sh > install.sh; chmod a+x install.sh; ./install.sh
```
 *Opcao 2*

# Como usar
```
checkuser --help
```
