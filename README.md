lua source code note cn
===============================================================================

为了实现我自己的编译器，我觉得可以来看看 `Lua` 到底是怎么实现一门全新的语言。

Quick Build
-------------------------------------------------------------------------------

在 `Liunx` 下使用命令即可：
```shell
make
```

在这之前需要使用：
```shell
sudo apt install make
sudo apt install texlive-full
```

其中 `texlive-full` 的大小约为`4GB`。如果希望精简一点，可以去官网查看并下载包含
`lualatex` 和宏包 `listings` 的最小版。

如果包管理器不是 `apt` 的话，请自行变更。

Quick Join
-------------------------------------------------------------------------------

作为一个小项目，欢迎参加。可以通过 `pull request` 或者 `issue` 来申请项目的写权
限。如果你具有写权限的话，请注意：保证提交的较高质量。

根据模板（在 `./conf/gitmessage.txt` 中可见）来编写提交：

```txt
# please follow this:
# ${title.attribute}: (${title.scope}) ${title.subject}
# [two-newlines] ${body}
# [two-newlines] ${footer}
#
# details:
# [title]
#     - attribute
#         - feat: new feature
#         - fix : fix the bug
#         - docs: about documents
#         - stl : the style of code
#         - rfcr: refactor the code but not add new feature
#         - test: about test
#         - chor: about helper or config
#     - scope
#         : about what the commit for
#     - subject
#         : tell shortly
# [body]
#     : those details
# [footer]
#     : about the issue message
#
```

在加入之前，最好在 `github.com/lua/lua` 中克隆一份。

跟随、或者添加 TODO。如果有较大改动的话，请提交 `issue`。

请注意：保证较高质量。

