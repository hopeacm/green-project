# 綠色社區平台 v1.0
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="創用 CC 授權條款" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />本著作係採用<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">創用 CC 姓名標示-非商業性-相同方式分享 4.0 國際 授權條款</a>授權.


环境配置：


    1、INSTALL NodeJS:
        sudo apt update
        sudo apt install nodejs
        sudo apt install npm
        nodejs -v

    2、INSTALL Visual Staudio Code：
        终端输入：https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme
    
    3、创建2个文件夹命名为starter、starter-react
        （1）在starter中打开终端：
            npm init
            配置参考下面：
            # EDIT package.json
            直接回车即可

            # CREATE server.js
            ####################
            const http = require('http');
            const hostname = '127.0.0.1';
            const port = 1337;
            http.createServer((req, res) => {
            res.writeHead(200, { 'Content-Type': 'text/plain' });
            res.end('Hello World\n');
            }).listen(port, hostname, () => {
            console.log(`Server running at http://${hostname}:${port}/`);
            });
            ####################
            node server.js
            # Server running at http://127.0.0.1:1337/
            # OPEN BROWSER URL htt
        （2）在starter-react打开终端：npm start
    
    4、运行是先打开readable、readable-apiServer的终端：npm start
