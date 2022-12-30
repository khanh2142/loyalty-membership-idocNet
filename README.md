# Folder structure (Cấu trúc thư mục)

```TSX
.
├── .vscode
│   └── setting.json // config IDE dùng chung trong dự án (nếu cần thiết)
├── build // thư mục được build ra
├── dist_prod // bản build dành cho môi trường product
├── dist_test // bản build dành cho môi trường develop
├── docs // document trong dự án
├── public
├── src/
│   ├── components // các component dùng chung được viết vào đây
│   ├── hooks // các hook dùng chung được viết vào đây
│   ├── modules // phần này liên quan đến login
│   ├── pages // các page được viết vào đây
│   │   ├── Manager // các phần master viết vào đây
│   │   ├── Member // các phần liên quan đến hội viên viết vào đây
│   │   └── Report // các phần liên quan đến báo cáo viết vào đây
│   ├── routes // phần routing viết vào đây
│   │   └── modules // cấu hình các route trong folder này
│   │       ├── administrator.ts // các route phần master
│   │       ├── membership.ts // các route phần hội viên
│   │       ├── programs.ts // các route phần chương trình
│   │       └── reports.ts // các route phần báo cáo
│   ├── services // phần các hàm call api viết vào đây (chưa refractor được)
│   ├── store // config redux viết vào đây
│   │   ├── reducer // viết các reducer vào đây
│   │   └── store.ts // config các reducer
│   ├── styles // css viết vào đây (được chia thành từng folder, css riêng từng thành phần)
│   ├── types // viết interface vào đây (nếu cần thiết)
│   └── utils // các hàm dùng chung thì viết vào đây
├── .env
├── .env.development // config môi trường develop
├── .env.production // config môi trường prodcut
├── package.json // config các thư viện
├── tsconfig.json // config TypeScript
└── vite.config.ts // config tool vite
```

Mọi người giúp em đi đúng flow thư mục nhé (đừng tạo folder linh tinh)

---
