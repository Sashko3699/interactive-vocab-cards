# Interactive Terminology Cards

Сервис интерактивного изучения терминологии и карточек для запоминания.

## Что это такое?

Это как Anki, только свой. Ты создаёшь карточки с терминами,
а программа сама показывает их в нужный момент — чтобы ты
не забывал то, что уже выучил.

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
