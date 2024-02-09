# CAST COMMAND, COMMON TO USE
To access storage of variable we can use `cast storage`, this command help us read from
blockchain and shows that because you inserted the word `private` doesn't mean it secure.

Use this command to read state variable

`cast storage 0x5FbDB2315678afecb367f032d93F642f64180aa3 1 --rpc-url http://127.0.0.1:8545`

0x5fbb... is the contract address.

---------
To convert bytes to string, use this cast command

`cast parse-bytes32-string 0x6d7950617373776f726400000000000000000000000000000000000000000014`

where 0x6d7... is the returned bytes

## To count lines of code
use the command `cloc ./src` to count
you can usee solidiy metrics to have a better details.
just right click on the folder and select solidity metricss
