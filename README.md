<a style="display: inline-block;" target="_blank" href="https://choosealicense.com/licenses/mit/">
  <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="MIT License">
</a>&nbsp;&nbsp;
<a style="display: inline-block;" target="_blank" href="https://github.com/sponsors/bruno-sartori">
  <img src="https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86" alt="Sponsor Bruno Sartori">
</a>&nbsp;&nbsp;
<a style="display: inline-block;" target="_blank" href="#">
  <img src="https://img.shields.io/badge/Build-Passing-green.svg" alt="Build Passing">
</a>

<h1 style="text-align: center;">GitHub Medium RSS</h1>

Show your recent published article from Medium on your Readme. See the live [demo](https://github.com/bruno-sartori).

![github-readme-medium-recent-article](https://raw.githubusercontent.com/bruno-sartori/github-medium-rss/main/example.jpg)

## Usage

Import this link in Readme as image source.

**Format:**
```bash
  https://github-medium-rss.vercel.app/medium/<medium-username>/<article-index>
```
- `medium-username`: your medium username/profile
- `article-index` : your recent article index. e.g: `0` means your latest article. 

#### Example
**Script in Readme.md**

```html
<a target="_blank" href="https://github-medium-rss.vercel.app/medium/@brunosartori.dev/0"><img src="https://github-medium-rss.vercel.app/medium/@brunosartori.dev/0" alt="Recent Article 0"> 

<a target="_blank" href="https://github-medium-rss.vercel.app/medium/@brunosartori.dev/2"><img src="https://github-medium-rss.vercel.app/medium/@brunosartori.dev/2" alt="Recent Article 2"> 

```
**Result**

<a target="_blank" href="https://github-medium-rss.vercel.app/medium/@brunosartori.dev/0"><img src="https://github-medium-rss.vercel.app/medium/@brunosartori.dev/0" alt="Recent Article 0">

<a target="_blank" href="https://github-medium-rss.vercel.app/medium/@brunosartori.dev/2"><img src="https://github-medium-rss.vercel.app/medium/@brunosartori.dev/2" alt="Recent Article 2">
