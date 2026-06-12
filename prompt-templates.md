# 🧩 Промпты (переиспользуемые)

Готовые промпты для всего пайплайна 2D faceless. Копируйте и подставляйте свои значения в [скобках].

---

## 1. Сценарий (Gemini / Claude)

```
Ты — сценарист faceless YouTube-канала в жанре [ЖАНР].

Напиши сценарий закадрового нарратива для аниме-ролика длиной ~8 минут
(примерно 1100–1300 слов озвучки, темп ~140 слов/мин).

Требования:
- Цепляющий хук в первые 30 секунд.
- Раздели текст на СЦЕНЫ. Каждая сцена = 1 абзац озвучки (15–25 секунд).
- В начале каждой сцены в квадратных скобках дай ВИЗУАЛЬНОЕ ОПИСАНИЕ кадра:
  место, персонажи, эмоция, ракурс, освещение.
- Мини-крючок в конце каждой 4-5 сцены.
- Язык простой, разговорный.
- В конце — призыв подписаться, вплетённый в историю.

Тема истории: [ИДЕЯ В 1-2 ПРЕДЛОЖЕНИЯХ]
```

---

## 2. Эталон персонажа (Nano Banana)

```
Anime style character reference sheet. [возраст, пол], [волосы], [глаза],
[одежда], [детали]. Front view, neutral expression, clean background,
full body. Consistent flat 2D anime art style, soft cell shading.
```

---

## 3. Кадр сцены с фиксацией персонажа (Nano Banana)

```
[Прикрепите 2-3 изображения эталона персонажа]

Using the attached character as reference, keep her/his face, hairstyle
and outfit identical.

Scene: [описание сцены из сценария].
Same flat 2D anime art style as reference. 16:9 aspect ratio.
```

---

## 4. Оживление кадра (Veo 3.1, image-to-video)

```
[Загрузите картинку как input image]

Subtle cinematic motion. [тип движения: slow camera push-in / gentle wind /
light parallax]. Keep the 2D anime art style unchanged, flat shading,
do not make it realistic. No sudden movements.
```

---

## 5. Стиль-якорь (вставляйте в КАЖДЫЙ промпт генерации)

```
flat 2D anime, soft cell shading, [ваша палитра, напр. muted cool palette]
```

> Держите одну и ту же формулировку стиля во всех промптах — это главное против скачков стиля.
