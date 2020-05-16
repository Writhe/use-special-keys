useSpecialKeys
==============

Installation
------------

```
npm -i use-special-keys
```
or
```
yarn add use-special-keys
```

Usage
-----

```typescript
import { useSpecialKeys } from 'use-special-keys';

const handleKeyDown = useSpecialKeys<HTMLInputElement>({
  Enter: event => console.log(event.currentTarget.value),
  Escape: event => console.log(event.currentTarget.value),
});
```
