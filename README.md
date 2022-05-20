###Procedimentos para instalacao de aplicativos em um MAC novo

1. Instalar o brew, abra o terminal e execute o comando

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`


2. Baixe o arquivo brewfile

`git clone https://github.com/saadmarcelo/Mac-setup.git`


3. execute o comando a seguir para instalar os programas

`brew bundle install`



###Extra:
Caso queira exportar seu proprio brewfile
`brew bundle dump --file=~/.private/Brewfile`