# CodeVoice 🎙️

Editor de código em C controlado por voz, criado como parte de um **projeto de extensão** com foco em **acessibilidade para pessoas com deficiência física** (motora) em cursos de TI.

Autor: **Henrique**

## Objetivo

Muitas pessoas com deficiência motora enfrentam barreiras para digitar código no teclado convencional durante estudos e atividades de programação. O CodeVoice permite escrever código em C ditando comandos por voz — palavras-chave, símbolos e estruturas prontas da linguagem são reconhecidos e convertidos automaticamente em sintaxe válida.

## Como funciona

- O reconhecimento de voz roda direto no navegador (Web Speech API), sem precisar instalar nada.
- Basta clicar em **"Ditado por Voz"** (ou usar o atalho `Ctrl + Espaço`) e falar os comandos.
- Cada comando de voz é convertido no símbolo ou palavra-chave correspondente em C (ex: "comando inteiro" → `int`, "abre chaves" → `{`, "ponto e vírgula" → `;`).
- A lista completa de comandos disponíveis pode ser consultada a qualquer momento no botão **"Ajuda"**.

## Funcionalidades

- Ditado por voz contínuo, com realce de sintaxe em tempo real
- Botão para apagar a última linha
- Botão para limpar todo o editor
- Download do código escrito como arquivo `.c`

## Requisitos

- Navegador com suporte a reconhecimento de voz (recomendado: Google Chrome ou Microsoft Edge)
- Permissão de acesso ao microfone

## Tecnologias

- HTML, CSS (Tailwind) e JavaScript puro
- Web Speech API (`webkitSpeechRecognition`)

---

Projeto em desenvolvimento contínuo, com o objetivo de ampliar o acesso à programação para pessoas com deficiência física.
