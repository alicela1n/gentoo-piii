# Why does this exist?
Simply put, some packages, such as polkit, and librsvg require rust. The Gentoo rust packages require SSE2, and there seems to be no way to build rust without it. One workaround is building rust on another machine without SSE2, however I want to build as much as possible natively on the machine.

# Use at your own risk
I created this overlay to run Gentoo on my Pentium III computer, I won't be actively maintaining it. I might fix issues, if you open a GitHub issue, or pull request, however don't expect me to actively maintain it.
