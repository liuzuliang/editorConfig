# Editor Config

一个非常通用的[.editorconfig] 文件，支持以下文件类型：

-  C＃ -  .cs，.csx，。蛋糕
-  Visual Basic  -  .vb
- 脚本 -  .sh，.ps1，.psm1，.bat，.cmd
-  XML  -  .xml，.config，.props，.targets，.nuspec，.resx，.ruleset
-  JSON  -  .json，.json5
-  YAML  -  .yml，.yaml
-  HTML  -  .htm，.html
-  JavaScript  -  .js，.ts，.tsx，.vue
-  CSS  -  .css，.sass，.scss，.less
-  SVG  -  .svg
-  Markdown  -  .md
-  Visual Studio  -  .sln，.csproj，.vbproj，.vcxproj，.vcxproj.filters，.proj，.projitems，.shproj

# 对于.NET代码
已经定义了C＃和VB.NET的广泛代码样式设置，需要使用最新的C＃功能。
所有与C＃相关的代码样式都与[StyleCop]（https://github.com/DotNetAnalyzers/StyleCopAnalyzers）默认样式一致。
所有.NET命名约定都与.NET Framework设计指南的[命名准则]（https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/naming-guidelines）一致。

# 什么是Editor Config

EditorConfig帮助开发人员在不同的编辑器和IDE之间定义和维护一致的编码样式。EditorConfig项目由用于定义编码样式的文件格式和一组文本编辑器插件组成，这些插件使编辑器能够读取文件格式并遵循定义的样式。EditorConfig文件易于阅读，与版本控制系统配合使用。在[editorconfig.org]（http://editorconfig.org/）和[Visual Studio Docs]（https://docs.microsoft.com/en-us/visualstudio/ide/editorconfig-code-style）了解更多信息-settings参考）。

# 我如何使用它？

您所要做的就是将其放入项目的根目录中。然后，只要在Visual Studio中打开文件，.editorconfig文件设置将用于帮助格式化文档，并在代码样式和格式不符合时引发警告。对于Visual Studio Code，您可以安装[EditorConfig for VS Code]（https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig）扩展以获得支持。
