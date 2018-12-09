# Master-of-my-own-git
To git and beyond


## Git Config
How to `~/.gitconfig` 
your git Experience can change by adding the following lines to your git config file `~/.gitconfig`.

### 1. User Info

`
[user]
	email = v.vidu171@gmail.com
	name = vidhyanshu
`

### 2. Create Alias

Create alias for all repo url being frequently use
`
[url "https://github.com/vidu171/"]
    insteadOf = vidu:
`


### 3. Open the corrosponding git Repo

Open the corrosponding git repo directly from terminal

Install git-open 
`
npm install --global git-open
`

Some Examples

```sh
$ git open
# opens https://github.com/TRACKED_REMOTE_USER/CURRENT_REPO/tree/CURRENT_BRANCH

$ git open someremote
# opens https://github.com/PROVIDED_REMOTE_USER/CURRENT_REPO/tree/CURRENT_BRANCH

$ git open someremote somebranch
# opens https://github.com/PROVIDED_REMOTE_USER/CURRENT_REPO/tree/PROVIDED_BRANCH

$ git open --issue
# If branches use naming convention of issues/#123,
# opens https://github.com/TRACKED_REMOTE_USER/CURRENT_REPO/issues/123
```
Checkout https://github.com/paulirish/git-open for more. 

