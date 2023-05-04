# 🕉 @sensethenlove/get-relative-time


### 🙏 Description
Simple function that recieves a date and gives back the relative time using `Intl.RelativeTimeFormat('en', { numeric: 'auto' })`


### ☯️ Install
```bash
pnpm add @sensethenlove/get-relative-time
```

### 💛 Example
```ts
import { getRelativeTime } from '@sensethenlove/get-relative-time'

getRelativeTime(new Date()) // now
getRelativeTime(new Date('2023-05-05')) // tomorrow
getRelativeTime(new Date('1991-04-08')) // 32 years ago
```


### 🧡 Supports
* Seconds
* Minutes
* Hours
* Days
* Weeks
* Months
* Years


### 💖 Our helpful packages!
* [@sensethenlove/jwt](https://www.npmjs.com/package/@sensethenlove/jwt)
* [@sensethenlove/slug](https://www.npmjs.com/package/@sensethenlove/slug)
* [@sensethenlove/toast](https://www.npmjs.com/package/@sensethenlove/toast)
* [@sensethenlove/env-write](https://www.npmjs.com/package/@sensethenlove/env-write)
* [@sensethenlove/svelte-modal](https://www.npmjs.com/package/@sensethenlove/svelte-modal)
* [@sensethenlove/global-style](https://www.npmjs.com/package/@sensethenlove/global-style)
* [@sensethenlove/get-form-entries](https://www.npmjs.com/package/@sensethenlove/get-form-entries)
* [@sensethenlove/svelte-turnstile](https://www.npmjs.com/package/@sensethenlove/svelte-turnstile)
* [@sensethenlove/svelte-loading-anchor](https://www.npmjs.com/package/@sensethenlove/svelte-loading-anchor)
