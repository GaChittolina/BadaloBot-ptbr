# Badalo Bot - Pt-Br
O Badalo Bot é um bot para o Discord que ajuda a manter as guildas limpas enquanto serve, também, como Bot de música. Ele exclui as próprias mensagens e as de outros bots, bem como as mensagens que os chamaram, 1 minuto depois de serem enviadas.

O Badalo Bot foi feito com a DiscordJS, uma API de JavaScript fácil de usar e intuitiva para o Discord.

A parte de música do Badalo Bot usa o discord.js-music, com algumas modificações.

O Badalo Bot pode ser adicionado ao seu canal aqui: [Me convide ao seu canal!](https://discordapp.com/oauth2/authorize?client_id=378358281858580490&scope=bot&permissions=8192)

Ele está hospedado no [Glitch](https://glitch.com) e usa o [UpTimeRobot](https://uptimerobot.com/) para ficar online 24/7.
___
## Comandos:
* ``$help``         : Exibe esta mensagem.
* ``$ordem``        : Limpa as últimas 100 mensagens em um canal de texto (mensagens que tenham sido enviadas há mais de 2 semanas não podem ser excluídas).
* ``$about``        : Sobre.
* ``$play``         : Reproduz a música com o nome ou url inseridos.
* ``$summon``       : Convoca o bot para o seu canal de voz.
* ``$disconnect``   : Desconecte o bot do canal de voz em que ele está.
* ``$skip [nº]``    : Pula determinado número de músicas. Pulará 1 música caso o número não seja especificado.
* ``$queue``        : Exibe a fila de músicas atual.
* ``$pause``        : Pausar a reprodução de música. (requer a permissão de gerenciar músicas).
* ``$resume``       : Retoma a reprodução de música. (requer a permissão de gerenciar músicas).
* ``$volume [nº]``  : Ajusta o volume de reprodução entre 1 e 200 (requer a permissão de gerenciar músicas).
* ``$clearqueue``   : Limpa a fila de músicas.
* ``$leave``        : Limpa a fila de músicas e sai do canal.
