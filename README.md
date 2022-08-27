# Vue.js_GeekBrains
Vue.js base cource from GeekBrains

PowerShell Policies For VS Code https://docs.microsoft.com/ru-ru/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-7.2

Create Project: vue create gbvueproj

Vue CLI v5.0.8
? Please pick a preset: Manually select features
? Check the features needed for your project: Babel, CSS Pre-processors, Linter
? Choose a version of Vue.js that you want to start the project with 2.x
? Pick a CSS pre-processor (PostCSS, Autoprefixer and CSS Modules are supported by default): Sass/SCSS (with dart-sass)
? Pick a linter / formatter config: Standard
? Pick additional lint features: Lint on save
? Where do you prefer placing config for Babel, ESLint, etc.? In dedicated config files

cd gbvueproj

Run Server: npm run serve

Если не запустился, то  npm install. Идут ошибки - npm doctor подсказывает
npm -v                   not ok  Use npm v8.16.0
node -v                  not ok  Use node v16.16.0 (current: v16.13.0)

Установка новой версии npm: npm i npm
Установка новой версии ноды с официального сайта https://nodejs.org/en/blog/release/v16.16.0/

Управление версиями Node.js и NPM с помощью NVM https://habr.com/ru/company/timeweb/blog/541452/
nvm можно установить с помощью команд curl или wget:
$ curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash
$ wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash
Данная команда позволяет получить последнюю поддерживаемую версию npm для текущей версии Node.js:
$ nvm install-latest-npm
nvm use устанавливает нужную версию только для текущей оболочки. Если вы измените оболочку, только что обновленная версия node.js будет потеряна.

/*********************************************************************************************************** */
$ npm install --location=global @vue/cli
npm WARN deprecated source-map-url@0.4.1: See https://github.com/lydell/source-map-url#deprecated
npm WARN deprecated urix@0.1.0: Please see https://github.com/lydell/urix#deprecated
npm WARN deprecated source-map-resolve@0.5.3: See https://github.com/lydell/source-map-resolve#deprecated
npm WARN deprecated resolve-url@0.2.1: https://github.com/lydell/resolve-url#deprecated
npm WARN deprecated subscriptions-transport-ws@0.11.0: The `subscriptions-transport-ws` package is no longer maintained. We recommend you use `graphql-ws` instead. For help migrating Apollo software to `graphql-ws`, see https://www.apollographql.com/docs/apollo-server/data/subscriptions/#switching-from-subscriptions-transport-ws    For general help using `graphql-ws`, see https://github.com/enisdenjo/graphql-ws/blob/master/README.md

added 852 packages, and audited 853 packages in 1m

64 packages are looking for funding
  run `npm fund` for details

4 vulnerabilities (2 moderate, 2 high)

To address all issues (including breaking changes), run:
  npm audit fix --force

Run `npm audit` for details.
/*********************************************************************************************************** */

 INFO  Starting development server...


 ERROR  Failed to compile with 1 error                                                                                                        00:28:52

 error 

Conflict: Multiple assets emit different content to the same filename index.html

ERROR in Conflict: Multiple assets emit different content to the same filename index.html

webpack compiled with 1 error
/*********************************************************************************************************** */


