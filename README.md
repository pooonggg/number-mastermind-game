# Number Mastermind 🎯

[English](#english) | [ภาษาไทย](#thai)

---

<a name="english"></a>
## 🎮 Number Mastermind - Classic Number Guessing Game

A modern web-based implementation of the classic Mastermind game with numbers. Challenge your logical thinking by guessing the secret number with helpful clues!

### ✨ Features

- 🎯 **4 Difficulty Levels**: Easy (3 digits), Medium (4 digits), Hard (5 digits + time limit), Expert (4 digits, limited hints)
- 🎨 **Modern UI/UX**: Dark theme with glassmorphism design
- 📱 **Fully Responsive**: Works perfectly on all devices
- 🔐 **Encoded Secret**: Base64 encoded secret number displayed upfront
- ⏱️ **Timer Mode**: Time pressure challenge in hard difficulty
- 🎉 **Victory Animation**: Confetti celebration when you win
- 📊 **Game Statistics**: Track attempts and time spent

### 🎯 How to Play

1. **Choose a difficulty level** from the main menu
2. **Enter your guess** - digits must not repeat
3. **Check the hints**:
   - **Correct Digits** (Orange): Total count of digits that exist in the secret number
   - **Correct Position** (Green): Count of digits in the exact right position
4. **Keep guessing** until you find the secret number!

### 📏 Game Rules

- Each digit (0-9) can only be used once
- The secret number is randomly generated
- Expert mode only shows correct positions (no digit count)
- Hard mode has a 60-second time limit per guess

### 💡 Example

If the secret is **305**:
- Guess **345** → Correct Digits: 2, Correct Position: 2
- Guess **530** → Correct Digits: 3, Correct Position: 1
- Guess **012** → Correct Digits: 1, Correct Position: 0

### 🚀 Quick Start

#### Option 1: Play Online
Visit: `https://[username].github.io/number-mastermind/`

#### Option 2: Run Locally
```bash
# Clone the repository
git clone https://github.com/[username]/number-mastermind.git

# Open in browser
open number-mastermind/index.html
```

### 🛠️ Deploy to GitHub Pages

1. Fork or create a new repository
2. Upload `index.html` to the repository
3. Go to Settings → Pages
4. Select Source: Deploy from branch (main)
5. Your game will be live at `https://[username].github.io/[repository-name]/`

### 🔧 Technologies Used

- Pure HTML5, CSS3, JavaScript (ES6+)
- No external dependencies
- CSS Variables for theming
- CSS Grid & Flexbox for layout
- CSS Animations & Transitions

### 📱 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Android)

### 🎮 Game Controls

- **Number Keys (0-9)**: Input your guess
- **Enter**: Submit your guess
- **Reveal Button**: Show the answer (ends game)
- **New Game**: Return to difficulty selection

### 🎨 Customization

Edit CSS variables in `index.html`:
```css
:root {
    --primary-color: #6366f1;
    --success-color: #10b981;
    --warning-color: #f59e0b;
}
```

### 📄 License

MIT License - Feel free to use and modify!

---

<a name="thai"></a>
## 🎮 Number Mastermind - เกมทายตัวเลขสุดคลาสสิก

เกมทายตัวเลขแบบ Mastermind ในรูปแบบเว็บแอปพลิเคชันสมัยใหม่ ท้าทายความคิดเชิงตรรกะด้วยการทายตัวเลขลับพร้อมคำใบ้ที่ช่วยให้คุณไขปริศนา!

### ✨ คุณสมบัติเด่น

- 🎯 **4 ระดับความยาก**: ง่าย (3 หลัก), กลาง (4 หลัก), ยาก (5 หลัก + จำกัดเวลา), มืออาชีพ (4 หลัก, คำใบ้จำกัด)
- 🎨 **UI/UX ทันสมัย**: ธีมมืดแบบ glassmorphism
- 📱 **รองรับทุกอุปกรณ์**: ใช้งานได้ดีทั้งมือถือและคอมพิวเตอร์
- 🔐 **รหัสลับเข้ารหัส**: แสดงตัวเลขลับที่เข้ารหัสด้วย Base64
- ⏱️ **โหมดจับเวลา**: ความท้าทายด้วยการจำกัดเวลาในระดับยาก
- 🎉 **อนิเมชันฉลองชัย**: ฉลองด้วยกระดาษโปรยเมื่อชนะ
- 📊 **สถิติเกม**: บันทึกจำนวนครั้งและเวลาที่ใช้

### 🎯 วิธีเล่น

1. **เลือกระดับความยาก** จากเมนูหลัก
2. **กรอกตัวเลขทาย** - ตัวเลขต้องไม่ซ้ำกัน
3. **ดูคำใบ้**:
   - **ตัวเลขถูก** (สีส้ม): จำนวนตัวเลขทั้งหมดที่มีอยู่ในคำตอบ
   - **ตำแหน่งถูก** (สีเขียว): จำนวนตัวเลขที่อยู่ตำแหน่งถูกต้อง
4. **ทายต่อไป** จนกว่าจะเจอตัวเลขลับ!

### 📏 กฎการเล่น

- ตัวเลขแต่ละตัว (0-9) ใช้ได้เพียงครั้งเดียว
- ตัวเลขลับถูกสุ่มขึ้นมาใหม่ทุกเกม
- ระดับมืออาชีพแสดงเฉพาะตำแหน่งที่ถูก (ไม่แสดงจำนวนตัวเลขถูก)
- ระดับยากมีการจำกัดเวลา 60 วินาทีต่อการทาย

### 💡 ตัวอย่าง

ถ้าเฉลยคือ **305**:
- ทาย **345** → ตัวเลขถูก: 2, ตำแหน่งถูก: 2
- ทาย **530** → ตัวเลขถูก: 3, ตำแหน่งถูก: 1
- ทาย **012** → ตัวเลขถูก: 1, ตำแหน่งถูก: 0

### 🚀 เริ่มเล่นทันที

#### วิธีที่ 1: เล่นออนไลน์
เข้าเล่นที่: `https://[username].github.io/number-mastermind/`

#### วิธีที่ 2: เล่นในเครื่อง
```bash
# Clone repository
git clone https://github.com/[username]/number-mastermind.git

# เปิดในเบราว์เซอร์
open number-mastermind/index.html
```

### 🛠️ วิธีนำขึ้น GitHub Pages

1. Fork หรือสร้าง repository ใหม่
2. อัพโหลดไฟล์ `index.html` ไปยัง repository
3. ไปที่ Settings → Pages
4. เลือก Source: Deploy from branch (main)
5. เกมจะพร้อมใช้งานที่ `https://[username].github.io/[repository-name]/`

### 🔧 เทคโนโลยีที่ใช้

- HTML5, CSS3, JavaScript (ES6+) ล้วน
- ไม่พึ่งพา library ภายนอก
- CSS Variables สำหรับปรับธีม
- CSS Grid & Flexbox สำหรับ layout
- CSS Animations & Transitions

### 📱 รองรับเบราว์เซอร์

- Chrome (แนะนำ)
- Firefox
- Safari
- Edge
- เบราว์เซอร์มือถือ (iOS Safari, Chrome Android)

### 🎮 การควบคุม

- **ปุ่มตัวเลข (0-9)**: ป้อนการทาย
- **Enter**: ส่งคำตอบ
- **ปุ่มเฉลย**: แสดงคำตอบ (จบเกมทันที)
- **เกมใหม่**: กลับไปเลือกระดับความยาก

### 🎨 การปรับแต่ง

แก้ไขตัวแปร CSS ใน `index.html`:
```css
:root {
    --primary-color: #6366f1;
    --success-color: #10b981;
    --warning-color: #f59e0b;
}
```

### 📄 สัญญาอนุญาต

MIT License - ใช้และแก้ไขได้อย่างอิสระ!

---

## 📸 Screenshots

<p align="center">
  <img src="https://via.placeholder.com/300x500/1e293b/6366f1?text=Menu+Screen" alt="Menu Screen" width="30%">
  <img src="https://via.placeholder.com/300x500/1e293b/10b981?text=Game+Screen" alt="Game Screen" width="30%">
  <img src="https://via.placeholder.com/300x500/1e293b/f59e0b?text=Victory+Screen" alt="Victory Screen" width="30%">
</p>

---

## 🤝 Contributing

Feel free to open issues or submit pull requests! / เปิด issue หรือส่ง pull request ได้เลย!

## ⭐ Support

If you like this game, please give it a star! / ถ้าชอบเกมนี้ กด ⭐ ให้ด้วยนะครับ!

---

<p align="center">
  Made with ❤️ by [Your Name]
</p>