# IntelliJ plugin for Scheme language

This plugin is modified from [cmf/schemely](https://github.com/cmf/schemely) which code is somehow too old to compiled on newer IntelliJ platforms.  
I made the old code can be compiled on newer IntelliJ platforms, and modified some code of the Lexer and Parser, and also with other modifcations (Some commits in [Saigut/schemely](https://github.com/Saigut/schemely)).  
But this plugin is not well tested yet, and also have some issues that may be hard to be fixed for me. And I have little free time to work on this plugin recently.

## Changelog

1. I just follow the JB docs and try fixup `java.lang.NoClassDefFoundError: com/intellij/openapi/actionSystem/DataKeys`

https://plugins.jetbrains.com/docs/intellij/getting-started.html#using-devkit

https://plugins.jetbrains.com/docs/intellij/setting-up-environment.html#configuring-intellij-platform-sdk

https://plugins.jetbrains.com/docs/intellij/creating-plugin-project.html#adding-code-to-the-project

https://plugins.jetbrains.com/docs/intellij/deploying-plugin.html

2. to make it compile with latest JB plugin SDK, I have to remove REPL ( I only use it for color scheme syntax purpose )
