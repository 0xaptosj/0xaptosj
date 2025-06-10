## Ultimate guide to build on [Aptos](https://aptosfoundation.org/)

- Youtube
  - [Intro to building on Aptos](https://www.youtube.com/watch?v=-UkbHdeSImc)
  - [Building custom indexer](https://www.youtube.com/watch?v=RqBWIdmxpPk)
  - [Develop from GitHub codespace](https://www.youtube.com/watch?v=RJnlSwyNI8Q)
  - [Dispatchable fungible asset aka transfer hook, with cross contract call](https://www.youtube.com/watch?v=sIS7AnL9DL4&t=1s)

- One liner pitch on why Aptos
  - Fast, cheap, stable. That's all you need to know as an app developer
  - Aptos is like Solana, but Aptos Move is easier to program than SVM contracts, and contract interaction is simpler
- Official docs: https://aptos.dev/en
  - Here you can find [environment setup](https://aptos.dev/en/build/get-started/developer-setup), [developer guide](https://aptos.dev/en/build/smart-contracts), [API docs](https://aptos.dev/en/build/apis), [SDK docs](https://aptos.dev/en/build/sdks), etc.
  - If you are coming from EVM or Solana, we also have cheatsheets
    - [From EVM](https://aptos.dev/en/build/get-started/ethereum-cheatsheet)
    - [From Solana](https://aptos.dev/en/build/get-started/solana-cheatsheet)
- Full stack templates
  - Aptos-full-stack-template：https://github.com/0xaptosj/aptos-full-stack-template
    - This template is more opinionated, it's the one I use personally, it has
      - Contract with unit test and integration test
      - Next.js frontend, with ABI type safety, server action demoing gasless transactions, demo of reading from the chain and indexer DB, and writing to the chain
      - Indexer in both Rust and TypeScript, with a complete guide on deployment
      - Node.js scripts for testing
    - To get started, clone it or fork it or use it as a template
  - Create-Aptos-Dapp：https://github.com/aptos-labs/create-aptos-dapp/
    - This template has more choices, there are basic templates, NFT+launchpad templates, FT+launchpad templates
    - Based on npx, you can use it directly without downloading
    - You can think of this template as a toolbox, take the modules you need, such as how to operate NFT, how to operate FT, how to operate launchpad, etc.
- Aptos learn: https://learn.aptoslabs.com/en
  - High level overview of Aptos and key concepts like object (Aptos equivalent of PDA or contract account), events, resources, etc
  - End to end tutorial with detailed explanation on templates in create-aptos-dapp
- Move by examples: https://github.com/aptos-labs/move-by-examples
  - A collection of move examples
  - Side-by-side comparison with SVM and EVM implementations

## [Aptos](https://aptosfoundation.org/)开发指南

- 视频
  - [Aptos开发101](https://www.youtube.com/watch?v=uAfK1Lpr33M)
  - [自定义索引器](https://www.youtube.com/watch?v=TtdeEnNj0jw)
  - [用GitHub codespace远程开发](https://www.youtube.com/watch?v=kAM0zH6N6pc)
  - [可编程代币 + 怎么在合约里调别的合约](https://www.youtube.com/watch?v=NKOVDmKXuVM&t=2s)

- 为什么选择 Aptos
  - 快，便宜，稳定，作为应用开发者知道这三点就够了
  - Aptos 就像 Solana，但是 Aptos 版本的 Move 比 SVM 合约更好写，而且链下链上调用更简单
- 官方文档：https://aptos.dev/en
  - 这里有[环境配置](https://aptos.dev/en/build/get-started/developer-setup)，[开发指南](https://aptos.dev/en/build/smart-contracts)，[API 文档](https://aptos.dev/en/build/apis)，[SDK 文档](https://aptos.dev/en/build/sdks)等等
  - 如果你是从 EVM 或者 Solana 过来的，我们也准备了迁移至南
    - [从 EVM 迁移](https://aptos.dev/en/build/get-started/ethereum-cheatsheet)
    - [从 Solana 迁移](https://aptos.dev/en/build/get-started/solana-cheatsheet)
- 全栈应用模版
  - Aptos-full-stack-template：https://github.com/0xaptosj/aptos-full-stack-template
    - 这个模版类似全家桶，也是我自己用的模版
      - 合约有单元测试和集成测试
      - Next.js 前端，有 ABI 类型安全，展示了 server action 里做无 gas 交易，展示了如何从链上和 indexer DB 读取数据，以及如何写入链上
      - Rust 和 TypeScript 编写的索引器，有完整的部署指南
      - Node.js 脚本用于测试
    - 直接在 github 上 fork，然后 clone 到本地，修改即可
  - Create-Aptos-Dapp：https://github.com/aptos-labs/create-aptos-dapp/
    - 这个模版选择更多，有纯基础模版，有 NFT+launchpad 模版，有 FT+launchpad 模版
    - 基于 npx，可以直接使用，不需要下载
    - 大家可以把这个模版当成工具箱，从里面拿自己需要的模块，比如怎么操作 NFT，怎么操作 FT，怎么操作 launchpad 等等
- Aptos learn: https://learn.aptoslabs.com/en
  - Aptos 的高层概述和关键概念，比如 object（Aptos 版本的 PDA 或者合约账户），events，resources 等等
  - 详细解释 create-aptos-dapp 里面的模版的完整教程
- Move by examples: https://github.com/aptos-labs/move-by-examples
  - 一系列Move合约模版
  - 同样的应用有SVM和EVM实现，方便大家理解和对比Aptos
