# MSDOS_echo

**Tags:** echo

## 1. echo

The echo command is used to show messages, most commonly from within script or batch files.

**Example 1**

> File path: ./test/test.bat

```
echo Hello
echo %%
echo %%1
echo zzz.bat
```

> CMD window output

```
C:\Users\UdCen\Desktop\test>test.bat

C:\Users\UdCen\Desktop\test>echo Hello
Hello

C:\Users\UdCen\Desktop\test>echo %
%

C:\Users\UdCen\Desktop\test>echo %1
%1

C:\Users\UdCen\Desktop\test>echo zzz.bat
zzz.bat

C:\Users\UdCen\Desktop\test>
```

## 2. @echo off

The echo command can also be used to turn the echoing feature (command lines display) on or off.

**Example 2**

> File path: ./test/test.bat

```
@echo off
echo Hello
echo %%
echo %%1
echo zzz.bat
```

> CMD window output

```
C:\Users\UdCen\Desktop\test>test.bat
Hello
%
%1
zzz.bat

C:\Users\UdCen\Desktop\test>
```
