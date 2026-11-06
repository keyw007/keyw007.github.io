# keyw007.github.io

放 tripsplit 的 Firebase 登入元件（`__/auth/`、`__/firebase/init.json`）。
tripsplit 的 `authDomain` 設成 `keyw007.github.io`，Google 登入用 redirect 才能在 iPhone 主畫面 App 裡完成。
這些檔案從 `https://tripsplit-86d7e.firebaseapp.com/__/...` 複製過來，用 Actions 的「更新 Firebase 登入元件」重新抓取。
`__/firebase/init.json` 是手寫的（tripsplit-86d7e 沒部署過 Hosting，官方來源是 404），內容同 tripsplit 的 firebaseConfig。
`.nojekyll` 必須保留，否則 GitHub Pages 會略過底線開頭的資料夾。
