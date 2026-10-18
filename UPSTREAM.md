# Upstream tracking

- **Upstream:** https://codeberg.org/sm61x5-mainline/linux
- **Maintainers:** Barnabás Czémán (barni2000), Kamil Gołda
- **Activity (checked 2026-10-18):** last push 2026-09-05; 2 active committers; default branch `sm61x5/7.2.3`, development branch `barni2000/7.2-develop`
- **Status:** ACTIVE — referenced, patches offered upstream when possible
- **Mirrored branches:** `upstream` = `sm61x5/7.2.3` (build base for v7.2.3)

## Omnipha patches (branch `omnipha`)
- `arm64: dts: qcom: sm6125: enable WCN3990 WiFi via MPSS remoteproc` — WiFi bring-up for xiaomi-laurel (wifi@c800000, MPSS remoteproc, smp2p-mpss, rmtfs-mem, pd-mapper domain). Partly ported from github.com/criollojoel10/pmos-laurel-sprout (6.1 kernel) to 7.2.3; regulator and rmtfs details adapted. First booted and verified 2026-10-18 on a Xiaomi Mi A3 (wlan0 associates after reboot, no manual steps).
