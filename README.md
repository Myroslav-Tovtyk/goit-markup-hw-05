# goit-markup-hw-05
Позиціонування


Всім привіт! :машу_рукой:
Беремося за інформацію пʼятого модуля.
Завдання виконано згідно з ТЗ
Основним джерелом необхідної інформації для виконання ДЗ – конспект, відеоуроки А. Репети та живі вебінари з викладачем.
Особливу увагу рекомендується приділити відносному позиціонуванню, оскільки це частіше зустрічатиметься у повсякденній верстці. Конкретніше - це абсолютне позиціюнування та властивість z-index
Основні моменти, на які варто звернути увагу під час виконання ДЗ:
У наступне ДЗ переносимо структуру з попереднього та перевірене ментором завдання. Якщо ви не виконали попереднє ДЗ або його не перевіряв ментор, готуйтеся вносити редагування у двох місцях. Без прийнятого попереднього ДЗ не здати наступного.
Анімацію прописуємо для ВСІХ посилань та кнопок без винятку, а також явно вказуємо властивість, яку анімуєте.
Підкреслення на навігаційних посиланнях при hover/ focus робити не обов’язково. Якщо вирішили зробити - не забуваємо за плавність появи та самого підкреслення. Відповідно до ТЗ - підкреслення треба візуального відображення поточної сторінки.
Якщо при анімації змінюється колір, фон або тінь – для цих властивостей теж прописуємо анімацію
ДЗ виконується згідно з ТЗ.
Код валідний та відформатований за допомогою prettier.
Зайвий код та непотрібні коментарі відсутні
Додаткові матеріали:
Position
CSS Transition
Готовий CSS код різних анімацій тексту
Всім продуктивного тижня. :ракета:


Каруселька slick

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.min.css" integrity="sha512-yHknP1/AwR+yx26cB1y0cjvQUMvEa2PFzt1c9LlS4pRQ5NOTZFWbhBig+X9G9eYW/8m0/4OXNx8pxJ6z57x0dw==" crossorigin="anonymous" referrerpolicy="no-referrer" />


<link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick-theme.min.css"
      integrity="sha512-17EgCFERpgZKcm0j0fEq1YCJuyAWdz9KUtv1EjVuaOz8pDnh/0nZxmU6BBXwaaxqoi9PQXnRWqlcDB027hgv9A=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />

<script src="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.min.js" integrity="sha512-XtmMtDEcNz2j7ekrtHvOVR4iwwaD6o/FUJe6+Zq+HgcCsk3kj4uSQQR8weQ2QVj1o0Pk6PwYLohm206ZzNfubg==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>

<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js" referrerpolicy="no-referrer"></script>


<script>
      $(".works-list").slick({
        infinite: true,
        slidesToShow: 3,
        slidesToScroll: 3,
      });
    </script>

Siema слайдер

https://pawelgrzybek.github.io/siema/

Bootstrap

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

