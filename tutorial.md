## 1. [前置教程](https://github.com/HuangDDU/HuangDDU.github.io.tailwind/blob/main/toturial.md)

1. 安装指定版本的Hugo（scoop之于windows相当于apt之于Ubuntu）

   ```bash
   # 删除旧版本
   scoop uninstall hugo-extended
   # 安装新版本
   scoop install hugo-extended@0.123.3
   ```

2. 执行并且本地查看

   ```bash
    hugo server -D
    ```

## 2. 内容调整

1. 简化导航栏：`config\_default\menus.yaml`
2. 简化章节：`content\_index.md`
3. 修改主页: `content\authors\admin`
4. 调整文献：
