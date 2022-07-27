# rubyschool
Rubyschool.us list of contents (Russian)

полезные ссылки:
-регулировка скорости видео на Vimeo (расширение для Chrome) https://goo.gl/C78s5P

Урок 1

- что такое Ruby
- что такое Ruby on Rails
- настраиваем окружение
- устанавливаем программы

Примечание:
Установить файловый менеджер far:
[Windows](https://www.farmanager.com/download.php)
[Linux](https://github.com/elfmz/far2l)

Если планируйте перейти на Linux то необходимо выбрать [Linux Mint Cinnamon](https://www.linuxmint.com/download.php)

RubyInstaller это ruby-окружение для [Windows](https://rubyinstaller.ru/)

Урок 2

- puts, print, gets. #, \n
- переменные
- специальные символы
- .chomp, .to_i, .to_s

Урок 3

- irb
- типы данных: string, fixnum, float, integer
- class, array. Hash
- задача про сопротивление (закон Ома)
- преобразование типов данных (to_i переводим в to_s)

Урок 4

- интерполяция строк  -  #{}
- поддержка русского языка в Windows (#encoding: 866 + ANSI)
- удаление символа (.chomp!)
- методы
- пайпы ||
- задачи на преобразование типов и интерполяцию строк
- дз: вывести числа 1..10, определить чётные и нечётные

Урок 5

- методы (продолжение): upto, capitalize, strip, whitespace
- \n \t \r
- .times (считает от 0)
- .upto (считает от 1)
- задача: вывести на экран ряд цифр с помощью upto
- задача: “Привет #{name}, в вашем имени #{name.length} букв”

Урок 6

- блоки
- sleep, .times, do...end, rand
- задания про upto, times, sleep
- задача: рассчитать накопления (сколько будем откладывать и сколько месяцев)
- formating disk, Matrix
- дз: доделать задачу про накопления

Урок 7

- if...end, операторы сравнения, exit
- задача: алгоритм "вы довольны зарплатой?" (Да/Нет)
- задача: посчитать, сколько гостей придёт
- задача: сделать игру "однорукий бандит"

Урок 8

- 1_000_000
- калькулятор
- if/else
- задача: игра - угадываем число
- break, while true, ranges, each
- разница между .. и ...
- rand

Урок 9

- функции и методы (def)
- глобальные переменные (@)
- символы (:)
- массивы, добавление в массивы
  
Урок 10

- инициализация массивов (продолжение)
- задачи: двигаем робота, удаляем/добавляем учеников в список
- loop do

Урок 11

- разбор дз камень-ножницы-бумага
- хэши (hash)

Урок 12

- отличия хэшей от массивов
- задача: создаем словарик
- задача: переделываем “однорукого бандита” с использованием хэшей
- функции (описание и их вызов)
- дз: “Tic-Tac-Toe” (крестики-нолики)

Урок 13

- повторяем хэши
- использование if в одну строку
- merge
- сохранение в файл >, >>
- немного об HTML

Урок 14

- введение в ООП
- классы
- объекты
- attr_reader, attr_accessor

Урок 15

- задачи с классами: самолеты и аэропорты, альбомы и песни
- наследование
- дз: сделать программу с классами Artist - Album - Song

Урок 16

- статические методы
- lambda-функции 
- yield
- наследование
- типы переменных

Урок 17

- мета-программирование (send)
- чтение и запись в файлы 
- получение списка папок и файлов в каталогах

Урок 18 

- GET/POST запросы
- задача: программа для подбора пароля 

Примечание:
Для 18 урока используйте докер-контейнер, который устанавливается командой:
`docker rm xxx; docker run -it --name xxx -p 4567:4567 ro31337/rubybook-save-the-world`
После этого у вас будет доступен локальный сервер по адресу http://localhost:4567

Если непонятно, что написано, то читаем ниже:
* скачиваешь программу Docker, устанавливаешь
* из консоли запускаешь команду - вот эту длинную, что на сайте rubyschool.us (см.сноску для 18 урока). Если ты на винде, то запускай по отдельности то, что разделено точкой с запятой (даже если дает ошибку): `docker rm xxx`, потом `docker run -it --name xxx -p 4567:4567 ro31337/rubybook-save-the-world`
* что-то качается и у тебя будет доступен адрес из браузера  http://localhost:4567

Урок 19

- установка DevKit на Windows
- установка Sinatra
- Helloworld на Синатре

Урок 20

- установка и работа с Git
- установка Ungit на Windows
- продолжение работы с Sinatra

Урок 21

- ещё немного HTML-разметки
- основы CSS
- Bootstrap
- установка готового небольшого приложения Sinatra с включенным Bootstrap'ом

Урок 22

- Рома создает репозиторий. а все копируют себе
- ещё немного теории по git
- доделываем приложение BarberShop для записи к парикмахеру (теперь уже с использованием Bootstrap)

Урок 23

- доработка приложения BarberShop
- немножко JS, jQuery
- делаем colorpicker при помощи jQuery плагина


Урок 24

- немного подробнее о коде из предыдущего jQuery плагина и просто JS и jQuery
- валидация
- сохранение значений в полях формы

Урок 25

- настройка git для пушей без запроса пароля (по ключу ssh)
- установка SQLite3
- немного про синтаксис SQL 
- создание БД и таблиц

Урок 26

- связываем приложение BarberShop с SQLite
- устанавливаем datetimepicker
- выборка из БД, вывод информации

Примечание: Для работы datetimepicker необходимо использовать файл builder\jquery.datetimepicker.full.js

Урок 27

- разбираем домашнее задание
- выводим из БД в веб (в таблицу)
- создаем вторую таблицу, добавляем туда значения
- делаем выборку из БД, заносим в выпадающее меню

Урок 28

- повторение
- новое приложение-блог (Leprosorium)
- прием параметра из ссылки

Примечание:
Если Win10x64 выдает: `require': cannot load such file -- sqlite3/sqlite3_native (LoadError)
Нужно выполнить в консоли
gem uninstall sqlite3 --all
gem install sqlite3 --platform=ruby

Урок 29

- введение в ActiveRecord
- rake
- tux
- migrations


Урок 30 

- продолжение ActiveRecords
- валидация при помощи ActiveRecord


Урок 31

- общая инфа по HTTP и запросам
- javascript

Урок 32

- повторение материала про классы
- работаем с localstorage
- создаём магазин пиццы
- разбираем вопросы, которые могут задавать на интервью при приёме на работу

Урок 33 

- продолжаем разбор вопросов, которые могут задавать на интервью при приёме на работу
- немного про yield
- пишем PizzaShop 

Урок 34

- небольшое объяснение про операторы для краткой записи операций x += 1; x ||= 1
- продолжаем делать pizzashop (javascript)
- устанавливаем Rails
- объяснение структуры Rails

- *Примечание: Если при запуске rails приложения выходит ошибка со следующим текстом
```
Puma caught this error: Error loading the 'sqlite3' Active Record adapter. Missing a gem it depends on? can't activate sqlite3 (~> 1.3.6), already activated sqlite3-1.4.0. Make sure all dependencies are added to Gemfile. (LoadError)
``` 
   Необходимо в gemfile исправить следующeю строку:
```gem 'sqlite3'``` на ```  gem 'sqlite3', '< 1.4'```

Урок 35

- ещё разбор вопросов, которые могут задавать на интервью при приёме на работу
- разбираем тесты, представленные на Odesk
- продолжаем писать PizzaShop

Урок 36

- краткое объяснение REST
- анализ написанного приложения

Урок 37

- введение в pull-реквесты
- разбираем задачи с собеседования
- настройка отступов в Sublime text
- запускаем Rails
-  режимы запуска Rails
- генераторы Rails
- создаем контроллер
- создаем модель

Урок 38 

- разбираем задачи на интервью
- повторение
- разбираем REST маршруты
- сравнениваем resource и resources

Урок 39

- создаем основные контроллеры (по REST) для сущности articles
- создаем статичные страницы в RoR

Урок 40

- удаление статей
- атрибуты тегов data-<something> (turbolinks)
- небольшой рассказ про render
- отношения one-to-many
- создаем форму для комментариев 

Урок 41

- про типы связей (many-to-many, one-to-many, one-to-one)
- задача: доделать блог  до минимального функционала (CRUD)
- полезные сервисы для веб-разработки
- rspec и тесты
- пишем пару простых тестов

Урок 42

- матчеры для тестов
- пишем тест, закрывающий баги на github
- devise: установка, минимальная настройка, создание ссылок для входа-выхода
* Примечание: начиная с Rails 5 синтаксис before_filter устарел и заменён на before_action

Урок 43

- делаем ссылки входа, выхода и т. п. с помощью devise
- сессии и куки
- чуть-чуть про json
- добавляем поля username в devise 
- настраиваем блог для поля username

- *Примечание: в devise начиная с версии 4 параметры Sanitizer Api изменились, используйте вместо этого:
```ruby
  devise_parameter_sanitizer.for(:sign_up) << :username
``` 
   это:
```ruby
  devise_parameter_sanitizer.permit(:sign_up, keys: [:username])
```  
  
Урок 44

- “интервью” с другом Романа - Алексеем. Вопросы про Odesk (Upwork) и в целом про ruby и программирование
- bootstrap
- основы responsive-дизайна

Урок 45

- принцип работы метода params в контроллерах (используется для приёма параметров через post)
- разница между render и redirect_to
- разница между before_filter и before_action
- немного про хелперы
- continuous integration и continuous delivery (CI и CD)
- немного про vagrant

Урок 46

- тестируем модели
- устанавливаем rspec в приложение blog (и capybara)
- устанавливаем shoulda-matchers
- устанавливаем FactoryGirl: простейшая настройка, создание фабрики, тестирование
- создаем фабрику с автоматическим назначением значений полей 
- * Примечание: в gem Rake начиная с версии 11 отсутствует метод "last_comment", этот метод используется в rspec-rails поэтому если вы используете свежую версию Rake не используйте старую версию rspec-rails. Для этого впишите в Gemfile rspec-rails без версии, и тогда bundle install подтянет сразу новую версию.
```ruby
group :development, :test do
  gem 'capybara'
  gem 'rspec-rails'
end
```
- * Примечание 2: когда вы будете использовать Shoulda Matchers его нужно будет настроить, для этого в сгенерированной rails_helper.rb при запуске rails g rspec:install (rspec-rails в версии от 3.0) добавьте
```ruby
Shoulda::Matchers.configure do |config|
  config.integrate do |with|
    with.test_framework :rspec
    with.library :rails
  end
end
```
  подробности http://matchers.shoulda.io/docs/v3.1.1/index.html
  в файл с тестом вместо 
```ruby
  require 'spec_helper'
```
  добавьте 
```ruby
  require 'rails_helper'
```
require 'support/factory_girl'
- * Примечание 3: При настройке Factory_girl в rspec-rails старше 3.0 нужно добавить строчку в rails_helper
```ruby
  require 'support/factory_girl'
```

Урок 47

- понятие о приёмочном тестировании (acceptance testing)
- пишем тест для capybara 
- понятие о  i18n (internationalization)
- применение i18n в capybara
- before и after hooks
- * Примечание: ссылка на capybara изменилась теперь: https://github.com/teamcapybara/capybara#using-capybara-with-rspec , для её настройки согласно документации нужно добавить в ваш файл rails_helper строчку (в rspec_helper для старых версий), хотя работает и без этой строки.
```ruby
  require 'capybara/rspec'
```
 
Урок 48

- Scaffolding (генерация модели, вида и контроллера одной командой)
- недостатки скаффолдинга
- создание небольшого приложения при помощи скаффолдинга
- кратко про отправку имейлов

Урок 49

- полиморфные ассоциации (краткое объяснение что это такое и создание небольшого примера)
- паттерны 
- Singleton. Разбор на примере. 
- типы переменных в классе, принадлежащие экземпляру класса и классу

Урок 50

- регулярные выражения
