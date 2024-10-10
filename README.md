# Idraaj

An advanced HTML number input with enhanced features, including number formatting, customizable decimal separators, integer-only mode, and more.

## Numeric Field

```typescript
import { numericField } from 'idraaj'
import { useState } from 'react'

function Component() {
  const [value, setValue] = useState<null | number>(324221)


  console.log({ value })


  return (
    <NumericField
      onChange={(val) => setValue(val)}
      decimalSeparator="comma"
      max={600000}
      enableSeparator={true}
    />
  )
}

export default Component
```
