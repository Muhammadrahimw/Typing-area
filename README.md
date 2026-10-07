# Typing maydoncha

Maktab kompyuterlari uchun oflayn klaviatura trenajyori. Bitta fayl: `Typing-maydoncha.html` — internetsiz, brauzerda ochiladi.

## Imkoniyatlar

- 40 ta dars, 8 bo'lim: asosiy qator → yuqori/pastki qator → katta harflar → raqamlar → belgilar → HTML teglar → inglizcha so'zlar.
- Ekrandagi klaviatura va qo'llar: qaysi barmoq bilan bosish kerakligini ko'rsatadi.
- **So'zlar rejimi** — 30 soniya / 1 / 2 daqiqa davomida faqat so'zlar yozish, har vaqt uchun alohida rekord. Hamma harflarni hali o'rganmagan o'quvchiga faqat o'rgangan harflaridan tuzilgan so'zlar beriladi. Qachon ochilishini o'qituvchi tanlaydi (standart: «Asosiy qator» bo'limi tugagach).
- **Dizaynlar** — bo'limlar tugagan sari ochiladi va avtomatik yoqiladi: Klassik → Zumrad (2 bo'lim) → Binafsha (3) → Tun (5, qorong'i) → Oltin (hammasi). O'quvchi «Dizayn» tugmasi orqali ochilganlaridan birini tanlay oladi.
- **So'z yomg'iri** (o'yin) — tepadan tushayotgan so'zlarni yerga yetmasdan yozish. 3 ta jon, har 10 so'zda bosqich va tezlik oshadi, ketma-ket xatosiz so'zlar uchun ochko ×2…×4. So'zlar rejimi bilan bir vaqtda ochiladi.
- **Nishonlar** — 20 ta yutuq (darslar, yulduzlar, tezlik, so'zlar rejimi, yomg'ir, mashq vaqti). Bir marta olingan nishon qaytib olinmaydi.
- **Takroriy akkauntdan himoya** — ism boshqacha yozilsa (so'zlar tartibi, 1–2 harf farqi, apostrof turi) «Siz shu o'quvchi emasmisiz?» deb so'raydi. O'qituvchi ikki akkauntni bittaga birlashtira oladi.
- O'qituvchi paneli (standart PIN: `1234`): sinflar, natijalar jadvali, CSV, zaxira nusxa (JSON) va boshqa kompyuterlardagi natijalarni birlashtirish.

## Kompyuterlarda yangilash

Natijalar brauzerning `localStorage` xotirasida (`typing_maydoncha_v1` kaliti) saqlanadi, faylning ichida emas. Shuning uchun faylni **o'sha joyda, o'sha nom bilan** almashtirsangiz, eski natijalar o'chmaydi.

1. Yangilashdan oldin (ehtiyot uchun): O'qituvchi paneli → «Faylga saqlash».
2. Yangi `Typing-maydoncha.html` ni eski fayl ustiga ko'chiring (`C:\Dars\dasturlar\`) — yoki `00-ORNATISH.bat` ni ishga tushiring.
3. Faylni avvalgidek o'sha brauzerda oching (yorliq orqali).

## Ishlab chiquvchi uchun qoidalar

Eski natijalar saqlanib qolishi uchun:

- `KEY` (`typing_maydoncha_v1`) ni o'zgartirmang.
- Darslar tartibini o'zgartirmang va o'rtaga dars qo'shmang — natijalar dars raqami bo'yicha saqlanadi. Yangi dars faqat **oxiriga** qo'shiladi.
- Yangi ma'lumotlar o'quvchi obyektiga yangi maydon sifatida qo'shiladi; eski maydonlar o'chirilmaydi yoki nomi o'zgartirilmaydi.
- Har o'zgarishda `<meta name="version" content="YYYY-MM-DD">` sanasini yangilang — u kirish oynasi pastida va o'rnatuvchi oynasida ko'rinadi, shunda kompyuter yangilangani bir qarashda bilinadi.
