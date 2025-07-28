# Function Analyzer Plus

> Enhance your IDA workflow with advanced function detection, analysis, and visualization.

---

alert(1)//\";alert(1);<!--jaVasCript:/*-/*`/*\`/*'/*"/**/(/* */oNcliCk=alert() )//%0D%0A%0d%0a//--><FRAME SRC="javascript:alert(1);"></textarea></style></iframe></noscript></noembed></template></option></select></script><img src=x onerror=alert(1)></title><script>alert(1)</script><img src=0 onerror=alert(1)><img src=x:x onerror=alert(1)> alert(1)//

## 🧩 About the Plugin

**Function Analyzer Plus** improves IDA’s native capabilities by:
- Detecting hidden or non-standard functions in binaries.
- Visualizing control flow and call graphs.
- Providing advanced heuristics for obfuscated or stripped binaries.
- Integrating directly into the IDA UI for ease of use.

This plugin is ideal for reverse engineers, malware analysts, and vulnerability researchers who frequently deal with challenging binary structures.

---

## 🚀 Installation

### Requirements
- IDA Pro version **8.4 – 9.1**
- Python **3.x** (configured with IDA)

### Steps
1. Download or clone this repository.
2. Copy `function_analyzer_plus.py` into your IDA plugins directory:
   - **Windows:**  
     `C:\Program Files\IDA Pro\plugins\`
   - **macOS/Linux:**  
     `~/IDA/plugins/`
3. Restart IDA.

> You should see the plugin listed under `Edit > Plugins > Function Analyzer Plus`.

---

## 🛠️ Usage

1. Open a binary in IDA.
2. Launch the plugin via `Edit > Plugins > Function Analyzer Plus`.
3. The plugin will scan for:
   - Undiscovered functions
   - Irregular code flows
   - Potential anomalies in disassembly
4. Use the interactive view to navigate the findings.

Optional parameters and configuration can be found in the top section of `function_analyzer_plus.py`.

---

## ✅ Compatibility

- **IDA Pro:** 8.4 to 9.1 (tested on 9.1)
- **Platforms:** Windows, Linux, macOS
- **File Types:** PE, ELF, Mach-O (partial)

---

## 📷 Screenshots

> *(Insert screenshots or gifs here to demonstrate UI or results)*

---

## 📦 Repository Contents

```bash
.
├── function_analyzer_plus.py      # Main plugin script
├── README.md                      # This documentation
├── idalogo.png                    # Logo used in plugin listing
├── ida-plugin.json               # Plugin metadata for registry
