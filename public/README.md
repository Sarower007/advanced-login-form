# public ফোল্ডার

এখানে **`shurjo.woff2`** ফন্ট ফাইলটি আছে।

`index.html`-এ `@font-face { font-family:'Surjo'; src:url('./public/shurjo.woff2') ... }`
দিয়ে এই ফন্টটি লোড করা হয়। ফাইলটি এখানে থাকায় পুরো অ্যাপ ও প্রিন্টে সূর্য ফন্ট
ব্যবহার হবে; কোনো কারণে না থাকলে স্বয়ংক্রিয়ভাবে Hind Siliguri / Noto Sans Bengali
ফন্টে ফলব্যাক করবে — অ্যাপ ভাঙবে না।

> নোট: `index.html`-এর `@font-face` রেফারেন্স ও এই ফাইলের নাম হুবহু এক
> (`shurjo.woff2`) হতে হবে।
