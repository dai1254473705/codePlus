# deno 学习

## 资源

|名称|链接|
|---|---|
|deno|https://deno.land/|
|markdown|https://www.runoob.com/markdown/md-table.html|
|项目地址|https://github.com/dai1254473705/deno-pro|
|deno版本管理工具|https://asdf-vm.com/#/|
|deno版本管理工具|https://github.com/asdf-community/asdf-deno|
|deno配置typescript|https://github.com/justjavac/typescript-deno-plugin#configuration|

## install

+ 通过homebrew: `brew install deno`
+ 指定版本：`curl -fsSL https://deno.land/x/install/install.sh | sh -s v0.38.0`

## vscode配置ts

> https://github.com/justjavac/typescript-deno-plugin#configuration


1. `yarn add -D typescript-deno-plugin typescript`
2. tsconfig.json

```sh
    {
    "compilerOptions": {
        "plugins": [
        {
            "name": "typescript-deno-plugin",
            "enable": true, // default is `true`
            "importmap": "import_map.json"
        }
        ]
    }
    }
```
3.




