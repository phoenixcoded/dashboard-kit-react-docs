---
description: Simple Folder structure helps you to navigate easily without any hassle.
---

# Folder Structure

Under **`dashboard-kit-react/`** directory, You will find the following folder structure.

{% tabs %}
{% tab title="Folder Structure (Ts Version)" %}
{% code title="DashboardKit-material-react- ts" %}
```typescript
..
├── package.json           -> Package json file.
├── public
├── README.md
├── src
│   ├── assets
│   │   └── images
│   │   └── fonts
│   │   └── scss           -> Template SCSS files
│   │       ├── style.scss -> Application main Scss file
│   ├── components         -> Template custom components, Cards, Widgets, Modals
│   ├── config             -> Template constant value and live customization
│   ├── contexts           -> State context
│   ├── data               -> json data to serve in pages
│   ├── hooks              -> Custom hooks
│   ├── layout
│   │   ├── AdminLayout     -> Layout for main components & routers
│   │   ├── GuestLayout     -> Layout for Guest Components & routes
│   ├── routes             -> different routes based on layouts
│   ├── store              -> Redux actions, reducers
│   ├── types              -> Redux actions, reducers
│   ├── utils
│   ├── views              -> View files for all pages
│   ├── App.tsx            -> starting point of application
│   ├── index.tsx          -> Application root
│   ├── menu-items.ts      -> menu data
..
```
{% endcode %}
{% endtab %}

{% tab title="Folder Structure (Js Version)" %}
{% code title="DashboardKit-material-react-Js version" %}
```javascript
..
├── package.json           -> Package json file.
├── public
├── README.md
├── src
│   ├── assets
│   │   └── images
│   │   └── fonts
│   │   └── scss           -> Template SCSS files
│   │       ├── style.scss -> Application main file
│   ├── components         -> Template custom components, Cards, Widgets, Modals
│   ├── config             -> Template constant value and live customization
│   ├── contexts           -> State context
│   ├── data               -> json data to serve in pages
│   ├── hooks              -> Custom hooks
│   ├── layout
│   │   ├── AdminLayout     -> Layout for main components & routers
│   │   ├── GuestLayout     -> Layout for Guest Components & routes
│   ├── routes             -> different route based on layouts
│   ├── store              -> Redux actions, reducers
│   ├── utils
│   ├── views              -> View files for all pages
│   ├── App.jsx            -> starting point of application
│   ├── index.jsx          -> Application root
│   ├── menu-items.js      -> menu data
..
```
{% endcode %}
{% endtab %}
{% endtabs %}
