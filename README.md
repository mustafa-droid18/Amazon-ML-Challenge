# Amazon-ML-Challenge
[Colab File](https://colab.research.google.com/drive/1fjSKCifsi2b0_s8yjraTt6eDEjrgJIbx?usp=sharing)


### Setting Up Virtual Env
1. Windows 
```

    pip install virtualenv 
    Set-ExecutionPolicy Unrestricted -Scope Process
    virtualenv envW
    # In cmd.exe
    envW\Scripts\activate.bat
    # In PowerShell
    envW\Scripts\Activate.ps1
```

```
Problem: cannot be loaded because running scripts is disabled on this system
https://stackoverflow.com/questions/67150436/cannot-be-loaded-because-running-scripts-is-disabled-on-this-system-for-more-in
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted
```

2. Linux 
