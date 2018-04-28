# Responsibly
Voting Application on Ganache
>Web3 = require('web3')
{ [Function: Web3]
  providers:
   { HttpProvider: [Function: HttpProvider],
     IpcProvider: [Function: IpcProvider] } }
> web3 = new Web3(new Web3.providers.HttpProvider("http://localhost:7545"));
Web3 {
  _requestManager:
   RequestManager {
     provider:
      HttpProvider {
        host: 'http://localhost:7545',
        timeout: 0,
        user: undefined,
        password: undefined },
     polls: {},
     timeout: null },
  currentProvider:
   HttpProvider {
     host: 'http://localhost:7545',
     timeout: 0,
     user: undefined,
     password: undefined },
  eth:
   Eth {
     _requestManager: RequestManager { provider: [Object], polls: {}, timeout: null },
     getBalance: { [Function: send] request: [Function: bound ], call: 'eth_getBalance' },
     getStorageAt: { [Function: send] request: [Function: bound ], call: 'eth_getStorageAt' },
     getCode: { [Function: send] request: [Function: bound ], call: 'eth_getCode' },
     getBlock: { [Function: send] request: [Function: bound ], call: [Function: blockCall] },
     getUncle: { [Function: send] request: [Function: bound ], call: [Function: uncleCall] },
     getCompilers: { [Function: send] request: [Function: bound ], call: 'eth_getCompilers' },
     getBlockTransactionCount:
      { [Function: send]
        request: [Function: bound ],
        call: [Function: getBlockTransactionCountCall] },
     getBlockUncleCount:
      { [Function: send]
        request: [Function: bound ],
        call: [Function: uncleCountCall] },
     getTransaction:
      { [Function: send]
        request: [Function: bound ],
        call: 'eth_getTransactionByHash' },
     getTransactionFromBlock:
      { [Function: send]
        request: [Function: bound ],
        call: [Function: transactionFromBlockCall] },
     getTransactionReceipt:
      { [Function: send]
        request: [Function: bound ],
        call: 'eth_getTransactionReceipt' },
     getTransactionCount: { [Function: send] request: [Function: bound ], call: 'eth_getTransactionCount' },
     call: { [Function: send] request: [Function: bound ], call: 'eth_call' },
     estimateGas: { [Function: send] request: [Function: bound ], call: 'eth_estimateGas' },
     sendRawTransaction: { [Function: send] request: [Function: bound ], call: 'eth_sendRawTransaction' },
     signTransaction: { [Function: send] request: [Function: bound ], call: 'eth_signTransaction' },
     sendTransaction: { [Function: send] request: [Function: bound ], call: 'eth_sendTransaction' },
     sign: { [Function: send] request: [Function: bound ], call: 'eth_sign' },
     compile: { solidity: [Object], lll: [Object], serpent: [Object] },
     submitWork: { [Function: send] request: [Function: bound ], call: 'eth_submitWork' },
     getWork: { [Function: send] request: [Function: bound ], call: 'eth_getWork' },
     coinbase: [Getter],
     getCoinbase: { [Function: get] request: [Function: bound ] },
     mining: [Getter],
     getMining: { [Function: get] request: [Function: bound ] },
     hashrate: [Getter],
     getHashrate: { [Function: get] request: [Function: bound ] },
     syncing: [Getter],
     getSyncing: { [Function: get] request: [Function: bound ] },
     gasPrice: [Getter],
     getGasPrice: { [Function: get] request: [Function: bound ] },
     accounts: [Getter],
     getAccounts: { [Function: get] request: [Function: bound ] },
     blockNumber: [Getter],
     getBlockNumber: { [Function: get] request: [Function: bound ] },
     protocolVersion: [Getter],
     getProtocolVersion: { [Function: get] request: [Function: bound ] },
     iban:
      { [Function: Iban]
        fromAddress: [Function],
        fromBban: [Function],
        createIndirect: [Function],
        isValid: [Function] },
     sendIBANTransaction: [Function: bound transfer] },
  db:
   DB {
     _requestManager: RequestManager { provider: [Object], polls: {}, timeout: null },
     putString: { [Function: send] request: [Function: bound ], call: 'db_putString' },
     getString: { [Function: send] request: [Function: bound ], call: 'db_getString' },
     putHex: { [Function: send] request: [Function: bound ], call: 'db_putHex' },
     getHex: { [Function: send] request: [Function: bound ], call: 'db_getHex' } },
  shh:
   Shh {
     _requestManager: RequestManager { provider: [Object], polls: {}, timeout: null },
     version: { [Function: send] request: [Function: bound ], call: 'shh_version' },
     info: { [Function: send] request: [Function: bound ], call: 'shh_info' },
     setMaxMessageSize: { [Function: send] request: [Function: bound ], call: 'shh_setMaxMessageSize' },
     setMinPoW: { [Function: send] request: [Function: bound ], call: 'shh_setMinPoW' },
     markTrustedPeer: { [Function: send] request: [Function: bound ], call: 'shh_markTrustedPeer' },
     newKeyPair: { [Function: send] request: [Function: bound ], call: 'shh_newKeyPair' },
     addPrivateKey: { [Function: send] request: [Function: bound ], call: 'shh_addPrivateKey' },
     deleteKeyPair: { [Function: send] request: [Function: bound ], call: 'shh_deleteKeyPair' },
     hasKeyPair: { [Function: send] request: [Function: bound ], call: 'shh_hasKeyPair' },
     getPublicKey: { [Function: send] request: [Function: bound ], call: 'shh_getPublicKey' },
     getPrivateKey: { [Function: send] request: [Function: bound ], call: 'shh_getPrivateKey' },
     newSymKey: { [Function: send] request: [Function: bound ], call: 'shh_newSymKey' },
     addSymKey: { [Function: send] request: [Function: bound ], call: 'shh_addSymKey' },
     generateSymKeyFromPassword:
      { [Function: send]
        request: [Function: bound ],
        call: 'shh_generateSymKeyFromPassword' },
     hasSymKey: { [Function: send] request: [Function: bound ], call: 'shh_hasSymKey' },
     getSymKey: { [Function: send] request: [Function: bound ], call: 'shh_getSymKey' },
     deleteSymKey: { [Function: send] request: [Function: bound ], call: 'shh_deleteSymKey' },
     post: { [Function: send] request: [Function: bound ], call: 'shh_post' } },
  net:
   Net {
     _requestManager: RequestManager { provider: [Object], polls: {}, timeout: null },
     listening: [Getter],
     getListening: { [Function: get] request: [Function: bound ] },
     peerCount: [Getter],
     getPeerCount: { [Function: get] request: [Function: bound ] } },
  personal:
   Personal {
     _requestManager: RequestManager { provider: [Object], polls: {}, timeout: null },
     newAccount: { [Function: send] request: [Function: bound ], call: 'personal_newAccount' },
     importRawKey: { [Function: send] request: [Function: bound ], call: 'personal_importRawKey' },
     unlockAccount: { [Function: send] request: [Function: bound ], call: 'personal_unlockAccount' },
     ecRecover: { [Function: send] request: [Function: bound ], call: 'personal_ecRecover' },
     sign: { [Function: send] request: [Function: bound ], call: 'personal_sign' },
     sendTransaction:
      { [Function: send]
        request: [Function: bound ],
        call: 'personal_sendTransaction' },
     lockAccount: { [Function: send] request: [Function: bound ], call: 'personal_lockAccount' },
     listAccounts: [Getter],
     getListAccounts: { [Function: get] request: [Function: bound ] } },
  bzz:
   Swarm {
     _requestManager: RequestManager { provider: [Object], polls: {}, timeout: null },
     blockNetworkRead: { [Function: send] request: [Function: bound ], call: 'bzz_blockNetworkRead' },
     syncEnabled: { [Function: send] request: [Function: bound ], call: 'bzz_syncEnabled' },
     swapEnabled: { [Function: send] request: [Function: bound ], call: 'bzz_swapEnabled' },
     download: { [Function: send] request: [Function: bound ], call: 'bzz_download' },
     upload: { [Function: send] request: [Function: bound ], call: 'bzz_upload' },
     retrieve: { [Function: send] request: [Function: bound ], call: 'bzz_retrieve' },
     store: { [Function: send] request: [Function: bound ], call: 'bzz_store' },
     get: { [Function: send] request: [Function: bound ], call: 'bzz_get' },
     put: { [Function: send] request: [Function: bound ], call: 'bzz_put' },
     modify: { [Function: send] request: [Function: bound ], call: 'bzz_modify' },
     hive: [Getter],
     getHive: { [Function: get] request: [Function: bound ] },
     info: [Getter],
     getInfo: { [Function: get] request: [Function: bound ] } },
  settings: Settings { defaultBlock: 'latest', defaultAccount: undefined },
  version:
   { api: '0.20.1',
     node: [Getter],
     getNode: { [Function: get] request: [Function: bound ] },
     network: [Getter],
     getNetwork: { [Function: get] request: [Function: bound ] },
     ethereum: [Getter],
     getEthereum: { [Function: get] request: [Function: bound ] },
     whisper: [Getter],
     getWhisper: { [Function: get] request: [Function: bound ] } },
  providers:
   { HttpProvider: [Function: HttpProvider],
     IpcProvider: [Function: IpcProvider] },
  _extend:
   { [Function: ex]
     formatters:
      { inputDefaultBlockNumberFormatter: [Function: inputDefaultBlockNumberFormatter],
        inputBlockNumberFormatter: [Function: inputBlockNumberFormatter],
        inputCallFormatter: [Function: inputCallFormatter],
        inputTransactionFormatter: [Function: inputTransactionFormatter],
        inputAddressFormatter: [Function: inputAddressFormatter],
        inputPostFormatter: [Function: inputPostFormatter],
        outputBigNumberFormatter: [Function: outputBigNumberFormatter],
        outputTransactionFormatter: [Function: outputTransactionFormatter],
        outputTransactionReceiptFormatter: [Function: outputTransactionReceiptFormatter],
        outputBlockFormatter: [Function: outputBlockFormatter],
        outputLogFormatter: [Function: outputLogFormatter],
        outputPostFormatter: [Function: outputPostFormatter],
        outputSyncingFormatter: [Function: outputSyncingFormatter] },
     utils:
      { padLeft: [Function: padLeft],
        padRight: [Function: padRight],
        toHex: [Function: toHex],
        toDecimal: [Function: toDecimal],
        fromDecimal: [Function: fromDecimal],
        toUtf8: [Function: toUtf8],
        toAscii: [Function: toAscii],
        fromUtf8: [Function: fromUtf8],
        fromAscii: [Function: fromAscii],
        transformToFullName: [Function: transformToFullName],
        extractDisplayName: [Function: extractDisplayName],
        extractTypeName: [Function: extractTypeName],
        toWei: [Function: toWei],
        fromWei: [Function: fromWei],
        toBigNumber: [Function: toBigNumber],
        toTwosComplement: [Function: toTwosComplement],
        toAddress: [Function: toAddress],
        isBigNumber: [Function: isBigNumber],
        isStrictAddress: [Function: isStrictAddress],
        isAddress: [Function: isAddress],
        isChecksumAddress: [Function: isChecksumAddress],
        toChecksumAddress: [Function: toChecksumAddress],
        isFunction: [Function: isFunction],
        isString: [Function: isString],
        isObject: [Function: isObject],
        isBoolean: [Function: isBoolean],
        isArray: [Function: isArray],
        isJson: [Function: isJson],
        isBloom: [Function: isBloom],
        isTopic: [Function: isTopic] },
     Method: [Function: Method],
     Property: [Function: Property] } }
