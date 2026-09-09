# CLAUDE.md — loyiha qoidalari

## Loyiha nima
Mavlon Mirzaxalilovning shaxsiy vizitka sayti (bitta sahifa).
Maqsad: potensial mijoz saytga kirib, kim ekanligimni tushunsin va bog'lansin.
U 3 yillik tajribaga ega dasturchi va front-end mentor; avtomatlashtirish tizimlari, CRM va LMS quradi.
Sayt tili — o'zbek (lotin). Apostrof sifatida `‘` ishlatiladi (`o‘quv`, `bog‘lanish`), oddiy `'` emas.

## Texnik chegaralar
- **Butun sayt — bitta `index.html` fayl.** CSS `<style>` ichida, JS `<script>` ichida. Alohida `.css`/`.js` fayl ochma.
- Tashqi kutubxona, framework, CDN, build qadam — **yo'q**. Faqat toza HTML/CSS/JS.
- Ikona kerak bo'lsa — inline SVG. Shrift — tizim shriftlari (`Segoe UI`, system-ui).
- Papkada faqat: `index.html`, `rasm.jpg` (profil surati), `CLAUDE.md`.
- Sayt `file://` orqali ochilishi kerak — server talab qiladigan narsa qo'shma.

## Uslub qoidalari
- **Iliq palitra.** Barcha ranglar `:root` dagi CSS o'zgaruvchilarida. Faylga qattiq yozilgan rang (hex) qo'shma — yangi rang kerak bo'lsa, avval token yarat.
- Ikki mavzu bor: yorug' va qorong'i. Har qanday yangi element **ikkalasida ham** to'g'ri ko'rinishi shart.
- Hero bo'limi — doim to'q jigarrang panel (o'z `--h-*` tokenlari bilan), mavzudan qat'i nazar.
- Minimalistik, education ohang: ko'p bo'sh joy, tinch ranglar, kam bezak, animatsiya minimal.
- Matn ohangi: sodda, ishonchli, maqtanchoqsiz. Reklama shiorlari va sun'iy hayajon yo'q.
- Mobil birinchi darajali: har o'zgarishdan keyin 375px kenglikda gorizontal scroll yo'qligini tekshir.

## Ish qoidalari
- **Kod yozishdan oldin qisqa reja ko'rsat** (2-4 gap: nima o'zgaradi, qayerda). Roziligimni kut.
- Kichik qadamlar bilan ishla. Bitta so'rovda bitta narsani o'zgartir, butun faylni sababsiz qayta yozma.
- O'zgarishdan keyin brauzerda tekshir va natijani ayt. "Ishlashi kerak" degan taxmin bilan cheklanma.
- Men so'ramagan bo'lim, xizmat yoki tugma **qo'shma**.
- Men bermagan faktni **o'ylab topma**: mijoz nomlari, loyiha tafsilotlari, raqamlar, sharhlar, sertifikatlar.
  Bo'sh joy kerak bo'lsa — mendan so'ra yoki aniq belgilangan placeholder qoldirib, menga ayt.
- Xato yoki muammo ko'rsang (kontrast, ishlamaydigan link, buzilgan layout) — tuzat yoki hech bo'lmasa aytib o't.

## Aloqa ma'lumotlari (saytdagi haqiqiy ma'lumot)
- Telefon: `+998916960729` → `tel:` link
- Telegram: `@MavlonMirzaxalilov` → `https://t.me/MavlonMirzaxalilov`
