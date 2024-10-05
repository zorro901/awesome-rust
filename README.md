# Awesome Rust [![build badge](https://github.com/rust-unofficial/awesome-rust/actions/workflows/rust.yml/badge.svg?branch=main)](https://github.com/rust-unofficial/awesome-rust/actions/workflows/rust.yml) [![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/rust-unofficial/awesome-rust/)

A curated list of Rust code and resources.

If you want to contribute, please read [this](CONTRIBUTING.md).

## Table of contents

<!-- toc -->

- [Applications](#applications)
  * [Audio and Music](#audio-and-music)
  * [Blockchain](#blockchain)
  * [Database](#database)
  * [Emulators](#emulators)
  * [File manager](#file-manager)
  * [Games](#games)
  * [Graphics](#graphics)
  * [Image processing](#image-processing)
  * [Industrial automation](#industrial-automation)
  * [Message Queue](#message-queue)
  * [MLOps](#mlops)
  * [Observability](#observability)
  * [Operating systems](#operating-systems)
  * [Package Managers](#package-managers)
  * [Payments](#payments)
  * [Productivity](#productivity)
  * [Routing protocols](#routing-protocols)
  * [Security tools](#security-tools)
  * [Social networks](#social-networks)
  * [System tools](#system-tools)
  * [Task scheduling](#task-scheduling)
  * [Text editors](#text-editors)
  * [Text processing](#text-processing)
  * [Utilities](#utilities)
  * [Video](#video)
  * [Virtualization](#virtualization)
  * [Web](#web)
  * [Web Servers](#web-servers)
- [Development tools](#development-tools)
  * [Build system](#build-system)
  * [Debugging](#debugging)
  * [Deployment](#deployment)
  * [Embedded](#embedded)
  * [FFI](#ffi)
  * [Formatters](#formatters)
  * [IDEs](#ides)
  * [Profiling](#profiling)
  * [Services](#services)
  * [Static analysis](#static-analysis)
  * [Testing](#testing)
  * [Transpiling](#transpiling)
- [Libraries](#libraries)
  * [Artificial Intelligence](#artificial-intelligence)
    + [Genetic algorithms](#genetic-algorithms)
    + [Machine learning](#machine-learning)
    + [OpenAI](#openai)
  * [Astronomy](#astronomy)
  * [Asynchronous](#asynchronous)
  * [Audio and Music](#audio-and-music-1)
  * [Authentication](#authentication)
  * [Automotive](#automotive)
  * [Bioinformatics](#bioinformatics)
  * [Caching](#caching)
  * [Cloud](#cloud)
  * [Command-line](#command-line)
  * [Compression](#compression)
  * [Computation](#computation)
  * [Concurrency](#concurrency)
  * [Configuration](#configuration)
  * [Cryptography](#cryptography)
  * [Data processing](#data-processing)
  * [Data streaming](#data-streaming)
  * [Data structures](#data-structures)
  * [Data visualization](#data-visualization)
  * [Database](#database-1)
  * [Date and time](#date-and-time)
  * [Distributed systems](#distributed-systems)
  * [Domain driven design](#domain-driven-design)
  * [eBPF](#ebpf)
  * [Email](#email)
  * [Encoding](#encoding)
  * [Filesystem](#filesystem)
  * [Finance](#finance)
  * [Functional Programming](#functional-programming)
  * [Game development](#game-development)
  * [Geospatial](#geospatial)
  * [Graph algorithms](#graph-algorithms)
  * [Graphics](#graphics-1)
  * [GUI](#gui)
  * [Image processing](#image-processing-1)
  * [Language specification](#language-specification)
  * [Logging](#logging)
  * [Macro](#macro)
  * [Markup language](#markup-language)
  * [Mobile](#mobile)
  * [Network programming](#network-programming)
  * [Parsing](#parsing)
  * [Peripherals](#peripherals)
  * [Platform specific](#platform-specific)
  * [Scripting](#scripting)
  * [Simulation](#simulation)
  * [Social networks](#social-networks-1)
  * [System](#system)
  * [Task scheduling](#task-scheduling-1)
  * [Template engine](#template-engine)
  * [Text processing](#text-processing-1)
  * [Text search](#text-search)
  * [Unsafe](#unsafe)
  * [Video](#video-1)
  * [Virtualization](#virtualization-1)
  * [Web programming](#web-programming)
- [Registries](#registries)
- [Resources](#resources)
- [License](#license)

<!-- tocstop -->

## Applications

See also [Rust - プロダクション](https://www.rust-lang.org/production) プロダクションでRustを実行している組織。

* [alacritty](https://github.com/alacritty/alacritty) - クロスプラットフォーム、GPU拡張ターミナルエミュレータ<div><sub>Stars: 55.9k / Last Update: 2024-10-02 / Initial Date: 2016-02-18</sub></div>
* [Arti](https://gitlab.torproject.org/tpo/core/arti) - Torの実装。(今のところ、あまり完全でないクライアントです。 しかし、このスペースに注目してください！) [![Crates.io]](https://img.shields.io/crates/v/arti.svg)](https://crates.io/crates/arti)
* [asm-cli-rust](https://github.com/cch123/asm-cli-rust) - 対話型のアセンブリシェル。<div><sub>Stars: 315 / Last Update: 2024-08-19 / Initial Date: 2019-01-17</sub></div>
* [cloudflare/boringtun](https://github.com/cloudflare/boringtun) - ユーザー空間WireGuard VPNの実装 [![ビルドバッジ]](https://img.shields.io/badge/crates.io-v0.2.0-orange.svg)](https://crates.io/crates/boringtun)<div><sub>Stars: 6.0k / Last Update: 2024-09-22 / Initial Date: 2018-10-12</sub></div>
* [defguard](https://github.com/defguard/defguard) - エンタープライズ・オープンソースSSOとWireGuard VPN、本物の2FA/MFA付き<div><sub>Stars: 1.1k / Last Update: 2024-10-04 / Initial Date: 2022-10-19</sub></div>
* [denoland/deno](https://github.com/denoland/deno) - V8とTokioで構築されたセキュアなJavaScript/TypeScriptランタイム[[ビルド状況]](https://github.com/denoland/deno/workflows/ci/badge.svg?branch=master&event=push)](https://github.com/denoland/deno/actions)<div><sub>Stars: 94.6k / Last Update: 2024-10-04 / Initial Date: 2018-05-15</sub></div>
* [EasyTier](https://github.com/EasyTier/EasyTier) - WireGuardをサポートしたシンプルでフル機能の分散型メッシュVPN。[![crates.io](https://img.shields.io/crates/v/easytier)](https://crates.io/crates/easytier) [![GitHub actions](https://github.com/EasyTier/EasyTier/actions/workflows/core.yml/badge.svg)](https://github.com/EasyTier/EasyTier/actions/)[![GitHub actions](https://github.com/EasyTier/EasyTier/actions/workflows/gui.yml/badge.svg)](https://github.com/EasyTier/EasyTier/actions/)<div><sub>Stars: 1.4k / Last Update: 2024-10-03 / Initial Date: 2023-09-29</sub></div>
* [fend](https://github.com/printfn/fend) - 任意精度単位認識電卓 [![build](https://github.com/printfn/fend/workflows/build/badge.svg)](https://github.com/printfn/fend)<div><sub>Stars: 646 / Last Update: 2024-10-03 / Initial Date: 2020-07-31</sub></div>
* [fend](https://github.com/printfn/fend) - 任意精度単位認識電卓 [![build](https://github.com/printfn/fend/workflows/build/badge.svg)](https://github.com/printfn/fend)<div><sub>Stars: 646 / Last Update: 2024-10-03 / Initial Date: 2020-07-31</sub></div>
* [Fractalide](https://github.com/fractalide/fractalide) - シンプルなマイクロサービス<div><sub>Stars: 868 / Last Update: 2024-07-09 / Initial Date: 2015-12-06</sub></div>
* [habitat](https://github.com/habitat-sh/habitat) - アプリケーションの構築、デプロイ、管理のためにChefによって作られたツール。<div><sub>Stars: 2.6k / Last Update: 2024-10-04 / Initial Date: 2015-05-22</sub></div>
* [hickory-dns](https://crates.io/crates/trust-dns) - DNSサーバー [![ビルド状況](https://github.com/hickory-dns/hickory-dns/workflows/test/badge.svg?branch=main)](https://github.com/hickory-dns/hickory-dns/actions?query=workflow%3Atest)
* [innernet](https://github.com/tonarino/innernet) - Wireguardを使用したオーバーレイまたはプライベート・メッシュ・ネットワーク<div><sub>Stars: 5.0k / Last Update: 2024-09-13 / Initial Date: 2021-03-29</sub></div>
* [jedisct1/flowgger](https://github.com/awslabs/flowgger) - 高速、シンプル、軽量なデータコレクタ<div><sub>Stars: 826 / Last Update: 2024-05-23 / Initial Date: 2015-08-09</sub></div>
* [kalker](https://github.com/PaddiM8/kalker) - ユーザー定義の変数、関数、導出、積分、複素数で数学のような構文をサポートする科学計算機。クロスプラットフォーム + WASM サポート [![ビルド状況](https://github.com/PaddiM8/kalker/workflows/Release/badge.svg)](https://github.com/PaddiM8/kalker/actions)<div><sub>Stars: 1.6k / Last Update: 2024-10-03 / Initial Date: 2020-06-04</sub></div>
* [kftray](https://github.com/hcavarsan/kftray) - 複数のkubectlポートフォワード設定を管理・共有するためのクロスプラットフォームのシステムトレイアプリ。[ビルド状況](https://github.com/hcavarsan/kftray/workflows/Release/badge.svg)](https://github.com/hcavarsan/kftray/actions)<div><sub>Stars: 810 / Last Update: 2024-10-04 / Initial Date: 2023-11-26</sub></div>
* [linkerd/linkerd2-proxy](https://github.com/linkerd/linkerd2-proxy) - Kubernetesのための超軽量サービスメッシュ。<div><sub>Stars: 2.0k / Last Update: 2024-10-04 / Initial Date: 2018-07-07</sub></div>
* [MaidSafe](https://github.com/maidsafe) - 分散型プラットフォーム。
* [mdBook](https://github.com/rust-lang/mdBook) - マークダウンファイルからブックを作成するコマンドラインユーティリティ [![ビルド状況]](https://github.com/rust-lang/mdBook/workflows/CI/badge.svg?branch=master)](https://github.com/rust-lang/mdBook/actions)<div><sub>Stars: 17.9k / Last Update: 2024-09-25 / Initial Date: 2015-07-07</sub></div>
* [mirrord](https://github.com/metalbear-co/mirrord) - ローカルプロセスとクラウド環境を接続し、クラウド環境でローカルコードを実行する。<div><sub>Stars: 3.8k / Last Update: 2024-10-04 / Initial Date: 2022-02-01</sub></div>
* [Pijul](https://pijul.org) - パッチベースの分散バージョン管理システム
* [Rauthy](https://github.com/sebadob/rauthy) - OpenID Connect シングルサインオン ID & アクセス管理<div><sub>Stars: 312 / Last Update: 2024-10-04 / Initial Date: 2023-07-01</sub></div>
* [shoes](https://github.com/cfal/shoes) - マルチプロトコル・プロキシサーバー<div><sub>Stars: 215 / Last Update: 2024-09-20 / Initial Date: 2022-01-29</sub></div>
* [shuttle](https://github.com/shuttle-hq/shuttle) - サーバーレス・プラットフォーム。<div><sub>Stars: 6.0k / Last Update: 2024-10-03 / Initial Date: 2022-02-19</sub></div>
* [Sniffnet](https://github.com/GyulyVGC/sniffnet) - ネットワークトラフィックを簡単に監視するクロスプラットフォームアプリケーション [![ビルドバッジ](https://img.shields.io/github/actions/workflow/status/gyulyvgc/sniffnet/rust.yml?logo=github)](https://github.com/GyulyVGC/sniffnet/blob/main/.github/workflows/rust.yml) [![クレート](https://img.shields.io/crates/v/sniffnet?logo=rust)](https://crates.io/crates/sniffnet)<div><sub>Stars: 17.9k / Last Update: 2024-09-30 / Initial Date: 2022-07-31</sub></div>
* [SWC](https://github.com/swc-project/swc) - 超高速TypeScript / JavaScriptコンパイラ<div><sub>Stars: 31.0k / Last Update: 2024-10-04 / Initial Date: 2017-12-22</sub></div>
* [tiny](https://github.com/osa1/tiny) - 端末用IRCクライアント<div><sub>Stars: 1.0k / Last Update: 2024-09-23 / Initial Date: 2016-01-06</sub></div>
* [UpVPN](https://github.com/upvpn/upvpn-app) - Tauriをベースに構築されたmacOS、Linux、Windows用のWireGuard VPNクライアント。<div><sub>Stars: 205 / Last Update: 2024-09-20 / Initial Date: 2023-06-14</sub></div>
* [wasmer](https://github.com/wasmerio/wasmer) - WASI と Emscripten をサポートする安全で高速な WebAssembly ランタイム [![ビルド状況](https://github.com/wasmerio/wasmer/workflows/build/badge.svg?style=flat-square)](https://github.com/wasmerio/wasmer/actions)<div><sub>Stars: 18.5k / Last Update: 2024-10-04 / Initial Date: 2018-10-11</sub></div>
* [Weld](https://github.com/serayuzgur/weld) - 完全な偽REST APIジェネレーター<div><sub>Stars: 304 / Last Update: 2023-12-07 / Initial Date: 2017-03-31</sub></div>
* [wezterm](https://github.com/wez/wezterm) - GPUアクセラレーションによるクロスプラットフォーム端末エミュレータとマルチプレクサ<div><sub>Stars: 17.0k / Last Update: 2024-10-01 / Initial Date: 2018-02-07</sub></div>
* [WinterJS](https://github.com/wasmerio/winterjs) - SpiderMonkeyとAxumで構築されたセキュアなJavaScriptランタイム<div><sub>Stars: 3.0k / Last Update: 2024-09-25 / Initial Date: 2023-09-21</sub></div>
* [zellij](https://github.com/zellij-org/zellij) - ターミナル・マルチプレクサ（ワークスペース）、電池付属<div><sub>Stars: 21.0k / Last Update: 2024-10-04 / Initial Date: 2020-09-01</sub></div>

### Audio and Music

* [dano](https://github.com/kimono-koans/dano) - メディアファイル用のhashdeep/md5tree(それ以上)<div><sub>Stars: 140 / Last Update: 2024-04-16 / Initial Date: 2022-08-16</sub></div>
* [Festival](https://github.com/hinto-janai/festival) - ローカルな音楽プレーヤー／サーバー／クライアント [![build-badge](https://github.com/hinto-janai/festival/actions/workflows/ci.yml/badge.svg)](https://github.com/hinto-janai/festival/actions/workflows/ci.yml)<div><sub>Stars: 272 / Last Update: 2024-03-27 / Initial Date: 2023-03-23</sub></div>
* [figsoda/mmtc](https://github.com/figsoda/mmtc) [[mmtc](https://crates.io/crates/mmtc)] - シンプルでありながら高度に設定可能であることを目指した、最小限の mpd 端末クライアント [![build-badge]](https://github.com/figsoda/mmtc/actions/workflows/ci.yml/badge.svg)](https://github.com/figsoda/mmtc/actions/workflows/ci.yml)<div><sub>Stars: 94 / Last Update: 2024-05-15 / Initial Date: 2020-10-21</sub></div>
* [Glicol](https://github.com/chaosprint/glicol) - グラフ指向のライブコーディング言語。<div><sub>Stars: 2.2k / Last Update: 2024-07-15 / Initial Date: 2020-07-13</sub></div>
* [ncspot](https://github.com/hrkfdn/ncspot) - ncmpcなどにインスパイアされた、クロスプラットフォームのncurses Spotifyクライアント。[ビルドバッジ](https://github.com/hrkfdn/ncspot/workflows/Build/badge.svg)](https://github.com/hrkfdn/ncspot/actions?query=workflow%3ABuild)<div><sub>Stars: 5.0k / Last Update: 2024-09-30 / Initial Date: 2018-11-10</sub></div>
* [Pinepods](https://github.com/madeofpendletonwool/PinePods) - マルチユーザーをサポートするサビベースのポッドキャスト管理システムです。Pinepodsは中央のデータベースを利用するので、リスニングタイムやテーマなどの側面がデバイス間でフォローされます。Tauriを使用して構築されたクライアントにより、完全なクロスプラットフォームのリスニングソリューションです！Dockerコンテナビルド](https://github.com/madeofpendletonwool/PinePods/actions/workflows/docker-publish.yml/badge.svg)<div><sub>Stars: 191 / Last Update: 2024-10-02 / Initial Date: 2022-09-03</sub></div>
* [Polaris](https://github.com/agersant/polaris) - 音楽ストリーミングアプリケーション。<div><sub>Stars: 1.4k / Last Update: 2024-10-05 / Initial Date: 2016-08-14</sub></div>
* [Spotify Player](https://github.com/aome510/spotify-player) - 端末にSpotifyプレーヤーを搭載し、フル機能のパリティを実現。<div><sub>Stars: 3.5k / Last Update: 2024-09-26 / Initial Date: 2021-07-08</sub></div>
* [Spotifyd](https://github.com/Spotifyd/spotifyd) - UNIXデーモンとして動作するオープンソースのSpotifyクライアント。継続的インテグレーション](https://github.com/Spotifyd/spotifyd/workflows/Continuous%20Integration/badge.svg?branch=master)<div><sub>Stars: 9.8k / Last Update: 2024-09-05 / Initial Date: 2014-12-10</sub></div>
* [termusic](https://github.com/tramhao/termusic) - 音楽プレーヤー TUI<div><sub>Stars: 1.1k / Last Update: 2024-09-23 / Initial Date: 2021-06-01</sub></div>

### Blockchain

* [beerus](https://github.com/eigerco/beerus) - Beerusは信頼できるStarkNetライトクライアントで、⚡猛烈に速い⚡ [[GitHub Workflow Status]](https://github.com/eigerco/beerus/actions/workflows/test.yml/badge.svg)](https://github.com/eigerco/beerus/actions/workflows/test.yml)<div><sub>Stars: 246 / Last Update: 2024-10-03 / Initial Date: 2022-11-09</sub></div>
* [cairo](https://github.com/starkware-libs/cairo) - Cairoは、一般的な計算のための証明可能なプログラムを作るための最初のチューリング完全言語である。これはまた、STARK証明を使ったZK-Rollupである[StarkNet](https://www.starknet.io)のネイティブ言語でもある ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/starkware-libs/cairo/CI?style=flat-square&logo=github)<div><sub>Stars: 1.6k / Last Update: 2024-10-05 / Initial Date: 2022-05-19</sub></div>
* [cairo-vm](https://github.com/lambdaclass/cairo-vm) - カイロVMの実装 [![サビ]](https://github.com/lambdaclass/cairo-vm/actions/workflows/rust.yml/badge.svg)](https://github.com/lambdaclass/cairo-vm/actions/workflows/rust.yml)<div><sub>Stars: 514 / Last Update: 2024-10-04 / Initial Date: 2022-04-26</sub></div>
* [ChainX](https://github.com/chainx-org/ChainX) - Polkadotの完全分散型インターチェーン暗号資産管理。<div><sub>Stars: 324 / Last Update: 2024-05-22 / Initial Date: 2018-10-11</sub></div>
* [electrumrs](https://github.com/romanz/electrs) - Electrumサーバーの効率的な再実装。<div><sub>Stars: 1.1k / Last Update: 2024-09-30 / Initial Date: 2018-04-08</sub></div>
* [ethers-rs](https://github.com/gakonst/ethers-rs) - イーサリアムとセロのライブラリとウォレットの完全な実装。ビルド状況](https://github.com/gakonst/ethers-rs/workflows/Tests/badge.svg)<div><sub>Stars: 2.5k / Last Update: 2024-09-23 / Initial Date: 2020-05-24</sub></div>
* [etk](https://github.com/quilt/etk) - etkはEVMバイトコードを書いたり、読んだり、解析したりするためのツールの集まりである。<div><sub>Stars: 356 / Last Update: 2024-06-21 / Initial Date: 2021-02-08</sub></div>
* [Forest](https://github.com/ChainSafe/forest) - ファイルコインの実装 [![ビルド状況](https://img.shields.io/circleci/build/gh/ChainSafe/forest/main?branch=master)](https://app.circleci.com/pipelines/github/ChainSafe/forest?branch=main)<div><sub>Stars: 632 / Last Update: 2024-10-04 / Initial Date: 2019-11-11</sub></div>
* [Foundry](https://github.com/foundry-rs/foundry) - Foundryは、Ethereumアプリケーション開発のための、高速でポータブルなモジュール式ツールキットです。ビルド状況](https://img.shields.io/github/workflow/status/foundry-rs/foundry/test?style=flat-square)<div><sub>Stars: 8.2k / Last Update: 2024-10-05 / Initial Date: 2021-09-08</sub></div>
* [Grin](https://github.com/mimblewimble/grin/) - MimbleWimbleプロトコルの進化<div><sub>Stars: 5.0k / Last Update: 2024-09-16 / Initial Date: 2016-10-21</sub></div>
* [Holochain](https://github.com/holochain/holochain) - ブロックチェーンに代わるスケーラブルなP2Pアプリケーション。[クリティカルチェックの失敗を検出する](https://github.com/holochain/holochain/actions/workflows/check_run_detect_release_pr_failure.yml/badge.svg)](https://github.com/holochain/holochain/actions/workflows/check_run_detect_release_pr_failure.yml)<div><sub>Stars: 1.2k / Last Update: 2024-10-04 / Initial Date: 2020-01-13</sub></div>
* [Hyperlane](https://github.com/hyperlane-xyz/hyperlane-monorepo) - パーミッションレスでモジュール化された相互運用性のためのフレームワーク。オフチェーン・クライアントはRustで書かれており、Solana VMとCosmWasmのスマート・コントラクトもRustで書かれている。<div><sub>Stars: 311 / Last Update: 2024-10-04 / Initial Date: 2021-12-13</sub></div>
* [ibc-rs](https://github.com/informalsystems/hermes) - ブロックチェーン間通信](https://ibc.cosmos.network/)プロトコルの実装<div><sub>Stars: 441 / Last Update: 2024-10-04 / Initial Date: 2020-02-24</sub></div>
* [interBTC](https://github.com/interlay/interbtc) - PolkadotとKusamaへの信頼できる完全分散型ビットコインブリッジ。<div><sub>Stars: 247 / Last Update: 2024-09-04 / Initial Date: 2020-03-31</sub></div>
* [Joystream](https://github.com/Joystream/joystream) - ユーザー主導のビデオ・プラットフォーム<div><sub>Stars: 1.4k / Last Update: 2024-09-18 / Initial Date: 2019-03-08</sub></div>
* [Lighthouse](https://github.com/sigp/lighthouse) - イーサリアムコンセンサスレイヤー(CL)クライアント [![ビルドステータス](https://github.com/sigp/lighthouse/workflows/test-suite/badge.svg?branch=master)](https://github.com/sigp/lighthouse/actions)<div><sub>Stars: 2.9k / Last Update: 2024-10-04 / Initial Date: 2018-07-06</sub></div>
* [madara](https://github.com/keep-starknet-strange/madara) - Kaioshinは⚡非常に速い⚡Starknetシーケンサーです。[[GitHubワークフロー状況](https://github.com/keep-starknet-strange/madara/actions/workflows/test.yml/badge.svg)](https://github.com/keep-starknet-strange/madara/actions/workflows/test.yml)<div><sub>Stars: 531 / Last Update: 2024-08-02 / Initial Date: 2023-02-10</sub></div>
* [near/nearcore](https://github.com/near/nearcore) - ローエンド・モバイル端末向けの分散型スマート・コントラクト・プラットフォーム。<div><sub>Stars: 2.3k / Last Update: 2024-10-04 / Initial Date: 2018-10-02</sub></div>
* [Nervos CKB](https://github.com/nervosnetwork/ckb) - Nervos CKBはパブリックなパーミッションレス・ブロックチェーンであり、Nervosネットワークの共通知識層である。<div><sub>Stars: 1.2k / Last Update: 2024-10-01 / Initial Date: 2018-11-19</sub></div>
* [Phala-Network/phala-blockchain](https://github.com/Phala-Network/phala-blockchain) - Intel SGXとSubstrateをベースとした機密スマートコントラクト・ブロックチェーン<div><sub>Stars: 332 / Last Update: 2024-09-09 / Initial Date: 2020-01-08</sub></div>
* [polkadot-sdk](https://github.com/paritytech/polkadot-sdk) - パリティ・ポルカドット・ブロックチェーンSDK<div><sub>Stars: 1.8k / Last Update: 2024-10-05 / Initial Date: 2023-08-04</sub></div>
* [revm](https://github.com/bluealloy/revm) - Revolutionary Machine（revm）は、高速なイーサリアム仮想マシンです。<div><sub>Stars: 1.6k / Last Update: 2024-10-04 / Initial Date: 2021-09-29</sub></div>
* [rust-bitcoin](https://github.com/rust-bitcoin/rust-bitcoin) - ビットコインに関連するデータ構造およびネットワークメッセージのデシリアライズ、パース、実行をサポートするライブラリ。<div><sub>Stars: 2.1k / Last Update: 2024-10-03 / Initial Date: 2014-07-18</sub></div>
* [rust-lightning](https://github.com/lightningdevkit/rust-lightning) [![Crate](https://img.shields.io/crates/v/lightning.svg?logo=rust)](https://crates.io/crates/lightning) - Bitcoin Lightning ライブラリ。メインのクレートである`lightning`は、ネットワーク、永続性、その他のI/Oを処理しません。したがって、ランタイムに依存しないが、ユーザーは基本的なネットワーキング・ロジック、チェーン・インタラクション、ディスク・ストレージを実装する必要がある。<div><sub>Stars: 1.1k / Last Update: 2024-10-03 / Initial Date: 2018-02-16</sub></div>
* [sigma-rust](https://github.com/ergoplatform/sigma-rust) - ErgoTreeインタプリタとウォレット関連機能。<div><sub>Stars: 69 / Last Update: 2024-10-04 / Initial Date: 2020-04-02</sub></div>
* [Solana](https://github.com/solana-labs/solana) - Proof-of-Historyを使用した、信じられないほど高速でスケーラビリティの高いブロックチェーン。<div><sub>Stars: 13.0k / Last Update: 2024-10-04 / Initial Date: 2018-02-14</sub></div>
* [Subspace](https://github.com/autonomys/subspace) - スケーラビリティ、セキュリティ、分散化を同時に実現することで、ブロックチェーンのトリレンマを完全に解決できる初のレイヤーワン型ブロックチェーン。<div><sub>Stars: 373 / Last Update: 2024-10-04 / Initial Date: 2021-08-22</sub></div>
* [Sui](https://github.com/MystenLabs/sui) - 高スループット、低レイテンシー、Moveプログラミング言語によるアセット指向プログラミングモデルを備えた次世代スマートコントラクトプラットフォーム。<div><sub>Stars: 6.0k / Last Update: 2024-10-05 / Initial Date: 2021-11-09</sub></div>
* [svm-rs](https://github.com/alloy-rs/svm-rs) - Solidity-Compiler Version Manager。<div><sub>Stars: 250 / Last Update: 2024-09-04 / Initial Date: 2021-09-11</sub></div>
* [tendermint-rs](https://github.com/informalsystems/tendermint-rs) - Tendermintブロックチェーンのデータ構造とクライアント<div><sub>Stars: 609 / Last Update: 2024-09-24 / Initial Date: 2019-07-22</sub></div>
* [zcash](https://github.com/zcash/zcash) - Zcashは「Zerocash」プロトコルの実装である。<div><sub>Stars: 4.9k / Last Update: 2024-10-04 / Initial Date: 2014-11-22</sub></div>

### Database

* [Atomic-Server](https://github.com/atomicdata-dev/atomic-server/) [[atomic-server](https://crates.io/crates/atomic_server)] - リアルタイム更新、動的インデックス、CMS目的の使いやすいGUIを備えたNoSQLグラフデータベース。[リリース](https://github.com/atomicdata-dev/atomic-server/actions/workflows/docker.yml/badge.svg)](https://github.com/atomicdata-dev/atomic-server/actions/workflows/docker.yml)<div><sub>Stars: 977 / Last Update: 2024-10-03 / Initial Date: 2020-07-04</sub></div>
* [CozoDB](https://github.com/cozodb/cozo) - Datalogを使用し、グラフデータとアルゴリズムに特化したトランザクショナルリレーショナルデータベース。タイムトラベルが可能で、高速！[GitHubワークフロー状況](https://img.shields.io/github/actions/workflow/status/cozodb/cozo/build.yml?branch=main)](https://github.com/cozodb/cozo/actions/workflows/build.yml)<div><sub>Stars: 3.4k / Last Update: 2024-08-12 / Initial Date: 2022-10-14</sub></div>
* [darkbird](https://github.com/Rustixir/darkbird) [[darkbird](https://crates.io/crates/darkbird)] - erlang mnesiaにインスパイアされた高可用性、リアルタイム、インメモリストレージ<div><sub>Stars: 482 / Last Update: 2024-06-02 / Initial Date: 2022-04-30</sub></div>
* [Databend](https://github.com/databendlabs/databend) - クラウドネイティブアーキテクチャを採用した最新のリアルタイムデータ処理・分析DBMS [[リリース]](https://github.com/databendlabs/databend/actions/workflows/databend-release.yml/badge.svg)](https://github.com/databendlabs/databend/actions/workflows/databend-release.yml)<div><sub>Stars: 7.7k / Last Update: 2024-10-04 / Initial Date: 2020-10-10</sub></div>
* [DB3 Network](https://github.com/dbpunk-labs/db3) - DB3はコミュニティ主導のブロックチェーンLayer2分散型データベースネットワークです！[GitHub Workflow Status (with event)](https://img.shields.io/github/actions/workflow/status/dbpunk-labs/db3/ci.yml?branch=main&style=flat-square)<div><sub>Stars: 358 / Last Update: 2024-07-29 / Initial Date: 2022-03-25</sub></div>
* [erikgrinaker/toydb](https://github.com/erikgrinaker/toydb) - 学習プロジェクトとして書かれた分散型SQLデータベース。<div><sub>Stars: 6.1k / Last Update: 2024-09-28 / Initial Date: 2019-04-28</sub></div>
* [FnckSQL](https://github.com/KipData/FnckSQL) - Rustの関数としてのSQL<div><sub>Stars: 540 / Last Update: 2024-09-29 / Initial Date: 2023-06-05</sub></div>
* [Garage](https://github.com/deuxfleurs-org/garage) [[garage](https://crates.io/crates/garage)] - 小規模から中規模のセルフホスティング向けに設計されたS3互換の分散オブジェクトストレージサービス。[ステータスバッジ](https://woodpecker.deuxfleurs.fr/api/badges/1/status.svg)](https://woodpecker.deuxfleurs.fr/repos/1)<div><sub>Stars: 539 / Last Update: 2024-09-22 / Initial Date: 2021-11-17</sub></div>
* [GreptimeDB](https://github.com/grepTimeTeam/greptimedb/) - PromQL/SQL/Pythonをサポートするオープンソース、クラウドネイティブ、分散型時系列データベース。[[CI]](https://github.com/greptimeTeam/greptimedb/actions/workflows/develop.yml/badge.svg)](https://github.com/greptimeTeam/greptimedb/actions/workflows/develop.yml)<div><sub>Stars: 4.2k / Last Update: 2024-10-04 / Initial Date: 2022-04-11</sub></div>
* [indradb](https://crates.io/crates/indradb) - グラフ・データベース
* [lancedb](https://github.com/lancedb/lancedb) [[vectordb](https://crates.io/crates/vectordb)] - AIアプリケーションのためのサーバーレスで低レイテンシーのベクトルデータベース<div><sub>Stars: 4.3k / Last Update: 2024-10-04 / Initial Date: 2023-02-28</sub></div>
* [Materialize](https://github.com/MaterializeInc/materialize) - Timely DataflowによるストリーミングSQLデータベース :heavy_dollar_sign: [[ビルド状況](https://badge.buildkite.com/97d6604e015bf633d1c2a12d166bb46f3b43a927d3952c999a.svg?branch=main)](https://buildkite.com/materialize/test)<div><sub>Stars: 5.7k / Last Update: 2024-10-05 / Initial Date: 2019-02-22</sub></div>
* [native_db](https://github.com/vincent-herlemont/native_db) [[native_db](https://crates.io/crates/native_db)] - マルチプラットフォームアプリ（サーバ、デスクトップ、モバイル）用のドロップイン組み込みデータベース。ラストタイプを簡単に同期<div><sub>Stars: 431 / Last Update: 2024-10-05 / Initial Date: 2023-05-09</sub></div>
* [Neon](https://github.com/neondatabase/neon) - サーバーレスPostgres。ストレージとコンピ ューターを分離し、オートスケール、ブランチング、ボトムレスストレージを提供します。<div><sub>Stars: 14.6k / Last Update: 2024-10-04 / Initial Date: 2021-03-26</sub></div>
* [ParadeDB](https://github.com/paradedb/paradedb/) - ParadeDBはPostgres上に構築されたElasticsearchの代替であり、リアルタイム検索と分析のために設計されています。<div><sub>Stars: 5.9k / Last Update: 2024-10-05 / Initial Date: 2023-06-30</sub></div>
* [ParityDB](https://github.com/paritytech/parity-db) - 読み取り操作に最適化された、高速で信頼性の高いデータベース<div><sub>Stars: 263 / Last Update: 2024-07-29 / Initial Date: 2020-03-30</sub></div>
* [Qdrant](https://github.com/qdrant/qdrant) - 拡張フィルタリングをサポートしたオープンソースのベクトル類似検索エンジン[[Tests]](https://github.com/qdrant/qdrant/workflows/Tests/badge.svg)](https://github.com/qdrant/qdrant/actions)<div><sub>Stars: 20.0k / Last Update: 2024-10-04 / Initial Date: 2020-05-30</sub></div>
* [Qrlew/qrlew](https://github.com/Qrlew/qrlew) [[qrlew](https://crates.io/crates/qrlew)] - SQLからSQLへの差分プライバシーレイヤー [![Qrlew](https://github.com/Qrlew/qrlew/actions/workflows/ci.yml/badge.svg)](https://github.com/Qrlew/qrlew/actions) ![Crates.ioバージョン](https://img.shields.io/crates/v/qrlew?logo=Rust)<div><sub>Stars: 40 / Last Update: 2024-10-01 / Initial Date: 2023-05-22</sub></div>
* [RisingWaveLabs/RisingWave](https://github.com/RisingWaveLabs/risingwave) - クラウドの次世代ストリーミング・データベース [![CI]](https://github.com/RisingWaveLabs/risingwave/actions/workflows/main.yml/badge.svg)](https://github.com/RisingWaveLabs/risingwave/actions/workflows/main.yml/badge.svg?branch=main)<div><sub>Stars: 6.9k / Last Update: 2024-10-05 / Initial Date: 2022-01-28</sub></div>
* [Skytable](https://github.com/skytable/skytable) - マルチモデルNoSQLデータベース ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/skytable/skytable/Tests?style=flat-square)<div><sub>Stars: 2.4k / Last Update: 2024-09-04 / Initial Date: 2020-06-30</sub></div>
* [sled](https://crates.io/crates/sled) - (ベータ版) モダンな組み込みデータベース [![ビルド状況](https://github.com/spacejam/sled/workflows/Rust/badge.svg?branch=master)](https://github.com/spacejam/sled/actions?workflow=Rust)
* [SQLSync](https://github.com/orbitinghail/sqlsync) - マルチプレイヤー・オフラインファーストSQLite [![GitHub Workflow Status]](https://github.com/orbitinghail/sqlsync/actions/workflows/actions.yaml/badge.svg?branch=main)](https://github.com/orbitinghail/sqlsync/actions?query=branch%3Amain)<div><sub>Stars: 2.3k / Last Update: 2024-03-11 / Initial Date: 2023-05-26</sub></div>
* [SurrealDB](https://github.com/surrealdb/surrealdb) - スケーラブルな分散型文書グラフデータベース [![構築状況]](https://img.shields.io/github/workflow/status/surrealdb/surrealdb/Continuous%20integration/main)](https://github.com/surrealdb/surrealdb/actions)<div><sub>Stars: 27.1k / Last Update: 2024-10-04 / Initial Date: 2021-12-09</sub></div>
* [TerminusDB](https://github.com/terminusdb/terminusdb-store) - オープンソースのグラフデータベースとドキュメントストア [![ビルド状況](https://github.com/terminusdb/terminusdb-store/workflows/Build/badge.svg?branch=master)](https://github.com/terminusdb/terminusdb-store/actions)<div><sub>Stars: 364 / Last Update: 2024-03-11 / Initial Date: 2019-07-23</sub></div>
* [tikv](https://github.com/tikv/tikv) - Rustによる分散KVデータベース [![ビルド状況]](https://ci.pingcap.net/job/tikv_ghpr_test/badge/icon)](https://ci.pingcap.net/job/tikv_ghpr_test/)<div><sub>Stars: 15.1k / Last Update: 2024-09-30 / Initial Date: 2015-12-31</sub></div>
* [Tonbo](https://github.com/tonbo-io/tonbo) - TonboはApache ArrowとParquetで構築された組み込み永続データベースです[![crates.io]](https://img.shields.io/crates/v/tonbo.svg)](https://crates.io/crates/tonbo)<div><sub>Stars: 654 / Last Update: 2024-09-30 / Initial Date: 2024-07-15</sub></div>
* [USearch](https://github.com/unum-cloud/usearch) - ベクトルと文字列の類似検索エンジン [![crates.io](https://img.shields.io/crates/v/usearch.svg)](https://crates.io/crates/usearch)<div><sub>Stars: 2.1k / Last Update: 2024-09-28 / Initial Date: 2023-02-22</sub></div>
* [valentinus](https://github.com/kn0sys/valentinus) - LMDBバインディングで構築された次世代ベクターデータベース [![Crates.io Version]](https://img.shields.io/crates/v/valentinus)](https://crates.io/crates/valentinus)<div><sub>Stars: 6 / Last Update: 2024-10-03 / Initial Date: 2024-07-08</sub></div>
* [vorot93/libmdbx-rs](https://github.com/vorot93/libmdbx-rs) [[mdbx-sys](https://crates.io/crates/mdbx-sys)] - 高速、コンパクト、パワフル、組み込み、トランザクション可能なキーバリューデータベース。これは mozilla/lmdb-rs のフォークで、libmdbx で動作するようにパッチを当てたものです。<div><sub>Stars: 79 / Last Update: 2024-09-25 / Initial Date: 2021-03-20</sub></div>

### Emulators

See also [crates matching keyword 'emulator'](https://crates.io/keywords/emulator).

* CHIP-8
* Commodore 64
* Flash Player
  * [Ruffle](https://github.com/ruffle-rs/ruffle) - RuffleはAdobe Flash Playerのエミュレータです。RuffleはWebAssemblyを使ってデスクトップとウェブの両方をターゲットにしています。[![ci](https://github.com/ruffle-rs/ruffle/actions/workflows/test_rust.yml/badge.svg)](https://github.com/ruffle-rs/ruffle/actions/workflows/test_rust.yml)[![ci](https://github.com/ruffle-rs/ruffle/actions/workflows/test_web.yml/badge.svg)](https://github.com/ruffle-rs/ruffle/actions/workflows/test_web.yml)<div><sub>Stars: 15.5k / Last Update: 2024-10-05 / Initial Date: 2019-04-25</sub></div>
* Gameboy
  * [joamag/boytacean](https://github.com/joamag/boytacean) - WebAssemblyを使ってWeb上で動作するGameBoy Colorエミュレータ。<div><sub>Stars: 619 / Last Update: 2024-09-30 / Initial Date: 2022-11-14</sub></div>
  * [mohanson/gameboy](https://github.com/mohanson/gameboy) - フル機能のクロスプラットフォームGameBoyエミュレータ。フォーエバーボーイズ<div><sub>Stars: 1.4k / Last Update: 2024-09-15 / Initial Date: 2019-04-18</sub></div>
  * [mvdnes/rboy](https://github.com/mvdnes/rboy) - ゲームボーイエミュレーター<div><sub>Stars: 598 / Last Update: 2024-09-29 / Initial Date: 2014-01-24</sub></div>
* Gameboy Advance
  * [michelhe/rustboyadvance-ng](https://github.com/michelhe/rustboyadvance-ng) - RustboyAdvance-ngは、デスクトップ、アンドロイド、[WebAssembly](https://michelhe.github.io/rustboyadvance-ng/)をサポートしたゲームボーイアドバンスエミュレータです。[ビルドバッジ](https://github.com/michelhe/rustboyadvance-ng/workflows/Deploy/badge.svg?branch=master)](https://github.com/michelhe/rustboyadvance-ng/actions?query=workflow%3ADeploy)<div><sub>Stars: 602 / Last Update: 2024-08-12 / Initial Date: 2019-06-21</sub></div>
* GameMaker
  * [OpenGMK](https://github.com/OpenGMK/OpenGMK) - OpenGMK はプロプライエタリな GameMaker Classic エンジンを現代的に書き直したもので、ランナーの完全なソースポート、デコンパイラ、TASing フレームワーク、そしてゲームデータを自分で扱うためのライブラリを提供します。<div><sub>Stars: 274 / Last Update: 2024-05-09 / Initial Date: 2019-02-24</sub></div>
* IBM PC
  * [MartyPC](https://github.com/dbalsom/martypc) - Rustで書かれたIBM PC/XTエミュレータ。<div><sub>Stars: 572 / Last Update: 2024-10-03 / Initial Date: 2022-05-23</sub></div>
* Intel 8080 CPU
  * [mohanson/i8080](https://github.com/mohanson/i8080) - インテル8080CPUエミュレータ<div><sub>Stars: 111 / Last Update: 2024-01-08 / Initial Date: 2019-04-27</sub></div>
* iOS
  * [touchHLE](https://github.com/touchHLE/touchHLE) - iPhone OSアプリ用のハイレベル・エミュレータ<div><sub>Stars: 2.7k / Last Update: 2024-10-04 / Initial Date: 2022-12-01</sub></div>
* iPod
  * [clicky](https://github.com/daniel5151/clicky) - クリックホイールiPodエミュレータ（WIP）<div><sub>Stars: 162 / Last Update: 2024-06-20 / Initial Date: 2019-09-10</sub></div>
* NES
  * [koute/pinky](https://github.com/koute/pinky) - ファミコンエミュレータ<div><sub>Stars: 770 / Last Update: 2023-11-27 / Initial Date: 2016-10-23</sub></div>
* Nintendo 64
  * [gopher64](https://github.com/gopher64/gopher64) - Rustで書かれたN64エミュレータ<div><sub>Stars: 90 / Last Update: 2024-09-02 / Initial Date: 2023-09-27</sub></div>
* Nintendo DS
  * [dust](https://github.com/kelpsyberry/dust) - ニンテンドーDSのエミュレーター<div><sub>Stars: 215 / Last Update: 2024-08-06 / Initial Date: 2023-06-29</sub></div>
* PlayStation 4
  * [Obliteration](https://github.com/obhq/obliteration) - Windows、macOS、Linux用PS4エミュレータの実験的開発[[CI]](https://github.com/obhq/obliteration/actions/workflows/main.yml/badge.svg)](https://github.com/obhq/obliteration/actions/workflows/main.yml)<div><sub>Stars: 622 / Last Update: 2024-10-04 / Initial Date: 2022-09-15</sub></div>
* ZX Spectrum
  * [rustzx/rustzx](https://github.com/rustzx/rustzx) - [RustZX CI](https://github.com/rustzx/rustzx/actions/workflows/ci.yml/badge.svg)](https://github.com/rustzx/rustzx/actions/workflows/ci.yml)<div><sub>Stars: 203 / 最終更新日: 2024-07-26 / 初期日付: 2016-02-02</sub></div><div><sub>Stars: 203 / Last Update: 2024-07-26 / Initial Date: 2016-02-02</sub></div>

### File manager

* [broot](https://github.com/Canop/broot) - ディレクトリツリーを見てナビゲートする新しい方法 (大きなディレクトリでも、ディレクトリの概要を知る; ディレクトリを見つけて、そこに `cd` する; 検索中にファイル階層を見失わない; ファイルを操作する, ...), さらに読む [dystroy.org/broot](https://dystroy.org/broot/) [![最新版](https://img.shields.io/crates/v/broot.svg)](https://crates.io/crates/broot)<div><sub>Stars: 10.6k / Last Update: 2024-09-23 / Initial Date: 2018-11-15</sub></div>
* [joshuto](https://github.com/kamiyaa/joshuto) - レンジャー風端末ファイルマネージャー<div><sub>Stars: 3.4k / Last Update: 2024-09-28 / Initial Date: 2018-07-13</sub></div>
* [xplr](https://github.com/sayanarijit/xplr) - ハック可能、最小、高速なTUIファイルエクスプローラ<div><sub>Stars: 4.2k / Last Update: 2024-09-03 / Initial Date: 2021-02-24</sub></div>
* [yazi](https://github.com/sxyazi/yazi) - 非同期I/Oに基づく、超高速ターミナル・ファイル・マネージャー。<div><sub>Stars: 15.2k / Last Update: 2024-10-04 / Initial Date: 2023-07-08</sub></div>

### Games

See also [Games Made With Piston](https://github.com/PistonDevelopers/piston/wiki/Games-Made-With-Piston).

* [buxx/OpenCombat](https://github.com/buxx/OpenCombat) - 第二次世界大戦のリアルタイム戦術ゲーム<div><sub>Stars: 82 / Last Update: 2024-05-28 / Initial Date: 2017-12-04</sub></div>
* [chess-tui](https://github.com/thomas-mauran/chess-tui) - チェスTUIの実装 ♟️<div><sub>Stars: 363 / Last Update: 2024-10-01 / Initial Date: 2023-11-14</sub></div>
* [doukutsu-rs](https://github.com/doukutsu-rs/doukutsu-rs) - 洞窟物語エンジンの再実装。<div><sub>Stars: 922 / Last Update: 2024-09-22 / Initial Date: 2020-08-18</sub></div>
* [gorilla-devs/ferium](https://github.com/gorilla-devs/ferium) - Ferium は、Modrinth、CurseForge、GitHub リリースから Minecraft Mods をダウンロード・更新し、Modrinth と CurseForge から Modpack をダウンロード・更新するための、高速で機能豊富な CLI プログラムです ![ferium build](https://github.com/gorilla-devs/ferium/actions/workflows/build.yml/badge.svg?branch=main)<div><sub>Stars: 1.1k / Last Update: 2024-10-02 / Initial Date: 2021-09-04</sub></div>
* [HactarCE/Hyperspeedcube](https://github.com/HactarCE/Hyperspeedcube) - カスタマイズ可能なマウスとキーボード操作、スピード解決のための高度な機能を備えた、現代的で初心者向けの3Dおよび4Dルービックキューブ・シミュレーター。<div><sub>Stars: 69 / Last Update: 2024-10-05 / Initial Date: 2020-04-24</sub></div>
* [mcthesw/game-save-manager](https://github.com/mcthesw/game-save-manager) - ゲームのセーブを管理するためのユーザーフレンドリーなツール [![ビルド・バッジ]](https://github.com/mcthesw/game-save-manager/actions/workflows/tauri.yml/badge.svg)](https://github.com/mcthesw/game-save-manager/actions/workflows/tauri.yml)<div><sub>Stars: 576 / Last Update: 2024-09-29 / Initial Date: 2022-01-26</sub></div>
* [mtkennerly/ludusavi](https://github.com/mtkennerly/ludusavi) - PCゲームセーブ用バックアップツール [![ビルドバッジ](https://img.shields.io/github/actions/workflow/status/mtkennerly/ludusavi/main.yaml?logo=github)](https://github.com/mtkennerly/ludusavi/actions/workflows/main.yaml) [![クレート](https://img.shields.io/crates/v/ludusavi?logo=rust)](https://crates.io/crates/ludusavi)<div><sub>Stars: 2.5k / Last Update: 2024-10-03 / Initial Date: 2020-06-20</sub></div>
* [SoftbearStudios/mk48](https://github.com/SoftbearStudios/mk48) - Mk48.ioは多人数参加型のオンライン海戦ゲームです。<div><sub>Stars: 331 / Last Update: 2024-08-01 / Initial Date: 2021-05-08</sub></div>
* [ttyperacer/terminal-typeracer](https://gitlab.com/ttyperacer/terminal-typeracer) - ターミナル用に書かれた一人用のタイピングテストゲーム
* [Veloren](https://gitlab.com/veloren/veloren) - オープンワールド、オープンソースのマルチプレイヤーボクセルRPGゲーム、現在アルファ版開発中[[ビルドバッジ]](https://gitlab.com/veloren/veloren/badges/master/pipeline.svg)](https://gitlab.com/veloren/veloren/-/pipelines)

### Graphics

* [flxzt/rnote](https://github.com/flxzt/rnote) - スケッチをし、手書きのメモを取る。<div><sub>Stars: 8.0k / Last Update: 2024-10-02 / Initial Date: 2021-08-05</sub></div>
* [ivanceras/svgbob](https://github.com/ivanceras/svgbob) - ASCIIダイアグラムをSVGグラフィックスに変換する<div><sub>Stars: 3.8k / Last Update: 2024-03-11 / Initial Date: 2016-10-09</sub></div>
* [KaminariOS/rustracer](https://github.com/KaminariOS/rustracer) - Vulkanレイトレーシングに基づくPBR glTF 2.0レンダラー。<div><sub>Stars: 69 / Last Update: 2023-10-13 / Initial Date: 2023-03-11</sub></div>
* [RazrFalcon/resvg](https://github.com/RazrFalcon/resvg) - SVG レンダリングライブラリ。<div><sub>Stars: 2.7k / Last Update: 2024-09-30 / Initial Date: 2016-10-27</sub></div>
* [rodrigorc/papercraft](https://github.com/rodrigorc/papercraft) - ハサミとのりを使って、3Dモデルを解きほぐし、紙の上に作成するツール。<div><sub>Stars: 127 / Last Update: 2024-10-01 / Initial Date: 2022-05-16</sub></div>
* [rustq/vue-skia](https://github.com/rustq/vue-skia) - Skiaベースの2DグラフィックスVueレンダリングライブラリ。Rustをベースにソフトウェアラスタライズを実装し、レンダリングを行います。<div><sub>Stars: 298 / Last Update: 2024-09-10 / Initial Date: 2022-12-31</sub></div>
* [turnage/valora](https://crates.io/crates/valora) - ジェネレーティブ・ファインアートのためのライブラリ ![Rust](https://github.com/turnage/valora/workflows/Rust/badge.svg?branch=master)
* [wahn/rs_pbrt](https://github.com/wahn/rs_pbrt) - PBRT本（第3版）のC++コードに対応するものを実装。<div><sub>Stars: 810 / Last Update: 2024-01-29 / Initial Date: 2016-12-21</sub></div>

### Image processing

* [shssoichiro/oxipng](https://github.com/shssoichiro/oxipng) [[oxipng](https://crates.io/crates/oxipng)] - Rustで書かれたマルチスレッドPNGオプティマイザ。[ビルド状況](https://github.com/shssoichiro/oxipng/workflows/oxipng/badge.svg)](https://github.com/shssoichiro/oxipng/actions?query=branch%3Amaster) [![バージョン](https://img.shields.io/crates/v/oxipng.svg)](https://crates.io/crates/oxipng)<div><sub>Stars: 2.9k / Last Update: 2024-09-28 / Initial Date: 2016-01-11</sub></div>

### Industrial automation

* [locka99/opcua](https://github.com/locka99/opcua) - OPC UA](https://opcfoundation.org/about/opc-technologies/opc-ua/)ライブラリ。<div><sub>Stars: 501 / Last Update: 2024-09-29 / Initial Date: 2017-01-07</sub></div>
* [slowtec/tokio-modbus](https://github.com/slowtec/tokio-modbus) - tokio](https://tokio.rs)ベースの[modbus](https://modbus.org)ライブラリ。<div><sub>Stars: 405 / Last Update: 2024-09-29 / Initial Date: 2017-10-21</sub></div>

### Message Queue

* [RobustMQ](https://github.com/robustmq/robustmq) - 次世代クラウドネイティブ・コンバージド・メッセージキュー。<div><sub>Stars: 129 / Last Update: 2024-09-30 / Initial Date: 2023-08-03</sub></div>

### MLOps

* [TensorZero](https://github.com/tensorzero/tensorzero) - 推論、観測可能性、最適化、実験を統合するLLMのためのデータと学習のフライホイール ![TensorZero ビルド状況](https://img.shields.io/github/check-runs/tensorzero/tensorzero/main)<div><sub>Stars: 142 / Last Update: 2024-10-04 / Initial Date: 2024-07-16</sub></div>

### Observability

* [MegaAntiCheat/client-backend](https://github.com/MegaAntiCheat/client-backend) - MAC](https://github.com/MegaAntiCheat)のクライアントアプリ。<div><sub>Stars: 120 / Last Update: 2024-09-25 / Initial Date: 2023-07-03</sub></div>
* [openobserve](https://github.com/openobserve/openobserve) - 10倍簡単、140倍低いストレージコスト、高性能、ペタバイトスケール<div><sub>Stars: 12.1k / Last Update: 2024-10-05 / Initial Date: 2023-02-02</sub></div>
* [OpenTelemetry](https://crates.io/crates/opentelemetry) - OpenTelemetryは、アプリケーションから分散トレースとメトリクスをキャプチャするためのAPI、ライブラリ、エージェント、コレクタサービスの単一セットを提供します。Prometheus、Jaeger、その他の観測可能性ツールを使って、それらを分析することができます。[GitHub Actions CI](https://github.com/open-telemetry/opentelemetry-rust/workflows/CI/badge.svg?branch=master)](https://github.com/open-telemetry/opentelemetry-rust/actions?query=workflow%3ACI+branch%3Amaster)
* [Quickwit-oss/quickwit](https://github.com/quickwit-oss/quickwit) - クラウドネイティブでコスト効率の高いログ管理用検索エンジン。![CI](https://github.com/quickwit-oss/quickwit/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/quickwit-oss/quickwit/actions?query=workflow%3ACI)<div><sub>Stars: 8.0k / Last Update: 2024-10-04 / Initial Date: 2021-04-13</sub></div>
* [Scaphandre](https://github.com/hubblo-org/scaphandre) - ホストや各サービスの消費電力を追跡し、より持続可能なシステムやアプリケーションの設計を可能にする消費電力監視エージェントです。どのような監視ツールチェーンにも適合するように設計されています（prometheus、warp10、riemann...をサポート済み）。<div><sub>Stars: 1.6k / Last Update: 2024-07-25 / Initial Date: 2020-10-16</sub></div>
* [vectordotdev/vector](https://github.com/vectordotdev/vector) - 高性能、ログ、メトリクス、イベントルーター。<div><sub>Stars: 17.6k / Last Update: 2024-10-04 / Initial Date: 2018-08-27</sub></div>

### Operating systems


* [Andy-Python-Programmer/aero](https://github.com/Andy-Python-Programmer/aero) - モノリシック・カーネル設計に従った、最新のユニックスライクなオペレーティング・システム。<div><sub>Stars: 1.2k / Last Update: 2024-09-07 / Initial Date: 2021-03-10</sub></div>
* [DragonOS-Community/DragonOS](https://github.com/DragonOS-Community/DragonOS) - ゼロから自社開発したカーネルとLinuxの互換性を持つオペレーティング・システム。<div><sub>Stars: 867 / Last Update: 2024-10-01 / Initial Date: 2022-01-15</sub></div>
* [redox-os/redox](https://gitlab.redox-os.org/redox-os/redox) - セキュリティ、安定性、パフォーマンス、正しさ、シンプルさ、実用性に重点を置いたUnixライクな汎用マイクロカーネルベースのオペレーティングシステムで、LinuxやBSDの完全な代替となることを目指しています。
* [thepowersgang/rust_os](https://github.com/thepowersgang/rust_os) - Rustで書かれたOSカーネル。POSIX非対応<div><sub>Stars: 730 / Last Update: 2024-06-28 / Initial Date: 2014-09-06</sub></div>
* [theseus-os/Theseus](https://github.com/theseus-os/Theseus) - ゼロから書かれた安全言語、単一アドレス空間、単一特権レベルのOS<div><sub>Stars: 2.9k / Last Update: 2024-09-22 / Initial Date: 2017-07-21</sub></div><div><sub>Stars: 2.9k / Last Update: 2024-09-22 / Initial Date: 2017-07-21</sub></div>
* [tock/tock](https://github.com/tock/tock) - Cortex-Mベースのマイクロコントローラ用のセキュアな組み込みオペレーティング・システム<div><sub>Stars: 5.4k / Last Update: 2024-10-04 / Initial Date: 2015-05-28</sub></div>

### Package Managers

* [helsing-ai/buffrs](https://github.com/helsing-ai/buffrs) [[buffrs](https://crates.io/crates/buffrs)] - プロトコルバッファとgRPCアーキテクチャのための最新のパッケージマネージャ。<div><sub>Stars: 208 / Last Update: 2024-09-25 / Initial Date: 2023-06-13</sub></div>
* [rebos](https://crates.io/crates/rebos) - あらゆる Linux ディストリビューションのパッケージ管理を自動化する宣言的な方法 [![crate](https://img.shields.io/crates/v/rebos?logo=rust)](https://crates.io/crates/rebos)

### Payments

* [hyperswitch](https://github.com/juspay/hyperswitch) - オープンソースのペイメントオーケストレーターで、複数のペイメントプロセッサーと接続し、ペイメントトラフィックをルーティングすることができます。<div><sub>Stars: 12.2k / Last Update: 2024-10-04 / Initial Date: 2022-10-17</sub></div>

### Productivity

* [ast-grep](https://github.com/ast-grep/ast-grep) - コード構造検索、lint、書き換えのためのCLIツール。<div><sub>Stars: 7.3k / Last Update: 2024-10-04 / Initial Date: 2022-07-01</sub></div>
* [Bartib](https://github.com/nikolassv/bartib) [[Bartib](https://crates.io/crates/bartib)] - コマンドライン用のシンプルなタイムトラッカー [![Tests]](https://github.com/nikolassv/bartib/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/nikolassv/bartib/actions/workflows/test.yml)<div><sub>Stars: 672 / Last Update: 2024-06-13 / Initial Date: 2021-02-04</sub></div>
* [espanso](https://github.com/espanso/espanso) - クロスプラットフォームのText Expander。![CI](https://github.com/espanso/espanso/actions/workflows/ci.yml/badge.svg?branch=dev&event=push)](https://github.com/espanso/espanso/actions/workflows/ci.yml)<div><sub>Stars: 9.9k / Last Update: 2024-09-29 / Initial Date: 2019-08-30</sub></div>
* [eureka](https://crates.io/crates/eureka) - ターミナルから離れることなくアイデアを入力・保存できるCLIツール
* [Furtherance](https://github.com/unobserved-io/Furtherance) - GTK4で作られたタイムトラッキングアプリ<div><sub>Stars: 264 / Last Update: 2024-10-04 / Initial Date: 2022-02-18</sub></div>
* [illacloud/illa](https://github.com/illacloud/illa) [[ILLA Cloud](https://illacloud.com)] - ローコード内部ツールビルダー。<div><sub>Stars: 239 / Last Update: 2024-04-14 / Initial Date: 2022-05-06</sub></div>
* [LLDAP](https://github.com/lldap/lldap) - 認証用の簡素化されたLDAPインターフェース。<div><sub>Stars: 4.3k / Last Update: 2024-10-02 / Initial Date: 2021-03-02</sub></div>
* [pier-cli/pier](https://github.com/pier-cli/pier) - すべてのワンライナー、スクリプト、ツール、CLIを管理（追加、メタデータ検索など）する中央リポジトリ<div><sub>Stars: 536 / Last Update: 2024-08-07 / Initial Date: 2019-03-05</sub></div>
* [ShadoySV/work-break](https://github.com/ShadoySV/work-break) [[work-break](https://crates.io/crates/work-break)] - 仕事と休養の時間バランスは、あなたの現在と今日の負担を考慮した[[ビルド]](https://github.com/shadoysv/work-break/actions/workflows/release.yml/badge.svg)](https://github.com/ShadoySV/work-break/releases)<div><sub>Stars: 8 / Last Update: 2024-02-03 / Initial Date: 2022-12-17</sub></div>
* [yashs662/rust_kanban](https://github.com/yashs662/rust_kanban) [[rust-kanban](https://crates.io/crates/rust-kanban)] [![Build](https://github.com/yashs662/rust_kanban/actions/workflows/build.yml/badge.svg)](https://github.com/yashs662/rust_kanban/releases) - 端末用かんばんアプリ<div><sub>Stars: 173 / Last Update: 2024-08-12 / Initial Date: 2022-10-07</sub></div>

### Routing protocols

* [Holo](https://github.com/holo-routing/holo) - Holoは、大規模で自動化されたネットワークをサポートするために設計されたルーティング・プロトコル群である。<div><sub>Stars: 261 / Last Update: 2024-10-04 / Initial Date: 2023-04-12</sub></div>
* [RustyBGP](https://github.com/osrg/rustybgp) - BGP<div><sub>Stars: 477 / Last Update: 2024-07-31 / Initial Date: 2019-11-26</sub></div>

### Security tools

* [AFLplusplus/LibAFL](https://github.com/AFLplusplus/LibAFL) - 高度なファジング・ライブラリ<div><sub>Stars: 2.0k / Last Update: 2024-10-04 / Initial Date: 2020-10-22</sub></div>
* [arp-scan-rs](https://github.com/kongbytes/arp-scan-rs) - ローカルネットワークを高速スキャンする最小限のARPスキャンツール<div><sub>Stars: 88 / Last Update: 2024-01-13 / Initial Date: 2021-05-06</sub></div>
* [cargo-audit](https://crates.io/crates/cargo-audit) - Cargo.lockでセキュリティ脆弱性のあるクレートを監査する
* [cargo-auditable](https://crates.io/crates/cargo-auditable) - プロダクションRustバイナリを監査可能にする
* [cargo-crev](https://crates.io/crates/cargo-crev) - カーゴパッケージマネージャ用の暗号検証可能なコードレビューシステム。
* [cargo-deny](https://crates.io/crates/cargo-deny) - 大規模な依存関係グラフの管理を支援するCargoプラグイン
* [Cherrybomb](https://github.com/blst-security/cherrybomb) - 中途半端なAPI仕様は、API仕様を検証することで未定義のユーザー動作を回避するCLIツールで止めましょう。<div><sub>Stars: 1.1k / Last Update: 2024-01-15 / Initial Date: 2021-11-17</sub></div>
* [cotp](https://github.com/replydev/cotp) - インポート機能を備えた、信頼できる暗号化されたコマンドラインのTOTP/HOTP認証アプリ。<div><sub>Stars: 243 / Last Update: 2024-10-02 / Initial Date: 2020-12-20</sub></div>
* [entropic-security/xgadget](https://github.com/entropic-security/xgadget) [[xgadget](https://crates.io/crates/xgadget)] - 高速、並列、異種ROP/JOPガジェット検索 [![GitHub Actions]](https://github.com/entropic-security/xgadget/workflows/test/badge.svg)](https://github.com/entropic-security/xgadget/actions)<div><sub>Stars: 81 / Last Update: 2023-11-24 / Initial Date: 2020-06-21</sub></div>
* [epi052/feroxbuster](https://github.com/epi052/feroxbuster) - シンプルで高速、再帰的なコンテンツ発見ツール。<div><sub>Stars: 5.8k / Last Update: 2024-09-15 / Initial Date: 2020-08-22</sub></div>
* [kpcyrd/rshijack](https://github.com/kpcyrd/rshijack) - TCPコネクションハイジャッカー。<div><sub>Stars: 457 / Last Update: 2024-02-10 / Initial Date: 2018-02-23</sub></div>
* [kpcyrd/sn0int](https://github.com/kpcyrd/sn0int) - 半自動OSINTフレームワークとパッケージマネージャ<div><sub>Stars: 2.0k / Last Update: 2024-09-24 / Initial Date: 2018-10-05</sub></div>
* [kpcyrd/sniffglue](https://github.com/kpcyrd/sniffglue) - 安全なマルチスレッドパケットスニファ<div><sub>Stars: 1.1k / Last Update: 2024-09-08 / Initial Date: 2017-09-12</sub></div>
* [observer_ward](https://github.com/emo-crab/observer_ward) - ウェブアプリケーションとサービスのフィンガープリント識別ツール<div><sub>Stars: 1.2k / Last Update: 2024-10-01 / Initial Date: 2021-08-21</sub></div>
* [Raspirus](https://github.com/Raspirus/Raspirus) - ユーザーとリソースに優しいシグネチャベースのマルウェアスキャナー [![ステータス]](https://github.com/Raspirus/Raspirus/actions/workflows/testproject.yml/badge.svg)](https://github.com/Raspirus/Raspirus/actions/workflows/testproject.yml)<div><sub>Stars: 119 / Last Update: 2024-10-05 / Initial Date: 2022-09-21</sub></div>
* [ripasso](https://github.com/cortex/ripasso/) - パスワードマネージャー、パスとファイルシステム互換<div><sub>Stars: 717 / Last Update: 2024-09-28 / Initial Date: 2017-03-15</sub></div>
* [rustscan/rustscan](https://github.com/RustScan/RustScan) - このポートスキャンツールでNmapを高速化する [![ビルドバッジ]](https://github.com/RustScan/RustScan/workflows/Continuous%20integration/badge.svg?branch=master)](https://github.com/RustScan/RustScan/actions?query=workflow%3A%22Continuous+integration%22)<div><sub>Stars: 14.3k / Last Update: 2024-09-30 / Initial Date: 2020-07-11</sub></div>

### Social networks

* Mastodon
* Telegram
  * [tgt](https://github.com/FedericoBruzzone/tgt) - テレグラム用のクロスプラットフォームTUI [![ci-linux](https://github.com/FedericoBruzzone/tgt/actions/workflows/ci-linux.yml/badge.svg)](https://github.com/FedericoBruzzone/tgt/actions/workflows/ci-linux.yml) [![ci-macos](https://github.com/FedericoBruzzone/tgt/actions/workflows/ci-macos.yml/badge.svg)](https://github.com/FedericoBruzzone/tgt/actions/workflows/ci-macos.yml) [![ci-windows](https://github.com/FedericoBruzzone/tgt/actions/workflows/ci-windows.yml/badge.svg)](https://github.com/FedericoBruzzone/tgt/actions/workflows/ci-windows.yml)<div><sub>Stars: 297 / Last Update: 2024-09-23 / Initial Date: 2024-02-15</sub></div>

### System tools

* [ajeetdsouza/zoxide](https://github.com/ajeetdsouza/zoxide/) - あなたの習慣を学習する `cd` に代わる高速な [[リリース]](https://github.com/ajeetdsouza/zoxide/workflows/.github/workflows/release.yml/badge.svg)](https://github.com/ajeetdsouza/zoxide/actions)<div><sub>Stars: 22.1k / Last Update: 2024-09-30 / Initial Date: 2020-03-05</sub></div>
* [atuin](https://github.com/atuinsh/atuin) [[atuin](https://crates.io/crates/atuin)] - Atuinは既存のシェル履歴をSQLiteデータベースで置き換え、コマンドの追加コンテキストを記録します。さらに、Atuinサーバーを経由して、オプションで完全に暗号化されたマシン間の履歴の同期を提供します。<div><sub>Stars: 20.4k / Last Update: 2024-10-03 / Initial Date: 2020-10-04</sub></div>
* [bandwhich](https://github.com/imsnif/bandwhich) - 端末帯域利用ツール<div><sub>Stars: 10.0k / Last Update: 2024-10-01 / Initial Date: 2019-09-06</sub></div>
* [bottom](https://github.com/ClementTsang/bottom) - さらにもう一つ、クロスプラットフォームのグラフィカルなプロセス/システムモニタがある。[GitHubワークフローのステータス（ブランチ）](https://img.shields.io/github/workflow/status/ClementTsang/bottom/ci/master)](https://github.com/ClementTsang/bottom/actions?query=branch%3Amaster)<div><sub>Stars: 9.9k / Last Update: 2024-09-28 / Initial Date: 2019-08-28</sub></div>
* [brocode/fblog](https://github.com/brocode/fblog) - 小さなコマンドラインJSONログ・ビューア<div><sub>Stars: 434 / Last Update: 2024-10-04 / Initial Date: 2017-07-06</sub></div>
* [brush-shell](https://github.com/reubeno/brush) - bash/POSIX互換シェル [![CICD](https://github.com/reubeno/brush/actions/workflows/ci.yaml/badge.svg)](https://github.com/reubeno/brush/actions/workflows/ci.yaml)[![Crate](https://img.shields.io/crates/v/brush-shell.svg?logo=rust)](https://crates.io/crates/brush-shell)<div><sub>Stars: 17 / Last Update: 2024-10-04 / Initial Date: 2024-05-10</sub></div>
* [bustd](https://github.com/vrmiguel/bustd) - Linux 上でメモリ不足のシナリオを処理するための軽量なプロセスキラー・デーモン。[GitHubワークフローの状況 (ブランチ)](https://img.shields.io/github/workflow/status/vrmiguel/bustd/build-and-test)](https://github.com/vrmiguel/bustd/actions?query=branch%3Amaster)<div><sub>Stars: 214 / Last Update: 2023-10-30 / Initial Date: 2021-07-06</sub></div>
* [cantino/mcfly](https://github.com/cantino/mcfly) - 殻の歴史を飛び越えろグレート・スコット<div><sub>Stars: 6.9k / Last Update: 2024-09-04 / Initial Date: 2018-07-15</sub></div>
* [ChurchTao/clipboard-rs](https://github.com/ChurchTao/clipboard-rs) [[clipboard-rs](https://crates.io/crates/clipboard-rs)] - システムレベルのクリップボードの内容を取得・設定・変更監視するための、Rustで書かれたクロスプラットフォーム・ライブラリ。<div><sub>Stars: 56 / Last Update: 2024-09-20 / Initial Date: 2024-01-25</sub></div>
* [crabz](https://github.com/sstadick/crabz) - マルチスレッド圧縮・解凍CLIツール [![ビルド状況](https://github.com/sstadick/crabz/workflows/Check/badge.svg)](https://github.com/sstadick/crabz/actions?query=workflow%3ACheck)<div><sub>Stars: 330 / Last Update: 2024-03-20 / Initial Date: 2021-08-22</sub></div>
* [cristianoliveira/funzzy](https://github.com/cristianoliveira/funzzy) - entr](http://eradman.com/entrproject/)にインスパイアされた、設定可能なファイルシステム・ウォッチャー。<div><sub>Stars: 233 / Last Update: 2024-09-23 / Initial Date: 2016-03-21</sub></div>
* [dalance/procs](https://github.com/dalance/procs) - ps'の現代的な置き換え[![回帰]](https://github.com/dalance/procs/actions/workflows/regression.yml/badge.svg)](https://github.com/dalance/procs/actions/workflows/regression.yml)<div><sub>Stars: 5.1k / Last Update: 2024-10-01 / Initial Date: 2019-01-28</sub></div>
* [dust](https://github.com/bootandy/dust) - より直感的なデュ<div><sub>Stars: 8.7k / Last Update: 2024-09-16 / Initial Date: 2018-03-16</sub></div>
* [eza-community/eza](https://github.com/eza-community/eza) - ls' の置き換え<div><sub>Stars: 11.5k / Last Update: 2024-10-04 / Initial Date: 2023-07-28</sub></div>
* [fselect](https://crates.io/crates/fselect) - SQLライクなクエリでファイルを検索
* [gitui](https://github.com/extrawurst/gitui) - git 用の超高速ターミナルクライアント。[ビルド](https://github.com/extrawurst/gitui/workflows/CI/badge.svg?branch=master)](https://github.com/extrawurst/gitui/actions)<div><sub>Stars: 18.3k / Last Update: 2024-10-03 / Initial Date: 2020-03-16</sub></div>
* [GQL](https://github.com/amrdeveloper/gql) - .gitファイルで実行するSQLライクなクエリ言語。<div><sub>Stars: 3.2k / Last Update: 2024-10-03 / Initial Date: 2023-06-05</sub></div>
* [httm](https://github.com/kimono-koans/httm) - ZFS/btrfs/nilfs2用のインタラクティブでファイルレベルのTime Machineライクなツール（実際のTime Machineバックアップも可能！）。<div><sub>Stars: 1.4k / Last Update: 2024-10-02 / Initial Date: 2022-03-07</sub></div>
* [j0ru/kickoff](https://github.com/j0ru/kickoff) - 高速で軽快なwaylandプログラムランチャー [![build](https://github.com/j0ru/kickoff/actions/workflows/ci.yml/badge.svg)](https://github.com/j0ru/kickoff/actions)<div><sub>Stars: 396 / Last Update: 2024-10-01 / Initial Date: 2020-12-21</sub></div>
* [Kondo](https://github.com/tbillington/kondo) - ソフトウェアプロジェクトの成果物を削除し、ディスク領域を取り戻すためのCLI & GUIツール<div><sub>Stars: 1.8k / Last Update: 2024-09-23 / Initial Date: 2020-01-27</sub></div>
* [LACT](https://github.com/ilya-zlobintsev/LACT) - Linux AMDGPUコントローラ<div><sub>Stars: 1.2k / Last Update: 2024-10-02 / Initial Date: 2020-10-17</sub></div>
* [lodosgroup/lpm](https://github.com/lodosgroup/lpm) - 実験的なシステムパッケージマネージャー<div><sub>Stars: 65 / Last Update: 2024-03-03 / Initial Date: 2022-02-15</sub></div>
* [lsd](https://github.com/lsd-rs/lsd) - きれいな色と素晴らしいアイコンをたくさん使ったls [![build](https://github.com/lsd-rs/lsd/workflows/CICD/badge.svg?branch=master)](https://github.com/lsd-rs/lsd/actions)<div><sub>Stars: 13.3k / Last Update: 2024-09-28 / Initial Date: 2018-11-24</sub></div>
* [mdgaziur/findex](https://github.com/mdgaziur/findex) - Findexは、GTK3を使用した高度にカスタマイズ可能なアプリケーション・ファインダーです。<div><sub>Stars: 577 / Last Update: 2024-09-29 / Initial Date: 2021-10-31</sub></div>
* [mitnk/cicada](https://github.com/mitnk/cicada) - bashライクなUnixシェル<div><sub>Stars: 975 / Last Update: 2024-09-29 / Initial Date: 2017-03-09</sub></div>
* [netscanner](https://github.com/Chleba/netscanner) - TUIネットワークスキャナー<div><sub>Stars: 824 / Last Update: 2024-09-16 / Initial Date: 2023-12-10</sub></div>
* [nickgerace/gfold](https://github.com/nickgerace/gfold) [[gfold](https://crates.io/crates/gfold)] - 複数の Git リポジトリを管理するための CLI ツール [![build](https://img.shields.io/github/workflow/status/nickgerace/gfold/merge/main)](https://github.com/nickgerace/gfold/actions?query=workflow%3Amerge+branch%3Amain)<div><sub>Stars: 283 / Last Update: 2024-07-28 / Initial Date: 2020-04-04</sub></div>
* [nushell/nushell](https://github.com/nushell/nushell) - 新しいタイプのシェル<div><sub>Stars: 31.9k / Last Update: 2024-10-04 / Initial Date: 2019-05-10</sub></div>
* [orhun/kmon](https://github.com/orhun/kmon) - Linuxカーネルマネージャとアクティビティモニタ ![https://github.com/orhun/kmon/actions](https://img.shields.io/github/actions/workflow/status/orhun/kmon/ci.yml?branch=master&label=build)<div><sub>Stars: 2.5k / Last Update: 2024-08-25 / Initial Date: 2019-11-05</sub></div>
* [orhun/systeroid](https://github.com/orhun/systeroid) - 端末ユーザインターフェイスを持つ sysctl(8) より強力な代替 ![https://github.com/orhun/systeroid/actions](https://img.shields.io/github/actions/workflow/status/orhun/systeroid/ci.yml?branch=main&label=build)<div><sub>Stars: 1.3k / Last Update: 2024-06-04 / Initial Date: 2021-10-17</sub></div>
* [ouch](https://github.com/ouch-org/ouch) - コマンドラインで無痛圧縮・解凍 [![GitHub Workflow Status (branch)]](https://img.shields.io/github/workflow/status/ouch-org/ouch/build-and-test)](https://github.com/ouch-org/ouch/actions?query=branch%3Amaster)<div><sub>Stars: 2.2k / Last Update: 2024-10-01 / Initial Date: 2021-03-19</sub></div>
* [pkolaczk/fclones](https://github.com/pkolaczk/fclones) - 効率的な重複ファイル検索・削除ツール<div><sub>Stars: 1.9k / Last Update: 2024-05-30 / Initial Date: 2020-06-06</sub></div>
* [pop-os/popsicle](https://github.com/pop-os/popsicle) - 複数のUSBデバイスを並行してフラッシュするためのGTK3とCLIユーティリティ<div><sub>Stars: 645 / Last Update: 2024-08-20 / Initial Date: 2017-10-03</sub></div>
* [pop-os/system76-power](https://github.com/pop-os/system76-power/) - CLIツールを備えたLinux電源管理デーモン（DBusインターフェース）。<div><sub>Stars: 586 / Last Update: 2024-09-06 / Initial Date: 2018-02-17</sub></div>
* [pueue](https://github.com/nukesor/pueue) - 長時間実行するシェルコマンドを管理する[GitHubアクションワークフロー](https://github.com/nukesor/pueue/workflows/Test%20build/badge.svg?branch=master)](https://github.com/nukesor/pueue/actions)<div><sub>Stars: 4.9k / Last Update: 2024-09-25 / Initial Date: 2015-09-04</sub></div>
* [qarmin/czkawka](https://github.com/qarmin/czkawka) - 重複、空フォルダ、類似画像などを探す多機能アプリ。[[GitHubアクションワークフロー]](https://github.com/qarmin/czkawka/actions/workflows/pages/pages-build-deployment/badge.svg?branch=master)](https://github.com/qarmin/czkawka/actions)<div><sub>Stars: 19.6k / Last Update: 2024-10-04 / Initial Date: 2020-09-01</sub></div>
* [redox-os/ion](https://github.com/redox-os/ion) - 次世代システムシェル<div><sub>Stars: 1.5k / Last Update: 2024-10-04 / Initial Date: 2015-10-07</sub></div>
* [sharkdp/bat](https://github.com/sharkdp/bat) - 羽の生えた猫(1)のクローン。[CICD](https://github.com/sharkdp/bat/actions/workflows/CICD.yml/badge.svg?branch=master)](https://github.com/sharkdp/bat/actions/workflows/CICD.yml)<div><sub>Stars: 49.0k / Last Update: 2024-10-01 / Initial Date: 2018-04-21</sub></div>
* [sharkdp/fd](https://github.com/sharkdp/fd) - シンプルで素早く、ユーザーフレンドリーな検索方法です。[CICD](https://github.com/sharkdp/fd/actions/workflows/CICD.yml/badge.svg)](https://github.com/sharkdp/fd/actions/workflows/CICD.yml)<div><sub>Stars: 33.6k / Last Update: 2024-10-02 / Initial Date: 2017-05-09</sub></div>
* [sitkevij/hex](https://github.com/sitkevij/hex) - カラー化されたhexdumpターミナルユーティリティ。<div><sub>Stars: 516 / Last Update: 2024-06-09 / Initial Date: 2018-03-13</sub></div>
* [supercilex/fuc](https://github.com/supercilex/fuc) - 高速な `cp` コマンドと `rm` コマンド<div><sub>Stars: 346 / Last Update: 2024-08-06 / Initial Date: 2021-11-23</sub></div>
* [trippy](https://github.com/fujiapple852/trippy) - ネットワーク診断ツール [![ビルドバッジ]](https://github.com/fujiapple852/trippy/workflows/CI/badge.svg)](https://github.com/fujiapple852/trippy/actions/workflows/ci.yml)<div><sub>Stars: 3.5k / Last Update: 2024-10-04 / Initial Date: 2022-03-28</sub></div>
* [uutils/coreutils](https://github.com/uutils/coreutils) - GNU coreutils [![CICD]](https://github.com/uutils/coreutils/actions/workflows/CICD.yml/badge.svg)](https://github.com/uutils/coreutils/actions/workflows/CICD.yml) をクロスプラットフォームで書き直したもの。<div><sub>Stars: 17.6k / Last Update: 2024-10-03 / Initial Date: 2013-08-02</sub></div>
* [watchexec](https://github.com/watchexec/watchexec) - ファイルの変更に応じてコマンドを実行する<div><sub>Stars: 5.3k / Last Update: 2024-08-21 / Initial Date: 2016-09-18</sub></div>
* [XAMPPRocky/tokei](https://github.com/XAMPPRocky/tokei) - コードの行数を数える<div><sub>Stars: 11.0k / Last Update: 2024-09-30 / Initial Date: 2015-05-26</sub></div>
* [ynqa/jnv](https://github.com/ynqa/jnv) - jq [![ci](https://github.com/ynqa/jnv/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/ynqa/jnv/actions/workflows/ci.yml) を使ったインタラクティブなJSONフィルター<div><sub>Stars: 4.8k / Last Update: 2024-09-25 / Initial Date: 2024-03-18</sub></div>
* [ynqa/sig](https://github.com/ynqa/sig) - 対話型grep（ストリーミング用） [![ci](https://github.com/ynqa/sig/actions/workflows/ci.yml/badge.svg)](https://github.com/ynqa/sig/actions/workflows/ci.yml)<div><sub>Stars: 578 / Last Update: 2024-07-29 / Initial Date: 2024-05-25</sub></div>

### Task scheduling

* [tasklet](https://github.com/stav121/tasklet) [[tasklet](https://crates.io/crates/tasklet)] - Rustで書かれたタスクスケジューリングライブラリ ![ビルド状況](https://img.shields.io/github/actions/workflow/status/stav121/tasklet/rust.yml)<div><sub>Stars: 25 / Last Update: 2024-08-08 / Initial Date: 2020-12-22</sub></div>

### Text editors

* [amp](https://amp.rs) - Vi/Vimにインスパイアされた。
* [emacs-ng](https://github.com/emacs-ng/emacs-ng) - 新機能を導入するために、CコードベースをRubstコードで補完する。<div><sub>Stars: 1.7k / Last Update: 2024-07-16 / Initial Date: 2020-08-23</sub></div>
* [helix](https://github.com/helix-editor/helix) - Neovim/Kakoune にインスパイアされたポストモダンなモーダルテキストエディタ。[ビルドバッジ](https://github.com/helix-editor/helix/actions/workflows/build.yml/badge.svg)](https://github.com/helix-editor/helix/actions)<div><sub>Stars: 33.2k / Last Update: 2024-10-04 / Initial Date: 2020-06-01</sub></div>
* [ilai-deutel/kibi](https://github.com/ilai-deutel/kibi) - シンタックスハイライト、インクリメンタルサーチなどを備えた小さな (1024LOC以下) テキストエディタ。[ビルドバッジ](https://github.com/ilai-deutel/kibi/workflows/CI/badge.svg?branch=master)](https://github.com/ilai-deutel/kibi/actions?query=branch%3Amaster)<div><sub>Stars: 1.5k / Last Update: 2024-10-02 / Initial Date: 2020-02-10</sub></div>
* [Lapce](https://github.com/lapce/lapce) - バックエンドを備えたモダンなエディター。廃止された[xi-editor](https://github.com/xi-editor/xi-editor)からヒントを得ています。<div><sub>Stars: 34.3k / Last Update: 2024-10-05 / Initial Date: 2018-02-06</sub></div>
* [ox](https://github.com/curlpipe/ox) - ターミナルで動作する独立したRustテキストエディタ！<div><sub>Stars: 3.3k / Last Update: 2024-10-03 / Initial Date: 2020-07-29</sub></div>
* [vamolessa/pepper](https://git.sr.ht/~lessa/pepper) [[pepper](https://crates.io/crates/pepper)] - ターミナルからのコード編集を簡素化する、意見付きモーダルエディタ
* [zed](https://github.com/zed-industries/zed) - AtomとTree-sitterのクリエイターによる、高性能でマルチプレイヤー対応のコードエディター。<div><sub>Stars: 47.9k / Last Update: 2024-10-04 / Initial Date: 2021-02-20</sub></div>

### Text processing

* [ashvardanian/stringzilla](https://github.com/ashvardanian/StringZilla) - x86 AVX2 & AVX-512 および Arm NEON 用 SIMD アクセラレーション文字列検索、ソート、編集距離、アライメント、ジェネレータ [![crates.io]](https://img.shields.io/crates/v/stringzilla.svg)](https://crates.io/crates/stringzilla)<div><sub>Stars: 2.1k / Last Update: 2024-10-03 / Initial Date: 2020-08-14</sub></div>
* [dominikwilkowski/cfonts](https://github.com/dominikwilkowski/cfonts) [[cfonts](https://crates.io/crates/cfonts)] - コンソール用のセクシーなANSIフォント ![ビルド・バッジ](https://github.com/dominikwilkowski/cfonts/actions/workflows/testing.yml/badge.svg)<div><sub>Stars: 1.6k / Last Update: 2024-06-17 / Initial Date: 2015-01-11</sub></div>
* [grex](https://github.com/pemistahl/grex) - ユーザー提供のテストケースから正規表現を生成するコマンドラインツールとライブラリ<div><sub>Stars: 7.2k / Last Update: 2024-10-03 / Initial Date: 2019-10-05</sub></div>
* [jqnatividad/qsv](https://github.com/jqnatividad/qsv) [[qsv](https://crates.io/crates/qsv)] - 高性能CSVデータラングリングツールキット。xsvからフォークされ、34以上のコマンドとその他が追加されている。[![Linuxのビルド状況](https://github.com/jqnatividad/qsv/actions/workflows/rust.yml/badge.svg)](https://github.com/jqnatividad/qsv/actions/workflows/rust.yml) [![Windowsのビルド状況](https://github.com/jqnatividad/qsv/actions/workflows/rust-windows.yml/badge.svg)](https://github.com/jqnatividad/qsv/actions/workflows/rust-windows.yml) [![macOSのビルド状況](https://github.com/jqnatividad/qsv/actions/workflows/rust-macos.yml/badge.svg)](https://github.com/jqnatividad/qsv/actions/workflows/rust-macos.yml)<div><sub>Stars: 2.5k / Last Update: 2024-10-04 / Initial Date: 2020-12-11</sub></div>
* [Lisprez/so_stupid_search](https://github.com/Lisprez/so_stupid_search) - 人間のためのシンプルで高速な文字列検索ツール<div><sub>Stars: 161 / Last Update: 2024-09-23 / Initial Date: 2016-04-01</sub></div>
* [phiresky/ripgrep-all](https://github.com/phiresky/ripgrep-all) - ripgrepだけでなく、PDF、電子書籍、Office文書、zip、tar.gzなどでも検索できる。<div><sub>Stars: 8.0k / Last Update: 2024-09-04 / Initial Date: 2019-06-04</sub></div>
* [replicadse/complate](https://github.com/replicadse/complate) - GITコミットのような）メッセージを標準化するために設計された、端末内のテキストテンプレートツール。[![crates.io](https://img.shields.io/crates/v/complate.svg)](https://crates.io/crates/complate) [![crates.io](https://img.shields.io/crates/d/complate?label=crates.io%20downloads)](https://crates.io/crates/complate) [![build badge](https://github.com/replicadse/complate/workflows/pipeline/badge.svg?branch=master)](https://github.com/replicadse/complate/actions)<div><sub>Stars: 37 / Last Update: 2024-08-17 / Initial Date: 2020-01-27</sub></div>
* [ripgrep](https://crates.io/crates/ripgrep) - は、シルバーサーチャーの使いやすさとgrepの速さを兼ね備えている。
* [ruplacer](https://github.com/your-tools/ruplacer) - ソース・ファイル内のテキストの検索と置換 [![テストの実行]](https://github.com/your-tools/ruplacer/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/your-tools/ruplacer/actions/workflows/test.yml)<div><sub>Stars: 432 / Last Update: 2024-08-10 / Initial Date: 2017-11-08</sub></div>
* [sd](https://crates.io/crates/sd) - 直感的な検索＆置換CLI
* [sstadick/hck](https://github.com/sstadick/hck) - cut` [![ビルドバッジ]](https://github.com/sstadick/hck/workflows/Check/badge.svg?branch=master)](https://github.com/sstadick/hck)より速く、より機能的なドロップイン代替品。<div><sub>Stars: 695 / Last Update: 2024-07-17 / Initial Date: 2021-06-24</sub></div>
* [sstadick/hck](https://github.com/sstadick/hck) - cut` [![ビルドバッジ]](https://github.com/sstadick/hck/workflows/Check/badge.svg?branch=master)](https://github.com/sstadick/hck)より速く、より機能的なドロップイン代替品。<div><sub>Stars: 695 / Last Update: 2024-07-17 / Initial Date: 2021-06-24</sub></div>
* [whitfin/bytelines](https://github.com/whitfin/bytelines) [[bytelines](https://crates.io/crates/bytelines)] - 入力ラインをバイト・スライスとして読み取り、高効率を実現。<div><sub>Stars: 57 / Last Update: 2024-01-05 / Initial Date: 2018-12-14</sub></div>
* [whitfin/runiq](https://github.com/whitfin/runiq) - ソートされていない入力から重複行をフィルタリングする効率的な方法。<div><sub>Stars: 204 / Last Update: 2024-09-23 / Initial Date: 2018-04-29</sub></div>
* [xsv](https://crates.io/crates/xsv) - 高速CSVコマンドラインツール（スライス、インデックス作成、選択、検索、サンプリングなど）

### Utilities

* [1History](https://github.com/1History/1History) - Firefox/Chrome/Safariの履歴を1つのSQLiteファイルにバックアップするコマンドラインインターフェイス [![ビルド状況]](https://github.com/1History/1History/actions/workflows/CI.yml/badge.svg)](https://github.com/1History/1History/actions/workflows/CI.yml)<div><sub>Stars: 450 / Last Update: 2024-03-26 / Initial Date: 2022-01-22</sub></div>
* [dcapal](https://github.com/dcapal/dcapal) - DcaPalは登録不要の無料オンラインツールで、ドルコスト平均法投資でポートフォリオのバランスを保つのに役立ちます。<div><sub>Stars: 54 / Last Update: 2024-09-30 / Initial Date: 2022-11-20</sub></div>
* [Epic Asset Manager](https://github.com/AchetaGames/Epic-Asset-Manager) - Unreal Engine をインストールし、Epic Games Store から購入したアセット、プロジェクト、プラグイン、ゲームをダウンロード、管理するための非公式クライアントです。<div><sub>Stars: 388 / Last Update: 2024-09-25 / Initial Date: 2021-02-20</sub></div>
* [Linus-Mussmaecher/rucola](https://github.com/Linus-Mussmaecher/rucola) - ターミナルベースのマークダウンノートマネージャ。[クレート](https://img.shields.io/crates/v/rucola-notes.svg?logo=rust)](https://crates.io/crates/rucola-notes) [![ビルドステータス](https://github.com/Linus-Mussmaecher/rucola/actions/workflows/continuous-testing.yml/badge.svg)](https://github.com/Linus-Mussmaecher/rucola/actions/workflows/continuous-testing.yml)<div><sub>Stars: 149 / Last Update: 2024-08-19 / Initial Date: 2024-02-21</sub></div>
* [Mobslide](https://github.com/thewh1teagle/mobslide) - スマートフォンをプレゼンテーションのリモコンにするデスクトップアプリケーション。<div><sub>Stars: 351 / Last Update: 2024-09-24 / Initial Date: 2023-11-18</sub></div>
* [mprocs](https://github.com/pvolok/mprocs) - 複数のプロセスを実行するためのTUI<div><sub>Stars: 1.5k / Last Update: 2024-07-26 / Initial Date: 2021-08-30</sub></div>
* [mrjackwills/oxker](https://github.com/mrjackwills/oxker) [[oxker](https://crates.io/crates/oxker)] - docker コンテナを表示・制御するためのシンプルな TUI。<div><sub>Stars: 666 / Last Update: 2024-09-07 / Initial Date: 2022-04-25</sub></div>
* [nix-community/nix-init](https://github.com/nix-community/nix-init) - ハッシュプリフェッチ、依存性推論、ライセンス検出などを使って URL から Nix パッケージを生成する [![build-badge]](https://github.com/nix-community/nix-init/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/nix-init/actions/workflows/ci.yml)<div><sub>Stars: 879 / Last Update: 2024-10-04 / Initial Date: 2023-01-18</sub></div>
* [nix-community/nix-melt](https://github.com/nix-community/nix-melt) - レンジャーのようなフレーク.lock viewer [![ビルドバッジ]](https://github.com/nix-community/nix-melt/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/nix-melt/actions/workflows/ci.yml)<div><sub>Stars: 226 / Last Update: 2024-10-02 / Initial Date: 2023-04-25</sub></div>
* [nix-community/nurl](https://github.com/nix-community/nurl) [[nurl](https://crates.io/crates/nurl)] - リポジトリURLからNixフェッチャーコールを生成する [![build-badge](https://github.com/nix-community/nurl/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/nurl/actions/workflows/ci.yml)<div><sub>Stars: 462 / Last Update: 2024-10-03 / Initial Date: 2022-12-30</sub></div>
* [nomino](https://github.com/yaa110/nomino) - 開発者向けバッチ・リネーム・ユーティリティ<div><sub>Stars: 562 / Last Update: 2024-06-06 / Initial Date: 2020-04-17</sub></div>
* [rust-parallel](https://github.com/aaronriekenberg/rust-parallel) - Tokioを使ってコマンドを並列実行する高速コマンドラインアプリ。  GNU Parallelやxargsに似たインターフェース。[クレート](https://img.shields.io/crates/v/rust-parallel.svg?logo=rust)](https://crates.io/crates/rust-parallel) [![ビルドステータス](https://github.com/aaronriekenberg/rust-parallel/actions/workflows/CI.yml/badge.svg)](https://github.com/aaronriekenberg/rust-parallel/actions/workflows/CI.yml)<div><sub>Stars: 156 / Last Update: 2024-08-25 / Initial Date: 2022-11-21</sub></div>
* [rustdesk/rustdesk](https://github.com/rustdesk/rustdesk) - TeamViewerやAnyDeskに代わるリモートデスクトップソフトウェア。<div><sub>Stars: 73.6k / Last Update: 2024-10-05 / Initial Date: 2020-09-28</sub></div>
* [rustic-rs/rustic](https://github.com/rustic-rs/rustic) [[rustic-rs](https://crates.io/crates/rustic-rs)] - Rustによる高速、暗号化、重複排除バックアップ。[バージョン](https://img.shields.io/crates/v/rustic-rs.svg)](https://crates.io/crates/rustic-rs)<div><sub>Stars: 1.8k / Last Update: 2024-10-05 / Initial Date: 2022-03-14</sub></div>
* [sorairolake/qrtool](https://github.com/sorairolake/qrtool) [[qrtool](https://crates.io/crates/qrtool)] - QRコード画像をエンコード・デコードするユーティリティ。[CI](https://github.com/sorairolake/qrtool/workflows/CI/badge.svg?branch=develop)](https://github.com/sorairolake/qrtool/actions?query=workflow%3ACI)<div><sub>Stars: 128 / Last Update: 2024-09-30 / Initial Date: 2022-08-18</sub></div>
* [str4d/rage](https://github.com/str4d/rage) [[rage](https://crates.io/crates/rage)] - age](https://github.com/FiloSottile/age)のRust実装。<div><sub>Stars: 2.6k / Last Update: 2024-10-02 / Initial Date: 2019-10-08</sub></div>
* [str4d/rage](https://github.com/str4d/rage) [[rage](https://crates.io/crates/rage)] - age](https://github.com/FiloSottile/age)のRust実装。<div><sub>Stars: 2.6k / Last Update: 2024-10-02 / Initial Date: 2019-10-08</sub></div>
* [suckit](https://github.com/Skallwar/suckit) - ウェブサイトを再帰的に訪問し、コンテンツをディスクにダウンロードする。[クレート](https://img.shields.io/crates/v/suckit.svg?logo=rust)](https://crates.io/crates/suckit) [![ビルド・ステータス](https://github.com/Skallwar/suckit/workflows/Build%20and%20test/badge.svg)](https://github.com/Skallwar/suckit/blob/master/.github/workflows/build_and_test.yml)<div><sub>Stars: 732 / Last Update: 2024-04-05 / Initial Date: 2019-10-29</sub></div>
* [Tabiew](https://github.com/shshemi/tabiew) - CSVファイルの表示とクエリを行う軽量なTUIアプリ。<div><sub>Stars: 378 / Last Update: 2024-09-08 / Initial Date: 2024-04-27</sub></div>
* [tversteeg/emplace](https://github.com/tversteeg/emplace) - 複数のマシンにインストールされたパッケージの同期<div><sub>Stars: 254 / Last Update: 2024-10-03 / Initial Date: 2019-09-08</sub></div>
* [vamolessa/verco](https://github.com/vamolessa/verco) [[verco](https://crates.io/crates/verco)] - キーボードショートカットに特化したシンプルな Git/Hg tui クライアント<div><sub>Stars: 229 / Last Update: 2023-11-14 / Initial Date: 2017-11-05</sub></div>
* [vaultwarden](https://github.com/dani-garcia/vaultwarden#readme) [![Build](https://github.com/dani-garcia/vaultwarden/actions/workflows/build.yml/badge.svg)](https://github.com/dani-garcia/vaultwarden/actions/workflows/build.yml) - Rustで書かれたBitwardenサーバーAPIの代替実装
* [Vibe](https://github.com/thewh1teagle/vibe) - あらゆるプラットフォームで、あらゆる言語の音声やビデオを書き起こします。<div><sub>Stars: 921 / Last Update: 2024-10-03 / Initial Date: 2024-01-08</sub></div>
* [warpdotdev/Warp](https://github.com/warpdotdev/Warp) - :heavy_dollar_sign：Warpは、あなたとあなたのチームの生産性を向上させるために作られた、GPUアクセラレーションを採用した超高速の最新ターミナルです。<div><sub>Stars: 21.1k / Last Update: 2024-07-30 / Initial Date: 2021-07-08</sub></div>
* [wrestic](https://github.com/alvaro17f/wrestic) - レスティックを包むもの。<div><sub>Stars: 80 / Last Update: 2024-04-22 / Initial Date: 2023-08-04</sub></div>
* [wthrr](https://github.com/ttytm/wthrr-the-weathercrab) - ターミナルの天気コンパニオン。[![crates.io](https://img.shields.io/crates/v/wthrr?logo=rust)](https://crates.io/crates/wthrr)<div><sub>Stars: 379 / Last Update: 2024-10-04 / Initial Date: 2022-07-12</sub></div>

### Video

* [dertuxmalwieder/yaydl](https://github.com/dertuxmalwieder/yaydl) [[yaydl](https://crates.io/crates/yaydl)] - シンプルな動画ダウンローダー<div><sub>Stars: 277 / Last Update: 2024-09-16 / Initial Date: 2020-11-08</sub></div>
* [gyroflow/gyroflow](https://github.com/gyroflow/gyroflow) - ジャイロデータを利用したビデオ安定化アプリケーション<div><sub>Stars: 6.6k / Last Update: 2024-10-05 / Initial Date: 2021-11-11</sub></div>
* [harlanc/xiu](https://github.com/harlanc/xiu) - 強力で安全なライブサーバー (rtmp/httpflv/hls/relay)。[![crates.io](https://img.shields.io/crates/v/xiu.svg)](https://crates.io/crates/xiu)<div><sub>Stars: 1.8k / Last Update: 2024-09-20 / Initial Date: 2020-08-16</sub></div>
* [vidmerger](https://github.com/TGotwig/vidmerger) - CLIでビデオ＆オーディオファイルをマージ<div><sub>Stars: 119 / Last Update: 2024-07-27 / Initial Date: 2020-06-05</sub></div>
* [xiph/rav1e](https://github.com/xiph/rav1e) - 最も高速で安全なAV1エンコーダ。<div><sub>Stars: 3.7k / Last Update: 2024-10-05 / Initial Date: 2017-09-24</sub></div>

### Virtualization

* [containers/youki](https://github.com/containers/youki) - コンテナー・ランタイム [![ビルド・バッジ]](https://github.com/containers/youki/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/containers/youki/actions)<div><sub>Stars: 6.2k / Last Update: 2024-10-04 / Initial Date: 2021-03-27</sub></div>
* [firecracker-microvm/firecracker](https://github.com/firecracker-microvm/firecracker) - コンテナワークロードのための軽量仮想マシン [Firecracker Microvm](https://firecracker-microvm.github.io/)<div><sub>Stars: 25.4k / Last Update: 2024-10-04 / Initial Date: 2017-10-19</sub></div>
* [kata-containers/kata-containers](https://github.com/kata-containers/kata-containers) - 軽量な仮想マシン（VM）の実装で、コンテナのように動作し、VMのワークロード分離とセキュリティの利点を提供する。<div><sub>Stars: 5.4k / Last Update: 2024-10-04 / Initial Date: 2017-12-07</sub></div>

### Web

* [cfal/tobaru](https://github.com/cfal/tobaru) - 許可リスト、IPおよびTLS SNI/ALPNルールベースのルーティング、iptablesサポート、ラウンドロビン転送（負荷分散）、ホットリローディングを備えたポートフォワーダー。<div><sub>Stars: 184 / Last Update: 2024-10-02 / Initial Date: 2021-04-19</sub></div>
* [importantimport/hatsu](https://github.com/importantimport/hatsu) - 🩵 静的サイトのための、セルフホストで全自動のActivityPubブリッジ。[リリース](https://github.com/importantimport/hatsu/actions/workflows/release.yml/badge.svg)](https://github.com/importantimport/hatsu/actions/workflows/release.yml)<div><sub>Stars: 131 / Last Update: 2024-09-30 / Initial Date: 2023-07-19</sub></div>
* [LemmyNet/lemmy](https://github.com/LemmyNet/lemmy) - フェディバースのためのリンクアグリゲータ／redditクローン[[ビルド・ステータス]](https://cloud.drone.io/api/badges/LemmyNet/lemmy/status.svg)](https://cloud.drone.io/LemmyNet/lemmy)<div><sub>Stars: 13.2k / Last Update: 2024-10-05 / Initial Date: 2019-02-14</sub></div>
* [libreddit](https://github.com/libreddit/libreddit) - Redditに代わるプライベート・フロントエンド<div><sub>Stars: 5.0k / Last Update: 2024-05-02 / Initial Date: 2020-08-12</sub></div>
* [MASQ-Project/Node](https://github.com/MASQ-Project/Node) - MASQ Nodeソフトウェアは、グローバル・ユーザーが通常のインターネット・コンテンツにアクセスするための分散型ノード・メッシュ・ネットワークを提供する。<div><sub>Stars: 173 / Last Update: 2024-10-04 / Initial Date: 2021-04-09</sub></div>
* [Plume-org/Plume](https://github.com/Plume-org/Plume) - ActivityPub連携ブログアプリケーション<div><sub>Stars: 2.1k / Last Update: 2024-10-02 / Initial Date: 2018-04-21</sub></div>
* [Revolt/backend](https://github.com/revoltchat/backend) - 最新のウェブテクノロジーで構築されたユーザーファーストのチャットプラットフォーム。<div><sub>Stars: 1.1k / Last Update: 2024-10-02 / Initial Date: 2021-06-15</sub></div>

### Web Servers

* [cloudflare/pingora](https://github.com/cloudflare/pingora) - 高速で信頼性が高く、進化可能なネットワークサービスを構築するためのライブラリ。<div><sub>Stars: 21.4k / Last Update: 2024-10-04 / Initial Date: 2023-05-05</sub></div>
* [emanuele-em/proxelar](https://github.com/emanuele-em/proxelar) - MITM プロキシ 🦀！HTTP/1、HTTP/2、SSL/TLS機能付きウェブソケット用ツールキット [![Rust](https://github.com/emanuele-em/proxelar/actions/workflows/rust.yml/badge.svg)](https://github.com/emanuele-em/proxelar/actions/workflows/rust.yml)<div><sub>Stars: 407 / Last Update: 2024-07-23 / Initial Date: 2023-01-19</sub></div>
* [mu-arch/skyfolder](https://github.com/mu-arch/skyfolder) - 🪂 手間のかからない美しいHTTP/Bittorrentサーバー。セキュア<div><sub>Stars: 122 / Last Update: 2024-03-02 / Initial Date: 2023-05-20</sub></div>
* [mufeedvh/binserve](https://github.com/mufeedvh/binserve) - ルーティング、テンプレート化、そしてセキュリティが単一のバイナリに含まれた、コードゼロでセットアップ可能な超高速静的ウェブサーバ [![ビルド・バッジ]](https://github.com/mufeedvh/binserve/workflows/CICD/badge.svg?branch=master)](https://github.com/mufeedvh/binserve/actions)<div><sub>Stars: 1.0k / Last Update: 2024-02-18 / Initial Date: 2020-10-01</sub></div>
* [orhun/rustypaste](https://github.com/orhun/rustypaste) - 最小限のファイル・アップロード／ペーストビン・サービス ![https://github.com/orhun/rustypaste/actions](https://img.shields.io/github/actions/workflow/status/orhun/rustypaste/ci.yml?branch=master&label=build)<div><sub>Stars: 771 / Last Update: 2024-09-30 / Initial Date: 2021-07-27</sub></div>
* [static-web-server](https://github.com/static-web-server/static-web-server) - 静的ファイル配信用の超高速非同期ウェブサーバー。⚡ [![CI](https://github.com/static-web-server/static-web-server/actions/workflows/devel.yml/badge.svg)](https://github.com/static-web-server/static-web-server/actions/workflows/devel.yml?query=branch%3Amaster)<div><sub>Stars: 1.5k / Last Update: 2024-09-17 / Initial Date: 2019-09-02</sub></div>
* [svenstaro/miniserve](https://github.com/svenstaro/miniserve) - 小さな、自己完結型のクロスプラットフォームCLIツールで、バイナリを取得してHTTP経由でファイルを提供することができる[![build badge]](https://github.com/svenstaro/miniserve/workflows/CI/badge.svg?branch=master)](https://github.com/svenstaro/miniserve/actions)<div><sub>Stars: 6.0k / Last Update: 2024-10-01 / Initial Date: 2018-04-26</sub></div>
* [thecoshman/http](https://github.com/thecoshman/http) - これらを主催してください<div><sub>Stars: 444 / Last Update: 2024-09-23 / Initial Date: 2016-12-12</sub></div>
* [TheWaWaR/simple-http-server](https://github.com/TheWaWaR/simple-http-server) - シンプルな静的httpサーバー<div><sub>Stars: 2.6k / Last Update: 2024-08-05 / Initial Date: 2017-05-27</sub></div>

## Development tools

* [ATAC](https://github.com/Julien-cpsn/ATAC) - Rustで作られた機能満載のTUI APIクライアント。ATACはフリー、オープンソース、オフライン、アカウント不要。<div><sub>Stars: 1.9k / Last Update: 2024-08-28 / Initial Date: 2024-02-05</sub></div>
* [bacon](https://github.com/Canop/bacon) - カーゴウォッチに似たバックグラウンドの錆コードチェッカー<div><sub>Stars: 1.8k / Last Update: 2024-10-04 / Initial Date: 2020-10-29</sub></div>
* [clippy](https://crates.io/crates/clippy) - さび止め
* [clog-tool/clog-cli](https://github.com/clog-tool/clog-cli) - git メタデータから変更履歴を生成 ([従来の変更履歴](https://blog.thoughtram.io/announcements/tools/2014/09/18/announcing-clog-a-conventional-changelog-generator-for-the-rest-of-us.html))<div><sub>Stars: 854 / Last Update: 2024-08-15 / Initial Date: 2014-09-12</sub></div>
* [cloudflare/foundations](https://github.com/cloudflare/foundations) - Foundationsはモジュール式のRustライブラリで、分散されたプロダクション・グレードのシステム向けにプログラムのスケーリングを支援するように設計されている。<div><sub>Stars: 1.3k / Last Update: 2024-10-03 / Initial Date: 2024-01-18</sub></div>
* [comtrya](https://github.com/comtrya/comtrya) - localhost / dotfiles用の設定管理ツール [![ビルド・バッジ]](https://github.com/comtrya/comtrya/actions/workflows/main.yaml/badge.svg)](https://github.com/comtrya/comtrya/actions)<div><sub>Stars: 487 / Last Update: 2024-10-04 / Initial Date: 2021-03-04</sub></div>
* [create-rust-app](https://github.com/Wulf/create-rust-app) - 1つのコマンドを実行するだけで、モダンなRubst+Reactウェブ・アプリをセットアップできる。[クレート](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/create-rust-app)<div><sub>Stars: 1.5k / Last Update: 2024-05-20 / Initial Date: 2021-05-08</sub></div>
* [dan-t/rusty-tags](https://github.com/dan-t/rusty-tags) - カーゴプロジェクトとその依存関係すべてに ctags/etags を作成する。<div><sub>Stars: 405 / Last Update: 2024-03-05 / Initial Date: 2014-12-07</sub></div>
* [datanymizer/datanymizer](https://github.com/datanymizer/datanymizer) - 柔軟なルールを備えた強力なデータベース・アノニマイザー [![ビルド・バッジ]](https://github.com/datanymizer/datanymizer/workflows/CI/badge.svg?branch=main)](https://github.com/datanymizer/datanymizer/actions?query=workflow%3ACI+branch%3Amain)<div><sub>Stars: 510 / Last Update: 2024-08-28 / Initial Date: 2020-11-24</sub></div>
* [delta](https://crates.io/crates/git-delta) - gitおよび差分出力用のシンタックス・ハイライト[![ビルド・バッジ]](https://github.com/dandavison/delta/workflows/Continuous%20Integration/badge.svg)](https://github.com/dandavison/delta//actions)
* [dotenv-linter](https://github.com/dotenv-linter/dotenv-linter) - .env`ファイル用リンター [![build badge](https://github.com/dotenv-linter/dotenv-linter/workflows/CI/badge.svg?branch=master)](https://github.com/dotenv-linter/dotenv-linter/actions?query=workflow%3ACI+branch%3Amaster)<div><sub>Stars: 1.8k / Last Update: 2024-09-09 / Initial Date: 2019-11-30</sub></div>
* [envio-cli/envio](https://github.com/envio-cli/envio) - 環境変数を管理するためのモダンでセキュアなCLIツール [![build badge]](https://github.com/envio-cli/envio/actions/workflows/CICD.yml/badge.svg?branch=main)](https://github.com/envio-cli/envio/actions/workflows/CICD.yml)<div><sub>Stars: 804 / Last Update: 2024-09-30 / Initial Date: 2023-03-20</sub></div>
* [Flox](https://github.com/flox/flox) - Floxは仮想環境とパッケージ・マネージャーを一体化したものだ。<div><sub>Stars: 2.5k / Last Update: 2024-10-04 / Initial Date: 2022-12-22</sub></div>
* [fw](https://github.com/brocode/fw) - ワークスペース生産性ブースター [![Rust]](https://github.com/brocode/fw/actions/workflows/rust.yml/badge.svg)](https://github.com/brocode/fw/actions/workflows/rust.yml)<div><sub>Stars: 535 / Last Update: 2024-10-01 / Initial Date: 2017-03-23</sub></div>
* [fzf-make](https://github.com/kyu08/fzf-make) [[fzf-make](https://crates.io/crates/fzf-make)] - プレビューウィンドウ付きのファジーファインダーを使ってmakeターゲットを実行するコマンドラインツール。[![crates.io](https://img.shields.io/crates/v/fzf-make?style=flatflat-square)](https://crates.io/crates/fzf-make)<div><sub>Stars: 77 / Last Update: 2024-10-04 / Initial Date: 2023-03-08</sub></div>
* [geiger](https://github.com/geiger-rs/cargo-geiger) - クレート内の安全でないコードとそのすべての依存関係の使用に関する統計を一覧表示するプログラム [![ビルドステータス]](https://dev.azure.com/cargo-geiger/cargo-geiger/_apis/build/status/geiger-rs.cargo-geiger?branchName=master)](https://dev.azure.com/cargo-geiger/cargo-geiger/_build/latest?definitionId=1&branchName=master)<div><sub>Stars: 1.4k / Last Update: 2024-08-10 / Initial Date: 2018-06-20</sub></div>
* [git-cliff](https://github.com/orhun/git-cliff) - 従来のコミット仕様に従った高度にカスタマイズ可能なChangelog Generator ![https://github.com/orhun/git-cliff/actions](https://img.shields.io/github/actions/workflow/status/orhun/git-cliff/ci.yml?branch=main&label=build)<div><sub>Stars: 9.1k / Last Update: 2024-10-03 / Initial Date: 2021-05-30</sub></div>
* [hot-lib-reloader](https://github.com/rksm/hot-lib-reloader-rs) - ホット・リロード・ラスト・コード [![ビルド・バッジ]](https://github.com/rksm/hot-lib-reloader-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/rksm/hot-lib-reloader-rs/actions/workflows/ci.yml)<div><sub>Stars: 597 / Last Update: 2024-04-29 / Initial Date: 2022-07-31</sub></div>
* [intelli-shell](https://github.com/lasantosr/intelli-shell) - プレースホルダーでコマンドをブックマークし、いつでも検索またはオートコンプリート [![crate](https://img.shields.io/crates/v/intelli-shell.svg)](https://crates.io/crates/intelli-shell) [![build badge](https://github.com/lasantosr/intelli-shell/actions/workflows/release.yml/badge.svg)](https://github.com/lasantosr/intelli-shell/actions/workflows/release.yml)<div><sub>Stars: 222 / Last Update: 2023-10-21 / Initial Date: 2023-01-20</sub></div>
* [just](https://github.com/casey/just) - プロジェクト特有のタスクに便利なコマンドランナー<div><sub>Stars: 20.6k / Last Update: 2024-10-01 / Initial Date: 2016-06-17</sub></div>
* [mask](https://github.com/jacobdeichert/mask) - シンプルなマークダウンファイルで定義されたCLIタスクランナー [![ビルドバッジ]](https://github.com/jacobdeichert/mask/workflows/CI/badge.svg?branch=master)](https://github.com/jacobdeichert/mask/actions?query=workflow%3ACI)<div><sub>Stars: 1.1k / Last Update: 2024-07-27 / Initial Date: 2019-07-06</sub></div>
* [ptags](https://github.com/dalance/ptags) - git リポジトリのためのユニバーサルタグの並列ラッパー<div><sub>Stars: 123 / Last Update: 2024-10-01 / Initial Date: 2018-03-12</sub></div>
* [Rust Search Extension](https://github.com/huhu/rust-search-extension) - アドレスバー(omnibox)でクレートやドキュメントを検索する便利なブラウザ拡張機能。[ビルド状況](https://github.com/huhu/rust-search-extension/workflows/build/badge.svg?branch=master)](https://github.com/huhu/rust-search-extension/actions)<div><sub>Stars: 1.2k / Last Update: 2024-10-02 / Initial Date: 2018-10-31</sub></div>
* [Rustup](https://github.com/rust-lang/rustup) - Rustツールチェーンインストーラ [![ビルドバッジ](https://github.com/rust-lang/rustup/workflows/Linux%20(master)/badge.svg?branch=master)](https://github.com/rust-lang/rustup/actions)<div><sub>Stars: 6.1k / Last Update: 2024-10-03 / Initial Date: 2015-09-26</sub></div>
* [scriptisto](https://github.com/igor-petruk/scriptisto) - 言語にとらわれない "shebangインタプリタ "で、コンパイルされた言語で1ファイルのスクリプトを書くことができます。[ビルド状況](https://cloud.drone.io/api/badges/igor-petruk/scriptisto/status.svg)](https://cloud.drone.io/igor-petruk/scriptisto)<div><sub>Stars: 942 / Last Update: 2024-07-24 / Initial Date: 2019-10-22</sub></div>
* [typos](https://github.com/crate-ci/typos) [[typos-cli](https://crates.io/crates/typos-cli)] - ソースコードスペルチェッカー<div><sub>Stars: 2.6k / Last Update: 2024-10-01 / Initial Date: 2019-04-16</sub></div>

### Build system

* [Cargo](https://crates.io/) - Rust パッケージマネージャ
  * [cargo-benchcmp](https://crates.io/crates/cargo-benchcmp) - マイクロベンチマークを比較するユーティリティ
  * [cargo-bitbake](https://crates.io/crates/cargo-bitbake) - meta-rustのクラスを利用してBitBakeレシピを生成できるカーゴ拡張機能。
  * [cargo-cache](https://crates.io/crates/cargo-cache) - カーゴキャッシュ (`~/.cargo/`/${CARGO_HOME}`) の検査/管理/掃除、サイズの表示など [![ビルドステータス](https://github.com/matthiaskrgr/cargo-cache/workflows/ci/badge.svg?branch=master)](https://github.com/matthiaskrgr/cargo-cache/actions)
  * [cargo-check](https://crates.io/crates/cargo-check) - cargo rustc --Zno-trans` のラッパーで、正しさのチェックだけが必要な場合に、コンパイルを高速化するのに役立つ。
  * [cargo-commander](https://crates.io/crates/cargo-commander) - cargo`のサブコマンドで、`package.json`のscriptsセクションの仕組みに似たCLIコマンドを実行することができる[![ビルドとテスト]](https://github.com/simonhyll/cargo-commander/actions/workflows/build.yml/badge.svg)](https://github.com/simonhyll/cargo-commander/actions/workflows/build.yml)
  * [cargo-count](https://crates.io/crates/cargo-count) - 安全でない統計も含め、ソースコード数と貨物プロジェクトの詳細をリストアップします。
  * [cargo-deb](https://crates.io/crates/cargo-deb) - バイナリ Debian パッケージを生成する
  * [cargo-depgraph](https://crates.io/crates/cargo-depgraph) - カーゴメタデータとグラフビズを使用して、カーゴプロジェクトの依存関係グラフを作成します。
  * [cargo-do](https://crates.io/crates/cargo-do) - 複数の貨物コマンドを連続して実行する
  * [cargo-ebuild](https://crates.io/crates/cargo-ebuild) - インツリーのeクラスを使ってebuildを生成できるカーゴ拡張機能
  * [cargo-edit](https://crates.io/crates/cargo-edit) - コマンドラインからCargo.tomlファイルを読み書きすることで、依存関係を追加したり一覧表示したりできます。
  * [cargo-generate](https://github.com/cargo-generate/cargo-generate) - 既存の git リポジトリをテンプレートとして活用することで rust プロジェクトを生成します。<div><sub>Stars: 1.9k / Last Update: 2024-10-04 / Initial Date: 2018-05-29</sub></div>
  * [cargo-info](https://crates.io/crates/cargo-info) - コマンドラインからcrates.ioにクレートの詳細を問い合わせる
  * [cargo-license](https://crates.io/crates/cargo-license) - すべての依存関係のライセンスを素早く表示するカーゴサブコマンド。
  * [cargo-limit](https://crates.io/crates/cargo-limit) - ノイズの少ないカーゴ：エラーが修正されるまで警告はスキップされる、Neovimとの統合など。[ビルドバッジ](https://github.com/cargo-limit//cargo-limit/actions/workflows/rust.yml/badge.svg)](https://github.com/cargo-limit//cargo-limit/actions)
  * [cargo-make](https://crates.io/crates/cargo-make) - タスクランナーとビルドツール。[ビルド・バッジ](https://github.com/sagiegurari/cargo-make/workflows/CI/badge.svg?branch=master)](https://github.com/sagiegurari/cargo-make/actions)
  * [cargo-modules](https://crates.io/crates/cargo-modules) - クレートのモジュールの概要をツリー状に表示するカーゴプラグイン。
  * [cargo-multi](https://crates.io/crates/cargo-multi) - 複数のクレートに対して指定したカーゴコマンドを実行する
  * [cargo-outdated](https://crates.io/crates/cargo-outdated) - Rustの依存関係の新しいバージョンが利用可能になったとき、または古くなったときに表示します。
  * [cargo-rdme](https://github.com/orium/cargo-rdme) [[cargo-rdme](https://crates.io/crates/cargo-rdme)] - crateのドキュメントからREADMEを作成するCargoサブコマンド。[ビルド・バッジ](https://github.com/orium/cargo-rdme/workflows/CI/badge.svg)](https://github.com/orium/cargo-rdme/actions?query=workflow%3ACI)<div><sub>Stars: 130 / Last Update: 2024-06-21 / Initial Date: 2021-10-09</sub></div>
  * [cargo-release](https://crates.io/crates/cargo-release) - gitで管理されたカーゴプロジェクトをリリースするためのツールで、ビルド、タグ付け、パブリッシュ、ドキュメント作成、プッシュができる[![Rust]](https://github.com/crate-ci/cargo-release/actions/workflows/ci.yml/badge.svg)](https://github.com/crate-ci/cargo-release/actions/workflows/rust.yml)
  * [cargo-script](https://crates.io/crates/cargo-script) - Cargoのパッケージ・エコシステムを利用できるRust "スクリプト "を素早く簡単に実行できる。
  * [cargo-udeps](https://github.com/est31/cargo-udeps) [[cargo-udeps](https://crates.io/crates/cargo-udeps)] - 未使用の依存関係を見つける<div><sub>Stars: 1.7k / Last Update: 2024-10-02 / Initial Date: 2019-08-26</sub></div>
  * [cargo-update](https://crates.io/crates/cargo-update) - インストールされた実行可能ファイルの更新をチェックし、適用するためのカーゴ・サブコマンド
  * [cargo-watch](https://crates.io/crates/cargo-watch) - ソースが変更されたときにプロジェクトをコンパイルするためのカーゴ用ユーティリティ
  * [dtolnay/cargo-expand](https://github.com/dtolnay/cargo-expand) - ソースコードにマクロを展開する<div><sub>Stars: 2.6k / Last Update: 2024-08-25 / Initial Date: 2016-06-05</sub></div>
* CMake
* [facebook/buck2](https://github.com/facebook/buck2) - [Buck2](https://buck2.build/)は、Rustで構築された大規模ビルドツールである。<div><sub>Stars: 3.5k / Last Update: 2024-10-04 / Initial Date: 2022-01-21</sub></div><div><sub>Stars: 3.5k / Last Update: 2024-10-04 / Initial Date: 2022-01-21</sub></div>
* GitHub actions
  * [peaceiris/actions-mdbook](https://github.com/peaceiris/actions-mdbook) - mdBookのGitHubアクション<div><sub>Stars: 295 / Last Update: 2024-10-03 / Initial Date: 2019-11-27</sub></div>
* [Nix](https://nixos.org/)
  * [nix-community/fenix](https://github.com/nix-community/fenix) - Rust toolchains and rust analyzer nightly for nix [![build-badge]](https://github.com/nix-community/fenix/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/fenix/actions/workflows/ci.yml)<div><sub>Stars: 670 / Last Update: 2024-10-04 / Initial Date: 2021-01-02</sub></div>
* [pantsbuild/pants](https://github.com/pantsbuild/pants) - [Pants](https://www.pantsbuild.org/)は、Rustで構築されたあらゆる規模のコードベースのための、高速でスケーラブルでユーザーフレンドリーなビルドシステムです。<div><sub>Stars: 3.3k / Last Update: 2024-10-04 / Initial Date: 2012-12-17</sub></div><div><sub>Stars: 3.3k / Last Update: 2024-10-05 / Initial Date: 2012-12-17</sub></div>
* [tracemachina/nativelink](https://github.com/tracemachina/nativelink) - [NativeLink](https://www.nativelink.com)は、[Buck2](https://buck2.build/)、[Bazel](https://bazel.build/)、[Pants](https://www.pantsbuild.org/)などのクライアントビルドシステム用にRubstで書かれたバックエンドリモート実行プラットフォームです。[[OpenSSFスコアカード](https://api.securityscorecards.dev/projects/github.com/TraceMachina/nativelink/badge)](https://securityscorecards.dev/viewer/?uri=github.com/TraceMachina/nativelink)[[OpenSSFベストプラクティス](https://www.bestpractices.dev/projects/8050/badge)](https://www.bestpractices.dev/projects/8050) [![Slack](https://img.shields.io/badge/slack--channel-blue?logo=slack)](https://nativelink.slack.com/join/shared_invite/zt-281qk1ho0-krT7HfTUIYfQMdwflRuq7A#/shared-invite/email)<div><sub>Stars: 1.1k / Last Update: 2024-10-04 / Initial Date: 2020-12-24</sub></div><div><sub>Stars: 1.1k / Last Update: 2024-10-04 / Initial Date: 2020-12-24</sub></div>

### Debugging

* GDB
  * [gdbgui](https://github.com/cs01/gdbgui) - C、C++、Rust、goをデバッグするためのブラウザベースのgdbフロントエンド。<div><sub>Stars: 9.9k / Last Update: 2024-03-11 / Initial Date: 2016-10-27</sub></div>
* [kxxt/tracexec](https://github.com/kxxt/tracexec) [[tracexec](https://crates.io/crates/tracexec)] - execve{,at}とpre-exec動作のトレーサー、デバッガー用ランチャー。<div><sub>Stars: 264 / Last Update: 2024-09-28 / Initial Date: 2023-10-22</sub></div>
* LLDB
  * [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) - Visual Studio Code](https://code.visualstudio.com/)用のLLDB拡張。

### Deployment

* Docker
  * [emk/rust-musl-builder](https://github.com/emk/rust-musl-builder) - musl-libcとmusl-gccを使用した静的Rustバイナリのコンパイル用Dockerイメージ。<div><sub>Stars: 1.5k / Last Update: 2024-05-04 / Initial Date: 2016-04-17</sub></div>
  * [kpcyrd/mini-docker-rust](https://github.com/kpcyrd/mini-docker-rust) - 非常に小さな錆びたドッカーイメージのためのプロジェクト例<div><sub>Stars: 215 / Last Update: 2024-01-07 / Initial Date: 2017-04-29</sub></div>
  * [LukeMathWalker/cargo-chef](https://github.com/LukeMathWalker/cargo-chef) - Dockerビルド間のリモート依存関係のコンパイルをキャッシュするためのツールとビルド済みイメージ。<div><sub>Stars: 1.7k / Last Update: 2024-09-23 / Initial Date: 2020-10-19</sub></div>
  * [rust-cross/rust-musl-cross](https://github.com/rust-cross/rust-musl-cross) - musl-crossを使って静的なRustバイナリをコンパイルするためのDockerイメージ [![Build](https://github.com/rust-cross/rust-musl-cross/workflows/Build/badge.svg)](https://github.com/rust-cross/rust-musl-cross/actions?query=workflow%3ABuild)<div><sub>Stars: 625 / Last Update: 2024-10-02 / Initial Date: 2017-10-11</sub></div>
  * [rust-lang-nursery/docker-rust](https://github.com/rust-lang/docker-rust) - 公式Rust Dockerイメージ<div><sub>Stars: 438 / Last Update: 2024-09-05 / Initial Date: 2017-08-02</sub></div>
  * [Stavrospanakakis/is_ready](https://github.com/Stavrospanakakis/is_ready) - 複数のサービスが利用可能になるのを待つ ![Build](https://github.com/Stavrospanakakis/is_ready/actions/workflows/release.yml/badge.svg)<div><sub>Stars: 124 / Last Update: 2024-09-30 / Initial Date: 2023-06-25</sub></div>
* Heroku
* [MarcoIeni/release-plz](https://github.com/MarcoIeni/release-plz) [[release-plz](https://crates.io/crates/release-plz)] - CIからクレートをリリースし、変更ログ生成とセンバチェックを行う。[ビルドバッジ](https://github.com/MarcoIeni/release-plz/workflows/CI/badge.svg)](https://github.com/MarcoIeni/release-plz/actions)<div><sub>Stars: 794 / Last Update: 2024-10-03 / Initial Date: 2021-12-19</sub></div>

### Embedded

[Rust Embedded](https://rust-embedded.org/) focuses on improving the end-to-end experience of using Rust in resource-constrained environments and non-traditional platforms. See [awesome-embedded-rust](https://github.com/rust-embedded/awesome-embedded-rust) for a curated, and more extended list of embedded Rust resources.

* Arduino
* Cross compiling
* Espressif
  * [esp-rs](https://github.com/esp-rs) - エスプレシフ・システムズが製造するさまざまなSoCやモジュールでプログラミング言語「Rust」を使用できるようにするコミュニティ・プロジェクトが数多く存在する。
* Firmware
  * [oreboot/oreboot](https://github.com/oreboot/oreboot) - orebootはcorebootのフォークで、C言語が取り除かれ、Rustで書かれている。<div><sub>Stars: 1.6k / Last Update: 2024-08-14 / Initial Date: 2019-03-04</sub></div>
* nRF
  * [nrf-rs/nrf-hal](https://github.com/nrf-rs/nrf-hal) - nRFデバイス・ファミリーのためのRust HAL<div><sub>Stars: 504 / Last Update: 2024-08-30 / Initial Date: 2018-08-24</sub></div>

### FFI


* C
  * [mozilla/cbindgen](https://github.com/mozilla/cbindgen) - Rust のソースファイルから C のヘッダファイルを生成します。Gecko for WebRender で使用されています。<div><sub>Stars: 2.4k / Last Update: 2024-08-17 / Initial Date: 2017-04-12</sub></div>
* C#
  * [csbindgen](https://github.com/Cysharp/csbindgen) - RustソースファイルのC#バインディングを生成します。<div><sub>Stars: 680 / Last Update: 2024-08-15 / Initial Date: 2023-02-26</sub></div>
* C++
  * [dtolnay/cxx](https://github.com/dtolnay/cxx) - RustとC++の安全な相互運用 [![ビルド・バッジ]](https://img.shields.io/badge/github-dtolnay/cxx-8da0cb?style=for-the-badge&labelColor=555555&logo=github)](https://github.com/dtolnay/cxx)<div><sub>Stars: 5.8k / Last Update: 2024-09-20 / Initial Date: 2019-12-27</sub></div>
  * [dtolnay/cxx](https://github.com/dtolnay/cxx) - RustとC++の安全な相互運用 [![ビルド・バッジ]](https://img.shields.io/badge/github-dtolnay/cxx-8da0cb?style=for-the-badge&labelColor=555555&logo=github)](https://github.com/dtolnay/cxx)<div><sub>Stars: 5.8k / Last Update: 2024-09-20 / Initial Date: 2019-12-27</sub></div>
  * [rust-cpp](https://crates.io/crates/cpp) - C++コードを直接Rustに埋め込む。[ビルド状況](https://ci.appveyor.com/api/projects/status/uu76vmcrwnjqra0u/branch/master?svg=true)](https://ci.appveyor.com/project/mystor/rust-cpp/branch/master)
  * [rust-lang/rust-bindgen](https://github.com/rust-lang/rust-bindgen) - Rustバインディングジェネレーター<div><sub>Stars: 4.4k / Last Update: 2024-10-03 / Initial Date: 2016-06-22</sub></div>
* Erlang
  * [rusterlium/rustler](https://github.com/rusterlium/rustler) - ErlangのNIF関数を作るための安全なRustブリッジ<div><sub>Stars: 4.3k / Last Update: 2024-10-01 / Initial Date: 2015-08-18</sub></div>
* Java
  * [j4rs](https://crates.io/crates/j4rs) - RustからJavaを使う
  * [jni](https://crates.io/crates/jni) - JavaからRustを使う
  * [jni-sys](https://crates.io/crates/jni-sys) - jni.hに対応するRust定義
  * [rucaja](https://crates.io/crates/rucaja) - RustからJavaを使う
* Lua
  * [mlua-rs/mlua](https://github.com/mlua-rs/mlua) - 高レベルの Lua 5.4/5.3/5.2/5.1（LuaJIT を含む）と Roblox Luau の Rust へのバインディングと非同期/待機のサポート [![ビルドバッジ]](https://github.com/mlua-rs/mlua/workflows/CI/badge.svg)](https://github.com/mlua-rs/mlua/actions)<div><sub>Stars: 1.6k / Last Update: 2024-10-04 / Initial Date: 2019-11-30</sub></div>
  * [tickbh/td_rlua](https://github.com/tickbh/td_rlua) [[td_rlua](https://crates.io/crates/td_rlua)] - Rust用ゼロコスト高レベルlua 5.3ラッパー<div><sub>Stars: 53 / Last Update: 2024-04-10 / Initial Date: 2016-03-31</sub></div>
  * [tomaka/hlua](https://github.com/tomaka/hlua) - Luaとのインターフェース用Rustライブラリ<div><sub>Stars: 507 / Last Update: 2024-07-27 / Initial Date: 2014-06-05</sub></div>
* mruby
* Node.js
  * [infinyon/node-bindgen](https://github.com/infinyon/node-bindgen) - Rustを使ってnodejsモジュールを生成する簡単な方法<div><sub>Stars: 521 / Last Update: 2024-09-06 / Initial Date: 2020-02-04</sub></div>
  * [neon-bindings/neon](https://github.com/neon-bindings/neon) - 安全で高速なネイティブNode.jsモジュールを書くためのRustバインディング<div><sub>Stars: 8.0k / Last Update: 2024-10-03 / Initial Date: 2015-09-19</sub></div>
  * [zhangyuang/node-ffi-rs](https://github.com/zhangyuang/node-ffi-rs) - RustとN-APIで書かれたモジュールは、Node.jsのためのインターフェース（FFI）機能を提供します。<div><sub>Stars: 165 / Last Update: 2024-09-22 / Initial Date: 2023-07-17</sub></div>
* Objective-C
* PHP
  * [phper-framework/phper](https://github.com/phper-framework/phper) - 可能な限り純粋で安全なRustを使ってPHPの拡張機能を書くことを可能にするフレームワーク。<div><sub>Stars: 290 / Last Update: 2024-08-08 / Initial Date: 2019-12-11</sub></div>
* Prolog
  * [mthom/scryer-prolog](https://github.com/mthom/scryer-prolog/) - Scryer Prologは、Rustで書かれたフリーソフトウェアのISO Prologシステムです。<div><sub>Stars: 2.0k / Last Update: 2024-09-30 / Initial Date: 2016-10-29</sub></div>
* Python
  * [dgrunwald/rust-cpython](https://github.com/dgrunwald/rust-cpython) - Pythonバインディング<div><sub>Stars: 1.8k / Last Update: 2024-08-14 / Initial Date: 2015-01-05</sub></div>
  * [PyO3/PyO3](https://github.com/PyO3/PyO3) - PythonインタプリタのRustバインディング<div><sub>Stars: 12.1k / Last Update: 2024-10-05 / Initial Date: 2017-05-13</sub></div>
  * [RustPython](https://github.com/RustPython/RustPython) - Rustで書かれたPythonインタプリタ [![ビルド状況]](https://github.com/RustPython/RustPython/workflows/CI/badge.svg)](https://github.com/RustPython/RustPython/actions?query=workflow%3ACI)<div><sub>Stars: 19.0k / Last Update: 2024-09-29 / Initial Date: 2018-05-28</sub></div>
* Ruby
  * [danielpclark/rutie](https://github.com/danielpclark/rutie) - Rustで書かれたネイティブのRuby拡張機能、またはその逆。<div><sub>Stars: 945 / Last Update: 2024-06-25 / Initial Date: 2018-06-19</sub></div>
* Web Assembly
  * [rhysd/wain](https://github.com/rhysd/wain) - wain：WebAssembly INterpreter from scratch in Safe Rust with zero dependency [![build badge](https://github.com/rhysd/wain/workflows/CI/badge.svg?branch=master&event=push)](https://github.com/rhysd/wain/actions?query=workflow%3ACI+branch%3Amaster+event%3Apush)<div><sub>Stars: 431 / Last Update: 2024-07-22 / Initial Date: 2020-02-18</sub></div>
  * [rustwasm/wasm-bindgen](https://github.com/rustwasm/wasm-bindgen) - wasmモジュールとJSの高レベルな相互作用を促進するプロジェクト。<div><sub>Stars: 7.7k / Last Update: 2024-09-28 / Initial Date: 2017-12-18</sub></div>
  * [rustwasm/wasm-pack](https://github.com/rustwasm/wasm-pack) - package: :sparkles: ワズムをパッケージしてnpmに公開する！<div><sub>Stars: 6.2k / Last Update: 2024-09-03 / Initial Date: 2018-02-12</sub></div>

### Formatters

* [dprint](https://github.com/dprint/dprint) - プラグイン可能で設定可能なコード・フォーマット・プラットフォーム [![ビルド・バッジ]](https://github.com/dprint/dprint/workflows/CI/badge.svg)](https://github.com/dprint/dprint/actions?query=workflow%3ACI)<div><sub>Stars: 3.2k / Last Update: 2024-09-09 / Initial Date: 2019-06-16</sub></div>
* [rustfmt](https://github.com/rust-lang/rustfmt) - Rustチームによって保守され、cargoに含まれているRustコードフォーマッタ。<div><sub>Stars: 6.0k / Last Update: 2024-09-27 / Initial Date: 2015-03-07</sub></div>

### IDEs

See also [Are we (I)DE yet?](https://areweideyet.com/) and [Rust Tools](https://www.rust-lang.org/tools).

  * [Eclipse](https://www.eclipse.org/)
    * [Eclipse Corrosion](https://github.com/eclipse-corrosion/corrosion) - Eclipse IDE用のRust開発プラグイン。Rust Analyzer言語サーバー、Cargoランナー、gdbデバッガーとの統合により、豊富なエディション体験を提供します。<div><sub>Stars: 223 / Last Update: 2024-09-12 / Initial Date: 2017-12-04</sub></div>
  * [Emacs](https://www.gnu.org/software/emacs/)
    * [flycheck-rust](https://github.com/flycheck/flycheck-rust) - フライチェック](https://github.com/flycheck/flycheck)のRustサポート<div><sub>Stars: 122 / Last Update: 2024-09-18 / Initial Date: 2014-08-13</sub></div>
    * [flycheck-rust](https://github.com/flycheck/flycheck-rust) - フライチェック](https://github.com/flycheck/flycheck)のRustサポート<div><sub>Stars: 122 / Last Update: 2024-09-18 / Initial Date: 2014-08-13</sub></div>
    * [rust-mode](https://github.com/rust-lang/rust-mode) - ラスト・メジャー・モード<div><sub>Stars: 1.1k / Last Update: 2024-09-19 / Initial Date: 2015-01-29</sub></div>
    * [rustic](https://github.com/brotzeit/rustic) - Emacs用Rust開発環境 [![ビルドバッジ]](https://github.com/brotzeit/rustic/workflows/CI/badge.svg)](https://github.com/brotzeit/rustic/actions?query=workflow%3ACI)<div><sub>Stars: 726 / Last Update: 2024-08-23 / Initial Date: 2017-12-07</sub></div>
  * [gitpod.io](https://gitpod.io) - Rust Language ServerをベースにRustをフルサポートしたオンラインIDE
  * [gnome-builder](https://wiki.gnome.org/Apps/Builder) - バージョン3.22.2からRustとCargoをネイティブサポート
  * [IntelliJ](https://www.jetbrains.com/idea/)
    * [intellij-rust/intellij-rust](https://github.com/intellij-rust/intellij-rust) - IntelliJ Platform用Rustプラグイン<div><sub>Stars: 4.5k / Last Update: 2024-03-13 / Initial Date: 2015-09-16</sub></div>
  * [Kakoune](http://kakoune.org/)
    * [kakoune-lsp](https://github.com/kakoune-lsp/kakoune-lsp/) - [LSP](https://microsoft.github.io/language-server-protocol/)クライアント。Rustで実装され、すぐにrlsをサポートする。<div><sub>Stars: 599 / Last Update: 2024-10-03 / Initial Date: 2018-03-28</sub></div><div><sub>Stars: 599 / Last Update: 2024-10-03 / Initial Date: 2018-03-28</sub></div>
  * [lapce](https://github.com/lapce/lapce) - Rustで書かれた高速でパワフルなコードエディター。[ビルドバッジ](https://github.com/lapce/lapce/actions/workflows/release.yml/badge.svg)](https://github.com/lapce/lapce/actions/workflows/release.yml)<div><sub>Stars: 34.3k / Last Update: 2024-10-05 / Initial Date: 2018-02-06</sub></div>
  * [Ride](https://github.com/madeso/ride) - Rust IDE<div><sub>Stars: 174 / Last Update: 2024-03-13 / Initial Date: 2015-01-30</sub></div>
  * [RustRover](https://www.jetbrains.com/rust/) - JetBrains社による強力なRust IDE、個人の非商用利用は無料
  * [Sublime Text](https://www.sublimetext.com/)
    * [rust-lang/rust-enhanced](https://github.com/rust-lang/rust-enhanced) - オフィシャル・ラスト・パッケージ<div><sub>Stars: 782 / Last Update: 2024-09-06 / Initial Date: 2014-01-08</sub></div>
  * [Vim](https://vim.sourceforge.io/) - どこにでもあるテキストエディタ
    * [crates.nvim](https://github.com/Saecki/crates.nvim) - crates.ioの依存関係を管理するためのプラグイン。<div><sub>Stars: 857 / Last Update: 2024-09-26 / Initial Date: 2021-08-24</sub></div>
  * Visual Studio
  * [Visual Studio Code](https://code.visualstudio.com/)
    * [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) - LLDBエクステンション
    * [Dependi](https://marketplace.visualstudio.com/items?itemName=fill-labs.dependi) - 依存関係を簡単に管理
    * [Even Better TOML](https://marketplace.visualstudio.com/items?itemName=tamasfe.even-better-toml) - vscodeでのTOMLサポート
    * [Prettier - コードフォーマッタ (Rust)](https://marketplace.visualstudio.com/items?itemName=jinxdash.prettier-rust)
    * [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer) - RLSに代わるサビ言語サーバー

### Profiling

* [bheisler/criterion.rs](https://github.com/bheisler/criterion.rs) - 統計に基づくベンチマーク・ライブラリ<div><sub>Stars: 4.5k / Last Update: 2024-09-17 / Initial Date: 2014-05-26</sub></div>
* [Divan](https://github.com/nvzqz/divan) - アロケーション・プロファイリングを備えたシンプルかつ強力なベンチマーク・ライブラリ<div><sub>Stars: 924 / Last Update: 2024-07-18 / Initial Date: 2023-06-30</sub></div>
* FlameGraphs
* [sharkdp/hyperfine](https://github.com/sharkdp/hyperfine) - コマンドラインベンチマークツール<div><sub>Stars: 21.7k / Last Update: 2024-09-01 / Initial Date: 2018-01-13</sub></div>

### Services

* [deps.rs](https://github.com/deps-rs/deps.rs) - 古い依存関係や安全でない依存関係を検出する<div><sub>Stars: 424 / Last Update: 2024-09-20 / Initial Date: 2018-01-26</sub></div>
* [docs.rs](https://docs.rs) - クレートの自動ドキュメント生成

### Static analysis

[[assert](https://crates.io/keywords/assert), [static](https://crates.io/keywords/static)]

* [facebookexperimental/MIRAI](https://github.com/facebookexperimental/mirai) - Rustの中間レベル中間表現(MIR)上で動作する抽象インタープリター[![継続的インテグレーション]](https://github.com/facebookexperimental/mirai/actions/workflows/rust.yml/badge.svg)](https://github.com/facebookexperimental/mirai/actions/workflows/rust.yml)<div><sub>Stars: 1.0k / Last Update: 2024-08-22 / Initial Date: 2018-11-06</sub></div>
* [static_assertions](https://crates.io/crates/static_assertions) - コンパイル時のアサーションにより、不変量が満たされていることを保証する。

### Testing

[[test](https://crates.io/keywords/test), [testing](https://crates.io/keywords/testing)]

* Code Coverage
  * [tarpaulin](https://crates.io/crates/cargo-tarpaulin) - コード・カバレッジ・ツール
* Continuous Integration
* Frameworks and Runners
  * [AlKass/polish](https://github.com/AlKass/polish) - ミニテスト／テスト駆動フレームワーク [![クレート・パッケージ・ステータス]](https://img.shields.io/crates/v/polish.svg)](https://crates.io/crates/polish)<div><sub>Stars: 52 / Last Update: 2024-07-31 / Initial Date: 2017-04-29</sub></div>
  * [cargo-dinghy](https://crates.io/crates/cargo-dinghy/) - スマートフォンやその他の小型プロセッサ・デバイス上でのライブラリ・テストやベンチの実行を簡素化するためのカーゴ拡張機能。
  * [cucumber](https://crates.io/crates/cucumber) [![Latest Version](https://img.shields.io/crates/v/cucumber.svg)](https://crates.io/crates/cucumber) - Rust用のCucumberテスト・フレームワークの実装。完全ネイティブで、外部のテストランナーや依存関係はありません。[ビルド状況](https://github.com/cucumber-rs/cucumber/workflows/CI/badge.svg?branch=master)](https://github.com/cucumber-rs/cucumber)<div><sub>Stars: 568 / Last Update: 2024-09-09 / Initial Date: 2018-06-17</sub></div>
  * [d-e-s-o/test-log](https://github.com/d-e-s-o/test-log) [[test-log](https://crates.io/crates/test-log)] - テストを実行する前にロギングやトレースのインフラストラクチャを初期化する `#[test]` 属性を置き換えたものです。[GitHubワークフローのステータス](https://github.com/d-e-s-o/test-log/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/d-e-s-o/test-log/actions/workflows/test.yml)<div><sub>Stars: 109 / Last Update: 2024-09-07 / Initial Date: 2019-04-28</sub></div>
  * [GoogleTest Rust](https://crates.io/crates/googletest) - C++テスト・ライブラリに基づく強力なテスト・アサーション・フレームワーク GoogleTest [![ビルド・ステータス](https://github.com/google/googletest-rust/workflows/CI/badge.svg)](https://github.com/google/googletest-rust/actions?query=workflow%3ACI+branch%3Amain)
  * [rlt](https://github.com/wfxr/rlt) - リアルタイムにtuiをサポートするユニバーサル負荷テストフレームワーク。<div><sub>Stars: 138 / Last Update: 2024-08-26 / Initial Date: 2024-03-23</sub></div>
  * [rstest](https://crates.io/crates/rstest) - フィクスチャベースのテストフレームワーク [![Build Status](https://github.com/la10736/rstest/workflows/Test/badge.svg?branch=master)](https://github.com/la10736/rstest/actions)
  * [speculate](https://crates.io/crates/speculate) - RSpecに着想を得た最小限のテスト・フレームワーク
* Mocking and Test Data
  * [asomers/mockall](https://github.com/asomers/mockall) [[mockall](https://crates.io/crates/mockall)] - 強力なモック・オブジェクト・ライブラリ。[Cirrusビルド状況](https://api.cirrus-ci.com/github/asomers/mockall.svg)](https://cirrus-ci.com/github/asomers/mockall)<div><sub>Stars: 1.5k / Last Update: 2024-09-29 / Initial Date: 2019-02-07</sub></div>
  * [fake-rs](https://github.com/cksac/fake-rs) - 偽データを生成するためのライブラリ<div><sub>Stars: 894 / Last Update: 2024-10-04 / Initial Date: 2016-06-29</sub></div>
  * [goldenfile](https://github.com/calder/rust-goldenfile) [[goldenfile](https://crates.io/crates/goldenfile)] - Goldenfile テスト用のシンプルな API を提供するライブラリ。<div><sub>Stars: 38 / Last Update: 2024-09-08 / Initial Date: 2016-12-01</sub></div>
  * [httpmock](https://github.com/alexliesenfeld/httpmock) - HTTPモッキング [![ビルド・バッジ]](https://dev.azure.com/alexliesenfeld/httpmock/_apis/build/status/alexliesenfeld.httpmock?branchName=master)](https://dev.azure.com/alexliesenfeld/httpmock/_build/latest?definitionId=2&branchName=master)<div><sub>Stars: 472 / Last Update: 2024-10-02 / Initial Date: 2019-09-09</sub></div>
  * [mockiato](https://crates.io/crates/mockiato) - 不安定なRust 2018のための、厳密だが親しみやすいモッキング・ライブラリ
  * [mockito](https://crates.io/crates/mockito) - HTTPモッキング
  * [nrxus/faux](https://github.com/nrxus/faux/) [![Latest Version](https://img.shields.io/crates/v/faux.svg)](https://crates.io/crates/faux) - 構造体からモックを作成するライブラリ。![ビルド](https://github.com/nrxus/faux/workflows/test/badge.svg?branch=master)<div><sub>Stars: 419 / Last Update: 2024-03-26 / Initial Date: 2019-08-15</sub></div>
  * [synth](https://github.com/shuttle-hq/synth/) - データベースのデータを宣言的に生成する。[ビルド](https://github.com/shuttle-hq/synth/actions/workflows/synth-test.yml/badge.svg)](https://github.com/shuttle-hq/synth)<div><sub>Stars: 1.4k / Last Update: 2024-09-27 / Initial Date: 2020-08-09</sub></div>
  * [synth](https://github.com/shuttle-hq/synth/) - データベースのデータを宣言的に生成する。[ビルド](https://github.com/shuttle-hq/synth/actions/workflows/synth-test.yml/badge.svg)](https://github.com/shuttle-hq/synth)<div><sub>Stars: 1.4k / Last Update: 2024-09-27 / Initial Date: 2020-08-09</sub></div>
* Mutation Testing
  * [cargo-mutants](https://github.com/sourcefrog/cargo-mutants) [[cargo-mutants](https://crates.io/crates/cargo-mutants)] - 変異を注入することで、テストが不十分なコードを見つける。[ビルドバッジ](https://github.com/sourcefrog/cargo-mutants/actions/workflows/tests.yml/badge.svg?branch=main&event=push)](https://github.com/sourcefrog/cargo-mutants/actions/workflows/tests.yml?query=branch%3Amain)<div><sub>Stars: 547 / Last Update: 2024-10-04 / Initial Date: 2021-09-08</sub></div>
* Property Testing and Fuzzing
  * [proptest](https://crates.io/crates/proptest) - Python用[Hypothesis](https://hypothesis.works/)フレームワークにインスパイアされた特性検査フレームワーク。
  * [quickcheck](https://crates.io/crates/quickcheck) - クイックチェック](https://wiki.haskell.org/Introduction_to_QuickCheck1)のサビ実装。
  * [rust-fuzz/afl.rs](https://github.com/rust-fuzz/afl.rs) - AFL](https://lcamtuf.coredump.cx/afl/)を使ったRustファザー。<div><sub>Stars: 1.6k / Last Update: 2024-09-30 / Initial Date: 2015-04-08</sub></div>

### Transpiling

* [immunant/c2rust](https://github.com/immunant/c2rust) - Clang/LLVMの上に構築されたCからRustへのトランスレータとクロスチェッカ。<div><sub>Stars: 4.0k / Last Update: 2024-09-24 / Initial Date: 2018-04-20</sub></div>

## Libraries


### Artificial Intelligence

#### Genetic algorithms


#### Machine learning

See [[Machine learning](https://crates.io/keywords/machine-learning)]

See also [About Rust’s Machine Learning Community](https://medium.com/@autumn_eng/about-rust-s-machine-learning-community-4cda5ec8a790#.hvkp56j3f) and [Are we learning yet?](https://www.arewelearningyet.com).

* [burn](https://github.com/tracel-ai/burn) - 柔軟で包括的なディープラーニングフレームワーク。<div><sub>Stars: 8.5k / Last Update: 2024-10-04 / Initial Date: 2022-07-18</sub></div>
* [coreylowman/dfdx](https://github.com/coreylowman/dfdx) - Rustのユニークな機能の多くを活用した、CUDAアクセラレーションによる機械学習フレームワーク。![Crates.io](https://img.shields.io/crates/v/dfdx)<div><sub>Stars: 1.7k / Last Update: 2024-07-23 / Initial Date: 2021-10-12</sub></div>
* [guillaume-be/rust-bert](https://github.com/guillaume-be/rust-bert) [[rust_bert](https://crates.io/crates/rust_bert)] - すぐに使えるNLPパイプラインと言語モデル<div><sub>Stars: 2.6k / Last Update: 2024-09-29 / Initial Date: 2020-01-25</sub></div>
* [huggingface/candle](https://github.com/huggingface/candle) [[candle-core](https://crates.io/crates/candle-core)] - 使いやすさとパフォーマンス（GPUサポートを含む）を重視した最小主義のMLフレームワーク。<div><sub>Stars: 15.4k / Last Update: 2024-10-04 / Initial Date: 2023-06-19</sub></div>
* [huggingface/tokenizers](https://github.com/huggingface/tokenizers) - Hugging Faceのトークナイザーは、モダンなNLPパイプラインのための（オリジナルの実装）Python用のバインディングを備えています。[ビルド状況](https://github.com/huggingface/tokenizers/workflows/Rust/badge.svg?branch=master)](https://github.com/huggingface/tokenizers/actions)<div><sub>Stars: 8.9k / Last Update: 2024-10-04 / Initial Date: 2019-11-01</sub></div>
* [LaurentMazare/tch-rs](https://github.com/LaurentMazare/tch-rs) - PyTorch 用のバインディング。<div><sub>Stars: 4.2k / Last Update: 2024-10-04 / Initial Date: 2019-02-16</sub></div>
* [perpetual-ml/perpetual](https://github.com/perpetual-ml/perpetual) [[perpetual](https://crates.io/crates/perpetual)] - ハイパーパラメータの最適化を必要としない自己汎化勾配ブースティング・マシン。<div><sub>Stars: 219 / Last Update: 2024-09-19 / Initial Date: 2024-05-20</sub></div>
* [rust-ml/linfa](https://github.com/rust-ml/linfa) - 機械学習のフレームワーク。<div><sub>Stars: 3.7k / Last Update: 2024-08-17 / Initial Date: 2018-04-05</sub></div>
* [smartcorelib/smartcore](https://github.com/smartcorelib/smartcore) - 機械学習ライブラリ [![ビルド状況](https://img.shields.io/circleci/build/github/smartcorelib/smartcore)](https://smartcorelib.org/)<div><sub>Stars: 698 / Last Update: 2024-08-05 / Initial Date: 2019-05-08</sub></div>
* [tensorflow/rust](https://github.com/tensorflow/rust) - TensorFlowのためのバインディング。<div><sub>Stars: 5.1k / Last Update: 2024-08-13 / Initial Date: 2016-02-05</sub></div>

#### OpenAI

* [64bit/async-openai](https://github.com/64bit/async-openai) [[async-openai](https://crates.io/crates/async-openai)] - OpenAPI仕様に基づいたOpenAI API用の人間工学的なRustバインディング。<div><sub>Stars: 1.1k / Last Update: 2024-09-26 / Initial Date: 2022-11-11</sub></div>
* [zurawiki/tiktoken-rs](https://github.com/zurawiki/tiktoken-rs) [[tiktoken-rs](https://crates.io/crates/tiktoken-rs)] - tiktokenを使ってOpenAIのモデルでテキストをトークン化するためのライブラリ。[CI](https://github.com/zurawiki/tiktoken-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/zurawiki/tiktoken-rs/actions/workflows/ci.yml)<div><sub>Stars: 245 / Last Update: 2024-08-14 / Initial Date: 2023-02-02</sub></div>

### Astronomy

[[astronomy](https://crates.io/keywords/astronomy)]

* [cds-astro/aladin-lite](https://github.com/cds-astro/aladin-lite) - さまざまな投影法による空間・惑星画像調査を視覚化するウェブ・アプリケーション<div><sub>Stars: 99 / Last Update: 2024-09-25 / Initial Date: 2017-09-06</sub></div>
* [fitsio](https://crates.io/crates/fitsio) - fitsインターフェイスライブラリ wrapping cfitsio

### Asynchronous

* [async-std](https://async.rs/) [[async-std](https://crates.io/crates/async-std)] - Rust標準ライブラリの非同期バージョン [![CI](https://github.com/async-rs/async-std/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/async-rs/async-std/actions/workflows/ci.yml)
* [igumnoff/gabriel2](https://github.com/igumnoff/gabriel2) [[gabriel2](https://crates.io/crates/gabriel2)] - Gabriel2：Tokioベースのアクターモデルライブラリ<div><sub>Stars: 24 / Last Update: 2024-07-12 / Initial Date: 2024-03-19</sub></div>
* [mio](https://github.com/tokio-rs/mio) - MIOは軽量なIOライブラリであり、OSの抽象化に対して可能な限りオーバーヘッドを追加しないことに重点を置いている。<div><sub>Stars: 6.3k / Last Update: 2024-10-03 / Initial Date: 2014-08-20</sub></div>
* [rust-lang/futures-rs](https://github.com/rust-lang/futures-rs) - ゼロコスト先物<div><sub>Stars: 5.4k / Last Update: 2024-10-04 / Initial Date: 2016-03-30</sub></div>
* [t3hmrman/async-dropper](https://github.com/t3hmrman/async-dropper) [[async-dropper](https://crates.io/crates/async-dropper)] - AsyncDrop`の実装<div><sub>Stars: 41 / Last Update: 2024-09-21 / Initial Date: 2023-07-26</sub></div>
* [tokio-rs/tokio](https://github.com/tokio-rs/tokio) - Rustプログラミング言語を使って、信頼性が高く、非同期で、スリムなアプリケーションを書くためのランタイム。<div><sub>Stars: 26.6k / Last Update: 2024-10-04 / Initial Date: 2016-09-09</sub></div>
* [tqwewe/kameo](https://github.com/tqwewe/kameo) - Tokioで構築されたフォールト・トレラントな非同期アクター<div><sub>Stars: 547 / Last Update: 2024-10-04 / Initial Date: 2024-03-29</sub></div>
* [Xudong-Huang/may](https://github.com/Xudong-Huang/may) - スタックフル・コルーチンライブラリ<div><sub>Stars: 1.9k / Last Update: 2024-09-18 / Initial Date: 2017-03-24</sub></div>

### Audio and Music

[[audio](https://crates.io/keywords/audio)]

* [hound](https://crates.io/crates/hound) - WAVエンコード/デコードライブラリ
* [insomnimus/nodi](https://github.com/insomnimus/nodi) [[nodi](https://crates.io/crates/nodi)] - MIDIファイルの再生と抽象化のためのライブラリ。[ビルドバッジ](https://github.com/insomnimus/nodi/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/insomnimus/nodi/actions)<div><sub>Stars: 21 / Last Update: 2024-08-27 / Initial Date: 2021-09-06</sub></div>
* [ozankasikci/rust-music-theory](https://github.com/ozankasikci/rust-music-theory) - 音楽理論ライブラリー<div><sub>Stars: 626 / Last Update: 2024-08-28 / Initial Date: 2020-01-15</sub></div>
* [pdeljanov/Symphonia](https://github.com/pdeljanov/Symphonia) - AAC、FLAC、MP3、MP4、OGG、Vorbis、WAVをサポートするオーディオデコードおよびメディアデマックスライブラリ。<div><sub>Stars: 2.3k / Last Update: 2024-10-03 / Initial Date: 2019-02-23</sub></div>
* [RustAudio](https://github.com/RustAudio)
  * [RustAudio/cpal](https://github.com/RustAudio/cpal) - 低レベルのクロスプラットフォームオーディオI/Oライブラリ。[アクションステータス](https://github.com/RustAudio/cpal/workflows/cpal/badge.svg?branch=master)](https://github.com/RustAudio/cpal/actions)<div><sub>Stars: 2.7k / Last Update: 2024-09-25 / Initial Date: 2014-12-11</sub></div>
  * [RustAudio/rodio](https://github.com/RustAudio/rodio) - オーディオ再生ライブラリ<div><sub>Stars: 1.7k / Last Update: 2024-10-04 / Initial Date: 2015-07-22</sub></div>
  * [RustAudio/rust-portaudio](https://github.com/RustAudio/rust-portaudio) - PortAudioバインディング<div><sub>Stars: 375 / Last Update: 2024-09-15 / Initial Date: 2013-09-05</sub></div>
* [Serial-ATA/lofty-rs](https://github.com/Serial-ATA/lofty-rs) [[lofty](https://crates.io/crates/lofty)] - 様々なオーディオフォーマットのメタデータを読み、編集するためのライブラリ [![ビルドバッジ]](https://github.com/Serial-ATA/lofty-rs/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Serial-ATA/lofty-rs/actions)<div><sub>Stars: 187 / Last Update: 2024-09-17 / Initial Date: 2021-04-04</sub></div>

### Authentication

* [constantoine/totp-rs](https://github.com/constantoine/totp-rs) [[totp-rs](https://crates.io/crates/totp-rs)] - TOTPベースのトークンを生成・検証する2faライブラリ ![ビルド状況](https://github.com/constantoine/totp-rs/workflows/Rust/badge.svg)<div><sub>Stars: 172 / Last Update: 2024-07-24 / Initial Date: 2020-04-11</sub></div>
* [Keats/jsonwebtoken](https://github.com/Keats/jsonwebtoken) - [JSONウェブトークン](https://en.wikipedia.org/wiki/JSON_Web_Token)ライブラリ<div><sub>Stars: 1.7k / Last Update: 2024-09-02 / Initial Date: 2015-11-01</sub></div><div><sub>Stars: 1.7k / Last Update: 2024-09-02 / Initial Date: 2015-11-01</sub></div>
* [oauth2](https://github.com/ramosbugs/oauth2-rs) - 拡張可能で強い型付けのOAuth2クライアントライブラリ<div><sub>Stars: 914 / Last Update: 2024-09-16 / Initial Date: 2014-07-02</sub></div>
* [oxide-auth](https://github.com/HeroicKatora/oxide-auth) - actixや他のフロントエンドと組み合わせて使用するOAuth2サーバーライブラリで、設定可能でプラグイン可能なバックエンドのセットを備えています[![ビルド状況]](https://api.cirrus-ci.com/github/HeroicKatora/oxide-auth.svg?branch=master)](https://cirrus-ci.com/github/HeroicKatora/oxide-auth)<div><sub>Stars: 685 / Last Update: 2024-08-19 / Initial Date: 2017-11-29</sub></div>
* [yup-oauth2](https://github.com/dermesser/yup-oauth2) - デバイス、インストール済み、およびサービスアカウントのフローを提供する oauth2 クライアントの実装。<div><sub>Stars: 219 / Last Update: 2024-08-06 / Initial Date: 2015-02-26</sub></div>

### Automotive

* [marcelbuesing/can-dbc](https://github.com/marcelbuesing/can-dbc) [[can-dbc](https://crates.io/crates/can-dbc)] - DBCフォーマットのパーサー<div><sub>Stars: 62 / Last Update: 2024-04-25 / Initial Date: 2018-09-30</sub></div>
* [mbr/socketcan](https://github.com/socketcan-rs/socketcan-rs) [[socketcan](https://crates.io/crates/socketcan)] - Linux SocketCAN ライブラリ<div><sub>Stars: 138 / Last Update: 2024-08-24 / Initial Date: 2016-05-08</sub></div>
* [Sensirion/lin-bus](https://github.com/Sensirion/lin-bus-rs) [[lin-bus](https://crates.io/crates/lin-bus)] - LINバスドライバの特性とプロトコルの実装 [![ビルドバッジ]](https://circleci.com/gh/Sensirion/lin-bus-rs.svg?style=svg)](https://app.circleci.com/pipelines/github/Sensirion/lin-bus-rs)<div><sub>Stars: 17 / Last Update: 2024-04-19 / Initial Date: 2018-06-13</sub></div>

### Bioinformatics

* [Rust-Bio](https://github.com/rust-bio) - バイオインフォマティクス・ライブラリー

### Caching

* [06chaynes/http-cache](https://github.com/06chaynes/http-cache) [[http-cache](https://crates.io/crates/http-cache)] - HTTPキャッシュ・ルールに従ったキャッシュ・ミドルウェア [![ビルド・バッジ]](https://github.com/06chaynes/http-cache/workflows/http-cache/badge.svg)](https://github.com/06chaynes/http-cache/actions/workflows/http-cache.yml)<div><sub>Stars: 66 / Last Update: 2024-07-08 / Initial Date: 2022-01-07</sub></div>
* [aisk/rust-memcache](https://github.com/aisk/rust-memcache) - Memcachedクライアント・ライブラリ<div><sub>Stars: 132 / Last Update: 2024-04-11 / Initial Date: 2013-07-10</sub></div>
* [al8n/stretto](https://github.com/al8n/stretto) - 高性能なスレッドセーフ・メモリバウンド・キャッシュ [![ビルド・バッジ]](https://github.com/al8n/stretto/actions/workflows/ci.yml/badge.svg)](https://github.com/al8n/stretto/actions/workflows/ci.yml)<div><sub>Stars: 412 / Last Update: 2024-05-04 / Initial Date: 2021-07-27</sub></div>
* [jaemk/cached](https://github.com/jaemk/cached) - シンプルな関数キャッシュ／メモ化<div><sub>Stars: 1.5k / Last Update: 2024-08-09 / Initial Date: 2017-04-02</sub></div>
* [moka-rs/moka](https://github.com/moka-rs/moka) - Java用Caffeineライブラリにインスパイアされた、高性能な同時キャッシュ・ライブラリ [![ビルド・バッジ]](https://github.com/moka-rs/moka/workflows/CI/badge.svg)](https://github.com/moka-rs/moka/actions/workflows/CI.yml)<div><sub>Stars: 1.6k / Last Update: 2024-09-16 / Initial Date: 2020-04-05</sub></div>
* [mozilla/sccache](https://github.com/mozilla/sccache/) - 共有コンパイル・キャッシュ、素晴らしいコンパイル<div><sub>Stars: 5.8k / Last Update: 2024-10-03 / Initial Date: 2016-04-26</sub></div>
* [zkat/cacache-rs](https://github.com/zkat/cacache-rs) - 非同期API用に最適化された、高性能で同時実行可能なコンテンツ・アドレス可能ディスク・キャッシュ [![バッジを作る]](https://github.com/zkat/cacache-rs/workflows/CI/badge.svg)](https://github.com/zkat/cacache-rs/actions/workflows/ci.yml)<div><sub>Stars: 525 / Last Update: 2024-06-25 / Initial Date: 2019-05-21</sub></div>

### Cloud

* AWS [[aws](https://crates.io/keywords/aws)]
  * [awslabs/aws-lambda-rust-runtime](https://github.com/awslabs/aws-lambda-rust-runtime) [[lambda_runtime](https://crates.io/crates/lambda_runtime)] - AWS Lambda用ランタイム [![ビルドバッジ]](https://github.com/awslabs/aws-lambda-rust-runtime/workflows/Rust/badge.svg)](https://github.com/awslabs/aws-lambda-rust-runtime/actions)<div><sub>Stars: 3.3k / Last Update: 2024-10-03 / Initial Date: 2018-11-08</sub></div>
  * [awslabs/aws-sdk-rust](https://github.com/awslabs/aws-sdk-rust) - 新しいAWS SDK<div><sub>Stars: 3.0k / Last Update: 2024-10-03 / Initial Date: 2021-04-12</sub></div>
* Load Balancer
* Multi Cloud
  * [Qovery/engine](https://github.com/Qovery/engine) - クラウドプロバイダーへのアプリケーション展開を数分で簡単にする抽象化レイヤーライブラリ<div><sub>Stars: 2.3k / Last Update: 2024-10-03 / Initial Date: 2020-10-21</sub></div>

### Command-line

* Argument parsing
  * [clap-rs](https://github.com/clap-rs/clap) [[clap](https://crates.io/crates/clap)] - 使いやすく、フル機能のコマンドライン引数パーサー<div><sub>Stars: 14.1k / Last Update: 2024-10-02 / Initial Date: 2015-02-25</sub></div>
  * [cliparser](https://crates.io/crates/cliparser) - シンプルなコマンドライン・パーサー。[ビルド・バッジ](https://github.com/sagiegurari/cliparser/workflows/CI/badge.svg?branch=master)](https://github.com/sagiegurari/cliparser/actions)
  * [google/argh](https://github.com/google/argh) [[argh](https://crates.io/crates/argh)] - コードサイズに最適化されたDeriveベースの引数パーサー [![ビルド・バッジ]](https://github.com/google/argh/workflows/Argh/badge.svg?branch=master)](https://github.com/google/argh/actions)<div><sub>Stars: 1.6k / Last Update: 2024-05-24 / Initial Date: 2020-01-30</sub></div>
  * [ksk001100/seahorse](https://github.com/ksk001100/seahorse) [[seahorse](https://crates.io/crates/seahorse)] - 最小限のCLIフレームワーク [![ビルド状況](https://github.com/ksk001100/seahorse/workflows/CI/badge.svg?branch=master)](https://github.com/ksk001100/seahorse/actions)<div><sub>Stars: 286 / Last Update: 2024-05-02 / Initial Date: 2019-12-09</sub></div>
* Data visualization
  * [nukesor/comfy-table](https://github.com/nukesor/comfy-table) [[comfy-table](https://crates.io/crates/comfy-table)] - CLIツール用の美しい動的テーブル。[ビルド状況](https://github.com/Nukesor/comfy-table/workflows/Tests/badge.svg?branch=master)](https://github.com/nukesor/comfy-table/actions)<div><sub>Stars: 937 / Last Update: 2024-09-30 / Initial Date: 2019-12-26</sub></div>
  * [zhiburt/tabled](https://github.com/zhiburt/tabled) [[tabled](https://crates.io/crates/tabled)] - 構造体や列挙型のテーブルをきれいに印刷するための使いやすいライブラリ。[ビルドステータス](https://github.com/zhiburt/tabled/actions/workflows/ci.yml/badge.svg)](https://github.com/zhiburt/tabled/actions)<div><sub>Stars: 2.0k / Last Update: 2024-08-11 / Initial Date: 2020-02-25</sub></div>
* Human-centered design
  * [rust-cli/human-panic](https://github.com/rust-cli/human-panic) [[human-panic](https://crates.io/crates/human-panic)] - 人間へのパニック・メッセージ<div><sub>Stars: 1.6k / Last Update: 2024-10-01 / Initial Date: 2018-04-15</sub></div>
* Line editor
  * [kkawakam/rustyline](https://github.com/kkawakam/rustyline) [[rustyline](https://crates.io/crates/rustyline)] - リードラインの実装<div><sub>Stars: 1.5k / Last Update: 2024-09-29 / Initial Date: 2015-03-20</sub></div>
* Other
  * [mgrachev/update-informer](https://github.com/mgrachev/update-informer) [[update-informer](https://crates.io/crates/update-informer)] - CLIアプリケーションの更新インフォーマー。Crates.ioとGitHub上の新しいバージョンをチェックします[![ビルドバッジ]](https://github.com/mgrachev/update-informer/workflows/CI/badge.svg)](https://github.com/mgrachev/update-informer/actions)<div><sub>Stars: 208 / Last Update: 2024-09-30 / Initial Date: 2021-12-08</sub></div>
* Pipeline
  * [imp/pager-rs](https://gitlab.com/imp/pager-rs) [[pager](https://crates.io/crates/pager)] - 出力を外部ページャーに通す
  * [oconnor663/duct.rs](https://github.com/oconnor663/duct.rs) [[duct](https://crates.io/crates/duct)] - サブプロセスパイプラインとIOリダイレクトのためのビルダー<div><sub>Stars: 819 / Last Update: 2024-08-01 / Initial Date: 2016-02-20</sub></div>
  * [rust-cli/rexpect](https://github.com/rust-cli/rexpect) [[rexpect](https://crates.io/crates/rexpect)] - ssh、ftp、passwdなどの対話型アプリケーションの自動化 [![CI](https://github.com/rust-cli/rexpect/actions/workflows/ci.yml/badge.svg)](https://github.com/rust-cli/rexpect/actions/workflows/ci.yml)<div><sub>Stars: 325 / Last Update: 2024-04-03 / Initial Date: 2017-06-02</sub></div>
  * [zhiburt/expectrl](https://github.com/zhiburt/expectrl) [[expectrl](https://crates.io/crates/expectrl)] - 擬似端末で対話型プログラムを制御するためのライブラリ [![ビルド・バッジ]](https://github.com/zhiburt/expectrl/actions/workflows/ci.yml/badge.svg)](https://github.com/zhiburt/expectrl/actions/workflows/ci.yml)<div><sub>Stars: 173 / Last Update: 2024-03-03 / Initial Date: 2021-06-25</sub></div>
* Progress
  * [console-rs/indicatif](https://github.com/console-rs/indicatif) [[indicatif](https://crates.io/crates/indicatif)] - 進捗状況をユーザーに示す<div><sub>Stars: 4.4k / Last Update: 2024-09-20 / Initial Date: 2017-04-23</sub></div>
  * [etienne-napoleone/spinach](https://github.com/etienne-napoleone/spinach) [[spinach](https://crates.io/crates/spinach)] - 実用的なスピナー。[CI](https://github.com/etienne-napoleone/spinach/actions/workflows/ci.yml/badge.svg)](https://github.com/etienne-napoleone/spinach/actions/workflows/ci.yml)<div><sub>Stars: 100 / Last Update: 2024-08-23 / Initial Date: 2022-03-22</sub></div>
  * [FGRibreau/spinners](https://github.com/FGRibreau/spinners) [[spinners](https://crates.io/crates/spinners)] - 60以上のエレガントな端末スピナー<div><sub>Stars: 542 / Last Update: 2023-10-05 / Initial Date: 2017-12-16</sub></div>
* Prompt
  * [mikaelmello/inquire](https://github.com/mikaelmello/inquire) [[inquire](https://crates.io/crates/inquire)] - 端末に対話的なプロンプトを表示するためのライブラリ。[ビルド状況](https://github.com/mikaelmello/inquire/actions/workflows/build.yml/badge.svg?branch=main)](https://github.com/mikaelmello/inquire/actions)<div><sub>Stars: 1.9k / Last Update: 2024-09-29 / Initial Date: 2021-06-15</sub></div>
  * [starship/starship](https://starship.rs/) [[starship](https://crates.io/crates/starship)] - あらゆるシェルのための、最小限の、高速な、そして非常にカスタマイズ可能なプロンプト [![Build status](https://github.com/starship/starship/workflows/Main%20workflow/badge.svg?branch=master)](https://github.com/starship/starship/actions)
  * [ynqa/promkit](https://github.com/ynqa/promkit) [[promkit](https://crates.io/crates/promkit)] - インタラクティブなコマンドラインツールを構築するためのツールキット [![ci]](https://github.com/ynqa/promkit/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/ynqa/promkit/actions/workflows/ci.yml)<div><sub>Stars: 258 / Last Update: 2024-09-25 / Initial Date: 2022-05-01</sub></div>
* Style
  * [colored](https://github.com/colored-rs/colored) [[colored](https://crates.io/crates/colored)] - カラーリングはとても簡単で、あなたはもうやり方を知っている！<div><sub>Stars: 1.7k / Last Update: 2024-07-20 / Initial Date: 2016-03-12</sub></div>
  * [console-rs/dialoguer](https://github.com/console-rs/dialoguer) [[dialoguer](https://crates.io/crates/dialoguer)] - コマンドライン・プロンプトやそれに類するもののためのライブラリ。<div><sub>Stars: 1.3k / Last Update: 2024-07-04 / Initial Date: 2017-05-09</sub></div>
  * [LukasKalbertodt/term-painter](https://github.com/LukasKalbertodt/term-painter) [[term-painter](https://crates.io/crates/term-painter)] - クロスプラットフォーム・スタイルのターミナル出力<div><sub>Stars: 78 / Last Update: 2024-02-26 / Initial Date: 2015-04-13</sub></div>
  * [SergioBenitez/yansi](https://github.com/SergioBenitez/yansi) [[yansi](https://crates.io/crates/yansi)] - シンプルなANSI端末カラーペイントライブラリ<div><sub>Stars: 245 / Last Update: 2024-03-13 / Initial Date: 2017-06-02</sub></div>
* TUI
  * BearLibTerminal
  * [ccbrown/iocraft](https://github.com/ccbrown/iocraft) [[iocraft](https://crates.io/crates/iocraft)] - 職人技で作られた美しいCLI、TUI、テキストベースのIOのためのクレート。[![Build status](https://github.com/ccbrown/iocraft/actions/workflows/commit.yaml/badge.svg?branch=main)](https://github.com/ccbrown/iocraft/actions) [![docs.rs](https://img.shields.io/docsrs/iocraft)](https://docs.rs/iocraft/)<div><sub>Stars: 299 / Last Update: 2024-10-04 / Initial Date: 2024-09-02</sub></div>
  * [gyscos/Cursive](https://github.com/gyscos/Cursive) [[cursive](https://crates.io/crates/cursive)] - リッチなTUIアプリケーションの構築<div><sub>Stars: 4.3k / Last Update: 2024-09-20 / Initial Date: 2015-05-09</sub></div>
  * ncurses
    * [jeaye/ncurses-rs](https://github.com/jeaye/ncurses-rs) [[ncurses](https://crates.io/crates/ncurses)] - [ncurses](https://www.gnu.org/software/ncurses/) バインディング<div><sub>Stars: 679 / Last Update: 2024-07-12 / Initial Date: 2013-09-30</sub></div><div><sub>Stars: 679 / Last Update: 2024-07-12 / Initial Date: 2013-09-30</sub></div>
  * [ratatui-org/ratatui](https://github.com/ratatui/ratatui) [[ratatui](https://crates.io/crates/ratatui)] - ターミナル・ユーザー・インターフェース(TUI)を作るためのライブラリ<div><sub>Stars: 10.2k / Last Update: 2024-10-05 / Initial Date: 2023-02-12</sub></div>
  * [redox-os/termion](https://github.com/redox-os/termion) [[termion](https://crates.io/crates/termion)] - ターミナル/TTY制御用バインドレス・ライブラリ<div><sub>Stars: 2.1k / Last Update: 2024-09-30 / Initial Date: 2016-03-06</sub></div>
  * [ruterm](https://crates.io/crates/ruterm) - TTY を扱うためのシンプルで小さなライブラリ
  * Termbox
  * [TimonPost/crossterm](https://github.com/crossterm-rs/crossterm) [[crossterm](https://crates.io/crates/crossterm)] - クロスプラットフォーム端末ライブラリ<div><sub>Stars: 3.2k / Last Update: 2024-08-26 / Initial Date: 2018-01-03</sub></div>

### Compression

* [7z](https://7-zip.org/7z.html)
  * [[sevenz-rust](https://crates.io/crates/sevenz-rust)] - 純粋な錆で書かれた7z解凍/圧縮機。
* [Brotli](https://opensource.googleblog.com/2015/09/introducing-brotli-new-compression.html)
  * [dropbox/rust-brotli](https://github.com/dropbox/rust-brotli) - オプションでstdlibを回避するBrotliデコンプレッサー<div><sub>Stars: 812 / Last Update: 2024-10-02 / Initial Date: 2016-04-17</sub></div>
* bzip2
* gzip
  * [zopfli](https://github.com/zopfli-rs/zopfli) [[zopfli](https://crates.io/crates/zopfli)] - Zopfli圧縮アルゴリズムの実装により、より高品質なdeflateまたはzlib圧縮を実現。<div><sub>Stars: 36 / Last Update: 2024-10-02 / Initial Date: 2022-03-05</sub></div>
* gzp
* miniz
  * [rust-lang/flate2-rs](https://github.com/rust-lang/flate2-rs) - [ミニッツ](https://code.google.com/archive/p/miniz) バインディング [![ビルド・バッジ](https://github.com/rust-lang/flate2-rs/workflows/CI/badge.svg?branch=master)](https://github.com/rust-lang/flate2-rs/actions)<div><sub>Stars: 893 / Last Update: 2024-09-26 / Initial Date: 2014-07-17</sub></div><div><sub>Stars: 893 / Last Update: 2024-09-26 / Initial Date: 2014-07-17</sub></div>
* tar
  * [alexcrichton/tar-rs](https://github.com/alexcrichton/tar-rs) - tar アーカイブの読み書き<div><sub>Stars: 624 / Last Update: 2024-09-26 / Initial Date: 2014-07-17</sub></div>
* zip
  * [zip-rs/zip2](https://github.com/zip-rs/zip2) [[zip](https://crates.io/crates/zip)] - ZIPアーカイブの読み書き<div><sub>Stars: 96 / Last Update: 2024-09-28 / Initial Date: 2023-04-23</sub></div>
* zstd
  * [gyscos/zstd-rs](https://github.com/gyscos/zstd-rs) - zstd圧縮ライブラリのRubバインディング<div><sub>Stars: 510 / Last Update: 2024-09-25 / Initial Date: 2016-02-19</sub></div>

### Computation

* [argmin-rs/argmin](https://github.com/argmin-rs/argmin) [[argmin](https://crates.io/crates/argmin)] - 最適化ライブラリ<div><sub>Stars: 992 / Last Update: 2024-10-03 / Initial Date: 2018-07-22</sub></div>
* [BLAS](https://en.wikipedia.org/wiki/Basic_Linear_Algebra_Subprograms) [[blas](https://crates.io/keywords/blas)]
* [dimforge/nalgebra](https://github.com/dimforge/nalgebra) - 低次元線形代数ライブラリ<div><sub>Stars: 4.0k / Last Update: 2024-10-01 / Initial Date: 2013-05-14</sub></div>
* [faer-rs](https://github.com/sarah-ek/faer-rs) [[faer](https://crates.io/crates/faer)] - ラストのための線形代数基礎<div><sub>Stars: 1.8k / Last Update: 2024-10-03 / Initial Date: 2022-06-13</sub></div>
* [GSL](http://www.gnu.org/software/gsl/)
  * [GuillaumeGomez/rust-GSL](https://github.com/GuillaumeGomez/rust-GSL) - GSLバインディング<div><sub>Stars: 190 / Last Update: 2024-04-15 / Initial Date: 2014-07-28</sub></div>
* [LAPACK](https://en.wikipedia.org/wiki/LAPACK)
* Parallel
* Science
  * [Axect/Peroxide](https://github.com/Axect/Peroxide) - 線形代数、数値解析、統計、機械学習ツールを純粋なRustで含むRust数値ライブラリ<div><sub>Stars: 509 / Last Update: 2024-10-05 / Initial Date: 2018-04-20</sub></div>
  * [cpmech/russell](https://github.com/cpmech/russell) - 数値数学、常微分方程式、特殊数学関数、高性能（スパース）線形代数のためのRust科学ライブラリ<div><sub>Stars: 109 / Last Update: 2024-09-29 / Initial Date: 2021-06-20</sub></div>
* Statrs
  * [statrs-dev/statrs](https://github.com/statrs-dev/statrs) - 頑健な統計計算ライブラリ<div><sub>Stars: 582 / Last Update: 2024-09-25 / Initial Date: 2016-03-11</sub></div>

### Concurrency

* [crossbeam-rs/crossbeam](https://github.com/crossbeam-rs/crossbeam) - 並列処理と低レベル並行処理のサポート<div><sub>Stars: 7.3k / Last Update: 2024-08-20 / Initial Date: 2015-05-13</sub></div>
* [orium/archery](https://github.com/orium/archery) [[archery](https://crates.io/crates/archery)] - Rc`/`Arc` ポインタ型を抽象化するライブラリ。[ビルドバッジ](https://github.com/orium/archery/workflows/CI/badge.svg)](https://github.com/orium/archery/actions?query=workflow%3ACI)<div><sub>Stars: 140 / Last Update: 2024-08-13 / Initial Date: 2019-02-20</sub></div>
* [Rayon](https://github.com/rayon-rs/rayon) - データ並列化ライブラリ<div><sub>Stars: 10.9k / Last Update: 2024-08-19 / Initial Date: 2014-10-02</sub></div>

### Configuration

* [Kixunil/configure_me](https://github.com/Kixunil/configure_me) [[configure_me](https://crates.io/crates/configure_me)] - アプリケーションの設定を簡単に処理するためのライブラリ<div><sub>Stars: 61 / Last Update: 2024-09-12 / Initial Date: 2018-04-26</sub></div>
* [mehcode/config-rs](https://github.com/mehcode/config-rs) [[config](https://crates.io/crates/config)] - レイヤー設定システム（12ファクターのアプリケーションを強力にサポート）。<div><sub>Stars: 2.6k / Last Update: 2024-07-31 / Initial Date: 2017-01-24</sub></div>
* [SergioBenitez/Figment](https://github.com/SergioBenitez/Figment) [[figment](https://crates.io/crates/figment)] - コンフィギュレーション・ライブラリーには詐欺がない。<div><sub>Stars: 621 / Last Update: 2024-09-13 / Initial Date: 2020-10-10</sub></div>
* [softprops/envy](https://github.com/softprops/envy) - envバーをtypesafe構造体にデシリアライズする [![Main](https://github.com/softprops/envy/actions/workflows/main.yml/badge.svg)](https://github.com/softprops/envy/actions/workflows/main.yml)<div><sub>Stars: 852 / Last Update: 2024-06-07 / Initial Date: 2016-06-28</sub></div>

### Cryptography

[[crypto](https://crates.io/keywords/crypto), [cryptography](https://crates.io/keywords/cryptography)]

* [arkworks-rs/circom-compat](https://github.com/arkworks-rs/circom-compat) - Groth16証明と証人生成のための、CircomのR1CSへのArkworksバインディング。<div><sub>Stars: 230 / Last Update: 2024-09-11 / Initial Date: 2021-07-26</sub></div>
* [briansmith/ring](https://github.com/briansmith/ring) - RustとBoringSSLの暗号化プリミティブを使用した、安全、高速、小規模な暗号。<div><sub>Stars: 3.7k / Last Update: 2024-10-04 / Initial Date: 2015-07-22</sub></div>
* [briansmith/webpki](https://github.com/briansmith/webpki) - Web PKI TLS X.509 証明書の検証。<div><sub>Stars: 461 / Last Update: 2024-02-18 / Initial Date: 2015-08-27</sub></div>
* [conradkleinespel/rooster](https://github.com/conradkleinespel/rooster) [[rooster](https://crates.io/crates/rooster)] - 端末で使えるシンプルなパスワード・マネージャー<div><sub>Stars: 151 / Last Update: 2023-12-05 / Initial Date: 2015-02-03</sub></div>
* [cossacklabs/themis](https://github.com/cossacklabs/themis) [[themis](https://crates.io/crates/themis)] - 典型的なデータ・セキュリティ・タスクを解決するための高レベル暗号ライブラリで、マルチプラットフォーム・アプリに最適です。[ビルド・バッジ](https://circleci.com/gh/cossacklabs/themis/tree/master.svg?style=shield)](https://app.circleci.com/pipelines/github/cossacklabs/themis)<div><sub>Stars: 1.9k / Last Update: 2024-09-12 / Initial Date: 2015-05-06</sub></div>
* [dalek-cryptography/curve25519-dalek](https://github.com/dalek-cryptography/curve25519-dalek) - カーブ25519作戦<div><sub>Stars: 884 / Last Update: 2024-09-30 / Initial Date: 2016-12-08</sub></div>
* [facebook/opaque-ke](https://github.com/facebook/opaque-ke) - 最近の[OPAQUE](https://datatracker.ietf.org/doc/draft-krawczyk-cfrg-opaque/)パスワード認証鍵交換の実装。[バッジを作る](https://github.com/facebook/opaque-ke/workflows/Rust%20CI/badge.svg?branch=master)](https://github.com/facebook/opaque-ke)<div><sub>Stars: 295 / Last Update: 2024-09-24 / Initial Date: 2020-06-04</sub></div>
* [facebook/opaque-ke](https://github.com/facebook/opaque-ke) - 最近の[OPAQUE](https://datatracker.ietf.org/doc/draft-krawczyk-cfrg-opaque/)パスワード認証鍵交換の実装。[バッジを作る](https://github.com/facebook/opaque-ke/workflows/Rust%20CI/badge.svg?branch=master)](https://github.com/facebook/opaque-ke)<div><sub>Stars: 295 / Last Update: 2024-09-24 / Initial Date: 2020-06-04</sub></div>
* [iddm/randomorg](https://github.com/iddm/randomorg) - random.orgクライアントライブラリ。[クレートバッジ](https://img.shields.io/crates/v/randomorg.svg)](https://crates.io/crates/randomorg)<div><sub>Stars: 8 / Last Update: 2023-12-05 / Initial Date: 2017-06-27</sub></div>
* [kornelski/rust-security-framework](https://github.com/kornelski/rust-security-framework) - セキュリティ・フレームワークのバインディング（OSXネイティブ）<div><sub>Stars: 238 / Last Update: 2024-09-20 / Initial Date: 2015-08-20</sub></div>
* [orion-rs/orion](https://github.com/orion-rs/orion) - このライブラリは、簡単で使い勝手の良い暗号を提供することを目的としている。使いやすい」とは、使いやすく悪用されにくい高レベルのAPIを公開することである。[テスト](https://github.com/orion-rs/orion/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/orion-rs/orion/actions/workflows/test.yml)<div><sub>Stars: 545 / Last Update: 2024-10-02 / Initial Date: 2018-02-06</sub></div>
* [racum/rust-djangohashers](https://github.com/racum/rust-djangohashers) [[djangohashers](https://crates.io/crates/djangohashers)] - Django Project で使われているパスワードプリミティブの移植版です。Django を必要とせず、パスワードのハッシュとバリデーションを Django のスタイルに従って行うだけです。<div><sub>Stars: 55 / Last Update: 2024-03-12 / Initial Date: 2015-11-13</sub></div>
* [RustCrypto/hashes](https://github.com/RustCrypto/hashes) - 暗号ハッシュ関数のコレクション<div><sub>Stars: 1.8k / Last Update: 2024-09-22 / Initial Date: 2016-11-18</sub></div>
* [rustls/rustls](https://github.com/rustls/rustls) - TLSの実装<div><sub>Stars: 5.9k / Last Update: 2024-10-04 / Initial Date: 2016-05-02</sub></div>
* [sfackler/rust-native-tls](https://github.com/sfackler/rust-native-tls) - ネイティブTLSライブラリ用バインディング<div><sub>Stars: 473 / Last Update: 2024-09-23 / Initial Date: 2016-04-17</sub></div>
* [sfackler/rust-openssl](https://github.com/sfackler/rust-openssl) - [OpenSSL](https://www.openssl.org/)バインディング<div><sub>Stars: 1.4k / Last Update: 2024-09-08 / Initial Date: 2013-12-28</sub></div><div><sub>Stars: 1.4k / Last Update: 2024-09-08 / Initial Date: 2013-12-28</sub></div>
* [sorairolake/abcrypt](https://github.com/sorairolake/abcrypt) [[abcrypt](https://crates.io/crates/abcrypt)] - シンプルでモダンでセキュアなファイル暗号化ライブラリ。[CI](https://github.com/sorairolake/abcrypt/workflows/CI/badge.svg?branch=develop)](https://github.com/sorairolake/abcrypt/actions?query=workflow%3ACI)<div><sub>Stars: 12 / Last Update: 2024-09-30 / Initial Date: 2023-08-25</sub></div>
* [sorairolake/scryptenc-rs](https://github.com/sorairolake/scryptenc-rs) [[scryptenc](https://crates.io/crates/scryptenc)] - scrypt暗号化データフォーマットの実装。[CI](https://github.com/sorairolake/scryptenc-rs/workflows/CI/badge.svg?branch=develop)](https://github.com/sorairolake/scryptenc-rs/actions?query=workflow%3ACI)<div><sub>Stars: 1 / Last Update: 2024-09-30 / Initial Date: 2022-10-09</sub></div>
* [w3f/schnorrkel](https://github.com/w3f/schnorrkel) - シュノアのVRFとリストレット・グループの署名<div><sub>Stars: 309 / Last Update: 2024-08-18 / Initial Date: 2018-11-13</sub></div>

### Data processing

* [amv-dev/yata](https://github.com/amv-dev/yata) - 高性能テクニカル分析ライブラリ [![ビルド状況](https://img.shields.io/github/workflow/status/amv-dev/yata/Rust?branch=master)](https://github.com/amv-dev/yata/actions?query=workflow%3ARust)<div><sub>Stars: 329 / Last Update: 2024-09-19 / Initial Date: 2020-09-17</sub></div>
* [bluss/ndarray](https://github.com/rust-ndarray/ndarray) - 配列ビュー、多次元スライス、効率的な操作を備えたN次元配列<div><sub>Stars: 3.6k / Last Update: 2024-09-26 / Initial Date: 2014-08-04</sub></div>
* [datafusion](https://github.com/apache/datafusion) - DataFusionは、Apache Arrowインメモリフォーマットを使用し、Rustで高品質なデータ中心システムを構築するための、非常に高速で拡張可能なクエリーエンジンです。<div><sub>Stars: 6.0k / Last Update: 2024-10-05 / Initial Date: 2021-04-17</sub></div>
* [pg_analytics](https://github.com/paradedb/paradedb/tree/dev/pg_analytics) - PostgreSQLの拡張機能で、Postgres内の分析クエリ処理を専用のOLAPデータベースに匹敵する性能レベルまで高速化します。
* [pg_lakehouse](https://github.com/paradedb/paradedb/tree/dev/pg_lakehouse) - AWSのS3/GCSのようなオブジェクトストアやDelta Lake/Icebergのようなテーブルフォーマット上でPostgreSQLを分析クエリーエンジンに変換するPostgreSQL拡張。
* [pola-rs/polars](https://github.com/pola-rs/polars) - 高速で完全なDataFrameライブラリ ![ビルドとテスト](https://github.com/pola-rs/polars/workflows/Build%20and%20test/badge.svg?branch=master)<div><sub>Stars: 29.6k / Last Update: 2024-10-05 / Initial Date: 2020-05-13</sub></div>

### Data streaming

* [ArroyoSystems/arroyo](https://github.com/ArroyoSystems/arroyo) - RustとSQLによる高性能リアルタイム分析 [![CI]](https://github.com/ArroyoSystems/arroyo/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/ArroyoSystems/arroyo/actions)<div><sub>Stars: 3.7k / Last Update: 2024-10-01 / Initial Date: 2023-03-31</sub></div>
* [iggy-rs/iggy](https://github.com/iggy-rs/iggy) [[iggy](https://crates.io/crates/iggy)] - QUIC、TCP、HTTPトランスポート・プロトコルをサポートする持続的メッセージ・ストリーミング・プラットフォーム[![CI]](https://github.com/iggy-rs/iggy/actions/workflows/test.yml/badge.svg)](https://github.com/iggy-rs/iggy/actions/workflows/test.yml)<div><sub>Stars: 1.8k / Last Update: 2024-10-03 / Initial Date: 2023-03-18</sub></div>
* [infinyon/fluvio](https://github.com/infinyon/fluvio) - プログラマブル・データ・ストリーミング・プラットフォーム [![CI](https://github.com/infinyon/fluvio/workflows/CI/badge.svg?branch=stable)](https://github.com/infinyon/fluvio/actions)<div><sub>Stars: 3.8k / Last Update: 2024-10-04 / Initial Date: 2019-08-31</sub></div>
* [swimos/swim-rust](https://github.com/swimos/swim-rust) [[swim-rust](https://crates.io/crates/swimos)] - ステートフルな大規模リアルタイム・ストリーミング・アプリケーションを構築するための自己完結型分散ソフトウェア・プラットフォーム。<div><sub>Stars: 304 / Last Update: 2024-10-04 / Initial Date: 2020-01-16</sub></div>

### Data structures

* [ashvardanian/simsimd](https://github.com/ashvardanian/SimSIMD) - x86 AVX2 & AVX-512 および Arm NEON 用 SIMD アクセラレーション・ベクトル距離および類似関数 [![crates.io](https://img.shields.io/crates/v/simsimd.svg)](https://crates.io/crates/simsimd)<div><sub>Stars: 916 / Last Update: 2024-10-04 / Initial Date: 2023-03-14</sub></div>
* [becheran/grid](https://github.com/becheran/grid) [[grid](https://crates.io/crates/grid)] - 使いやすく高速な2次元データ構造を提供する。[構築状況](https://github.com/becheran/grid/actions/workflows/rust.yml/badge.svg)](https://github.com/becheran/grid/actions)<div><sub>Stars: 82 / Last Update: 2024-09-22 / Initial Date: 2020-03-31</sub></div>
* [contain-rs](https://github.com/contain-rs) - Rustのstd::collectionsの拡張。
* [fizyk20/generic-array](https://github.com/fizyk20/generic-array) - typenumでサイズを指定する配列を可能にするハック<div><sub>Stars: 404 / Last Update: 2024-07-05 / Initial Date: 2015-09-24</sub></div>
* [garro95/priority-queue](https://github.com/garro95/priority-queue)[[priority-queue](https://crates.io/crates/priority-queue)] - 優先順位の変更を実行する優先順位キュー。<div><sub>Stars: 173 / Last Update: 2024-09-22 / Initial Date: 2017-07-06</sub></div>
* [greyblake/nutype](https://github.com/greyblake/nutype) [[nutype](https://crates.io/crates/nutype)] - バリデーション制約を持つnewtype構造を定義する。[構築状況](https://github.com/greyblake/nutype/actions/workflows/ci.yml/badge.svg)](https://github.com/greyblake/nutype/actions)<div><sub>Stars: 1.4k / Last Update: 2024-09-21 / Initial Date: 2022-10-09</sub></div>
* [mrhooray/kdtree-rs](https://github.com/mrhooray/kdtree-rs) - 高速な地理空間インデックスと最近傍探索のためのK次元ツリー<div><sub>Stars: 227 / Last Update: 2024-05-21 / Initial Date: 2015-07-29</sub></div>
* [orium/rpds](https://github.com/orium/rpds) [[rpds](https://crates.io/crates/rpds)] - 永続的なデータ構造。[ビルド・バッジ](https://github.com/orium/rpds/workflows/CI/badge.svg)](https://github.com/orium/rpds/actions?query=workflow%3ACI)<div><sub>Stars: 1.2k / Last Update: 2024-09-06 / Initial Date: 2017-07-06</sub></div>
* [RoaringBitmap/roaring-rs](https://github.com/RoaringBitmap/roaring-rs) - 咆哮するビットマップ<div><sub>Stars: 748 / Last Update: 2024-09-23 / Initial Date: 2014-12-27</sub></div>
* [rust-itertools/itertools](https://github.com/rust-itertools/itertools) - 追加のイテレータ・アダプタ、関数、マクロ<div><sub>Stars: 2.7k / Last Update: 2024-09-20 / Initial Date: 2014-07-28</sub></div>
* [xfix/enum-map](https://codeberg.org/xfix/enum-map) [[enum-map](https://crates.io/crates/enum-map)] - 値を格納するために配列を使用する、列挙型のための最適化されたマップ実装。

### Data visualization

* [blitzarx1/egui_graphs](https://github.com/blitzarx1/egui_graphs) [[egui_graphs](https://crates.io/crates/egui_graphs)] - eguiとpetgraphによるインタラクティブなグラフ可視化ウィジェット。[![Crates.io](https://img.shields.io/crates/v/egui_graphs)](https://crates.io/crates/egui_graphs) [![docs.rs](https://img.shields.io/docsrs/egui_graphs)](https://docs.rs/egui_graphs)<div><sub>Stars: 395 / Last Update: 2024-09-30 / Initial Date: 2023-03-28</sub></div>
* [mazznoer/colorgrad-rs](https://github.com/mazznoer/colorgrad-rs) [[colorgrad](https://crates.io/crates/colorgrad)] - データビジュアライゼーション、チャート、ゲーム、地図、ジェネレーティブアートなどのためのカラースケールライブラリ。<div><sub>Stars: 283 / Last Update: 2024-09-04 / Initial Date: 2020-12-23</sub></div>
* [plotly](https://github.com/plotly/plotly.rs) - Plotly for Rust<div><sub>Stars: 1.1k / Last Update: 2024-10-02 / Initial Date: 2020-01-26</sub></div>
* [plotpy](https://github.com/cpmech/plotpy) [[plotpy](https://crates.io/crates/plotpy)] - Python（Matplotlib）を使ったRustプロットライブラリ<div><sub>Stars: 64 / Last Update: 2024-09-29 / Initial Date: 2021-08-15</sub></div>
* [plotters](https://github.com/plotters-rs/plotters) - [ビルド・バッジ](https://github.com/plotters-rs/plotters/workflows/CI/badge.svg)](https://github.com/plotters-rs/plotters/actions)<div><sub>星：3.8k / 最終更新日：2024-10-04 / 期限：2019-04-24</sub></div></div>。<div><sub>Stars: 3.8k / Last Update: 2024-10-04 / Initial Date: 2019-04-24</sub></div>
* [rerun](https://github.com/rerun-io/rerun) - [再放送](https://crates.io/crates/rerun)]<div><sub>星: 6.3k / 最終更新日: 2024-10-04 / 初回表示日: 2022-04-08</sub></div></div<div><sub>Stars: 6.3k / Last Update: 2024-10-05 / Initial Date: 2022-04-08</sub></div>

### Database

[[database](https://crates.io/keywords/database)]

* NoSQL [[nosql](https://crates.io/keywords/nosql)]

  * [ArangoDB](https://arangodb.com)
    * [Aragog](https://gitlab.com/qonfucius/aragog) [[aragog](https://crates.io/crates/aragog)] - 軽量ArangoDBオブジェクトドキュメント・リレーショナル・グラフマッパー [![パイプラインの状況]](https://gitlab.com/qonfucius/aragog/badges/master/pipeline.svg)](https://gitlab.com/qonfucius/aragog/-/commits/master)
    * [Arangors](https://github.com/fMeow/arangors) [[arangors](https://crates.io/crates/arangors)] - ArangoDBドライバ<div><sub>Stars: 126 / Last Update: 2024-08-21 / Initial Date: 2018-09-06</sub></div>
  * [Cassandra](https://cassandra.apache.org/_/index.html) [[cassandra](https://crates.io/keywords/cassandra), [cql](https://crates.io/keywords/cql)]
    * [cassandra-rs](https://github.com/cassandra-rs/cassandra-rs) - DataStax C/C++へのバインディング<div><sub>Stars: 134 / Last Update: 2024-06-18 / Initial Date: 2017-06-12</sub></div>
    * [krojew/cdrs-tokio](https://github.com/krojew/cdrs-tokio) - 100%Rustで書かれた高レベルの非同期Cassandraクライアント。[ビルド・バッジ](https://github.com/krojew/cdrs-tokio/actions/workflows/rust.yml/badge.svg)](https://github.com/krojew/cdrs-tokio/actions)<div><sub>Stars: 136 / Last Update: 2024-09-30 / Initial Date: 2020-11-17</sub></div>
      * [[cassandra-protocol](https://crates.io/crates/cassandra-protocol)] - Cassandraプロトコルの実装。
      * [[cdrs-tokio](https://crates.io/crates/cdrs-tokio)] - 非同期 Apache Cassandra ドライバクライアント
  * CouchDB [[couchdb](https://crates.io/keywords/couchdb)]
  * [DynamoDB](https://aws.amazon.com/dynamodb/) [[dynamodb](https://crates.io/keywords/dynamodb)]
  * Elasticsearch [[elasticsearch](https://crates.io/keywords/elasticsearch)]
  * etcd
  * [InfluxDB](https://www.influxdata.com/)
    * [driftluo/InfluxDBClient-rs](https://github.com/driftluo/InfluxDBClient-rs) - 同期インターフェース<div><sub>Stars: 82 / Last Update: 2024-07-05 / Initial Date: 2017-06-11</sub></div>
  * LevelDB
  * LMDB [[lmdb](https://crates.io/keywords/lmdb)]
  * MongoDB [[mongodb](https://crates.io/keywords/mongodb)]
    * [mongodb/mongo-rust-driver](https://github.com/mongodb/mongo-rust-driver) [[mongodb](https://crates.io/crates/mongodb)] - [MongoDB](https://www.mongodb.com/)バインディング<div><sub>星: 1.4k / 最終更新日: 2024-10-04 / 初期日付: 2019-04-29</sub></div></div<div><sub>Stars: 1.4k / Last Update: 2024-10-04 / Initial Date: 2019-04-29</sub></div>
  * [PickleDB](https://pythonhosted.org/pickleDB/)
  * [PoloDB](https://www.polodb.org/)
    * [PoloDB](https://github.com/PoloDB/PoloDB) - MongoDBに似たAPIを持つJSONベースの組み込みデータベース。![GitHubワークフローのステータス](https://img.shields.io/github/actions/workflow/status/PoloDB/PoloDB/rust.yml)<div><sub>Stars: 885 / Last Update: 2024-10-03 / Initial Date: 2020-08-01</sub></div>
  * [Redb](https://www.redb.org/)
    * [Redb](https://github.com/cberner/redb) - 組み込みキー・バリュー・データベース。rocksdbやlmdbのような他の組み込みKey-Valueストアに似たインタフェースを提供する。 ![GitHubワークフロー状況](https://github.com/cberner/redb/actions/workflows/ci.yml/badge.svg)<div><sub>Stars: 3.2k / Last Update: 2024-10-02 / Initial Date: 2018-09-23</sub></div>
  * Redis [[redis](https://crates.io/keywords/redis)]
    * [aembke/fred](https://github.com/aembke/fred.rs) [[fred](https://crates.io/crates/fred)] - Tokioを使ったRust用の高レベル非同期[Redis](https://redis.io/)クライアント。[サークルCI](https://circleci.com/gh/aembke/fred.rs/tree/main.svg?style=svg)]([https://circleci.com/gh/aembke/fred.rs/tree/main](https://app.circleci.com/pipelines/github/aembke/fred.rs?branch=main))<div><sub>Stars: 376 / Last Update: 2024-09-05 / Initial Date: 2021-08-12</sub></div>
    * [redis-rs](https://github.com/redis-rs/redis-rs) - [Redis](https://redis.io/)ライブラリ [![Rust]](https://github.com/redis-rs/redis-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/redis-rs/redis-rs/actions/workflows/rust.yml)<div><sub>Stars: 3.6k / 最終更新日: 2024-10-03 / 初期日付: 2013-12-29</sub></div><div><sub>Stars: 3.6k / Last Update: 2024-10-03 / Initial Date: 2013-12-29</sub></div>
  * [RocksDB](https://rocksdb.org/)
    * [rust-rocksdb/rust-rocksdb](https://github.com/rust-rocksdb/rust-rocksdb) - RocksDBバインディング [![RocksDB CI]](https://github.com/rust-rocksdb/rust-rocksdb/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/rust-rocksdb/rust-rocksdb/actions/workflows/rust.yml)<div><sub>Stars: 1.8k / Last Update: 2024-09-20 / Initial Date: 2014-11-16</sub></div>
  * [SurrealDB](https://surrealdb.com/)
    * [surrealdb/surrealdb](https://github.com/surrealdb/surrealdb) - SurrealDB組み込みドキュメント・グラフ・データベース<div><sub>Stars: 27.1k / Last Update: 2024-10-04 / Initial Date: 2021-12-09</sub></div>
  * [UnQLite](https://github.com/symisc/unqlite)
  * [ZooKeeper](https://zookeeper.apache.org/)
    * [krojew/rust-zookeeper](https://github.com/krojew/rust-zookeeper) [[zookeeper-async](https://crates.io/crates/zookeeper-async)] - tokio ベースの非同期 Zookeeper クライアント。  ビルド状況](https://github.com/krojew/rust-zookeeper/actions/workflows/rust.yml/badge.svg)<div><sub>Stars: 22 / Last Update: 2024-08-08 / Initial Date: 2019-09-25</sub></div>
* OGM [[ogm](https://crates.io/keywords/ogm)]
    * [Aragog](https://gitlab.com/qonfucius/aragog) [[aragog](https://crates.io/crates/aragog)] - 軽量ArangoDBオブジェクトドキュメント・リレーショナル・グラフマッパー [![パイプラインの状況]](https://gitlab.com/qonfucius/aragog/badges/master/pipeline.svg)](https://gitlab.com/qonfucius/aragog/-/commits/master)
* ORM [[orm](https://crates.io/keywords/orm)]
  * [Brendonovich/prisma-client-rust](https://github.com/Brendonovich/prisma-client-rust) - Prismaエコシステムを使用して、シンプルで完全に型安全なデータベースアクセスを提供する自動生成クエリビルダー。[テストステータス](https://img.shields.io/github/workflow/status/Brendonovich/prisma-client-rust/CI?label=tests&style=flat-square)](https://github.com/Brendonovich/prisma-client-rust/actions)<div><sub>Stars: 1.8k / Last Update: 2024-05-15 / Initial Date: 2021-05-25</sub></div>
  * [diesel-rs/diesel](https://github.com/diesel-rs/diesel) - ORMとクエリビルダ<div><sub>Stars: 12.6k / Last Update: 2024-10-02 / Initial Date: 2015-08-29</sub></div>
  * [mjovanc/njord](https://github.com/mjovanc/njord) - ⛵ Rust用の軽量ORMライブラリ [![ビルド状況](https://github.com/mjovanc/njord/actions/workflows/ci.yml/badge.svg)](https://github.com/mjovanc/njord/actions/workflows/ci.yml) ![crates.io](https://img.shields.io/crates/v/njord.svg)<div><sub>Stars: 302 / Last Update: 2024-10-05 / Initial Date: 2023-04-08</sub></div>
  * [rbatis/rbatis](https://github.com/rbatis/rbatis) - ORMフレームワーク ハイパフォーマンス(JSONベース)<div><sub>Stars: 2.3k / Last Update: 2024-09-29 / Initial Date: 2019-03-08</sub></div>
  * [SeaQL/sea-orm](https://github.com/SeaQL/sea-orm) - 🐚 非同期＆動的ORM [![crate](https://img.shields.io/crates/v/sea-orm.svg)](https://crates.io/crates/sea-orm) [![docs](https://img.shields.io/docsrs/sea-orm/latest)](https://docs.rs/sea-orm) [![build status](https://github.com/SeaQL/sea-orm/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-orm/actions/workflows/rust.yml)<div><sub>Stars: 7.1k / Last Update: 2024-10-04 / Initial Date: 2021-02-09</sub></div>
  * [SeaQL/seaography](https://github.com/SeaQL/seaography) - SeaORM ↪So_1F9ED のための GraphQL フレームワーク [![crate](https://img.shields.io/crates/v/seaography.svg)](https://crates.io/crates/seaography) [![docs](https://img.shields.io/docsrs/seaography/latest)](https://docs.rs/seaography) [![build status](https://github.com/SeaQL/seaography/actions/workflows/tests.yaml/badge.svg)](https://github.com/SeaQL/seaography/actions/workflows/tests.yaml)<div><sub>Stars: 378 / Last Update: 2024-09-12 / Initial Date: 2022-06-12</sub></div>
* SQL [[sql](https://crates.io/keywords/sql)]
  * Generic
    * [launchbadge/sqlx](https://github.com/launchbadge/sqlx) - 強力なタイピングをサポートする非同期PostgreSQL/MySQL/SQLite接続プール [![ビルドバッジ]](https://img.shields.io/github/workflow/status/launchbadge/sqlx/Rust/master?style=flat-square)](https://github.com/launchbadge/sqlx)<div><sub>Stars: 13.2k / Last Update: 2024-10-05 / Initial Date: 2019-12-28</sub></div>
    * [launchbadge/sqlx](https://github.com/launchbadge/sqlx) - 強力なタイピングをサポートする非同期PostgreSQL/MySQL/SQLite接続プール [![ビルドバッジ]](https://img.shields.io/github/workflow/status/launchbadge/sqlx/Rust/master?style=flat-square)](https://github.com/launchbadge/sqlx)<div><sub>Stars: 13.2k / Last Update: 2024-10-05 / Initial Date: 2019-12-28</sub></div>
    * [SeaQL/sea-query](https://github.com/SeaQL/sea-query) - MySQL、Postgres、SQLite用の動的SQLクエリビルダ 🔱 [![crate](https://img.shields.io/crates/v/sea-query.svg)](https://crates.io/crates/sea-query) [![docs](https://img.shields.io/docsrs/sea-query/latest)](https://docs.rs/sea-query) [![build status](https://github.com/SeaQL/sea-query/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-query/actions/workflows/rust.yml)<div><sub>Stars: 1.1k / Last Update: 2024-10-05 / Initial Date: 2020-12-16</sub></div>
    * [SeaQL/sea-schema](https://github.com/SeaQL/sea-schema) - SQL スキーマの定義と発見 [![crate](https://img.shields.io/crates/v/sea-schema.svg)](https://crates.io/crates/sea-schema) [![docs](https://img.shields.io/docsrs/sea-schema/latest)](https://docs.rs/sea-schema) [![build status](https://github.com/SeaQL/sea-schema/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-schema/actions/workflows/rust.yml)<div><sub>Stars: 185 / Last Update: 2024-09-05 / Initial Date: 2021-03-14</sub></div>
  * Microsoft SQL
    * [prisma/tiberius](https://github.com/prisma/tiberius) - [貨物テスト](https://github.com/prisma/tiberius/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/prisma/tiberius/actions/workflows/test.yml)<div><sub>星: 326 / 最終更新日: 2024-07-31 / 期日: 2020-03-26</sub></div<div><sub>Stars: 326 / Last Update: 2024-07-31 / Initial Date: 2020-03-26</sub></div>
  * MySql [[mysql](https://crates.io/keywords/mysql)]
    * [blackbeam/mysql_async](https://github.com/blackbeam/mysql_async) [[mysql_async](https://crates.io/crates/mysql_async)] - Tokioベースの非同期Mysqlドライバ。[サークルCI](https://circleci.com/gh/blackbeam/mysql_async/tree/master.svg?style=shield)](https://app.circleci.com/pipelines/github/blackbeam/mysql_async?branch=master)<div><sub>Stars: 377 / Last Update: 2024-08-13 / Initial Date: 2016-10-12</sub></div>
    * [blackbeam/rust-mysql-simple](https://github.com/blackbeam/rust-mysql-simple) [[mysql](https://crates.io/crates/mysql)] - ネイティブのMySqlクライアント<div><sub>Stars: 661 / Last Update: 2024-08-11 / Initial Date: 2014-02-18</sub></div>
  * Oracle
    * [kubo/rust-oracle](https://github.com/kubo/rust-oracle) [[oracle](https://crates.io/crates/oracle)] - オラクル・ドライバー [![ビルド・バッジ]](https://github.com/kubo/rust-oracle/actions/workflows/run-tests.yml/badge.svg?branch=master)](https://github.com/kubo/rust-oracle/actions/workflows/run-tests.yml)<div><sub>Stars: 191 / Last Update: 2024-08-05 / Initial Date: 2017-02-11</sub></div>
  * PostgreSql [[postgres](https://crates.io/keywords/postgres), [postgresql](https://crates.io/keywords/postgresql)]
    * [c410-f3r/wtx](https://github.com/c410-f3r/wtx) - 外部依存の少ない高速実装。<div><sub>Stars: 142 / Last Update: 2024-10-03 / Initial Date: 2023-08-28</sub></div>
    * [sfackler/rust-postgres](https://github.com/sfackler/rust-postgres) [[postgres](https://crates.io/crates/postgres)] - ネイティブの[PostgreSQL](https://www.postgresql.org/)クライアント<div><sub>Stars: 3.5k / Last Update: 2024-09-16 / Initial Date: 2013-07-23</sub></div>
  * Sqlite [[sqlite](https://crates.io/keywords/sqlite)]
    * [rusqlite](https://github.com/rusqlite/rusqlite) - [Sqlite3](https://www.sqlite.org/index.html)バインディング<div><sub>星: 3.1k / 最終更新日: 2024-10-01 / 初回表示日: 2014-11-04</sub></div<div><sub>Stars: 3.1k / Last Update: 2024-10-01 / Initial Date: 2014-11-04</sub></div>

### Date and time

[[date](https://crates.io/keywords/date), [time](https://crates.io/keywords/time)]

* [arthurhenrique/rusti-cal](https://github.com/arthurhenrique/rusti-cal) [[rusti-cal](https://crates.io/crates/rusti-cal)] - cal(1)クローンは電光石火の速さで〜9999年以上〜Rustで書かれている。<div><sub>Stars: 56 / Last Update: 2024-07-19 / Initial Date: 2021-04-22</sub></div>
* [chronotope/chrono](https://github.com/chronotope/chrono) - 日時ライブラリー<div><sub>Stars: 3.3k / Last Update: 2024-10-01 / Initial Date: 2014-03-28</sub></div>
* [sorairolake/nt-time](https://github.com/sorairolake/nt-time) [[nt-time](https://crates.io/crates/nt-time)] - Windowsのファイルタイムライブラリ。![CI](https://github.com/sorairolake/nt-time/workflows/CI/badge.svg?branch=develop)](https://github.com/sorairolake/nt-time/actions?query=workflow%3ACI)<div><sub>Stars: 5 / Last Update: 2024-09-30 / Initial Date: 2023-03-19</sub></div>
* [time-rs/time](https://github.com/time-rs/time) - [ビルド・バッジ](https://github.com/time-rs/time/workflows/Build/badge.svg)](https://github.com/time-rs/time/actions)<div><sub>星: 1.1k / 最終更新日: 2024-09-06 / 初回表示日: 2014-11-10</sub></div></div<div><sub>Stars: 1.1k / Last Update: 2024-09-06 / Initial Date: 2014-11-10</sub></div>

### Distributed systems

* Antimony
* Apache Kafka
  * [fede1024/rust-rdkafka](https://github.com/fede1024/rust-rdkafka) [[rdkafka](https://crates.io/crates/rdkafka)] - [librdkafka](https://github.com/confluentinc/librdkafka) バインディング<div><sub>星: 1.6k / 最終更新日: 2024-10-03 / 初期日付: 2016-10-29</sub></div><div><sub>Stars: 1.6k / Last Update: 2024-10-03 / Initial Date: 2016-10-29</sub></div>
  * [gklijs/schema_registry_converter](https://github.com/gklijs/schema_registry_converter) [[schema_registry_converter](https://crates.io/crates/schema_registry_converter)] - confluent schema registry](https://www.confluent.io/product/confluent-platform/data-compatibility/)と統合する。<div><sub>Stars: 101 / Last Update: 2024-10-02 / Initial Date: 2018-09-15</sub></div>
  * [kafka-rust/kafka-rust](https://github.com/kafka-rust/kafka-rust) - Apache Kafka 用 Rust クライアント<div><sub>Stars: 1.2k / Last Update: 2024-09-22 / Initial Date: 2015-05-07</sub></div>
* HDFS
* Other
  * [build-trust/ockam](https://github.com/build-trust/ockam) [[ockam](https://crates.io/crates/ockam)] - 分散アプリケーションのためのエンドツーエンドの暗号化、相互認証、ABAC [![ビルドバッジ]](https://github.com/build-trust/ockam/workflows/Rust/badge.svg)](https://github.com/build-trust/ockam)<div><sub>Stars: 4.4k / Last Update: 2024-10-05 / Initial Date: 2018-11-30</sub></div>
  * [build-trust/ockam](https://github.com/build-trust/ockam) [[ockam](https://crates.io/crates/ockam)] - 分散アプリケーションのためのエンドツーエンドの暗号化、相互認証、ABAC [![ビルドバッジ]](https://github.com/build-trust/ockam/workflows/Rust/badge.svg)](https://github.com/build-trust/ockam)<div><sub>Stars: 4.4k / Last Update: 2024-10-05 / Initial Date: 2018-11-30</sub></div>

### Domain driven design

  * [serverlesstechnology/cqrs](https://github.com/serverlesstechnology/cqrs) [[cqrs-es](https://crates.io/crates/cqrs-es)] - ユーザーガイド](https://doc.rust-cqrs.org/)によるCQRSとイベント・ソーシングのためのフレームワーク<div><sub>Stars: 369 / Last Update: 2024-09-30 / Initial Date: 2020-04-07</sub></div>

### eBPF

* [aya/aya-rs](https://github.com/aya-rs/aya) - 開発者の体験と操作性を重視して構築。<div><sub>Stars: 3.1k / Last Update: 2024-10-04 / Initial Date: 2021-01-20</sub></div>
* [libbpf/libbpf-rs](https://github.com/libbpf/libbpf-rs) - ミニマムで意見の多いeBPFツール。<div><sub>Stars: 749 / Last Update: 2024-10-02 / Initial Date: 2020-04-12</sub></div>

### Email

[[email](https://crates.io/keywords/email), [imap](https://crates.io/keywords/imap), [smtp](https://crates.io/keywords/smtp)]

* [duesee/imap-codec](https://github.com/duesee/imap-codec) [[imap-codec](https://crates.io/crates/imap-codec)] - IMAP用の揺るぎない完全なコーデック [![Build & Test]](https://github.com/duesee/imap-codec/actions/workflows/build_and_test.yml/badge.svg)](https://github.com/duesee/imap-codec/actions/workflows/build_and_test.yml)<div><sub>Stars: 39 / Last Update: 2024-10-03 / Initial Date: 2020-03-30</sub></div>
* [gsquire/sendgrid-rs](https://github.com/gsquire/sendgrid-rs) - SendGrid API 用ライブラリ<div><sub>Stars: 106 / Last Update: 2024-09-04 / Initial Date: 2015-10-06</sub></div>
* [jdrouet/catapulte](https://github.com/jdrouet/catapulte) - MRML](https://github.com/jdrouet/mrml)テンプレートを使ってメールを送信するマイクロサービス。<div><sub>Stars: 139 / Last Update: 2024-07-17 / Initial Date: 2020-05-23</sub></div>
* [jdrouet/catapulte](https://github.com/jdrouet/catapulte) - MRML](https://github.com/jdrouet/mrml)テンプレートを使ってメールを送信するマイクロサービス。<div><sub>Stars: 139 / Last Update: 2024-07-17 / Initial Date: 2020-05-23</sub></div>
* [jdrouet/mrml](https://github.com/jdrouet/mrml) - どんなメールクライアントでも動作する、素敵なメールテンプレートを生成するライブラリ。<div><sub>Stars: 343 / Last Update: 2024-09-30 / Initial Date: 2020-05-11</sub></div>
* [lettre/lettre](https://github.com/lettre/lettre) - SMTP ライブラリ [![CI](https://github.com/lettre/lettre/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/lettre/lettre/actions/workflows/test.yml)<div><sub>Stars: 1.8k / Last Update: 2024-09-13 / Initial Date: 2014-02-03</sub></div>
* [mailtutan/mailtutan](https://github.com/mailtutan/mailtutan) - テスト・開発環境用のSMTPサーバー。<div><sub>Stars: 165 / Last Update: 2024-08-10 / Initial Date: 2023-05-13</sub></div>
* [meli/meli](https://github.com/meli/meli) - 🐝 端末メールクライアント<div><sub>Stars: 653 / Last Update: 2024-09-24 / Initial Date: 2019-06-10</sub></div>
* [staktrace/mailparse](https://github.com/staktrace/mailparse) [[mailparse](https://crates.io/crates/mailparse)] - 実世界の電子メールファイルを解析するライブラリ<div><sub>Stars: 181 / Last Update: 2024-04-29 / Initial Date: 2016-05-29</sub></div>
* [stalwartlabs/mail-auth](https://github.com/stalwartlabs/mail-auth) [[mail-auth](https://crates.io/crates/mail-auth)] - DKIM、ARC、SPF、DMARCメッセージ認証ライブラリ [![ビルドバッジ]](https://github.com/stalwartlabs/mail-auth/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-auth/actions/workflows/rust.yml)<div><sub>Stars: 83 / Last Update: 2024-08-11 / Initial Date: 2022-11-02</sub></div>
* [stalwartlabs/mail-parser](https://github.com/stalwartlabs/mail-parser) [[mail-parser](https://crates.io/crates/mail-parser)] - 完全な MIME サポートを備えた高速で堅牢な電子メール解析ライブラリ [![ビルドバッジ]](https://github.com/stalwartlabs/mail-parser/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-parser/actions/workflows/rust.yml)<div><sub>Stars: 291 / Last Update: 2024-09-08 / Initial Date: 2021-10-03</sub></div>
* [stalwartlabs/mail-send](https://github.com/stalwartlabs/mail-send) [[mail-send](https://crates.io/crates/mail-send)] - DKIMをサポートした電子メールビルダーとSMTPクライアントライブラリ [![ビルドバッジ]](https://github.com/stalwartlabs/mail-send/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-send/actions/workflows/rust.yml)<div><sub>Stars: 203 / Last Update: 2024-08-12 / Initial Date: 2022-05-27</sub></div>
* [tweedegolf/mailcrab](https://github.com/tweedegolf/mailcrab) - 開発用メールテストサーバー。<div><sub>Stars: 713 / Last Update: 2024-08-26 / Initial Date: 2022-10-21</sub></div>

### Encoding

[[encoding](https://crates.io/keywords/encoding)]

* ASN.1
  * [alex/rust-asn1](https://github.com/alex/rust-asn1) - ASN.1（DER）シリアライザ<div><sub>Stars: 98 / Last Update: 2024-10-04 / Initial Date: 2015-07-18</sub></div>
* Binary
  * [bincode-org/bincode](https://github.com/bincode-org/bincode) - バイナリ・エンコーダ／デコーダ [![CI](https://github.com/bincode-org/bincode/actions/workflows/rust.yml/badge.svg?branch=trunk)](https://github.com/bincode-org/bincode/actions/workflows/rust.yml)<div><sub>Stars: 2.7k / Last Update: 2024-08-07 / Initial Date: 2014-09-17</sub></div>
  * [jamesmunns/postcard](https://github.com/jamesmunns/postcard) [[postcard](https://crates.io/crates/postcard)] - Postcard は、#![no_std] にフォーカスした Serde 用のシリアライザおよびデシリアライザです。<div><sub>Stars: 874 / Last Update: 2024-09-19 / Initial Date: 2019-04-03</sub></div>
  * [m4b/goblin](https://github.com/m4b/goblin) [[goblin](https://crates.io/crates/goblin)] - クロスプラットフォーム、ゼロコピー、エンディアンを意識したバイナリ解析<div><sub>Stars: 1.2k / Last Update: 2024-08-14 / Initial Date: 2016-05-13</sub></div>
* BSON
  * [mongodb/bson-rust](https://github.com/mongodb/bson-rust) - BSONのエンコードとデコードのサポート<div><sub>Stars: 400 / Last Update: 2024-09-19 / Initial Date: 2015-04-08</sub></div>
* Byte swapping
  * [BurntSushi/byteorder](https://github.com/BurntSushi/byteorder) - ビッグエンディアン、リトルエンディアン、ネイティブバイトオーダーをサポート<div><sub>Stars: 972 / Last Update: 2024-09-25 / Initial Date: 2015-02-03</sub></div>
* Cap'n Proto
  * [capnproto/capnproto-rust](https://github.com/capnproto/capnproto-rust) - Cap'n Protoは分散システム用の型システムです。<div><sub>Stars: 2.0k / Last Update: 2024-09-25 / Initial Date: 2013-07-04</sub></div>
* CBOR
  * [serde_cbor](https://crates.io/crates/serde_cbor) - セルデのCBORサポート
* Character Encoding
  * [hsivonen/encoding_rs](https://github.com/hsivonen/encoding_rs) [[encoding_rs](https://crates.io/crates/encoding_rs)] - エンコーディング・スタンダードのGecko指向の実装<div><sub>Stars: 383 / Last Update: 2024-09-20 / Initial Date: 2016-01-04</sub></div>
* CRC
  * [mrhooray/crc-rs](https://github.com/mrhooray/crc-rs) - 様々な規格に対応したCRC(16, 32, 64)のサビ実装<div><sub>Stars: 188 / Last Update: 2024-04-08 / Initial Date: 2015-03-15</sub></div>
* CSV
  * [BurntSushi/rust-csv](https://github.com/BurntSushi/rust-csv) - Serdeをサポートした高速で柔軟なCSVリーダー／ライター<div><sub>Stars: 1.7k / Last Update: 2024-09-25 / Initial Date: 2014-03-22</sub></div>
* EDN
  * [edn-rs](https://github.com/naomijub/edn-rs) [[edn-rs](https://crates.io/crates/edn-rs)] - crate を使用して、EDN フォーマットを解析し、Rust 型に変換します。<div><sub>Stars: 81 / Last Update: 2024-09-16 / Initial Date: 2019-11-27</sub></div>
* [FlatBuffers](https://flatbuffers.dev/)
  * [frol/flatc-rust](https://github.com/frol/flatc-rust) - FlatBuffersコンパイラ(flatc)のCargoビルドスクリプトへの統合<div><sub>Stars: 105 / Last Update: 2024-02-10 / Initial Date: 2019-01-15</sub></div>
* HAR
* HTML
  * [servo/html5ever](https://github.com/servo/html5ever) - 高性能ブラウザグレードのHTML5パーサー<div><sub>Stars: 2.1k / Last Update: 2024-09-10 / Initial Date: 2014-03-13</sub></div>
* JSON
  * [cloudwego/sonic-rs](https://github.com/cloudwego/sonic-rs) [[sonic-rs](https://crates.io/crates/sonic-rs)] - SIMDベースの高速Rust JSONライブラリ。<div><sub>Stars: 447 / Last Update: 2024-09-20 / Initial Date: 2023-07-27</sub></div>
  * [rustadopt/jzon-rs](https://github.com/rustadopt/jzon-rs/) [[jzon](https://crates.io/crates/jzon)] - JSONの実装<div><sub>Stars: 8 / Last Update: 2024-08-03 / Initial Date: 2023-08-25</sub></div>
  * [serde-rs/json](https://github.com/serde-rs/json) [[serde\_json](https://crates.io/crates/serde_json)] - Serde](https://github.com/serde-rs/serde)フレームワークのJSONサポート<div><sub>Stars: 4.8k / Last Update: 2024-09-27 / Initial Date: 2015-05-19</sub></div>
  * [serde-rs/json](https://github.com/serde-rs/json) [[serde\_json](https://crates.io/crates/serde_json)] - Serde](https://github.com/serde-rs/serde)フレームワークのJSONサポート<div><sub>Stars: 4.8k / Last Update: 2024-09-27 / Initial Date: 2015-05-19</sub></div>
  * [simd-lite/simd-json](https://github.com/simd-lite/simd-json) [[simd-json](https://crates.io/crates/simd-json)] - simdjsonを移植した高性能JSONパーサー<div><sub>Stars: 1.1k / Last Update: 2024-09-22 / Initial Date: 2019-03-24</sub></div>
* MsgPack
  * [3Hren/msgpack-rust](https://github.com/3Hren/msgpack-rust) - 低／高レベルのMessagePack実装<div><sub>Stars: 1.1k / Last Update: 2024-08-21 / Initial Date: 2015-03-20</sub></div>
* NetCDF
  * [georust/netcdf](https://github.com/georust/netcdf) [[netcdf](https://crates.io/crates/netcdf)] - 中レベルのnetCDFバインディングで、配列のような構造を簡単にファイルに読み書きできる。<div><sub>Stars: 81 / Last Update: 2024-10-03 / Initial Date: 2015-06-27</sub></div>
* PEM
  * [jcreekmore/pem-rs](https://github.com/jcreekmore/pem-rs) [[pem](https://crates.io/crates/pem)] - PEMエンコードされたデータの解析とエンコード<div><sub>Stars: 54 / Last Update: 2024-04-08 / Initial Date: 2016-02-21</sub></div>
* ProtocolBuffers
  * [stepancheg/rust-protobuf](https://github.com/stepancheg/rust-protobuf) - GoogleプロトコルバッファのRust実装<div><sub>Stars: 2.8k / Last Update: 2024-09-30 / Initial Date: 2013-07-28</sub></div>
  * [tokio-rs/prost](https://github.com/tokio-rs/prost) - [継続的インテグレーション](https://github.com/tokio-rs/prost/workflows/continuous%20integration/badge.svg?branch=master)](https://github.com/tokio-rs/prost/actions)<div><sub>星: 3.9k / 最終更新日: 2024-10-02 / 初回更新日: 2017-06-13</sub></div></div<div><sub>Stars: 3.9k / Last Update: 2024-10-02 / Initial Date: 2017-06-13</sub></div>
* rkyv
  * [rkyv/rkyv](https://github.com/rkyv/rkyv) [[rkyv](https://crates.io/crates/rkyv)] - rkyv (archive)はゼロコピーでデシリアライズするフレームワークです。<div><sub>Stars: 2.9k / Last Update: 2024-10-01 / Initial Date: 2020-11-05</sub></div>
* RON (Rusty Object Notation)
  * [https://github.com/ron-rs/ron](https://github.com/ron-rs/ron) - ラスティ・オブジェクト表記法<div><sub>Stars: 3.3k / Last Update: 2024-09-29 / Initial Date: 2015-04-20</sub></div>
* Serde
  * [iddm/serde-aux](https://github.com/iddm/serde-aux/) - serdeライブラリを使用するための追加ツール。[CI](https://github.com/iddm/serde-aux/actions/workflows/ci.yml/badge.svg)](https://github.com/iddm/serde-aux/actions/workflows/ci.yml) [![木枠バッジ]](https://img.shields.io/crates/v/serde-aux.svg)](https://crates.io/crates/serde-aux)<div><sub>Stars: 155 / Last Update: 2024-04-21 / Initial Date: 2018-02-22</sub></div>
* TOML
  * [tamasfe/taplo](https://github.com/tamasfe/taplo) [[taplo](https://crates.io/crates/taplo)] - TOMLツールキット [![CI](https://github.com/tamasfe/taplo/workflows/Continuous%20integration/badge.svg)](https://github.com/tamasfe/taplo/actions?query=workflow%3A%22Continuous+integration%22)<div><sub>Stars: 1.4k / Last Update: 2024-10-04 / Initial Date: 2020-05-23</sub></div>
  * [toml-rs/toml](https://github.com/toml-rs/toml) - [[CI](https://github.com/toml-rs/toml/actions/workflows/ci.yml/badge.svg)](https://github.com/toml-rs/toml/actions/workflows/ci.yml)<div><sub>スター数：700 / 最終更新日：2024-10-01 / 初回更新日：2017-06-30</sub></div>。<div><sub>Stars: 700 / Last Update: 2024-10-01 / Initial Date: 2017-06-30</sub></div>
* XML
  * [media-io/yaserde](https://github.com/media-io/yaserde) - XMLに特化したもうひとつのシリアライザー／デシリアライザー<div><sub>Stars: 177 / Last Update: 2024-09-16 / Initial Date: 2018-04-09</sub></div>
  * [netvl/xml-rs](https://github.com/netvl/xml-rs) - ストリーミングXMLライブラリ<div><sub>Stars: 460 / Last Update: 2024-03-31 / Initial Date: 2014-06-07</sub></div>
  * [tafia/quick-xml](https://github.com/tafia/quick-xml) - 高性能XMLプルリーダー/ライター<div><sub>Stars: 1.2k / Last Update: 2024-09-29 / Initial Date: 2016-01-27</sub></div>
* YAML
  * [dtolnay/serde-yaml](https://github.com/dtolnay/serde-yaml) [[serde\_yaml](https://crates.io/crates/serde_yaml)] - Serde](https://github.com/serde-rs/serde)フレームワークのYAMLサポート[![build](https://img.shields.io/github/workflow/status/dtolnay/serde-yaml/CI/master)](https://github.com/dtolnay/serde-yaml/actions?query=branch%3Amaster)<div><sub>Stars: 955 / Last Update: 2024-03-25 / Initial Date: 2016-02-24</sub></div>
  * [dtolnay/serde-yaml](https://github.com/dtolnay/serde-yaml) [[serde\_yaml](https://crates.io/crates/serde_yaml)] - Serde](https://github.com/serde-rs/serde)フレームワークのYAMLサポート[![build](https://img.shields.io/github/workflow/status/dtolnay/serde-yaml/CI/master)](https://github.com/dtolnay/serde-yaml/actions?query=branch%3Amaster)<div><sub>Stars: 955 / Last Update: 2024-03-25 / Initial Date: 2016-02-24</sub></div>
  * [vitiral/stfu8](https://github.com/vitiral/stfu8) [[stfu8](https://crates.io/crates/stfu8)] - UTF-8のソート・テキスト・フォーマット<div><sub>Stars: 26 / Last Update: 2024-01-09 / Initial Date: 2018-01-15</sub></div>

### Filesystem

[[filesystem](https://crates.io/keywords/filesystem)]
* Operations
  * [Camino](https://github.com/camino-rs/camino) [[camino](https://crates.io/crates/camino)] - Rustのstd::path::Pathのようなものだが、UTF-8である。<div><sub>Stars: 429 / Last Update: 2024-08-18 / Initial Date: 2020-07-07</sub></div>
  * [OpenDAL](https://github.com/apache/opendal) [[opendal](https://crates.io/crates/opendal)] - 統一されたデータアクセスレイヤーにより、ユーザーは多様なストレージサービスからシームレスかつ効率的にデータを取り出すことができる。[ビルド](https://img.shields.io/github/actions/workflow/status/apache/opendal/ci_core.yml?branch=main)](https://github.com/apache/opendal/actions?query=branch%3Amain)<div><sub>Stars: 3.3k / Last Update: 2024-10-05 / Initial Date: 2022-02-14</sub></div>
  * [pop-os/sys-mount](https://github.com/pop-os/sys-mount) [[sys-mount](https://crates.io/crates/sys-mount)] - mount` / `umount2` システムコールを高レベルで抽象化する。<div><sub>Stars: 41 / Last Update: 2024-02-05 / Initial Date: 2018-10-02</sub></div>
* Temporary Files
  * [Stebalien/tempfile](https://github.com/Stebalien/tempfile) - テンポラリファイルライブラリ<div><sub>Stars: 1.2k / Last Update: 2024-09-28 / Initial Date: 2015-04-12</sub></div>
  * [Stebalien/xattr](https://github.com/Stebalien/xattr) [[xattr](https://crates.io/crates/xattr)] - UNIX拡張ファイル属性のリストと操作<div><sub>Stars: 58 / Last Update: 2024-06-10 / Initial Date: 2015-07-10</sub></div>

### Finance

* [avhz/RustQuant](https://github.com/avhz/RustQuant) [[RustQuant](https://crates.io/crates/RustQuant)] - クオンツファイナンスライブラリ。![GitHubワークフロー状況(イベントあり)](https://img.shields.io/github/actions/workflow/status/avhz/RustQuant/build.yml)<div><sub>Stars: 1.1k / Last Update: 2024-10-01 / Initial Date: 2022-08-31</sub></div>
* [d-e-s-o/apca](https://github.com/d-e-s-o/apca) [[apca](https://crates.io/crates/apca)] - 株式取引などのための[Alpaca API](https://alpaca.markets/)への意見的で包括的なバインディング。GitHubワークフロー状況](https://github.com/d-e-s-o/apca/actions/workflows/test.yml/badge.svg?branch=main)<div><sub>Stars: 142 / Last Update: 2024-07-28 / Initial Date: 2020-04-21</sub></div>
* [dancixx/stochastic-rs](https://github.com/dancixx/stochastic-rs) [[stochastic-rs](https://crates.io/crates/stochastic-rs)] - クオンツファイナンスツールを用いた確率過程のための高性能データ生成ライブラリ。GitHubワークフローの状況](https://github.com/dancixx/stochastic-rs/actions/workflows/rust.yml/badge.svg)<div><sub>Stars: 12 / Last Update: 2024-10-04 / Initial Date: 2023-05-21</sub></div>

### Functional Programming

[[functional programming](https://crates.io/keywords/fp)]
* Prelude

### Game development

See also [Are we game yet?](https://arewegameyet.rs)
* Allegro
  * [SiegeLord/RustAllegro](https://github.com/SiegeLord/RustAllegro) - [アレグロ5](https://liballeg.org/)バインディング<div><sub>Stars: 94 / Last Update: 2024-07-21 / Initial Date: 2013-04-12</sub></div><div><sub>Stars: 94 / Last Update: 2024-07-21 / Initial Date: 2013-04-12</sub></div>
* [Awesome Quads](https://github.com/ozkriff/awesome-quads) - ミニクワッド／マクロクワッド関連コード＆リソースへのリンク集<div><sub>Stars: 183 / Last Update: 2024-10-03 / Initial Date: 2021-01-28</sub></div>
* bracket-lib (previously RLTK)
* Challonge
  * [iddm/challonge-rs](https://github.com/iddm/challonge-rs) [[challonge](https://crates.io/crates/challonge)] - Challonge REST APIのクライアントライブラリ。トーナメント開催に役立つ。[CI](https://github.com/iddm/challonge-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/iddm/challonge-rs/actions/workflows/ci.yml)<div><sub>Stars: 2 / Last Update: 2023-12-05 / Initial Date: 2016-07-01</sub></div>
* Entity-Component Systems (ECS)
  * [amethyst/specs](https://github.com/amethyst/specs) - スペック パラレルECS<div><sub>Stars: 2.5k / Last Update: 2024-06-07 / Initial Date: 2016-04-06</sub></div>
* Game Engines
  * [Bevy](https://github.com/bevyengine/bevy) - は爽やかでシンプルなデータ駆動型ゲームエンジンだ。<div><sub>Stars: 35.5k / Last Update: 2024-10-04 / Initial Date: 2020-01-18</sub></div><div><sub>Stars: 35.5k / Last Update: 2024-10-05 / Initial Date: 2020-01-18</sub></div>
  * [Fyrox](https://fyrox.rs/) - ゲームエンジン3D [![Crates.io](https://img.shields.io/crates/v/fyrox.svg)](https://crates.io/crates/fyrox) [![ライセンス](https://img.shields.io/crates/l/fyrox.svg)](https://github.com/FyroxEngine/Fyrox/blob/master/LICENSE.md) [![Crates.io](https://img.shields.io/crates/d/fyrox.svg)](https://crates.io/crates/fyrox)
  * [Kiss3d](http://kiss3d.org) - シンプルで愚直な3Dグラフィックエンジン [![Crates.io](https://img.shields.io/crates/d/kiss3d.svg)](https://crates.io/crates/kiss3d)
  * [Piston](https://www.piston.rs/) - [![Crates.io](https://img.shields.io/crates/v/piston.svg?style=flat-square)](https://crates.io/crates/piston) [![Crates.io](https://img.shields.io/crates/l/piston.svg)](https://github.com/PistonDevelopers/piston/blob/master/LICENSE) [![Crates.io](https://img.shields.io/crates/d/piston.svg)](https://crates.io/crates/piston)
* Game Servers
  * [gamedig/rust-gamedig](https://github.com/gamedig/rust-gamedig) [[gamedig](https://crates.io/crates/gamedig)] - 名前、オンラインプレイヤー、最大プレイヤー数などの情報をゲームサーバーに問い合わせる。[![Crates.io](https://img.shields.io/crates/v/gamedig.svg)](https://crates.io/crates/gamedig) [![Crates.io](https://img.shields.io/crates/d/gamedig.svg)](https://crates.io/crates/gamedig)<div><sub>Stars: 39 / Last Update: 2024-10-03 / Initial Date: 2022-10-14</sub></div>
* [Godot](https://godotengine.org/)
  * [godot-rust/gdnative](https://github.com/godot-rust/gdnative) [[gdnative](https://crates.io/crates/gdnative)] - Godotゲームエンジンへのバインディング [![CI](https://github.com/godot-rust/gdnative/actions/workflows/full-ci.yml/badge.svg)](https://github.com/godot-rust/gdnative/actions/workflows/full-ci.yml)<div><sub>Stars: 3.6k / Last Update: 2024-09-09 / Initial Date: 2017-04-10</sub></div>
* [Raylib](https://www.raylib.com/)
  * [deltaphc/raylib-rs](https://github.com/deltaphc/raylib-rs) [[raylib](https://crates.io/crates/raylib)] - raylib 用バインディング<div><sub>Stars: 753 / Last Update: 2024-08-20 / Initial Date: 2018-07-31</sub></div>
* [SDL](http://www.libsdl.org/) [[sdl](https://crates.io/keywords/sdl)]
  * [Rust-SDL2/rust-sdl2](https://github.com/Rust-SDL2/rust-sdl2) - SDL2バインディング<div><sub>Stars: 2.7k / Last Update: 2024-08-20 / Initial Date: 2013-08-17</sub></div>
* SFML
  * [jeremyletang/rust-sfml](https://github.com/jeremyletang/rust-sfml) - [SFML](https://www.sfml-dev.org/) バインディング<div><sub>Stars: 631 / Last Update: 2024-10-04 / Initial Date: 2013-05-29</sub></div><div><sub>Stars: 631 / Last Update: 2024-10-04 / Initial Date: 2013-05-29</sub></div>
* Skillratings
  * [atomflunder/skillratings](https://github.com/atomflunder/skillratings) [[skillratings](https://crates.io/crates/skillratings)] - Elo、Glicko-2、TrueSkillなどのマルチプレイヤーゲームのスキル評価アルゴリズムのコレクション。[![crates.io badge](https://img.shields.io/crates/v/skillratings)](https://crates.io/crates/skillratings) [![CI](https://github.com/atomflunder/skillratings/actions/workflows/ci.yml/badge.svg)](https://github.com/atomflunder/skillratings/actions/workflows/ci.yml)<div><sub>Stars: 41 / Last Update: 2024-06-08 / Initial Date: 2022-08-09</sub></div>
* Tcod-rs
  * Warning: Not maintained anymore
* Toornament-rs
  * [iddm/toornament-rs](https://github.com/iddm/toornament-rs) - Tornament.comのAPIバインディング。[CI](https://github.com/iddm/toornament-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/iddm/toornament-rs/actions/workflows/ci.yml) [![クレートバッジ]](https://img.shields.io/crates/v/toornament.svg)](https://crates.io/crates/toornament)<div><sub>Stars: 4 / Last Update: 2024-03-20 / Initial Date: 2017-06-01</sub></div>
* Victorem

### Geospatial

[[geo](https://crates.io/keywords/geo), [gis](https://crates.io/keywords/gis)]

* [Georust](https://github.com/georust) - 地理空間ツールおよびライブラリ
* [MapLibre/Martin](https://github.com/maplibre/martin) - PostGIS、MBTiles、PMTiles、スプライトをサポートしたマップタイルサーバー。[![CIビルド](https://github.com/maplibre/martin/actions/workflows/ci.yml/badge.svg)](https://github.com/maplibre/martin/actions)[![crates.ioバージョン](https://img.shields.io/crates/v/martin.svg)](https://crates.io/crates/martin)[![書籍](https://img.shields.io/badge/docs-Book-informational)](https://maplibre.org/martin/)<div><sub>Stars: 2.2k / Last Update: 2024-10-02 / Initial Date: 2017-09-30</sub></div>
* [rust-reverse-geocoder](https://github.com/gx0r/rrgeo) - thampiman/reverse-geocoder](https://github.com/thampiman/reverse-geocoder)にインスパイアされた、高速なオフラインのリバースジオコーダー。<div><sub>Stars: 122 / Last Update: 2024-06-19 / Initial Date: 2015-12-31</sub></div>
* [vlopes11/geomorph](https://github.com/vlopes11/geomorph) [[geomorph](https://crates.io/crates/geomorph)] - UTM、LatLon、MGRS座標間の変換<div><sub>Stars: 14 / Last Update: 2024-09-13 / Initial Date: 2018-06-04</sub></div>

### Graph algorithms

* [neo4j-labs/graph](https://github.com/neo4j-labs/graph) - 高性能グラフアルゴリズムのためのライブラリ [![graph CI status](https://img.shields.io/github/workflow/status/neo4j-labs/graph/CI/main?label=CI)](https://github.com/neo4j-labs/graph/actions/workflows/rust.yml)<div><sub>Stars: 381 / Last Update: 2023-11-22 / Initial Date: 2021-06-11</sub></div>
* [petgraph/petgraph](https://github.com/petgraph/petgraph) - グラフデータ構造ライブラリ。[グラフCIステータス](https://github.com/petgraph/petgraph/workflows/Continuous%20integration/badge.svg?branch=master)](https://github.com/petgraph/petgraph/actions/workflows/ci.yml)<div><sub>Stars: 2.9k / Last Update: 2024-08-19 / Initial Date: 2014-12-22</sub></div>

### Graphics

[[graphics](https://crates.io/keywords/graphics)]

* Font
  * [RazrFalcon/rustybuzz](https://github.com/RazrFalcon/rustybuzz) - Harfbuzzのインクリメンタル移植<div><sub>Stars: 544 / Last Update: 2024-10-04 / Initial Date: 2020-01-12</sub></div>
* [gfx-rs/wgpu](https://github.com/gfx-rs/wgpu) - gfx-hal ベースのネイティブ WebGPU 実装。[ビルドバッジ](https://github.com/gfx-rs/wgpu/workflows/CI/badge.svg?branch=master)](https://github.com/gfx-rs/wgpu/actions)<div><sub>Stars: 12.3k / Last Update: 2024-10-04 / Initial Date: 2018-09-13</sub></div>
* OpenGL [[opengl](https://crates.io/keywords/opengl)]
  * [glium/glium](https://github.com/glium/glium) - 安全なOpenGLラッパー。<div><sub>Stars: 3.5k / Last Update: 2024-09-28 / Initial Date: 2014-10-03</sub></div>
  * [glutin](https://crates.io/crates/glutin) - GLFW](https://www.glfw.org/)の代替案。
  * [Kiss3d](http://kiss3d.org) - draw simple geometric figures and play with them with one-liners
  * [PistonDevelopers/glfw-rs](https://github.com/PistonDevelopers/glfw-rs) - GLFW3バインディングとイディオマティック・ラッパー<div><sub>Stars: 645 / Last Update: 2024-08-04 / Initial Date: 2012-09-15</sub></div>
* PDF
  * [bastibense/libharu_ng](https://github.com/bastibense/libharu_ng) [[libharu_ng](https://crates.io/crates/libharu_ng)] - RustアプリからPDFを簡単に生成。<div><sub>Stars: 14 / Last Update: 2024-06-19 / Initial Date: 2024-01-20</sub></div>
  * [fschutt/printpdf](https://github.com/fschutt/printpdf) - PDFライティング・ライブラリー<div><sub>Stars: 805 / Last Update: 2024-08-05 / Initial Date: 2017-05-09</sub></div>
  * [J-F-Liu/lopdf](https://github.com/J-F-Liu/lopdf) - PDF文書操作<div><sub>Stars: 1.6k / Last Update: 2024-09-30 / Initial Date: 2016-12-13</sub></div>
* [Vulkan](https://www.vulkan.org/) [[vulkan](https://crates.io/keywords/vulkan)]
  * [erupt](https://gitlab.com/Friz64/erupt) [[erupt](https://crates.io/crates/erupt)] - [ビルド・バッジ](https://gitlab.com/Friz64/erupt/badges/main/pipeline.svg)](https://gitlab.com/Friz64/erupt/-/pipelines)
  * [vulkano](https://github.com/vulkano-rs/vulkano) [[vulkano](https://crates.io/crates/vulkano)] - VulkanAPIの安全でリッチなRustラッパー<div><sub>Stars: 4.5k / Last Update: 2024-10-02 / Initial Date: 2015-07-06</sub></div>

### GUI

[[gui](https://crates.io/keywords/gui)]

* Cocoa
  * [servo/core-foundation-rs](https://github.com/servo/core-foundation-rs) - Mac OS XおよびiOSにおけるCore Foundationおよびその他の低レベルライブラリへのRustバインディング<div><sub>Stars: 998 / Last Update: 2024-08-30 / Initial Date: 2012-08-30</sub></div>
* [DioxusLabs/dioxus](https://github.com/dioxuslabs/dioxus) - Rustでクロスプラットフォームのユーザーインターフェイスを構築するための、移植性が高く、パフォーマンスと人間工学に基づいたフレームワークです。rust ci](https://github.com/dioxuslabs/dioxus/actions/workflows/main.yml/badge.svg)<div><sub>Stars: 20.5k / Last Update: 2024-10-03 / Initial Date: 2021-01-15</sub></div>
* [emilk/egui](https://github.com/emilk/egui) - eguiはウェブ上でも、ネイティブでも、お気に入りのゲームエンジンでも動作します。[ビルド状況](https://github.com/emilk/egui/workflows/CI/badge.svg)](https://github.com/emilk/egui/actions?workflow=CI)<div><sub>Stars: 21.9k / Last Update: 2024-10-04 / Initial Date: 2019-01-13</sub></div>
* [emoon/rust_minifb](https://github.com/emoon/rust_minifb) - minifbは、オプションでビットマップレンダリングが可能なクロスプラットフォームのウィンドウセットアップです。また、マウスとキーボードによる簡単な入力も可能です。主にプロトタイピング用に設計されている。<div><sub>Stars: 1.0k / Last Update: 2024-09-26 / Initial Date: 2015-11-22</sub></div>
* [FLTK](https://www.fltk.org/)
  * [fltk-rs](https://github.com/fltk-rs/fltk-rs) - FLTKバインディング [![Build](https://github.com/fltk-rs/fltk-rs/workflows/Build/badge.svg?branch=master)](https://github.com/fltk-rs/fltk-rs/actions)<div><sub>Stars: 1.6k / Last Update: 2024-10-04 / Initial Date: 2019-10-24</sub></div>
* [Flutter](https://flutter.dev/)
  * [cunarist/rinf](https://github.com/cunarist/rinf) - RustをFlutterのバックエンドに、FlutterをRustのフロントエンドに[[ビルド・テスト]](https://github.com/cunarist/rinf/actions/workflows/build_test.yaml/badge.svg)](https://github.com/cunarist/rinf/actions/workflows/build_test.yaml?query=branch%3Amain)<div><sub>Stars: 1.9k / Last Update: 2024-10-03 / Initial Date: 2023-02-15</sub></div>
  * [fzyzcjy/flutter_rust_bridge](https://github.com/fzyzcjy/flutter_rust_bridge) - Flutter/Dart <-> Rust 用高レベルメモリーセーフ・バインディング・ジェネレーター<div><sub>Stars: 4.2k / Last Update: 2024-10-02 / Initial Date: 2021-10-04</sub></div>
* [fschutt/azul](https://github.com/fschutt/azul) - Rustで書かれたデスクトップアプリケーションを迅速に開発するための、フリーで機能的なIMGUI指向のGUIフレームワークで、Mozilla WebRenderレンダリングエンジンでサポートされています。<div><sub>Stars: 5.9k / Last Update: 2024-05-29 / Initial Date: 2018-01-16</sub></div>
* [GTK+](https://www.gtk.org/) [[gtk](https://crates.io/keywords/gtk)]
  * [gtk-rs/gtk4-rs](https://github.com/gtk-rs/gtk4-rs) - GTK4バインディング ![CI](https://github.com/gtk-rs/gtk4-rs/workflows/CI/badge.svg)<div><sub>Stars: 1.8k / Last Update: 2024-09-30 / Initial Date: 2019-05-13</sub></div>
  * [relm](https://github.com/antoyo/relm) - Elmにインスパイアされた、非同期、GTK+ベースのGUIライブラリ<div><sub>Stars: 2.4k / Last Update: 2024-04-19 / Initial Date: 2017-02-10</sub></div>
* [iced-rs/iced](https://github.com/iced-rs/iced) [[iced](https://crates.io/crates/iced)] - シンプルさと型安全性を重視したクロスプラットフォームGUIライブラリ。Elmにインスパイアされています。<div><sub>Stars: 24.4k / Last Update: 2024-10-04 / Initial Date: 2019-07-15</sub></div>
* [ImGui](https://github.com/ocornut/imgui)
  * [imgui-rs](https://github.com/imgui-rs/imgui-rs) - ImGui 用バインディング [![ビルド状況](https://github.com/imgui-rs/imgui-rs/workflows/ci/badge.svg?branch=master)](https://github.com/imgui-rs/imgui-rs/actions)<div><sub>Stars: 2.6k / Last Update: 2024-10-03 / Initial Date: 2015-08-16</sub></div>
* [IUP](http://webserver2.tecgraf.puc-rio.br/iup/)
* [makepad/makepad](https://github.com/makepad/makepad) [[makepad-widgets](https://crates.io/crates/makepad-widgets)] - Makepadは、wasm/webGL、osx/metal、windows/dx11 linux/openglにコンパイルできるクリエイティブなソフトウェア開発プラットフォームです。<div><sub>Stars: 5.1k / Last Update: 2024-10-04 / Initial Date: 2019-02-20</sub></div>
* [Nuklear](https://github.com/Immediate-Mode-UI/Nuklear)
* [Qt](https://doc.qt.io)
  * [rust-qt](https://github.com/rust-qt) - Rust用Qtバインディング
  * [woboq/qmetaobject-rs](https://github.com/woboq/qmetaobject-rs) - コンパイル時にQMetaObjectをビルドすることで、QmlとRustを統合します。<div><sub>Stars: 638 / Last Update: 2024-08-07 / Initial Date: 2018-06-06</sub></div>
* [Sciter](https://sciter.com/)
* [slint-ui/slint](https://github.com/slint-ui/slint) [slint](https://crates.io/crates/slint) - [Slint](https://slint.dev/)は、組み込み機器やデスクトップアプリケーション向けの流体グラフィカル・ユーザー・インターフェースを効率的に開発するためのツールキットです。[ビルド状況](https://github.com/slint-ui/slint/workflows/CI/badge.svg?branch=master)](https://github.com/slint-ui/slint/actions?query=workflow%3ACI)<div><sub>Stars: 17.1k / Last Update: 2024-10-04 / Initial Date: 2020-05-04</sub></div><div><sub>Stars: 17.1k / Last Update: 2024-10-05 / Initial Date: 2020-05-04</sub></div>
* [tauri-apps/tauri](https://github.com/tauri-apps/tauri) - WRY](https://github.com/tauri-apps/wry)によるウェブフロントエンドで、より小さく、より速く、より安全なデスクトップアプリケーションを構築しましょう。[テストライブラリ](https://img.shields.io/github/workflow/status/tauri-apps/tauri/test%20library?label=test%20library)](https://github.com/tauri-apps/tauri/actions?query=workflow%3A%22test+library%22)<div><sub>Stars: 82.6k / Last Update: 2024-10-04 / Initial Date: 2019-07-13</sub></div>
* [tauri-apps/tauri](https://github.com/tauri-apps/tauri) - WRY](https://github.com/tauri-apps/wry)によるウェブフロントエンドで、より小さく、より速く、より安全なデスクトップアプリケーションを構築しましょう。[テストライブラリ](https://img.shields.io/github/workflow/status/tauri-apps/tauri/test%20library?label=test%20library)](https://github.com/tauri-apps/tauri/actions?query=workflow%3A%22test+library%22)<div><sub>Stars: 82.6k / Last Update: 2024-10-04 / Initial Date: 2019-07-13</sub></div>
* [tauri-apps/wry](https://github.com/tauri-apps/wry) - ウェブビューレンダリングライブラリ。<div><sub>Stars: 3.6k / Last Update: 2024-10-04 / Initial Date: 2020-07-12</sub></div>
* [xilem](https://github.com/linebender/xilem) - データファーストUIデザインツールキット[druid](https://github.com/linebender/druid)の後継。<div><sub>Stars: 3.6k / Last Update: 2024-10-04 / Initial Date: 2022-11-16</sub></div>
* [xilem](https://github.com/linebender/xilem) - データファーストUIデザインツールキット[druid](https://github.com/linebender/druid)の後継。<div><sub>Stars: 3.6k / Last Update: 2024-10-04 / Initial Date: 2022-11-16</sub></div>

### Image processing

* [Enet4/dicom-rs](https://github.com/Enet4/dicom-rs) - DICOM標準の純粋なRust実装で、ユーザーはDICOMオブジェクトを操作し、DICOMアプリケーションと対話することができます。<div><sub>Stars: 416 / Last Update: 2024-09-13 / Initial Date: 2016-10-23</sub></div>
* [image-rs/image](https://github.com/image-rs/image) - 基本的な画像処理機能と画像フォーマットとの変換方法<div><sub>Stars: 4.9k / Last Update: 2024-10-02 / Initial Date: 2014-05-25</sub></div>
* [image-rs/imageproc](https://github.com/image-rs/imageproc) - image` ライブラリをベースにした画像処理ライブラリ。<div><sub>Stars: 743 / Last Update: 2024-09-19 / Initial Date: 2015-09-27</sub></div>
* [twistedfall/opencv-rust](https://github.com/twistedfall/opencv-rust) - OpenCV用バインディング<div><sub>Stars: 2.0k / Last Update: 2024-09-30 / Initial Date: 2015-04-14</sub></div>

### Language specification

* [shnewto/bnf](https://github.com/shnewto/bnf) - Backus-Naur形式の文脈自由文法を解析するためのライブラリ。<div><sub>Stars: 256 / Last Update: 2024-10-02 / Initial Date: 2017-10-23</sub></div>

### Logging

[[log](https://crates.io/keywords/log)]

* [donnie4w/tklog](https://github.com/donnie4w/tklog "donnie4w/tklog") - ログレベル、ファイルセグメンテーション、圧縮アーカイブをサポートする、軽量で効率的な錆構造ログライブラリ。
* [estk/log4rs](https://github.com/estk/log4rs) - JavaのLogbackとlog4jライブラリをモデルにした、高度に設定可能なロギング・フレームワーク [![CircleCI]](https://circleci.com/gh/estk/log4rs.svg?style=shield)](https://app.circleci.com/pipelines/github/estk/log4rs)<div><sub>Stars: 998 / Last Update: 2024-08-07 / Initial Date: 2015-01-27</sub></div>
* [rbatis/fast_log](https://github.com/rbatis/fast_log) - 非同期ログ 高性能な非同期ロギング<div><sub>Stars: 240 / Last Update: 2024-09-14 / Initial Date: 2020-02-29</sub></div>
* [rust-lang/log](https://github.com/rust-lang/log) - ロギングの実装<div><sub>Stars: 2.2k / Last Update: 2024-08-02 / Initial Date: 2014-12-13</sub></div>
* [slog-rs/slog](https://github.com/slog-rs/slog) - 構造化された、コンポーザブルなロギング<div><sub>Stars: 1.6k / Last Update: 2024-09-23 / Initial Date: 2016-06-12</sub></div>
* [tokio-rs/tracing](https://github.com/tokio-rs/tracing) - 非同期を意識した構造化ロギング、エラー処理、メトリクスなどのためのアプリケーション・レベルのトレース・フレームワーク [![ビルド・ステータス]](https://github.com/tokio-rs/tracing/workflows/CI/badge.svg?branch=master)](https://github.com/tokio-rs/tracing/actions?query=workflow%3ACI)<div><sub>Stars: 5.4k / Last Update: 2024-10-04 / Initial Date: 2019-01-11</sub></div>

### Macro

* cute

### Markup language

* CommonMark
  * [pulldown-cmark/pulldown-cmark](https://github.com/pulldown-cmark/pulldown-cmark) - [コモンマーク](https://commonmark.org/)パーサー<div><sub>Stars: 2.0k / Last Update: 2024-09-24 / Initial Date: 2015-06-03</sub></div><div><sub>Stars: 2.0k / Last Update: 2024-09-24 / Initial Date: 2015-06-03</sub></div>
* [insomnimus/tidier](https://github.com/insomnimus/tidier) [[tidier](https://crates.io/crates/tidier)] - HTML、XHTML、XML文書をフォーマットするためのライブラリ。[ビルドバッジ](https://github.com/insomnimus/tidier/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/insomnimus/tidier/actions)<div><sub>Stars: 4 / Last Update: 2024-08-27 / Initial Date: 2023-12-18</sub></div>

### Mobile

* Android / iOS
* Generic
  * [redbadger/crux](https://github.com/redbadger/crux) [[crux_core](https://crates.io/crates/crux_core)] - クロスプラットフォーム・アプリ開発。Cruxは、モバイル（iOS/Android）とウェブでアプリのビジネスロジックと動作を共有するのに役立ちます。<div><sub>Stars: 1.7k / Last Update: 2024-10-01 / Initial Date: 2022-10-08</sub></div>
* iOS
  * [TimNN/cargo-lipo](https://github.com/TimNN/cargo-lipo) - iOSアプリケーションで使用するユニバーサル・ライブラリを自動的に作成するカーゴ・リポ・サブコマンド。<div><sub>Stars: 534 / Last Update: 2024-05-27 / Initial Date: 2015-09-21</sub></div>

### Network programming

* Bluetooth
  * [bluez/bluer](https://github.com/bluez/bluer) [[bluer](https://crates.io/crates/bluer)] - BlueZ公式バインディング。[ビルドバッジ](https://github.com/bluez/bluer/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/bluez/bluer/actions/workflows/rust.yml)<div><sub>Stars: 310 / Last Update: 2024-08-20 / Initial Date: 2021-07-05</sub></div>
* CoAP
  * [Covertness/coap-rs](https://github.com/Covertness/coap-rs) - Constrained Application Protocol(CoAP)](https://datatracker.ietf.org/doc/html/rfc7252)ライブラリ。<div><sub>Stars: 209 / Last Update: 2024-09-04 / Initial Date: 2015-07-12</sub></div>
* Docker
  * [fussybeaver/bollard](https://github.com/fussybeaver/bollard) - DockerデーモンAPI<div><sub>Stars: 881 / Last Update: 2024-10-02 / Initial Date: 2018-06-19</sub></div>
* FTP
* gRPC
  * [hyperium/tonic](https://github.com/hyperium/tonic) - 非同期/待機をサポートしたネイティブなgRPCクライアントとサーバの実装 [![Crates.io]](https://img.shields.io/crates/v/tonic)](https://crates.io/crates/tonic)<div><sub>Stars: 9.8k / Last Update: 2024-10-03 / Initial Date: 2019-08-09</sub></div>
  * [tikv/grpc-rs](https://github.com/tikv/grpc-rs) - Cコアライブラリとフューチャーズで構築されたgRPCライブラリ<div><sub>Stars: 1.8k / Last Update: 2024-08-13 / Initial Date: 2017-04-21</sub></div>
* HTTP
  * [Hurl](https://github.com/Orange-OpenSource/hurl) - プレーンテキストとlibcurlを使ったHTTPリクエストの実行とテスト [![CI](https://github.com/Orange-OpenSource/hurl/workflows/CI/badge.svg)](https://github.com/Orange-OpenSource/hurl/actions)<div><sub>Stars: 12.9k / Last Update: 2024-10-05 / Initial Date: 2020-08-25</sub></div>
* IPNetwork
  * [achanda/ipnetwork](https://github.com/achanda/ipnetwork) - IPネットワークを扱うためのライブラリ<div><sub>Stars: 121 / Last Update: 2024-09-24 / Initial Date: 2015-04-18</sub></div>
* Low level
  * [actix/actix](https://github.com/actix/actix) - 俳優ライブラリー<div><sub>Stars: 8.6k / Last Update: 2024-09-23 / Initial Date: 2017-09-18</sub></div>
  * [libpnet/libpnet](https://github.com/libpnet/libpnet) - クロスプラットフォームの低レベルネットワーキング<div><sub>Stars: 2.3k / Last Update: 2024-08-02 / Initial Date: 2014-08-31</sub></div>
  * [smoltcp-rs/smoltcp](https://github.com/smoltcp-rs/smoltcp) - ベアメタル、リアルタイムシステム用に設計されたスタンドアロン、イベントドリブンTCP/IPスタック<div><sub>Stars: 3.8k / Last Update: 2024-09-30 / Initial Date: 2016-12-02</sub></div>
* message-io
  * [lemunozm/message-io](https://github.com/lemunozm/message-io) - ネットワーク・アプリケーションを簡単かつ高速に構築するためのイベント駆動型メッセージ・ライブラリ。TCP、UDP、WebSocketをサポートしています。[ビルド・バッジ](https://img.shields.io/github/workflow/status/lemunozm/message-io/message-io%20ci)](https://github.com/lemunozm/message-io/actions?query=workflow%3A%22message-io+ci%22)<div><sub>Stars: 1.1k / Last Update: 2024-07-11 / Initial Date: 2020-07-03</sub></div>
* MQTT
  * [bytebeamio/rumqtt](https://github.com/bytebeamio/rumqtt) - MQTTプロトコル](https://mqtt.org)とTCPとWebSocketで、TLSの有無にかかわらず通信するアプリケーションを開発するためのライブラリです。[ビルドとテスト](https://github.com/bytebeamio/rumqtt/actions/workflows/build.yml/badge.svg)](https://github.com/bytebeamio/rumqtt/actions/workflows/build.yml)<div><sub>Stars: 1.6k / Last Update: 2024-10-02 / Initial Date: 2019-10-15</sub></div>
  * [rmqtt/rmqtt](https://github.com/rmqtt/rmqtt) - MQTTサーバー/MQTTブローカー<div><sub>Stars: 538 / Last Update: 2024-09-30 / Initial Date: 2021-03-09</sub></div>
* NanoMsg
  * [thehydroimpulse/nanomsg.rs](https://github.com/thehydroimpulse/nanomsg.rs) - [nanomsg](https://nanomsg.org/) バインディング<div><sub>Stars: 391 / Last Update: 2023-11-02 / Initial Date: 2013-09-07</sub></div><div><sub>Stars: 391 / Last Update: 2023-11-02 / Initial Date: 2013-09-07</sub></div>
* NATS
  * [nats-io/nats.rs](https://github.com/nats-io/nats.rs) - クラウド・ネイティブ・メッセージング・システム NATS のクライアント。[ビルド状況](https://github.com/nats-io/nats.rs/workflows/Rust/badge.svg?branch=master)](https://github.com/nats-io/nats.rs/actions)<div><sub>Stars: 1.0k / Last Update: 2024-10-04 / Initial Date: 2020-02-24</sub></div>
* Nng
  * [neachdainn/nng-rs](https://gitlab.com/neachdainn/nng-rs) [[Nng](https://crates.io/crates/nng)] - [Nng (nanomsg v2)](https://nng.nanomsg.org/index.html) バインディング [![ビルドバッジ]](https://gitlab.com/neachdainn/nng-rs/badges/master/pipeline.svg)](https://gitlab.com/neachdainn/nng-rs/-/pipelines)
* NNTP
* P2P
  * [libp2p/rust-libp2p](https://github.com/libp2p/rust-libp2p) - libp2pネットワークスタックの実装。[サークルCI](https://circleci.com/gh/libp2p/rust-libp2p.svg?style=svg)](https://app.circleci.com/pipelines/github/libp2p/rust-libp2p)<div><sub>Stars: 4.5k / Last Update: 2024-10-04 / Initial Date: 2017-03-24</sub></div>
  * [n0-computer/iroh](https://github.com/n0-computer/iroh) [[iroh](https://crates.io/crates/iroh)] - デバイス間の直接接続を構築するための木枠[![CI]](https://github.com/n0-computer/iroh/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/n0-computer/iroh/actions/workflows/ci.yml)<div><sub>Stars: 2.4k / Last Update: 2024-10-04 / Initial Date: 2022-03-14</sub></div>
* POP3
* QUIC
  * [aws/s2n-quic](https://github.com/aws/s2n-quic) - IETF QUICプロトコルの実装 ![ci](https://img.shields.io/github/actions/workflow/status/aws/s2n-quic/ci.yml?branch=main)<div><sub>Stars: 1.1k / Last Update: 2024-10-04 / Initial Date: 2020-06-25</sub></div>
  * [cloudflare/quiche](https://github.com/cloudflare/quiche) - cloudflareによるQUICトランスポートプロトコルとHTTP/3の実装 ![build](https://img.shields.io/github/actions/workflow/status/cloudflare/quiche/stable.yml?branch=master)<div><sub>Stars: 9.3k / Last Update: 2024-10-02 / Initial Date: 2018-09-29</sub></div>
  * [mozilla/neqo](https://github.com/mozilla/neqo) - QUICの実装<div><sub>Stars: 1.8k / Last Update: 2024-10-04 / Initial Date: 2019-02-18</sub></div>
  * [quinn-rs/quinn](https://github.com/quinn-rs/quinn) - 先物ベースのQUIC実装 [![ビルド・バッジ]](https://dev.azure.com/dochtman/Projects/_apis/build/status/Quinn?branchName=master)](https://dev.azure.com/dochtman/Projects/_build)<div><sub>Stars: 3.8k / Last Update: 2024-10-03 / Initial Date: 2018-04-03</sub></div>
  * [tencent/tquic](https://github.com/Tencent/tquic) - 高性能、軽量、クロスプラットフォームのQUICライブラリ [![ビルド状況](https://img.shields.io/github/actions/workflow/status/tencent/tquic/rust.yml)](https://github.com/Tencent/tquic/actions/workflows/rust.yml)<div><sub>Stars: 1.1k / Last Update: 2024-09-27 / Initial Date: 2023-10-26</sub></div>
* Raknet
* RPC
  * [ENQT-GmbH/remoc](https://github.com/ENQT-GmbH/remoc) [[remoc](https://crates.io/crates/remoc)] - RemocはTokioと同様のチャンネル(broadcast, mpsc, oneshot, watch)を提供し、どのようなリモート・トランスポート上でも呼び出しが可能です。[ビルドバッジ](https://github.com/ENQT-GmbH/remoc/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/ENQT-GmbH/remoc/actions/workflows/rust.yml)<div><sub>Stars: 172 / Last Update: 2024-09-27 / Initial Date: 2021-07-01</sub></div>
  * [smallnest/rpcx-rs](https://github.com/smallnest/rpcx-rs) - マイクロサービスを簡単かつシンプルに開発するためのRPCライブラリ。<div><sub>Stars: 127 / Last Update: 2024-03-13 / Initial Date: 2019-07-28</sub></div>
* Socket.io
  * [1c3t3a/rust-socketio](https://github.com/1c3t3a/rust-socketio) [[rust_socketio](https://crates.io/crates/rust_socketio)] - Rustで書かれた[socket.io](https://socket.io)クライアントの実装です。[ビルド・バッジ](https://github.com/1c3t3a/rust-socketio/actions/workflows/build.yml/badge.svg)](https://github.com/1c3t3a/rust-socketio/actions/workflows/build.yml)<div><sub>Stars: 408 / Last Update: 2024-10-01 / Initial Date: 2020-12-28</sub></div>
* SSH
  * [alexcrichton/ssh2-rs](https://github.com/alexcrichton/ssh2-rs) - [libssh2](https://libssh2.org/) バインディング<div><sub>Stars: 485 / Last Update: 2024-07-31 / Initial Date: 2014-09-18</sub></div><div><sub>Stars: 486 / Last Update: 2024-07-31 / Initial Date: 2014-09-18</sub></div>
  * [Thrussh](https://pijul.org/thrussh) [[thrussh](https://crates.io/crates/thrussh)] - libsodium](https://doc.libsodium.org/) にバックアップされた SSH ライブラリ。
* Stomp
* VPN
  * [defguard/wireguard-rs](https://github.com/DefGuard/wireguard-rs) - OS カーネルおよびユーザー空間のネイティブ WireGuard プロトコル実装を使用して WireGuard インターフェースを管理するための統一ハイレベル API を提供するマルチプラットフォームライブラリ。<div><sub>Stars: 141 / Last Update: 2024-10-04 / Initial Date: 2023-08-24</sub></div>
* Zenoh
  * [eclipse-zenoh-flow/zenoh-flow](https://github.com/eclipse-zenoh-flow/zenoh-flow) - クラウド*から*モノ*にまたがる計算のための宣言的フレームワーク<div><sub>Stars: 89 / Last Update: 2024-08-16 / Initial Date: 2021-05-17</sub></div>
  * [eclipse-zenoh/zenoh](https://github.com/eclipse-zenoh/zenoh) - ゼロ・オーバーヘッド・ネットワーク・プロトコル<div><sub>Stars: 1.4k / Last Update: 2024-10-05 / Initial Date: 2020-01-21</sub></div>
* ZeroMQ

### Parsing

  * [comex/rust-shlex](https://github.com/comex/rust-shlex) [[shlex](https://crates.io/crates/shlex)] - Pythonのshlexのように、文字列をシェル語に分割する。[ビルド・バッジ](https://github.com/comex/rust-shlex/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/comex/rust-shlex/actions/workflows/test.yml)<div><sub>Stars: 101 / Last Update: 2024-01-22 / Initial Date: 2015-06-22</sub></div>
  * [Eliah-Lakhin/lady-deirdre](https://github.com/Eliah-Lakhin/lady-deirdre) - 新しいプログラミング言語とLSPサーバーのためのフレームワーク。<div><sub>Stars: 443 / Last Update: 2024-09-03 / Initial Date: 2022-11-08</sub></div>
  * [hmeyer/stl_io](https://crates.io/crates/stl_io) - STL (STereoLithography) ファイルのパーサー
  * [igumnoff/shiva](https://github.com/igumnoff/shiva) - Shivaライブラリ：あらゆるタイプのドキュメント（プレーンテキスト、Markdown、HTML、PDFなど）のパーサとジェネレータをRustで実装。<div><sub>Stars: 168 / Last Update: 2024-09-25 / Initial Date: 2024-03-18</sub></div>
  * [kevinmehall/rust-peg](https://github.com/kevinmehall/rust-peg) - パーシング表現文法（PEG）パーサー・ジェネレーター<div><sub>Stars: 1.5k / Last Update: 2024-07-21 / Initial Date: 2013-08-19</sub></div>
  * [lalrpop/lalrpop](https://github.com/lalrpop/lalrpop) - LR(1)パーサー生成器<div><sub>Stars: 3.0k / Last Update: 2024-10-04 / Initial Date: 2015-06-12</sub></div>
  * [Marwes/combine](https://github.com/Marwes/combine) - パーサ・コンビネータ・ライブラリ<div><sub>Stars: 1.3k / Last Update: 2024-04-10 / Initial Date: 2015-01-12</sub></div>
  * [pest-parser/pest](https://github.com/pest-parser/pest) - エレガントなパーサー<div><sub>Stars: 4.6k / Last Update: 2024-09-27 / Initial Date: 2016-04-24</sub></div>
  * [rust-bakery/nom](https://github.com/rust-bakery/nom) - パーサ・コンビネータ・ライブラリ<div><sub>Stars: 9.4k / Last Update: 2024-08-12 / Initial Date: 2014-11-23</sub></div>
  * [softdevteam/grmtools](https://github.com/softdevteam/grmtools/) - 誤り訂正機能を強化したLRパーサー<div><sub>Stars: 507 / Last Update: 2024-09-30 / Initial Date: 2018-08-06</sub></div>
  * [tree-sitter/tree-sitter](https://github.com/tree-sitter/tree-sitter) - プログラミングツール向けのパーサー生成ツールとインクリメンタルなパーシングライブラリ<div><sub>Stars: 18.2k / Last Update: 2024-10-05 / Initial Date: 2013-11-06</sub></div>

### Peripherals

* Fingerprint reader
  * [alvaroparker/libfprint-rs](https://github.com/alvaroparker/libfprint-rs) [[libfprint-rs](https://crates.io/crates/libfprint-rs)] - Libfprint-rsは、Linuxのlibfprintライブラリーのラッパーを提供する。<div><sub>Stars: 11 / Last Update: 2024-10-02 / Initial Date: 2023-06-20</sub></div>
* Serial Port
  * [serialport/serialport-rs](https://github.com/serialport/serialport-rs) [[serialport](https://crates.io/crates/serialport)] - シリアルポートへのアクセスを提供するクロスプラットフォームライブラリ<div><sub>Stars: 478 / Last Update: 2024-09-28 / Initial Date: 2022-02-07</sub></div>

### Platform specific

* Cross-platform
  * [iddm/thread-priority](https://github.com/iddm/thread-priority/) - シンプルでクロスプラットフォームなスレッド優先度管理。[CI](https://github.com/iddm/thread-priority/actions/workflows/ci.yml/badge.svg)](https://github.com/iddm/thread-priority/actions/workflows/ci.yml) [![クレート・バッジ]](https://img.shields.io/crates/v/thread-priority.svg)](https://crates.io/crates/thread-priority)<div><sub>Stars: 108 / Last Update: 2024-04-29 / Initial Date: 2017-06-22</sub></div>
  * [svartalf/rust-battery](https://crates.io/crates/battery) - ノートパソコンのバッテリーに関するクロスプラットフォーム情報
* FreeBSD
  * [fubarnetes/libjail-rs](https://github.com/fubarnetes/libjail-rs/) [[jail](https://crates.io/crates/jail)] - FreeBSD jail ライブラリ<div><sub>Stars: 50 / Last Update: 2024-10-01 / Initial Date: 2018-05-16</sub></div>
* Linux
  * [hannobraun/inotify-rs](https://github.com/hannobraun/inotify-rs) - [inotify](https://en.wikipedia.org/wiki/Inotify) バインディング [![Rust](https://github.com/hannobraun/inotify-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/hannobraun/inotify-rs/actions/workflows/rust.yml)<div><sub> 星数: 256 / 最終更新日: 2024-09-18 / 初回更新日: 2014-04-10</sub></div><div><sub>Stars: 256 / Last Update: 2024-09-18 / Initial Date: 2014-04-10</sub></div>
  * [pop-os/distinst](https://github.com/pop-os/distinst/) - Linuxディストリビューションのインストーラー<div><sub>Stars: 222 / Last Update: 2024-07-31 / Initial Date: 2017-08-28</sub></div>
* Unix-like
  * [nix-rust/nix](https://github.com/nix-rust/nix) - UnixライクなAPIバインディング [![Cirrus Build Status](https://api.cirrus-ci.com/github/nix-rust/nix.svg)](https://cirrus-ci.com/github/nix-rust/nix)<div><sub>Stars: 2.6k / Last Update: 2024-09-27 / Initial Date: 2014-08-07</sub></div>
  * [rustix](https://github.com/bytecodealliance/rustix) - POSIX/Unix/Linux/Winsock2のシステムコールへの安全なバインディング [![Actions Status](https://github.com/bytecodealliance/rustix/workflows/CI/badge.svg)](https://github.com/bytecodealliance/rustix/actions?query=workflow%3ACI)<div><sub>Stars: 1.5k / Last Update: 2024-10-05 / Initial Date: 2020-09-14</sub></div>
* Windows
  * [microsoft/windows-rs](https://github.com/microsoft/windows-rs) - Rust for Windows [![アクションステータス]](https://github.com/microsoft/windows-rs/workflows/CI/badge.svg)](https://github.com/microsoft/windows-rs/actions)<div><sub>Stars: 10.4k / Last Update: 2024-10-04 / Initial Date: 2019-09-12</sub></div>

### Scripting

[[scripting](https://crates.io/keywords/scripting)]

* [3body-lang](https://github.com/rustq/3body-lang) - 3つのボディランゲージ<div><sub>Stars: 180 / Last Update: 2024-09-29 / Initial Date: 2023-02-08</sub></div>
* [clarkmcc/cel-rust](https://github.com/clarkmcc/cel-rust) [[cel-interpreter](https://crates.io/crates/cel-interpreter)] - 共通表現言語パーサーとインタープリター<div><sub>Stars: 366 / Last Update: 2024-10-02 / Initial Date: 2023-04-27</sub></div>
* [duckscript](https://crates.io/crates/duckscript) - [シンプルで、拡張可能で、埋め込み可能なスクリプト言語。](https://github.com/sagiegurari/duckscript) [![ビルド・バッジ](https://github.com/sagiegurari/duckscript/workflows/CI/badge.svg?branch=master)](https://github.com/sagiegurari/duckscript/actions)<div><sub>Stars: 512 / Last Update: 2024-10-04 / Initial Date: 2019-12-12</sub></div><div><sub>Stars: 512 / Last Update: 2024-10-04 / Initial Date: 2019-12-12</sub></div>
* [gluon-lang/gluon](https://github.com/gluon-lang/gluon) - 小さな静的型付け関数型プログラミング言語<div><sub>Stars: 3.2k / Last Update: 2024-03-03 / Initial Date: 2015-08-02</sub></div>
* [kcl](https://github.com/kcl-lang/kcl) - 主にコンフィギュレーションやポリシーのシナリオで使用される制約ベースのレコード＆関数型言語。<div><sub>Stars: 1.6k / Last Update: 2024-09-24 / Initial Date: 2022-05-05</sub></div>
* [metacall/core](https://github.com/metacall/core) [[metacall](https://crates.io/crates/metacall)] - NodeJS、JavaScript、TypeScript、Python、Ruby、C#、Wasm、Java、Cobolなどをサポートするクロスプラットフォームのポリグロット・ランタイム。[ビルドバッジ](https://gitlab.com/metacall/core/badges/master/pipeline.svg)](https://gitlab.com/metacall/core)<div><sub>Stars: 1.6k / Last Update: 2024-09-25 / Initial Date: 2018-12-26</sub></div>
* [mun](https://github.com/mun-lang/mun) - コンパイル済みの静的型付けスクリプト言語であり、ファーストクラスのホットリローディングをサポートする。<div><sub>Stars: 1.9k / Last Update: 2024-09-19 / Initial Date: 2019-07-21</sub></div>
* [PistonDevelopers/dyon](https://github.com/PistonDevelopers/dyon) - 錆びた動的型付けスクリプト言語<div><sub>Stars: 1.8k / Last Update: 2024-02-28 / Initial Date: 2016-01-23</sub></div>
* [rhaiscript/rhai](https://github.com/rhaiscript/rhai) - JavaScriptとRustを組み合わせたような、小さくて高速な組み込みスクリプト言語 [![ビルド・バッジ]](https://github.com/rhaiscript/rhai/workflows/Build/badge.svg)](https://github.com/rhaiscript/rhai/actions)<div><sub>Stars: 3.8k / Last Update: 2024-10-04 / Initial Date: 2016-02-29</sub></div>
* [rune-rs/rune](https://github.com/rune-rs/rune) - 埋め込み可能な動的プログラミング言語<div><sub>Stars: 1.7k / Last Update: 2024-09-28 / Initial Date: 2020-07-25</sub></div>

### Simulation

[[simulation](https://crates.io/keywords/simulation)]

* [nyx-space](https://crates.io/crates/nyx-space) - 高忠実度、高速、高信頼性、検証済みの天体力学ツールキットライブラリで、宇宙船のミッション設計や軌道決定に使用される[[ビルド状況]](https://gitlab.com/nyx-space/nyx/badges/master/pipeline.svg)](https://gitlab.com/nyx-space/nyx/-/pipelines)

### Social networks

* Telegram
  * [tdilb-rs](https://github.com/FedericoBruzzone/tdlib-rs) [[tdilb-rs](https://crates.io/crates/tdlib-rs)] - Telegram Database Library (TDLib) のクロスプラットフォーム Rust ラッパー [![CI Linux](https://github.com/FedericoBruzzone/tdlib-rs/actions/workflows/ci-linux.yml/badge.svg)](https://github.com/FedericoBruzzone/tdlib-rs/actions/workflows/ci-linux.yml) [![CI macOS](https://github.com/FedericoBruzzone/tdlib-rs/actions/workflows/ci-macos.yml/badge.svg)](https://github.com/FedericoBruzzone/tdlib-rs/actions/workflows/ci-macos.yml) [![CI Windows](https://github.com/FedericoBruzzone/tdlib-rs/actions/workflows/ci-windows.yml/badge.svg)](https://github.com/FedericoBruzzone/tdlib-rs/actions/workflows/ci-windows.yml)<div><sub>Stars: 39 / Last Update: 2024-08-12 / Initial Date: 2024-05-19</sub></div>

### System

* [ardaku/whoami](https://github.com/ardaku/whoami) [[whoami](https://crates.io/crates/whoami)] - クレートで現在のユーザーと環境を取得する。[ビルド・バッジ](https://github.com/ardaku/whoami/actions/workflows/ci.yml/badge.svg?branch=stable)](https://github.com/ardaku/whoami/actions/workflows/ci.yml)<div><sub>Stars: 185 / Last Update: 2024-09-03 / Initial Date: 2017-07-29</sub></div>
* [GuillaumeGomez/sysinfo](https://github.com/GuillaumeGomez/sysinfo) [[sysinfo](https://crates.io/crates/sysinfo)] - システム情報を取得するクロスプラットフォーム・ライブラリ [![ビルド・バッジ]](https://github.com/GuillaumeGomez/sysinfo/actions/workflows/CI.yml/badge.svg?branch=master)](https://github.com/GuillaumeGomez/sysinfo/actions/workflows/CI.yml)<div><sub>Stars: 2.0k / Last Update: 2024-10-03 / Initial Date: 2015-03-10</sub></div>
* [sorairolake/sysexits-rs](https://github.com/sorairolake/sysexits-rs) [[sysexits](https://crates.io/crates/sysexits)] - <<sysexits.h>`](https://manpages.ubuntu.com/manpages/lunar/man3/sysexits.h.3head.html)で定義されているシステム終了コード。![CI](https://github.com/sorairolake/sysexits-rs/workflows/CI/badge.svg?branch=develop)](https://github.com/sorairolake/sysexits-rs/actions?query=workflow%3ACI)<div><sub>Stars: 22 / Last Update: 2024-10-01 / Initial Date: 2022-05-28</sub></div>

### Task scheduling

* [delay-timer](https://github.com/BinChengZhao/delay-timer) - 遅延タスクのタイムマネージャー。crontabのようなものだが、非同期タスクも可能。[ビルド](https://github.com/BinChengZhao/delay-timer/actions/workflows/rust.yml/badge.svg)]( https://github.com/BinChengZhao/delay-timer/actions)<div><sub>Stars: 311 / Last Update: 2024-05-20 / Initial Date: 2020-06-01</sub></div>

### Template engine

* Handlebars
  * [sunng87/handlebars-rust](https://github.com/sunng87/handlebars-rust) - 継承、カスタムヘルパーをサポートしたHandlebarsテンプレートエンジン。<div><sub>Stars: 1.3k / Last Update: 2024-10-04 / Initial Date: 2014-12-21</sub></div>
  * [zzau13/yarte](https://github.com/zzau13/yarte) - Yarteは**Y**et **A**nother **R**ust **T**emplate **E**Engineの略で、最速のテンプレートエンジンです。<div><sub>Stars: 280 / Last Update: 2024-08-07 / Initial Date: 2019-07-06</sub></div>
* HTML
  * [djc/askama](https://github.com/djc/askama) - Jinjaベースのテンプレート・レンダリング・エンジン<div><sub>Stars: 3.4k / Last Update: 2024-09-28 / Initial Date: 2016-12-22</sub></div>
  * [kaj/ructe](https://github.com/kaj/ructe) - HTMLテンプレートシステム<div><sub>Stars: 453 / Last Update: 2024-06-30 / Initial Date: 2016-09-15</sub></div>
  * [Keats/tera](https://github.com/Keats/tera) - Jinja2 と Django テンプレート言語に基づいたテンプレートエンジンです。[アクションステータス](https://github.com/Keats/tera/workflows/ci/badge.svg?branch=master)](https://github.com/Keats/tera/actions)<div><sub>Stars: 3.5k / Last Update: 2024-07-25 / Initial Date: 2015-07-17</sub></div>
  * [lambda-fairy/maud](https://github.com/lambda-fairy/maud) - コンパイル時HTMLテンプレート<div><sub>Stars: 2.1k / Last Update: 2024-10-05 / Initial Date: 2014-12-17</sub></div>
* Mustache

### Text processing

* [becheran/wildmatch](https://github.com/becheran/wildmatch) [[wildmatch](https://crates.io/crates/wildmatch)] - クエスチョンマークと星形ワイルドカード演算子による単純な文字列マッチング [![アクションステータス]](https://github.com/becheran/wildmatch/workflows/Build/badge.svg?branch=master)](https://github.com/becheran/wildmatch/actions)<div><sub>Stars: 74 / Last Update: 2024-09-30 / Initial Date: 2020-01-01</sub></div>
* [BurntSushi/suffix](https://github.com/BurntSushi/suffix) - 線形時間接尾辞配列構築（ユニコード対応）<div><sub>Stars: 261 / Last Update: 2023-10-10 / Initial Date: 2014-12-28</sub></div>
* [BurntSushi/tabwriter](https://github.com/BurntSushi/tabwriter) - 伸縮性のあるタブストップ（つまり、テキスト列のアライメント）<div><sub>Stars: 247 / Last Update: 2024-09-25 / Initial Date: 2014-09-07</sub></div>
* [cpc](https://github.com/probablykasper/cpc) - 1+2`から`1% round(1 lightyear / 14!s to km/h)`まで、単位と単位変換をサポートする数学の文字列を解析して計算する。<div><sub>Stars: 128 / Last Update: 2024-01-13 / Initial Date: 2019-12-05</sub></div>
* [fancy-regex/fancy-regex](https://github.com/fancy-regex/fancy-regex) [[fancy-regex](https://crates.io/crates/fancy-regex)] - ルックアラウンドやバックトラックなど、比較的豊富な機能をサポートするように設計された正規表現実装。[クレート](https://img.shields.io/crates/v/fancy-regex.svg)](https://crates.io/crates/fancy-regex) [![ビルド・バッジ](https://github.com/fancy-regex/fancy-regex/workflows/ci/badge.svg)](https://github.com/fancy-regex/fancy-regex/actions/workflows/ci.yml)<div><sub>Stars: 422 / Last Update: 2024-07-19 / Initial Date: 2018-10-02</sub></div>
* [greyblake/whatlang-rs](https://github.com/greyblake/whatlang-rs) - トリグラムに基づく自然言語検出ライブラリ<div><sub>Stars: 968 / Last Update: 2024-03-16 / Initial Date: 2016-11-05</sub></div>
* [mgeisler/textwrap](https://github.com/mgeisler/textwrap) [[textwrap](https://crates.io/crates/textwrap)] - ワードラップテキスト（ハイフネーション対応）<div><sub>Stars: 454 / Last Update: 2024-10-03 / Initial Date: 2016-12-16</sub></div>
* [null8626/decancer](https://github.com/null8626/decancer) [[decancer](https://crates.io/crates/decancer)] - 文字列から一般的な unicode 混同文字/ホモグリフを除去する小さなパッケージです。[![crates](https://img.shields.io/crates/v/decancer.svg)](https://crates.io/crates/decancer) [![build badge](https://github.com/null8626/decancer/workflows/CI/badge.svg)](https://github.com/null8626/decancer/actions/workflows/CI.yml)<div><sub>Stars: 100 / Last Update: 2024-09-21 / Initial Date: 2021-06-26</sub></div>
* [rust-lang/regex](https://github.com/rust-lang/regex) - 正規表現（RE2スタイル）<div><sub>Stars: 3.5k / Last Update: 2024-09-29 / Initial Date: 2014-12-11</sub></div>
* [strsim-rs](https://crates.io/crates/strsim) - 文字列の類似性メトリクス
* [yaa110/rake-rs](https://github.com/yaa110/rake-rs) [[rake](https://crates.io/crates/rake)] - Rust用RAKEアルゴリズムの多言語実装<div><sub>Stars: 33 / Last Update: 2024-04-07 / Initial Date: 2018-03-17</sub></div>

### Text search

* [andylokandy/simsearch-rs](https://github.com/andylokandy/simsearch-rs) [[simsearch](https://crates.io/crates/simsearch)] - メモリ上で動作し、類似した文字列を検索する、シンプルで軽量なファジー検索エンジン。<div><sub>Stars: 166 / Last Update: 2024-04-19 / Initial Date: 2019-04-15</sub></div>
* [BurntSushi/fst](https://github.com/BurntSushi/fst) [[fst](https://crates.io/crates/fst)] - 有限状態機械を用いた順序集合と写像の高速実装<div><sub>Stars: 1.8k / Last Update: 2024-09-25 / Initial Date: 2015-09-05</sub></div>
* [meilisearch/MeiliSearch](https://github.com/meilisearch/MeiliSearch) - 極めて適切で、瞬時に、そして誤字脱字に強い全文検索API。[構築状況](https://github.com/meilisearch/MeiliSearch/workflows/Cargo%20test/badge.svg?branch=master)](https://github.com/meilisearch/MeiliSearch/actions)<div><sub>Stars: 46.8k / Last Update: 2024-10-03 / Initial Date: 2018-04-23</sub></div>
* [pg_search](https://github.com/paradedb/paradedb/tree/dev/pg_search) - BM25アルゴリズムを使用したSQLテーブルの全文検索を可能にするPostgreSQL拡張。
* [tantivy](https://github.com/quickwit-oss/tantivy) [[tantivy](https://crates.io/crates/tantivy)] - Rustで書かれた馬速全文検索エンジンライブラリ。[ビルド状況](https://github.com/quickwit-oss/tantivy/actions/workflows/test.yml/badge.svg)](https://github.com/quickwit-oss/tantivy/actions/workflows/test.yml)<div><sub>Stars: 11.9k / Last Update: 2024-09-26 / Initial Date: 2016-01-11</sub></div>

### Unsafe

* [zerocopy](https://crates.io/crates/zerocopy) - "Zerocopyはゼロコストのメモリ操作を楽にする。私たちは`unsafe`を書くので、あなたは書く必要がない。"

### Video

* [ffmpeg-sidecar](https://github.com/nathanbabcock/ffmpeg-sidecar) - スタンドアロンのFFmpegバイナリを直感的なIteratorインターフェイスでラップする。[ビルド状況](https://github.com/nathanbabcock/ffmpeg-sidecar/actions/workflows/rust.yml/badge.svg)](https://github.com/nathanbabcock/ffmpeg-sidecar/actions/workflows/rust.yml)<div><sub>Stars: 237 / Last Update: 2024-09-01 / Initial Date: 2023-02-09</sub></div>

### Virtualization

* [bytecodealliance/wasmtime](https://github.com/bytecodealliance/wasmtime) - WebAssembly用スタンドアロンランタイム [![ビルド状況]](https://github.com/bytecodealliance/wasmtime/workflows/CI/badge.svg)](https://github.com/bytecodealliance/wasmtime/actions?query=workflow%3ACI)<div><sub>Stars: 15.2k / Last Update: 2024-10-05 / Initial Date: 2017-08-29</sub></div>
* [chromium/chromiumos/platform/crosvm](https://chromium.googlesource.com/chromiumos/platform/crosvm/) - CrOSVM Chrome OSで、高速でセキュアな仮想化環境でLinuxアプリケーションを実行可能
* [oxidecomputer/propolis](https://github.com/oxidecomputer/propolis) - illumos bhyve カーネルモジュール用ユーザ空間プログラム<div><sub>Stars: 176 / Last Update: 2024-10-05 / Initial Date: 2020-10-05</sub></div>

### Web programming

See also [Are we web yet?](https://www.arewewebyet.org) and [Rust web framework comparison](https://github.com/flosse/rust-web-framework-comparison).

* Client-side / WASM
  * [cargo-web](https://crates.io/crates/cargo-web) - クライアントサイドのWeb用Cargoサブコマンド
  * [leptos](https://github.com/leptos-rs/leptos) - Leptosはフルスタックの同型ウェブ・フレームワークで、きめ細かな反応性を活用して宣言的なユーザー・インターフェースを構築する。[[クレート]](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/leptos)<div><sub>Stars: 16.0k / Last Update: 2024-10-04 / Initial Date: 2022-07-31</sub></div>
  * [sauron](https://github.com/ivanceras/sauron) - Elmアーキテクチャに忠実なクライアントサイドのウェブフレームワークです。<div><sub>Stars: 2.0k / Last Update: 2024-06-02 / Initial Date: 2019-04-15</sub></div>
  * [stdweb](https://crates.io/crates/stdweb) - クライアントサイド・ウェブのための標準ライブラリ
  * [yew](https://crates.io/crates/yew) - クライアント・ウェブ・アプリケーションを作るためのフレームワーク
* HTTP Client
  * [alexcrichton/curl-rust](https://github.com/alexcrichton/curl-rust) - [libcurl](https://curl.se/libcurl/) バインディング<div><sub>Stars: 1.0k / Last Update: 2024-09-30 / Initial Date: 2014-06-05</sub></div><div><sub>Stars: 1.0k / Last Update: 2024-09-30 / Initial Date: 2014-06-05</sub></div>
  * [async-graphql](https://github.com/async-graphql/async-graphql) - GraphQLサーバー・ライブラリ [![ビルド状況](https://dev.azure.com/graphql-rust/GraphQL%20Rust/_apis/build/status/graphql-rust.juniper)](https://dev.azure.com/graphql-rust/GraphQL%20Rust/_build/latest?definitionId=1)<div><sub>Stars: 3.4k / Last Update: 2024-09-26 / Initial Date: 2020-03-01</sub></div>
  * [c410-f3r/wtx](https://github.com/c410-f3r/wtx) - HTTP/2クライアント・フレームワーク<div><sub>Stars: 142 / Last Update: 2024-10-03 / Initial Date: 2023-08-28</sub></div>
  * [DoumanAsh/yukikaze](https://gitlab.com/Douman/yukikaze) [[yukikaze](https://crates.io/crates/yukikaze)] - 美しくエレガントなYukikazeは、hyperベースの小さなHTTPクライアントライブラリです。[ビルドバッジ](https://gitlab.com/Douman/yukikaze/badges/master/pipeline.svg)](https://gitlab.com/Douman/yukikaze)
  * [ducaale/xh](https://github.com/ducaale/xh) - HTTPリクエストを送信するためのフレンドリーで高速なツール [![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/xh) [![GitHub actions Status](https://github.com/ducaale/xh/workflows/CI/badge.svg?branch=master)](https://github.com/ducaale/xh/actions)<div><sub>Stars: 5.5k / Last Update: 2024-09-30 / Initial Date: 2020-09-10</sub></div>
  * [graphql-client](https://github.com/graphql-rust/graphql-client) - タイプされた正しいGraphQLリクエストとレスポンス。[GitHubアクションステータス](https://github.com/graphql-rust/graphql-client/workflows/CI/badge.svg?branch=master)](https://github.com/graphql-rust/graphql-client/actions)<div><sub>Stars: 1.1k / Last Update: 2024-07-27 / Initial Date: 2018-06-02</sub></div>
  * [hyperium/hyper](https://github.com/hyperium/hyper) - HTTPの実装 [![CI](https://github.com/hyperium/hyper/workflows/CI/badge.svg?branch=master)](https://github.com/hyperium/hyper/actions?query=workflow%3ACI)<div><sub>Stars: 14.4k / Last Update: 2024-09-17 / Initial Date: 2014-08-30</sub></div>
  * [seanmonstar/reqwest](https://github.com/seanmonstar/reqwest) - 人間工学に基づいたHTTPクライアント。<div><sub>Stars: 9.8k / Last Update: 2024-09-30 / Initial Date: 2016-07-01</sub></div>
* HTTP Server
  * [actix/actix-web](https://github.com/actix/actix-web) - ウェブソケットをサポートする軽量の非同期ウェブフレームワーク<div><sub>Stars: 21.4k / Last Update: 2024-10-01 / Initial Date: 2017-09-30</sub></div>
  * [branca](https://crates.io/crates/branca) - 認証および暗号化されたAPIトークンのためのBrancaの実装。
  * [c410-f3r/wtx](https://github.com/c410-f3r/wtx) - 低レベルと高レベルのHTTP/2サーバー<div><sub>Stars: 142 / Last Update: 2024-10-03 / Initial Date: 2023-08-28</sub></div>
  * [GildedHonour/frank_jwt](https://github.com/GildedHonour/frank_jwt) - JSON ウェブ トークンの実装。<div><sub>Stars: 250 / Last Update: 2023-11-24 / Initial Date: 2014-10-21</sub></div>
  * [Gotham](https://github.com/gotham-rs/gotham) - 安全性、セキュリティ、スピードを犠牲にしない柔軟なウェブフレームワーク。<div><sub>Stars: 2.2k / Last Update: 2024-06-03 / Initial Date: 2017-07-22</sub></div>
  * [handlebars-rust](https://github.com/sunng87/handlebars-rust) - アイアン・ウェブ・フレームワークのミドルウェア。<div><sub>Stars: 1.3k / Last Update: 2024-10-04 / Initial Date: 2014-12-21</sub></div>
  * [hyperium/hyper](https://github.com/hyperium/hyper) - HTTPの実装 [![CI](https://github.com/hyperium/hyper/workflows/CI/badge.svg?branch=master)](https://github.com/hyperium/hyper/actions?query=workflow%3ACI)<div><sub>Stars: 14.4k / Last Update: 2024-09-17 / Initial Date: 2014-08-30</sub></div>
  * [Juniper](https://github.com/graphql-rust/juniper) - GraphQLサーバーライブラリ<div><sub>Stars: 5.7k / Last Update: 2024-09-26 / Initial Date: 2016-09-11</sub></div>
  * [poem-web/poem](https://github.com/poem-web/poem) - フル機能で使いやすいウェブフレームワーク。[CI](https://github.com/poem-web/poem/actions/workflows/ci.yml/badge.svg)](https://github.com/poem-web/poem/actions/workflows/ci.yml)<div><sub>Stars: 3.5k / Last Update: 2024-10-02 / Initial Date: 2021-08-11</sub></div>
  * [Rocket](https://github.com/rwf2/Rocket) - Rocketは、使いやすさ、表現力、スピードを重視したWebフレームワークです。<div><sub>Stars: 24.3k / Last Update: 2024-09-03 / Initial Date: 2016-03-18</sub></div>
  * [Salvo](https://github.com/salvo-rs/salvo) - hyperとtokioをベースにした使いやすいWebフレームワークです。[[ビルド build](https://github.com/salvo-rs/salvo/workflows/CI%20(Linux)/badge.svg?branch=master&event=push)](https://github.com/salvo-rs/salvo/actions)<div><sub>Stars: 3.3k / Last Update: 2024-10-04 / Initial Date: 2019-11-07</sub></div>
  * [Saphir](https://github.com/richerarc/saphir) - プログレッシブ・ウェブ・フレームワーク。<div><sub>Stars: 91 / Last Update: 2024-05-14 / Initial Date: 2018-06-01</sub></div>
  * [seanmonstar/warp](https://github.com/seanmonstar/warp) - ワープスピードに対応した、超簡単でコンポーザブルなウェブ・サーバー・フレームワーク。[クレート](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/warp)<div><sub>Stars: 9.5k / Last Update: 2024-08-08 / Initial Date: 2018-07-11</sub></div>
  * [spring-rs](https://github.com/spring-rs/spring-rs) - spring-rsは、Javaのspring-bootにインスパイアされて書かれたRubst製のアプリケーションフレームワークである。<div><sub>Stars: 383 / Last Update: 2024-10-05 / Initial Date: 2024-05-26</sub></div>
  * [tokio/axum](https://github.com/tokio-rs/axum) - Tokio、Tower、Hyperで構築された人間工学に基づいたモジュール式のウェブ・フレームワーク[[ビルド・バッジ]](https://github.com/tokio-rs/axum/actions/workflows/CI.yml/badge.svg?branch=main)](https://github.com/tokio-rs/axum/actions/workflows/CI.yml)<div><sub>Stars: 18.6k / Last Update: 2024-10-04 / Initial Date: 2021-05-30</sub></div>
  * [tomaka/rouille](https://github.com/tomaka/rouille) - ウェブ・フレームワーク<div><sub>Stars: 1.1k / Last Update: 2024-07-31 / Initial Date: 2015-07-15</sub></div>
  * [Zino](https://github.com/zino-rs/zino) - コンポーザブル・アプリケーションのための次世代フレームワーク<div><sub>Stars: 758 / Last Update: 2024-10-05 / Initial Date: 2022-12-29</sub></div>
* Miscellaneous
  * [edezhic/prest](https://github.com/edezhic/prest) [[prest](https://crates.io/crates/prest)] - フルスタック開発の簡素化を目指したプログレッシブRESTfulフレームワーク<div><sub>Stars: 51 / Last Update: 2024-09-01 / Initial Date: 2023-03-30</sub></div>
  * [osohq/oso](https://github.com/osohq/oso) [[oso](https://crates.io/crates/oso)] - アプリケーションに組み込まれた認可のためのポリシーエンジン。[ビルドステータス](https://github.com/osohq/oso/workflows/Development/badge.svg?branch=main)](https://github.com/osohq/oso/actions?query=branch%3Amain+ワークフロー%3ADevelopment)<div><sub>Stars: 3.5k / Last Update: 2024-06-13 / Initial Date: 2020-05-04</sub></div>
  * [pwoolcoc/soup](https://gitlab.com/pwoolcoc/soup) [[soup](https://crates.io/crates/soup)] - PythonのBeautifulSoupに似たライブラリで、HTML文書を素早く簡単に操作したり問い合わせたりできるように設計されています。[ビルド状況](https://gitlab.com/pwoolcoc/soup/badges/master/pipeline.svg)](https://gitlab.com/pwoolcoc/soup/badges/master/pipeline.svg)
  * [pyrossh/rust-embed](https://github.com/pyrossh/rust-embed) - 静的アセットをRustバイナリに埋め込むマクロ<div><sub>Stars: 1.6k / Last Update: 2024-07-09 / Initial Date: 2015-11-29</sub></div>
  * [rookie](https://github.com/thewh1teagle/rookie) - あらゆるプラットフォーム上のあらゆるブラウザからクッキーをロードする。![crates.io](https://img.shields.io/crates/v/rookie.svg)<div><sub>Stars: 150 / Last Update: 2024-09-01 / Initial Date: 2023-09-26</sub></div>
  * [rust-scraper/scraper](https://github.com/rust-scraper/scraper) [[scraper](https://crates.io/crates/scraper)] - CSSセレクタを使ったHTMLの解析とクエリ。[ビルド状況](https://github.com/rust-scraper/scraper/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/rust-scraper/scraper/actions)<div><sub>Stars: 1.9k / Last Update: 2024-09-16 / Initial Date: 2016-01-01</sub></div>
  * [serenity-rs/serenity](https://github.com/serenity-rs/serenity) [[serenity](https://crates.io/crates/serenity)] - Discord API用ライブラリ<div><sub>Stars: 4.7k / Last Update: 2024-09-30 / Initial Date: 2016-11-06</sub></div>
  * [svix/svix-webhooks](https://github.com/svix/svix-webhooks) [[svix](https://crates.io/crates/svix)] - ウェブフックを送信し、署名を検証するためのライブラリ。<div><sub>Stars: 2.3k / Last Update: 2024-10-04 / Initial Date: 2021-02-25</sub></div>
  * [tbot](https://gitlab.com/SnejUgal/tbot) [[tbot](https://crates.io/crates/tbot)] - クールなTelegramボットを簡単に作る [![パイプラインの状況]](https://gitlab.com/SnejUgal/tbot/badges/master/pipeline.svg)](https://gitlab.com/SnejUgal/tbot/-/commits/master)
  * [teloxide/teloxide](https://github.com/teloxide/teloxide/) - エレガントなTelegramボットフレームワーク [![Build Status](https://github.com/teloxide/teloxide/workflows/Continuous%20integration/badge.svg?branch=master)](https://github.com/teloxide/teloxide/actions)<div><sub>Stars: 3.1k / Last Update: 2024-10-05 / Initial Date: 2019-09-01</sub></div>
  * [tu6ge/valitron](https://github.com/tu6ge/valitron) [[valitron](https://crates.io/crates/valitron)] - 人間工学に基づいた、機能的で設定可能なバリデータ<div><sub>Stars: 61 / Last Update: 2024-09-19 / Initial Date: 2023-08-18</sub></div>
  * [utkarshkukreti/select.rs](https://github.com/utkarshkukreti/select.rs) [[select](https://crates.io/crates/select)] - HTML文書から有用なデータを抽出するライブラリで、Webスクレイピングに適している。<div><sub>Stars: 964 / Last Update: 2024-06-21 / Initial Date: 2015-07-15</sub></div>
  * [Utoipa](https://github.com/juhaku/utoipa) - シンプル、高速、コードファースト、コンパイル時に生成されるOpenAPIドキュメント [![crates.io](https://img.shields.io/crates/v/utoipa.svg?label=crates.io&color=orange&logo=rust)](https://crates.io/crates/utoipa) [![Utoipa build](https://github.com/juhaku/utoipa/actions/workflows/build.yaml/badge.svg)](https://github.com/juhaku/utoipa/actions/workflows/build.yaml)<div><sub>Stars: 2.2k / Last Update: 2024-10-04 / Initial Date: 2021-09-30</sub></div>
  * [Utoipauto](https://github.com/ProbablyClem/utoipauto) - ウトイパへのパス／スキーマの追加を自動化するRustマクロ [![crates.io]](https://img.shields.io/crates/v/utoipauto.svg?label=crates.io&color=orange&logo=rust)](https://crates.io/crates/utoipauto)<div><sub>Stars: 119 / Last Update: 2024-10-02 / Initial Date: 2023-11-27</sub></div>
* Reverse Proxy
  * [sozu-proxy/sozu](https://github.com/sozu-proxy/sozu) [[sozu](https://crates.io/crates/sozu)] - HTTPリバースプロキシ。[CI](https://github.com/sozu-proxy/sozu/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/sozu-proxy/sozu/actions/workflows/ci.yml)<div><sub>Stars: 3.0k / Last Update: 2024-10-04 / Initial Date: 2017-01-18</sub></div>
* Static Site Generators
  * [cobalt-org/cobalt.rs](https://github.com/cobalt-org/cobalt.rs) - 静的サイト・ジェネレーター [![ビルド・ステータス](https://dev.azure.com/cobalt-org/cobalt-org/_apis/build/status/cobalt.rs?branchName=master)](https://dev.azure.com/cobalt-org/cobalt-org/_build?definitionId=2)<div><sub>Stars: 1.4k / Last Update: 2024-10-01 / Initial Date: 2014-10-28</sub></div>
  * [FuGangqiang/mdblog.rs](https://github.com/FuGangqiang/mdblog.rs) [[mdblog](https://crates.io/crates/mdblog)] - マークダウン・ファイルからの静的サイト・ジェネレータ。<div><sub>Stars: 58 / Last Update: 2024-08-12 / Initial Date: 2016-06-05</sub></div>
  * [getzola/zola](https://github.com/getzola/zola) [[zola](https://www.getzola.org/)] - すべてを内蔵した静的サイトジェネレータ。[構築状況](https://dev.azure.com/getzola/zola/_apis/build/status/getzola.zola?branchName=master)](https://dev.azure.com/getzola/zola/_build)<div><sub>Stars: 13.5k / Last Update: 2024-10-03 / Initial Date: 2016-12-06</sub></div>
  * [grego/blades](https://github.com/grego/blades) [[blades](https://www.getblades.org/)] - 高速でシンプルな静的サイトジェネレータ。<div><sub>Stars: 333 / Last Update: 2024-07-22 / Initial Date: 2020-10-11</sub></div>
* [WebSocket](https://datatracker.ietf.org/doc/rfc6455/)
  * [c410-f3r/wtx](https://github.com/c410-f3r/wtx) - 暗号化をサポートするクライアントとサーバー。<div><sub>Stars: 142 / Last Update: 2024-10-03 / Initial Date: 2023-08-28</sub></div>
  * [iddm/urlshortener-rs](https://github.com/iddm/urlshortener-rs) - とてもシンプルなurlshortenerライブラリ。[CI](https://github.com/iddm/urlshortener-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/iddm/urlshortener-rs/actions/workflows/ci.yml) [![クレートバッジ]](https://img.shields.io/crates/v/urlshortener.svg)](https://crates.io/crates/urlshortener)<div><sub>Stars: 49 / Last Update: 2024-05-14 / Initial Date: 2016-07-04</sub></div>
  * [snapview/tungstenite-rs](https://github.com/snapview/tungstenite-rs) - 軽量なストリームベースのWebSocket実装。<div><sub>Stars: 1.9k / Last Update: 2024-09-14 / Initial Date: 2017-03-17</sub></div>
  * [swimos/ratchet](https://github.com/swimos/ratchet) [[ratchet_rs](https://crates.io/crates/ratchet_rs)] - Ratchetは、WebSocketプロトコルの高速、軽量、完全な非同期実装で、拡張機能とDeflateをサポートしている。<div><sub>Stars: 38 / Last Update: 2024-09-30 / Initial Date: 2021-11-23</sub></div>
  * [vi/websocat](https://github.com/vi/websocat) - Netcat、Curl、Socatの機能を備えた、WebSocketとやりとりするためのCLI。<div><sub>Stars: 7.0k / Last Update: 2024-09-26 / Initial Date: 2016-11-23</sub></div>

## Registries

A registry allows you to publish your Rust libraries as crate packages, to share them with others publicly and privately.

* [Cloudsmith :heavy_dollar_sign:](https://cloudsmith.com/product/formats/cargo-registry) - 完全に管理されたパッケージ管理SaaSで、パブリックおよびプライベートのCargo/Rustレジストリ（その他多数）をファーストクラスでサポートします。寛大な無料層があり、オープンソースも完全に無料です。
* [Crates](https://crates.io) - Rust/Cargoの公式レジストリ。

## Resources

* Benchmarks
  * [c410-f3r/wtx-bench](https://github.com/c410-f3r/wtx-bench) - ウェブベンチマーク<div><sub>Stars: 0 / Last Update: 2024-10-03 / Initial Date: 2024-04-18</sub></div>
* Decks & Presentations
  * [Learning systems programming with Rust](https://speakerdeck.com/jvns/learning-systems-programming-with-rust) - 発表者[Julia Evans](https://twitter.com/@b0rk) @ Rustconf 2016.
  * [Rust: Hack Without Fear!](https://www.youtube.com/watch?v=lO1z-7cuRYI) - ニコラス・マサキス】(https://github.com/nikomatsakis) による発表 @ C++Now 2018
  * [Shipping a Solid Rust Crate](https://www.youtube.com/watch?v=t4CyEKb-ywA) - 発表者：【マイケル・ガットッツィ】(https://github.com/mgattozzi) @ RustConf 2017
* Learning
  * [100 Exercises To Learn Rust](https://rust-exercises.com) - 構文や型など、100の実践的な演習を通してRustを学ぶ
  * [Aquascope](https://github.com/cognitive-engineering-lab/aquascope) - コンパイル時と実行時におけるRustのインタラクティブな可視化<div><sub>Stars: 2.0k / Last Update: 2024-09-29 / Initial Date: 2022-09-15</sub></div>
  * [awesome-rust-mentors](https://rustbeginners.github.io/awesome-rust-mentors/) - メンティーを受け入れ、ラストとプログラミングについて教育してくれる親切なメンターのリスト。
  * [Build a language VM](https://blog.subnetzero.io/post/building-language-vm-part-00/) - 言語VMの構築方法を詳しく説明する一連の投稿。
  * [CIS 198: Rust Programming](http://cis198-2016s.github.io/schedule/) - University of Pennsylvania's Comp Sci Rust Programming Course
  * [CodeCrafters.io](https://app.codecrafters.io/tracks/rust) - 独自のRedis、Git、Docker、SQLiteを構築する
  * [Comprehensive Rust 🦀](https://google.github.io/comprehensive-rust/) - Rust Fundamentalsの3日間コースと、Android、Bare-metal Rust、Concurrencyの1日間コース。英語、[ブラジルポルトガル語](https://google.github.io/comprehensive-rust/pt-BR/)、[韓国語](https://google.github.io/comprehensive-rust/ko/)で受講可能。
  * [exercism.org](https://exercism.org/tracks/rust) - Rustの新しいコンセプトを学ぶのに役立つプログラミング演習。
  * [Hands-on Rust](https://pragprog.com/titles/hwrust/hands-on-rust/) - ゲームを作ってRustを学ぶ実践ガイド
  * [Idiomatic Rust](https://github.com/mre/idiomatic-rust) - イディオム・ラストを教える論文／講演／レポの査読付きコレクション。<div><sub>Stars: 6.5k / Last Update: 2024-05-10 / Initial Date: 2017-05-03</sub></div>
  * [Learning Rust With Entirely Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/) - いくつかの異なるタイプのリスト構造を実装することで、Rustのメモリ管理ルールについて深く掘り下げる。
  * [Little Book of Rust Books](https://lborb.github.io/book/) - 錆に関する書籍やハウツーのキュレーションリスト。
  * [Programming Community Curated Resources for Learning Rust](https://hackr.io/tutorials/learn-rust) - プログラミング・コミュニティによって投票された推奨リソースのリスト。
  * [Refactoring to Rust](https://www.manning.com/books/refactoring-to-rust) - Rust言語の入門書。
  * [Rust by Example](https://doc.rust-lang.org/rust-by-example/) - は、Rustの様々なコンセプトや標準ライブラリを説明する実行可能なサンプル集です。
  * [Rust Cookbook](https://rust-lang-nursery.github.io/rust-cookbook/) - Rustエコシステムのクレートを使って、一般的なプログラミング作業を達成するためのグッドプラクティスを示すシンプルなサンプル集。
  * [Rust Flashcards](https://github.com/ad-si/Rust-Flashcards) - 550枚以上のフラッシュカードでRustを初歩から学べます。<div><sub>Stars: 531 / Last Update: 2024-06-25 / Initial Date: 2024-03-03</sub></div>
  * [Rust for professionals](https://overexact.com/rust-for-professionals/) - 経験豊富なソフトウェア開発者向けのRust入門書。
  * [Rust in Action](https://www.manning.com/books/rust-in-action) - ティム・マクナマラ](https://github.com/timClicks)によるRustによるシステム・プログラミングのハンズオン・ガイド(有料)
  * [Rust in Motion](https://www.manning.com/livevideo/rust-in-motion?a_aid=cnichols&a_bid=6a993c2e) - キャロル・ニコルズ](https://github.com/carols10cents)と[ジェイク・グールディング](https://github.com/shepmaster)によるビデオシリーズ(有料)
  * [Rust Language Cheat Sheet](https://cheats.rs/) - Rust言語チートシート
  * [Rust Tiếng Việt](https://rust-tieng-viet.github.io/) - ベトナム語でサビを学ぶ
  * [rust-learning](https://github.com/ctjhoa/rust-learning) - Rustの学習に役立つリソース集<div><sub>Stars: 11.4k / Last Update: 2024-05-27 / Initial Date: 2015-05-07</sub></div>
  * [Rustlings](https://github.com/rust-lang/rustlings) - Rustコードの読み書きに慣れるための小演習<div><sub>Stars: 53.2k / Last Update: 2024-09-26 / Initial Date: 2015-09-15</sub></div>
  * [Rusty CS](https://github.com/AbdesamedBendjeddou/Rusty-CS) - 習得した知識をRustで実践できるコンピュータサイエンス・カリキュラム<div><sub>Stars: 900 / Last Update: 2024-01-08 / Initial Date: 2022-03-28</sub></div>
  * [Take your first steps with Rust](https://learn.microsoft.com/en-us/training/paths/rust-first-steps/) - Rustで迅速かつ効果的なプログラムを構築するために必要な知識の基礎を築きます。
  * [Tour of Rust](https://tourofrust.com) - これは、プログラミング言語Rustの機能をインタラクティブなステップ・バイ・ステップで紹介するものです。
* Podcasts
  * [New Rustacean](https://newrustacean.com) - Rustを学ぶポッドキャスト
  * [Rustacean Station](https://rustacean-station.org/) - Rustのポッドキャスト・コンテンツを制作するコミュニティ・プロジェクト
* [Rust Design Patterns](https://github.com/rust-unofficial/patterns) - Rustデザインパターン、アンチパターン、イディオムのカタログ<div><sub>Stars: 8.0k / Last Update: 2024-10-04 / Initial Date: 2015-10-15</sub></div>
* [Rust Guidelines](http://aturon.github.io/) - Aaron Turon's blog posts on rust
* [Rust Servers, Services and Apps - MEAP](https://www.manning.com/books/rust-servers-services-and-apps)
* [Rust Subreddit](https://www.reddit.com/r/rust/) - サビに関する質問、記事、リソースが投稿され、議論されるサブレディット(フォーラム)
* [RustBooks](https://github.com/sger/RustBooks) - ラストブックのリスト<div><sub>Stars: 4.4k / Last Update: 2024-07-27 / Initial Date: 2016-07-31</sub></div>
* [RustCamp 2015 Talks](https://www.youtube.com/playlist?list=PLE7tQUdRKcybdIw61JpCoo89i4pWU5f_t) - RustCamp 2015の講演を収録
* [RustViz](https://github.com/rustviz/rustviz) - Rust LifetimeとBorrowingの仕組みをよりよく理解するために、簡単なRustプログラムから視覚化されたデータを生成します。<div><sub>Stars: 2.7k / Last Update: 2024-02-13 / Initial Date: 2020-10-05</sub></div>
* [Watch Jon Gjengset Implement BitTorrent in Rust](https://www.youtube.com/watch?v=jf_ddGnum_4) - RustでBitTorrentクライアント（の一部）を実装する

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
