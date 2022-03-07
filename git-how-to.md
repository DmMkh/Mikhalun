 Как создать ssh ключ
1. ssh-keygen -t ed25519 -C "email@gmail.com"
2. Указать пароль, если нужно
 Как добавить ключ в аккаунт на github
1. Выбрать нужный репозиторий
2. ->settings->SSH AND GPG keys-> new SSH key
3. Копировать ключ в поле key, указав имя в поле title
 Как склонировать репозиторий
1. Пройти аутентификацию
2. прописать команду git clone git@github.com:DmMkh/Mikhalun.git
