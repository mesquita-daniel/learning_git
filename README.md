# Anotações sobre uso de git

## Certifique-se de ser reconhecido

Gere uma chave ssh no diretório .ssh

```console
cd ~/.ssh
ssh-keygen
```

Vá para https://github.com/settings/keys nova chave ssh e cole a saída do comando

```console
cat ~/.ssh/id_rsa.pub # Considerando que seguiu definições padrão
```

Depois faça:

```console
cat ~/.ssh/id_rsa.pub # Considerando que seguiu definições padrão
```

Vai receber mensagem de boas vindas.

## Fluxo normal

```console
# Adiciona git index ao projeto
git init 

# Adiciona tudo ao index
git add .

# Comita
git commit -m 'first commit'

# Adiciona repositório remoto
git remote add origin git@github.com:mesquita-daniel/coisas.git

# Sobe o conteúdo no branch master
git push -u origin master
```