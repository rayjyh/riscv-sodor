srcDir          := $(abspath ../../)

CXX := g++
SBT := java -Xmx4096M -Xss8M -XX:MaxPermSize=128M -jar $(srcDir)/sbt-launch.jar $(SBT_FLAGS)

MK_TARGET_PROC  := rv32_2stage
 
global_asm_tests += \
	rv32mi-p-csr \
	rv32mi-p-illegal \
 
include $(srcDir)/emulator/common/Makefile.include
