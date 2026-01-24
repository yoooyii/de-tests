# 🌻 DE Monats-Test (Monthly German Mini Tests)

这是一个我自己制作的 **德语小测验合集**。  
每过几个月会发布一份新的网页测验（Nov Test, Feb Test...），  
点击即可直接在线作答，无需登录或输入姓名。

---

## 🚀 使用方式

📍 在线访问主页：  
👉 [https://yoooyii.github.io/](https://yoooyii.github.io/)

进入后选择对应月份的测验即可开始。

所有测验均可在浏览器中离线完成，判分与状态记录保存在浏览器本地（`localStorage`），不会上传任何数据。

---

## 🪄 新增一个月份的测验

1. 在 `tests/` 文件夹中复制一份旧测验（例如 `2025-11-Nov_Test.html`）；
2. 改成新的名字，例如 `2025-12-Dez_Test.html`；
3. 打开 `monats.json`，在末尾添加一条记录：

```json
{
    "id": "2025-11",
    "title": "Nov Test · Guten Tag! & Auf Deutsch, bitte!",
    "path": "tests/2025-11-Nov_Test.html",
    "time": "15分钟",
    "topics": ["Begrüßung", "Vorstellung", "Klassenzimmer"]
}
```
---

## 📌 24.11.2025 更新
1. 新增：语音听力按钮（Aufgabe 3 & Hörverstehen）
2. 新增：开始测试按钮（Starten!）
3. 新增：悬浮计时器

---

## 📌 24.01.2026 更新
1. 新增一月份的测验
2. 打开 `monats.json`，在末尾添加一条新记录：

```json
{
    "id": "2026-01",
    "title": "Jan Test · Woher kommst du? & Entschuldigung!",
    "path": "tests/2026-01-Jan_Test.html",
    "time": "20分钟",
    "topics": ["Woher/kommen", "Berufe", "Länder & Städte", "Entschuldigung"]
}
```

---
### 隔壁有单词练习网页 [https://github.com/yoooyii/vokabel-web](https://github.com/yoooyii/vokabel-web)
