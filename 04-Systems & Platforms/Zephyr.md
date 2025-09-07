# Installation 
1. Install gcc with https://www.msys2.org/ 
1a. Add to path ```C:\msys64\ucrt64\bin```
1b. Test ```gcc --version```
2. Python manual install 
https://docs.zephyrproject.org/latest/develop/getting_started/index.html



# File Structure (inside zephyrproject\zephyr_apps\<project>)

## src\main.c
```C
#include <zephyr/kernel.h>
#include <zephyr/drivers/gpio.h>

int main(void)
{
    printk("Hello from GPIO config app!\n");
    return 0;
}
```
## CMakeList
```txt
cmake_minimum_required(VERSION 3.20.0)

find_package(Zephyr REQUIRED HINTS $ENV{ZEPHYR_BASE})
project(gpio_config)
target_sources(app PRIVATE src/main.c)
```

## prj.conf
```
CONFIG_LOG=y
```


# Instructions
cd ${ZEPHYR_PROJECT_PATH}\zephyrproject
.\.venv\Scripts\Activate.ps1
$env:ZEPHYR_BASE="${ZEPHYR_PROJECT_PATH}\zephyrproject\zephyr"
pip install pyelftools
west build -b nucleo_u575zi_q -p always .
