## Hexo Tag Plugins Sublime Text Snippets

[Hexo](https://hexo.io/ "hexo official site") tag plugins snippets for [Sublime text 3](http://www.sublimetext.com/ "Sublime text 3 official site").  

### Installation

#### For Windows
`$ cd "%APPDATA%/Sublime Text 3\Packages\User"`  
`$ git clone: https://github.com/hatobane/hexo-tag-plugins-sublime-snippets.git`

#### For Mac/Linux
`$ cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages`  
`$ git clone: https://github.com/hatobane/hexo-tag-plugins-sublime-snippets.git`

### Snippets
Snippet            | Tab Trigger   | Output
:-----------       | :-----------  | :-----------
tags               | hexo-tag      | {% tag option %}
blockquote(source) | hexo-bq       | {% blockquote "author", "source" %} <br> content <br> {% endblockquote %}
blockquote(link)   | hexo-bq       | {% blockquote "author" URL "source title" %} <br> content <br> {% endblockquote %}
codeblock          | hexo-cb       | {% codeblock "title" lang:html URL "link text" %} <br> content <br> {% endcodeblock %}
raw                | hexo-raw      | {% raw %} <br> content <br> {% endraw %}
image              | hexo-img      | {% img class /path/to/image width height "title text" %}
link               | hexo-a        | {% link "text" URL "title" %}
post path          | hexo-pp       | {% post_path file %}
post link          | hexo-pl       | {% post_link file "text" %}
asset path         | hexo-ap       | {% asset_path file %}
asset link         | hexo-al       | {% asset_link file "text" %}
asset image        | hexo-ai       | {% asset_img file %}
pull quote         | hexo-pq       | {% pullquote class %}content{% endpullquote %}
