---
title: "'CNPJ': O valor '' não é aceito para o padrão. '[0-9] {14}'"
date: 2020-05-18T11:02:05+04:00
lastmod: 2020-05-18T11:02:05+04:00
weight: 3
draft: false
# search related keywords
keywords: ["nfe","nota","fiscal","cnpj","padrão","erro"]
---

![image example](rejeicao.png "Erro CNPJ")
A SEFAZ de alguns estados (UFs) faz-se obrigatório o CNPJ da operadora da máquina de cartão para emitir NFe de vendas realizadas em cartão.

Esse erro geralmente ocorre quando a Operadora do Cartão não foi configurada corretamente na forma de pagamento que está sendo usada na venda.

Para correção, identifique a operadora na Forma de Pagamento da venda.

Após isso, busque e atualize a forma de pagamento na Filial Fiscal (Configurações > Rede > Configurações Fiscais e Financeira). 
![image example](configuracoes.png "Configurações Fiscais")
Ao clicar no botão EDITAR do PDV que deseja atualizar, clique na aba "Configuração das Formas de Pagamento" e selecione a operadora da(s) máquina(s) utilizada(s) neste PDV e salve.
![image example](forma-pagto-operadora.png "Operadora")

Por fim, realize o envio da nota novamente.