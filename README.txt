МАРАМЕЛЬ — версия с отдельными блоками в HTML

Все разделы находятся прямо в index.html, каждый подписан комментариями:
ЗОЛОТАЯ ПАРА, СЕРЕБРЯНАЯ ПАРА, БЕЛЫЕ ПЕРСОНАЖИ и т.д.

ФОТО КАЖДОЙ ПАРЫ:
images/gold-pair.jpg
images/silver-pair.jpg
images/white-pair.jpg
images/red-pair.jpg
images/blue-pair.jpg
images/cyan-pair.jpg
images/santa-pair.jpg

ФОН КАЖДОГО РАЗДЕЛА:
images/gold-background.jpg
images/silver-background.jpg
images/white-background.jpg
images/red-background.jpg
images/blue-background.jpg
images/cyan-background.jpg
images/santa-background.jpg

ЛОГОТИП:
Положите файл images/logo.png. Если логотипа пока нет, браузер покажет пустое место изображения — это нормально, замените файл позже.

КАК ДОБАВИТЬ РАЗДЕЛ:
Скопируйте целиком любой блок <section class="catalog-section ...">...</section> внутри <main class="catalog">.
Задайте уникальный id и класс, измените все пути к фото и фону, заголовок, описание, цену.
Новый класс цвета можно оформить в style.css по образцу .gold-section.

КАК УДАЛИТЬ:
Удалите целиком нужный section от открывающего тега <section ...> до закрывающего </section>. Остальные блоки не трогайте.

ПРИМЕЧАНИЕ:
Названия фото должны точно совпадать с путями в HTML. Рекомендуется JPG/WebP для фото и PNG для логотипа.
