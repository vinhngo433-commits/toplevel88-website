# toplevel88.com

Website of **TOP LEVEL 88 – Gội Đầu Đế Vương / 帝王洗头** (head spa & massage, 406 Nguyễn Công Trứ, District 1, Ho Chi Minh City).

Live site: https://www.toplevel88.com/ · Hosting: Netlify (deploys automatically from the `main` branch).

---

## English

### What this is
- A static one-page site in the `site/` folder: `index.html`, `robots.txt`, `sitemap.xml` and `img/` (25 photos). Only `site/` is published (see `netlify.toml`); this README is not.
- No CMS, no database, no build step. Open `site/index.html` in a browser to preview.

### How to make changes
1. **Never push to `main` directly.** Create a branch, commit your changes, open a **Pull Request**.
2. Netlify builds a **Deploy Preview** link for every Pull Request. Check it on mobile and desktop.
3. Describe in the Pull Request what you changed and why (SEO reason).
4. The shop owner reviews the preview and merges. Merging to `main` publishes the live site.
5. Group related changes into one Pull Request.

### Must stay unchanged (a Pull Request missing any of these will be sent back)
- Google Ads tag `AW-16682769167` in `<head>`, and the code that fires the 3 conversions on every **Call** (`tel:`), **WhatsApp/Zalo** and **Directions** button, including any new button you add.
- Main address `https://www.toplevel88.com/` in `canonical`, `og:url`, `sitemap.xml`, `robots.txt` and the JSON-LD data.
- Real shop facts: 406 Nguyễn Công Trứ, District 1; open 09:00–22:30 every day; phone / WhatsApp / Zalo 0814 179 022; the two price lists as they are now.
- Do not add prices, offers or promotions the owner has not approved.
- Logo: only the official gold logo (`img/logo.png`, `img/mark.png`, `img/icon.png`). Do not draw or generate a new logo.
- Photos: only real photos of the shop. No AI-generated images, no stock photos from the internet.
- Reviews quoted on the site: only real reviews from the shop's Google Maps profile.
- The WhatsApp booking button (pre-filled message) must keep working.

### Known SEO work (priority)
1. Split the 4 languages (EN / 中文 / 한국어 / Tiếng Việt) into 4 separate URLs with `hreflang` (today the language is switched by JavaScript on one URL, so Google only indexes English).
2. Mobile speed: PageSpeed mobile 67/100, LCP 12.3 s (large images, no modern formats / lazy loading).
3. Remove the hard-coded review count "207" (~15 places); the real count changes daily (231 on 26/11/2026).
4. Custom 404 page (currently Netlify default).

### Search Console
Domain property `toplevel88.com` is verified (DNS TXT record at the registrar). **Do not remove the `google-site-verification` TXT record.** Ask the owner for access with your Google account.

---

## 中文

### 网站说明
- 静态单页网站，位于 `site/` 文件夹：`index.html`、`robots.txt`、`sitemap.xml` 和 `img/`（25 张照片）。只有 `site/` 会被发布（见 `netlify.toml`），本 README 不会公开。
- 没有 CMS、没有数据库、无需构建。直接用浏览器打开 `site/index.html` 即可预览。

### 修改流程
1. **不要直接推送到 `main` 分支。** 请新建分支、提交修改，然后创建 **Pull Request**。
2. 每个 Pull Request 都会由 Netlify 自动生成 **预览链接（Deploy Preview）**，请在手机和电脑上检查。
3. 在 Pull Request 中写明修改了什么、以及 SEO 方面的原因。
4. 店主查看预览后合并（merge）。合并到 `main` 后正式网站自动更新。
5. 相关的修改请合并在同一个 Pull Request 里。

### 必须保持不变（缺少任何一项，Pull Request 会被退回）
- `<head>` 中的 Google Ads 代码 `AW-16682769167`，以及所有 **拨打电话**（`tel:`）、**WhatsApp/Zalo**、**导航** 按钮上触发 3 个转化的代码（新增按钮也必须加上）。
- 主网址 `https://www.toplevel88.com/`：用于 `canonical`、`og:url`、`sitemap.xml`、`robots.txt` 和 JSON-LD 数据。
- 店铺真实信息：地址 406 Nguyễn Công Trứ, 第一郡；每天 09:00–22:30 营业；电话 / WhatsApp / Zalo 0814 179 022；两张价目表保持现状。
- 未经店主同意，不得添加价格、优惠或促销信息。
- 标志：只能使用官方金色标志（`img/logo.png`、`img/mark.png`、`img/icon.png`），不得自行设计或用 AI 生成新标志。
- 图片：只能使用店铺真实照片。不得使用 AI 生成图片或网络图库图片。
- 网站上引用的评价：只能引用店铺 Google 地图上的真实评价。
- WhatsApp 预约按钮（预填消息）必须正常工作。

### 已知的 SEO 工作（优先级）
1. 将 4 种语言（EN / 中文 / 한국어 / Tiếng Việt）拆分为 4 个独立网址并添加 `hreflang`（目前在同一网址用 JavaScript 切换语言，Google 只收录英文）。
2. 移动端速度：PageSpeed 移动端 67/100，LCP 12.3 秒（图片过大，未使用新格式 / 延迟加载）。
3. 删除写死的评价数量 "207"（约 15 处）；真实数量每天变化（2026/11/26 为 231）。
4. 自定义 404 页面（目前为 Netlify 默认页面）。

### Search Console
域名资源 `toplevel88.com` 已通过验证（域名注册商处的 DNS TXT 记录）。**请勿删除 `google-site-verification` TXT 记录。** 如需访问，请把您的 Google 账号告诉店主。

---

## Tiếng Việt (cho chủ tiệm)
- Đội IT sửa trên nhánh riêng và mở **Pull Request**. Netlify tạo **link xem trước**.
- Anh/chị (hoặc Claude) xem link, kiểm tra mục "Bắt buộc giữ nguyên", thấy ổn thì bấm **Merge** → web thật đổi.
- Không ổn thì không bấm gì, web thật giữ nguyên.
