BBF POS - GitHub Actions Ready Android Project
==============================================

Is ZIP mein aapka poora Android WebView project + GitHub Actions workflow (.github/workflows/build-apk.yml) + latest index.html pehle se set hai.

Mobile se 2 minute mein APK kaise banayein:
1. Is ZIP file ko apne phone mein Extract karein.
2. GitHub (github.com) par login karein aur ek New Repository banayein (e.g., BBF-POS-App).
3. Repository mein "uploading an existing file" par click karein aur extract kiye gaye folder ke andar ki saari files aur folders (.github, app, build.gradle, settings.gradle, gradle.properties) upload karke Commit karein.
4. Repository ke upar "Actions" tab par jayein -> "Build BBF POS APK" workflow chalega (ya "Run workflow" dabayein).
5. Build complete (Green Tick) hone ke baad neeche "Artifacts" section mein "BBF-POS-APK" par click karke download karein.
6. Downloaded ZIP ko extract karein — andar app-debug.apk milega, use phone mein install kar lein!

Included Features in APK:
- Live Camera Barcode Scanner (HTTPS WebViewAssetLoader + Runtime Camera Permission)
- Direct Receipt & Report Print (Android PrintManager + Thermal Printer support)
- JSON Backup, CSV & PDF File Downloads (Saved directly to phone's Downloads folder)
- Offline LocalStorage Persistence
