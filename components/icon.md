# Icon
That little Facebook icon never looked better.

### Usage
Imports:
```js
import { Icon } from 'galio-framework';
```

Simple example:
```jsx
<Icon name="pin-3" family="Galio" color={rgb(100,120,40)} size={10} />
```

### Props

|  Prop  |  Type  |       Default      |                  Description                  |
|:------:|:------:|:------------------:|:---------------------------------------------:|
| name   | string | null               | Choose your Icon's name from Expo's icon list |
| family | string | null               | Choose your Icon's family from the same list  |
| size   | number | theme.SIZES.BASE   | This sets your Icon's size                    |
| color  | string | theme.COLORS.BLACK | This sets your Icon's color                   |
