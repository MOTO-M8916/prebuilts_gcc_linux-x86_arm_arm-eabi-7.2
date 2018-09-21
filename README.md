# linaro 7.2


 git clone https://github.com/MOTO-M8916/prebuilts_gcc_linux-x86_arm_arm-eabi-7.2 -b master prebuilts/gcc/linux-x86/arm/arm-eabi-7.2


This in Boardconfig



# Kernel Toolchain
KERNEL_TOOLCHAIN := $(ANDROID_BUILD_TOP)/prebuilts/gcc/$(HOST_OS)-x86/arm/arm-eabi-7.2/bin
KERNEL_TOOLCHAIN_PREFIX := arm-eabi-

