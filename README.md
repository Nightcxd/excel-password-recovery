# Excel-Password-Recovery

移除 Excel 文件的工作簿密码保护、工作表密码保护、只读密码保护。

> 1. 只能直接移除密码保护，不能获取原密码
> 2. 只支持 `.xlsx` 格式文件，不支持`.xls`等其它格式
> 3. 无法移除打开密码

## Usage

Install requirements

```console
$ pip install -r requirements.txt
```

Run GUI

```console
$ apt install python3-tk    # if you are using python3
$ python src/gui-main.py
```

Run in command line:

```console
$ python src/tools/recovery.py [input.xlsx] [output.xlsx]
```

Distribute as `.exe` (Windows only):

```console
$ # install [py2exe](http://www.py2exe.org/)
$ python src/setup.py py2exe
```
