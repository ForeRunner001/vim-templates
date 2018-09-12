# vim-templates
vim plugin for files template

vim script is from [here](http://forum.ubuntu.org.cn/viewtopic.php?f=68&t=306094)

----

- **step 1** edit ~/.vimrc

```
g:enable_template = 1

let g:template_dir = "~/.vim/bundle/vim-templates/templates"
```

----

- **step 2** add plugin in vundle

```
call vundle#begin()

...  # other plugins

Plugin 'ForeRunner001/vim-templates'

...  # other plugins

call vundle#end()
```

----

- **step 3** install plugin

```
vim

:PluginInstall
```

