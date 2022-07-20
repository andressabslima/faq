---
title: "Meus cupons fiscais não aparecem para serem impressos"
date: 2020-08-17T11:02:05+04:00
lastmod: 2020-08-17T11:02:05+04:00
weight: 3
draft: false
# search related keywords
keywords: ["cupom","sincroniza","eficaz","paf"]
---

Para que seja realizado o sincronismo dos cupons fiscais é necessário que você siga todo o passo a passo abaixo.

- Feche o Eficaz.

- Clique no menu Iniciar do seu sistema operacional e digite : services.msc aparecerá um aplicativo chamado "Serviços", clique para executa-lo.

![image example](services.png "Serviços")

![image example](abrindoservices.png "Abrindo")

- Procure pelos serviços IntegradorPAF / Firebird Guardian / Firebird Server e clique para reiniciar cada um dos serviços.

![image example](reiniciandoservicos.gif "Como fazer")

- Feito isso, basta abrir o eficaz novamente.

( Obs : As vendas serão sincronizadas de 30 em 30 segundos )
