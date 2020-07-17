---
title: "'xLgr': O valor tem o tamanho '1'; deve ter o tamanho mínimo de '2'"
date: 2020-05-18T11:02:05+04:00
lastmod: 2020-05-18T11:02:05+04:00
weight: 3
draft: false
# search related keywords
keywords: ["nfe","nota","fiscal","xlgr","tamanho","erro"]
---

![image example](rejeicao.png "Erro xLgr")
Erro causado devido ao cadastro do cliente, nos campos RUA (Lgr = logradouro = Rua) ou BAIRRO, possuir somente 1 caractere.

Essa situação é rejeitada pela SEFAZ, sendo necessário cadastrar no mínimo 2 ou 3 caracteres dependendo do estado.

1. Para a Rua, verifique o nome oficial da rua, se é numeral (2) ou por extenso "DOIS".
    * Quando o nome oficial for numeral, adicione a palavra "Rua" ou "Bairro" conforme o campo a ser atualizado.
    * Caso o nome correto for "por extenso", corrigir a informação.

> Exemplos incorretos:
>
> Bairro: 3
>
> Rua: A

> Exemplos corrigidos:
>
> Bairro: Três
>
> Bairro: Bairro 3
>
> Rua: Rua A
