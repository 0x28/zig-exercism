# Installation

There are many ways to install Zig, and the number of ways to install Zig are steadily increasing as the language matures.
Fortunately, all of the popular installation methods are listed on the [Zig install page][install-zig].

## Additional utilities

### Zig fmt - Generating well-formatted code

When completing any exercise, you may use all kinds of code styles for your solutions.
However, outside of solving exercises, such as making applications or libraries, it's typically a good idea to make your code consistent and readable.
Those assumption are especially important when others who would want to help out with your projects would have to read your code.

To fix this problem the Zig compiler comes with a built-in lightweight [linter][linters] to format your code in a convenient manner.
This code formatter aims to follow the [style guide][style-guide] already established by the [Zig documentation][documentation].

To see the features of Zig's native formatter use the following command:

```bash
zig fmt --help
```

### Zig Zen - Rules to code by!

Sometimes some direction goes a long way when completing any task, even when writing code.
Thankfully we have a fun command built right into the Zig compiler to remind ourselves of some of the goals that go into writing good Zig code.

To check out these words of wisdom you can use the following command:

```bash
zig zen
```

[documentation]: https://ziglang.org/documentation/master/
[install-zig]: https://ziglang.org/download/
[linters]: https://en.wikipedia.org/wiki/Lint_(software)
[style-guide]: https://ziglang.org/documentation/master/#Style-Guide
