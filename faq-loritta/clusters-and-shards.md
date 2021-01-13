title: "Clusters e shards"
---
Sharding é separar várias instâncias do Discord, para que várias instâncias possam controlar servidores diferentes.

Por padrão o Discord faz com que todos os bots que estão em mais de 2500 servidores precisem usar shards. Cada shard pode controlar, no máximo, 2500 servidores (se você tem um bot e ele não faz sharding, ele não poderá ser adicionado em mais de 2500 servidores).

Uma shard seria como se você abrisse o Discord novamente, só que cada novo "Discord aberto" possuísem servidores diferentes.

O Sharding é usado para diminuir o "peso" de um bot nos servidores do Discord, e também é vantajoso para bots, já que cada shard tem um rate limit diferente, causando menos problemas relacionados a isso.

Clusters são conjuntos de shards. No momento, eu tenho o total de 16 clusters! Você pode ver todas elas usando o comando `+ping clusters`. Use apenas `+ping` para saber em qual seu servidor se encontra. Não é possível escolher qual cluster ou shard é a do seu servidor.

## Coisas que os Clusters influenciam no meu funcionamento

* [Bom Dia & Cia](/extras/faq-loritta/bomdiaecia);
* Comandos e mensagens que envolvem emoji;
* Instabilidades (eu posso ficar instável em um servidor e estar funcionando normalmente em outro devido ao sistema de clusters).


