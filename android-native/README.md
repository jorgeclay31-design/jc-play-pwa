# JC PLAY — projeto Android/PWA

Base inicial do aplicativo JC PLAY com interface azul-marinho, azul elétrico e turquesa.

## O que já está incluído
- Tela de acesso com URL, usuário e senha.
- Cadastro, seleção e remoção de vários servidores no aparelho.
- Campo separado para URL M3U/M3U8.
- Layout responsivo e configuração inicial para Capacitor/Android.

## Gerar o projeto Android
Requisitos: Node.js LTS e Android Studio com Android SDK instalado.

1. Extraia o ZIP.
2. Abra um terminal na pasta `JC-PLAY`.
3. Execute `npm install`.
4. Execute `npm run android:init` (gera a pasta nativa `android`).
5. Execute `npm run android:sync`.
6. Execute `npm run android:open`.
7. No Android Studio, aguarde a sincronização do Gradle e use **Build > Build Bundle(s) / APK(s) > Build APK(s)**.

## Importante
Este pacote é um ponto de partida funcional de interface, não um APK final. A autenticação Xtream Codes, importação/parsing de playlists, categorias, EPG e reprodução ainda precisam ser conectados e testados com uma API/playlist autorizada do provedor. O botão Conectar ainda não declara autenticação bem-sucedida. As credenciais salvas no navegador/localStorage são locais e não devem ser consideradas armazenamento seguro para distribuição comercial; antes de publicar, migrar para armazenamento seguro nativo e revisar a política de privacidade.
