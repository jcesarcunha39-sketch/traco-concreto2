# Traço de Concreto — Android

Projeto Android nativo simples que empacota a aplicação HTML fornecida em um WebView local.

## O que já está incluído
- Nome do app: Traço de Concreto
- Orientação vertical
- HTML/CSS/JavaScript executado localmente
- Funcionamento sem depender do Netlify
- Botão voltar do Android
- JavaScript e armazenamento DOM habilitados

## Como gerar o APK
1. Abra esta pasta no Android Studio.
2. Aguarde a sincronização do Gradle.
3. Use **Build > Build APK(s)**.
4. O APK de debug será criado em `app/build/outputs/apk/debug/`.

O código da calculadora foi preservado a partir do HTML enviado. A tabela de dosagem usa os dados presentes no arquivo, incluindo resistências de 15, 20, 25, 30, 35 e 42 MPa e os três tipos de brita.
