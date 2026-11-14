# Snapmaker U1 calibration firmware — 2.0

**Maintainer: cheeky-bastard | Restored: 2026-11-14**

Personal Paxx-based firmware with independent T1/T2/T3 calibration and a guarded mixed-nozzle print-start workaround. T0 directs the operator to stock full calibration; clean/validate saves nothing.

Read the [usermod instructions](overlays/mods/cheeky_b52/README.md), [full calibration documentation](https://github.com/cheeky-bastard/Snapmaker-U1-Single-Tool-Calibration), and [Releases](https://github.com/cheeky-bastard/SnapmakerU1-Extended-Firmware/releases).

These are web UI macro buttons. In Mainsail, put the seven primary buttons in a **Tool Calibration** macro group and enable Standby visibility.

Pinned upstream: `2c80e3dc495fdf724bc53c5c35c875010ee1668f`. Reviewed native/CFG payload hashes are unchanged. Restored CI builds are pending; new images require their own printer acceptance. Obtain verified configuration/native backups before persistent printer changes. Use normal operation without debug or factory mode.

## Attribution

Built from [Paxx's Extended Firmware](https://github.com/paxx12-snapmaker-u1/SnapmakerU1-Extended-Firmware). Upstream source history and notices are preserved. See [upstream README](README.upstream.md), [GPL-3.0](LICENSE), and [modification notice](overlays/mods/cheeky_b52/NOTICE.md).

Restored under `cheeky-bastard` on 2026-11-14. Historical source banners, copyright notices and exact native/CFG payload hashes are retained. Old account URLs in source comments and historical records identify provenance; current project links use the new account. The stable `cheeky_b52` mod namespace is retained for compatibility. No upstream PR is authorized.
