# Angular 4 app template
App created following the official angular tutorial @https://angular.io/docs/ts/latest/tutorial/

### Environment's configuration:
Install latest nodeJs version
npm install -g ionic
npm install -g cordova
npm install -g @angular/cli


### Install the app
npm install
npm install @angular/common@next @angular/compiler@next @angular/compiler-cli@next @angular/core@next @angular/forms@next @angular/http@next @angular/platform-browser@next @angular/platform-browser-dynamic@next @angular/platform-server@next @angular/router@next @angular/animations@next --save
npm install typescript@2.2.1 --save

### Just in Time (JiT) Compilation

Runs the TypeScript compiler and launches the app

```
npm start
```a

### Ahead of Time (AoT) Compilation

Runs the Angular AoT compiler, rollup, uglify for an optimized bundle, then launches the app

```
npm run start-aot
```

### AoT + gzip

Runs AoT plus gzips and launches the app

```
gulp copy-aot-gzip
npm run aot
npm run rollup
http-server
