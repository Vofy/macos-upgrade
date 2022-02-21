## macOS Boot Options

`Shift`: Start your Mac in Safe Mode. Since safe mode only loads essential software, you can determine whether a system process or a user-installed application is causing your problem.

`Option`: Boot into Startup Manager. From here you can select different startup disks if any bootable partitions are available.

`Command` + `R`: Boot into Recovery Mode. Recovery Mode is macOS’s powerful recovery suite with a bunch of options for saving or wiping your Mac. You can use it to reinstall macOS, restore from a Time Machine backup or use Disk Utility to repair or format your hard drive.

![macos-high-sierra-recovery-mode-reinstall](https://user-images.githubusercontent.com/44552607/154996339-8f9f0046-8054-455f-899b-09c2e30c0312.png)


`Shift` + `Command` + `Option` + `R`: Start in Internet Recovery Mode, skipping your system’s hard drive. This allows you to reinstall the build of macOS that came with your computer from the factory. macOS might do this one on its own if your installation is so messed up that you can’t boot into Recovery Mode.

`Command` + `S`: Start in single user, command-line-only mode. This is useful for running diagnostic Terminal commands or fsck, but it can’t do much beyond that.

`Command` + `V`: Boot in verbose mode. This mode displays logging and diagnostic messages as your Mac boots. If your Mac is showing the Apple logo but failing to start completely, try this step to see where in the boot process the error occurs.

## Reset Commands

`Command` + `Option` + `P` + `R`: Reset your Mac’s NVRAM or PRAM. This small memory module stores certain settings essential to your Mac’s operation, and resetting is a good first step when you’re trying to resolve tricky hardware issues. Hold down the key combo immediately after pressing your Mac’s power button. Then release the keys after about twenty seconds. During the reset process it might seem like your Mac is restarting before starting up normally.

`Shift` + `Control` + `Option` + `Power`: Reset the SMC on an Apple laptop. The SMC, or System Management Controller, is responsible for low-level hardware functionality like fan speed, battery charging and sleep routines. To perform the reset, hold down the Shift, Control and Option keys on the left side of the built-in keyboard, then press the power button at the same time. Hold the modifier keys and power button down for ten seconds, then release all the keys and start the computer normally. For Apple desktops you can reset the SMC by disconnecting the power cable and all peripherals for fifteen seconds.

## Legacy Commands

`C`: Start up from a CD, DVD or USB thumb drive that contains a valid Mac operating system.

`T`: Start up in Target Disk mode. This command makes the computer it was executed on behave like a hard drive, allowing you to pull data off of it with another Mac. If you absolutely cannot save your computer, sometimes you can save the data with Target Disk Mode. The target computer must be connected with a Firewire, Thunderbolt or USB-C cable.

`Eject`, Mouse button, Trackpad button or `F12`: Eject a CD or DVD from the optical disc drive.

`X`: Force the system to boot from your macOS startup disk.


## Advanced Commands

![boot-option-shortcut-keys-apple-diagnostics](https://user-images.githubusercontent.com/44552607/154996207-6aceb051-a0f3-4045-b0f0-085a96eba934.png)

`D`: Start up in diagnostic mode, launching Apple Diagnostics. On pre-June 2013 Macs, this command launches the analogous Apple Hardware Test.

`Option` + `D`: Start the appropriate diagonistic utility over the Internet, bypassing your computer’s internal storage system.

`N`: Start from a compatible NetBoot server, if there is one available.

`Option` + `N`: Boot from the default boot image on a compatible NetBoot server.
