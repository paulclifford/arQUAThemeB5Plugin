# arQUAThemeB5Plugin

## Queen's University Archives Bootstrap 5 Theme

A theme for AtoM 2.9. A skeleton for an empty AtoM theme plugin that extends arDominionB5Plugin without any modifications can be found in this arThemeB5Plugin repository (https://github.com/artefactual-labs/arThemeB5Plugin). For more information, please see:

https://www.accesstomemory.org/en/docs/2.9/admin-manual/customization/theming/

Requires:

1. AtoM 2.9
1. NodeJS v22 or above

Deploy:

1. Clone this repo into `~/atom/plugins`
1. From `~/atom` run `npm install` and then `npm run build`
1. Run `php symfony cc`
1. Activate the theme via the AtoM admin UI
