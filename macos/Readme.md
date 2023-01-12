# macos

macOS has some weird stuff going on. I got a collection of tipps and tricks.
I specifically talk about 2019 macbook pro 16 i9.

## 2x 4k displays

Having two 4k displays with USB-C connected to the macbook, there is a weird behaviour going on in the activity monitor. For some reason the "kernel_task"
skyrockets to >500% CPU usage. When I disconnect one monitor, it goes back to normal.

Possible solutions:
- Reset SMC
- Uncheck "Automatic graphics switching" in the Battery settings

Apparently this is a known issue: https://developer.apple.com/forums/thread/17263
