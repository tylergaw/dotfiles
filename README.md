# Deprecated

Stopped using these in May 2020 when I switched to a new machine. Now that the default shell is zsh I went with https://github.com/ohmyzsh/ohmyzsh. It covers ~90% of what I needed. The few things it doesn't, I customized in my `.zshrc`.

----------

Make setting up new crud easier.

I borrowed this from Chris https://github.com/cshoe/dotfiles

## Setup
In general, you may have to make local changes to these depending on the machine. Just don't commit those back to master, or branch, tag or something. YMMV.

- Clone this repo to your home directory
- If it doesn't exist, create `~/.profile`

### Optional items
- git completion: If it doesn't exist, create `~/.git-completion.sh` and use https://github.com/git/git/blob/master/contrib/completion/git-completion.bash for the contents
- git prompt: If it doesn't exist, create `~/.git-prompt.sh` and use https://github.com/git/git/blob/master/contrib/completion/git-prompt.sh for the contents
- github open: Quick script to open the current repo on github.com. Create `~/.github-open.sh` and use https://gist.github.com/tylergaw/f9640c7f7050a206dced for the contents

## To Install, execute:

```bash
~/dotfiles/install.sh
```
