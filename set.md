[<- К содержанию](./readme.md)

# Первая настройка GIT
После [установки](./download.md) _GIT_ на компьютере, нужно сделать первоначальные настройки для работы. Для этого в окне [Терминала](./terminal.md) выполнить следующие команды:

+ ## Команда ***git config***

  Для того, чтобы прописать свой адрес электронной почты и пароль, которые будут использоваться для передачи данных на сервер _Git_, используйте команду ***git config***. 
  
  Например:

  ```bash-
  git config --global user.name "Your Name" 
  ```

  ```bash-
  git config --global user.email "your_email@examle.com" 
  ```

+ ## Команда ***git init***

  Для того, чтобы создать новый пустой репозиторий на вашем компьютере, а также необходимые файлы для его работы, введите команду
  ```bash-
  git init
  ```

  Также эта команда создаст в текущей директории новую поддиректорию с именем .git

  [**<- Назад |**](./terminal.md "Использование Терминала")[**| Далее ->**](./add.md "Команда git add")