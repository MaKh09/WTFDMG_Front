```markdown
# 🚀 WTFDMG Mentor Platform (Frontend)

**Веб-приложение для поиска IT-менторов**  
*Разрабатывается в связке с [бекендом на Go](https://github.com/MaKh09/WTFDMG_Back) и [мобильным приложением](https://github.com/MaKh09/WTFDMG_Mobile).*

---

## 📌 О проекте
Площадка для IT-менторов, где они могут создавать профили, а начинающие разработчики — находить наставников и бронировать сессии.

**Основной функционал:**
- ✅ Просмотр карточек менторов
- ✅ Фильтрация по технологиям (React, Kotlin, Go и др.)
- ✅ Система бронирования и оплаты
- ✅ Чат между ментором и учеником

---

## 🛠 Технологии
- **Frontend**: React 18 + TypeScript
- **Стили**: Tailwind CSS (или SCSS)
- **Сборка**: Vite
- **API**: [В процессе написания](ссылка_на_доку_бека)
- **Тестирование**: Jest + React Testing Library

---

## 🚀 Как запустить проект?

### Установка зависимостей
```bash
npm install
```

### Запуск dev-сервера
```bash
npm run dev
```
Откроется на [http://localhost:5173](http://localhost:5173)

### Сборка для production
```bash
npm run build
```

---

## 🌿 Ветки и Git-процесс
Мы используем **Git Flow**:
- `main` — стабильная версия (только через PR)
- `develop` — текущая разработка
- `feature/*` — новые фичи (например, `feature/auth`)

**Пример работы:**
```bash
git checkout develop
git pull origin develop
git checkout -b feature/mentor-card
```

---

## 📁 Структура проекта
```
src/
├── components/   # Reusable UI-компоненты
│   ├── MentorCard.tsx
│   └── Header.tsx
├── pages/        # Страницы
│   ├── Home.tsx
│   └── Profile.tsx
├── hooks/        # Кастомные хуки
├── store/        # Zustand/Redux
├── api/          # Запросы к бекенду
└── assets/       # Изображения, шрифты
```

---

## 🤝 Как внести вклад?
1. Форкните репозиторий
2. Создайте ветку (`git checkout -b feature/your-feature`)
3. Сделайте коммит (`git commit -m "feat: add amazing feature"`)
4. Запушьте (`git push origin feature/your-feature`)
5. Откройте Pull Request

---

## 📜 Лицензия
MIT © [Danila Mochalov/MaKho9]

