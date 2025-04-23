---
description: Page and URL routing
---

# Routing

DashboardKit routing system is based on [react-router](https://reacttraining.com/react-router/) and its package [react-router-dom,](https://reacttraining.com/react-router/web/guides/quick-start) it's also using code splitting for better performance.

{% hint style="info" %}
**How can I add a new page with a menu item?**

You can use the below explanation to add/remove menu routes and their menu items.
{% endhint %}

## Configure route

Ope&#x6E;**`...\src\routes\route.tsx`**&#x59;ou will find the below example code. In the below code we have shown four different routes.

{% tabs %}
{% tab title="typescript" %}
{% code title="src\routes\routes.tsx" %}
```javascript
import { lazy } from 'react';
import { createBrowserRouter } from 'react-router-dom';

// project import
import MainRoutes from './MainRoutes';

import GuestLayout from 'layouts/GuestLayout';

// render - landing page
const PagesLanding = lazy(() => import('../views/page-layouts/Landing'));

// ==============================|| ROUTING RENDER ||============================== //

const router = createBrowserRouter(
  [
    {
      path: '/',
      element: <GuestLayout />,
      children: [
        {
          index: true,
          element: <PagesLanding />
        }
      ]
    },
    MainRoutes
  ],
  { basename: import.meta.env.VITE_APP_BASE_NAME }
);

export default router;
```
{% endcode %}
{% endtab %}
{% endtabs %}