> web3.eth.accounts['0x3F419db42Fb52A9c9520B0677bE88489C0e096Ca']
undefined
> web3.eth.accounts['0x3F419db42Fb52A9c9520B0677bE88489C0e096Ca,0x821694D070d007D8a062e0662252D9FFD6a68568,0xAf827CE65BD56cded2dC2710BD0155e22326a0C6']
undefined
> code = fs.readFileSync('Voting.sol').toString()
Error: ENOENT: no such file or directory, open 'E:\Projects\2_Blockchain\0_Angel-hack\voting\zastrin\Voting.sol'
    at Object.fs.openSync (fs.js:646:18)
    at Object.fs.readFileSync (fs.js:551:33)
> code = fs.readFileSync('chapter1/Voting.sol').toString()
'pragma solidity ^0.4.18;\r\n\r\ncontract Voting {\r\n\r\n  mapping (bytes32 => uint8) public votesReceived;\r\n  bytes32[] public candidateList;\r\n\r\n  function Voting(bytes32[] candidateNames) public {\r\n    candidateList = candidateNames;\r\n  }\r\n\r\n  function totalVotesFor(bytes32 candidate) view public returns (uint8) {\r\n    require(validCandidate(candidate));\r\n    return votesReceived[candidate];\r\n  }\r\n\r\n  function voteForCandidate(bytes32 candidate) public {\r\n    require(validCandidate(candidate));\r\n    votesReceived[candidate]  += 1;\r\n  }\r\n\r\n  function validCandidate(bytes32 candidate) view public returns (bool) {\r\n    for(uint i = 0; i < candidateList.length; i++) {\r\n      if (candidateList[i] == candidate) {\r\n        return true;\r\n      }\r\n    }\r\n    return false;\r\n   }\r\n}'
> solc = require('solc')
{ version: [Function],
  semver: [Function: versionToSemver],
  license: [Function],
  compile: [Function: compile],
  compileStandard: [Function: compileStandard],
  compileStandardWrapper: [Function: compileStandardWrapper],
  linkBytecode: [Function: linkBytecode],
  supportsMulti: true,
  supportsImportCallback: true,
  supportsStandard: true,
  loadRemoteVersion: [Function: loadRemoteVersion],
  setupMethods: [Function: setupMethods] }
