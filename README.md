# Kamen Rider Legends RPG — Android Native Prototype

## Keadaan projek
Ini ialah prototaip asas Android Native Kotlin + OpenGL ES 2.0. Ia menyediakan medan 3D primitif, HUD dan gelung combat asas. Ia bukan port Memory of Heroes dan tidak menggunakan aset rasmi Kamen Rider.

## Keperluan build
- Android Studio dengan Android SDK Platform 35
- JDK 17
- Android Gradle Plugin 8.7.3 / Kotlin 2.0.21
- Peranti Android API 23+ yang menyokong OpenGL ES 2.0

## Build APK
1. Buka folder projek ini dalam Android Studio.
2. Tunggu Gradle Sync selesai.
3. Pilih Build > Build Bundle(s) / APK(s) > Build APK(s).
4. APK debug biasanya berada di `app/build/outputs/apk/debug/app-debug.apk`.

## Kawalan
ATTACK, DODGE, COUNTER, SKILL 1–4, ULTIMATE, BOSS, NORMAL, HENSHIN, CHEAT.

## Batasan prototaip
- Rider dan musuh ialah kubus placeholder, bukan model 3D sebenar.
- Animasi ialah status/timer combat, belum ada skeletal animation.
- Ultimate menetapkan pemasa cinematic, tetapi kamera sinematik sebenar belum dianimasikan.
- Dunia hanyalah arena rata, bukan open world.
- AI musuh mengejar dan menyerang menggunakan jarak serta cooldown asas.
- Senarai Rider ialah subset contoh, bukan roster rasmi lengkap.
- Belum ada audio, save/load, quest, inventori, collision dunia atau sistem level penuh.
- Belum diuji pada peranti fizikal; APK belum dibina dalam persekitaran ini.
