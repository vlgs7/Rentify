Next.js 13 应用，包含有 React, Tailwind, Prisma, MongoDB 和 NextAuth 等技术栈。
*   使用 Tailwind 设计
*   Tailwind 动画和效果
*   响应式
*   身份验证
*   Google 身份验证
*   Github 身份验证
*   使用 Cloudinary CDN 进行图像上传
*   使用 react-hook-form 进行客户端表单验证和处理
*   使用 react-toast 进行服务器错误处理
*   使用 react-date-range 进行日历操作
*   页面加载状态
*   页面空状态
*   预订/预订系统
*   访客预订取消
*   房主预订取消
*   创建和删除房产
*   定价计算
*   通过类别、日期范围、地图位置、客人数量、房间和浴室数量进行高级搜索算法
*   例如，我们将过滤掉在您的期望旅行日期范围内有预订的房产
*   收藏夹系统
*   可共享的 URL 过滤器
*   假设您选择了类别、位置和日期范围，将能够与在另一个浏览器中登录的朋友共享 URL，他们将看到相同的结果
*   在路由处理程序（app/api）中编写 POST 和 DELETE 路由
*   在服务器 react 组件中直接访问数据库获取数据
*   处理类似于 error.tsx 和 loading.tsx 的文件，这些文件是 Next 13 模板文件，用于统一加载和错误处理

访问 [demo](https://rentify-sigma.vercel.app/)

RUN


```shell
npm i
```
设置 .env 文件：

```makefile
DATABASE_URL=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
GITHUB_ID=
GITHUB_SECRET=
NEXTAUTH_SECRET=
```
设置 Prisma：

```perl
npx prisma db push
```

启动应用：

```shell
npm run dev
```