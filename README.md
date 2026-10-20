# Zephyr
- Clone this **Zephyrproject** Repository
- Run **west init -l Repo** using CMD in Repo Folder
- Do **west update**

# Environment update
set ZEPHYR_TOOLCHAIN_VARIANT=zephyr
set ZEPHYR_SDK_INSTALL_DIR=C:\Users\Chait\Desktop\zephyrproject\zephyr-sdk-0.16.9

# Build Commands
west build -p always -b cytvii_b_e_1m_100_cpu/cyt2b75cae/m0p ../my-app <!-- Blinky code -->
west build -p always -b cytvii_b_e_1m_100_cpu/cyt2b75cae/m4 samples/basic/button
