# -10RegExp
# Форма валидации RegExp v1.0.1
## Демо-сайт проекта: https://timingtea.github.io/-10RegExp/

### Валидируемые поля:
* Имя (обязательное поле)
* E-mail
* Телефон
* Адрес сайта

### Для имени:
* только кириллица;
* первая буква заглавная;
* можно ввести от 2 до 20 символов — это можно задать в атрибутах minlength и maxlength;
возможна запись двойных имён — например Анна-Мария.
### Для e-mail:
* только латиница;
* «собака» @ — обязательный символ;
* точка . — тоже обязательный символ;
* цифры, подчерк, тире — разрешённые символы.

### Для телефона:
#### Шаблон для телефона должен находить номера в таких форматах:
* +7(925)900-90-90
* +7(925) 900-90-90
* +7 925-900-90-90
* +79259009090
* 89259009090

### Для сайта:
Адрес сайта должен:
* начинаться с http:// или https://;
* затем www. — это необязательная группа;
* IP-адрес — 255.255.255.255 или доменное имя — stasbasov.ru
* порт — тоже необязательная группа. Порт начинается с двоеточия, за которым идут от 2 до 5 цифр. Например: :8080;
* путь — последовательность из цифр, слешей и латинских букв, на конце которого может стоять решётка #.
