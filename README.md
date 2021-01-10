Minimal example of a [yeoman](https://yeoman.io/) generator written in typescript.
It is intended to be used as a template for new generators.

See https://github.com/yeoman/yeoman/issues/1734 for some background.

**Getting started** 
```bash
npm install -g yo
git clone https://github.com/gliviu/generator-typescript-template
cd generator-typescript-template
npm install
npm run build

# Link the package to global scope so that yeoman discovers the new generator
npm link

yo --generators # check the generator is in place

yo typescript-template argument1 --option2 secondOption

# Check that ./dummyfile.txt was created according to above CLI arguments

npm run watch    # build generator as development goes
```
