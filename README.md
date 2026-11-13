# AGRO-INVEST — interaktiv demo prototip

Bu Vite + React asosidagi statik demo-sayt. Backend, haqiqiy to‘lov, SMS, ferma IoT va video oqimi ulanmagan. Tugmalar, navigatsiya, kalkulyator, filtrlar, modallar, demo xabar yuborish, CSV eksport va chop etish oynalari ishlaydi.

## Lokal ishga tushirish

```bash
npm install
npm run dev
```

## Vercel'ga joylash

1. `agro-invest-demo` papkasini GitHub repository'ga yuklang (yoki papkani ZIP'dan oching).
2. Vercel'da **Add New → Project** ni tanlang va repository'ni import qiling.
3. Framework Preset: **Vite** (avtomatik aniqlanadi).
4. Build Command: `npm run build`.
5. Output Directory: `dist`.
6. **Deploy** tugmasini bosing. Vercel demo-sayt uchun ommaviy URL beradi.

`vercel.json` SPA route'larini bosh sahifaga qayta yo‘naltiradi.

## Demo raqamlarining yagona manbasi

`src/main.jsx` faylida hayvonlar ro‘yxati va operatsiyalar reyestri markazlashgan. Bosh sahifa va hisobot summalari reyestrdan hisoblanadi.

- Hayvon aktivlari: 3,500,000 + 3,200,000 + 980,000 + 920,000 = **8,600,000 so‘m**.
- Demo investitsiya kapitali: **5,000,000 so‘m**.
- Aprel–sentabr tushumlari: **2,260,000 so‘m**.
- Aprel–sentabr xarajatlari: **503,000 so‘m**.
- Sof loyiha natijasi: **1,757,000 so‘m**.
- Takaful demo zaxirasi: sof natijaning 2%i = **35,140 so‘m**.
- Taqsimlanadigan natija: **1,721,860 so‘m**.
- Investor ulushi: 70% = **1,205,302 so‘m**.
- Boshqaruvchi ulushi: 30% = **516,558 so‘m**.

Kalkulyator alohida ssenariy parametrlaridan foydalanadi: loyiha foydasi yiliga 24% deb faraz qilinadi, undan 2% zaxira ajratilib, qolgan foyda 70/30 nisbatda taqsimlanadi. Bu kafolatlangan daromad yoki haqiqiy investitsiya taklifi emas.
