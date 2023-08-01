# tree-sitter-surrealdb.nvim
tree-sitter-surrealdb nvim integration plugin

## features
### highlighting
![highlighting](https://raw.githubusercontent.com/DariusCorvus/DariusCorvus/main/assets/wezterm-gui_X5Q2m2wOXH.png)

### inline javascript
![Inline Javascript](https://raw.githubusercontent.com/DariusCorvus/DariusCorvus/main/assets/wezterm-gui_JxVBb8Lgg5.png)

## tree-sitter
[tree-sitter-surrealdb](https://github.com/DariusCorvus/tree-sitter-surrealdb)

## usage
###
The official extension for SurrealDB files is `.surql`, by default files which matches the pattern `*.surql` are detected.

### requirements
- [nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter)
### installation

_Packer:_

```lua
use({
	"dariuscorvus/tree-sitter-surrealdb.nvim",
	requires = { "nvim-treesitter" },
})
```

_Lazy:_

Try running `:TSInstall surrealdb` if syntax highlighting doesn't appear after loading plugin.

```lua
 {
  "dariuscorvus/tree-sitter-surrealdb.nvim",
  dependencies = { "nvim-treesitter/nvim-treesitter" },
  config = function()
    -- setup step
    require("tree-sitter-surrealdb").setup()
  end,
}
```

### setup

_Packer:_

```lua
require("tree-sitter-surrealdb").setup()
```

