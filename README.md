ismpc_walking-controller-superbuild
==

This repository is an extension repository for [mc-rtc-superbuild](https://github.com/mc-rtc/mc-rtc-superbuild)

It builds:

- Choreonoid fully equipped with HRP robots
- All dependencies of ismpc_walking
- ismpc_walking controller

Usage
--

```bash
git clone https://github.com/mc-rtc/mc-rtc-superbuild
cd mc-rtc-superbuild
git clone git@github.com:isri-aist/ispmc-walking-superbuild extensions/ismpc-walking-superbuild
cmake --preset relwithdebinfo
cmake --build --preset relwithdebinfo
```

Options
--

The following options are provided by this extension:

- `INTERNAL_MACHINE` (default: `OFF`)
