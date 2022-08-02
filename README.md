# cmp-emoji

nvim-cmp source for emojis.

# Setup

```lua
require'cmp'.setup {
  sources = {
    { name = 'emoji' }
  }
}
```

# Option

#### insert (type: boolean)

Specify whether emoji should be inserted or not.

Default: `false`
