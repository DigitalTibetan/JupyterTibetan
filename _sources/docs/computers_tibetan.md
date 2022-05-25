# Computers and Tibetan script

All current computers and operating system support working with Tibetan script. Worst contender is Windows that has no built-in input method for Wylie.

| Computer type | Tibetan display  | Input methods  | development | Support |
| ------------- | :--------------: | :------------: | :---------: | :-----: |
| [macOS](computers_macos.md)         |    + +           |   o[^1]          |   + +       | - - |
| [Windows](computers_windows.md)       |    + +           |   +[^2]        |   +         | + |
| [Linux KDE](computers_linux_kde.md)     |    + +           |   + +          |   + + +     | + + |
| [Linux Gnome](computers_linux_gnome.md)   |    + +           |   + +          |   + + +     | + + |

[^1]: macOS Wylie support is currently quite bug ridden and is currently no more Wylie EWTS-compliant. See [Working with macOS, keyboards](macos_keyboard) for work-arounds and details.
[^2]: Windows does not come with a Wylie input method.  Support for Wylie hinges on third-party tools with uncertain long-term availability. Alternatively Windows' own Tibetan keyboard, which is non-Wylie, can be used.

## I want to work with Tibetan texts, what's the best choice for a new computer?

* [Working with macOS](computers_macos.md): A good overall choice for most people is a macOS laptop: everything that's needed to work with Tibetan is already part of the operating system macOS: Tibetan fonts, Sanskrit fonts, input methods for Tibetan (caveat[^1]) and Sanskrit diacritics are built in, and only some simple configuration steps are required to activate everything that's needed. Things become problematic, if you ever encounter problems: Apple has basically *no working support* for bug tracking and improving situations for low-resource languages. Tibetan on Mac seems to be on slow decline.

* Working with Linux [KDE](computers_linux_kde.md) or [Gnome](computers_linux_gnome.md): For those who are technically well versed, Linux is the best choice: Linux hardware is available at lower cost, and the possibilities, especially, if natural language processing or [computational dharma](computational_dharma.ipynb) are areas of interest, Linux (KDE or Gnome is just a matter of taste) is an even better choice. Technical problems and bugs can be fixed, because of open source. The trade-off is the higher technical complexity.

* [Working with Windows](computers_windows.md): For every body else: Windows it will be. There are two drawbacks: a Wylie input method is only available via a third-party plug-ins that have last been updated around 2012 (TISE) and 2018 (Tib-Type), and it's uncertain if it will continue to work with newer versions of windows. If the focus might be on computational dharma, then Windows is not as good of a choice, posing more obstacles to getting things working than Linux. <br>Still, as of now it is perfectly possible to work with Windows computers and Tibetan texts.
