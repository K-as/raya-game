# raya-game
# 🎉 Sampul Raya Mini Game

A simple **mobile-friendly Sampul Raya web game** where players tap the screen as fast as possible within **5 seconds** to win duit raya. The higher the score, the bigger the prize.

Perfect for family gatherings during Hari Raya where guests can **scan a QR code and play instantly on their phone**.

---

## 📱 How It Works

1. Guest scans the QR code.
2. The webpage opens on their phone.
3. Player presses **Start Game**.
4. Player taps the screen as many times as possible in **5 seconds**.
5. The final score determines the **duit raya prize**.

---

## 🏆 Prize System

| Score | Prize        |
| ----- | ------------ |
| 0–20  | RM1          |
| 21–40 | RM5          |
| 41–60 | RM10         |
| 61–80 | RM20         |
| 81+   | RM50 Jackpot |

You can change these values in the `showPrize()` function inside `index.html`.

---

## 🚀 Deployment (GitHub Pages)

1. Create a repository on GitHub.
2. Upload the project files.
3. Ensure the main file is named:

```
index.html
```

4. Go to **Settings → Pages**.
5. Select:

```
Branch: main
Folder: / (root)
```

6. Save.

Your site will be available at:

```
https://yourusername.github.io/repository-name/
```

---

## 📷 Create the QR Code

After publishing the site:

1. Copy the GitHub Pages URL.
2. Generate a QR code using any free QR generator.
3. Print it on the **Sampul Raya envelope**.

Guests can scan the code and play instantly.

---

## ⚠️ Limitations

Because this project runs as a **static webpage**:

* Players can refresh and replay the game.
* No server or database is used.
* Prize tracking is not stored.

This is designed for **fun interactive Sampul Raya experiences**, not strict prize control.

---

## 💡 Ideas for Future Improvements

* Add **confetti animation** for jackpot wins
* Add **Raya sound effects**
* Create a **spin wheel lucky draw**
* Limit **one play per device**
* Add **ketupat-themed graphics**

---

## 📄 License

Free to use and modify for personal projects.
Enjoy your interactive **Sampul Raya Game**! 🎊
