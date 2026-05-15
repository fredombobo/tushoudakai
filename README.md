# 隐私政策网页发布说明

华为后台要求隐私政策必须是公网可访问的 HTTPS URL，本地路径不能通过审核。

## 方式一：GitHub Pages

1. 新建一个公开 GitHub 仓库，例如 `tushou-checkin-privacy`。
2. 上传本目录里的 `index.html`。
3. 进入仓库 Settings -> Pages。
4. Source 选择主分支，目录选择根目录。
5. 保存后等待几分钟，GitHub 会给出一个 HTTPS 地址。
6. 打开地址确认能看到“徒手打卡隐私政策”。
7. 把该地址填入 AppGallery Connect 的“隐私政策网址”和“隐私权利网址”。

## 方式二：Gitee Pages 或自有网站

1. 把 `index.html` 上传到公开网站。
2. 确认链接以 `https://` 开头。
3. 用无痕窗口打开，确认不需要登录也能访问。
4. 把该链接填入 AppGallery Connect。

## 发布后要同步替换

发布成功后，把以下文件中的“待发布 HTTPS 链接”改成真实链接：

- `E:\CODEX\tushou-checkin-harmony\store\APPGALLERY_FIELDS.json`
- `E:\CODEX\tushou-checkin-harmony\store\PRIVACY_POLICY.md`
- `E:\CODEX\tushou-checkin-harmony\store\RELEASE_MATERIALS_INDEX.md`
