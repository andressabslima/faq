---
title: "O mês ou o ano selecionado está divergente do período do extrato"
date: 2020-05-18T11:02:05+04:00
lastmod: 2020-05-18T11:02:05+04:00
weight: 3
draft: false
# search related keywords
keywords: ["contestacao","periodo","erro"]
---

![image example](rejeicao.png "Erro receita")
Motivo: O sistema faz a validação da coluna "S" no arquivo importado. Se a data do serviço lançado estiver fora do período estipulado para contestar, o sistema retornará o erro acima.

Solução: Faça a validação com referência as datas e realize a exclusão das linhas que estiverem fora do prazo em que deseja contestar. 
Após deixar apenas serviços efetivados no mesmo período em que está configurado, salve o arquivo e tente importá-lo novamente.