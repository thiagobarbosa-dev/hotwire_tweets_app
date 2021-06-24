# Como usar o Hotwire com o Ruby On Rails

### Projeto construído baseando-se no tutorial:

[Como usar o Hotwire com o Ruby on Rails](https://onebitcode.com/como-usar-o-hotwire-com-o-ruby-on-rails-passo-a-passo/)
by: OneBitCode

### O que é o Hotwire?

O coração do Hotwire é a gem Turbo. Um conjunto de técnicas complementares, para acelerar a navegação das páginas e envios de formulários, dividindo páginas complexas em componentes e transmitindo atualizações parciais das páginas através do WebSocket (o qual consiste em ActionCable, Channels e Streaming Data).

Tudo isso com a possibilidade de não escrever nenhum JavaScript, apenas se for necessário escrever algum código customizado e para esse caso usaremos o Stimulus que torna isso muito fácil com uma abordagem centrada em HTML para estados e navegação entre a rede (wire) e que foi projetado desde o início para se integrar perfeitamente com aplicativos híbridos nativos para iOS e Android.

### O que criamos?

Uma aplicação web responsiva para se adequar as telas de computador e celular aonde poderemos criar, visualizar, atualizar, dar like e retweetar o tweet se igualando quase a uma SPA sem sacrificar velocidade e capacidade de armazenamento das respostas usando Rails com Hotwire.