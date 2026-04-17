<div align="center">

```
███╗   ███╗ █████╗ ████████╗██████╗ ██╗██╗  ██╗
████╗ ████║██╔══██╗╚══██╔══╝██╔══██╗██║╚██╗██╔╝
██╔████╔██║███████║   ██║   ██████╔╝██║ ╚███╔╝ 
██║╚██╔╝██║██╔══██║   ██║   ██╔══██╗██║ ██╔██╗ 
██║ ╚═╝ ██║██║  ██║   ██║   ██║  ██║██║██╔╝ ██╗
╚═╝     ╚═╝╚═╝  ╚═╝   ╚═╝   ╚═╝  ╚═╝╚═╝╚═╝  ╚═╝
         R E C O V E R Y
```

**A custom Android recovery — rebuilt from the ground up.**

[![Android](https://img.shields.io/badge/Android-12.1%20%7C%2014.1-3DDC84?style=flat-square&logo=android&logoColor=white)](https://github.com/Matrix-Recovery)
[![Based on OrangeFox](https://img.shields.io/badge/Based%20on-OrangeFox%20R11.3-FF7043?style=flat-square)](https://orangefox.download)
[![Version](https://img.shields.io/badge/Matrix-R1.0-blueviolet?style=flat-square)](https://github.com/Matrix-Recovery)
[![Status](https://img.shields.io/badge/Status-Active%20Development-brightgreen?style=flat-square)](https://github.com/Matrix-Recovery)

</div>

---

## What is Matrix Recovery?

Matrix Recovery is a TWRP-based custom Android recovery forked from OrangeFox, built with clean branding, maintainability, and full upstream compatibility.

Think of it as OrangeFox — but ours.

> Flashing. Restoring. Staying in control.

---

## Repositories

| | Repo | Description |
|---|---|---|
| 🔧 | [matrix-sync](https://github.com/Matrix-Recovery/matrix-sync) | Sync tooling — clone this first |
| 💻 | [bootable_recovery](https://github.com/Matrix-Recovery/bootable_recovery) | Recovery source tree |
| 📦 | [vendor_recovery](https://github.com/Matrix-Recovery/vendor_recovery) | Vendor build scripts |

---

## Getting Started

```bash
git clone https://github.com/Matrix-Recovery/matrix-sync sync
cd sync
./matrix_sync.sh --branch 12.1 --path ~/matrix_12.1
```

That's it. The sync script handles the rest.

---

## Supported Targets

| Android version | Branch | Status |
|---|---|---|
| Android 12.1 | `matrix_12.1` | ✅ Stable |
| Android 14.1 | `matrix_14.1` | 🧪 Experimental |

---

<div align="center">

Made with 🖤 by [@minhmc2007](https://github.com/minhmc2007)

*Fork it. Flash it. Own it.*

</div>
