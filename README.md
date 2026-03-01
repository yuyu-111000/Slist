# Slist

[中文版文档](./README.zh-CN.md)

Slist 是一个专注于任务管理与时间追踪的跨平台应用。

## 功能概览

- 任务管理与清单组织
- 专注计时与时间追踪
- 项目与标签管理
- 多端同步

## 技术栈

- `Angular`
- `TypeScript`
- `NgRx`
- `Electron`
- `Capacitor`

## 快速开始

### 安装依赖

```bash
npm install
```

### 启动开发模式

```bash
npm run start
```

### 仅启动前端

```bash
npm run startFrontend
```

## 常用命令

```bash
npm run build
npm run lint
npm run test
npm run e2e
```

## 目录结构

```text
src/            应用源码
electron/       桌面端进程与集成
android/        Android 工程
ios/            iOS 工程
packages/       扩展与共享包
```

## 构建与发布

```bash
npm run dist
```

平台构建示例：

```bash
npm run dist:win
npm run dist:linuxAndWin
npm run dist:android
npm run dist:ios:prod
```

## 作者

Sariel

## License

MIT
