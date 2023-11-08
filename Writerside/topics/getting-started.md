# 起步

<!--Writerside adds this topic when you create a new documentation project.
You can use it as a sandbox to play with Writerside features, and remove it from the TOC when you don't need it anymore.-->

> 我认为你在看这篇文档的时候已经预装了官方支持的数据库管理软件`DataGrip`，以下文档都将基于它进行演示及说明。
>
{style="note"}

<!--![JetBrains](JetBrains.png){ width="600" }-->
## 介绍
%product% 是一款基于IntelliJ 的数据库辅助插件，可以帮助我们开发人员快速生成多值SQL查询语句，减少手动连接多值SQL查询语句所需的时间。
- 支持JetBrains旗下所有的数据库管理软件
- 插件允许自定义选择区域去转换
- 打开 **Settings | Tools | Comma** 自定义配置

对于经常数据库运维人员来说，它可能是你的最爱。如果你有什么建议或者反馈，请点击<a href="mailto:peichenwan@gmail.com">这里</a>给我们发送邮件。

## 安装
<procedure title="InstallPlugin" id="install-plugin">
    <step>
        <p>打开<code>DataGrip</code>，进入<ui-path>Settings|Plugins|Marketplace</ui-path>，搜索插件<code>Comma</code>。</p>
        <img src="Marketplace.png" alt="InstallPlugin" border-effect="line"/>
    </step>
    <step>
        <p>点击 <code>Install</code> 按钮安装插件，等待下载完成即可。</p>
    </step>
</procedure>

## 使用
你只需要选择需要转换的几行数据即可，右键选择 <code>Comma</code> ，即可完成转换，快去试试呀。
<p>
    <img src="quick_access.gif" alt="" />
</p>
同时快速转换也是支持快捷键，Mac用户 <shortcut>Control+Option+ ,</shortcut> ，而Windows用户 <shortcut>Ctrl+Alt+ ,</shortcut>，朋友们可以自己尝试一下。

## 反馈与支持
我们的工具难免会有不足需要改善的地方，如果你在使用的过程中有什么问题，欢迎及时向我们反馈，你可以发邮件至<a href="mailto:peichenwan@gmail.com">peichenwan@gmail.com</a>，感谢广大朋友们支持。
