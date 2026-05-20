# Lung Cancer / NSCLC Trials 公開網站

這個資料夾是 GitHub Pages 發布用的 git repo，來源專案是上一層的 `lung_cancer_trials/`。

## 這裡放什麼

- `index.html`：公開網站首頁，由 `../generate_html.py` 從 `../lung_cancer.db` 產生並同步。
- `.github/workflows/pages.yml`：GitHub Pages 部署設定。

## 注意

- 這裡不是原始資料維護區；真正的資料庫在 `../lung_cancer.db`。
- 更新 trial 資料時，先回上一層修改資料庫並執行 `generate_html.py`，再到此資料夾提交與推送 `index.html`。
- 公開網站 repo：`itrytodoit-code/nsclc-trials`
- GitHub Pages：`https://itrytodoit-code.github.io/nsclc-trials/`
