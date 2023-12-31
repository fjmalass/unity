# Sunblink - Onboarding Unity

## License
Copy files in `License` folder in `<NINTENDO_SDK_ROOT>\NintendoSDC\Include\nn\account` directory

## Using NNPM
 No longer using hardware

### Update Switch Firmware

1. **OS** `<NintendoSDK-Version>\NintendoSDK\Tools\CommandLineTools\InitializeSdevWin.exe`: Firmware updater (*Edev*, *Adev*, etc.)

2. **Controllers**: `<NintentdoSDK-Version>\NintendoSDK\TargetTools\NX-NXFP2-a64\ControllerFirmwareUpdater\Release` 
    a. Copy `nsp` to device using `Target Manager`
    b. Run to update controllers

 
## Target Manager 2
 * `C:\Program Files\Nintendo\NintendoTargetManager2\NintendoTargetManager2.exe`
 * `C:\Program Files\Nintendo\NintendoSdkDaemon\NintendoSdkDaemon.exe`

### Default Target Logs: 
`<USER>\AppData\Local\Temp\Nintendo\TargetLogs`

## Documentation 

Location of Tools and files `https://developer.nintendo.com/` `NX->Features->Controlling the Development Hardware` 

## Timing on Switch

### `Production` FPS
* Switch: Enable FPS screen in "DevMode (Hold "Home" button and select "Report FPS")

### `Production` Nintendo CPU Profile
* `<NintendoSDK-Version>\NintendoSDK\Tools\NintendoCpuProfiler\Nintendo CPU Profiler.exe`
* `https://developer.nintendo.com/html/online-docs/g1kr9vj6-en/Packages/SDK/NintendoSDK/Documents/Package/contents/Pages/Page_171379056.html`

### `Development` GPU - Low Level Graphics Debugger (LLGD)
* In `<NintendoSDK-Version>\LowLevelGraphicsDebugger\Llgd\LLGDHost.exe`




