# 第三方内容说明

本仓库包含项目介绍、界面截图，并在 Releases 中提供桌面安装包；不分发实现源码或完整数据集。每个 release 另附随安装包分发的完整第三方声明。

截图和安装包中的手写数字样本源于 MNIST（Yann LeCun、Corinna Cortes、Christopher J. C. Burges）：
http://yann.lecun.com/exdb/mnist/ 。安装包只内置少量演示样本。样本权利仍归原权利人，本项目的专有声明不将
这些样本据为己有，也不另行授予第三方数据使用权。

应用支持的 Penn-Fudan 行人数据来源为
https://www.cis.upenn.edu/~jshi/ped_html/ ，本仓库和安装包都没有打包其照片、标注或衍生数据集。

桌面安装包使用 Tauri、serde_json、base64、aes-gcm 等 Rust 组件（MIT 或 Apache-2.0 许可）及其依赖，前端混淆使用
javascript-obfuscator（BSD-2-Clause，许可文本随应用分发）。Windows 安装包含 Microsoft WebView2 加载器
`WebView2Loader.dll`。Linux 版依赖系统的 GTK 与 WebKitGTK。这些组件的上游许可和版权仍然适用。

LICENSE 仅涉及项目权利人依法享有的权利，不能覆盖第三方权利、公共领域材料、
不受版权保护的事实/思想或依法不得限制的权利。