>
> compiledCode = solc.compile(code)
{ contracts:
   { ':Voting':
      { assembly: [Object],
        bytecode: '608060405234801561001057600080fd5b50604051610412380380610412833981018060405281019080805182019291905050508060019080519060200190610049929190610050565b50506100c8565b828054828255906000526020600020908101928215610092579160200282015b82811115610091578251829060001916905591602001919060010190610070565b5b50905061009f91906100a3565b5090565b6100c591905b808211156100c15760008160009055506001016100a9565b5090565b90565b61033b806100d76000396000f30060806040526004361061006d576000357c0100000000000000000000000000000000000000000000000000000000900463ffffffff1680632f265cf714610072578063392e6678146100bd5780637021939f14610106578063b13c744b14610151578063cc9ab2671461019a575b600080fd5b34801561007e57600080fd5b506100a160048036038101908080356000191690602001909291905050506101cb565b604051808260ff1660ff16815260200191505060405180910390f35b3480156100c957600080fd5b506100ec6004803603810190808035600019169060200190929190505050610210565b604051808215151515815260200191505060405180910390f35b34801561011257600080fd5b50610135600480360381019080803560001916906020019092919050505061026f565b604051808260ff1660ff16815260200191505060405180910390f35b34801561015d57600080fd5b5061017c6004803603810190808035906020019092919050505061028f565b60405180826000191660001916815260200191505060405180910390f35b3480156101a657600080fd5b506101c960048036038101908080356000191690602001909291905050506102b2565b005b60006101d682610210565b15156101e157600080fd5b600080836000191660001916815260200190815260200160002060009054906101000a900460ff169050919050565b600080600090505b60018054905081101561026457826000191660018281548110151561023957fe5b90600052602060002001546000191614156102575760019150610269565b8080600101915050610218565b600091505b50919050565b60006020528060005260406000206000915054906101000a900460ff1681565b60018181548110151561029e57fe5b906000526020600020016000915090505481565b6102bb81610210565b15156102c657600080fd5b6001600080836000191660001916815260200190815260200160002060008282829054906101000a900460ff160192506101000a81548160ff021916908360ff160217905550505600a165627a7a72305820ce7b549e9d4b5aa2a71ceb8ff4e2bf0c1012122cf5facd81d0ac86f76ebf3a860029',
        functionHashes: [Object],
        gasEstimates: [Object],
        interface: '[{"constant":true,"inputs":[{"name":"candidate","type":"bytes32"}],"name":"totalVotesFor","outputs":[{"name":"","type":"uint8"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[{"name":"candidate","type":"bytes32"}],"name":"validCandidate","outputs":[{"name":"","type":"bool"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[{"name":"","type":"bytes32"}],"name":"votesReceived","outputs":[{"name":"","type":"uint8"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[{"name":"","type":"uint256"}],"name":"candidateList","outputs":[{"name":"","type":"bytes32"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"name":"candidate","type":"bytes32"}],"name":"voteForCandidate","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"inputs":[{"name":"candidateNames","type":"bytes32[]"}],"payable":false,"stateMutability":"nonpayable","type":"constructor"}]',
        metadata: '{"compiler":{"version":"0.4.23+commit.124ca40d"},"language":"Solidity","output":{"abi":[{"constant":true,"inputs":[{"name":"candidate","type":"bytes32"}],"name":"totalVotesFor","outputs":[{"name":"","type":"uint8"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[{"name":"candidate","type":"bytes32"}],"name":"validCandidate","outputs":[{"name":"","type":"bool"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[{"name":"","type":"bytes32"}],"name":"votesReceived","outputs":[{"name":"","type":"uint8"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[{"name":"","type":"uint256"}],"name":"candidateList","outputs":[{"name":"","type":"bytes32"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"name":"candidate","type":"bytes32"}],"name":"voteForCandidate","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"inputs":[{"name":"candidateNames","type":"bytes32[]"}],"payable":false,"stateMutability":"nonpayable","type":"constructor"}],"devdoc":{"methods":{}},"userdoc":{"methods":{}}},"settings":{"compilationTarget":{"":"Voting"},"evmVersion":"byzantium","libraries":{},"optimizer":{"enabled":false,"runs":200},"remappings":[]},"sources":{"":{"keccak256":"0xde6cf275417e4c710ac69f0c4b805d6a4165c9bf07fa59f1ee66b68b87fa50a7","urls":["bzzr://0bca55eb1a57cf6b176a2c2755193f56458daad08dcd5b68fdae1b0efe8b9d26"]}},"version":1}',
        opcodes: 'PUSH1 0x80 PUSH1 0x40 MSTORE CALLVALUE DUP1 ISZERO PUSH2 0x10 JUMPI PUSH1 0x0 DUP1 REVERT JUMPDEST POP PUSH1 0x40 MLOAD PUSH2 0x412 CODESIZE SUB DUP1 PUSH2 0x412 DUP4 CODECOPY DUP2 ADD DUP1 PUSH1 0x40 MSTORE DUP2 ADD SWAP1 DUP1 DUP1 MLOAD DUP3 ADD SWAP3 SWAP2 SWAP1 POP POP POP DUP1 PUSH1 0x1 SWAP1 DUP1 MLOAD SWAP1 PUSH1 0x20 ADD SWAP1 PUSH2 0x49 SWAP3 SWAP2 SWAP1 PUSH2 0x50 JUMP JUMPDEST POP POP PUSH2 0xC8 JUMP JUMPDEST DUP3 DUP1 SLOAD DUP3 DUP3 SSTORE SWAP1 PUSH1 0x0 MSTORE PUSH1 0x20 PUSH1 0x0 KECCAK256 SWAP1 DUP2 ADD SWAP3 DUP3 ISZERO PUSH2 0x92 JUMPI SWAP2 PUSH1 0x20 MUL DUP3 ADD JUMPDEST DUP3 DUP2 GT ISZERO PUSH2 0x91 JUMPI DUP3 MLOAD DUP3 SWAP1 PUSH1 0x0 NOT AND SWAP1 SSTORE SWAP2 PUSH1 0x20 ADD SWAP2 SWAP1 PUSH1 0x1 ADD SWAP1 PUSH2 0x70 JUMP JUMPDEST JUMPDEST POP SWAP1 POP PUSH2 0x9F SWAP2 SWAP1 PUSH2 0xA3 JUMP JUMPDEST POP SWAP1 JUMP JUMPDEST PUSH2 0xC5 SWAP2 SWAP1 JUMPDEST DUP1 DUP3 GT ISZERO PUSH2 0xC1 JUMPI PUSH1 0x0 DUP2 PUSH1 0x0 SWAP1 SSTORE POP PUSH1 0x1 ADD PUSH2 0xA9 JUMP JUMPDEST POP SWAP1 JUMP JUMPDEST SWAP1 JUMP JUMPDEST PUSH2 0x33B DUP1 PUSH2 0xD7 PUSH1 0x0 CODECOPY PUSH1 0x0 RETURN STOP PUSH1 0x80 PUSH1 0x40 MSTORE PUSH1 0x4 CALLDATASIZE LT PUSH2 0x6D JUMPI PUSH1 0x0 CALLDATALOAD PUSH29 0x100000000000000000000000000000000000000000000000000000000 SWAP1 DIV PUSH4 0xFFFFFFFF AND DUP1 PUSH4 0x2F265CF7 EQ PUSH2 0x72 JUMPI DUP1 PUSH4 0x392E6678 EQ PUSH2 0xBD JUMPI DUP1 PUSH4 0x7021939F EQ PUSH2 0x106 JUMPI DUP1 PUSH4 0xB13C744B EQ PUSH2 0x151 JUMPI DUP1 PUSH4 0xCC9AB267 EQ PUSH2 0x19A JUMPI JUMPDEST PUSH1 0x0 DUP1 REVERT JUMPDEST CALLVALUE DUP1 ISZERO PUSH2 0x7E JUMPI PUSH1 0x0 DUP1 REVERT JUMPDEST POP PUSH2 0xA1 PUSH1 0x4 DUP1 CALLDATASIZE SUB DUP2 ADD SWAP1 DUP1 DUP1 CALLDATALOAD PUSH1 0x0 NOT AND SWAP1 PUSH1 0x20 ADD SWAP1 SWAP3 SWAP2 SWAP1 POP POP POP PUSH2 0x1CB JUMP JUMPDEST PUSH1 0x40 MLOAD DUP1 DUP3 PUSH1 0xFF AND PUSH1 0xFF AND DUP2 MSTORE PUSH1 0x20 ADD SWAP2 POP POP PUSH1 0x40 MLOAD DUP1 SWAP2 SUB SWAP1 RETURN JUMPDEST CALLVALUE DUP1 ISZERO PUSH2 0xC9 JUMPI PUSH1 0x0 DUP1 REVERT JUMPDEST POP PUSH2 0xEC PUSH1 0x4 DUP1 CALLDATASIZE SUB DUP2 ADD SWAP1 DUP1 DUP1 CALLDATALOAD PUSH1 0x0 NOT AND SWAP1 PUSH1 0x20 ADD SWAP1 SWAP3 SWAP2 SWAP1 POP POP POP PUSH2 0x210 JUMP JUMPDEST PUSH1 0x40 MLOAD DUP1 DUP3 ISZERO ISZERO ISZERO ISZERO DUP2 MSTORE PUSH1 0x20 ADD SWAP2 POP POP PUSH1 0x40 MLOAD DUP1 SWAP2 SUB SWAP1 RETURN JUMPDEST CALLVALUE DUP1 ISZERO PUSH2 0x112 JUMPI PUSH1 0x0 DUP1 REVERT JUMPDEST POP PUSH2 0x135 PUSH1 0x4 DUP1 CALLDATASIZE SUB DUP2 ADD SWAP1 DUP1 DUP1 CALLDATALOAD PUSH1 0x0 NOT AND SWAP1 PUSH1 0x20 ADD SWAP1 SWAP3 SWAP2 SWAP1 POP POP POP PUSH2 0x26F JUMP JUMPDEST PUSH1 0x40 MLOAD DUP1 DUP3 PUSH1 0xFF AND PUSH1 0xFF AND DUP2 MSTORE PUSH1 0x20 ADD SWAP2 POP POP PUSH1 0x40 MLOAD DUP1 SWAP2 SUB SWAP1 RETURN JUMPDEST CALLVALUE DUP1 ISZERO PUSH2 0x15D JUMPI PUSH1 0x0 DUP1 REVERT JUMPDEST POP PUSH2 0x17C PUSH1 0x4 DUP1 CALLDATASIZE SUB DUP2 ADD SWAP1 DUP1 DUP1 CALLDATALOAD SWAP1 PUSH1 0x20 ADD SWAP1 SWAP3 SWAP2 SWAP1 POP POP POP PUSH2 0x28F JUMP JUMPDEST PUSH1 0x40 MLOAD DUP1 DUP3 PUSH1 0x0 NOT AND PUSH1 0x0 NOT AND DUP2 MSTORE PUSH1 0x20 ADD SWAP2 POP POP PUSH1 0x40 MLOAD DUP1 SWAP2 SUB SWAP1 RETURN JUMPDEST CALLVALUE DUP1 ISZERO PUSH2 0x1A6 JUMPI PUSH1 0x0 DUP1 REVERT JUMPDEST POP PUSH2 0x1C9 PUSH1 0x4 DUP1 CALLDATASIZE SUB DUP2 ADD SWAP1 DUP1 DUP1 CALLDATALOAD PUSH1 0x0 NOT AND SWAP1 PUSH1 0x20 ADD SWAP1 SWAP3 SWAP2 SWAP1 POP POP POP PUSH2 0x2B2 JUMP JUMPDEST STOP JUMPDEST PUSH1 0x0 PUSH2 0x1D6 DUP3 PUSH2 0x210 JUMP JUMPDEST ISZERO ISZERO PUSH2 0x1E1 JUMPI PUSH1 0x0 DUP1 REVERT JUMPDEST PUSH1 0x0 DUP1 DUP4 PUSH1 0x0 NOT AND PUSH1 0x0 NOT AND DUP2 MSTORE PUSH1 0x20 ADD SWAP1 DUP2 MSTORE PUSH1 0x20 ADD PUSH1 0x0 KECCAK256 PUSH1 0x0 SWAP1 SLOAD SWAP1 PUSH2 0x100 EXP SWAP1 DIV PUSH1 0xFF AND SWAP1 POP SWAP2 SWAP1 POP JUMP JUMPDEST PUSH1 0x0 DUP1 PUSH1 0x0 SWAP1 POP JUMPDEST PUSH1 0x1 DUP1 SLOAD SWAP1 POP DUP2 LT ISZERO PUSH2 0x264 JUMPI DUP3 PUSH1 0x0 NOT AND PUSH1 0x1 DUP3 DUP2 SLOAD DUP2 LT ISZERO ISZERO PUSH2 0x239 JUMPI INVALID JUMPDEST SWAP1 PUSH1 0x0 MSTORE PUSH1 0x20 PUSH1 0x0 KECCAK256 ADD SLOAD PUSH1 0x0 NOT AND EQ ISZERO PUSH2 0x257 JUMPI PUSH1 0x1 SWAP2 POP PUSH2 0x269 JUMP JUMPDEST DUP1 DUP1 PUSH1 0x1 ADD SWAP2 POP POP PUSH2 0x218 JUMP JUMPDEST PUSH1 0x0 SWAP2 POP JUMPDEST POP SWAP2 SWAP1 POP JUMP JUMPDEST PUSH1 0x0 PUSH1 0x20 MSTORE DUP1 PUSH1 0x0 MSTORE PUSH1 0x40 PUSH1 0x0 KECCAK256 PUSH1 0x0 SWAP2 POP SLOAD SWAP1 PUSH2 0x100 EXP SWAP1 DIV PUSH1 0xFF AND DUP2 JUMP JUMPDEST PUSH1 0x1 DUP2 DUP2 SLOAD DUP2 LT ISZERO ISZERO PUSH2 0x29E JUMPI INVALID JUMPDEST SWAP1 PUSH1 0x0 MSTORE PUSH1 0x20 PUSH1 0x0 KECCAK256 ADD PUSH1 0x0 SWAP2 POP SWAP1 POP SLOAD DUP2 JUMP JUMPDEST PUSH2 0x2BB DUP2 PUSH2 0x210 JUMP JUMPDEST ISZERO ISZERO PUSH2 0x2C6 JUMPI PUSH1 0x0 DUP1 REVERT JUMPDEST PUSH1 0x1 PUSH1 0x0 DUP1 DUP4 PUSH1 0x0 NOT AND PUSH1 0x0 NOT AND DUP2 MSTORE PUSH1 0x20 ADD SWAP1 DUP2 MSTORE PUSH1 0x20 ADD PUSH1 0x0 KECCAK256 PUSH1 0x0 DUP3 DUP3 DUP3 SWAP1 SLOAD SWAP1 PUSH2 0x100 EXP SWAP1 DIV PUSH1 0xFF AND ADD SWAP3 POP PUSH2 0x100 EXP DUP2 SLOAD DUP2 PUSH1 0xFF MUL NOT AND SWAP1 DUP4 PUSH1 0xFF AND MUL OR SWAP1 SSTORE POP POP JUMP STOP LOG1 PUSH6 0x627A7A723058 KECCAK256 0xce PUSH28 0x549E9D4B5AA2A71CEB8FF4E2BF0C1012122CF5FACD81D0AC86F76EBF GASPRICE DUP7 STOP 0x29 ',
        runtimeBytecode: '60806040526004361061006d576000357c0100000000000000000000000000000000000000000000000000000000900463ffffffff1680632f265cf714610072578063392e6678146100bd5780637021939f14610106578063b13c744b14610151578063cc9ab2671461019a575b600080fd5b34801561007e57600080fd5b506100a160048036038101908080356000191690602001909291905050506101cb565b604051808260ff1660ff16815260200191505060405180910390f35b3480156100c957600080fd5b506100ec6004803603810190808035600019169060200190929190505050610210565b604051808215151515815260200191505060405180910390f35b34801561011257600080fd5b50610135600480360381019080803560001916906020019092919050505061026f565b604051808260ff1660ff16815260200191505060405180910390f35b34801561015d57600080fd5b5061017c6004803603810190808035906020019092919050505061028f565b60405180826000191660001916815260200191505060405180910390f35b3480156101a657600080fd5b506101c960048036038101908080356000191690602001909291905050506102b2565b005b60006101d682610210565b15156101e157600080fd5b600080836000191660001916815260200190815260200160002060009054906101000a900460ff169050919050565b600080600090505b60018054905081101561026457826000191660018281548110151561023957fe5b90600052602060002001546000191614156102575760019150610269565b8080600101915050610218565b600091505b50919050565b60006020528060005260406000206000915054906101000a900460ff1681565b60018181548110151561029e57fe5b906000526020600020016000915090505481565b6102bb81610210565b15156102c657600080fd5b6001600080836000191660001916815260200190815260200160002060008282829054906101000a900460ff160192506101000a81548160ff021916908360ff160217905550505600a165627a7a72305820ce7b549e9d4b5aa2a71ceb8ff4e2bf0c1012122cf5facd81d0ac86f76ebf3a860029',
        srcmap: '28:748:0:-;;;140:92;8:9:-1;5:2;;;30:1;27;20:12;5:2;140:92:0;;;;;;;;;;;;;;;;;;;;;;;;;;;;;212:14;196:13;:30;;;;;;;;;;;;:::i;:::-;;140:92;28:748;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;:::i;:::-;;;:::o;:::-;;;;;;;;;;;;;;;;;;;;;;;;;;;:::o;:::-;;;;;;;',
        srcmapRuntime: '28:748:0:-;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;238:155;;8:9:-1;5:2;;;30:1;27;20:12;5:2;238:155:0;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;541:232;;8:9:-1;5:2;;;30:1;27;20:12;5:2;541:232:0;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;51:47;;8:9:-1;5:2;;;30:1;27;20:12;5:2;51:47:0;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;103:30;;8:9:-1;5:2;;;30:1;27;20:12;5:2;103:30:0;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;399:136;;8:9:-1;5:2;;;30:1;27;20:12;5:2;399:136:0;;;;;;;;;;;;;;;;;;;;;;;;;;;;;238:155;301:5;323:25;338:9;323:14;:25::i;:::-;315:34;;;;;;;;363:13;:24;377:9;363:24;;;;;;;;;;;;;;;;;;;;;;;;;;;356:31;;238:155;;;:::o;541:232::-;605:4;622:6;631:1;622:10;;618:130;638:13;:20;;;;634:1;:24;618:130;;;698:9;678:29;;;:13;692:1;678:16;;;;;;;;;;;;;;;;;;:29;;;;674:67;;;727:4;720:11;;;;674:67;660:3;;;;;;;618:130;;;761:5;754:12;;541:232;;;;;:::o;51:47::-;;;;;;;;;;;;;;;;;;;;;;:::o;103:30::-;;;;;;;;;;;;;;;;;;;;;;;;;;;:::o;399:136::-;466:25;481:9;466:14;:25::i;:::-;458:34;;;;;;;;528:1;499:13;:24;513:9;499:24;;;;;;;;;;;;;;;;;;:30;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;399:136;:::o' } },
  errors:
   [ ':8:3: Warning: Defining constructors as functions with the same name as the contract is deprecated. Use "constructor(...) { ... }" instead.\n  function Voting(bytes32[] candidateNames) public {\r\n  ^ (Relevant source part starts here and spans across multiple lines).\n' ],
  sourceList: [ '' ],
  sources: { '': { AST: [Object] } } }
