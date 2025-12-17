```ts
import { strict as assert } from 'node:assert';

enum Mode {
  Focus = 'focus',
  Flow = 'flow',
}

enum Time {
  Unknown = 'unknown',
}

const state = {
  user: 'ksprptr',
  mode: Mode.Focus,
  time: Time.Unknown,
  process: 'building web apps',
};

assert(state.mode === Mode.Focus);

export default state;
```
