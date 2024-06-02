## Archive Telegram Chat

How do we archive a Telegram chat? Requirements:

- long-term storage
- technical simplicity
- ability to download messages, text, comments, media files, likes, status changes, etc.
- ability to store changes (likes over time, deleted messages, etc.)
- ability to search and view media/messages/likes in a web browser

## Technical solution

- [tg-archive](https://github.com/osintukraine/tg-archive)
  - works in a Docker container
  - saves messages in a SQLite database
  - saves media files in a directory
  - generates a static website with messages and media files
  - Problems: media files are not stored in the original format

## Institutes and organizations

These organisations in Zurich could be interested in archiving Telegram chats:

- [K-Set](https://www.k-set.net/)
- [Sozialarchiv](https://www.sozialarchiv.ch/)
- [feministisches Streikhaus](https://streikhaus.ch/)
