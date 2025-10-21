# Mais Barato – Demonstração

🚫 **Este repositório é demonstrativo. O uso, cópia ou redistribuição sem autorização explícita é proibido.**  
© Mollitiam Development.

## Sobre o App

O **Mais Barato** é um aplicativo para comparação de preços de produtos, facilitando a escolha da melhor opção para o consumidor.  
Com ele, é possível adicionar produtos manualmente ou por leitura de código de barras, comparar preços por unidade de medida e salvar históricos de comparação.

## Funcionalidades Principais

- Adição de produtos manualmente ou por código de barras
- Comparação automática de preços por unidade
- Histórico de comparações realizadas
- Interface simples e intuitiva
- Modo escuro e configurações personalizáveis

## Technical Overview

- **Linguagem:** Swift
- **Framework:** SwiftUI
- **Arquitetura:** MVVM
- **Funcionalidades:** Leitura de código de barras, comparação de preços, histórico local, modo escuro
- **Integração:** API REST para consulta de produtos
- **Armazenamento:** Local e sincronização com nuvem (Supabase)

## Funcionamento do Scanner

- Scanner atualizado e otimizado (AVFoundation + SwiftUI)
- Consulta em 7 fontes de dados, com cache via Supabase
- Ordem de busca revisada e mensagem de resultado ajustada
- Fallback simples para adição manual quando não encontrado
- Estrutura de banco (Supabase) preparada para cache e histórico

## Fontes consultadas

1. Supabase (cache)
2. Open Food Facts
3. Open Products Facts
4. Open Pet Food Facts
5. Open Beauty Facts
6. UPCitemdb
7. Barcode Lookup

## 📱 Screenshots

### 1. Tela Inicial
<img src="screenshots/tela-inicial.png" width="300"/>

### 2. Escolha do Método de Entrada do Produto
<img src="screenshots/escolha-metodo.png" width="300"/>

### 3. Leitura do Código de Barras
<img src="screenshots/leitura-codigo-barras-1.png" width="300"/>
<img src="screenshots/leitura-codigo-barras-2.png" width="300"/>

### 4. Detalhes do Produto
<img src="screenshots/detalhes-produto.png" width="300"/>

### 5. Comparação de Preços
<img src="screenshots/comparacao-precos.png" width="300"/>

### 6. Comparação Realizada
<img src="screenshots/comparacao-realizada.png" width="300"/>

### 7. Configurações
<img src="screenshots/configuracoes.png" width="300"/>

### 8. Histórico
<img src="screenshots/historico.png" width="300"/>

---

## Baixe na App Store

[![App Store](https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg)](https://apps.apple.com/br/app/mais-barato/id6746170601?l=en-GB)

---

## Contato

Para mais informações, entre em contato:  
https://mollitiamdevelopment.great-site.net
