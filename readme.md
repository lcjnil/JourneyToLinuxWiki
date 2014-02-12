# 说明
这个wiki是在Vimwiki下建成的,其配置文件为

    set nocompatible
    filetype plugin on
    syntax on

    let g:vimwiki_list = [{'path': '~/vimwiki/',
    \ 'path_html': '~/vimwiki/html/',
    \ 'template_path': '~/vimwiki/templates/',
    \ 'template_default': 'templates',
    \ 'template_ext': '.html'}]
    let g:vimwiki_camel_case = 0
    let g:vimwiki_CJK_length = 1
    let g:vimwiki_valid_html_tags='b,i,s,u,sub,sup,kbd,br,hr,div,del,code,small,p,pre'

简单的Vimwiki语法这里不再赘述
因为Vimwiki的语法和Markdown的语法不一样,所以会导致直接在github中访问wiki文件排版格式出错,所以想要浏览,最好在html下访问网页.

未来的安排:
* 转为Markdown语法,并且用pandoc生成HTML
* 整体上目录再规划
* 加入更多细致的内容
