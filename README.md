# lorquotes_archive
Т.к. lorquotes.ru похоже всё (проклятый ковид..), сохраню то, что удалось добыть, в github

На сайте были цитаты с linux.org.ru в формате, удобном для утилиты fortune

Актуальность архива ~ 2021-07-19. Спасибо AVRs

# установка и использование
1. скачать файл lor
2. подготовить его для использования в fortune
```
strfile lor
# должен появится файл lor.dat
```
3. запустить
```
fortune  PATH_TO_DIR_OR_FILE
```
4. при желании можно добавить в .bashrc
```
fortune $HOME/Документы/fortunes/ || /bin/true
```

# see also
https://www.linux.org.ru/forum/talks/16518115
