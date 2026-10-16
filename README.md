# wacli-sborka

Сборка [openclaw/wacli](https://github.com/openclaw/wacli) (лицензия MIT) для AI-секретаря курса Protuz «Нейросети для бизнеса: эра AI-агентов».

Код wacli не меняется. Отличия от официальных выпусков только в сборке:
- macOS 12 и новее (официальные файлы требуют macOS 15), один универсальный файл для Apple Silicon и Intel;
- Windows x64 и Windows ARM64.

Файлы собираются из исходников авторов в GitHub Actions (`.github/workflows/sborka.yml`), к каждому выпуску прилагается `checksums.txt`. Новая версия wacli подхватывается автоматически раз в неделю.

Устанавливает и проверяет файл скрипт `SKRIPTY/wa_ustanovka.py` из пакета секретаря.
