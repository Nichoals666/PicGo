# anaconda镜像源



> ## 清华镜像源
>
> ```python
> conda config --set show_channel_urls yes
> conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/
> conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main/
> conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
> conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/pytorch/
> 
> 
> conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/
> conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
> conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/msys2/
> conda config --set show_channel_urls true
> ```

 

> ## 中科大源
>
> ```python
> conda config --add channels https://mirrors.ustc.edu.cn/anaconda/pkgs/main/
> conda config --add channels https://mirrors.ustc.edu.cn/anaconda/pkgs/free/
> conda config --add channels https://mirrors.ustc.edu.cn/anaconda/cloud/conda-forge/
> conda config --add channels https://mirrors.ustc.edu.cn/anaconda/cloud/msys2/
> conda config --add channels https://mirrors.ustc.edu.cn/anaconda/cloud/bioconda/
> conda config --add channels https://mirrors.ustc.edu.cn/anaconda/cloud/menpo/
> conda config --set show_channel_urls yes
> ```



> ## 豆瓣源
>
> ```python
> pip install 包名 -i http://pypi.douban.com/simple/ --trusted-host pypi.douban.com
> ```
>
> 

