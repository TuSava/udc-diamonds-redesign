# UDC DIAMONDS — Luxury Digital Flagship & Experience Redesign

> **«Діаманти рідкісні. Довіра — ще рідкісніша. Справжня розкіш ніколи не просить купити її зі знижкою — вона запрошує доторкнутися до досконалості».**

Повний комплексний редизайн та розробка фронтенду офіційного сайту **UDC Diamonds (Український Діамантовий Центр)** у стилістиці **Graff / Quiet Luxury** з підтримкою кінематографічного медіаконтенту 360°.

---

## 💎 Живий прототип та Figma

- **Жива демо-версія на Vercel / GitHub Pages**: [Переглянути наживо](https://tusava.github.io/udc-diamonds-redesign/)
- **Полотно проєкту у Figma**: [UDC Diamonds Redesign & Design System](https://www.figma.com/design/yd609eMG9lQyBnRxXZZm7b)
- **Комерційна пропозиція (Front-end + Video 360°)**: [UDC_COMMERCIAL_OFFER_FRONTEND_AND_CONTENT.md](./UDC_COMMERCIAL_OFFER_FRONTEND_AND_CONTENT.md)

---

## 🏛️ Ключові особливості реалізації

1. **Едиторіал-дизайн світового рівня**:
   - Бенчмарк: *Graff Haute Joaillerie*.
   - Палітра Quiet Luxury: *Warm White (#FAF9F6)*, *Ivory Canvas (#F1EEE8)*, *Champagne Gold (#D8CBB8)*, *Deep Charcoal (#292929)*, *Timeless Black (#111111)*.
   - Серифна типографіка *Playfair Display* & *Cormorant Garamond* у поєднанні з надчітким гротеском *Inter*.

2. **Дворівневий Grand Crown Header**:
   - Верхній ярус: центральний брендовий логотип (з 2001 року), VIP-запис, кошик, обране та порівняння.
   - Нижній ярус: центрована навігація категорій.

3. **Автентичні колекції та вироби UDC**:
   - 5 знакових колекцій: *UDC Fine Jewelry, Green Elegance, Tenderness, Діамантові хрестики, Blue Velvet*.
   - Реальні артикули та ціни: Fancy Yellow 1.80 ct (`Ю65416` — 405 903 ₴), Pavé Trilogy (`Ф36321` — 323 807 ₴), сережки-трансформери (`Ю65572` — 79 224 ₴).
   - 4 стовпи довіри: 100% GIA, ательє з 2001 року, прямий імпорт з біржі Рамат-Ган, 5 салонів у Києві.

4. **100% адаптивність під Apple HIG**:
   - Desktop (1440px), Tablet (768px), Mobile (390px iPhone).
   - Повноекранне мобільне консьєрж-меню з блюром 24px та викликом `0 800 330 740`.
   - Плаваючий стікі-бар запису на примірку внизу смартфона.
   - Захист від накладання тексту на фото (Zero-Overlap).

5. **Підтримка відеоконтенту 360°**:
   - Адаптовані блоки під кінематографічні 360° макро-лупи діамантів на поворотному столі.

---

## 📁 Структура файлів проєкту

- `index.html` — Офіційна адаптивна головна сторінка (Production-ready).
- `udc-stage3-responsive.html` — Повний адаптивний прототип (Desktop, Tablet, Mobile).
- `udc-design-system.html` — Інтерактивна дизайн-система та UI Kit.
- `udc-prototype-flow.html` — Специфікація інтерактивних сценаріїв та матриця переходів.
- `assets/` — Офіційні фотоматеріали прикрас та колекцій.
- `figma_exports/` — Оптимізовані артборди для імпорту в Figma.
