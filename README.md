# Transmissão de vídeos
São scripts feitos para oferecer uma interface de utilização no terminal.

As ferramentas usam o [invidious](https://github.com/omarroth/invidious), plataforma de acesso aos vídeos do youtube simples e objetiva, burlando bloqueios regionais e por idade, aumenta a tua privacidade e evita as taxações de relevância arbritárias da plataforma original.

__Pesquisa__:
>script em python que usa __requests__ e __BeautifulSoup4__ para buscar e filtrar vídeos.

* Dependências:

>python3-bs4, python3-requests, python3-colorama

__Transmissao__:
> script em shell que pede link de transmissão para o invidious e abre direto num player

* Dependências:

> sed, curl, proxychains4, mplayer