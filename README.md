# Mucic Player

Um app de reprodução de áudio com a capacidade de executar arquivos locais e de uma nuvem(torrent?), além de acessar esta nuvem o usuário pode enviar seus arquivos de áudio locais para ter uma biblioteca sincronizada em diversos dispositivos. Os arquivos enviados para a nuvem são públicos e para uso de todos os usuários da mesma.


### Repositórios relacionados

* API: https://github.com/vineckb/music-player-api
* Mobile APP: https://github.com/vineckb/music-player-mobile
* Web APP: https://github.com/vineckb/music-player-webapp
* Landing page: https://github.com/vineckb/music-player-landing

## Roadmap

### Versão 1

Estrategicamente(preciso ter algo concreto em curto prazo), farei uma versão de stream de audio “closed caption”, semelhante ao spotify com as seguintes features:

* biblioteca de músicas, organizadas em playlists, artistas e álbuns
* criar, editar ou remover playlists
* adicionar músicas às playlists
* acesso a músicas do dispositivo, organizadas em artistas, álbuns e músicas
* adicionar músicas locais às mesmas playlists das músicas da plataforma
* enviar músicas para a nuvem
* sincronizar músicas enviadas para nuvem em outros dispositivos


### Versão 2

Esta será a versão final
Os arquivos de áudio serão distribuídos por em uma rede descentralizada suportada pelos próprios usuários 
A nuvem será construída pelos próprios usuários. Não existirá o servidor centralizado para as músicas, o usuário terá acesso a uma rede p2p. Todos os arquivos que o usuários sincronizar de seus dispositivos, serão inseridos à nuvem.

O conteúdo enviado pelos usuários será moderado e organizado de forma automatizada. Primeiramente o arquivo deve ser catalogado, isto é, identificar nome da música, artista e album. Após catalogação, deve associado a algum SEMELHANTE caso haja algum registrado na rede na rede, a fim de evitar duplicidade de conteúdo. Caso a música não tenha sido registrada previamente, será enviada para o serviço de moderação, que confirmará todas as informações da etapa de catalogação e levantará informações pendentes. A etapa de moderação também deve ser capaz de identificar e excluir arquivos de áudio não referentes a múscas.
