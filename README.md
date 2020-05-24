# vim-spell-eu

Euskarazko hiztegia vim-eko zuzentzailearentzako.

```
:set spell spelllang=eu
```

Ohiko moduan, hitz baten gainean kurtsorea dagoelarik sakatu `z=` iradokizunak ikustarazteko.

Instalatzeko
===========

Vim-en:
```
mkdir -p ~/.vim/spell/
wget https://github.com/gkobeaga/vim-spell-eu/raw/master/eu.utf-8.spl -P ~/.vim/spell/
```

Neovim-en:
```
mkdir -p ~/.config/nvim/spell/
wget https://github.com/gkobeaga/vim-spell-eu/raw/master/eu.utf-8.spl -P ~/.config/nvim/spell/
```

Hiztegia berreraikitzeko
=======================

Vim-eko zuzentzaileak erabiltzen duen *spl* fitxategia, Hunspell-eko *aff* eta *dic* fitxategiak erabiliz eraiki da.  Berreraiki hiztegia bakarrik beharrezkoa bada (eguneratzeko adibidez), izan ere prozesu oso astuna da. Gutxi gora-behera lau egun behar dira *spl* fitxategia sortzeko.

```
git clone https://github.com/gkobeaga/vim-spell-eu
cd vim-spell-eu
vim
:silent mkspell eu eu_ES
```

Hunspell-eko fitxategiak, *aff* eta *dic*, [Xuxen](http://xuxen.eus/static/hunspell/xuxen_5.1_hunspell.zip) proiektutik hartuta daude.
