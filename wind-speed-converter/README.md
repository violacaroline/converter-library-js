# Wind Speed Converter - Wind Wizard

## What is Wind Wizard?

Use the Wind Wizard to convert the most common wind speed units (km/h, m/s, ft/s, mph, knots).

## How do you install?

Run `npm i windwizard`

Then...

## How do you use?

import { windwizard } from 'windwizard'

windwizard({
  from: 'kmh',
  to: 'ms'
})

### What are the options?

In the options object you specify:

- from = What unit do you want to convert *FROM*?
- to = What unit do you want to conver *TO*?