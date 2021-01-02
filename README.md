This is a mono-repo demo.
If you want a mono-repo + react template, just clone it.

With [lerna](https://lerna.js.org/), there are 3 sub-projects:
* `common`: shared components
* `admin-site`: a react project using common project
* `customer-site`: another react project using common project

**run admin-site**
```
yarn start:aSite
```

**run customer-site**
```
yarn start:cSite
```

**build admin-site**
```
yarn build:aSite
```

**build customer-site**
```
yarn build:cSite
```

这是一个mono-repo的示例项目，如果你需要一个mono-repo + react的项目模板，直接clone吧。

本项目使用[lerna](https://lerna.js.org/)管理了三个子项目：
* `common`: 公共组件
* `admin-site`: 管理员站点，引用了上面的公共组件
* `customer-site`: 客户站点，也引用了上面的公共组件

