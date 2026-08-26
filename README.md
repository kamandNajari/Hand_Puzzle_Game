# 🧩 Hand Puzzle Game

Turn any photo into an interactive tile puzzle — and solve it using nothing but your hand, tracked live through your webcam. No mouse, no touchscreen, just your fingers in the air.

Pick a photo you love, choose a difficulty, and piece it back together with a simple pinch gesture. Powered by real-time computer vision.

## ✨ Features

- 📷 Use **any photo** you choose from your own device
- 🎚️ Three difficulty levels — Easy, Medium, Hard
- 🖐️ Fully hand-controlled — no keyboard or mouse needed to play
- 🎯 Smart snapping — pieces lock into place automatically when placed correctly
- 🔵 Live self-view in a small camera circle, so you always see your hand
- 🖼️ Faint reference outline of the original photo shown on the board to guide you

## 📦 Requirements

- Python 3.9 or newer
- A working webcam

## 📥 Clone the Repository

```bash
git clone https://github.com/kamandNajari/Hand_Puzzle_Game.git
```

If you don't have Git installed, you can also download the project directly:

1. Go to the repository page on GitHub
2. Click the green **Code** button
3. Select **Download ZIP**
4. Extract the ZIP file to a folder on your computer

## 🚀 Installation

```bash
cd Hand_Puzzle_Game
pip install -r requirements.txt
```

The hand tracking model is downloaded automatically on first run — no manual setup needed.

## 📓 Running the Notebook

Make sure you have Jupyter installed:

```bash
pip install jupyter
```

Then launch it:

```bash
jupyter notebook
```

Open `Hand_Puzzle_Game.ipynb` from the Jupyter interface and run the cell (Shift + Enter).

## ▶️ How to Play

1. Run the notebook — a file picker will open, choose any photo from your device
2. Select a difficulty level from the console: Easy (3x3), Medium (4x4), or Hard (5x5)
3. The puzzle board appears in the center of the screen with a faint outline of your photo as a guide
4. Scattered tile pieces appear around the board
5. Use your hand to pick up and place each tile onto its matching spot

## 🖐️ Hand Controls

| Gesture | Action |
|---------|--------|
| 👌 Pinch (thumb + index finger together) near a piece | Grab the piece |
| Move your pinched hand | Drag the piece across the screen |
| Release the pinch | Drop the piece at its current position |
| Drop a piece near its correct board position | Piece snaps and locks into place automatically |

**Important:** you must bring your **thumb and index finger together** (pinch) to grab and move a piece — just pointing at it with your index finger alone will not work.

## ⌨️ Keyboard Controls

| Key | Action |
|-----|--------|
| `r` | Restart the puzzle with a new shuffle |
| `q` | Quit the application |

## 🛠️ Tech Stack

- [OpenCV](https://opencv.org/) — video capture and rendering
- [MediaPipe](https://developers.google.com/mediapipe) — hand landmark detection
- [NumPy](https://numpy.org/) — numerical operations for tile placement and layout

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details. 

---

## 📖 راهنمای فارسی

این پروژه هر عکسی که دوست داشته باشی رو می‌گیره و تبدیلش می‌کنه به یه پازل تعاملی که فقط با حرکت دستت، جلوی وب‌کم، حلش می‌کنی. نیازی به موس، صفحه‌کلید یا لمس صفحه نیست — تمام کنترل بازی با تشخیص زنده‌ی دست انجام میشه.

### ✨ ویژگی‌ها

- امکان انتخاب **هر عکسی** که خودت بخوای، مستقیم از روی سیستم
- سه سطح سختی قابل‌انتخاب: آسون، متوسط، سخت
- کنترل کامل بازی فقط با دست، بدون نیاز به موس یا کیبورد در حین بازی
- قفل‌شدن خودکار قطعه وقتی دقیقاً سر جای درستش گذاشته بشه
- نمایش زنده‌ی تصویر خودت در یه دایره‌ی کوچیک گوشه‌ی صفحه، برای دیدن دستت در حین بازی
- یه راهنمای محو از خود عکس روی صفحه‌ی پازل، برای کمک به چیدن درست قطعات

### 📦 پیش‌نیازها

- Python نسخه ۳.۹ به بالا
- یه وب‌کم فعال و سالم

### 📥 دریافت پروژه

```bash
git clone https://github.com/kamandNajari/Hand_Puzzle_Game.git
cd Hand_Puzzle_Game
```

### 🚀 نصب کتابخونه‌ها

```bash
pip install -r requirements.txt
```

فایل مدل تشخیص دست به‌صورت خودکار در اولین اجرا دانلود میشه، نیازی به تنظیم دستی نیست.

### 📓 اجرای پروژه

```bash
pip install jupyter
jupyter notebook
```

فایل `Hand_Puzzle_Game.ipynb` رو از محیط Jupyter باز کن و سلول رو اجرا کن (کلید ترکیبی `Shift + Enter`).

### ▶️ نحوه‌ی بازی

1. با اجرای برنامه، یه پنجره‌ی انتخاب فایل باز میشه — عکس دلخواهت رو انتخاب کن
2. سطح سختی رو مشخص کن: آسون (۳×۳)، متوسط (۴×۴)، یا سخت (۵×۵)
3. صفحه‌ی پازل وسط تصویر ظاهر میشه، همراه با یه طرح محو از خود عکس به‌عنوان راهنما
4. قطعات پازل به‌صورت پراکنده دور صفحه چیده میشن
5. با دستت هر قطعه رو بردار و داخل صفحه‌ی وسط، سر جای درست خودش قرار بده

### 🖐️ راهنمای حرکت دست

| حرکت | نتیجه |
|------|-------|
| نزدیک کردن نوک شست و نوک انگشت اشاره به هم (پینچ) روی یه قطعه | گرفتن آن قطعه |
| حرکت دادن دست در حالی که پینچ باز نشده | جابه‌جا کردن قطعه در صفحه |
| باز کردن پینچ (دور کردن شست و اشاره از هم) | رها کردن قطعه در همان نقطه |
| رها کردن قطعه نزدیک جایگاه درست خودش روی صفحه | قفل‌شدن خودکار قطعه در جای درست |

**نکته‌ی مهم:** برای گرفتن و جابه‌جا کردن هر قطعه، حتماً باید **نوک شست و نوک انگشت اشاره** رو به هم نزدیک کنی (حرکت پینچ). فقط نزدیک بردن انگشت اشاره به‌تنهایی، بدون نزدیک کردن شست، قطعه را نمی‌گیرد.

### ⌨️ کلیدهای صفحه‌کلید

| کلید | عملکرد |
|------|--------|
| `r` | شروع دوباره‌ی بازی با چیدمان تصادفی جدید قطعات |
| `q` | خروج کامل از برنامه |

### 🛠️ ابزارهای استفاده‌شده

- **OpenCV** — گرفتن تصویر از وب‌کم و رسم عناصر بازی
- **MediaPipe** — تشخیص دقیق نقاط دست در لحظه
- **NumPy** — محاسبات مربوط به چیدمان و موقعیت قطعات
