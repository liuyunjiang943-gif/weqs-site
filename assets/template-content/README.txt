新素材临时放置区

1. 可以在这里新建 hero、works、logo 等英文文件夹。
2. 建议文件名只使用英文小写、数字和连字符，例如 project-01.jpg。
3. 放入 JPG、JPEG 或 PNG 后，在项目终端运行：
   npm run template:prepare
4. 转换后的 WebP 会保存在原图旁边，原图不会被删除。
5. 然后把对应的 /assets/template-content/... 路径填写到：
   src/content/siteConfig.ts
   src/content/homeConfig.ts
   src/content/showcases.ts
