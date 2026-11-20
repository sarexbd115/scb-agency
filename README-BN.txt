SCB AGENCY - PWA prototype

এই প্যাকেজটি এখনো local/offline prototype। পোস্ট, মন্তব্য, সদস্য ও ঘোষণা একই ডিভাইসের browser storage-এ থাকে। অন্য সদস্যের ফোনে ডেটা sync হয় না।

GitHub Pages-এ প্রকাশ:
1. ZIP Extract করো।
2. GitHub repository scb-agency খুলে Add file > Upload files নির্বাচন করো।
3. ZIP-এর ভেতরের সব 6টি ফাইল একসাথে upload করো: index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png, README-BN.txt।
4. Commit changes চাপো।
5. Settings > Pages > Deploy from a branch > main > /(root) > Save নির্বাচন করো।
6. প্রকাশিত HTTPS লিংক Chrome-এ খুলে Add to Home screen নির্বাচন করো।

নিরাপত্তা ও সীমাবদ্ধতা:
- এটি এখনো real multi-user app নয়।
- Login, invite approval, cloud database, real-time messaging নেই।
- গোপন তথ্য বা ব্যক্তিগত সদস্য-তথ্য এই prototype-এ রেখো না।
- বাস্তব private community করতে পরে secure authentication, database এবং access rules যোগ করতে হবে।
