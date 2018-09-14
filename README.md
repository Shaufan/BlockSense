# BlockSense — A Blockchain-based Decentralized Crowd-sensing System

#### Installation

```bash
$ npm install
```

#### Run it

```bash
$ npm start
```

#### FAQ

**Q:** Error: A dynamic link library (DLL) initialization routine failed
**A:** [https://github.com/electron/electron/issues/10193](https://github.com/electron/electron/issues/10193)
     [https://electronjs.org/docs/tutorial/using-native-node-modules](https://electronjs.org/docs/tutorial/using-native-node-modules)
     以及只有在`dependencies`中的modules才会被rebuild，还是失败的话检查一下package.json文件有没有写对

**Q:** How to use `sloc` and `js-ipfs` modules with Electron
**A:** [https://www.npmjs.com/package/solc#using-with-electron](https://www.npmjs.com/package/solc#using-with-electron)
     [https://electronjs.org/docs/faq](https://electronjs.org/docs/faq)

**Q:** npm install build `ERROR MSB4019`
**A:** [https://stackoverflow.com/questions/18774929/npm-install-g-karma-error-msb4019-the-imported-project-c-microsoft-cpp-defau](https://stackoverflow.com/questions/18774929/npm-install-g-karma-error-msb4019-the-imported-project-c-microsoft-cpp-defau)