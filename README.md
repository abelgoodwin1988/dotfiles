# dotfiles

> my dot files and how i set up my dev machine

| Tooling / QOL | Tool |
|:---|:---|
|IDE|[VSCode](https://code.visualstudio.com/)|
|Shell|[Zsh](https://github.com/robbyrussell/oh-my-zsh)|
|Containerization|[Docker](https://docs.docker.com/docker-for-mac/install/)|
|Container Orchestration|[Kubernetes](https://kubernetes.io/docs/tasks/tools/install-kubectl/#install-with-homebrew-on-macos)|
|Documentation Search|[Dash](https://kapeli.com/dash)|
|Pomodoro|[Pomotodo](https://pomotodo.com/intl/en/)|
|Memeing|[Tenor](https://tenor.com/mac)|

### Language Specific

#### Setup

1. Install Xcode (from appstore, I forget everytime)
2. Install [homebrew](https://brew.sh/), add to path.
    ```zsh
    /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
    ...
    ```

#### Python

1. Install [Python3](https://docs.python-guide.org/starting/install3/osx/)
    ```zsh
    brew install python
    ```
2. Install pipenv
    ```zsh
    pip3 install pipenv
    ```

#### Go

Download and use [package installer](https://golang.org/doc/install#macos).
