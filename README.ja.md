[English](README.md) | **日本語**

# scatGUI — イオン注入 & チャネリングシミュレーションソフトウェア

法政大学 イオンビーム工学研究所

作成者: 西村智朗 (Tomoaki Nishimura)、t-nishi (a) hosei.ac.jp

## ダウンロード

配布ファイルは [Releases](https://github.com/hosei-ionbeam/scatGUI-releases/releases) から入手してください。最新版は **v1.42 (2023-06-23)** です。

このリポジトリには配布ファイルとその説明だけを置いています。ソースコードは含みません。

## ファイルの照合

ダウンロードしたファイルが改ざんされていないことは、SHA-256 を下の表と比べて確認できます。

```powershell
Get-FileHash .\scatGUI-v1.42-2023-06-23.zip -Algorithm SHA256
```

| 版 | ファイル | SHA-256 |
|---|---|---|
| 1.42 | `scatGUI-v1.42-2023-06-23.zip` | `aa239cb76142d6a9ce34ba65a96911e6784fb81daace0b442d8103891628f689` |
| 1.40 | `scatGUI-v1.40-2022-10-07.zip` | `0d16d3f5c321714fef71fd4dbf421bc280be11023c29c37fbe20e236bd60433e` |
| 1.38 | `scatGUI-v1.38-2022-01-21.zip` | `5d73033ba9b37866d17ee3960f7478443ebe79b9d04d865a75363f433344b004` |
| 1.37 | `scatGUI-v1.37-2021-07-09.exe` | `04f5729e1cd3562dccf26e739009f5736a683293687d9b1311716668fe085105` |
| 1.33 | `scatGUI-v1.33-2021-05-10.zip` | `431b6267a15b7aa41bc6ff30f854d71031107fab16ca5af2d489e9bb118bb6d8` |
| 1.31 | `scatGUI-v1.31-2021-04-22.zip` | `c604af43e2ab05acd005931872427a2a2063501371d8d8c390606eb67ceaa6c5` |
| 1.30 | `scatGUI-v1.30-2021-04-21.zip` | `ddcd8e32a3f85699a6f3bd9df0b4439604ba9e8429553b7386f39501aff575d2` |
| 1.27 | `scatGUI-v1.27-2021-04-07.zip` | `291085b79ecb973f5603254a17df5ac5d09e15ede1d18f3e1684254fc64fbfa8` |
| 1.26 | `scatGUI-v1.26-2021-03-18.zip` | `413f7a3a129062de2ad4ebcd8768e389895d1be2c7a2fb78a27b4d10997d8d07` |
| 1.24 | `scatGUI-v1.24-2021-03-16.zip` | `9bcdc57d8f1485802d55d41cc36276af6af8db109508f07c6109e8b77864d47e` |

## 配布場所の移設について

これらの版は、2021〜2023 年に研究所のウェブサイトで公開してきたものです。2026 年 10 月に配布場所をこの GitHub リポジトリへ移しました。ファイルの中身は変えていません (当時の原本とバイト一致を確認済み)。

## 参考文献

1. Tomoaki Nishimura and Tetsu Kachi, "Simulation of channeled implantation of magnesium ions in gallium nitride", Applied Physics Express 14, 116502 (2021). https://doi.org/10.35848/1882-0786/ac2a55
2. Tomoaki Nishimura, Kiyoji Ikeda, and Tetsu Kachi, "Channeled implantation of magnesium ions in gallium nitride for deep and low-damage doping", Applied Physics Express 14, 066503 (2021). https://doi.org/10.35848/1882-0786/ac039e
3. T. Nishimura, M. Satoh, K. Nomoto, T. Nakamura, T. Mishima, "Site identification of GaN using preferential scattering effect along [1-100] axis", Nuclear Instruments and Methods in Physics Research B 268 (2010) 1942–1944.
