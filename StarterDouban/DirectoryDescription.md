# StarterDouban 工程目录结构说明

````
├── build              // webpack以及vue-loader的相关配置文件
├── config             // 开发/生产环境相关配置
├── src                // 主要开发目录
│   ├── assets        // 静态资源文件
│   │   ├── images   // 图片
│   │   ├── style    // 公用css(styl)文件
│   ├── components    // 通用组件
│   │   ├── 组件名   // 组件目录，主要组件名对应目录名
│   ├── router        // vue-router路由配置目录
│   ├── store         // vuex状态管理目录
│   │   ├── modules  // vuex modules配置目录，对应各个view
│   ├── views         // 页面目录
├── .bablelrc          // babel配置文件
├── .editorconfig      // IDE编码风格配置文件
├── .eslintignore      // eslint忽略目录配置文件
├── .eslintrc.js       // eslint规则配置文件
├── .gitignore         // git忽略目录配置文件
├── .postcssrc.js      // postcss配置文件
├── index.html
├── package.json
└── README.md
````