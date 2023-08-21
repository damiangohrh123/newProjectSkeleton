# newProjectSkeleton <br />
Steps to do: <br />
<br />
Initialize node and install webpack (Required) <br />
1. Run 'npm init' in console and it should create a package.json <br />
2. Run 'npm install webpack webpack-cli --save-dev' <br />
<br />
Install style loaders, copy paste webpack configurations, copy paste gitignore (Required) <br />
3. Run 'npm install --save-dev style-loader css-loader' to enable CSS, images, and fonts to load <br />
4. Copy paste 'dist' folder, 'src' folder <br />
5. Copy paste 'webpack.config.js' <br />
6. Copy paste '.gitignore' <br />
<br />
ESLint (Optional/Recommended) <br />
7. Run 'npm init @eslint/config' to install ESLint. Go through steps. Choose Airbnb style for now <br />
8. Go to .eslint.js. Under rules, paste this code:  'no-plusplus': 'off', <br />
9. Copy paste '.eslintignore' file <br />
<br />
Prettier (Optional/Recommended) <br />
10. Run 'npm install --save-dev --save-exact prettier' to install Prettier <br />
11. Copy paste '.prettier.json' <br />
<br />
If running ESLint and Prettier together <br />
12. Run 'npm install --save-dev eslint-config-prettier' <br />
13. Add 'prettier' to '.eslint.js' under extends <br />
    Make sure it is an array, it should look like this:   extends: [ 'airbnb-base', 'prettier' ], <br />
<br />
If you want to publish to git pages while using webpack in project <br />
14. https://gist.github.com/cobyism/4730490 <br />
