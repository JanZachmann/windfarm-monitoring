# windfarm-monitoring
Product page: https://www.omnect.io/home

## Instruction
This module is based on the omnect Device Management [iot-client-template-rs](https://github.com/omnect/iot-client-template-rs). All information you need to build the project can be found there.

## What is windfarm-monitoring
This module is designed to **demonstrate windfarm signal values** using Prometheus Metrics in a Rust Web Service:
The monitoring module provides the following metrics on his endpoint:
- latitude
- longitude
- wind_speed
- wind_direction

Default address is **0.0.0.0:8080**, but could be overwritten by an os environment variable **BIND_ADDR_AND_PORT**.

## License
Licensed under either of
* Apache License, Version 2.0, (./LICENSE-APACHE or <http://www.apache.org/licenses/LICENSE-2.0>)
* MIT license (./LICENSE-MIT or <http://opensource.org/licenses/MIT>)
at your option.

## Contribution
Unless you explicitly state otherwise, any contribution intentionally
submitted for inclusion in the work by you, as defined in the Apache-2.0
license, shall be dual licensed as above, without any additional terms or
conditions.


---

copyright (c) 2022 conplement AG<br>
Content published under the Apache License Version 2.0 or MIT license, are marked as such. They may be used in accordance with the stated license conditions.
