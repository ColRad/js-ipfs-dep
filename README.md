Compile a js-ipfs binary as a dependency of your project
========================================================

# Installation

```
npm install js-ipfs-dep --save
```

## Development

**Warning**: The binary gets put in the `pkg` folder inside the module folder.

### Which js-ipfs version is used?

Currently only tested for ipfs 0.34.4, v0.35.0-rc.0, v0.38.0

But it can be specified in `package.json`.
Modify the ipfs version, eg:

```json
"ipfs": "v0.35.0-rc.0",
```

### Target/Platform

The binary is compiled against your current platform/node version eg. `node8-linux-x64` 