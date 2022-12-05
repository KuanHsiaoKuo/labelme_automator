# Labelme自动化改造

- [使用pyinstaller打包Labelme中文版教程](https://dengzile.com/2022/04/%E4%BD%BF%E7%94%A8pyinstaller%E6%89%93%E5%8C%85labelme%E4%B8%AD%E6%96%87%E7%89%88%E6%95%99%E7%A8%8B/)

## 源码运行方式

```shell
python -m venv project_venv
source project_venv/bin/activate
pip install -r requirements.txt
python -m labelme
```

## 安装环境的问题

- No module named 'yaml'

```shell
pip install pyyaml

```

## Jetbrains配置模块执行

```shell
python -m labelme
```

- 对应jetbrains配置

![CleanShot 2022-12-05 at 12.59.39@2x](https://raw.githubusercontent.com/KuanHsiaoKuo/writing_materials/main/imgs/CleanShot%202022-12-05%20at%2012.59.39%402x.png)
