# SimpleHello — минимальный SwiftUI iOS проект

Пример простого приложения SwiftUI с одним экраном, показывающим "Hello, World!".

## Структура проекта

- SimpleHello.xcodeproj — Xcode проект
- SimpleHello/
   - ContentView.swift — код экрана
   - SimpleHelloApp.swift — точка входа
   - Info.plist — настройки бандла
- ExportOptions.plist — для экспорта IPA
- .github/workflows/build.yml — GitHub Actions workflow

## Сборка через GitHub Actions

Архив IPA автоматически собирается при push в ветку main на GitHub, используя macos-latest.

Получить собранный артефакт можно во вкладке Actions → соответствующий Workflow run → "iOS-IPA" artifact.
