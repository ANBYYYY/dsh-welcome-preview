# JARVFF 预览版

**Just A Rather Very Fat Fish.**

给 DeepSeek Harness（DSH）用户的一组 Windows 本地工具：把已保存的网页转成 Markdown、修改文件前留快照、记录项目进度供新会话接着做。

### [下载 Windows 预览版 ↓](<https://github.com/ANBYYYY/jarvff/releases/download/final-rc-20261128-02/dsh-friend-final-candidate.zip>)

这是**脚本与指南包**，不是独立桌面应用，也不包含 DSH。运行脚本需要已有稳定版 **Node.js ≥18.17.0**；仅阅读指南不需要。

## 开始使用

1. **解压**到一个空白、可写的独立目录，打开根目录的 `从这里开始.md`。
2. **交给 DSH 助手**：把下面这句话中的路径和任务换成自己的，再发送。

   > 请先阅读 `完整解压路径/从这里开始.md`。我想做：＿＿。先告诉我怎么用、会生成哪些文件，再开始执行。

3. **按任务选工具**：网页转换处理本地 HTML；快照和交接按指南使用。解压不会自动接入 DSH，也不会自动安装依赖或更改全局设置。

<details>
<summary>想先试一个网页转换演示？</summary>

确认已安装所需 Node.js 后，运行解压目录中的 `welcome/first-use/run-first-use.cmd`。它转换包内自带样页，结果生成在 `welcome/first-use/out/`，不需要拿自己的文件试手。

转换自己的网页时，请先把网页保存为本地 HTML；这个工具不直接联网抓取网址。遇到依赖缺失或系统拦截就先停下，不要绕过安全策略。

</details>

## 试用前知道

这是**非稳定预览版**，目前只在 Windows / Node.js 24.19.0 下做过有限验证。陌生用户完整使用流程和失败恢复时保住新增数据尚未实测，请在独立目录试用并保留备份。

[发布说明与下载校验](<https://github.com/ANBYYYY/jarvff/releases/tag/final-rc-20261128-02>) · [反馈问题](<https://github.com/ANBYYYY/jarvff/issues>)

---

独立社区项目，与深度求索（DeepSeek）无隶属或授权关系。自写代码采用包内 MIT 许可，第三方内容按各自许可。