> abiDefinition = JSON.parse(compiledCode.contracts[':Voting'].interface)
[ { constant: true,
    inputs: [ [Object] ],
    name: 'totalVotesFor',
    outputs: [ [Object] ],
    payable: false,
    stateMutability: 'view',
    type: 'function' },
  { constant: true,
    inputs: [ [Object] ],
    name: 'validCandidate',
    outputs: [ [Object] ],
    payable: false,
    stateMutability: 'view',
    type: 'function' },
  { constant: true,
    inputs: [ [Object] ],
    name: 'votesReceived',
    outputs: [ [Object] ],
    payable: false,
    stateMutability: 'view',
    type: 'function' },
  { constant: true,
    inputs: [ [Object] ],
    name: 'candidateList',
    outputs: [ [Object] ],
    payable: false,
    stateMutability: 'view',
    type: 'function' },
  { constant: false,
    inputs: [ [Object] ],
    name: 'voteForCandidate',
    outputs: [],
    payable: false,
    stateMutability: 'nonpayable',
    type: 'function' },
  { inputs: [ [Object] ],
    payable: false,
    stateMutability: 'nonpayable',
    type: 'constructor' } ]
> VotingContract = web3.eth.contract(abiDefinition)
ContractFactory {
  eth:
   Eth {
     _requestManager: RequestManager { provider: [Object], polls: {}, timeout: null },
     getBalance: { [Function: send] request: [Function: bound ], call: 'eth_getBalance' },
     getStorageAt: { [Function: send] request: [Function: bound ], call: 'eth_getStorageAt' },
     getCode: { [Function: send] request: [Function: bound ], call: 'eth_getCode' },
     getBlock: { [Function: send] request: [Function: bound ], call: [Function: blockCall] },
     getUncle: { [Function: send] request: [Function: bound ], call: [Function: uncleCall] },
     getCompilers: { [Function: send] request: [Function: bound ], call: 'eth_getCompilers' },
     getBlockTransactionCount:
      { [Function: send]
        request: [Function: bound ],
        call: [Function: getBlockTransactionCountCall] },
     getBlockUncleCount:
      { [Function: send]
        request: [Function: bound ],
        call: [Function: uncleCountCall] },
     getTransaction:
      { [Function: send]
        request: [Function: bound ],
        call: 'eth_getTransactionByHash' },
     getTransactionFromBlock:
      { [Function: send]
        request: [Function: bound ],
        call: [Function: transactionFromBlockCall] },
     getTransactionReceipt:
      { [Function: send]
        request: [Function: bound ],
        call: 'eth_getTransactionReceipt' },
     getTransactionCount: { [Function: send] request: [Function: bound ], call: 'eth_getTransactionCount' },
     call: { [Function: send] request: [Function: bound ], call: 'eth_call' },
     estimateGas: { [Function: send] request: [Function: bound ], call: 'eth_estimateGas' },
     sendRawTransaction: { [Function: send] request: [Function: bound ], call: 'eth_sendRawTransaction' },
     signTransaction: { [Function: send] request: [Function: bound ], call: 'eth_signTransaction' },
     sendTransaction: { [Function: send] request: [Function: bound ], call: 'eth_sendTransaction' },
     sign: { [Function: send] request: [Function: bound ], call: 'eth_sign' },
     compile: { solidity: [Object], lll: [Object], serpent: [Object] },
     submitWork: { [Function: send] request: [Function: bound ], call: 'eth_submitWork' },
     getWork: { [Function: send] request: [Function: bound ], call: 'eth_getWork' },
     coinbase: [Getter],
     getCoinbase: { [Function: get] request: [Function: bound ] },
     mining: [Getter],
     getMining: { [Function: get] request: [Function: bound ] },
     hashrate: [Getter],
     getHashrate: { [Function: get] request: [Function: bound ] },
     syncing: [Getter],
     getSyncing: { [Function: get] request: [Function: bound ] },
     gasPrice: [Getter],
     getGasPrice: { [Function: get] request: [Function: bound ] },
     accounts: [Getter],
     getAccounts: { [Function: get] request: [Function: bound ] },
     blockNumber: [Getter],
     getBlockNumber: { [Function: get] request: [Function: bound ] },
     protocolVersion: [Getter],
     getProtocolVersion: { [Function: get] request: [Function: bound ] },
     iban:
      { [Function: Iban]
        fromAddress: [Function],
        fromBban: [Function],
        createIndirect: [Function],
        isValid: [Function] },
     sendIBANTransaction: [Function: bound transfer] },
  abi:
   [ { constant: true,
       inputs: [Array],
       name: 'totalVotesFor',
       outputs: [Array],
       payable: false,
       stateMutability: 'view',
       type: 'function' },
     { constant: true,
       inputs: [Array],
       name: 'validCandidate',
       outputs: [Array],
       payable: false,
       stateMutability: 'view',
       type: 'function' },
     { constant: true,
       inputs: [Array],
       name: 'votesReceived',
       outputs: [Array],
       payable: false,
       stateMutability: 'view',
       type: 'function' },
     { constant: true,
       inputs: [Array],
       name: 'candidateList',
       outputs: [Array],
       payable: false,
       stateMutability: 'view',
       type: 'function' },
     { constant: false,
       inputs: [Array],
       name: 'voteForCandidate',
       outputs: [],
       payable: false,
       stateMutability: 'nonpayable',
       type: 'function' },
     { inputs: [Array],
       payable: false,
       stateMutability: 'nonpayable',
       type: 'constructor' } ],
  new: { [Function] getData: [Function: bound ] } }
