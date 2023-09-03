# Dictionaries / Dicionários
If you're here you probably know Portuguese so... 

Dado à inexistência de Dicionários para Português de Portugal para o Vim eu decidi criar 2.
- Número de vezes que a palavra dicionario é dita: 18

# 0. Instalação
Escolhe o dicionário que preferes e copia-o para a pasta spell do vim. Esta está provavelmente em $HOME/.local/share/nvim/site/spell ou em $HOME/.config/nvim/spell.

Para selecionares o teu novo dicionário,

    :set spelllang=<nome_do_dicionário_sem_o_.utf-8.spell>

Para ativares/desativares o spellcheck,

    :set spell!


# 1. Dicionário Antigo (1913) 
Aqui podes encontrar a maneira como as palavras eram escritas em português do séc.XX, todas  as palavras aqui 
presentes estão no "Novo Dicionário da Língua Portuguesa" - Candido de Figueiredo (1913). 
Acessível através do site: https://dicionario-aberto.net/

Um agradecimento especial a toda gente que contribuiu para a criação e manutenção deste dicionário sem o
qual seria muito mais difícil ter acesso à Língua Portuguesa como era escrita há um século atrás.

# 2. Dicionário Natura (Atual) 
O Grupo Natura também desenvolve e mantém o seu dicionário para o Vim o qual recomendo, a não ser que pretenda controlar 
extamente quais as palavras que estão no dicionário. Nestes dicionários tem a versão pré e pós acordo ortográfico.
Consulte: https://natura.di.uminho.pt/download/sources/Dictionaries/vim/LATEST/

# 3. Dicionário costumizado - acordo ortográfico (2022)
Dicionário feito por mim com base na lista de palavras presente no trabalho de colaboração entre o Portal da 
Língua Portuguesa e o grupo Natura da Universidade do Minho.
Algumas alterações foram feitas nomeadamente acrescentar o "à", "é" e o "ó". 
Este é acessível através do site: https://natura.di.uminho.pt/download/sources/Dictionaries/wordlists/
Este dicionário serve apenas como exemplo para a criação de dicionários pessoais.

Instruções:

Abrir o Vim  e executar o código:

    :mkspell <nome_do_ficheiro_com_as_palavras>

Depois mudar o nome do ficheiro cirado para 
    
    mv <nome_do_ficheiro_com_as_palavras> <nome_do_ficheiro_com_as_palavras>.utf-8.spl

Depois basta carregar o dicionário.

# Agradecimentos

Queria agradecer a todos aqueles que investiram o seu tempo no desenvolvimento deste dicionários
nomeadamente o Portal da Língua Portuguesa, o Grupo Natura e todos os que trabalham no site Dicionário Aberto. 
Se acredita que algum dos ficheiros não deveria estar aqui.
Contacte-me em: dcoderultra@tutanota.com

# Links
- https://dicionario-aberto.net/
- http://www.portaldalinguaportuguesa.org/
- https://natura.di.uminho.pt/wiki/doku.php?id=projectonatura
- https://natura.di.uminho.pt/wiki/doku.php?id=dicionarios:main
- https://natura.di.uminho.pt/download/sources/Dictionaries/vim/LATEST/
- https://natura.di.uminho.pt/download/sources/Dictionaries/wordlists/