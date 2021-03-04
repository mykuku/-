#同类型表格合并
Same type table merge
可将同个类型excel表格合并成一个excel表格


想必复制粘贴的工作内容是否让你感到厌倦
重复性的工作内容让你感到疲倦，乏味
甚至是身体上带来的疲惫

你是否有过需要将多个表格的数据内容一个个复制粘贴到一个表格进行汇总吗？
假如是一两个乃至10个左右的表格进行合并，都可以自己手动复制粘贴
可是当文件数量上升到上百上千呢，再更甚者，每天都要进行成千上万的表格复制粘贴工作
你是否会因此而崩溃

现在我自己根据自己自学的python知识，做出了这么一个可以合并多个表格的小工具，
将全部需要合并的同类型表格放入同一个文件夹当中，运行脚本，会弹出一个小框，这个框是我用tkinter库所作的GUI界面
点击“选择”按钮，选择文件所在的文件夹，ps：如果选择的文件夹当中，并未有excel文件，我通过tkinter会弹出一个并未找到文件的提示框
再点击“筛选文件”按钮，这时会再次弹出一个选择窗口
该窗口是我借鉴他们分享于网上UI布局，利用tkinter中的画布canvas和滚动条scroll放在一个框架Frame当中实现了，展现你所选择的文件夹中，需要合并的全部excel列表
并且设置多个函数如多选函数，以及全选的回调函数，可以再次确认，或者去除来不及从文件夹剔除的excel文件
最后点击左上角“合并”按钮，脚本就会运行
合并成功的表格会被放置在选择的文件夹当中，并且此时会弹出提示你是否需要打开该文件的窗口
ps:保存的文件命名为当时合并的时间
