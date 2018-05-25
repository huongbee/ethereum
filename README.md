# ethereum
1. run on terminal:
geth —syncmode="light" —cache 2048 —rpc —rpcaddr localhost —rpcport 8545 —rpcapi "web3,eth,personal" —rpccorsdomain "http://localhost:3000"

|  geth console --syncmode "light"


2. open another terminal
get attach
3. in terminal step 2, start RPC and allow : web3,net,eth,personal"
  admin.startRPC("127.0.0.1", 8545, "*", "web3,net,eth,personal")


