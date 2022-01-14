# ToDoList-Project
Test task for Tele 2

## Todo list React-Redux project
Проект выполнен с добавлением Expo. Весь функционал реализован. Для запуска клонировать репозиторий себе в редактор кода, установить все зависимости из package-json с помощью npm install, и прописать expo start --no-dev --minify, затем, с помощью приложения Expo и мобильного устройства запустить по QR-коду.
### Функции
Все задачи отображаются на главной странице. Ниже представлен счетчик задач выполненные/все. Для добавления задачи снизу поле ввода, нажатие по которому открывает клавиатуру. 
Максимальное количество символов для задачи - 50, переменная со значением, которую можно менять, находится в компоненте AddTask.js под названием lengthOfTask. Добавление задачи в 
список происходит нажатием на зеленую область с плюсом. Максимальное кол-во задач - 20. Чтобы отметить задачу, как выполненную, нужно нажать на чекбокс слева от задачи, чтобы 
удалить задачу, нужно нажать на красную область с минусом.
### Компоненты 
Главный компонент AppWrapper, где подключено хранилище Redux, а также дочерний компонент App, в котором находятся все остальные компоненты: AddTask, TaskItem, TotalCompleteItems. 
