# basenew1contract
forge verify-contract \
  --chain-id 84532 \
  --etherscan-api-key $BASESCAN_API_KEY \
  <địa-chỉ-contract> \
  src/New1.sol:New1 \
  --constructor-args $(cast abi-encode "constructor(string)" "Xin chao Base!")
  ...
  basenew1contract
  ...
