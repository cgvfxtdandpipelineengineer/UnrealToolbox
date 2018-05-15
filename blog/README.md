
# 5/15/2018

## References

- http://www.chrisevans3d.com/pub_blog/python-ships-unreal-engine-4-19/
- https://github.com/20tab/UnrealEnginePython/tree/master/tutorials

## Installing PySide

pip that was shipped with Unreal Engine was not working

```bash
C:\Program Files\Epic Games\UE_4.19\Engine\Source\ThirdParty\Python\Win64\Scripts>pip.exe install PySide
Traceback (most recent call last):
  File "c:\python27\lib\runpy.py", line 174, in _run_module_as_main
    "__main__", fname, loader, pkg_name)
  File "c:\python27\lib\runpy.py", line 72, in _run_code
    exec code in run_globals
  File "C:\Program Files\Epic Games\UE_4.19\Engine\Source\ThirdParty\Python\Win64\Scripts\pip.exe\__main__.py", line 5, in <module>
ImportError: cannot import name main
```

I had to use the pip installed with my system python to install PySide

```bash
C:\Program Files\Epic Games\UE_4.19\Engine\Source\ThirdParty\Python\Win64>pip install PySide
Traceback (most recent call last):
  File "c:\python27\lib\runpy.py", line 174, in _run_module_as_main
    "__main__", fname, loader, pkg_name)
  File "c:\python27\lib\runpy.py", line 72, in _run_code
    exec code in run_globals
  File "C:\Program Files\Epic Games\UE_4.19\Engine\Source\ThirdParty\Python\Win64\Scripts\pip.exe\__main__.py", line 5, in <module>
ImportError: cannot import name main
```
