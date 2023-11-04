# MUI5 currency textfield [![npm](https://img.shields.io/npm/v/mdornseif/mui-currency-textfield.svg?style=flat-square)](https://www.npmjs.com/package/mdornseif/mui-currency-textfield)

[View on Github](https://github.com/mdornseif/mui-currency-textfield)

## Installation

```bash
npm install @mdornseif/mui-currency-textfield --save
```

## Usage

```html
import React from 'react' import CurrencyTextField from
'@mdornseif/mui-currency-textfield' export default function MyComponent() {
const [value, setValue] = React.useState(); return ( <CurrencyTextField
label="Amount" variant="standard" value={value} currencySymbol="$"
outputFormat="string" onChange={(event, value)=> setValue(value)} /> ); }
```
