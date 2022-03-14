# .dotfiles

### Repository klónozása

	git clone https://github.com/szabopeter1/.dotfiles.git ~/.dotfiles

### Szimbolikus linkek létrehozása a config fájlokhoz:

##### Kitty

	ln -s -f ~/.dotfiles/kitty.conf ~/.config/kitty/kitty.conf

##### Rofi

	ln -s -f ~/.dotfiles/config.rasi ~/.config/rofi/config.rasi

##### Vim

	ln -s -f ~/.dotfiles/.vimrc ~/.vimrc

##### Xterm

	ln -s -f ~/.dotfiles/.Xresources ~/.Xresources

*Az Xresources fájl betöltése és összefűzése*

	xrdb -merge ~/.Xresources

