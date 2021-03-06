
![](https://avatars3.githubusercontent.com/u/3979232?v=2&s=200)
#ROS 2.0 prototype for embedded devices using FreeRTOS

This prototype includes:

| chat|
|----------|
|  tinq dds|
|FreeRTOS|


### Compile the code

```bash
make
```


### Debugging with gdb:

```bash
make gdb
```

Assuming that `.gdbinit` is configured in your `$HOME` as:

```
# GDB init file
target remote 127.0.0.1:3333
```

In another shell:

```bash
 arm-none-eabi-gdb main.elf
```

![](http://osrfoundation.org/assets/images/osrf_masthead.png)
