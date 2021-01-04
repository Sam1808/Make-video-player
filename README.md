# Верстаем видеоплеер
## Прототип видеоплеера для Игоря Иванова. 

Видеоплеер построен на базе библиотеки [Playable](https://wix.github.io/playable/), код любезно предоставлен [Devman](https://github.com/devmanorg/video-player-jslib).

Реализованы кнопки управления Play, Pause, Mute, Full screen.
Добавлен анимированный Progress-bar с отображением времени. 
Дизайн максимально соответствует предоставленному [макету](https://gist.github.com/dvmn-tasks/c86e26be451abcf94f15b80189eb0390).

Пример прототипа плеера опубликован на GitHub Pages по ссылке: <br>
[https://sam1808.github.io/Make-video-player/player/index.html](https://sam1808.github.io/Make-video-player/player/index.html)

## Как запустить плеер локально
Скачайте код: 
```
git clone https://github.com/Sam1808/Make-video-player.git
```
В репозитории представлены две папки `fonts` и `player`. Запустите двойным кликом файл `index.html` из папки `player`.
В браузере вы должны получить следующий результат:

![Иллюстрация](./layout.png)

Не забудьте подключить компьютер к сети Интернет для корректной работы плеера, т.к. код "подтягивает" соответсвтующие стили и шрифты.