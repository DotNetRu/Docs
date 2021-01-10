# Добавление нового сообщества

Технически процесс добавления нового сообщества в DotNetRu связан с кучей мелких задач. Здесь они собраны в минимальном виде, чтобы ничего не забыть.

1. Сгенерировать [логотип](https://github.com/kulakovt/Boombr/blob/master/src/Brand/BrandBook.ps1)
1. Завести Сообщество в [Audit'е](https://github.com/DotNetRu/Audit) вместе с первым митапом
1. Добавить сообщество на [сайт](https://github.com/DotNetRu/Site) ([должен добавляться из Аудита](https://github.com/DotNetRu/Site/issues/7))
1. Создать поддомен Сообщества в [DNS](https://www.reg.ru/)
1. Обновить [wiki](https://github.com/DotNetRu/BrandBook/wiki)
1. Создать репозиторий для поддомена Сообщества:
    - Запустить [автоматизированную часть](https://github.com/AnatolyKulakov/Boombr/blob/master/src/GitHubBuddy.ps1#L191)
    - Зафиксировать CNAME файл
    - Разрешить использовать GitHub Pages в `master` ветке
    - Включить `Enforce HTTPS` (становится доступно через какое-то время)
    - Перегенерить сайт для поддержки поддомена
1. [Завести](https://biz.mail.ru/) e-mail адрес для Сообщества
1. Добавить ссылку на Сообщество в [VK](https://vk.com/dotnetru?act=links)
1. Сделать репосты о первом митапе в [VK DotNetRu](https://vk.com/dotnetru) (а также в других сообществах), [Telegram'е](https://t.me/DotNetRu), [Twitter'е](https://twitter.com/dotnetru).