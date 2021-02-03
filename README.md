# APX Autopilot Firmware releases

This repository contains binary packages of **[APX Autopilot Firmware](https://github.com/uavos/apx-fw)** (`APXFW`), created by [UAVOS Company](http://uavos.com). See https://docs.uavos.com for more details.

The `APXFW` is tightly coupled with [APX Ground Control](https://github.com/uavos/apx-gcs) (`GCS`) project (which is open-source), through the [`apx-lib`](https://github.com/uavos/apx-lib) shared library. The `GCS` will automatically manage firmware updates and you don't have to download anything directly from this repository releases.

## Issues reporting

All `issues`, `bugs` and `feature requests` related to the **APX Autopilot**, i.e. `APXFW`, should be reported in this repository ([`apx-ap`](https://github.com/uavos/apx-ap/issues)).

Issues, related to the UI of the `GCS`, and its features, should be reported here: [apx-gcs](https://github.com/uavos/apx-gcs/issues).

## Firmware versioning

The firmware version of `X.Y.zzz` is compatible with the `GCS` version of `X.Y.zzz`, where `zzz` is any number. The `GCS` will automatically suggest firmware updates, when available, based on this principle.

## Contents

This repository provides [release packages](https://github.com/uavos/apx-ap/releases) with a `zip` archive of firmware files (`.apxfw`). The `.apxfw` file is a `JSON` encoded data with information about node hardware and firmware binary data. The `GCS` is capable to download, read and upload firmware data from such files to the APX Autopilot hardware nodes.

## Links

 * [Changelog](https://uavos.github.io/apx-ap/CHANGELOG.html) - Autopilot changelog gh pages view;
 * [uavos/apx-fw](https://github.com/uavos/apx-fw) - the `private` repository with the source code of the firmware packages published here;
 * [UAVOS Inc. company web site](http://uavos.com) with products and more;
 * [APX Autopilot documentation](http://docs.uavos.com)
 * [UAVOS Inc. GitHub Organization](https://github.com/uavos)

#   

>&copy; [Aliaksei Stratsilatau](https://github.com/uavinda)
