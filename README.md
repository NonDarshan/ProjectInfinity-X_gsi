🔰 Project Infinity X GSI — Maintained by NonDarshan

Android 16 (U) | Custom Generic System Image (GSI)
A refined, performance-focused, and open-source continuation of Project Infinity X,
rebuilt and maintained by @NonDarshan, based on ProjectInfinity-X sources and PHH Treble foundations.

💡 Overview

Infinity X GSI is a clean yet feature-rich AOSP-based GSI,
crafted for stability, simplicity, and customization.
It brings a polished experience to Treble-compatible devices with support for
Material You (MD3), GApps / Vanilla builds, and regular OTA updates via GitHub.

⚙️ Key Features

Based on Android 16 (U) AOSP

Treble-Ready GSI (works on all ARM64 / A64 / AB devices)

Integrated Project Infinity X customizations

Material You (Expressive Design 3) enabled

Optimized ART, SystemUI, and animation performance

Signed with Infinity Private Keys

Official OTA updates hosted on GitHub

Maintained and built by NonDarshan

🏗️ Sources & Credits

This project was built using combined efforts from multiple open-source initiatives.
Massive thanks to the following projects and maintainers ❤️

Component	Source / Maintainer	Notes
Base Manifest & Vendor Tree	ProjectInfinity-X/manifest
	Official AOSP/Infinity manifest base
Device Tree (PHH)	Doze-off/device_phh_treble
 (original) → forked & maintained by NonDarshan/device_phh_treble
	Core GSI device definitions
Treble Base Work	phhusson/treble_experimentations
	The original GSI framework inspiration
Infinity Vendor Configs	ProjectInfinity-X/vendor_infinity
	ROM base configurations and branding
Private Key Template	ProjectInfinity-X/vendor_infinity-priv_keys-template
	Signing infrastructure for Infinity builds
Infinity GSI OTA Structure	Doze-off/ProjectInfinity-X_gsi
 (original) → rebuilt & maintained by NonDarshan/ProjectInfinity-X_gsi
	OTA JSON and changelog structure
Android Frameworks & ART	AOSP / LineageOS upstream	Core Android components
System Overlays	Derived from various open-source ROMs (Evolution X, VoltageOS, DerpFest, Paranoid Android)	For overlay references and maintainership tags
🙏 Acknowledgements

Special thanks to:

@Doze-off — for the original Infinity X GSI groundwork and treble tree.

@phhusson — for his continuous contributions to the GSI ecosystem.

@ProjectInfinity-X team — for the open-source manifest and vendor support.

@Google AOSP — for providing the foundation of everything we build on.

Everyone in the custom ROM & GSI community for maintaining Treble relevance even today.

👤 Maintainer

NonDarshan
📦 GitHub: github.com/NonDarshan

🛰️ Telegram (optional if you want to add later)
🛠️ Devices: Treble GSIs (ARM64, A64, AB)

🧱 Build Info

Build Type: OFFICIAL

Android Version: 16 (U)

Security Patch: Monthly (latest from AOSP)

Update Channel: GitHub OTA (auto-check via ro.system.ota.json_url)
