# City Center Residence

Live site: https://citycenter.chernivtsi.space

## About
City Center Residence — готель у Чернівцях. Односторінковий лендинг. Фото закладу немає (`photos_source: null`), тому hero типографічний (CSS/SVG), а єдині фото — міста Чернівців з Pexels (див. Photos).

## Hero concept
Панель ліфта: табло з «28 номерів», кнопки-зручності (горить «Ліфт») і адресна табличка. Ліфт — підтверджена зручність.

## Amenities (verified, list.json)
- Безкоштовний Wi‑Fi
- Кондиціонер
- Цілодобова рецепція
- Ліфт
- Щоденне прибирання
- Камера зберігання багажу
- Сніданок
- Трансфер з аеропорту

## Check-in / check-out
Заїзд 14:00–24:00; Виїзд 08:00–12:00

## Reviews
Booking.com 8.7/10 (136), Google 4.0/5 (490). Знімок на 30.09.2026, платформи окремо, без aggregateRating.

## Contact
- Phone: +380 66 044 9533
- Booking.com: https://www.booking.com/hotel/ua/city-center-residence.en-gb.html
- Google Maps: https://maps.google.com/?cid=11333068226875083733
- Address: вул. Ольги Кобилянської, 36, Чернівці

## Not published
Зірковість (Google Hotels і Booking показують 4★, офіційного джерела немає), «у центрі міста» (лише з назви), email, сайт, Instagram, категорії номерів. 28 номерів — з Hotels24 (medium), у schema не передано.

## Forms
HotelOS (`ch-citycenter`): `stay-request` (проживання). Документ `hotels/ch-citycenter` у Firestore треба створити вручну, інакше правила відхилять заявки.

## Photos
Лише фото міста (не готелю), з Pexels, підключені за прямими посиланнями images.pexels.com (без копій у репо), з підписами та авторами на сторінці:

- Вежа з годинником Резиденції митрополитів: pexels.com/photo/23881442 (Constantin Ch)
- Чернівці крізь арку: pexels.com/photo/17265268 (Андрій Копічевський)
- Дворик, оповитий плющем: pexels.com/photo/17268819 (Андрій Копічевський)

## SEO
Title і description з маніфесту, canonical, Open Graph, `geo.*`, JSON-LD `Hotel` лише з підтвердженими полями (без numberOfRooms, starRating, aggregateRating), `robots.txt`, `sitemap.xml`, `404.html`.
