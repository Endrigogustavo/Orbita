# Órbita — app Android

O app completo (offline, sem CDN) está em `www/index.html`.

## Opção A — APK automático pelo GitHub (sem instalar nada)
1. Crie um repositório no GitHub e envie esta pasta inteira (inclua a pasta `.github`).
2. Abra a aba **Actions** → "Build APK" roda sozinho (~5 min).
3. Baixe o artefato **orbita-apk** → `app-debug.apk`.
4. No celular: abra o arquivo e permita "instalar apps desconhecidos".

## Opção B — no seu computador
Requisitos: Node 18+, JDK 17 e Android Studio (SDK).
```
npm install
npx cap add android
npm run apk
```
APK gerado em `android/app/build/outputs/apk/debug/app-debug.apk`.
Para abrir no Android Studio: `npm run open`.

## Demo
- ana@orbita.com · PIN 1234
- bruno@orbita.com · PIN 4321
- carla@orbita.com · PIN 1111 (bloqueada)
- Código do gerente: 0000
