# PyMicroChat

##Python3.3以上的版本通过venv模块原生支持虚拟环境，可以代替Python之前的virtualenv.低版本请用pip安装。

> git 下载
>>    git clone https://github.com/InfiniteTsukuyomi/PyMicroChat.git

Windows环境
> 创建Python3的venv虚拟环境
>> D:\VSCODE\PyMicroChat>python3 -m venv .

> 进入虚拟环境
>> D:\VSCODE\PyMicroChat>.\Scripts\activate

> 首次执行，配置依赖包，以后根据更新依赖环境运行
>> (PyMicroChat) D:\VSCODE\PyMicroChat>pip freeze > requirements.txt

> 修改run.py相应的usrname & passwd，执行
>> (PyMicroChat) D:\VSCODE\PyMicroChat>python run.py

> 退出
>> (PyMicroChat) D:\VSCODE\PyMicroChat>deactivate