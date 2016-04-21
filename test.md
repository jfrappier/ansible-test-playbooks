>>> from markdown import Markdown

>>> markdown = Markdown(extensions=['fontawesome_markdown']
>>> markdown.convert('i ♥ :fa-coffee:')
<p>i ♥ <i class="fa fa-coffee"></i></p>
