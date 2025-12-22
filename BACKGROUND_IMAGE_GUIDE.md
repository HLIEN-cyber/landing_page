# 更換背景圖片指南

## 快速步驟

1. **下載書牆圖片**
   前往以下任一網站下載免費高解析度書牆圖片：

   - [Unsplash](https://unsplash.com/s/photos/bookshelf) - 搜尋 "bookshelf" 或 "library"
   - [Pexels](https://www.pexels.com/search/bookshelf/) - 完全免費，無需註冊
   - [Pixabay](https://pixabay.com/images/search/bookshelf/) - 免費商用授權

2. **建議的圖片規格**
   - 解析度：至少 3000x2000 像素
   - 格式：JPG 或 PNG
   - 風格：溫暖的書牆、圖書館、或書架場景

3. **替換方式**

   **方法一：直接替換檔案**
   ```bash
   # 將下載的圖片重新命名並替換
   mv 你下載的圖片.jpg images/hero-bg.jpg
   ```

   **方法二：使用新檔名**
   如果你想使用不同的檔名（例如：bookshelf.jpg），請修改 `index.html` 第 68 行：
   ```html
   <!-- 從這個： -->
   <section id="home" data-parallax="scroll" data-image-src="images/hero-bg.jpg" ...>

   <!-- 改成： -->
   <section id="home" data-parallax="scroll" data-image-src="images/bookshelf.jpg" ...>
   ```

4. **提交變更**
   ```bash
   git add images/hero-bg.jpg  # 或你的新圖片檔名
   git commit -m "Update hero background to bookshelf image"
   git push -u origin claude/deploy-github-pages-h3DdA
   ```

## 推薦圖片範例

在 Unsplash 搜尋這些關鍵字可以找到很棒的書牆圖片：
- "library books"
- "bookshelf vintage"
- "old books"
- "book collection"
- "library shelves"

## 需要幫助？

如果需要我協助修改 HTML 指向新的圖片檔案，請告訴我你的圖片檔名！
