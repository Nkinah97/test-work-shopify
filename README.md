# Shopify Theme

Це тема для Shopify магазину. Для локальної розробки потрібно виконати наступні кроки:

## Вимоги

- Node.js (версія 16 або вище)
- Shopify CLI
- Shopify партнерський акаунт
- Доступ до Shopify магазину

## Встановлення

1. Встановіть Shopify CLI:
```bash
npm install -g @shopify/cli @shopify/theme
```

2. Авторизуйтесь в Shopify CLI:
```bash
shopify auth login
```

3. Клонуйте репозиторій:
```bash
git clone https://github.com/Nkinah97/test-work-shopify.git
cd test-work-shopify
```

4. Підключіть тему до вашого Shopify магазину:
```bash
shopify theme dev
```

## Структура проекту

- `assets/` - стилі, скрипти та зображення
- `config/` - налаштування теми
- `layout/` - шаблони сторінок
- `sections/` - секції теми
- `snippets/` - повторювані елементи
- `templates/` - шаблони сторінок
- `locales/` - файли локалізації

## Розробка

1. Запустіть локальний сервер розробки:
```bash
shopify theme dev
```

2. Відкрийте браузер за адресою, яку вкаже CLI (зазвичай http://127.0.0.1:9292)

3. Всі зміни в коді будуть автоматично синхронізуватися з вашим Shopify магазином

## Розгортання

Для розгортання змін на продакшн:

```bash
shopify theme push
```

## Додаткова інформація

- [Документація Shopify CLI](https://shopify.dev/themes/tools/cli)
- [Документація Shopify теми](https://shopify.dev/themes)
- [Документація Liquid](https://shopify.dev/docs/api/liquid)
