<div align="center">
    <!--<img width="200" src="logo.png" alt="logo"></br>-->
<img src="logo.svg" alt="nonebot-plugin-make-choice" width="300" />

# nonebot-plugin-make-choice

[NoneBot2](https://github.com/nonebot/nonebot2) 侧的随机选择插件，移植自 HoshinoBot

</div>

## 这是什么？

有选择困难症？让 Bot 帮你选！

发送 `选xx选xx` 或 `要xx要xx` 即可让 Bot 帮你做出选择

有小几率两个都帮你选哦

## 安装插件

使用 nb-cli 安装（推荐）

```shell
nb plugin install nonebot-plugin-make-choice
```

使用 pip/pipenv/poetry/pdm 安装

```shell
# pip
pip install nonebot-plugin-make-choice
# pipenv
pipenv install nonebot-plugin-make-choice
# poetry
poetry add nonebot-plugin-make-choice
# pdm
pdm add nonebot-plugin-make-choice
```

## 配置插件

本插件可以不用配置直接使用，唯一有效的配置项是同时选择两个选项的概率，默认为 `0.1`

```
choose_both_chance=0.1
```