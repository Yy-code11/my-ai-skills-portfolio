# 小白版：如何把这个项目上传到 GitHub

你现在要做的事情只有一个：

> 在 GitHub 上新建一个仓库，然后把这个文件夹里的内容上传进去。

## 第 0 步：先解压

下载 zip 后，双击解压，得到文件夹：

```text
my-four-ai-skills-portfolio
```

注意：里面有一个 `.github` 文件夹。Mac 默认可能看不到以点开头的文件夹。

如果看不到 `.github`：

```text
按 Command + Shift + .
```

就可以显示隐藏文件。

## 第 1 步：登录 GitHub

打开 GitHub 网站，登录你的账号。

## 第 2 步：新建仓库

右上角点 `+`，选择 `New repository`。

建议填写：

```text
Repository name:
my-ai-skills-portfolio
```

Description 可以写：

```text
A personal AI workflow skills portfolio for resume translation, finance briefing, WeChat sticker processing, and academic writing review.
```

Visibility：

- 想放作品集：选 Public
- 还没想公开：选 Private

然后点击 `Create repository`。

## 第 3 步：上传文件

进入新仓库后，点：

```text
Add file → Upload files
```

然后把解压后的文件夹内容拖进去。

要上传的是文件夹里面的内容，不是把 zip 包直接传上去。

必须确认这些文件被上传：

```text
README.md
index.html
.github/skills/resume-english-translation/SKILL.md
.github/skills/daily-finance-briefing/SKILL.md
.github/skills/wechat-sticker-processing/SKILL.md
.github/skills/academic-paper-review/SKILL.md
docs/github-step-by-step.md
docs/how-to-use.md
prompts/codex-improve-this-repo.txt
```

## 第 4 步：提交

页面下方会有一个 commit message，可以写：

```text
Add initial AI skills portfolio
```

然后点：

```text
Commit changes
```

## 第 5 步：检查

上传后，GitHub 首页应该自动显示 README。

你点开：

```text
.github/skills/
```

应该能看到 4 个 skill 文件夹。

## 可选：开启 GitHub Pages

如果你想让 `index.html` 变成一个可以打开的网页：

1. 进入仓库
2. 点 `Settings`
3. 左边点 `Pages`
4. Source 选择 `Deploy from a branch`
5. Branch 选择 `main`
6. Folder 选择 `/root`
7. Save

等一会儿，GitHub 会给你一个网页链接。
