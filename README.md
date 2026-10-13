**English** | [日本語](README.ja.md)

# scatGUI — ion implantation & channeling simulation software

Research Center of Ion Beam Technology, Hosei University

Author: Tomoaki Nishimura, t-nishi (a) hosei.ac.jp

## Download

Download the packages from [Releases](https://github.com/hosei-ionbeam/scatGUI-releases/releases). The latest version is **v1.42 (2023-06-23)**.

This repository hosts the distribution packages and their notes only. It contains no source code.

## Verifying the files

You can confirm that a downloaded file has not been altered by comparing its SHA-256 with the table below.

```powershell
Get-FileHash .\scatGUI-v1.42-2023-06-23.zip -Algorithm SHA256
```

| Version | File | SHA-256 |
|---|---|---|
| 1.42 | `scatGUI-v1.42-2023-06-23.zip` | `aa239cb76142d6a9ce34ba65a96911e6784fb81daace0b442d8103891628f689` |
| 1.40 | `scatGUI-v1.40-2022-10-07.zip` | `0d16d3f5c321714fef71fd4dbf421bc280be11023c29c37fbe20e236bd60433e` |
| 1.40 (detail) | `scatGUI-v1.40-detail-4HSiC-EN.pdf` | `62cf74476617222e3ca7e1b8d61b3de5da1ac1430e0f2ee1e98a43fb7486d7c7` |
| 1.40 (detail) | `scatGUI-v1.40-detail-ManyBody-EN.pdf` | `0cda871b0d9277fa484a50ed165b9d3c8099092c8e0244031cd75b42eb19cf7a` |
| 1.40 (detail) | `scatGUI-v1.40-detail-4HSiC-JP.pdf` | `12b2a7919144f4b251726b1b45227c8de9d18aa73c79de792d1b91977abc76b0` |
| 1.40 (detail) | `scatGUI-v1.40-detail-ManyBody-JP.pdf` | `72adca4d44e1164f83ea8ddfb4e6a90118dafc76e986c77052da1908d1fa3513` |
| 1.38 | `scatGUI-v1.38-2022-01-21.zip` | `5d73033ba9b37866d17ee3960f7478443ebe79b9d04d865a75363f433344b004` |
| 1.37 | `scatGUI-v1.37-2021-07-09.exe` | `04f5729e1cd3562dccf26e739009f5736a683293687d9b1311716668fe085105` |
| 1.33 | `scatGUI-v1.33-2021-05-10.zip` | `431b6267a15b7aa41bc6ff30f854d71031107fab16ca5af2d489e9bb118bb6d8` |
| 1.31 | `scatGUI-v1.31-2021-04-22.zip` | `c604af43e2ab05acd005931872427a2a2063501371d8d8c390606eb67ceaa6c5` |
| 1.30 | `scatGUI-v1.30-2021-04-21.zip` | `ddcd8e32a3f85699a6f3bd9df0b4439604ba9e8429553b7386f39501aff575d2` |
| 1.27 | `scatGUI-v1.27-2021-04-07.zip` | `291085b79ecb973f5603254a17df5ac5d09e15ede1d18f3e1684254fc64fbfa8` |
| 1.26 | `scatGUI-v1.26-2021-03-18.zip` | `413f7a3a129062de2ad4ebcd8768e389895d1be2c7a2fb78a27b4d10997d8d07` |
| 1.24 | `scatGUI-v1.24-2021-03-16.zip` | `9bcdc57d8f1485802d55d41cc36276af6af8db109508f07c6109e8b77864d47e` |

## Version history

Dates are those listed on the old website. For the changes in each version, see its release notes.

| Version | Date |
|---|---|
| [1.42](https://github.com/hosei-ionbeam/scatGUI-releases/releases/tag/v1.42) | 2023-06-23 |
| [1.40](https://github.com/hosei-ionbeam/scatGUI-releases/releases/tag/v1.40) | 2022-10-07 |
| [1.38](https://github.com/hosei-ionbeam/scatGUI-releases/releases/tag/v1.38) | 2022-01-18 |
| [1.37](https://github.com/hosei-ionbeam/scatGUI-releases/releases/tag/v1.37) | 2021-07-09 |
| [1.33](https://github.com/hosei-ionbeam/scatGUI-releases/releases/tag/v1.33) | 2021-05-10 |
| [1.31](https://github.com/hosei-ionbeam/scatGUI-releases/releases/tag/v1.31) | 2021-04-22 |
| [1.30](https://github.com/hosei-ionbeam/scatGUI-releases/releases/tag/v1.30) | 2021-04-21 |
| [1.27](https://github.com/hosei-ionbeam/scatGUI-releases/releases/tag/v1.27) | 2021-04-07 |
| [1.26](https://github.com/hosei-ionbeam/scatGUI-releases/releases/tag/v1.26) | 2021-03-19 |
| [1.24](https://github.com/hosei-ionbeam/scatGUI-releases/releases/tag/v1.24) | 2021-03-16 |

## About the move

These versions were originally distributed on the Research Center's website between 2021 and 2023. In October 2026 the distribution was moved to this GitHub repository. The files are unchanged (verified byte-identical to the original builds).

## References

1. Tomoaki Nishimura and Tetsu Kachi, "Simulation of channeled implantation of magnesium ions in gallium nitride", Applied Physics Express 14, 116502 (2021). https://doi.org/10.35848/1882-0786/ac2a55
2. Tomoaki Nishimura, Kiyoji Ikeda, and Tetsu Kachi, "Channeled implantation of magnesium ions in gallium nitride for deep and low-damage doping", Applied Physics Express 14, 066503 (2021). https://doi.org/10.35848/1882-0786/ac039e
3. Tomoaki Nishimura and Kazuhiro Mochizuki, "Electronic-stopping and damage parameters for random and channeled implantation of B, N, O, and Si into GaN(0001)", Japanese Journal of Applied Physics 65, 170901 (2026). https://doi.org/10.35848/1347-4065/ae9c12
4. T. Nishimura, M. Satoh, K. Nomoto, T. Nakamura, T. Mishima, "Site identification of GaN using preferential scattering effect along [1-100] axis", Nuclear Instruments and Methods in Physics Research B 268 (2010) 1942–1944.
