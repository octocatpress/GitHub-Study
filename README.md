1. 一定要先测试命令的效果后，再用于工作环境中，以防止造成不可弥补的后果。
2. 所有的都在`git version 2.16.1.windows.4`中测试通过。
3. 统一概念:
  - 工作区:改动(增删文件和内容)
  - 暂存区:输入命令:git add 改动的文件名，此次改动就放到了"暂存区"
  - 本地仓库(简称:本地):输入命令:git commit "此次输入叙述",此次改动就放到了"本地仓库"，每个commit，都为一个"版本"
  - 远程仓库(简称:远程):输入命令:git push 远程仓库,此次改动就放到了"远程仓库"(比如GitHub等)
  - commit-id:输出命令:git log,最上面的那行commit xxxxxxx，后面的字符串就是commit-id
  - test:带有test字样的文件，全部是用来在本项目中测试使用的，并不是真正的代码，所以并不能直接执行使用。
4. 本项目只针对个人学习测试使用，并不做他用，且不对外公开，只对内测试。所以很抱歉，并不接受任何的star、pr和issue。
5. github本身就是为了给开发者更好更便捷的管理代码，如果你认为一个功能并没有给你带来实质性的帮助，那么你就应该放弃使用。而不是跟风认为别人这么做很帅很酷，而我也要去用。
6. 所有验证测试过的命令均记录于`github_note.md`文件。

[*此项目于2019/2/22开始进行测试*]
