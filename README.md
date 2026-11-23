# Movie Search — шаблон домашнього завдання 3

Шаблон для домашнього завдання 3 курсу React v4: пошук фільмів через TMDB.

## Що вже є в шаблоні

- проєкт на Vite: React, TypeScript, React Compiler, ESLint;
- встановлені `modern-normalize`, `clsx`, `lucide-react` і `sonner`; у `src/main.tsx` підключено `modern-normalize` і глобальні стилі `src/index.css`;
- налаштовано аліас `@/` для папки `src`: імпорти з інших папок пиши через `@/` (`import type { Movie } from "@/types/movie"`), а файли з тієї ж папки — відносним шляхом `./`;
- компонент `App` у `src/components/App/App.tsx`;
- готові стилі всіх компонентів у файлах `.module.css` у папках `src/components`;
- файл `.env.example`; `.env` уже додано в `.gitignore`.

Стилі писати не треба. Файли компонентів `.tsx`, сервіс запитів, типи і `src/vite-env.d.ts` ти створюєш сам.

## Як почати

1. Натисни **Use this template** → **Create a new repository** і створи репозиторій `03-react-movies` у своєму акаунті.
2. Склонуй свій репозиторій і встанови залежності:

   ```bash
   npm install
   ```

3. Скопіюй `.env.example` у `.env` і впиши свій токен TMDB:

   ```bash
   VITE_TMDB_TOKEN=твій_токен
   ```

4. Запусти проєкт:

   ```bash
   npm run dev
   ```

## Перевірка перед здачею

```bash
npm run lint
npm run build
```

Обидві команди мають виконатися без помилок.
