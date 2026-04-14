# Vega10 BIOS Editor

## English

Vega10 graphics card BIOS editing tool. Designed for AMD MI25 and MI50 GPUs.

Original code was forked from an unknown developer. This version adds:
- Chinese/English language switching (toggle in top-right corner)
- Export registry file function - no need to flash BIOS, works like More Power Tool
- Fixed bugs in the original code

### Environment Requirements

- **Operating System:** Windows 10/11
- **.NET Framework:** 4.7.1 or higher (usually pre-installed on Windows 10/11)
- **Graphics Card:** AMD Vega 10 series (Vega 56, Vega 64, etc.)

### How to Use

1. **Download:**
   - Go to [Releases](https://github.com/303287771/Vega10BiosEditor/releases) or download from `VegaBiosEditor/bin/Debug/` folder
   - Download `VegaBiosEditor.exe` and `VegaBiosEditor.exe.config`

2. **Run:** Double-click `VegaBiosEditor.exe` to start

3. **Edit BIOS:**
   - Click "OPEN" to load your BIOS file (.rom)
   - Modify parameters (Power Control Limit, GPU/Memory clock, etc.)
   - Click "SAVE" to save modified BIOS file

4. **Export Registry (No Flashing):**
   - After modifying parameters, click "Export Registry" button
   - Save as .reg file
   - Double-click to import - no BIOS flashing required!
   - Restart computer or reload AMD driver to take effect

### Language Switch

Toggle between English/Chinese using the dropdown in the top-right corner.

**Note:** Use at your own risk. I'm not responsible for any damage.

---

## 中文

Vega10显卡BIOS调整工具。专为AMD MI25和MI50显卡设计。

原代码忘了是从哪个大神那克隆的，此版本增加：
- 中英语言切换（右上角下拉框）
- 导出注册表文件功能，无需刷BIOS，像More Power Tool软件那样
- 修复了原代码中的bug

### 环境依赖

- **操作系统：** Windows 10/11
- **.NET Framework：** 4.7.1 或更高版本（Windows 10/11通常已预装）
- **显卡：** AMD Vega 10系列（Vega 56、Vega 64等）

### 使用方法

1. **下载：**
   - 前往 [Releases](https://github.com/303287771/Vega10BiosEditor/releases) 或从 `VegaBiosEditor/bin/Debug/` 文件夹下载
   - 下载 `VegaBiosEditor.exe` 和 `VegaBiosEditor.exe.config`

2. **运行：** 双击 `VegaBiosEditor.exe` 启动

3. **修改BIOS：**
   - 点击"OPEN"打开BIOS文件（.rom）
   - 修改参数（功耗控制限制、GPU/显存频率等）
   - 点击"SAVE"保存修改后的BIOS文件

4. **导出注册表（无需刷BIOS）：**
   - 修改参数后，点击"导出注册表"按钮
   - 保存为.reg文件
   - 双击导入 - 无需刷BIOS！
   - 重启电脑或重载AMD驱动即可生效

### 语言切换

点击右上角语言选择框切换中英文。

**注意：** 使用需谨慎，出现问题本人不承担责任。