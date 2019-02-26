# Тестовое задание для компании ФИЗИКОН на вакансию «Разработчик javascript/frontend»

Описание задания.

Необходимо выполнить нижеследующее задание, допустимо использование любых библиотек или фреймворков.

Имеется следующий метод API:
POST http://krapipl.imumk.ru:8082/api/mobilev1/update
в теле запроса передается объект json
{'data':''}

Возвращается результат вида:
```
{
    "items": [
        {
            "courseId": "105",
            "extId": "Physicon_IMUMK_Course_285524",
            "courseHash": "191153621289246190966820186118178188200176110202548",
            "title": "Задачник по биологии, демо-версия",
            "grade": "8;9;10;11",
            "genre": "Задачник",
            "subject": "Биология",
            "itunes_id": "ru.physicon.imumk.Physicon_IMUMK_Course_285524",
            "progress": 0,
            "description": "Задачник по биологии, демо-версия",
            "status": "demo",
            "price": 100,
            "shopUrl": null,
            "google_id": "ru.fizikon.physicon_imumk_course_285524",
            "winstore_id": null,
            "isNew": false,
            "priceBonus": 5000
        }, …
   ],
    "result": "Ok",
    "errorMessage": null
}
```
Необходимо собрать аналог витрины https://imumk.ru/showcase,
т.е. страницу с плашками и фильтрами по предмету, классу, жанру, поиском по названию.
Верстка «резиновая», внешний вид плашек полностью идентичен приведенному на странице.
На кнопке «Попробовать» вместо надписи «Попробовать» вывести цену в рублях из поля price.
Дополнительно разместить на странице переключатель «рубли/бонусы», выводить соответственно цену в рублях или бонусах.
Витрина должна получать данные асинхронно, фильтрацию осуществлять на клиенте.

Недостающие данные получить методом наблюдения или из html-кода страницы.

Код выложить на гитхаб, страницу опубликовать на GitHub Pages.
