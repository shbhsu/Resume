# myinfo

This is a jekyll webpage about myinfo.


# 建置環境 Development
## windows
1. clone this repo
2. install `chocolatey`
3. install `ruby` by `choco`
4. install `jekyll` by `gem`
5. run `jekyll serve` or `jekyll serve --drafts`
6. open browser to `127.0.0.1:4000`

push to github results to automatically render a static site for you

## mac
1. install `jekyll` by `gem`
2. run `jekyll serve` or `jekyll serve --drafts`
3. open browser to `127.0.0.1:4000`

# 檔案結構 Structure

## 站內資料 Data
- /_data/
  - aboutus.json
    - 關於我
  - experiences.json
    - 經歷
  - projects.json
    - 專案
  - skills.json
    - 技能
- /_config.yml
  - 資訊

## 頁面版型 Page
- /_layouts/
  - 版型可用之嵌入內容 [色碼可參考][2]
- /_includes/
  - page 可用之版型
- /pages/
  - 各頁 page
