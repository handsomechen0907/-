# 学习笔记 · 单词本

WorkBuddy 工作空间里出现过、值得记下来的英文词。

不是词典，是**用过一遍之后往回捞**的东西。所以每条尽量带上它出现的原句，光背中文意思不长记性。

## 目录

| 文件 | 内容 |
| --- | --- |
| [`words/writing-avoid.md`](words/writing-avoid.md) | 作文里**不要用**的 AI 高频词（反查表） |

> 新增词表时在 `words/` 下建一个 `.md`，然后把文件名补进上表。

## 文件约定

每个词表文件建议用同样的表格结构，方便以后统一检索：

| 词 | 词性 | 中文 | 原句 / 用法 | 熟练 |
| --- | --- | --- | --- | --- |
| example | n. | 例子 | 待补 | |

- **原句**尽量写真实出处那句，比孤立释义好记。
- **熟练**列空着 = 还没复习过；复习过一轮再打勾。
- 新词追加到表格末尾，不删旧条目。

## 远端

GitHub：<https://github.com/handsomechen0907/xiaodanta>

- 远端走 SSH（`git@github.com:handsomechen0907/xiaodanta.git`），不走 HTTPS——该网络下 HTTPS 会遇到证书吊销检查报错 `CRYPT_E_NO_REVOCATION_CHECK`。
- 本地 `main` 已设置 upstream 追踪 `origin/main`，直接 `git push` / `git pull` 即可。
- 想在 VS Code 里同步：左下角状态栏云朵图标，或源代码管理面板的 `...` → 拉取/推送。

## 本地位置

`D:\wb\xiaodanta`（桌面「学习软件」文件夹里的 `git.lnk` 双击可直接进入）
