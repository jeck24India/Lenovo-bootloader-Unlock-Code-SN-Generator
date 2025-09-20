# Lenovo Bootloader SN Generator

A **secure, local SN.img generator** for Lenovo new-generation devices. This tool helps generate the bootloader unlock file directly in your browser without sending any data to external servers.

---

## 🚀 Features

- **Local Processing**: All computations happen in the browser; no external server involved.  
- **Hex View**: Visualize the generated SN.img content in a clean, readable hex format.  
- **Frosted Glass UI**: Modern, responsive, mobile-friendly interface.  
- **Input Validation**: Ensures proper 64-character bootloader SN.  
- **One-Click Download**: Generates and downloads the `sn.img` file instantly.  

---

## 📦 How to Use

1. **Retrieve your bootloader SN**:

```bash
fastboot getvar all
# Or
adb shell getprop ro.boot.bootload_sn
