# 📘 Amiibo NFC Tags Guide

This repository contains a complete step-by-step guide on how to write Amiibo characters to NFC tags using **TagMo** and use them just like real Amiibo figures.

---

## 📱 What This Guide Covers

- What Amiibo NFC tags are
- Required hardware
- How to install and set up TagMo
- How to write Amiibo data to NTAG215 tags
- How to use your custom Amiibo tags on Nintendo systems
- Troubleshooting common issues

---

## 🛠 Requirements

Before starting, you will need:

- 📱 An **Android phone with NFC support**
- 🏷 **NTAG215 NFC tags** (Required for Amiibo compatibility)
- 📦 The **TagMo** app (APK installed on Android)
- 📁 Amiibo `.bin` files
- 🔑 `keys.bin` encryption file

> ⚠ Only NTAG215 tags work for Amiibo. NTAG213 or NTAG216 will NOT work.

---

## 📥 Installing TagMo

1. Download the latest **TagMo APK**.
2. Install it on your Android device.
3. Enable **NFC** in your phone settings.
4. Open TagMo.
5. Import your `keys.bin` file inside the app when prompted.

---

## 📝 Writing an Amiibo to an NFC Tag (Using TagMo)

1. Open **TagMo**
2. Tap **Load Tag**
3. Select your Amiibo `.bin` file
4. Tap **Write Tag**
5. Place the NTAG215 tag against the back of your phone
6. Wait for the confirmation message

✅ Your NFC tag will now function like the real Amiibo figure.

---

## 🎮 Using Your Amiibo Tag

Simply scan your written NFC tag on your Nintendo console the same way you would scan a real Amiibo figure.

---

## 📁 Suggested Repository Structure

```
Amiibo-NFC-Tags-Guide/
├── README.md
├── android-setup/
│   └── tagmo-installation.md
├── writing-guide/
│   └── how-to-write-tags.md
├── troubleshooting/
│   └── common-errors.md
├── images/
│   └── screenshots/
```

---

## ❓ Troubleshooting

### Tag Not Scanning?
- Make sure NFC is enabled.
- Remove phone case if necessary.
- Move tag slowly around the NFC antenna area.

### Write Failed?
- Confirm tag is NTAG215.
- Reload `keys.bin`.
- Restart TagMo.
- Try another NFC tag.

### "Key file missing" Error?
- Ensure `keys.bin` is properly imported into TagMo.

---

## ⚠ Important Notes

- Do not remove the NFC tag during writing.
- Keep backup copies of your `.bin` files.
- Use responsibly.
- This repository is for educational purposes only.

---

## 🤝 Contributing

Want to improve this guide?

1. Fork the repository
2. Add improvements or fixes
3. Submit a pull request

Contributions are welcome!

---

## ⭐ Support

If this guide helped you, consider starring the repository!

