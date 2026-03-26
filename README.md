# 📖 Help VPN - User Documentation Site

**Роль:** База знаний для пользователей Outlivion VPN  
**Технологии:** Next.js (Nextra), Markdown  
**Домен:** `https://help.outlivion.space`

---

## ⚠️ ВАЖНО: Scope документации

`Help VPN` содержит **ТОЛЬКО пользовательский контент**:
- ✅ Как подключиться к VPN
- ✅ Инструкции по установке приложений
- ✅ FAQ для пользователей
- ✅ Типовые проблемы (пользовательский уровень)

`Help VPN` **НЕ содержит**:
- ❌ Архитектуру системы
- ❌ API документацию
- ❌ Deployment инструкции
- ❌ Troubleshooting для разработчиков

**Для инженерной документации → [`../docs/`](../docs/README.md)**

---

## 🚀 Быстрый старт

### Локальная разработка:
```bash
npm install
npm run dev
```

Сайт будет доступен на `http://localhost:3000`

### Структура:
```
vpn-help/
├── pages/              # Страницы документации (MDX)
│   ├── index.mdx      # Главная страница
│   ├── installation/  # Инструкции по установке
│   └── faq/           # Часто задаваемые вопросы
├── public/            # Статические файлы
└── theme.config.tsx   # Конфигурация Nextra
```

---

## 📝 Как добавить новую страницу

1. Создать MDX файл в `pages/`:
```bash
# Например: pages/faq/new-question.mdx
```

2. Добавить в `_meta.json`:
```json
{
  "new-question": "Новый вопрос"
}
```

3. Написать контент в MDX

---

## 📚 Связанная документация

- **Инженерная документация:** [`../docs/`](../docs/README.md)
- **API документация:** [`../docs/04-apis/`](../docs/04-apis/)
- **Архитектура:** [`../docs/02-architecture.md`](../docs/02-architecture.md)
- **Copy standard:** [`../docs/COPY_STANDARD.md`](../docs/COPY_STANDARD.md)
- **Legal audit:** [`../docs/LEGAL_COPY_AUDIT_2026-03-26.md`](../docs/LEGAL_COPY_AUDIT_2026-03-26.md)

---

**Поддержка:** User support team  
**Последнее обновление:** 2025-01-18
