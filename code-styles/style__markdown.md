# Markdown style

## Unicode

| Символ | ASCII | Пример                          | Значение       |
| ------ | ----- | ------------------------------- | -------------- |
| —      | ---   | Век живи — век учись.           | Тире           |
| –      | --    | 2010–2012                       | Короткое тире  |
| −      | -     | 5−2=3                           | Минус          |
| -      | -     | Кое-что, тел.: 123-45-67        | Обычный дефис  |
| «»     | <<>>  | Петя сказал: «Скоро Новый год». | Кавычки-елочки |
| ©      | (c)   | Все права защищены © 2022.      | Знак копирайта |
| ×      | x     | 1920 × 768 px                   | Знак умножения |
| →      | ->    | `File` → `New file`             | Стрелка        |
| …      | ...   | Надо так много сказать…         | Троеточие      |
| °      |       | Температура была +31°.          | Градус         |
| 🠕      |       | Рост на 10% 🠕                   | Повышение      |
| 🠗      |       | Падение на 10% 🠗                | Понижение      |

ASCII значения не используем.

## Emoji

⭐ 🔥 💥 👍 🔗 ❤️ 🎵 ⚡ 🗺️ 🌏 🌎 🎓 🎁 💾 📷 🎥 💻 ☎️ 📞 🔍 🔒 🔓 🔑 📧 ✉️ 📦 📁 📂 📅 📆 ⏱️ 🔔 📚 📖 🏆 🇷🇺 🇺🇸 ❌ ✅ ❓ ❗ ⛔ 🚫 🔍 🔖 🏷️ ✏️ 🔞 📝 ⚠️ 💡 👉🏻 4️⃣2️⃣ 🐍

## Lists

[Punctuation](https://docs.gitlab.com/ee/development/documentation/styleguide/#punctuation-1):

- Don’t add commas (`,`) or semicolons (`;`) to the ends of list items.
- If a list item is a complete sentence (with a subject and a verb), add a period at the end.
- Majority rules. If the majority of items do not end in a period, do not end any of the items in a period.
- Separate list items from explanatory text with a colon (`:`). В русских текстах для этого может использоваться тире (`—`).

```markdown
The list is as follows:

- First item: this explains the first item.
- Second item: this explains the second item.
```
