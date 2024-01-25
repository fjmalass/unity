# Sunblink - Onboarding Unity

## Communication Suite

- Notion (malassenet@gmail.com)
- Slack (malassenet@gmail.com)
- Linear (malassenet@gmail.com)
- Google Drive (malassenet@gmail.com)
  - [Perf Google Drive](https://drive.google.com/drive/folders/1VQs6GZ01UiJ4ay48NPYjCzFVQ9qkpkOL)

## License

Copy files in `License` folder in `<NINTENDO_SDK_ROOT>\NintendoSDC\Include\nn\account` directory

## Using NNPM

No longer using hardware

### Update Switch Firmware

1. **OS** `<NintendoSDK-Version>\NintendoSDK\Tools\CommandLineTools\InitializeSdevWin.exe`: Firmware updater (_Edev_, _Adev_, etc.)

2. **Controllers**: `<NintentdoSDK-Version>\NintendoSDK\TargetTools\NX-NXFP2-a64\ControllerFirmwareUpdater\Release`
   a. Copy `nsp` to device using `Target Manager`
   b. Run to update controllers

## Target Manager 2

- `C:\Program Files\Nintendo\NintendoTargetManager2\NintendoTargetManager2.exe`
- `C:\Program Files\Nintendo\NintendoSdkDaemon\NintendoSdkDaemon.exe`

### Default Target Logs:

`<USER>\AppData\Local\Temp\Nintendo\TargetLogs`

## Documentation

Location of Tools and files `https://developer.nintendo.com/` `NX->Features->Controlling the Development Hardware`

## Timing on Switch

### `Production` FPS

- Switch: Enable FPS screen in "DevMode (Hold "Home" button and select "Report FPS")

### `Production` Nintendo CPU Profile

- `<NintendoSDK-Version>\NintendoSDK\Tools\NintendoCpuProfiler\Nintendo CPU Profiler.exe`
- [developer.nintendo.com](https://developer.nintendo.com/html/online-docs/g1kr9vj6-en/Packages/SDK/NintendoSDK/Documents/Package/contents/Pages/Page_171379056.html)
- To look up the Assembly to source code, Expected `.nso` files should reside in `<NintentdoSDK-Version>/NintendoSDK/Libraries/NX-NXFP2-a64/Release`
- Options->General->Assembly:
  - Command: `"C:\Program Files\JetBrains\JetBrains Rider 2023.3\bin\rider64.exe"`
  - Arguments: `--line $2 $1`
- Rem: `Diff` in the `Function` is active when a previous profile has been opened

### `Development` GPU - Low Level Graphics Debugger (LLGD)

- In `<NintendoSDK-Version>\LowLevelGraphicsDebugger\Llgd\LLGDHost.exe`

## Switch and Specifics

### Limits Maxima for File [Write/Read](https://developer.nintendo.com/html/online-docs/nx-en/g1kr9vj6-en/document.html?doc=Packages/Docs/Guidelines/NX-Guidelines/NintendoSwitch-Guidelines.html) - [NintendoSDK-API nn::fs::library](https://developer.nintendo.com/html/online-docs/nx-en/g1kr9vj6-en/document.html?doc=Packages/SDK/NintendoSDK/Documents/index.html)

## Clean Git

1. `git clean -xdf` - Remove all changes
2. `git reset --hard HEAD` - Discard
3. `git pull` - Get the latest
