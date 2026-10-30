# SendMail

App Android para escrever um e-mail e enviá-lo pelo aplicativo de e-mail do celular, feito em **Kotlin**.

> Projeto desenvolvido na faculdade, na disciplina de Programação para Dispositivos Móveis (PDM), em 2024.

## Funcionalidades

- Campos de destinatário, CC, CCO, assunto e mensagem
- Botão **Enviar**, que abre a lista de apps de e-mail instalados para concluir o envio
- Botão **Limpar**, que apaga todos os campos

## Tecnologias

- Kotlin
- Android SDK (mínimo API 21, alvo API 34)
- View Binding
- Intents implícitas (`ACTION_SENDTO` com `mailto:` e `ACTION_CHOOSER`)

## Como funciona

O app não envia o e-mail sozinho. Ele monta uma Intent com os dados preenchidos e pede ao Android para abrir um app de e-mail (Gmail, Outlook etc.), que faz o envio.

## Como rodar

1. Clone o repositório e abra no Android Studio.
2. Rode o app num celular ou emulador que tenha um app de e-mail configurado.
