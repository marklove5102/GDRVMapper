# GDRVMapper
This is similar to GdrvLoader but it works on EAC (&amp; BE but same for GdrvLoader) with included gdrv.sys (cert)

Place gdrv.sys from the main dir to `C:\Windows\System32\drivers` and load using exported `WindLoadDriver/WindUnloadDriver` functions.

```cpp
WindUnloadDriver("C:\\Windows\\System32\\Drivers\\YourDriver.sys", TRUE);
WindLoadDriver("C:\\Windows\\System32\\Drivers\\gdrv.sys", "C:\\Windows\\System32\\Drivers\\YourDriver.sys", TRUE);
```

discord `s.n.o.w.l.e.o.p.a.r.d`
