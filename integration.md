---
description: Start working with DashboardKit with minimum setup by creating new project
---

# Integration

With the years of experience and after crafting many templates, we come to know that, users are often confused with how to use all those components with most of the admin templates which they downloaded/purchased from the internet. If you ever downloaded admin themes, you might come across questions like,

* **How can I use this component in the project?**
* **How can I create a new project and set up a theme/components?**
* **Can I have a minimal code-base to start?** etc.

If you ever found yourself in such a situation, we came here to the rescue.

DashboardKit is structured with a huge set of ready-to-use components. We tried to provide as many as possible components with customization so that you can integrate those directly into your projects.

## Get started with Skeleton

If you have a purchased theme, it already comes with a skeleton structure, so that you can start directly from there. **Skeleton is a folder structure created using react-script with minimal files from the full version to get started**. It has all the dependencies preloaded in `package.json` so you do not need to add any additional dependency unless needed from your side. It has a sample page to get started; With that, Routes, menus, styles, configuration, and many other things have already been set into that which saves ample no. of hours to set up a new project. Isn't it cool and time-savvy?

{% hint style="warning" %}
The Skeleton version is only available in the purchased package.
{% endhint %}

So when you run the project using yarn/npm, you will see a minimal site like below:

![](<.gitbook/assets/Screenshot (19) (1).png>)

It provides you with a very simple and intuitive structure to get started with a new project. You can add new components from the full version. Now let's see how can we do that.

### Add components into skeleton/new project

Now, let's add some cool components from the full version to the project which we just created. It will help you to craft your pages as per your need. So Let's begin:

Consider a scenario that you want to add `StatisticCard` widget from the full version default dashboard to the sample page. For that, we need to do the following things in order.

1. Find StatisticCard from `src\components\Widgets\Statistic\StatisticCard.tsx`
2. Add card to the index page.
3. You will have the following final version of `sample/index.tsx`

{% code title="src/views/sample/index.tsx" %}
```typescript

// react-bootstrap
import MainCard from 'components/Card/MainCard';
import { Row, Col } from 'react-bootstrap';

// -----------------------|| SAMPLE ||-----------------------//

export default function Sample(): React.ReactElement {
  return (
    <Row>
      <Col sm={12}>
        <MainCard title="Hello card">
          <p>
            "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
            enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor
            in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident,
            sunt in culpa qui officia deserunt mollit anim id est laborum."
          </p>
        </MainCard>
      </Col>
    </Row>
  );
}

```
{% endcode %}

The output of this will be the following:

![](<.gitbook/assets/Screenshot (22).png>)

You can set styling as per your need after that.

Cool and straightforward, right?

You can do the same for other components and design your pages as per your needs. We have made common and reusable controls as well which you can see inside `/src/components`. Feel free to refer to those as well and start developing your page.

I hope, we cover some basics to get started with the DashboardKit template and how to integrate it for your new project.
