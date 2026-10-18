###  Install Homebrew
<code>
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
</code>

### Install RayCast
<code>brew install --cask raycast</code>

### Install Chrome
<code>brew install --cask google-chrome</code>

### Install Github
<code>brew install gh</code>

### Install Aerospace
<code>brew install --cask nikitabobko/tap/aerospace</code>

### Install 1Password
<code>brew install --case 1password</code>

### Install Cursor 
<code>brew install --cask cursor</code>

### Install VS Code
<code>brew install --cask visual-studio-code</code>

### Install Claude
<code>brew install --cask claude</code>

### Install Slack 
<code>brew install --cask slack</code>

### Install TablePlus
<code>brew install --cask tableplus</code>

### Install Postgres
<code>brew install postgres@18</code>

### Install oh-my-zsh
<code>sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"</code>

### Install Notion
<code>brew install --cask notion</code>

### Install NVM (Node Version Management)
<code>brew update && brew install nvm</code>
You should create NVM's working directory if it doesn't exist: `mkdir ~/.nvm`

Enable the built-in `nvm` oh-my-zsh plugin in ~/.zshrc config file

### Install OrbStack (Docker Containers Management)
<code>brew install orbstack</code>
If you use Oh My Zsh, you can install completions without modifying ~/.zshrc by storing the completion script in the ~/.oh-my-zsh/completions directory.

```
    $ brew install docker-completion
    $ mkdir -p ~/.oh-my-zsh/completions
    $ docker completion zsh > ~/.oh-my-zsh/completions/_docker
```

### Install Redis Server
<code>brew install redis</code>
Start the redis server
<code>brew services start redis</code>
