# git-hooks
Some Git hooks that can be useful to have.

## 1. drupal-php-pre-commit ##

Checks for php parse-errors and devel/xdebug debug code before committing.

__Install:__
`<code>`
cp git-hooks/drupal-php-pre-commit MY-PROJECT/.git/hooks/pre-commit
chmod +x MY-PROJECT/.git/hooks/pre-commit
`<code>`
