# How to use this manifest

## Download source

Init repo

	repo init --repo-url=https://mirrors.tuna.tsinghua.edu.cn/git/git-repo -u https://github.com/54shady/qop_manifests -b master

sync all project code

	repo sync

## Download compiler

	wget https://releases.linaro.org/components/toolchain/binaries/6.3-2017.05/aarch64-linux-gnu/gcc-linaro-6.3.1-2017.05-x86_64_aarch64-linux-gnu.tar.xz
	mkdir -p prebuilts/gcc/linux-x86/aarch64
	tar Jxvf gcc-linaro-6.3.1-2017.05-x86_64_aarch64-linux-gnu.tar.xz -C prebuilts/gcc/linux-x86/aarch64/
