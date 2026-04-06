# InstantSearch — универсальный сканер

**InstantSearch** — это кроссплатформенное приложение, объединяющее визуальный и аудиопоиск в одном интерфейсе. Разработано на Unity 6 с использованием URP и Sentis.

## Возможности

- 📷 Распознавание объектов через камеру (MobileNetV3 / YOLOv8 ONNX)
- 🎤 Распознавание аудио и музыки (Whisper tiny)
- 🌐 Встроенный браузер с результатами поиска (unity-webview)
- 🔒 Полностью локальная работа — без серверов и интернета
- 📱 Поддержка Android, iOS, Windows

## Технологии

| Компонент | Технология |
|-----------|------------|
| Движок | Unity 6000.4.0f1 (Unity 6) |
| Рендеринг | Universal Render Pipeline (URP) |
| AI | Unity Sentis (ONNX модели) |
| WebView | unity-webview (GREE, MIT) |
| Язык | C# |

## Установка и сборка

1. Установите Unity Hub и Unity 6000.4.0f1
2. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/Joldy9/InstantSearch.git