> byteCode = compiledCode.contracts[':Voting'].bytecode
'608060405234801561001057600080fd5b50604051610412380380610412833981018060405281019080805182019291905050508060019080519060200190610049929190610050565b50506100c8565b828054828255906000526020600020908101928215610092579160200282015b82811115610091578251829060001916905591602001919060010190610070565b5b50905061009f91906100a3565b5090565b6100c591905b808211156100c15760008160009055506001016100a9565b5090565b90565b61033b806100d76000396000f30060806040526004361061006d576000357c0100000000000000000000000000000000000000000000000000000000900463ffffffff1680632f265cf714610072578063392e6678146100bd5780637021939f14610106578063b13c744b14610151578063cc9ab2671461019a575b600080fd5b34801561007e57600080fd5b506100a160048036038101908080356000191690602001909291905050506101cb565b604051808260ff1660ff16815260200191505060405180910390f35b3480156100c957600080fd5b506100ec6004803603810190808035600019169060200190929190505050610210565b604051808215151515815260200191505060405180910390f35b34801561011257600080fd5b50610135600480360381019080803560001916906020019092919050505061026f565b604051808260ff1660ff16815260200191505060405180910390f35b34801561015d57600080fd5b5061017c6004803603810190808035906020019092919050505061028f565b60405180826000191660001916815260200191505060405180910390f35b3480156101a657600080fd5b506101c960048036038101908080356000191690602001909291905050506102b2565b005b60006101d682610210565b15156101e157600080fd5b600080836000191660001916815260200190815260200160002060009054906101000a900460ff169050919050565b600080600090505b60018054905081101561026457826000191660018281548110151561023957fe5b90600052602060002001546000191614156102575760019150610269565b8080600101915050610218565b600091505b50919050565b60006020528060005260406000206000915054906101000a900460ff1681565b60018181548110151561029e57fe5b906000526020600020016000915090505481565b6102bb81610210565b15156102c657600080fd5b6001600080836000191660001916815260200190815260200160002060008282829054906101000a900460ff160192506101000a81548160ff021916908360ff160217905550505600a165627a7a72305820ce7b549e9d4b5aa2a71ceb8ff4e2bf0c1012122cf5facd81d0ac86f76ebf3a860029'
> deployedContract = VotingContract.new(['Rama','Nick','Jose'],{data: byteCode, from: web3.eth.accounts[0], gas: 4700000})
Contract {
  _eth:
   Eth {
     _requestManager: RequestManager { provider: [Object], polls: {}, timeout: null },
     getBalance: { [Function: send] request: [Function: bound ], call: 'eth_getBalance' },
     getStorageAt: { [Function: send] request: [Function: bound ], call: 'eth_getStorageAt' },
     getCode: { [Function: send] request: [Function: bound ], call: 'eth_getCode' },
     getBlock: { [Function: send] request: [Function: bound ], call: [Function: blockCall] },
     getUncle: { [Function: send] request: [Function: bound ], call: [Function: uncleCall] },
     getCompilers: { [Function: send] request: [Function: bound ], call: 'eth_getCompilers' },
     getBlockTransactionCount:
      { [Function: send]
        request: [Function: bound ],
        call: [Function: getBlockTransactionCountCall] },
     getBlockUncleCount:
      { [Function: send]
        request: [Function: bound ],
        call: [Function: uncleCountCall] },
     getTransaction:
      { [Function: send]
        request: [Function: bound ],
        call: 'eth_getTransactionByHash' },
     getTransactionFromBlock:
      { [Function: send]
        request: [Function: bound ],
        call: [Function: transactionFromBlockCall] },
     getTransactionReceipt:
      { [Function: send]
        request: [Function: bound ],
        call: 'eth_getTransactionReceipt' },
     getTransactionCount: { [Function: send] request: [Function: bound ], call: 'eth_getTransactionCount' },
     call: { [Function: send] request: [Function: bound ], call: 'eth_call' },
     estimateGas: { [Function: send] request: [Function: bound ], call: 'eth_estimateGas' },
     sendRawTransaction: { [Function: send] request: [Function: bound ], call: 'eth_sendRawTransaction' },
     signTransaction: { [Function: send] request: [Function: bound ], call: 'eth_signTransaction' },
     sendTransaction: { [Function: send] request: [Function: bound ], call: 'eth_sendTransaction' },
     sign: { [Function: send] request: [Function: bound ], call: 'eth_sign' },
     compile: { solidity: [Object], lll: [Object], serpent: [Object] },
     submitWork: { [Function: send] request: [Function: bound ], call: 'eth_submitWork' },
     getWork: { [Function: send] request: [Function: bound ], call: 'eth_getWork' },
     coinbase: [Getter],
     getCoinbase: { [Function: get] request: [Function: bound ] },
     mining: [Getter],
     getMining: { [Function: get] request: [Function: bound ] },
     hashrate: [Getter],
     getHashrate: { [Function: get] request: [Function: bound ] },
     syncing: [Getter],
     getSyncing: { [Function: get] request: [Function: bound ] },
     gasPrice: [Getter],
     getGasPrice: { [Function: get] request: [Function: bound ] },
     accounts: [Getter],
     getAccounts: { [Function: get] request: [Function: bound ] },
     blockNumber: [Getter],
     getBlockNumber: { [Function: get] request: [Function: bound ] },
     protocolVersion: [Getter],
     getProtocolVersion: { [Function: get] request: [Function: bound ] },
     iban:
      { [Function: Iban]
        fromAddress: [Function],
        fromBban: [Function],
        createIndirect: [Function],
        isValid: [Function] },
     sendIBANTransaction: [Function: bound transfer] },
  transactionHash: '0x1fa4d4cf54552b8abecf883adba43aa136b287f154dc9d69609261b0104b74f0',
  address: undefined,
  abi:
   [ { constant: true,
       inputs: [Array],
       name: 'totalVotesFor',
       outputs: [Array],
       payable: false,
       stateMutability: 'view',
       type: 'function' },
     { constant: true,
       inputs: [Array],
       name: 'validCandidate',
       outputs: [Array],
       payable: false,
       stateMutability: 'view',
       type: 'function' },
     { constant: true,
       inputs: [Array],
       name: 'votesReceived',
       outputs: [Array],
       payable: false,
       stateMutability: 'view',
       type: 'function' },
     { constant: true,
       inputs: [Array],
       name: 'candidateList',
       outputs: [Array],
       payable: false,
       stateMutability: 'view',
       type: 'function' },
     { constant: false,
       inputs: [Array],
       name: 'voteForCandidate',
       outputs: [],
       payable: false,
       stateMutability: 'nonpayable',
       type: 'function' },
     { inputs: [Array],
       payable: false,
       stateMutability: 'nonpayable',
       type: 'constructor' } ] }
