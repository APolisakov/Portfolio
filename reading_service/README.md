# Описания проекта Анализ сервиса для чтения книг по подписке.


## Данные

таблица books: 
- book_id идентификатор книги, 
- author_id идентификатор автора, 
- title название книги, 
- num_pages количество страниц, 
- publication_date дата публикации книги, 
- publisher_id идентификатор издателя.

таблица authors:
- author_id идентификатор автора, 
- author имя автора.

таблица publishers: 
- publisher_id идентификатор издателя, 
- publisher название издательства.

таблица ratings: 
- rating_id идентификатор оценки, 
- book_id идентификатор книги, 
- username имя пользователя, оставившего оценку, 
- rating оценка книги.

таблица reviews: 
- review_id идентификатор обзора, 
- book_id идентификатор книги, 
- username имя пользователя написавшего обзор, 
- text текст обзора.

## Задача

Проанализировать базу данных сервиса для чтения книг по подписке и сформулировать ценностное предложение для нового продукта.  

## Используемые библиотеки
*pandas*, *sqlalchemy*
