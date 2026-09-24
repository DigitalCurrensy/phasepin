# Phasepin

Is the clock good enough?

A local atomic clock is used first, then network time, then a holdover shorter than four hours. GPS alone is not good enough. An error of 1 millisecond or more is too large. Fiberlock and Photonseal both refuse those two cases.

It takes the error bound the switch already announced, in nanoseconds. It does not read the switch's private message, and it does not run the network time protocol.

Copyright 2026 DIGITAL CURRENSY INC / Module Kinetic Ltd. Apache-2.0. See [LICENSE](LICENSE).
Parent: [module-kinetic-ltd](https://github.com/DigitalCurrensy/module-kinetic-ltd)
