# manifest

build environment for xiaomi 12 "cupid" lineageos kernel

`mkdir cupid-kernel && cd cupid-kernel`

`repo init -u https://github.com/carlyle-felix/manifest.git`

`repo sync`


`curl -LSs "https://raw.githubusercontent.com/tiann/KernelSU/main/kernel/setup.sh" | bash -` <-- KernelSU


`. build_cupid.sh` <-- build kernel


`. zip.sh` <-- pack flashable zip in /AnyKernel3
