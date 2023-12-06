# @segment/loosely-validate-event

> [!NOTE]
> Segment has paused maintenance on this project, but may return it to an active status in the future. Issues and pull requests from external contributors are not being considered, although internal contributions may appear from time to time. The project remains available under its open source license for anyone to use.

Loosely validate an event.

## Example

```js
const validate = require('@segment/loosely-validate-event')

const event = {
  type: 'track',
  userId: 'abc123',
  properties: {
    foo: 'bar'
  }
}

validate(event) // throws if `event` does not pass validation
```
