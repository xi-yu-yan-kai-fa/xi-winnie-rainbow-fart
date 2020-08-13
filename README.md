<h1 align="center">
⭐️ 大独裁者 ⭐️ 習近平小熊維尼 ⭐️ 习近平 ⭐️ 小熊维尼 ⭐️ rainbow-fart ⭐️ 语音包 ⭐️
</h1>

<p align="center">
<strong>「 這個宇宙太瘋狂 」</strong>
</p>

---

这是一个 vscode 彩虹屁🌈插件 [vscode-rainbow-fart](https://github.com/SaekiRaku/vscode-rainbow-fart) 的语音扩展包 (支持 `JS` `TS` `python` `golang`)

**光復香港 時代革命**


## Preview

语音文件: [voices/](./voices/)

关键词语音列表: [keywords-voices.yml](./keywords-voices.yml)


## Install

在 vscode-rainbow-fart(v1.2.3) 中引入语音包是需要打包成 zip 然后引用的，

**本项目已经提供了打包好的文件，可以直接在 [Releases](https://github.com/xi-yu-yan-kai-fa/xi-winnie-rainbow-fart/releases) 中下载最新版 zip；**

(或者作为开发者从[本仓库](https://github.com/xi-yu-yan-kai-fa/xi-winnie-rainbow-fart) clone 后自己手动把相关资源打包成 zip (`npm run build`)。)

然后在本地 vscode 启动的 rainbow-fart 配置页面中 `Settings` -> `Voice Packages` -> `Import` 中导入 zip，导入后需要点 enable 开关开启使用；

## Customize

导入后可以在页面上打开音频文件夹然后编辑 `manifest.json` 来简单自定义**修改触发关键词和语音**，

如果觉得触发太频繁可以手动删掉一些关键词，或者**把某些关键词改成错误拼写** (目前内置了一些常见 typo)，**五大诉求，缺一不可**


## Dev & Contribute

目前[关键词和语音](./keywords-voices.yml)意思不太对应，希望众五毛战狼放出，完善一下语音和对应关键词，让习大大骂得更爽一点。

切分的语音全都放在 [voices/](./voices/) 目录下了

开发时对于触发关键词的只需要改 [keywords-voices.yml](./keywords-voices.yml) 文件，

因为拆分了关键词和语音配置，所以做了一些打包流程，依赖 nodejs；

常规本地构建 (打包产出在 `./dist/` 中)：

```bash
npm ci
npm run build
```

## Ref

- [vscode-rainbow-fart](https://github.com/SaekiRaku/vscode-rainbow-fart)

