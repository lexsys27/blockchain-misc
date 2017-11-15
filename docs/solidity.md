# Solidity

Smart contract is a script running on the blockchain.

`.sol` - file extension

`Contract.sol` - suffix

Solidity programs are compiled to Ethereum Virtual Machine (EVM) code.

[Solidity on-line compiler][1] allows you to test contracts in the browser, fast
and cheap

Install syntax highlighting for Solidity:

```
git clone https://github.com/tomlion/vim-solidity.git ~/.vim/bundle/vim-solidity
```

I need `vim airline` + `syntastic` + some Solidity linter for syntax check

```
# Install vim airline
git clone https://github.com/vim-airline/vim-airline ~/.vim/bundle/vim-airline

# Install solhint and solium
npm install -g solium
npm install -g solhint

# Add following line to the .vimrc
let g:syntastic_solidity_checkers = ['solium', 'solhint']

```
[1]: https://ethereum.github.io/browser-solidity

