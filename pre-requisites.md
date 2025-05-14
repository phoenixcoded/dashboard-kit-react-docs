---
description: Pre Requisites for DashboardKit React
---

# Pre-requisites

## **Pre-requisites**

DashboardKit is based on `node` and `vite`. Please check the following **prerequisites** before jumping into it.

1. [Node JS](https://nodejs.org/en/) - Version 22.x.x recommended
2. [Yarn](https://yarnpkg.com/)/[NPM ](https://www.npmjs.com/)package manager
3. When copying folders, include hidden files like `.env`. This file contains important theme settings. **Do not delete** the `.env` file. Update its **values** according to your organization’s needs, but **do not change the keys**.
4. The theme includes two lock files: `yarn.lock` (for Yarn) and `package-lock.json` (for npm). Each of these files corresponds to a different package manager. To ensure consistency and avoid potential conflicts:
   1. **Choose a Package Manager**: Decide whether you will use Yarn or npm to manage your project's dependencies.
      * **If using Yarn**: Retain `yarn.lock` and delete `package-lock.json`.
      * **If using npm**: Retain `package-lock.json` and delete `yarn.lock`.
   2. **Do Not Modify Lock Files Manually**: Avoid editing the contents of `yarn.lock` or `package-lock.json` directly. Manually changing these files can lead to dependency issues and inconsistencies. Always use the appropriate package manager commands (`yarn` or `npm`) to update or regenerate these files.

You can check your current version using the following commands:

```
c:\> node -v
c:\> yarn -v
c:\> npm -v
```

\


{% hint style="success" %}
We used yarn as a command everywhere and we also recommend the same.
{% endhint %}
