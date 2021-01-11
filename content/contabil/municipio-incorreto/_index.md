---
title: "'cMun': O valor '' não é aceito para o padrão. '[0-9] {7}'"
date: 2020-05-18T11:02:05+04:00
lastmod: 2020-05-18T11:02:05+04:00
weight: 3
draft: false
# search related keywords
keywords: ["nfe","nota","fiscal","cMun","municipio","padrão","erro"]
---

![image example](rejeicao.png "Erro cMun")
Esse erro ocorre devido ao campo CIDADE do cadastro do cliente, constar um distrito e não o nome da cidade desse distrito.

Como distrito não tem código, ocorre este erro.

Para este caso é necessário alterar o campo informando a CIDADE "responsável" por este distrito. Por fim, deixe registrado o nome do DISTRITO no campo Complemento.
![image example](distrito.png "Exemplo")
