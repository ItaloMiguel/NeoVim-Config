# Configuração do NeoVim
- Uma pequena configuração que eu fiz, ela está bem básica. Caso queira testar copie o código e teste,

# Como instalar vim?
### OBS: Tutorial feito para distribuições Unix que já tenho um pouco de noção

- #### Ubunto:
        sudo apt update && sudo apt upgrade -y
        sudo apt install neovim -y

- #### Arch
        sudo pacman -Syu && sudo pacman -Sy -y
        sudo pacman -S neovim -y

# Onde colocar esses código?

- #### Utilize esse comando para criar as pastas e arquivo
        mkdir ~/.config/nvim
        cd ~/.config/nvim
        nvim init.vim
    - Depois que fizer isso é só cópiar o comando que existe no arquivo do repositorio

# Cole isso em seu terminal se você usa alguma distribuição linux

- #### Código para baixar as extenções e nvim completo sem trabalho
        sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'

### Créditos
- Curso da alura e alguns tutoriais na internet. Fiz isso apenas para adianta a vida das pessoas que querem usar vim e não sabe muito bem configurar ou esta com preguiça
    
