# 显示器亮度调节-ddcctl

## 安装
----
```bash
make install
```

For an On-Screen Display using [OSDisplay.app](https://github.com/zulu-entertainment/OSDisplay):  
`make CCFLAGS=-DOSD clean ddcctl`

## 使用
----
Run `ddcctl -h` for some options.  
[ddcctl.sh](/ddcctl.sh) is a script I use to control two PC monitors plugged into my Mac Mini.  
You can point Alfred, ControlPlane, or Karabiner at it to quickly switch presets.  

执行以下命令调节显示器亮度。其中 1 代表显示器 1，60 代表亮度 60%。

```
ddcctl -d 1 -b 60
```
