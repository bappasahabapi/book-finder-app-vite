##    Run the project

- `npm i`
- `npm run dev`



# Github Maintain two remote url

##    mulltiple deploy

`npm run push`

- Vercel এ ফ্রি হোস্ট করার জন্য পার্সনাল একাউন্টের প্রাইভেট রিপোজিটরি 
## নিচের কমান্ড গুলো ফলো করুন :


- `git init`
- `git add .`
- `git commit -m "First commit"`
- `git branch -M main`

```
git remote add vercel YOUR_PERSONAL_ACCOUNT_REPOSITORY_HTTPS_URL

```

```
git remote add code BSB_CLASSROOM_REPOSITORY_HTTPS_URL

```

```
git push vercel main

```

```
git push code main

```

- মনে রাখবেন পুশ করার সময় খেয়াল রাখবেন আপনি কোন ব্রাঞ্চে আছেন আর কোন ব্রাঞ্চে পুশ করতেছে। **Git bash** Terminal এ দেখতে পারবেন আপনি কোন ব্রাঞ্চে আছেন বর্তমানে।
এরকম হলে ব্রাঞ্চ পরিবর্তন করে আবার পুশ করেন।

```
git branch -M main

```

এর পরেও না হলে:

- `.git` হিডেন ফোল্ডার ডিলিট দিয়ে আবার চেষ্টা করুন।

বিঃ দ্রঃ মনে রাখতে হবে কোনো কিছু পুশ করলে আপনাকে ২টা রিপোজিটরিতে পুশ করতে হবে। Deploy করার পরে গিটে আবার পুশ করলে vercel এ অটো আপডেট হয়ে যাবে।