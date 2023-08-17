# newProjectSkeleton
Steps to do:

Initialize node and install webpack (Required)
1. Run 'npm init' in console and it should create a package.json
2. Run 'npm install webpack webpack-cli --save-dev'

Intall style loaders, copy paste webpack configurations, copy paste gitignore (Required)
3. Run 'npm install --save-dev style-loader css-loader' to enable CSS, images, and fonts to load
4. Copy paste 'dist' folder, 'src' folder
5. Copy paste 'webpack.config.js'
6. Copy paste '.gitignore'

ESLint (Optional/Recommended)
7. Run 'npm init @eslint/config' to install ESLint. Go through steps. Choose Airbnb style for now
8. Go to .eslint.js. Under rules, paste this code:  no-plusplus': 'off',
9. Copy paste '.eslintignore' file

Prettier (Optional/Recommended)
10. Run 'npm install --save-dev --save-exact prettier' to install Prettier
11. Copy paste '.prettier.json'

If running ESLint and Prettier together
12. Run 'npm install --save-dev eslint-config-prettier'
13. Add 'prettier' to '.eslint.js' under extends
    Make sure it is an array, it should look like this:   extends: [ 'airbnb-base', 'prettier' ],

If you want o publish to git pages while using webpack in project
14. https://gist.github.com/cobyism/4730490
