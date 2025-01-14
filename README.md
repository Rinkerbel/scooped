# scooped [![Tests](https://github.com/Rinkerbel/scooped/actions/workflows/ci.yml/badge.svg)](https://github.com/Rinkerbel/scooped/actions/workflows/ci.yml) [![Excavator](https://github.com/Rinkerbel/scooped/actions/workflows/excavator.yml/badge.svg)](https://github.com/Rinkerbel/scooped/actions/workflows/excavator.yml)

A [Scoop](https://scoop.sh) bucket containing some apps that weren't on scoop yet.

## List of applications in this bucket

- [Seanime](https://github.com/5rahim/seanime)

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add <bucketname> https://github.com/<username>/<bucketname>
scoop install <bucketname>/<manifestname>
```
## Usage

After installing [Scoop](https://scoop.sh/), enter the following line in a
Command Prompt or PowerShell window:

```powershell
scoop bucket add Rinkerbel_scooped https://github.com/Rinkerbel/scooped
```

Once this is done, you can install any app from this bucket.\
For instance, use the following command:

```powershell
scoop install seanime-server
```
