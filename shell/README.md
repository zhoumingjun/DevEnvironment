# shell

## oh-my-zsh

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
curl -o ~/.oh-my-zsh/themes/honukai.zsh-theme https://raw.githubusercontent.com/oskarkrawczyk/honukai-iterm/master/honukai.zsh-theme
case "$OSTYPE" in
  darwin*)  sed -i '' 's/^ZSH_THEME=.*/ZSH_THEME="honukai"/' ~/.zshrc ;; 
  linux*)   sed -i 's/^ZSH_THEME=.*/ZSH_THEME="honukai"/' ~/.zshrc ;;
  *)        echo "unknown: $OSTYPE" ;;
esac

```

 