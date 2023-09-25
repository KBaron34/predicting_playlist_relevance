# predicting_playlist_relevance
Прогнозирование на сколько плейлист будет релевантен определенному треку.

Описание задачи:

Данные собраны с помощью API Spotify.

Как понять какой музыкальный трек подойдет к какому плейлисту? В ходе этого проекта я разработал ML-модель, кторая ранжирует плейлисты в порядке их релевантности для определенного произведения.
Цель задачи - разработать модель, которая на основе данных об имеющихся плейлистах, а также о музыкантах и их треках будет составлять ранжированный список наиболее релевантных плейлистов для конкретного музыкального произведения.

Описание данных:
- author_name – имя исполнителя;
- album_name - название альбома;
- track_name - название трека;
- track_id - id трека;
- playlist_id - id плейлиста;
- description - описание плейлиста;
- playlist_name - название плейлиста;
- owner_name - имя куратора плейлиста;
- score - метка принадлежности: трек присутствует в плейлисте (1 - Да, 0 - Нет).
