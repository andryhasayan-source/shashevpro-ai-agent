# История версий

[English below](#changelog-english)

Здесь отмечаются только изменения, заметные пользователю. Внутренние
правки и подробные разборы остаются в рабочей документации.

## 1.13.8 — текущая

Первая завершённая версия коммерческого продукта.

**Работа с документами**
- Word, Excel, PDF, PowerPoint
- Формулы Excel с русскими именами функций
- Заполнение фирменных бланков по меткам
- Презентации на фирменном шаблоне `.potx` заказчика
- Лендинги одним самодостаточным файлом
- Печать документов

**Голос**
- Полный офлайн-контур: распознавание, синтез, пробуждение по имени
- Отдельный чат для разговора вслух
- Автоматический выбор рабочего микрофона: петли записи и молчащие
  входы обходятся без участия человека

**Каналы**
- Telegram и MAX: тот же агент с телефона
- Публикация постов в канал
- Голосовые сообщения превращаются в наброски

**Данные и подключения**
- Почта (IMAP/SMTP), календарь по ссылке iCal
- База знаний по своим документам
- Наблюдение за своим сервером по SSH-ключу, только чтение
- Подключение внешних инструментов по протоколу MCP

**Безопасность**
- Три уровня риска с подтверждением по кнопке
- Белый список папок
- Обезличивание запросов с предпросмотром до отправки
- Журнал действий только на дописывание
- Шифрование ключей и паролей на компьютере

**Сборка и поставка**
- Две сборки: под процессор и с поддержкой видеокарты
- Портативная версия и установщик
- 522 автоматических теста

---

<a name="changelog-english"></a>

# Changelog (English)

Only user-visible changes are listed here. Internal work and detailed
post-mortems stay in the working documentation.

## 1.13.8 — current

The first complete release of the commercial product.

**Documents**
- Word, Excel, PDF, PowerPoint
- Russian Excel function names handled automatically
- Corporate templates filled in by placeholders
- Presentations built on the customer's own `.potx`
- Landing pages as a single self-contained file
- Document printing

**Voice**
- Full offline loop: recognition, synthesis, wake word
- Spoken conversations kept in their own chat
- Working microphone picked automatically; loopback and silent inputs
  are skipped without user involvement

**Channels**
- Telegram and MAX: the same agent from a phone
- Publishing posts to a channel
- Voice messages transcribed into notes

**Data and connections**
- Email (IMAP/SMTP), calendar via iCal link
- Knowledge base over your own documents
- Server monitoring over an SSH key, read-only
- External tools via the MCP protocol

**Security**
- Three risk levels with button confirmation
- Folder allowlist
- Request anonymisation with a preview before sending
- Append-only action journal
- Keys and passwords encrypted on the machine

**Build and delivery**
- Two builds: CPU-only and GPU-enabled
- Portable version and installer
- 522 automated tests
