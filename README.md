# XenBlox
> Efficient multi-arch (yet) CPU miner for Xen Blocks

## About
Go to [Release](https://github.com/beshenkaD/XenBloxMiner/releases) page to download XenBlox.
### Features
- Easy to use. A simple json config is enough to start mining. Simple distribution for all popular systems.
- Multi-arch. Currently XenBlox supports `amd64` and `aarch64`.
- Multi-platform. Both windows and linux are supported. There is deb packages for linux.
- Highly optimized using SIMD instructions. SSE, AVX, XOP, NEON are supported.
- Automatic check for updates.
- [TODO] Hiveos support.
- [TODO] Built-in validator.
- [TODO] GPU support (both nvidia and amd!)

### DevFee
Minimum devfee is 2%. The devfee is triggered every 2 hours and lasts for about 2.4 minutes.  
**Important note**: DevFee triggers using local time, not a timer. So there is no way to skip it via miner restarting.

## Contribution
At the moment the miner is in `alpha` version, so there might be bugs. If you encounter any problems feel free to open the [issue](https://github.com/beshenkaD/XenBloxMiner/issues). Take a look at [issue template](https://github.com/beshenkaD/XenBloxMiner/blob/main/ISSUE.md) to get started. 
Also you can contact me directly using [telegram](https://t.me/beshenkaD).
