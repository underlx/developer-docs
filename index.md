---
layout: default
---

Bem-vindo(a)!
Este é o ponto de partida para todos os que procuram contribuir para o desenvolvimento do [projeto UnderLX](https://underlx.com/about), ou que pretendem utilizar os recursos do UnderLX nos seus projetos.

# Documentação

 - **[API](./api)** - a API principal do UnderLX, utilizada principalmente pela aplicação Android, está documentada de acordo com a especificação OpenAPI versão 2 (também conhecida por Swagger 2.0), e pode ser usada pelo público em geral.

_Mais em breve_

# Código fonte

 - **[disturbancesmlx](https://github.com/underlx/disturbancesmlx)** - código fonte do servidor, responsável por:
   - aquisição de dados (consumidor de APIs e _scraper_ de páginas públicas);
   - funcionamento da [API](./api), incluindo comunicação em tempo real (MQTT e notificações [FCM](https://firebase.google.com/docs/cloud-messaging/));
   - site [Perturbações.pt](https://perturbacoes.pt);
   - [PosPlay](https://posplay.underlx.com);
   - Bot disponível no [servidor de Discord do UnderLX](https://perturbacoes.pt/discord).
 - **[underlx](https://github.com/underlx/underlx)** - código fonte da [aplicação Android](https://play.google.com/store/apps/details?id=im.tny.segvault.disturbances)
   - inclui o [S2LS](https://github.com/underlx/underlx/tree/master/s2ls/src/main/java/im/tny/segvault/s2ls) (Segvault Subway Location System), sistema especializado de localização do utilizador e de cálculo de rotas na rede de Metro.

O código fonte do projeto UnderLX está sob a licença [Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0).

## Componentes relacionados

À parte do UnderLX, existem componentes que foram desenvolvidos para utilização neste projeto:

 - [ankiddie](https://github.com/gbl08ma/ankiddie) - gestor de ambientes de execução de _scripts_ [anko](https://github.com/mattn/anko/) que oferece, entre outras coisas, uma solução integrada para _monkey patching_;
 - [chewup](https://github.com/gbl08ma/chewup) - gerador extremamente simples de sites estáticos, usado para gerir o [underlx.com](https://underlx.com)
 - [disduper](https://github.com/gbl08ma/disduper) - bot de Discord, integrável noutros bots, para desduplicação de mensagens (dos tempos em que o Discord facilmente duplicava mensagens enviadas em más condições de rede). Já não é utilizado no UnderLX.

# Dados abertos

Parte dos dados fornecidos pela [API](./api) e disponibilizados no [Perturbações.pt](https://perturbacoes.pt) são fornecidos pela [iniciativa de dados abertos do UnderLX](https://github.com/underlx/data).

Exceto se indicado em contrário, estes dados, assim como os restantes fornecidos pela API, são disponibilizados sob a licença [ODbL v1.0](https://opendatacommons.org/licenses/odbl/1-0/index.html).

# Discussão

Neste momento, toda a discussão em torno do desenvolvimento do projeto UnderLX ocorre no [nosso servidor de Discord](https://perturbacoes.pt/discord).

# Contactos

Para assuntos relacionados com o desenvolvimento do projeto, poderá contactar a equipa do UnderLX através dos [canais habituais](https://underlx.com/contact).