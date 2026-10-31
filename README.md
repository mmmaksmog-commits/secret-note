# 🔏 Секретная записка

**Шифрование сообщений паролем прямо в браузере.**

### ▶️ [Открыть](https://mysik-portfolio.vercel.app/secret-note/)

Работает на телефоне и на ПК, без установки и регистрации.

## Возможности

- AES-256-GCM, ключ из пароля через PBKDF2 (250 000 итераций)
- Зашифрованные данные лежат в ссылке после #, на сервер не уходят
- Подсказка к паролю
- Проверка неверного пароля

## Стек

Web Crypto API. Один файл `index.html`, без фреймворков и сборки.

## Запуск локально

```bash
git clone https://github.com/mmmaksmog-commits/secret-note.git
cd secret-note
python3 -m http.server 8000
```

---

Часть [портфолио](https://mysik-portfolio.vercel.app/).
