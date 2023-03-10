# viaIR size issue

When calling an internal function multiple times using viaIR=true, the contract size increase drastically compared to using viaIR=false

With viaIR=true
```
 ·····················|··············|·················
 |  Test              ·      14.445  ·  
 ·····················|··············|·················
```
 With viaIR=false
```
  ·····················|··············|·················
 |  Test              ·       3.788  ·                │
 ·····················|··············|·················
```

## Getting Started

### Prerequisites

What things you need to install the software and how to install them

```bash
# Install nvm
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
# Install proper node version
nvm use
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```bash
# Install the dependencies
npm install
```

### Compile

Compile without viaIR
```bash
npm run compile
```

Compile with viaIR
```bash
npm run compile-viair
```
## Built With

* [Hardhat](https://hardhat.org/) - Task runner

