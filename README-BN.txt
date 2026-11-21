প্রভাত Sales PWA

ফাইলসমূহ:
- index.html: আপনার দেওয়া মূল অ্যাপ; নীল/সায়ান ডিজাইন ও বিদ্যমান ফিচার রাখা হয়েছে।
- manifest.webmanifest: Android PWA পরিচিতি।
- service-worker.js: অফলাইন অ্যাপ শেল এবং নতুন ভার্সন চেক।
- icons/: অ্যাপ আইকন।

GitHub Pages-এ প্রকাশ:
1. ZIP extract করুন।
2. সব ফাইল/ফোল্ডার আপনার GitHub repository-এর root-এ আপলোড করুন (index.html root-এ থাকতে হবে)।
3. Commit changes দিন এবং GitHub Pages চালু রাখুন।
4. HTTPS-এ সাইট খুলে Android Chrome-এর menu থেকে 'Install app' / 'Add to Home screen' চাপুন.

গুরুত্বপূর্ণ সীমাবদ্ধতা:
- Firebase/সার্ভার/ডেটাবেস যুক্ত করা হয়নি।
- Product, Bank, Profile ও Report ডেটা browser localStorage-এ থাকে; ডিভাইস/ব্রাউজারভেদে আলাদা।
- Admin password-সহ HTML/localStorage-ভিত্তিক ব্যবস্থা নিরাপদ সার্ভার লগইন নয়। শেয়ার করা পাবলিক লিংকে গোপনীয় ডেটা রাখবেন না।
- অ্যাপ আপডেট: GitHub-এ নতুন index.html ও service-worker.js প্রকাশ হলে অনলাইন অবস্থায় পরেরবার খুললে নতুন কনটেন্ট নেওয়ার চেষ্টা করবে। প্রয়োজন হলে Chrome-এ পেজ reload করুন।
