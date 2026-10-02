# Interactive Terminology Cards

Сервис интерактивного изучения терминологии и карточек для запоминания.

## Что это такое?

Система решает проблему забывания профессиональных терминов.
Пользователь создаёт колоды карточек, а сервис по алгоритму SM-2
(как в Anki) определяет, когда показать карточку снова — для
максимально эффективного запоминания.

## На чём сделано?

- Frontend (то, что видит пользователь): React + TypeScript
- Backend (мозг программы): Python + FastAPI
- База данных: PostgreSQL
- Запуск: Docker

## Как запустить (потом, когда будет готово)

```bash
git clone https://github.com/ТВОЙ_НИК/interactive-vocab-cards.git
cd interactive-vocab-cards
cp .env.example .env
docker-compose up -d
