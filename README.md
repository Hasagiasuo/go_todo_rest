# To-Do List REST API на Golang

Цей проєкт являє собою REST API для керування завданнями (To-Do List), розроблений мовою Go (Golang). Сервіс дає змогу створювати, переглядати, оновлювати та видаляти завдання.
Не забудьте заповнити файл конфігурації

## Функціонал

- **Створення завдання**
- **Отримання всіх завдань**
- **Отримання одного завдання за ID**
- **Оновлення завдання**
- **Видалення завдання**

## Технології

- **Мова програмування**: Go (Golang)
- **Фреймворк**: `net/http`, `gin`
- **База даних**: POSTGRES (може бути замінена на іншу)
- **Формат обміну даними**: JSON

## Встановлення та запуск

### Клонування репозиторію

```bash
git clone https://github.com/Hasagiasuo/todo_rest_api_go.git
cd todo_rest_api_go
```

### Установка залежностей

```bash
go mod tidy
```

### Запуск сервера

```bash
go run cmd/main.go
```

## Використання бази даних

За замовчуванням використовується POSTGRES. База даних створюється автоматично під час першого запуску.

## TODO

- Додати аутентифікацію.
- Поліпшити обробку помилок.
- Додати фільтрацію та сортування завдань.

## Ліцензія

Цей проєкт поширюється під ліцензією MIT.

