## `D3React Test/Learning`

Download and setup:

```
git https://github.com/rbojha/D3React.git D3React && cd $_
export PATH=$PWD/node_modules/.bin:$PATH
```

Setup:

```
npm install
npm install -g live-server

npm install -g grunt-cli 
npm install --save-dev grunt 
npm install --save-dev grunt-browserify 
npm install --save-dev grunt-contrib-less 
npm install --save-dev grunt-contrib-watch 
npm install --save-dev jit-grunt 
npm install --save-dev reactify

```

Run:

```
grunt
live-server (in another terminal window)
```

`gulp watch` can be used to recompile on the fly
