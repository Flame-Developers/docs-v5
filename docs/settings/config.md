У каждого сервера есть свой список настроек, которые отвечают за мелкие и не очень нюансы. Например, у Вас есть возможность заставить бота скрывать ранее отключенные Вами команды от других, перестать на них отвечать, либо просто изменить стиль ошибок. Для этого, можно вызвать команду `config` с указанием необходимого Вам параметра в качестве первого аргумента:
```
f.config <Параметр>
```

## Список параметров
| Параметр  |      Отвечает за...      |
|----------|:-------------:|
| `clearCommandCalls` |  удаление вызываемых сообщений. |
| `deleteUserAfterLeave` | удаление пользователей из локальной базы сервера при выходе.   |
| `answerOnDisabledCommands` | ответы на ранее отключенные на сервере команды. |
| `hideDisabledCommands` | скрытие раннее отключенных на сервере команд из общего списка. |
| `embedErrorMessages` | использование эмбед-сообщений в сообщениях об ошибках. |