# PROXYacademy
The Back Door!
## Start
Proxied contracts do not make use of constructor, its common to move the constructor logic to an external `initialize()` function. This makes this function a special one.
## CAUTION 
- When used with inheritance, manual care must be taken to not invoke a parent initializer twice, or to ensure that all initializers are idempotent.
- Avoid leaving a contract uninitialized.
- use `{_disableInitializers}` 2 prevent implementation from being used.

## sources
- [OZ initializable.sol](https://github.com/OpenZeppelin/openzeppelin-contracts-upgradeable/blob/dd8ca8adc47624c5c5e2f4d412f5f421951dcc25/contracts/proxy/utils/Initializable.sol#L10)
