SURAJ TRADING TRACKER - APK BANANE KE STEPS (laptop/phone browser se, ~10 minute)

1. github.com par free account banao (agar nahi hai).
2. New repository banao (naam: trading-tracker, Public ya Private dono chalega).
3. "uploading an existing file" par click karo aur is ZIP ke ANDAR ki saari files/folders
   upload karo: www, package.json, capacitor.config.json aur .github folder.
   (Dhyan rakho: ".github/workflows/build-apk.yml" ka path bilkul waisa hi rehna chahiye.
    Agar .github folder upload nahi hota, toh "Add file > Create new file" mein naam likho
    .github/workflows/build-apk.yml aur uska text paste kar do.)
4. Commit karo. Upar "Actions" tab mein "Build APK" chalna shuru ho jayega (5-8 minute).
5. Green tick aane par us run par click karo, neeche "Artifacts" mein
   "Suraj-Trading-Tracker-APK" download karo. Zip kholo, andar app-debug.apk milega.
6. APK ko phone mein bhejo, install karo (Settings mein "Install unknown apps" allow karna padega).

NOTE: Trades phone ke andar hi save hote hain. App uninstall karoge toh data chala jayega.
