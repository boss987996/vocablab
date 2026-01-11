# VocabLab - TOEIC Vocabulary Learning App

แอปเรียนคำศัพท์ TOEIC พร้อมระบบ Spaced Repetition (1-3-7-30 วัน) และ AI ช่วยสร้างประโยคตัวอย่าง

## ✨ Features

- 📚 สร้าง Deck และจัดการคำศัพท์
- 🎴 Flashcard Study Mode พร้อม Keyboard Shortcuts
- 🧠 SRS Algorithm (SM-2 variant)
- ✨ AI สร้างประโยคตัวอย่างแบบ TOEIC
- 📊 Dashboard ติดตาม Streak และ Progress
- 📥 Import/Export CSV

## 🚀 Deploy to Vercel

### วิธีที่ 1: Deploy ผ่าน GitHub (แนะนำ)

1. สร้าง Repository ใหม่บน GitHub
2. Push โค้ดขึ้น GitHub
3. ไปที่ [vercel.com](https://vercel.com) และ Sign up ด้วย GitHub
4. คลิก "New Project" → เลือก Repository
5. คลิก "Deploy" — เสร็จ!

### วิธีที่ 2: Deploy ด้วย Vercel CLI

```bash
npm i -g vercel
vercel login
vercel --prod
```

## 🔑 ตั้งค่า AI API Key

1. ไปที่ Vercel Dashboard → Project Settings → Environment Variables
2. เพิ่ม:
   - `ANTHROPIC_API_KEY` = your-api-key

## 📝 CSV Import Format

```csv
word,meaning_th,meaning_en,example,phonetic,category,level
accomplish,ทำให้สำเร็จ,to succeed,We accomplished our goals.,/əˈkɑːmplɪʃ/,verb,intermediate
```

## ⌨️ Keyboard Shortcuts (Study Mode)

- `Space` / `Enter` = Flip card
- `1` = Again (reset)
- `2` = Hard
- `3` = Good
- `4` = Easy

## 🛠 Tech Stack

- React 18
- LocalStorage (client-side)
- Claude API (AI assistance)
- Vercel (hosting)

---

Made with ❤️ for TOEIC learners
