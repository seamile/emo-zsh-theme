# Emo Zsh Theme

An [oh-my-zsh](https://ohmyz.sh/) theme inspired by [lambda mod theme](https://github.com/halfo/lambda-mod-zsh-theme).

Named 'emo' for its use of random emoji symbols as prompt leaders, this theme brings variety to your terminal by switching to a new emoji each time you open a shell. It also offers a rich set of clear symbolic indicators for diverse Git repository states.


## Screenshot

![summary](./ScreenShot.png)


## All status symbols

| Status symbol | Description                       |
|:-------------:|-----------------------------------|
|     **✚**     | new files or modifications added  |
|     **✘**     | files deleted                     |
|     **⚫︎**     | files modified but unstaged       |
|     **↺**     | files renamed                     |
|     **☑**     | stashed changes                   |
|     **⤭**     | unmerged conflicts                |
|     **?**     | untracked files                   |
|     **⤒**     | local branch ahead of remote      |
|     **⤓**     | local branch behind remote        |
|     **ᚶ**     | local branch diverged from remote |
|       🔒       | read only dir                     |
|       ⚙️       | background jobs are running       |


## Depends

- zsh
- git
- [oh-my-zsh](https://ohmyz.sh/#install)
- [powerline-fonts](https://github.com/powerline/fonts)


## Install

1. Download

    ```shell
    wget https://raw.githubusercontent.com/seamile/emo-zsh-theme/master/emo.zsh-theme -P $ZSH_CUSTOM/themes
    ```

    or

    ```shell
    curl -sSfL https://raw.githubusercontent.com/seamile/emo-zsh-theme/master/emo.zsh-theme -o $ZSH_CUSTOM/themes/emo.zsh-theme
    ```

2. Usage

    use the `omz` command: `omz theme set emo`

    or

    Open `~/.zshrc` with an editor and manually modify the value of `ZSH_THEME` to `ZSH_THEME="emo"`
