---
description: Configuration option for entire DashboardKit Template
---

# Project Configuration

DashboardKit has a single source of truth for default configuration which lets users manage it effectively. It also makes it scalable for new configurations. you can set config like font, border, theme layout, locale, etc. All those can be configured at `src\config\constant.ts`

| **Option**      | **Default**      | **Data Type** | **Description**                                                                                                         |
| --------------- | ---------------- | ------------- | ----------------------------------------------------------------------------------------------------------------------- |
| BASE\_URL       | /dashboard/sales | string        | default path                                                                                                            |
| BASE\_TITLE     | -                | String        | set page title                                                                                                          |
| layout          | vertical         | String        | `vertical`, `horizontal`                                                                                                |
| sidebarHide     | false            | Boolean       | `True`, `False`                                                                                                         |
| collapseMenu    | false            | Boolean       | <kbd>True</kbd>, `False`                                                                                                |
| layoutType      | dark-sidebar     | String        | `light-sidebar`, `dark-sidebar`                                                                                         |
| pageType        | " "              | String        | `app-dark-mode`                                                                                                         |
| colorBrand      | " "              | String        | `bg-primary`, `bg-danger`, `bg-warning`, `bg-info`, `bg-success`, `bg-dark`                                             |
| headerBackColor | " "              | String        | `bg-primary`, `bg-danger`, `bg-warning`, `bg-info`, `bg-success`, `bg-dark`                                             |
| presetColor     | preset-1         | String        | `preset-1`, `preset-2`, `preset-3`, `preset-4`, `preset-5`, `preset-6`, `preset-7`, `preset-8`, `preset-9`, `preset-10` |
| captionHide     | true             | Boolean       | <kbd>True</kbd>, `False`                                                                                                |
| boxLayout       | true             | Boolean       | <kbd>True</kbd>, `False`                                                                                                |

{% tabs %}
{% tab title="Typescript" %}
{% code title="src/config/constant.ts" %}
```typescript
// imports from project
export const BASE_URL = '/dashboard/sales';
export const BASE_TITLE = ' | DashboardKit React Bootstrap 5 Admin Template';

export const BUY_NOW = '#';
export const DOCS_LINK = '#';
export const SUPPORT_LINK = 'https://phoenixcoded.authordesk.app/';

// -----------------------|| Application default Configuration ||-----------------------//

export const CONFIG = {
  layout: 'vertical', // vertical, horizontal
  sidebarHide: false,
  collapseMenu: false, // true for mini-menu
  layoutType: 'dark-sidebar', // light-sidebar
  pageType: '', // app-dark-mode
  colorBrand: '', // bg-primary, bg-danger, bg-warning, bg-info, bg-success, bg-dark
  headerBackColor: '', // bg-primary, bg-danger, bg-warning, bg-info, bg-success, bg-dark
  presetColor: 'preset-1', // preset-1, preset-2, preset-3, preset-4, preset-5, preset-6, preset-7, preset-8, preset-9, preset-10
  captionHide: true,
  boxLayout: true
};
```
{% endcode %}
{% endtab %}

{% tab title="Javascript" %}
{% code title="src/config/constant.js" %}
```javascript
// imports from project
export const BASE_URL = '/dashboard/sales';
export const BASE_TITLE = ' | DashboardKit React Bootstrap 5 Admin Template';

export const BUY_NOW = '#';
export const DOCS_LINK = '#';
export const SUPPORT_LINK = 'https://phoenixcoded.authordesk.app/';

// -----------------------|| Application default Configuration ||-----------------------//

export const CONFIG = {
  layout: 'vertical', // vertical, horizontal
  sidebarHide: false,
  collapseMenu: false, // true for mini-menu
  layoutType: 'dark-sidebar', // light-sidebar
  pageType: '', // app-dark-mode
  colorBrand: '', // bg-primary, bg-danger, bg-warning, bg-info, bg-success, bg-dark
  headerBackColor: '', // bg-primary, bg-danger, bg-warning, bg-info, bg-success, bg-dark
  presetColor: 'preset-1', // preset-1, preset-2, preset-3, preset-4, preset-5, preset-6, preset-7, preset-8, preset-9, preset-10
  captionHide: true,
  boxLayout: true
};
```
{% endcode %}
{% endtab %}
{% endtabs %}
