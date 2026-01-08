### `git reset --soft`

* It removes the commit but keeps changes staged
* local, unpushed commits is not get delete
* Useful to quickly fix a mistaken commit or message

### `git revert`

* Creates a new commit that undoes the changes
* Preserves history
* Safe for pushed or shared branches

## we can say :
Use `reset --soft` before pushing, and `revert` after pushing.
