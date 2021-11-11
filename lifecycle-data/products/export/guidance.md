---
title: Guia de exportação de dados do ciclo de vida
description: Exporte o guia de informação do ciclo de vida do produto
ms.date: 12/16/2020
layout: ContentPage
ms.openlocfilehash: 5e9dddbff5fac32e6d3cf8ef0943151d2dfe5e35
ms.sourcegitcommit: 6ea3221fd5475440480515f04f33988656d71748
ms.translationtype: HT
ms.contentlocale: pt-PT
ms.lasthandoff: 11/02/2021
ms.locfileid: "3546867"
---
# <a name="lifecycle-data-export-guidance"></a>Guia de exportação de dados do ciclo de vida
Este documento descreve como utilizar o ficheiro de exportação de produtos.

## <a name="query-information"></a>Informações sobre as consultas
No documento Excel, existem campos para ajudar a identificar os dados preenchidos na tabela de produtos.

### <a name="end-of-support"></a>Fim de Suporte
O valor de fim do suporte irá filtrar os produtos pela data de fim do produto ou pelas datas de fim de lançamento.

Valores possíveis: Tudo (sem filtro aplicado), Ano e um Intervalo.

### <a name="family"></a>Família
O valor da família filtra produtos pelo nível principal na hierarquia conhecida como família.

Valores possíveis: Tudo (sem filtro aplicado), Nome da Família

### <a name="group"></a>Grupo
O valor do grupo filtra os produtos dentro do nível principal (família) para um grupo específico.

Valores possíveis: Tudo (sem filtro aplicado), Nome do Grupo

## <a name="table-columns"></a>Colunas da tabela
A tabela de produtos consiste em colunas que definem o produto, edições, lançamentos e datas de suporte correspondentes.

> [!NOTE]
> Haverá uma linha para cada combinação de produto, edição e lançamento.

### <a name="product"></a>Produto
O nome do produto.

### <a name="edition"></a>Edição
A coluna da edição será preenchida quando o produto contiver edições. Quando não houver nenhuma edição de produto, este campo estará em branco.

### <a name="release"></a>Versão
A coluna de lançamento será preenchida quando o produto contiver múltiplos lançamentos.
Quando o produto tiver apenas um lançamento, este campo estará em branco.

### <a name="support-policy"></a>Política de Suporte
Este campo define a política de suporte que o produto segue.

Valores possíveis: [Fixo,](/lifecycle/policies/fixed) [Moderno](/lifecycle/policies/modern), Componente

### <a name="start-date"></a>Data de Início
Data de início do suporte do produto.

### <a name="mainstream-date"></a>Data base
Quando a Política de Suporte é **Fixa** ou **Componente**, esta é a data de fim base do produto.
  
Quando a Política de Suporte for **Moderna**, esta estará em branco.

### <a name="extended-end-date"></a>Data de fim alargada
Quando a Política de Suporte é **Fixa** ou **Componente**, esta é a data de fim alargada do produto.

Quando a Política de Suporte for **Moderna**, esta estará em branco.

### <a name="retirement-date"></a>Data da reforma
Quando a Política de Suporte for **Fixa** ou **Componente**, esta estará em branco.

Quando a Política de Suporte for **Moderna**, esta será a data de reforma do produto.

### <a name="release-start-date"></a>Data de início do lançamento
Data de inicio de suporte para o lançamento. Quando o produto tiver apenas um lançamento, este campo estará em branco.
 
### <a name="release-end-date"></a>Data de fim do lançamento
Data de fim do suporte para o lançamento.
Quando o produto tiver apenas um lançamento, este campo estará em branco.

### <a name="docs-url"></a>URL de docs
URL para documentação alargada.
