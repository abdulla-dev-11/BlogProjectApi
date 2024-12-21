# BlogProjectApi

BlogProjectApi — bu blog platformasi uchun yaratilgan RESTful API bo'lib, foydalanuvchilarga maqolalar yaratish, o'qish, yangilash va o'chirish imkonini beradi.

## Loyihaning asosiy imkoniyatlari

- **Maqolalar boshqaruvi**: foydalanuvchilar yangi maqolalar yaratishi, mavjudlarini ko'rishi, tahrirlashi va o'chirishi mumkin.
- **Foydalanuvchilar autentifikatsiyasi**: foydalanuvchilar ro'yxatdan o'tishi va tizimga kirishi mumkin.

## Texnologiyalar

Loyiha quyidagi texnologiyalar yordamida ishlab chiqilgan:

- **Python**: dasturlash tili.
- **Django**: veb-dasturlarni yaratish uchun mo'ljallangan ramka.
- **Django REST Framework**: RESTful API yaratish uchun vosita.

## O'rnatish

Loyihani lokal muhitda ishga tushirish uchun quyidagi amallarni bajaring:

1. **Repizitoriyani klonlash**:

   ```bash
   git clone https://github.com/abdulla-dev-11/BlogProjectApi
   ```

2. **Virtual muhit yaratish va faollashtirish**:

   ```bash
   python -m venv venv
   source venv/bin/activate  # Unix
   venv\Scripts\activate  # Windows
   ```

3. **Talab qilinadigan kutubxonalarni o'rnatish**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Ma'lumotlar bazasini migratsiya qilish**:

   ```bash
   python manage.py migrate
   ```

5. **Serverni ishga tushirish**:

   ```bash
   python manage.py runserver
   ```

Shundan so'ng, API `http://127.0.0.1:8000/` manzilida ishlaydi.

## Foydalanish

API endpointlari va ularning funksiyalari haqida batafsil ma'lumot olish uchun [Django REST Framework](https://www.django-rest-framework.org/) hujjatlariga murojaat qilishingiz mumkin.

## Hissa qo'shish

Agar loyihaga hissa qo'shmoqchi bo'lsangiz, quyidagi amallarni bajaring:

1. **Fork** qiling.
2. O'zingizning branch'ingizni yarating: `git checkout -b my-feature-branch`.
3. O'zgartirishlarni kiriting va commit qiling: `git commit -m 'Yangi imkoniyat qo'shildi'`.
4. O'zgartirishlarni push qiling: `git push origin my-feature-branch`.
5. Pull request yuboring.

## Litsenziya

Ushbu loyiha [MIT litsenziyasi](LICENSE) ostida tarqatiladi.

## Aloqa

Savollar yoki takliflar uchun [Firdavs Valiyev](https://github.com/abdulla-dev-11) bilan bog'lanishingiz mumkin. 