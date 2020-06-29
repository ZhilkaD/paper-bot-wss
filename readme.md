### Бот / ферма для приложения Paper Scroll vk.com/app7420483

---
Поддерживает разные типов ботов (stealer, miner, infected, storage), автопокупка улучшений и бонусов, автозаражение топов, автоворовство, передача баланса цепочкой и тд.

Установка:
 - `git clone https://github.com/asyven/paper-bot-wss.git`
 - `npm install`
 - настроить `config.js`

Есть возможность запуска кластера (множества аккаунтов):
Переименовать `example.config.js` в `config.js` (там же и описание некоторых параметров) и настройте `config.js` после чего запустите `node cluster.js`

Или же 1 файл, но нужно указывать все параметры запуска с файла конфига:
`node index.js -id 123 -wss wss://paper-scroll.ru/socket?vk_acces... -role stealer`

Так же сделан дебандл минифицированного файла клиентской части, он находится `decode-fronted/dist/0.js`.

За основу подключения к сокетам взял `https://github.com/xTCry/VCoin`
А кластеризацию сделал на основе `https://github.com/xTCry/VCoin/pull/20`
Сделан за вечер, возможность бана - **огромная**, отслеживайте закономерность и улучшайте работу.

Вот профит за сутки с ботов в режиме stealer:
https://streamable.com/ek7f9c

Если будут вопросы - найти меня можете тут: `vk.com/asyven`
