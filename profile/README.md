## Hi there 👋

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
这里是 [组件化宏内核StarryOS](https://github.com/Starry-OS/StarryOS/)的各种内核组件集中存放的组织。我们期望做到：

- 内核组件细粒度划分
- 每一个内核组件作为一个独立的仓库，有对应的集成 CI 测试
- 可以通过统一的工具在主仓库直接拉取对应所需的仓库，打包成为一个整体内核进行运行
- 每一个子组件在足够细粒度的情况下，支持复用到其他内核


相关历史链接：
- https://github.com/rcore-os/arceos: Starry 基于的初始内核 ArceOS
- https://github.com/Arceos-monolithic/Starry: 训练营使用的初始版本的 Starry 仓库，可以用来理解 Starry 架构功能，是最初的版本
- https://github.com/Azure-stars/Starry/: Starry 改造为单向依赖的过渡版本，改动了一些模块的依赖关系，准备进行组件拆分
- https://github.com/Starry-OS/Starry-Old/: 2024年的主仓库，代表 Starry 在2024年的功能
