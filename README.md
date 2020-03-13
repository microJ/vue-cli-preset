# vue-cli-preset

预制好的 vue-cli-service create 用 preset

- 跳过 git 初始化
- 使用 yarn
- 使用淘宝 npm 源
- 预设 less, babel, typescript, router, vuex, eslint, prettier, unit-mocha, e2e-cypress

## Usage

`vue create -n -m yarn -r https://registry.npm.taobao.org -p https://raw.githubusercontent.com/microJ/vue-cli-preset/master/preset.json <project_name>`

或者

`vue create -n -m yarn -r https://registry.npm.taobao.org -i '{"useConfigFiles":true,"plugins":{"@vue/cli-plugin-babel":{},"@vue/cli-plugin-typescript":{"classComponent":true,"useTsWithBabel":true},"@vue/cli-plugin-router":{"historyMode":true},"@vue/cli-plugin-vuex":{},"@vue/cli-plugin-eslint":{"config":"prettier","lintOn":["save","commit"]},"@vue/cli-plugin-unit-mocha":{},"@vue/cli-plugin-e2e-cypress":{}},"cssPreprocessor":"less"}' <project_name>`
