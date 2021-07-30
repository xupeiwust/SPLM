# Semantic Portal for Product Lifecycle Management (SP4PLM) 
## in short: Semantic PLM (SPLM)

# Назначение портала

Портал предназначен для навигации и анализа данных, представленных в семантическом виде, см стандарты Semantic Web на официальном сайте [w3c.org](https://www.w3.org/standards/semanticweb/). Портал так же предназначен для интеграции информации из разных источников.

![w3c](https://www.w3.org/Icons/SW/sw-horz-w3c.png)

# Особенность портала

Ключевой особенностью портала является то, что все данные на портале отображаются в зависимости от их классов зарегистрированных в нем онтологий. Т. е. каждый класс онтологии имеет свою форму представления данных, которая может быть уникальной и заданной в явном виде. Или создаваться «на лету» в результате наследования от своего старшего класса онтологии. 

# Содержание

- [Установка:](#1)
- [Основные модули портала](#3) 
- [Возможные области применения портала](#4)

<a name="1"></a>
## Установка

1) Загрузите исходный код с git:
    ```
    git clone git://github.com/oleg-post/SPLM.git
    ```
2) Перейдите в директорию проекта:
    ```
    cd SPLM
    ```
3) Подготовьте виртуальное окружение VirtualEnv и VirtualEnvWrapper. Дополнительно смотрите: http://www.doughellmann.com/docs/virtualenvwrapper/ и https://python-scripts.com/virtualenv. Создайте virtual environment:
    ```
    mkvirtualenv environment
    ```
4) Установите необходимые дополнительные пакеты (python dependencies):
    ```
    pip install -r requirements.txt
    ```
5) Запустите сервер приложения:
    ```
    python run.py
    ```
<a name="3"></a>
## Основные модули портала
Основные модули портала являют ядром и поставляются на условиях [лицензии](LICENSE). К основным модулям портала относятся:
- Администрирование портала
- Управление пользователями
- Управление оформлением 
- Управление онтологиями
- Загрузка данных
- Управление запросами в базе данных
- Управление модулями

<a name="4"></a>
## Возможные области применения портала
- Управление информацией об оборудовании (информационна модель изделия)
- Управление информацией для календарно-сетевого планирования
- Интеграция данных
- Витрина данных
- Аналитика данных, включая, но не ограничиваясь:
  - предиктивная аналитика, 
  - классификация, 
  - кластеризация, 
  - регрессионный анализ, 
  - построение дерева решений и т.д.