> deployedContract.address
'0x2b325d8cf5b827b4a547e2e42f18214a84416960'
> contractInstance = VotingContract.at(deployedContract.address)
Contract {
  _eth:
   Eth {
     _requestManager: RequestManager { provider: [Object], polls: {}, timeout: null },
     getBalance: { [Function: send] request: [Function: bound ], call: 'eth_getBalance' },
     getStorageAt: { [Function: send] request: [Function: bound ], call: 'eth_getStorageAt' },
     getCode: { [Function: send] request: [Function: bound ], call: 'eth_getCode' },
     getBlock: { [Function: send] request: [Function: bound ], call: [Function: blockCall] },
     getUncle: { [Function: send] request: [Function: bound ], call: [Function: uncleCall] },
     getCompilers: { [Function: send] request: [Function: bound ], call: 'eth_getCompilers' },
     getBlockTransactionCount:
      { [Function: send]
        request: [Function: bound ],
        call: [Function: getBlockTransactionCountCall] },
     getBlockUncleCount:
      { [Function: send]
        request: [Function: bound ],
        call: [Function: uncleCountCall] },
     getTransaction:
      { [Function: send]
        request: [Function: bound ],
        call: 'eth_getTransactionByHash' },
     getTransactionFromBlock:
      { [Function: send]
        request: [Function: bound ],
        call: [Function: transactionFromBlockCall] },
     getTransactionReceipt:
      { [Function: send]
        request: [Function: bound ],
        call: 'eth_getTransactionReceipt' },
     getTransactionCount: { [Function: send] request: [Function: bound ], call: 'eth_getTransactionCount' },
     call: { [Function: send] request: [Function: bound ], call: 'eth_call' },
     estimateGas: { [Function: send] request: [Function: bound ], call: 'eth_estimateGas' },
     sendRawTransaction: { [Function: send] request: [Function: bound ], call: 'eth_sendRawTransaction' },
     signTransaction: { [Function: send] request: [Function: bound ], call: 'eth_signTransaction' },
     sendTransaction: { [Function: send] request: [Function: bound ], call: 'eth_sendTransaction' },
     sign: { [Function: send] request: [Function: bound ], call: 'eth_sign' },
     compile: { solidity: [Object], lll: [Object], serpent: [Object] },
     submitWork: { [Function: send] request: [Function: bound ], call: 'eth_submitWork' },
     getWork: { [Function: send] request: [Function: bound ], call: 'eth_getWork' },
     coinbase: [Getter],
     getCoinbase: { [Function: get] request: [Function: bound ] },
     mining: [Getter],
     getMining: { [Function: get] request: [Function: bound ] },
     hashrate: [Getter],
     getHashrate: { [Function: get] request: [Function: bound ] },
     syncing: [Getter],
     getSyncing: { [Function: get] request: [Function: bound ] },
     gasPrice: [Getter],
     getGasPrice: { [Function: get] request: [Function: bound ] },
     accounts: [Getter],
     getAccounts: { [Function: get] request: [Function: bound ] },
     blockNumber: [Getter],
     getBlockNumber: { [Function: get] request: [Function: bound ] },
     protocolVersion: [Getter],
     getProtocolVersion: { [Function: get] request: [Function: bound ] },
     iban:
      { [Function: Iban]
        fromAddress: [Function],
        fromBban: [Function],
        createIndirect: [Function],
        isValid: [Function] },
     sendIBANTransaction: [Function: bound transfer] },
  transactionHash: null,
  address: '0x2b325d8cf5b827b4a547e2e42f18214a84416960',
  abi:
   [ { constant: true,
       inputs: [Array],
       name: 'totalVotesFor',
       outputs: [Array],
       payable: false,
       stateMutability: 'view',
       type: 'function' },
     { constant: true,
       inputs: [Array],
       name: 'validCandidate',
       outputs: [Array],
       payable: false,
       stateMutability: 'view',
       type: 'function' },
     { constant: true,
       inputs: [Array],
       name: 'votesReceived',
       outputs: [Array],
       payable: false,
       stateMutability: 'view',
       type: 'function' },
     { constant: true,
       inputs: [Array],
       name: 'candidateList',
       outputs: [Array],
       payable: false,
       stateMutability: 'view',
       type: 'function' },
     { constant: false,
       inputs: [Array],
       name: 'voteForCandidate',
       outputs: [],
       payable: false,
       stateMutability: 'nonpayable',
       type: 'function' },
     { inputs: [Array],
       payable: false,
       stateMutability: 'nonpayable',
       type: 'constructor' } ],
  totalVotesFor:
   { [Function: bound ]
     request: [Function: bound ],
     call: [Function: bound ],
     sendTransaction: [Function: bound ],
     estimateGas: [Function: bound ],
     getData: [Function: bound ],
     bytes32: [Circular] },
  validCandidate:
   { [Function: bound ]
     request: [Function: bound ],
     call: [Function: bound ],
     sendTransaction: [Function: bound ],
     estimateGas: [Function: bound ],
     getData: [Function: bound ],
     bytes32: [Circular] },
  votesReceived:
   { [Function: bound ]
     request: [Function: bound ],
     call: [Function: bound ],
     sendTransaction: [Function: bound ],
     estimateGas: [Function: bound ],
     getData: [Function: bound ],
     bytes32: [Circular] },
  candidateList:
   { [Function: bound ]
     request: [Function: bound ],
     call: [Function: bound ],
     sendTransaction: [Function: bound ],
     estimateGas: [Function: bound ],
     getData: [Function: bound ],
     uint256: [Circular] },
  voteForCandidate:
   { [Function: bound ]
     request: [Function: bound ],
     call: [Function: bound ],
     sendTransaction: [Function: bound ],
     estimateGas: [Function: bound ],
     getData: [Function: bound ],
     bytes32: [Circular] },
  allEvents: [Function: bound ] }
