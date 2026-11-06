# AIM LAB 瞄準訓練場

這是一個免安裝、無需建置步驟的靜態網站。

## 發布到 GitHub Pages

1. 將本資料夾中的 `index.html`、`.github/workflows/pages.yml` 和本說明上傳到一個公開的 GitHub 儲存庫。
2. 儲存庫若使用 `main` 或 `master` 作為預設分支，推送檔案後便會自動部署。若使用其他分支，請在 `pages.yml` 的 `push.branches` 加入該分支名稱。
3. 在儲存庫開啟 **Settings → Pages**，將 **Build and deployment → Source** 設為 **GitHub Actions**。
4. 前往 **Actions** 確認「Deploy static site to GitHub Pages」工作流程完成。網站網址會顯示在部署結果中，通常是 `https://<帳號>.github.io/<儲存庫名稱>/`。

之後推送到 `main` 或 `master` 的變更都會自動重新發布。
