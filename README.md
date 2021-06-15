Guia Acelerado de Estudo de Flutter
Introdução:
Ler a Linguagem Dart. Se não quiser ler tudo, pelo menos leia o básico e o tópico de Asynchrony support.
Fazer todos os 5 passos de Get started.
Procurar a sua plataforma de origem em "From another plataform" e ler como os conceitos da sua plataforma se relacionam com os conceitos de Flutter: Android e iOS.
Ler todos os itens dentro de Development > User Interface.
Pode pular Navigator 2.0, ele é algo bem recente e complexo, ainda precisa amadurecer um pouco. Talvez vamos usar, mas ainda não estou certo.
Ler esse artigo sobre Keys.
Ler dentro de Data & Backend:
State Management.
Networking & http.
Passem o olho rápido em Packages & Plugins.
Passem o olho rápido em Tools & Techniques.
Passem o olho rápido em Debugging Tools e Testing. Tem um material de testes em outros lugares. A maioria dos tópicos dentro dessa sessão são coisas que ninguém nunca usa porque a IDE faz tudo pra você.
Passem o olho rápido em Performance & Optimization.
Passem o olho bem rápido em Deployment, pra ter em mente como é o processo e as opções.
Médio:
Ler sobre as principais libraries de Dart. Só é bom passar o olho pra conhecer, mas é bom dar um foco maior na dart:async.
Ler rápido o guia de estilo de Dart. Ele se conflita um pouco com o de Flutter as vezes. O guia de estilo de Flutter é gigante, mas vale passar o olho nos exemplos. Esse é o guia do repo de Flutter, mas é interessante seguir ele em projetos que usam Flutter.
Estudar Futures e Streams.
Aprender sobre o RxDart.
Explorem o Catálogo de Widgets, ele é o seu "cinto de utilidades do Batman".
Vejam os videos do Widget of the Week.
Prefer using classes over functions to make a reusable widget-tree.
The build method should not trigger an http call or modify any state.
Ver o que são InheritedWidgets para entender melhor como funciona o Provider.
Ler a documentação do Provider. É importante ler essa documentação pois existem detalhes de implementação que podem impactar performance ou gerar bugs.
Ler a documentação do built_value. Como a própria documentação fala, tem um material adicional para entender o paradigma na página do AutoValue de Java, vale a leitura também.
Passar o olho rápido na documentação do quiver. A parte de strings é utilizada no projeto (isBlank, isNotBlank).
Ler cookbooks:
Websockets.
Store key-value data on disk. Só passar o olho rápido.
Ler sobre como funcionam os Slivers. É importante porque em alguns casos eles são melhores que uma ListView (ListView é uma abstração de Sliver).
Ler a documentação do test. Ela é enorme então não precisa ler tudo de uma vez, só precisa entender por alto como ele funciona. Aqui tem um Cookbook rápido sobre unit testing.
Ler a documentação do mockito. Ela é enorme então não precisa ler tudo de uma vez, só precisa entender por alto como ele funciona.
Ler sobre os novos Material Buttons e como funciona a migração.
Ler sobre as modificações em Theme.
Avançado (Extra - Não é necessário):
Ler sobre a arquitetura interna do Flutter.
Assistir How Flutter renders Widgets.
