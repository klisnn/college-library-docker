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

## Docker арқылы іске қосу

Docker image құру:

```bash
docker build -t college-library .
```

Контейнерді іске қосу:

```bash
docker run -d -p 8080:80 --name college-library-app college-library
```

Сайт: `http://localhost:8080`

Контейнерді тоқтату:

```bash
docker stop college-library-app
```

Контейнерді қайта іске қосу:

```bash
docker start college-library-app
```

## Автор
Колледж студентінің практикалық жобасы.
