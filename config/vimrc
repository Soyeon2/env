set expandtab
autocmd BufEnter * lcd %:p:h
filetype plugin on
filetype plugin indent on  
set nobackup tabstop=4 shiftwidth=4 foldmethod=marker
set foldmethod=indent
set foldcolumn=2
set nu
set encoding=utf-8
set fileencodings=ucs-bom,utf-8
set laststatus=2
set statusline=%f%m%r%h%w%=[FORMAT=%{&ff}][TYPE=%Y][ASCII=%03.3b][HEX=%02.2B][POS=%04l,%04v][%02.3p%%]
set noswapfile
set t_Co=256  
colo tokyo-metro

autocmd BufNewFile *.lua, exec ":call SetTitle()"
let $author_name = "Louis"
let $version = "1.0"
 
func SetTitle()
    call setline(1,"\--------------------------------------------------------------")
    call append(line("."), "\--! @File Name: ".expand("%"))
    call append(line(".")+1, "\--! @Author: ".$author_name)
    call append(line(".")+2, "\--! @brief: ")
    call append(line(".")+3, "\--! @version: ".$version)
    call append(line(".")+4, "\--! @Created Time: ".strftime("%c"))
    call append(line(".")+5, "\--------------------------------------------------------------")
endfunc

