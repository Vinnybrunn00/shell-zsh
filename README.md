# Configurando shell-zsh no Ubuntu

## git teste

![zshrc](https://user-images.githubusercontent.com/91799009/180929714-01493ae7-abdc-4e2a-a737-c3d772088183.png)

> Instalando o zsh do repositório oficial

```
sudo apt-get install zsh
```

> Tornando o shell-zsh padrão do sistema

```
sudo gedit /etc/passwd
```

Procure seu diretório home, no meu caso é:

```vinny:x:1000:1000:Vinícius Bruno,,,:/home/vinny:/bin/bash```

Agora troque "bash" por "zsh":

```vinny:x:1000:1000:Vinícius Bruno,,,:/home/vinny:/bin/zsh```

E salve!

> Ao fazer todos esses processo, clone o projeto na sua "Pasta Pessoal":

```
git cline https://github.com/Vinnybrunn00/shell-zsh.git
```

Depois de ter feito isso, encerre a sessão do seu Ubuntu e abra novamente o terminal!

