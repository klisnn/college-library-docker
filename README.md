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

## Docker арқылы іске қосу

Docker image құру:

```bash
docker build -t college-library .
```

Контейнерді іске қосу:

```bash
docker run -d -p 8080:80 --name college-library-app college-library
```

Сайт: http://localhost:8080

Контейнерді тоқтату:

```bash
docker stop college-library-app
```

Compose арқылы іске қосу:

```bash
docker compose up -d --build
```

Compose контейнерлерін тоқтату:

```bash
docker compose down
```