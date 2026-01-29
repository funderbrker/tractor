# Tractor
Tractor is a system integrated into Beanstalk that allows for generalized sequences of instructions to be encoded, using EIP-712 signing and verification, on the EVM. The core of the code outlined here can be trivially expanded for use with any protocol.

## Beanstalk
An example of the system being expanded with protocol-specific functionality can be seen in Beanstalk. I led this integration and the relevant files are visible here.
- https://github.com/BeanstalkFarms/Beanstalk/blob/master/protocol/contracts/libraries/LibTractor.sol
- https://github.com/BeanstalkFarms/Beanstalk/blob/master/protocol/contracts/beanstalk/farm/TractorFacet.sol
- https://github.com/BeanstalkFarms/Beanstalk/blob/master/protocol/test/foundry/farm/Tractor.t.sol
