# PCB 3D models

These models are kept with the project so `${KIPRJMOD}` references in
`custom_keyboard.kicad_pcb` do not depend on a particular workstation.

| Project file | Source |
| --- | --- |
| `Cherry_MX.step` | Existing local project asset, formerly referenced as `Cherry MX.STEP` |
| `D_DO-35_SOD27_P7.62mm_Horizontal.step` | [KiCad Packages3D](https://gitlab.com/kicad/libraries/kicad-packages3D/-/raw/master/Diode_THT.3dshapes/D_DO-35_SOD27_P7.62mm_Horizontal.step) |
| `RaspberryPi_Pico.step` | [KiCad Packages3D](https://gitlab.com/kicad/libraries/kicad-packages3D/-/raw/master/Module.3dshapes/RaspberryPi_Pico.step) |
| `Stabilizer-2u.stp` | [Keychron L1 2.25u stabilizer](http://www.keychron.co:34568/keychron-github-assets/Keychron-Keyboards-Hardware-Design/L-Series/L1/Stabilizer-2.25u.stp) |
| `Stabilizer-6.25u.stp` | [Keychron L1 6.25u stabilizer](http://www.keychron.co:34568/keychron-github-assets/Keychron-Keyboards-Hardware-Design/L-Series/L1/Stabilizer-6.25u.stp) |
| `Stabilizer_5u.wrl` | Project-local, footprint-aligned horizontal 5u stabilizer representation |
| `Stabilizer_ISO.wrl` | Project-local, footprint-aligned vertical ISO stabilizer representation |
| `Keycap_1u_Transparent.wrl` | Project-local generic transparent keycap shell |
| `Keycap_ISO_Transparent.wrl` | Project-local transparent ISO Enter shell |

The standard 2.25u stabilizer assembly is also used for the 2u and 2.75u
footprints because they share the same 23.8125 mm stem spacing. ISO Enter uses
a project-local vertical representation aligned directly to its four mounting
holes.

Refer to the upstream projects for their model licensing terms.
