# Vue.js_GeekBrains
Vue.js base cource from GeekBrains

PowerShell Policies For VS Code https://docs.microsoft.com/ru-ru/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-7.2

Create Project: vue create gbvueproj

Vue-CLI Settings:
? Please pick a preset: Manually select features
? Check the features needed for your project: Babel, CSS Pre-processors, Linter
? Pick a CSS pre-processor (PostCSS, Autoprefixer and CSS Modules are supported by default): Sass/SCSS (with node-sass)
? Pick a linter / formatter config: Standard
? Pick additional lint features: (Press <space> to select, <a> to toggle all, <i> to invert selection)Lint on save
? Where do you prefer placing config for Babel, ESLint, etc.? In dedicated config files
? Save this as a preset for future projects? (y/N) N

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


