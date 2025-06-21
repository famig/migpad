使用代码空间
终端依次输入：
cd zmk
west init -l app/
west update

 编译：
cd app
west build -p -b nrfmicro_13_52833 -- -DSHIELD=migpad
固件在app/build/zephyr/对应键盘名字的uf2文件
