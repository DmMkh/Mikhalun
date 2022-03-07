##Как создать ssh ключ##

ssh-keygen -t ed25519 -C "email@gmail.com"
Указать пароль, если нужно ##Как добавить ключ в аккаунт на github##
Выбрать нужный репозиторий
->settings->deploy keys->add deploy key
Копировать ключ в поле key, указав имя в поле title ##Как склонировать репозиторий##
Пройти аутентификацию
прописать команду git clone git@github.com:DmMkh/Mikhalun.git