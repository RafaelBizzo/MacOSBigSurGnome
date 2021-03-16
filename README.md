Um Tutorial Simples para transformar seu Gnome em MacOS Big Sur.

# Downloads

[Tema GTK](https://github.com/vinceliuice/WhiteSur-gtk-theme)

[Tema de Icones](https://www.gnome-look.org/p/1405756/)

[Tema do Cursor](https://www.gnome-look.org/p/1408466/)

# Instalação

## Tema GTK 

Clone o repositório, e rode:

```
sudo bash install.sh -g
```

## Tema de Icones e do Cursor

Descompactar e soltar os arquivos em `/usr/share/icons` como sudo.

## Aplicar tema do cursor no GDM

Abra o arquivo `/usr/share/themes/default/index.theme` como sudo e onde modifique:

```
[Icon Theme]
Inherits=macOSBigSur
```

# Configuração

Instalar o gnome tweaks no Ubuntu via:

```
sudo apt install gnome-tweaks
```

Abra o Firefox e vá para [Gnome Extensions](https://extensions.gnome.org/), instale a extensão do Firefox e depois instale duas extensões no site: User Themes, e Floating Dock

Abra o Extensions App e ative o Floating Dock e o User Themes, em seguida abra o Tweaks e vá em aparência e selecione o seguinte:

![](https://raw.githubusercontent.com/RafaelBizzo/MacOSBigSurGnome/main/src/Tweaks.png)

Agora vá na aba de Janelas e coloque a posição dos botões para a esquerda.

# Conclusão

Vale a pena utilizar o sistema dessa formal, bem parecido com MacOS. Repositório criado apenas para indexar links de Download.