# 📖 Quran Omar — Official Releases

Welcome to the official public distribution repository for **Quran Omar**.

A native Android Quran application featuring:
- **Madani 15-line Calligraphy Pages** with authentic pixel-perfect Ayah markers.
- **Audio recitation playback** with verse-by-verse streaming.
- **Homelab Cloud Sync & Bookmarks** with offline-first synchronization.
- **Automatic In-App Updates**.

---

## ⬇️ Downloads

| Package | Platform | Latest Release | Download Link |
|---|---|---|---|
| **Android APK** | Android 8.0+ (API 26+) | **v1.0.13 (Build 14)** | [Download QuranOmar-release.apk](https://github.com/Omar-allahham/quran-omar-releases/releases/latest/download/QuranOmar-release.apk) |

---

## 🔐 Security & Signature Verification

All release APKs in this repository are signed with our verified release key.

- **Package Name**: `com.quran.omar`
- **Certificate SHA-256 Fingerprint**:
  ```text
  15:68:A9:66:6B:22:0B:F3:8B:95:29:B8:17:B8:EF:42:41:C8:CF:F5:E5:9A:03:A3:A8:80:80:B7:3D:E8:F0:D0
  ```
- **Signature Schemes**: APK Signature Scheme v1, v2, v3, and v4 (`apksigner` verified).

To verify the APK signature integrity:
```bash
apksigner verify --verbose QuranOmar-release.apk
```
