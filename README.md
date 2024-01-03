# UPhoto - Веб-приложение для фотографов-студентов ТГУ

Добро пожаловать в репозиторий проекта UPhoto, разработанного студентами Томского государственного университета (ТГУ), Института прикладной математики и компьютерных наук (ИПМКН). Этот проект был создан в рамках учебного курса "Web-технологии", где наша команда стремилась разработать веб-приложение, которое решало бы проблему неосвещённости мероприятий ТГУ.

Ознакомиться с готовым результатом проекта можно, перейдя по [ссылке](http://j9617073.beget.tech/index.php).

# О проекте
UPhoto- это веб-приложение, разработанное специально для студентов-фотографов Томского государственного университета (ТГУ). Наш проект создан с учетом особенностей студенческого сообщества и направлен на удовлетворение потребностей как организаторов мероприятий, так и фотографов-студентов.

Организаторам мероприятий ТГУ часто требуются фотографы для запечатления ключевых моментов и атмосферы их мероприятий. С другой стороны, студенты-фотографы ищут возможности для практики, съемки событий и наращивания опыта для своего портфолио.

Главная проблема заключается в том, что организаторы не знают всех активных фотографов из ТГУ. Ведь кто-то может перестать снимать, а кто-то только начинает свой путь в фотографии. Кроме того, руководители комиссий и клубов меняются, и информация о фотографах, способных осветить мероприятие, может утрачиваться. Веб-приложение решает эту проблему, поскольку там отображаются активные фотографы.

# Наша команда
Наша творческая и сплоченная команда состоит из трёх выдающихся студентов:

[Зайнулин Владислав](https://github.com/kitten-owner) - Team Lead, Frontend-разработчик, а также фотограф с двумя годами опыта освещения мероприятий ТГУ и не только. Владислав создал интуитивный и адаптивный пользовательский интерфейс, обеспечивая удобство использования веб-приложения для всех пользователей.

[Шлейнингер Никита](https://github.com/Libernik) - Наш непревзойденный Backend разработчик. Никита ответственен за создание мощной и эффективной серверной части приложения, обеспечивая его стабильную работу и безопасность данных.

[Аксёнова Ирина](https://github.com/rinaAks) - Наш талантливый дизайнер. Ирина воплощает креативные идеи в привлекательный дизайн. Ее творческий вклад придает приложению стиль и привлекательность.

Вместе мы создали веб-приложение, нацеленное на удовлетворение потребностей студенческого сообщества ТГУ в сфере фотографии.

# Дизайн
Дизайн проекта разрабатывался с помощью графического редактора Figma. 
![Adaptive example](Pictures/Figma.jpg)

Для дизайна использовалась следующая палитра цветов: #37447E (тёмно-синий), #6FB6F4 (голубой), #848AF2 (сиреневый), #8ED9F1 (голубой). Ширина страниц - 1440px, за основу бралась сетка из 12 столбцов с шириной 65px и расстоянием 30px. В качестве декоративных элементов использовались пятна с градиентом из цвета палитры в прозрачность, созданные с помощью плагина Blobs. 
Иконки для картинок были также добавлены через плагины Iconly Pro и Material Design Icons, некоторые отредактированы / созданы самостоятельно.

Логотип проекта напоминает форму буквы U. "U" как "University" (Университет) указывает на образовательный аспект проекта, а "U" как "you" (Вы) подразумевает, что проект ориентирован на индивидуальные потребности и интересы каждого пользователя.


# Frontend
Для создания Frontend-части проекта использовались следующие инструменты:
- Языки: HTML, CSS, JS
- Framework: Bootstrap
- Библиотеки: jQuery, smartcrop.js
- Select2: Это замена полей выбора на основе jQuery, обеспечивающая улучшенный пользовательский опыт в интерактивных элементах выбора.

В процессе разработки Frontend-части проекта успешно внедрены следующие функциональные возможности:

1) Полностью адаптивные страницы проекта: Гарантирует оптимальное отображение и удобство использования на различных устройствах.
![Adaptive example](Pictures/Adaptive.png)

2) Функции, позволяющие загружать и получать превью фотографии: Обеспечивает быструю и эффективную загрузку изображений с предварительным просмотром.

3) Использование smartcrop.js: Алгоритм для выделения наиболее интересной и важной части изображения и обрезка её таким образом, чтобы сохранить важные детали.
![Smartcrop.js](Pictures/Smartcrop.png)

4) Невероятно удобное добавление тэгов за счёт Select2: Улучшает процесс добавления тэгов, предоставляя удобный и интерактивный пользовательский опыт.

5) Функция, ограничивающая выбор даты, не превышающей сегодня: Обеспечивает контроль и предотвращает выбор будущих дат.

6) Скрипты, позволяющие динамично расширять форму: Предоставляет возможность динамического расширения формы, что делает её более гибкой и удобной для пользователя.

# Backend
Для создания Backend-части проекта использовались следующие инструменты:
- Языки: HTML, JS, PHP, SQL
- Библиотеки: jQuery, phpMailer
- AJAX: Подход к построению интерактивных пользовательских интерфейсов веб-приложений.
- СУБД: MySQL с администрированием через PhpMyAdmin.

В процессе разработки Backend-части были успешно реализованы следующие  функциональные возможности:

1) Live search фотографов: Возможность динамического поиска фотографов в режиме реального времени, обеспечивающая удобство пользователей.
![Live search](Pictures/Search.png)

2) Динамичный вывод постов по тегам: Вывод постов на основе тегов с динамическим обновлением контента, что облегчает навигацию по сайту.

3) Lazy loading: Оптимизированная загрузка изображений и контента по мере прокрутки страницы, повышая скорость загрузки и улучшая пользовательский опыт.

4) Отправка кода подтверждения на e-mail: Реализация механизма отправки кодов подтверждения на электронную почту для повышения безопасности и подтверждения идентификации пользователей.
![e-mail](Pictures/E-mail.png)

5) Полный CRUD профиля и постов: Разработка функционала полного управления профилями и постами, включая создание, чтение, обновление и удаление данных.

6) Отслеживание активности фотографов на сайте: Возможность мониторинга активности фотографов в режиме реального времени, обеспечивая веб-приложение актуальной информацией.


# Результат
Мы с гордостью представляем наше веб-приложение - [UPhoto](http://j9617073.beget.tech/index.php)! 

В процессе разработки были успешно реализованы все поставленные задачи, а также успешно решены возникающие проблемы. Наше веб-приложение предоставляет пользователям удобный и эффективный опыт, а команда уверена в его функциональности и надежности. Мы гордимся результатом нашей работы и убеждены, что это веб-приложение полностью соответствует ожиданиям пользователей.

Также мы благодарны нашим преподавателям за предоставленную возможность реализовать этот проект в качестве альтернативы лабораторным работам, что позволило нам полностью освоить материал предмета. Нам было приятно поработать в команде и узнать много нового в процессе создания веб-приложения. Этот проект стал для нас ценным опытом и возможностью применить полученные знания на практике.
