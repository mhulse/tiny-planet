# Fisheye

Equirectangular to fisheye maker!

## Example

### Input

**Equirectangular:**

![](input.jpg)

### Output

**Tiny Planet:**

![](output_tiny-planet.jpg)

**Big Sky:**

![](output_big-sky.jpg)

## Options

option | description | default
--- | --- | ---
`view` | conversion view type: `tiny-planet` or `big-sky` | `tiny-planet`
`image` | **required**, local path to equirectangular image | `undefined`
`directory` | output directory if different from `image` | input image’s directory
`name` | specify name of output image | input image’s name

## Usage

See: [`example.js`](./tests/example.js)

## License

Copyright © 2019 [Michael Hulse](http://mky.io).

Licensed under the Apache License, Version 2.0 (the “License”); you may not use this work except in compliance with the License. You may obtain a copy of the License in the LICENSE file, or at:

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an “AS IS” BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