> contractInstance.totalVotesFor.call('Rama')
BigNumber { s: 1, e: 0, c: [ 0 ] }
> contractInstance.voteForCandidate('Rama', {from: web3.eth.accounts[0]})
'0xb2717dc864a70d7ab1af95e99421cd2912692f3284b9e59528106077611f609e'
> contractInstance.voteForCandidate('Rama', {from: web3.eth.accounts[0]})
'0x343c07fd9a58920766187ec403d792afa2f825bfdaf1f24c09c10811b244d214'
> contractInstance.voteForCandidate('Rama', {from: web3.eth.accounts[0]})
'0x6742ef953f5136637fb4b1ce73765cd8d956afd6ada1ee684f239e8e852abfc7'
> contractInstance.totalVotesFor.call('Rama')
BigNumber { s: 1, e: 0, c: [ 3 ] }
>
> contractInstance.totalVotesFor.call('Rama')
BigNumber { s: 1, e: 0, c: [ 3 ] }
> contractInstance.voteForCandidate('Rama', {from: web3.eth.accounts[0]})
'0x8facbabfb99535b99f6828232b26296abb327a977d2a249f57c21d844408f4e4'
> contractInstance.totalVotesFor.call('Rama')
BigNumber { s: 1, e: 0, c: [ 4 ] }

