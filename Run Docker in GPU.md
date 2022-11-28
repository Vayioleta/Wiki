## Run Docker in GPU

**Requirements**
> you must have NVIDIA Drivers CUDA Version: 12.0
> you can check it by running this command in Power Shell

`$ nvidia-smi `
 Power Shell You should get a response similar to this:
`
| NVIDIA-SMI 526.98 Driver Version: 526.98 CUDA Version: 12.0 |
`
if the Cuida is less than 12, update the drivers of your Nvidia graphics card.

------------


>To install on windows you must install Docker Desktop & restart
>Docker Desktop: https://www.docker.com/products/docker-desktop/

>you should now download the Linux Kernel Update Package on WSL 2 for x64 machines:
>https://learn.microsoft.com/es-es/windows/wsl/install-manual#step-4---download-the-linux-kernel-update-package
>you can find it here or download it directly from here:
>https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi

>To install Ubuntu distro for windows
>Ubuntu GPU https://www.microsoft.com/store/productId/9PDXGNCFSCZV

>Enabling Docker support in WSL 2 distros and config to default is Ubuntu in WSL 2
>WSL: https://docs.docker.com/desktop/windows/wsl/
>running this commands in Power Shell
>To check the WSL mode, run: `$ wsl.exe -l -v `
> ` wsl.exe --set-default-version 2 `
> I haven't closed this console yet.

> go to Docker Desktop an restart.
> go to Settings > Resources > WSL Integration.
> The Docker-WSL integration will be enabled on your default WSL distribution. To change your default WSL distro, run.

> go back to Power Shell console and select ubuntu
>`$ wsl --set-default ubuntu `
