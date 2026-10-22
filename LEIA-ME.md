# Rift Runner: APK pelo GitHub

1. Crie um repositório no GitHub (público ou privado).
2. Envie o CONTEÚDO desta pasta (não a pasta em si): `www/`, `package.json`, `capacitor.config.json`, `.gitignore`, `.github/` e `LEIA-ME.md`.
3. Aba **Actions** → **Build APK** → **Run workflow**.
4. Espere terminar (5 a 10 minutos). Quando ficar com ✅ verde, abra a execução.
5. Em **Artifacts**, baixe `rift-runner-apk` e extraia: dentro está `app-debug.apk`.
6. Passe o APK para o celular e instale. Se o Android pedir, libere "instalar apps desconhecidos" para o app que abriu o arquivo.

Para atualizar o jogo: troque `www/index.html` no repositório e rode o workflow de novo.

Observação: este APK é de teste (debug). Para a Play Store é preciso um APK/AAB assinado.
