#this is for issue for improved feel free to put here
#method : #[Compiler] - Bugs
#GCC 6/7 - BlockExplorer.cpp
- /root/coins/DirhamCli/src/BlockchainExplorer/BlockchainExplorer.cpp:149:1: error: ‘CryptoNote::BlockchainExplorer::database’ is initialized with itself [-Werror=init-self]
 BlockchainExplorer::BlockchainExplorer(INode& node, Logging::ILogger& logger) :
 ^~~~~~~~~~~~~~~~~~

