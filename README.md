# 🌌 Phosphophyllite Theme for Shikimori

**Описание**: Тёмная бирюзовая тема в стиле Фосфофиллита из Houseki no Kuni с адаптивным дизайном и кастомными элементами.
![Скриншот](https://i.ibb.co/ZpDmGXRZ/cb1002a96dc0af68483f6569193cfda0.jpg) - Фон по умолчанию (можно заменить),

![Скриншот](https://i.ibb.co/s9cybFjC/i.jpg) - баннер по умолчанию (тоже можно заменить).
## 🛠 Установка
1.Установи расширение Stylus для Chrome/Firefox.

2.Нажми → RAW-ссылка на CSS.

3.В Stylus выбери "Установить стиль".

Или вставь вручную:
```css
@import url("https://raw.githubusercontent.com/ed-main/ed-main.github.io/master/cssfiles/main_code_1.css");
@import url("https://raw.githubusercontent.com/ed-main/ed-main.github.io/master/cssfiles/main_code_2.css");
@import url("https://raw.githubusercontent.com/ed-main/ed-main.github.io/master/cssfiles/main_code_3.css");
@import url("https://raw.githubusercontent.com/ed-main/ed-main.github.io/master/cssfiles/main_code_4mob.css");
@import url("https://raw.githubusercontent.com/ed-main/ed-main.github.io/master/cssfiles/prof_form_over.css");
@import url("https://raw.githubusercontent.com/Dream-Mercy/Phosphophyllite-teme/main/Phos_Shiki-theme.css");
```
## ✨ Особенности
### 🎨 Цветовая схема
```css
:root {
  --bright-color: #6BBABC;  /* Бирюзовые акценты */
  --dark-color: #0A1F26;    /* Тёмный фон */
  --gold-color: #FFD700;    /* Золотые элементы (как трещины Фосфофиллита) */
```

### 🎮 Интерактивные элементы  
- **Кнопки**:  
  ```css
  --buttoms-color: #3A6E70;          /* Стандартный цвет */
  --hover-bottoms-1: #4A8A8D;        /* Hover-эффект */
  ```
## 🌟 Ключевые элементы
Кастомный фон профиля (для экранов >1200px):
```css
#profiles_show .profile-head::after {
  background-image: url("https://i.ibb.co/yBKqknk0/i.jpg");
}
```
### Анимация рейтингов:
Высокий: бирюза

Средний: светлая бирюза

Низкий: золото

### Футер с подписью:
```css
.l-footer::after {
  content: "*Calidum*";  /* Ваш уникальный знак */
}
```
## 📱 Адаптивность
Мобильная версия (main_code_4mob.css) оптимизирована под маленькие экраны.

ПК-версия включает:

1.Фон профиля

2.Улучшенные hover-эффекты
## 🐛 Отчёт о проблемах
Нашли баг? Создай Issue с:

1.Скриншотом ошибки

2.Версией браузера

3.Описанием, как воспроизвести
## 💡 Советы по кастомизации
1.Сменить фон: 
```css
body::after {
  background-image: url("ВАША_ССЫЛКА.jpg");
}
```
2.Изменить акцентные цвета:
Подправь значения --bright-color и --gold-color в :root. 

3.Если хочешь поменять какие-то цвета на свои, то просто измени цветовые значения в :root.
## **💡 Идеи для развития темы**  
1. **Добавить тёмный/светлый режим** (переключатель через CSS-переменные).  
2. **Кастомные курсоры** (например, в форме кристаллов).  
3. **Анимацию загрузки** в стиле *Houseki no Kuni*.  

### **📌 Как это реализовать?**  
1. **Для анимаций**:  
   ```css
   @keyframes phos-flicker {
     0% { opacity: 0.7; }
     50% { opacity: 1; }
     100% { opacity: 0.7; }
   }

2. **Для режимов**:
  ```css
body[data-theme="light"] {
  --dark-color: #D0F0F0;
  --bright-color: #0A1F26;
}
 ```
## Автор: Dream_Mercy
Вдохновение: Houseki no Kuni, бирюзовые палитры

"Лучше быть бриллиантом, чем углём." © Фосфофиллит
## 📸 Скриншоты  
![Скриншот](https://i.ibb.co/7xF0dnnv/photo-2025-04-23-15-11-43.jpg)
![Скриншот](https://i.ibb.co/d0qsMZ8C/photo-2025-04-23-15-11-33.jpg)
![Скриншот](https://i.ibb.co/PGZXrVCX/photo-2025-04-23-15-11-40.jpg) 
