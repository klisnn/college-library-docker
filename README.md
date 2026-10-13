<<<<<<< HEAD
# College Library

## Жоба мақсаты
Колледж кітапханасының пайдаланушыларын басқаруға арналған веб-жоба.

## Технологиялар
- PHP
- MySQL
- HTML
- CSS
- Apache
- Docker

## Мүмкіндіктері
- Тіркелу және жүйеге кіру
- Пайдаланушыларды басқару
- Әкімші панелі
- Дерекқормен жұмыс
=======
# college-library-docker
# College Library Web Project

## Жобаның мақсаты
Колледж кітапханасының жұмысын автоматтандыруға арналған веб-сайт жасау.

## Қолданылатын технологиялар
- HTML
- CSS
- PHP
- MySQL
- Apache
- Docker

## Негізгі мүмкіндіктері
- Пайдаланушыны тіркеу
- Жүйеге кіру және шығу
- Құпиясөзді қауіпсіз сақтау
- Әкімші панелі
- Пайдаланушыларды басқару
- MySQL дерекқорымен жұмыс

## Жобаны іске қосу
1. XAMPP бағдарламасын орнату.
2. Apache және MySQL қызметтерін іске қосу.
3. Жобаны `htdocs` бумасына орналастыру.
4. `college_library` дерекқорын жасау.
5. Браузерден `http://localhost/college_library/` мекенжайын ашу.
>>>>>>> 4aea0a9af8aae2501f7bdf4d7ed758891b1aebb2

## Docker арқылы іске қосу

Docker image құру:

```bash
docker build -t college-library .
```

Контейнерді іске қосу:

```bash
docker run -d -p 8080:80 --name college-library-app college-library
```

<<<<<<< HEAD
Сайт: http://localhost:8080
=======
Сайт: `http://localhost:8080`
>>>>>>> 4aea0a9af8aae2501f7bdf4d7ed758891b1aebb2

Контейнерді тоқтату:

```bash
docker stop college-library-app
```

<<<<<<< HEAD
Compose арқылы іске қосу:

```bash
docker compose up -d --build
```

Compose контейнерлерін тоқтату:

```bash
docker compose down
```
=======
Контейнерді қайта іске қосу:

```bash
docker start college-library-app
```

## Автор
Колледж студентінің практикалық жобасы.
>>>>>>> 4aea0a9af8aae2501f7bdf4d7ed758891b1aebb2
