# hyper-v
**2021.11**

**Virtual box Ubuntu, Wsl2 issue**

## 설명
* 저 두개를 하나의 컴퓨터에 설치하면 충돌이 일어나는데, hyper-V때문이다.
* To disable:

```
bcdedit /set hypervisorlaunchtype off
```

* To enable:
```
bcdedit /set hypervisorlaunchtype auto
```
