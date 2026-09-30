# আল বারাকা জুয়েলার্স - সোনার হিসাব (Android)

## APK বানানোর সহজ উপায় (কম্পিউটারে কিছু ইনস্টল ছাড়াই)
1. github.com-এ বিনামূল্যে অ্যাকাউন্ট খুলুন, নতুন repository বানান (নাম: albaraka-gold)।
2. এই ফোল্ডারের সব ফাইল (লুকানো `.github` ফোল্ডারসহ) upload করুন।
3. repository-র **Actions** ট্যাবে যান → **Build APK** → **Run workflow**।
4. ৫-১০ মিনিট পর কাজ শেষ হলে সেই run-এর নিচে **Artifacts → AlBaraka-APK** ডাউনলোড করুন।
5. zip খুলে `app-debug.apk` ফোনে দিয়ে ইনস্টল করুন (Unknown sources অনুমতি লাগবে)।

## Android Studio দিয়ে
    npm install
    npx cap add android
    npx cap sync android
    npx cap open android   # Build > Build APK(s)

## কোড কোথায় বদলাবেন
সব লজিক ও ডিজাইন `www/index.html`-এ।
