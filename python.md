# Python

### 包

- [openpyxl](http://openpyxl.readthedocs.io/en/default/): 处理 Excel 2010 xlsx/xlsm 

- [Pipenv](https://github.com/pypa/pipenv):提供包管理和虚拟环境支持
- pprint， 使用import pprint导入

### Jupyter Notebook插件

- Collapsible headings
- Notify
- Code folding
- tqdm_notebook： 执行进度条
- %debug：这也不是Notebook原生的。它最初是IPython magic的一个命令，支持两种激活调试器的方式：一是在执行代码之前激活调试器，二是在验尸模式下激活调试器。简而言之，就是当代码出现异常后，输入%debug可以直接激活调试器跳到出现错误的地方，而且你还可以检查前后代码情况。它实现了即时调试+快速迭代，更多细节可以参考Radek Osmulski的推文
- %lsmagic：执行%lsmagic，它会列出所有可用的IPython magics。
- Zen mode extension：隐藏活动状态栏，方便你把注意力集中在代码上。
- Execute time extension：显示运行的时间。
- autoreload：无需退出Jupyter Notebook就能动态修改代码。它的具体操作是：
    
    %load_ext autoreload%autoreload 2