Mymax-Ubuntu-Keyboard-Layout
============================

Layout Português Brasileiro para Teclado Soft Multimídia, da Mymax. Este projeto visa corrigir o posicionamento das teclas na instalação do teclado Soft Multimídia da Mymax em sistemas operacionais Linux derivados da distro Debian. Este projeto não possui vinculo com a empresa Mymax nem intenciona adquirir qualquer ganho financeiro relacionado. Este projeto foi criado para facilitar a vida dos usuários leigos de sistemas operacionais derivados da distro Linux Debian.

Usabilidade:
1 – Acesse o diretório /usr/share/X11/xkb/symbols
	cd /usr/share/X11/xkb/symbols/

2 – Altere o nome do arquivo com o script de configuração do layout Português Brasileiro (br)
	sudo mv br br_backup

3 – Crie um novo arquivo 'br'
	sudo touch br

4 – Edite o arquivo 'br' e adicione o script 'br' do projeto (copiando e colando) no novo arquivo
	sudo gedit br
5 – Salve o novo arquivo com o scritp e reinicie o computador. 
