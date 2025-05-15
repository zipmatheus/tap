# Data Processor TAP - Portabilidade

Este projeto é uma aplicação web simples desenvolvida para processar, organizar e classificar dados de portabilidade de forma eficiente. Ele é utilizado no contexto de migração de linhas telefônicas, separando os dados por status como "Aprovar", "Reprovar - CPF/CNPJ Diferente" e "Reprovar - Terminal Vago".

## 🚀 Funcionalidades

- Interface intuitiva e responsiva baseada em Bootstrap 5.
- Processamento de dados colados no formato tabulado (TSV).
- Classificação automática em 4 grupos:
  - **Aprovar**
  - **Reprovar - CPF Diferente (55)**
  - **Reprovar - CNPJ Diferente (57)**
  - **Reprovar - Terminal Vago (53)**
- Divisão de grandes volumes em grupos de até 200 registros.
- Botões para copiar rapidamente colunas específicas (TN, BP, CNL).
- Feedback visual para confirmação de cópia.

## 🧠 Como Funciona

1. O usuário cola os dados brutos no campo de texto.
2. Ao clicar em **"Processar Dados"**, os dados são analisados linha a linha.
3. Cada linha é classificada com base em palavras-chave e códigos de status.
4. Os dados classificados são exibidos em blocos com botões de cópia rápida.

## 📋 Exemplo de Entrada

Formato esperado (tabulado):

```
sistema	TN	BP	TNL	documento	...	status
```

Exemplo:
```
TAP	31999999999	123456789	ABC123	12345678901	REPROVADO CPF/CNPJ DIF - 98765432100
```

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3 (com Bootstrap)
- JavaScript (puro)
- Font Awesome (ícones)

## 📁 Estrutura

O projeto é composto por um único arquivo `index.html`, contendo:
- Layout (HTML)
- Estilo (CSS embutido)
- Lógica (JavaScript)

## 👨‍💻 Autor

Desenvolvido por **Matheus Barbosa**  
Portabilidade - Oi  
