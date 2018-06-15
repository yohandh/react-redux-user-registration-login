Yohan Hirimuthugoda@DESKTOP-KGIG8I4 MINGW64 /c/React/Learn
$ git clone https://github.com/cornflourblue/react-redux-registration-login-example
Cloning into 'react-redux-registration-login-example'...
remote: Counting objects: 128, done.
remote: Compressing objects: 100% (13/13), done.
remote: Total 128 (delta 4), reused 8 (delta 4), pack-reused 111
Receiving objects: 100% (128/128), 141.16 KiB | 258.00 KiB/s, done.
Resolving deltas: 100% (47/47), done.

Yohan Hirimuthugoda@DESKTOP-KGIG8I4 MINGW64 /c/React/Learn
$ cd react-redux-registration-login-example/

Yohan Hirimuthugoda@DESKTOP-KGIG8I4 MINGW64 /c/React/Learn/react-redux-registration-login-example (master)
$ npm install

> uglifyjs-webpack-plugin@0.4.6 postinstall C:\React\Learn\react-redux-registration-login-example\node_modules\uglifyjs-webpack-plugin
> node lib/post_install.js

npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.2.4 (node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.4: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})

added 751 packages in 211.967s

$ npm start

> react-redux-registration-login-example@1.0.0 start C:\React\Learn\react-redux-registration-login-example
> webpack-dev-server --open

Project is running at http://localhost:8080/
webpack output is served from /
404s will fallback to /index.html
webpack: wait until bundle finished: /
Hash: a253f4df5e1512010d52
Version: webpack 3.12.0
Time: 11619ms
     Asset       Size  Chunks                    Chunk Names
 bundle.js    1.43 MB       0  [emitted]  [big]  main
index.html  882 bytes          [emitted]
   [0] ./node_modules/react/index.js 190 bytes {0} [built]
  [11] ./node_modules/react-redux/es/index.js 230 bytes {0} [built]
  [17] ./src/_helpers/index.js 1.2 kB {0} [built]
  [50] multi (webpack)-dev-server/client?http://localhost:8080 ./src/index.jsx 40 bytes {0} [built]
  [51] (webpack)-dev-server/client?http://localhost:8080 7.93 kB {0} [built]
  [52] ./node_modules/url/url.js 23.3 kB {0} [built]
  [59] ./node_modules/strip-ansi/index.js 161 bytes {0} [built]
  [61] ./node_modules/loglevel/lib/loglevel.js 7.86 kB {0} [built]
  [62] (webpack)-dev-server/client/socket.js 1.08 kB {0} [built]
  [64] (webpack)-dev-server/client/overlay.js 3.67 kB {0} [built]
  [69] (webpack)/hot nonrecursive ^\.\/log$ 170 bytes {0} [built]
  [71] (webpack)/hot/emitter.js 77 bytes {0} [built]
  [73] ./src/index.jsx 600 bytes {0} [built]
  [76] ./node_modules/react-dom/index.js 1.36 kB {0} [built]
 [128] ./src/App/index.js 338 bytes {0} [built]
    + 146 hidden modules
Child html-webpack-plugin for "index.html":
     1 asset
       [0] ./node_modules/html-webpack-plugin/lib/loader.js!./src/index.html 1.23 kB {0} [built]
       [1] ./node_modules/lodash/lodash.js 540 kB {0} [built]
       [2] (webpack)/buildin/global.js 509 bytes {0} [built]
       [3] (webpack)/buildin/module.js 517 bytes {0} [built]
webpack: Compiled successfully.