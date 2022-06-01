# 即时设计插件 API 类型

此仓库包含即时设计插件 API 类型包。

## 用法

1. 安装
    ```sh
    npm i --save-dev @jsdesigndeveloper/plugin-typings
    # or
    yarn add -D @jsdesigndeveloper/plugin-typings
    ```

2. 配置 _tsconfig.json_
    ```js
    {
        "compilerOptions": {
            "typeRoots": [
                "./node_modules/@types",
                "./node_modules/@jsdesigndeveloper"
            ]
        }
    }
    ```
