# Huncheng Lab（混成实验室）

> 有物混成，先天地生。——帛书老子·二十五章

这里是 [@xinetzone](https://github.com/xinetzone) 的实验场：未定型的原型、快速验证的 demo、跑着玩的想法。
成熟的项目会从这里分化出去，成为独立的正式仓库。

## 这是什么

- 🧪 各种技术 demo 和原型实验
- 📦 短期验证项目（几天到几个月生命周期）
- 🎨 不追求完美，只追求"能跑起来看到效果"

## 这不是什么

- ❌ 正式产品或长期维护的项目（去 [xinetzone/SpecWeave](https://github.com/xinetzone/SpecWeave)）
- ❌ 生产环境代码
- ❌ 有商业交付要求的项目

## 仓库命名规范

```
demo-<主题>-<技术栈>
```

示例：
- `demo-react-markdown-editor`
- `demo-fastapi-async-task`
- `demo-threejs-galaxy`

规则：
- 统一 `demo-` 前缀
- 全小写，连字符分隔
- 第二个词是功能/主题，第三个词（可选）是核心技术栈

## 仓库状态约定

每个仓库 README 顶部必须标注：

```
Status: 🚧 WIP        # 正在开发中
Status: ✅ Done       # 已完成验证，不再更新
Status: 📦 Archived   # 已归档（超过6个月无提交）
Status: 🌟 Graduated # 已毕业（拆分为正式项目）
```

## 归档规则

- 创建后 **6 个月无任何提交** → 自动归档（Read-only）
- 归档后如果重新激活，随时取消归档
- 毕业的项目在原仓库 README 顶部注明新仓库地址

## 质量底线

不要求测试覆盖率、不要求 CI 必过，但**必须有一个能跑起来的 README**：
1. 一句话说明这个 demo 在验证什么
2. 一行启动命令
3. 一张截图或一段 GIF