# 依赖

除了需要安装 python2.7 和 VCForPython27.msi 之外，还需要安装 pywin32、Pycrypto

```python
pip install Pycrypto
pip install pywin32
```

# 运行

```shell
python ineptpdf.py "password" "D:\source.pdf" "D:\target.pdf"
```

直接运行 `python ineptpdf.py` 会打开 GUI 窗口
