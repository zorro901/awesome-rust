* TUI
  * BearLibTerminal
  * [ccbrown/iocraft](https://github.com/ccbrown/iocraft) [[iocraft](https://crates.io/crates/iocraft)] - A crate for beautiful, artisanally crafted CLIs, TUIs, and text-based IO. [![Build status](https://github.com/ccbrown/iocraft/actions/workflows/commit.yaml/badge.svg?branch=main)](https://github.com/ccbrown/iocraft/actions) [![docs.rs](https://img.shields.io/docsrs/iocraft)](https://docs.rs/iocraft/)
  * [gyscos/Cursive](https://github.com/gyscos/Cursive) [[cursive](https://crates.io/crates/cursive)] - build rich TUI applications
  * ncurses
    * [jeaye/ncurses-rs](https://github.com/jeaye/ncurses-rs) [[ncurses](https://crates.io/crates/ncurses)] - [ncurses](https://www.gnu.org/software/ncurses/) バインディング<div><sub>Stars: 679 / Last Update: 2024-07-12 / Initial Date: 2013-09-30</sub></div>
  * [ratatui-org/ratatui](https://github.com/ratatui/ratatui) [[ratatui](https://crates.io/crates/ratatui)] - Library that's all about cooking up terminal user interfaces (TUIs)
  * [redox-os/termion](https://github.com/redox-os/termion) [[termion](https://crates.io/crates/termion)] - bindless library for controlling terminals/TTY
  * [ruterm](https://crates.io/crates/ruterm) - TTY を扱うためのシンプルで小さなライブラリ
  * Termbox
  * [TimonPost/crossterm](https://github.com/crossterm-rs/crossterm) [[crossterm](https://crates.io/crates/crossterm)] - crossplatform terminal library

### Compression

* [7z](https://7-zip.org/7z.html)
  * [[sevenz-rust](https://crates.io/crates/sevenz-rust)] - 純粋な錆で書かれた7z解凍/圧縮機。
* [Brotli](https://opensource.googleblog.com/2015/09/introducing-brotli-new-compression.html)
  * [dropbox/rust-brotli](https://github.com/dropbox/rust-brotli) - Brotli decompressor that optionally avoids the stdlib
* bzip2
* gzip
  * [zopfli](https://github.com/zopfli-rs/zopfli) [[zopfli](https://crates.io/crates/zopfli)] - implementation of the Zopfli compression algorithm for higher quality deflate or zlib compression
* gzp
* miniz
  * [rust-lang/flate2-rs](https://github.com/rust-lang/flate2-rs) - [ミニッツ](https://code.google.com/archive/p/miniz) バインディング [![ビルド・バッジ](https://github.com/rust-lang/flate2-rs/workflows/CI/badge.svg?branch=master)](https://github.com/rust-lang/flate2-rs/actions)<div><sub>Stars: 893 / Last Update: 2024-09-26 / Initial Date: 2014-07-17</sub></div>
* tar
  * [alexcrichton/tar-rs](https://github.com/alexcrichton/tar-rs) - tar archive reading/writing
* zip
  * [zip-rs/zip2](https://github.com/zip-rs/zip2) [[zip](https://crates.io/crates/zip)] - read and write  ZIP archives
* zstd
  * [gyscos/zstd-rs](https://github.com/gyscos/zstd-rs) - rust binding for the zstd compression library

### Computation

* [argmin-rs/argmin](https://github.com/argmin-rs/argmin) [[argmin](https://crates.io/crates/argmin)] - Optimization library
* [BLAS](https://en.wikipedia.org/wiki/Basic_Linear_Algebra_Subprograms) [[blas](https://crates.io/keywords/blas)]
* [dimforge/nalgebra](https://github.com/dimforge/nalgebra) - low-dimensional linear algebra library
* [faer-rs](https://github.com/sarah-ek/faer-rs) [[faer](https://crates.io/crates/faer)] - Linear algebra foundation for Rust
* [GSL](http://www.gnu.org/software/gsl/)
  * [GuillaumeGomez/rust-GSL](https://github.com/GuillaumeGomez/rust-GSL) - GSL bindings
* [LAPACK](https://en.wikipedia.org/wiki/LAPACK)
* Parallel
* Science
  * [Axect/Peroxide](https://github.com/Axect/Peroxide) - Rust numeric library containing linear algebra, numerical analysis, statistics and machine learning tools in pure rust
  * [cpmech/russell](https://github.com/cpmech/russell) - Rust Scientific Library for numerical mathematics, ordinary differential equations, special math functions, high-performance (sparse) linear algebra
* Statrs
  * [statrs-dev/statrs](https://github.com/statrs-dev/statrs) - Robust statistical computation library

### Concurrency

* [crossbeam-rs/crossbeam](https://github.com/crossbeam-rs/crossbeam) - Support for parallelism and low-level concurrency
* [orium/archery](https://github.com/orium/archery) [[archery](https://crates.io/crates/archery)] - Library to abstract from `Rc`/`Arc` pointer types. [![build badge](https://github.com/orium/archery/workflows/CI/badge.svg)](https://github.com/orium/archery/actions?query=workflow%3ACI)
* [Rayon](https://github.com/rayon-rs/rayon) - A data parallelism library

### Configuration

* [Kixunil/configure_me](https://github.com/Kixunil/configure_me) [[configure_me](https://crates.io/crates/configure_me)] - library for processing application configuration easily
* [mehcode/config-rs](https://github.com/mehcode/config-rs) [[config](https://crates.io/crates/config)] - Layered configuration system (with strong support for 12-factor applications).
* [SergioBenitez/Figment](https://github.com/SergioBenitez/Figment) [[figment](https://crates.io/crates/figment)] - A configuration library so con-free, it's unreal.
* [softprops/envy](https://github.com/softprops/envy) - deserialize env vars into typesafe structs [![Main](https://github.com/softprops/envy/actions/workflows/main.yml/badge.svg)](https://github.com/softprops/envy/actions/workflows/main.yml)

### Cryptography

[[crypto](https://crates.io/keywords/crypto), [cryptography](https://crates.io/keywords/cryptography)]

* [arkworks-rs/circom-compat](https://github.com/arkworks-rs/circom-compat) - Arkworks bindings to Circom's R1CS, for Groth16 Proof and Witness generation.
* [briansmith/ring](https://github.com/briansmith/ring) - Safe, fast, small crypto using Rust and BoringSSL's cryptography primitives.
* [briansmith/webpki](https://github.com/briansmith/webpki) - Web PKI TLS X.509 certificate validation.
* [conradkleinespel/rooster](https://github.com/conradkleinespel/rooster) [[rooster](https://crates.io/crates/rooster)] - Simple password manager to use in your terminal
* [cossacklabs/themis](https://github.com/cossacklabs/themis) [[themis](https://crates.io/crates/themis)] - a high-level cryptographic library for solving typical data security tasks, best fit for multi-platform apps. [![build badge](https://circleci.com/gh/cossacklabs/themis/tree/master.svg?style=shield)](https://app.circleci.com/pipelines/github/cossacklabs/themis)
* [dalek-cryptography/curve25519-dalek](https://github.com/dalek-cryptography/curve25519-dalek) - Curve25519 operations
* [facebook/opaque-ke](https://github.com/facebook/opaque-ke) - Implementation of the recent [OPAQUE](https://datatracker.ietf.org/doc/draft-krawczyk-cfrg-opaque/) password-authenticated key exchange. [![build badge](https://github.com/facebook/opaque-ke/workflows/Rust%20CI/badge.svg?branch=master)](https://github.com/facebook/opaque-ke)
* [facebook/opaque-ke](https://github.com/facebook/opaque-ke) - Implementation of the recent [OPAQUE](https://datatracker.ietf.org/doc/draft-krawczyk-cfrg-opaque/) password-authenticated key exchange. [![build badge](https://github.com/facebook/opaque-ke/workflows/Rust%20CI/badge.svg?branch=master)](https://github.com/facebook/opaque-ke)
* [iddm/randomorg](https://github.com/iddm/randomorg) - A random.org client library. [![Crates badge](https://img.shields.io/crates/v/randomorg.svg)](https://crates.io/crates/randomorg)
* [kornelski/rust-security-framework](https://github.com/kornelski/rust-security-framework) - Bindings for Security Framework (OSX native)
* [orion-rs/orion](https://github.com/orion-rs/orion) - This library aims to provide easy and usable crypto. 'Usable' meaning exposing high-level API's that are easy to use and hard to misuse. [![Tests](https://github.com/orion-rs/orion/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/orion-rs/orion/actions/workflows/test.yml)
* [racum/rust-djangohashers](https://github.com/racum/rust-djangohashers) [[djangohashers](https://crates.io/crates/djangohashers)] - Port of the password primitives used in the Django Project. It doesn't require Django, only hashes and validates passwords according to its style.
* [RustCrypto/hashes](https://github.com/RustCrypto/hashes) - Collection of cryptographic hash functions
* [rustls/rustls](https://github.com/rustls/rustls) - Implementation of TLS
* [sfackler/rust-native-tls](https://github.com/sfackler/rust-native-tls) - Bindings for native TLS libraries
* [sfackler/rust-openssl](https://github.com/sfackler/rust-openssl) - [OpenSSL](https://www.openssl.org/)バインディング<div><sub>Stars: 1.4k / Last Update: 2024-09-08 / Initial Date: 2013-12-28</sub></div>
* [sorairolake/abcrypt](https://github.com/sorairolake/abcrypt) [[abcrypt](https://crates.io/crates/abcrypt)] - A simple, modern and secure file encryption library. [![CI](https://github.com/sorairolake/abcrypt/workflows/CI/badge.svg?branch=develop)](https://github.com/sorairolake/abcrypt/actions?query=workflow%3ACI)
* [sorairolake/scryptenc-rs](https://github.com/sorairolake/scryptenc-rs) [[scryptenc](https://crates.io/crates/scryptenc)] - An implementation of the scrypt encrypted data format. [![CI](https://github.com/sorairolake/scryptenc-rs/workflows/CI/badge.svg?branch=develop)](https://github.com/sorairolake/scryptenc-rs/actions?query=workflow%3ACI)
* [w3f/schnorrkel](https://github.com/w3f/schnorrkel) - Schnorr VRFs and signatures on the Ristretto group

### Data processing

* [amv-dev/yata](https://github.com/amv-dev/yata) - high performance technical analysis library [![Build Status](https://img.shields.io/github/workflow/status/amv-dev/yata/Rust?branch=master)](https://github.com/amv-dev/yata/actions?query=workflow%3ARust)
* [bluss/ndarray](https://github.com/rust-ndarray/ndarray) - N-dimensional array with array views, multidimensional slicing, and efficient operations
* [datafusion](https://github.com/apache/datafusion) - DataFusion is a very fast, extensible query engine for building high-quality data-centric systems in Rust, using the Apache Arrow in-memory format.
* [pg_analytics](https://github.com/paradedb/paradedb/tree/dev/pg_analytics) - PostgreSQLの拡張機能で、Postgres内の分析クエリ処理を専用のOLAPデータベースに匹敵する性能レベルまで高速化します。
* [pg_lakehouse](https://github.com/paradedb/paradedb/tree/dev/pg_lakehouse) - AWSのS3/GCSのようなオブジェクトストアやDelta Lake/Icebergのようなテーブルフォーマット上でPostgreSQLを分析クエリーエンジンに変換するPostgreSQL拡張。
* [pola-rs/polars](https://github.com/pola-rs/polars) - Fast feature complete DataFrame library ![Build and test](https://github.com/pola-rs/polars/workflows/Build%20and%20test/badge.svg?branch=master)

### Data streaming

* [ArroyoSystems/arroyo](https://github.com/ArroyoSystems/arroyo) - High-performance real-time analytics in Rust and SQL [![CI](https://github.com/ArroyoSystems/arroyo/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/ArroyoSystems/arroyo/actions)
* [iggy-rs/iggy](https://github.com/iggy-rs/iggy) [[iggy](https://crates.io/crates/iggy)] - Persistent message streaming platform, supporting QUIC, TCP and HTTP transport protocols [![CI](https://github.com/iggy-rs/iggy/actions/workflows/test.yml/badge.svg)](https://github.com/iggy-rs/iggy/actions/workflows/test.yml)
* [infinyon/fluvio](https://github.com/infinyon/fluvio) - Programmable data streaming platform [![CI](https://github.com/infinyon/fluvio/workflows/CI/badge.svg?branch=stable)](https://github.com/infinyon/fluvio/actions)
* [swimos/swim-rust](https://github.com/swimos/swim-rust) [[swim-rust](https://crates.io/crates/swimos)] - Self-contained distributed software platform for building stateful, massively real-time streaming applications.

### Data structures

* [ashvardanian/simsimd](https://github.com/ashvardanian/SimSIMD) - SIMD-accelerated vector distances and similarity functions for x86 AVX2 & AVX-512, and Arm NEON [![crates.io](https://img.shields.io/crates/v/simsimd.svg)](https://crates.io/crates/simsimd)
* [becheran/grid](https://github.com/becheran/grid) [[grid](https://crates.io/crates/grid)] - Provide a two dimensional data structure that is easy to use and fast. [![build status](https://github.com/becheran/grid/actions/workflows/rust.yml/badge.svg)](https://github.com/becheran/grid/actions)
* [contain-rs](https://github.com/contain-rs) - Rustのstd::collectionsの拡張。
* [fizyk20/generic-array](https://github.com/fizyk20/generic-array) - a hack to allow for arrays sized by typenums
* [garro95/priority-queue](https://github.com/garro95/priority-queue)[[priority-queue](https://crates.io/crates/priority-queue)] - A priority queue that implements priority changes.
* [greyblake/nutype](https://github.com/greyblake/nutype) [[nutype](https://crates.io/crates/nutype)] - define newtype structures with validation constraints. [![build status](https://github.com/greyblake/nutype/actions/workflows/ci.yml/badge.svg)](https://github.com/greyblake/nutype/actions)
* [mrhooray/kdtree-rs](https://github.com/mrhooray/kdtree-rs) - K-dimensional tree for fast geospatial indexing and nearest neighbors lookup
* [orium/rpds](https://github.com/orium/rpds) [[rpds](https://crates.io/crates/rpds)] - Persistent data structures. [![build badge](https://github.com/orium/rpds/workflows/CI/badge.svg)](https://github.com/orium/rpds/actions?query=workflow%3ACI)
* [RoaringBitmap/roaring-rs](https://github.com/RoaringBitmap/roaring-rs) - Roaring Bitmaps
* [rust-itertools/itertools](https://github.com/rust-itertools/itertools) - Extra iterator adaptors, functions and macros
* [xfix/enum-map](https://codeberg.org/xfix/enum-map) [[enum-map](https://crates.io/crates/enum-map)] - 値を格納するために配列を使用する、列挙型のための最適化されたマップ実装。

### Data visualization

* [blitzarx1/egui_graphs](https://github.com/blitzarx1/egui_graphs) [[egui_graphs](https://crates.io/crates/egui_graphs)] - Interactive graph visualization widget powered by egui and petgraph. [![Crates.io](https://img.shields.io/crates/v/egui_graphs)](https://crates.io/crates/egui_graphs) [![docs.rs](https://img.shields.io/docsrs/egui_graphs)](https://docs.rs/egui_graphs)
* [mazznoer/colorgrad-rs](https://github.com/mazznoer/colorgrad-rs) [[colorgrad](https://crates.io/crates/colorgrad)] - Color scales library for data visualization, charts, games, maps, generative art and others.
* [plotly](https://github.com/plotly/plotly.rs) - Plotly for Rust
* [plotpy](https://github.com/cpmech/plotpy) [[plotpy](https://crates.io/crates/plotpy)] - Rust plotting library using Python (Matplotlib)
* [plotters](https://github.com/plotters-rs/plotters) - [ビルド・バッジ](https://github.com/plotters-rs/plotters/workflows/CI/badge.svg)](https://github.com/plotters-rs/plotters/actions)<div><sub>Stars: 3.8k / Last Update: 2024-10-04 / Initial Date: 2019-04-24</sub></div>
* [rerun](https://github.com/rerun-io/rerun) - [再放送](https://crates.io/crates/rerun)]<div><sub>Stars: 6.3k / Last Update: 2024-10-04 / Initial Date: 2022-04-08</sub></div>

### Database

[[database](https://crates.io/keywords/database)]

* NoSQL [[nosql](https://crates.io/keywords/nosql)]

  * [ArangoDB](https://arangodb.com)
    * [Aragog](https://gitlab.com/qonfucius/aragog) [[aragog](https://crates.io/crates/aragog)] - 軽量ArangoDBオブジェクトドキュメント・リレーショナル・グラフマッパー [![パイプラインの状況]](https://gitlab.com/qonfucius/aragog/badges/master/pipeline.svg)](https://gitlab.com/qonfucius/aragog/-/commits/master)
    * [Arangors](https://github.com/fMeow/arangors) [[arangors](https://crates.io/crates/arangors)] - An ArangoDB driver
  * [Cassandra](https://cassandra.apache.org/_/index.html) [[cassandra](https://crates.io/keywords/cassandra), [cql](https://crates.io/keywords/cql)]
    * [cassandra-rs](https://github.com/cassandra-rs/cassandra-rs) - bindings to the DataStax C/C++
    * [krojew/cdrs-tokio](https://github.com/krojew/cdrs-tokio) - High-level async Cassandra client written in 100% Rust. [![build badge](https://github.com/krojew/cdrs-tokio/actions/workflows/rust.yml/badge.svg)](https://github.com/krojew/cdrs-tokio/actions)
      * [[cassandra-protocol](https://crates.io/crates/cassandra-protocol)] - Cassandraプロトコルの実装。
      * [[cdrs-tokio](https://crates.io/crates/cdrs-tokio)] - 非同期 Apache Cassandra ドライバクライアント
  * CouchDB [[couchdb](https://crates.io/keywords/couchdb)]
  * [DynamoDB](https://aws.amazon.com/dynamodb/) [[dynamodb](https://crates.io/keywords/dynamodb)]
  * Elasticsearch [[elasticsearch](https://crates.io/keywords/elasticsearch)]
  * etcd
  * [InfluxDB](https://www.influxdata.com/)
    * [driftluo/InfluxDBClient-rs](https://github.com/driftluo/InfluxDBClient-rs) - Synchronization interface
  * LevelDB
  * LMDB [[lmdb](https://crates.io/keywords/lmdb)]
  * MongoDB [[mongodb](https://crates.io/keywords/mongodb)]
    * [mongodb/mongo-rust-driver](https://github.com/mongodb/mongo-rust-driver) [[mongodb](https://crates.io/crates/mongodb)] - [MongoDB](https://www.mongodb.com/)バインディング<div><sub>Stars: 1.4k / Last Update: 2024-10-04 / Initial Date: 2019-04-29</sub></div>
  * [PickleDB](https://pythonhosted.org/pickleDB/)
  * [PoloDB](https://www.polodb.org/)
    * [PoloDB](https://github.com/PoloDB/PoloDB) - An embedded JSON-based database has API similar to MongoDB. ![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/PoloDB/PoloDB/rust.yml)
  * [Redb](https://www.redb.org/)
    * [Redb](https://github.com/cberner/redb) - An embedded key-value database. It provides a similar interface to other embedded key-value stores such as rocksdb and lmdb. ![GitHub Workflow Status](https://github.com/cberner/redb/actions/workflows/ci.yml/badge.svg)
  * Redis [[redis](https://crates.io/keywords/redis)]
    * [aembke/fred](https://github.com/aembke/fred.rs) [[fred](https://crates.io/crates/fred)] - A high level async [Redis](https://redis.io/) client for Rust with Tokio. [![CircleCI](https://circleci.com/gh/aembke/fred.rs/tree/main.svg?style=svg)]([https://circleci.com/gh/aembke/fred.rs/tree/main](https://app.circleci.com/pipelines/github/aembke/fred.rs?branch=main))
    * [redis-rs](https://github.com/redis-rs/redis-rs) - [Redis](https://redis.io/)ライブラリ [![Rust](https://github.com/redis-rs/redis-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/redis-rs/redis-rs/actions/workflows/rust.yml)<div><sub>Stars: 3.6k / Last Update: 2024-10-03 / Initial Date: 2013-12-29</sub></div>
  * [RocksDB](https://rocksdb.org/)
    * [rust-rocksdb/rust-rocksdb](https://github.com/rust-rocksdb/rust-rocksdb) - RocksDB bindings [![RocksDB CI](https://github.com/rust-rocksdb/rust-rocksdb/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/rust-rocksdb/rust-rocksdb/actions/workflows/rust.yml)
  * [SurrealDB](https://surrealdb.com/)
    * [surrealdb/surrealdb](https://github.com/surrealdb/surrealdb) - SurrealDB embedded document-graph database
  * [UnQLite](https://github.com/symisc/unqlite)
  * [ZooKeeper](https://zookeeper.apache.org/)
    * [krojew/rust-zookeeper](https://github.com/krojew/rust-zookeeper) [[zookeeper-async](https://crates.io/crates/zookeeper-async)] - Async Zookeeper client, based on tokio.  ![build status](https://github.com/krojew/rust-zookeeper/actions/workflows/rust.yml/badge.svg)
* OGM [[ogm](https://crates.io/keywords/ogm)]
    * [Aragog](https://gitlab.com/qonfucius/aragog) [[aragog](https://crates.io/crates/aragog)] - 軽量ArangoDBオブジェクトドキュメント・リレーショナル・グラフマッパー [![パイプラインの状況]](https://gitlab.com/qonfucius/aragog/badges/master/pipeline.svg)](https://gitlab.com/qonfucius/aragog/-/commits/master)
* ORM [[orm](https://crates.io/keywords/orm)]
  * [Brendonovich/prisma-client-rust](https://github.com/Brendonovich/prisma-client-rust) - An autogenerated query builder that provides simple and fully type-safe database access using the Prisma ecosystem. [![Test Status](https://img.shields.io/github/workflow/status/Brendonovich/prisma-client-rust/CI?label=tests&style=flat-square)](https://github.com/Brendonovich/prisma-client-rust/actions)
  * [diesel-rs/diesel](https://github.com/diesel-rs/diesel) - an ORM and Query builder
  * [mjovanc/njord](https://github.com/mjovanc/njord) - ⛵ A lightweight ORM library for Rust [![build status](https://github.com/mjovanc/njord/actions/workflows/ci.yml/badge.svg)](https://github.com/mjovanc/njord/actions/workflows/ci.yml) ![crates.io](https://img.shields.io/crates/v/njord.svg)
  * [rbatis/rbatis](https://github.com/rbatis/rbatis) - ORM Framework High Performance(JSON based)
  * [SeaQL/sea-orm](https://github.com/SeaQL/sea-orm) - 🐚 An async & dynamic ORM  [![crate](https://img.shields.io/crates/v/sea-orm.svg)](https://crates.io/crates/sea-orm) [![docs](https://img.shields.io/docsrs/sea-orm/latest)](https://docs.rs/sea-orm) [![build status](https://github.com/SeaQL/sea-orm/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-orm/actions/workflows/rust.yml)
  * [SeaQL/seaography](https://github.com/SeaQL/seaography) - 🧭 GraphQL framework for SeaORM [![crate](https://img.shields.io/crates/v/seaography.svg)](https://crates.io/crates/seaography) [![docs](https://img.shields.io/docsrs/seaography/latest)](https://docs.rs/seaography) [![build status](https://github.com/SeaQL/seaography/actions/workflows/tests.yaml/badge.svg)](https://github.com/SeaQL/seaography/actions/workflows/tests.yaml)
* SQL [[sql](https://crates.io/keywords/sql)]
  * Generic
    * [launchbadge/sqlx](https://github.com/launchbadge/sqlx) - async PostgreSQL/MySQL/SQLite connection pool with strong typing support [![build badge](https://img.shields.io/github/workflow/status/launchbadge/sqlx/Rust/master?style=flat-square)](https://github.com/launchbadge/sqlx)
    * [launchbadge/sqlx](https://github.com/launchbadge/sqlx) - async PostgreSQL/MySQL/SQLite connection pool with strong typing support [![build badge](https://img.shields.io/github/workflow/status/launchbadge/sqlx/Rust/master?style=flat-square)](https://github.com/launchbadge/sqlx)
    * [SeaQL/sea-query](https://github.com/SeaQL/sea-query) - 🔱 A dynamic SQL query builder for MySQL, Postgres and SQLite [![crate](https://img.shields.io/crates/v/sea-query.svg)](https://crates.io/crates/sea-query) [![docs](https://img.shields.io/docsrs/sea-query/latest)](https://docs.rs/sea-query) [![build status](https://github.com/SeaQL/sea-query/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-query/actions/workflows/rust.yml)
    * [SeaQL/sea-schema](https://github.com/SeaQL/sea-schema) - 🌿 SQL schema definition and discovery [![crate](https://img.shields.io/crates/v/sea-schema.svg)](https://crates.io/crates/sea-schema) [![docs](https://img.shields.io/docsrs/sea-schema/latest)](https://docs.rs/sea-schema) [![build status](https://github.com/SeaQL/sea-schema/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-schema/actions/workflows/rust.yml)
  * Microsoft SQL
    * [prisma/tiberius](https://github.com/prisma/tiberius) - [貨物テスト](https://github.com/prisma/tiberius/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/prisma/tiberius/actions/workflows/test.yml)<div><sub>Stars: 326 / Last Update: 2024-07-31 / Initial Date: 2020-03-26</sub></div>
  * MySql [[mysql](https://crates.io/keywords/mysql)]
    * [blackbeam/mysql_async](https://github.com/blackbeam/mysql_async) [[mysql_async](https://crates.io/crates/mysql_async)] - asynchronous Mysql driver based on Tokio. [![CircleCI](https://circleci.com/gh/blackbeam/mysql_async/tree/master.svg?style=shield)](https://app.circleci.com/pipelines/github/blackbeam/mysql_async?branch=master)
    * [blackbeam/rust-mysql-simple](https://github.com/blackbeam/rust-mysql-simple) [[mysql](https://crates.io/crates/mysql)] - A native MySql client
  * Oracle
    * [kubo/rust-oracle](https://github.com/kubo/rust-oracle) [[oracle](https://crates.io/crates/oracle)] - Oracle driver [![build badge](https://github.com/kubo/rust-oracle/actions/workflows/run-tests.yml/badge.svg?branch=master)](https://github.com/kubo/rust-oracle/actions/workflows/run-tests.yml)
  * PostgreSql [[postgres](https://crates.io/keywords/postgres), [postgresql](https://crates.io/keywords/postgresql)]
    * [c410-f3r/wtx](https://github.com/c410-f3r/wtx) - Fast implementation with a low set of external dependencies.
    * [sfackler/rust-postgres](https://github.com/sfackler/rust-postgres) [[postgres](https://crates.io/crates/postgres)] - A native [PostgreSQL](https://www.postgresql.org/) client
  * Sqlite [[sqlite](https://crates.io/keywords/sqlite)]
    * [rusqlite](https://github.com/rusqlite/rusqlite) - [Sqlite3](https://www.sqlite.org/index.html)バインディング<div><sub>Stars: 3.1k / Last Update: 2024-10-01 / Initial Date: 2014-11-04</sub></div>

### Date and time

[[date](https://crates.io/keywords/date), [time](https://crates.io/keywords/time)]

* [arthurhenrique/rusti-cal](https://github.com/arthurhenrique/rusti-cal) [[rusti-cal](https://crates.io/crates/rusti-cal)] - A cal(1) clone lightning-fast ~ more than 9999 years ~ Written in Rust.
* [chronotope/chrono](https://github.com/chronotope/chrono) - Date and time library
* [sorairolake/nt-time](https://github.com/sorairolake/nt-time) [[nt-time](https://crates.io/crates/nt-time)] - A Windows file time library. [![CI](https://github.com/sorairolake/nt-time/workflows/CI/badge.svg?branch=develop)](https://github.com/sorairolake/nt-time/actions?query=workflow%3ACI)
* [time-rs/time](https://github.com/time-rs/time) - [ビルド・バッジ](https://github.com/time-rs/time/workflows/Build/badge.svg)](https://github.com/time-rs/time/actions)<div><sub>Stars: 1.1k / Last Update: 2024-09-06 / Initial Date: 2014-11-10</sub></div>

### Distributed systems

* Antimony
* Apache Kafka
  * [fede1024/rust-rdkafka](https://github.com/fede1024/rust-rdkafka) [[rdkafka](https://crates.io/crates/rdkafka)] - [librdkafka](https://github.com/confluentinc/librdkafka) バインディング<div><sub>Stars: 1.6k / Last Update: 2024-10-03 / Initial Date: 2016-10-29</sub></div>
  * [gklijs/schema_registry_converter](https://github.com/gklijs/schema_registry_converter) [[schema_registry_converter](https://crates.io/crates/schema_registry_converter)] - to integrate with [confluent schema registry](https://www.confluent.io/product/confluent-platform/data-compatibility/)
  * [kafka-rust/kafka-rust](https://github.com/kafka-rust/kafka-rust) - Rust client for Apache Kafka
* HDFS
* Other
  * [build-trust/ockam](https://github.com/build-trust/ockam) [[ockam](https://crates.io/crates/ockam)] - End-to-End Encryption, Mutual Authentication, and ABAC for distributed applications [![build badge](https://github.com/build-trust/ockam/workflows/Rust/badge.svg)](https://github.com/build-trust/ockam)
  * [build-trust/ockam](https://github.com/build-trust/ockam) [[ockam](https://crates.io/crates/ockam)] - End-to-End Encryption, Mutual Authentication, and ABAC for distributed applications [![build badge](https://github.com/build-trust/ockam/workflows/Rust/badge.svg)](https://github.com/build-trust/ockam)

### Domain driven design

  * [serverlesstechnology/cqrs](https://github.com/serverlesstechnology/cqrs) [[cqrs-es](https://crates.io/crates/cqrs-es)] - A framework for CQRS and event sourcing with [user guide](https://doc.rust-cqrs.org/)

### eBPF

* [aya/aya-rs](https://github.com/aya-rs/aya) - Built with a focus on developer experience and operability.
* [libbpf/libbpf-rs](https://github.com/libbpf/libbpf-rs) - A minimal and opinionated eBPF tooling.

### Email

[[email](https://crates.io/keywords/email), [imap](https://crates.io/keywords/imap), [smtp](https://crates.io/keywords/smtp)]

* [duesee/imap-codec](https://github.com/duesee/imap-codec) [[imap-codec](https://crates.io/crates/imap-codec)] - Rock-solid and complete codec for IMAP [![Build & Test](https://github.com/duesee/imap-codec/actions/workflows/build_and_test.yml/badge.svg)](https://github.com/duesee/imap-codec/actions/workflows/build_and_test.yml)
* [gsquire/sendgrid-rs](https://github.com/gsquire/sendgrid-rs) - Library for SendGrid API
* [jdrouet/catapulte](https://github.com/jdrouet/catapulte) - A microservice to send emails using [MRML](https://github.com/jdrouet/mrml) templates.
* [jdrouet/catapulte](https://github.com/jdrouet/catapulte) - A microservice to send emails using [MRML](https://github.com/jdrouet/mrml) templates.
* [jdrouet/mrml](https://github.com/jdrouet/mrml) - A library to generate nice email templates working on any mail client.
* [lettre/lettre](https://github.com/lettre/lettre) - an SMTP-library [![CI](https://github.com/lettre/lettre/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/lettre/lettre/actions/workflows/test.yml)
* [mailtutan/mailtutan](https://github.com/mailtutan/mailtutan) - An SMTP server for test and development environment.
* [meli/meli](https://github.com/meli/meli) - 🐝 terminal mail client
* [staktrace/mailparse](https://github.com/staktrace/mailparse) [[mailparse](https://crates.io/crates/mailparse)] - A library for parsing real-world email files
* [stalwartlabs/mail-auth](https://github.com/stalwartlabs/mail-auth) [[mail-auth](https://crates.io/crates/mail-auth)] - DKIM, ARC, SPF and DMARC message authentication library [![build badge](https://github.com/stalwartlabs/mail-auth/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-auth/actions/workflows/rust.yml)
* [stalwartlabs/mail-parser](https://github.com/stalwartlabs/mail-parser) [[mail-parser](https://crates.io/crates/mail-parser)] - A fast and robust e-mail parsing library with full MIME support [![build badge](https://github.com/stalwartlabs/mail-parser/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-parser/actions/workflows/rust.yml)
* [stalwartlabs/mail-send](https://github.com/stalwartlabs/mail-send) [[mail-send](https://crates.io/crates/mail-send)] - E-mail builder and SMTP client library with DKIM support [![build badge](https://github.com/stalwartlabs/mail-send/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-send/actions/workflows/rust.yml)
* [tweedegolf/mailcrab](https://github.com/tweedegolf/mailcrab) - Email test server for development.

### Encoding

[[encoding](https://crates.io/keywords/encoding)]

* ASN.1
  * [alex/rust-asn1](https://github.com/alex/rust-asn1) - ASN.1 (DER) serializer
* Binary
  * [bincode-org/bincode](https://github.com/bincode-org/bincode) - A binary encoder/decoder [![CI](https://github.com/bincode-org/bincode/actions/workflows/rust.yml/badge.svg?branch=trunk)](https://github.com/bincode-org/bincode/actions/workflows/rust.yml)
  * [jamesmunns/postcard](https://github.com/jamesmunns/postcard) [[postcard](https://crates.io/crates/postcard)] - Postcard is a #![no_std] focused serializer and deserializer for Serde.
  * [m4b/goblin](https://github.com/m4b/goblin) [[goblin](https://crates.io/crates/goblin)] - cross-platform, zero-copy, and endian-aware binary parsing
* BSON
  * [mongodb/bson-rust](https://github.com/mongodb/bson-rust) - Encoding and decoding support for BSON
* Byte swapping
  * [BurntSushi/byteorder](https://github.com/BurntSushi/byteorder) - Supports big-endian, little-endian and native byte orders
* Cap'n Proto
  * [capnproto/capnproto-rust](https://github.com/capnproto/capnproto-rust) - Cap'n Proto is a type system for distributed systems
* CBOR
  * [serde_cbor](https://crates.io/crates/serde_cbor) - セルデのCBORサポート
* Character Encoding
  * [hsivonen/encoding_rs](https://github.com/hsivonen/encoding_rs) [[encoding_rs](https://crates.io/crates/encoding_rs)] - A Gecko-oriented implementation of the Encoding Standard
* CRC
  * [mrhooray/crc-rs](https://github.com/mrhooray/crc-rs) - Rust implementation of CRC(16, 32, 64) with support of various standards
* CSV
  * [BurntSushi/rust-csv](https://github.com/BurntSushi/rust-csv) - A fast and flexible CSV reader and writer, with support for Serde
* EDN
  * [edn-rs](https://github.com/naomijub/edn-rs) [[edn-rs](https://crates.io/crates/edn-rs)] - crate to parse and emit EDN format into Rust types.
* [FlatBuffers](https://flatbuffers.dev/)
  * [frol/flatc-rust](https://github.com/frol/flatc-rust) - FlatBuffers compiler (flatc) integration for Cargo build scripts
* HAR
* HTML
  * [servo/html5ever](https://github.com/servo/html5ever) - High-performance browser-grade HTML5 parser
* JSON
  * [cloudwego/sonic-rs](https://github.com/cloudwego/sonic-rs) [[sonic-rs](https://crates.io/crates/sonic-rs)] - A fast Rust JSON library based on SIMD.
  * [rustadopt/jzon-rs](https://github.com/rustadopt/jzon-rs/) [[jzon](https://crates.io/crates/jzon)] - JSON implementation
  * [serde-rs/json](https://github.com/serde-rs/json) [[serde\_json](https://crates.io/crates/serde_json)] - JSON support for [Serde](https://github.com/serde-rs/serde) framework
  * [serde-rs/json](https://github.com/serde-rs/json) [[serde\_json](https://crates.io/crates/serde_json)] - JSON support for [Serde](https://github.com/serde-rs/serde) framework
  * [simd-lite/simd-json](https://github.com/simd-lite/simd-json) [[simd-json](https://crates.io/crates/simd-json)] - High performance JSON parser based on a port of simdjson
* MsgPack
  * [3Hren/msgpack-rust](https://github.com/3Hren/msgpack-rust) - Low/high level MessagePack implementation
* NetCDF
  * [georust/netcdf](https://github.com/georust/netcdf) [[netcdf](https://crates.io/crates/netcdf)] - Medium-level netCDF bindings, allowing easy reading and writing of array-like structures to a file.
* PEM
  * [jcreekmore/pem-rs](https://github.com/jcreekmore/pem-rs) [[pem](https://crates.io/crates/pem)] - Parse and encode PEM-encoded data
* ProtocolBuffers
  * [stepancheg/rust-protobuf](https://github.com/stepancheg/rust-protobuf) - Rust implementation of Google protocol buffers
  * [tokio-rs/prost](https://github.com/tokio-rs/prost) - [継続的インテグレーション](https://github.com/tokio-rs/prost/workflows/continuous%20integration/badge.svg?branch=master)](https://github.com/tokio-rs/prost/actions)<div><sub>Stars: 3.9k / Last Update: 2024-10-02 / Initial Date: 2017-06-13</sub></div>
* rkyv
  * [rkyv/rkyv](https://github.com/rkyv/rkyv) [[rkyv](https://crates.io/crates/rkyv)] - rkyv (archive) is a zero-copy deserialization framework
* RON (Rusty Object Notation)
  * [https://github.com/ron-rs/ron](https://github.com/ron-rs/ron) - Rusty Object Notation
* Serde
  * [iddm/serde-aux](https://github.com/iddm/serde-aux/) - additional tools for using with the serde library. [![CI](https://github.com/iddm/serde-aux/actions/workflows/ci.yml/badge.svg)](https://github.com/iddm/serde-aux/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/serde-aux.svg)](https://crates.io/crates/serde-aux)
* TOML
  * [tamasfe/taplo](https://github.com/tamasfe/taplo) [[taplo](https://crates.io/crates/taplo)] - A TOML toolkit [![CI](https://github.com/tamasfe/taplo/workflows/Continuous%20integration/badge.svg)](https://github.com/tamasfe/taplo/actions?query=workflow%3A%22Continuous+integration%22)
  * [toml-rs/toml](https://github.com/toml-rs/toml) - [[CI](https://github.com/toml-rs/toml/actions/workflows/ci.yml/badge.svg)](https://github.com/toml-rs/toml/actions/workflows/ci.yml)<div><sub>Stars: 700 / Last Update: 2024-10-01 / Initial Date: 2017-06-30</sub></div>
* XML
  * [media-io/yaserde](https://github.com/media-io/yaserde) - Yet Another Serializer/Deserializer specialized for XML
  * [netvl/xml-rs](https://github.com/netvl/xml-rs) - A streaming XML library
  * [tafia/quick-xml](https://github.com/tafia/quick-xml) - High performance XML pull reader/writer
* YAML
  * [dtolnay/serde-yaml](https://github.com/dtolnay/serde-yaml) [[serde\_yaml](https://crates.io/crates/serde_yaml)] - YAML support for [Serde](https://github.com/serde-rs/serde) framework [![build](https://img.shields.io/github/workflow/status/dtolnay/serde-yaml/CI/master)](https://github.com/dtolnay/serde-yaml/actions?query=branch%3Amaster)
  * [dtolnay/serde-yaml](https://github.com/dtolnay/serde-yaml) [[serde\_yaml](https://crates.io/crates/serde_yaml)] - YAML support for [Serde](https://github.com/serde-rs/serde) framework [![build](https://img.shields.io/github/workflow/status/dtolnay/serde-yaml/CI/master)](https://github.com/dtolnay/serde-yaml/actions?query=branch%3Amaster)
  * [vitiral/stfu8](https://github.com/vitiral/stfu8) [[stfu8](https://crates.io/crates/stfu8)] - Sorta Text Format in UTF-8

### Filesystem

[[filesystem](https://crates.io/keywords/filesystem)]
* Operations
  * [Camino](https://github.com/camino-rs/camino) [[camino](https://crates.io/crates/camino)] - Like Rust's std::path::Path, but UTF-8.
  * [OpenDAL](https://github.com/apache/opendal) [[opendal](https://crates.io/crates/opendal)] - A unified data access layer, empowering users to seamlessly and efficiently retrieve data from diverse storage services. [![build](https://img.shields.io/github/actions/workflow/status/apache/opendal/ci_core.yml?branch=main)](https://github.com/apache/opendal/actions?query=branch%3Amain)
  * [pop-os/sys-mount](https://github.com/pop-os/sys-mount) [[sys-mount](https://crates.io/crates/sys-mount)] - High level abstraction for the `mount` / `umount2` system calls.
* Temporary Files
  * [Stebalien/tempfile](https://github.com/Stebalien/tempfile) - temporary file library
  * [Stebalien/xattr](https://github.com/Stebalien/xattr) [[xattr](https://crates.io/crates/xattr)] - list and manipulate unix extended file attributes

### Finance

* [avhz/RustQuant](https://github.com/avhz/RustQuant) [[RustQuant](https://crates.io/crates/RustQuant)] - A quantitative finance library. ![GitHub Workflow Status (with event)](https://img.shields.io/github/actions/workflow/status/avhz/RustQuant/build.yml)
* [d-e-s-o/apca](https://github.com/d-e-s-o/apca) [[apca](https://crates.io/crates/apca)] - Opinionated and comprehensive bindings to the [Alpaca API](https://alpaca.markets/) for stock trading and more. ![GitHub Workflow Status](https://github.com/d-e-s-o/apca/actions/workflows/test.yml/badge.svg?branch=main)
* [dancixx/stochastic-rs](https://github.com/dancixx/stochastic-rs) [[stochastic-rs](https://crates.io/crates/stochastic-rs)] - High-performance data generation library for stochastic process with quant finance tools. ![GitHub Workflow Status](https://github.com/dancixx/stochastic-rs/actions/workflows/rust.yml/badge.svg)

### Functional Programming

[[functional programming](https://crates.io/keywords/fp)]
* Prelude

### Game development

See also [Are we game yet?](https://arewegameyet.rs)
* Allegro
  * [SiegeLord/RustAllegro](https://github.com/SiegeLord/RustAllegro) - [アレグロ5](https://liballeg.org/)バインディング<div><sub>Stars: 94 / Last Update: 2024-07-21 / Initial Date: 2013-04-12</sub></div>
* [Awesome Quads](https://github.com/ozkriff/awesome-quads) - A curated list of links to miniquad/macroquad-related code & resources
* bracket-lib (previously RLTK)
* Challonge
  * [iddm/challonge-rs](https://github.com/iddm/challonge-rs) [[challonge](https://crates.io/crates/challonge)] - Client library for the Challonge REST API. Helps to organize tournaments. [![CI](https://github.com/iddm/challonge-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/iddm/challonge-rs/actions/workflows/ci.yml)
* Entity-Component Systems (ECS)
  * [amethyst/specs](https://github.com/amethyst/specs) - Specs Parallel ECS
* Game Engines
  * [Bevy](https://github.com/bevyengine/bevy) - は爽やかでシンプルなデータ駆動型ゲームエンジンだ。<div><sub>Stars: 35.5k / Last Update: 2024-10-04 / Initial Date: 2020-01-18</sub></div>
  * [Fyrox](https://fyrox.rs/) - ゲームエンジン3D [![Crates.io](https://img.shields.io/crates/v/fyrox.svg)](https://crates.io/crates/fyrox) [![ライセンス](https://img.shields.io/crates/l/fyrox.svg)](https://github.com/FyroxEngine/Fyrox/blob/master/LICENSE.md) [![Crates.io](https://img.shields.io/crates/d/fyrox.svg)](https://crates.io/crates/fyrox)
  * [Kiss3d](http://kiss3d.org) - シンプルで愚直な3Dグラフィックエンジン [![Crates.io](https://img.shields.io/crates/d/kiss3d.svg)](https://crates.io/crates/kiss3d)
  * [Piston](https://www.piston.rs/) - [![Crates.io](https://img.shields.io/crates/v/piston.svg?style=flat-square)](https://crates.io/crates/piston) [![Crates.io](https://img.shields.io/crates/l/piston.svg)](https://github.com/PistonDevelopers/piston/blob/master/LICENSE) [![Crates.io](https://img.shields.io/crates/d/piston.svg)](https://crates.io/crates/piston)
* Game Servers
  * [gamedig/rust-gamedig](https://github.com/gamedig/rust-gamedig) [[gamedig](https://crates.io/crates/gamedig)] - Query game servers for informations such as name, players online, max players count etc. [![Crates.io](https://img.shields.io/crates/v/gamedig.svg)](https://crates.io/crates/gamedig) [![Crates.io](https://img.shields.io/crates/d/gamedig.svg)](https://crates.io/crates/gamedig)
* [Godot](https://godotengine.org/)
  * [godot-rust/gdnative](https://github.com/godot-rust/gdnative) [[gdnative](https://crates.io/crates/gdnative)] - Bindings to the Godot game engine [![CI](https://github.com/godot-rust/gdnative/actions/workflows/full-ci.yml/badge.svg)](https://github.com/godot-rust/gdnative/actions/workflows/full-ci.yml)
* [Raylib](https://www.raylib.com/)
  * [deltaphc/raylib-rs](https://github.com/deltaphc/raylib-rs) [[raylib](https://crates.io/crates/raylib)] - Bindings for raylib
* [SDL](http://www.libsdl.org/) [[sdl](https://crates.io/keywords/sdl)]
  * [Rust-SDL2/rust-sdl2](https://github.com/Rust-SDL2/rust-sdl2) - SDL2 bindings
* SFML
  * [jeremyletang/rust-sfml](https://github.com/jeremyletang/rust-sfml) - [SFML](https://www.sfml-dev.org/) バインディング<div><sub>Stars: 631 / Last Update: 2024-10-04 / Initial Date: 2013-05-29</sub></div>
* Skillratings
  * [atomflunder/skillratings](https://github.com/atomflunder/skillratings) [[skillratings](https://crates.io/crates/skillratings)] - Collection of skill rating algorithms for multiplayer games like Elo, Glicko-2, TrueSkill etc. [![crates.io badge](https://img.shields.io/crates/v/skillratings)](https://crates.io/crates/skillratings) [![CI](https://github.com/atomflunder/skillratings/actions/workflows/ci.yml/badge.svg)](https://github.com/atomflunder/skillratings/actions/workflows/ci.yml)
* Tcod-rs
  * Warning: Not maintained anymore
* Toornament-rs
  * [iddm/toornament-rs](https://github.com/iddm/toornament-rs) - Toornament.com API bindings. [![CI](https://github.com/iddm/toornament-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/iddm/toornament-rs/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/toornament.svg)](https://crates.io/crates/toornament)
* Victorem

### Geospatial

[[geo](https://crates.io/keywords/geo), [gis](https://crates.io/keywords/gis)]

* [Georust](https://github.com/georust) - 地理空間ツールおよびライブラリ
* [MapLibre/Martin](https://github.com/maplibre/martin) - Map tile server with PostGIS, MBTiles, PMTiles, and sprites support. [![CI build](https://github.com/maplibre/martin/actions/workflows/ci.yml/badge.svg)](https://github.com/maplibre/martin/actions)[![crates.io version](https://img.shields.io/crates/v/martin.svg)](https://crates.io/crates/martin)[![Book](https://img.shields.io/badge/docs-Book-informational)](https://maplibre.org/martin/)
* [rust-reverse-geocoder](https://github.com/gx0r/rrgeo) - A fast, offline reverse geocoder, inspired by [thampiman/reverse-geocoder](https://github.com/thampiman/reverse-geocoder)
* [vlopes11/geomorph](https://github.com/vlopes11/geomorph) [[geomorph](https://crates.io/crates/geomorph)] - conversion between UTM, LatLon and MGRS coordinates

### Graph algorithms

* [neo4j-labs/graph](https://github.com/neo4j-labs/graph) - A library for high-performant graph algorithms [![graph CI status](https://img.shields.io/github/workflow/status/neo4j-labs/graph/CI/main?label=CI)](https://github.com/neo4j-labs/graph/actions/workflows/rust.yml)
* [petgraph/petgraph](https://github.com/petgraph/petgraph) - Graph data structure library. [![graph CI status](https://github.com/petgraph/petgraph/workflows/Continuous%20integration/badge.svg?branch=master)](https://github.com/petgraph/petgraph/actions/workflows/ci.yml)

### Graphics

[[graphics](https://crates.io/keywords/graphics)]

* Font
  * [RazrFalcon/rustybuzz](https://github.com/RazrFalcon/rustybuzz) - An incremental harfbuzz port
* [gfx-rs/wgpu](https://github.com/gfx-rs/wgpu) - Native WebGPU implementation based on gfx-hal. [![build badge](https://github.com/gfx-rs/wgpu/workflows/CI/badge.svg?branch=master)](https://github.com/gfx-rs/wgpu/actions)
* OpenGL [[opengl](https://crates.io/keywords/opengl)]
  * [glium/glium](https://github.com/glium/glium) - safe OpenGL wrapper.
  * [glutin](https://crates.io/crates/glutin) - GLFW](https://www.glfw.org/)の代替案。
  * [Kiss3d](http://kiss3d.org) - draw simple geometric figures and play with them with one-liners
  * [PistonDevelopers/glfw-rs](https://github.com/PistonDevelopers/glfw-rs) - GLFW3 bindings and idiomatic wrapper
* PDF
  * [bastibense/libharu_ng](https://github.com/bastibense/libharu_ng) [[libharu_ng](https://crates.io/crates/libharu_ng)] - Easily generate PDFs from your Rust app.
  * [fschutt/printpdf](https://github.com/fschutt/printpdf) - PDF writing library
  * [J-F-Liu/lopdf](https://github.com/J-F-Liu/lopdf) - PDF document manipulation
* [Vulkan](https://www.vulkan.org/) [[vulkan](https://crates.io/keywords/vulkan)]
  * [erupt](https://gitlab.com/Friz64/erupt) [[erupt](https://crates.io/crates/erupt)] - [ビルド・バッジ](https://gitlab.com/Friz64/erupt/badges/main/pipeline.svg)](https://gitlab.com/Friz64/erupt/-/pipelines)
  * [vulkano](https://github.com/vulkano-rs/vulkano) [[vulkano](https://crates.io/crates/vulkano)] - Safe and rich Rust wrapper around the Vulkan API

### GUI

[[gui](https://crates.io/keywords/gui)]

* Cocoa
  * [servo/core-foundation-rs](https://github.com/servo/core-foundation-rs) - Rust bindings to Core Foundation and other low level libraries on Mac OS X and iOS
* [DioxusLabs/dioxus](https://github.com/dioxuslabs/dioxus) - a portable, performant, and ergonomic framework for building cross-platform user interfaces in Rust. ![rust ci](https://github.com/dioxuslabs/dioxus/actions/workflows/main.yml/badge.svg)
* [emilk/egui](https://github.com/emilk/egui) - Simple, fast, and highly portable immediate mode GUI library. egui runs on the web, natively, and in your favorite game engine. [![Build Status](https://github.com/emilk/egui/workflows/CI/badge.svg)](https://github.com/emilk/egui/actions?workflow=CI)
* [emoon/rust_minifb](https://github.com/emoon/rust_minifb) - minifb is a cross-platform window setup with optional bitmap rendering. It also comes with easy mouse and keyboard input. Primarily designed for prototyping
* [FLTK](https://www.fltk.org/)
  * [fltk-rs](https://github.com/fltk-rs/fltk-rs) - FLTK bindings [![Build](https://github.com/fltk-rs/fltk-rs/workflows/Build/badge.svg?branch=master)](https://github.com/fltk-rs/fltk-rs/actions)
* [Flutter](https://flutter.dev/)
  * [cunarist/rinf](https://github.com/cunarist/rinf) - Rust as your Flutter backend, Flutter as your Rust frontend [![Build Test](https://github.com/cunarist/rinf/actions/workflows/build_test.yaml/badge.svg)](https://github.com/cunarist/rinf/actions/workflows/build_test.yaml?query=branch%3Amain)
  * [fzyzcjy/flutter_rust_bridge](https://github.com/fzyzcjy/flutter_rust_bridge) - High-level memory-safe binding generator for Flutter/Dart <-> Rust
* [fschutt/azul](https://github.com/fschutt/azul) - A free, functional, IMGUI-oriented GUI framework for rapid development of desktop applications written in Rust, supported by the Mozilla WebRender rendering engine.
* [GTK+](https://www.gtk.org/) [[gtk](https://crates.io/keywords/gtk)]
  * [gtk-rs/gtk4-rs](https://github.com/gtk-rs/gtk4-rs) - GTK4 binding ![CI](https://github.com/gtk-rs/gtk4-rs/workflows/CI/badge.svg)
  * [relm](https://github.com/antoyo/relm) - Asynchronous, GTK+-based, GUI library, inspired by Elm
* [iced-rs/iced](https://github.com/iced-rs/iced) [[iced](https://crates.io/crates/iced)] - A cross-platform GUI library, focused on simplicity and type-safety. Inspired by Elm.
* [ImGui](https://github.com/ocornut/imgui)
  * [imgui-rs](https://github.com/imgui-rs/imgui-rs) - Bindings for ImGui [![Build Status](https://github.com/imgui-rs/imgui-rs/workflows/ci/badge.svg?branch=master)](https://github.com/imgui-rs/imgui-rs/actions)
* [IUP](http://webserver2.tecgraf.puc-rio.br/iup/)
* [makepad/makepad](https://github.com/makepad/makepad) [[makepad-widgets](https://crates.io/crates/makepad-widgets)] - Makepad is a creative software development platform that compiles to wasm/webGL, osx/metal, windows/dx11 linux/opengl.
* [Nuklear](https://github.com/Immediate-Mode-UI/Nuklear)
* [Qt](https://doc.qt.io)
  * [rust-qt](https://github.com/rust-qt) - Rust用Qtバインディング
  * [woboq/qmetaobject-rs](https://github.com/woboq/qmetaobject-rs) - Integrate Qml and Rust by building the QMetaObject at compile time.
* [Sciter](https://sciter.com/)
* [slint-ui/slint](https://github.com/slint-ui/slint) [slint](https://crates.io/crates/slint) - [Slint](https://slint.dev/)は、組み込み機器やデスクトップアプリケーション向けの流体グラフィカル・ユーザー・インターフェースを効率的に開発するためのツールキットです。[ビルド状況](https://github.com/slint-ui/slint/workflows/CI/badge.svg?branch=master)](https://github.com/slint-ui/slint/actions?query=workflow%3ACI)<div><sub>Stars: 17.1k / Last Update: 2024-10-04 / Initial Date: 2020-05-04</sub></div>
* [tauri-apps/tauri](https://github.com/tauri-apps/tauri) - Build smaller, faster, and more secure desktop applications with a web frontend, powered by [WRY](https://github.com/tauri-apps/wry). [![test library](https://img.shields.io/github/workflow/status/tauri-apps/tauri/test%20library?label=test%20library)](https://github.com/tauri-apps/tauri/actions?query=workflow%3A%22test+library%22)
* [tauri-apps/tauri](https://github.com/tauri-apps/tauri) - Build smaller, faster, and more secure desktop applications with a web frontend, powered by [WRY](https://github.com/tauri-apps/wry). [![test library](https://img.shields.io/github/workflow/status/tauri-apps/tauri/test%20library?label=test%20library)](https://github.com/tauri-apps/tauri/actions?query=workflow%3A%22test+library%22)
* [tauri-apps/wry](https://github.com/tauri-apps/wry) - Webview Rendering librarY.
* [xilem](https://github.com/linebender/xilem) - Successor of the data-first UI design toolkit [druid](https://github.com/linebender/druid).
* [xilem](https://github.com/linebender/xilem) - Successor of the data-first UI design toolkit [druid](https://github.com/linebender/druid).

### Image processing

* [Enet4/dicom-rs](https://github.com/Enet4/dicom-rs) - A pure Rust implementation of the DICOM standard, allowing users to work with DICOM objects and interact with DICOM applications, while aiming to be fast, safe, and intuitive to use.
* [image-rs/image](https://github.com/image-rs/image) - Basic imaging processing functions and methods for converting to and from image formats
* [image-rs/imageproc](https://github.com/image-rs/imageproc) - An image processing library, based on the `image` library.
* [twistedfall/opencv-rust](https://github.com/twistedfall/opencv-rust) - Bindings for OpenCV

### Language specification

* [shnewto/bnf](https://github.com/shnewto/bnf) - A library for parsing Backus–Naur form context-free grammars.

### Logging

[[log](https://crates.io/keywords/log)]

* [donnie4w/tklog](https://github.com/donnie4w/tklog "donnie4w/tklog") - ログレベル、ファイルセグメンテーション、圧縮アーカイブをサポートする、軽量で効率的な錆構造ログライブラリ。
* [estk/log4rs](https://github.com/estk/log4rs) - highly configurable logging framework modeled after Java's Logback and log4j libraries [![CircleCI](https://circleci.com/gh/estk/log4rs.svg?style=shield)](https://app.circleci.com/pipelines/github/estk/log4rs)
* [rbatis/fast_log](https://github.com/rbatis/fast_log) - Async log High-performance asynchronous logging
* [rust-lang/log](https://github.com/rust-lang/log) - Logging implementation
* [slog-rs/slog](https://github.com/slog-rs/slog) - Structured, composable logging
* [tokio-rs/tracing](https://github.com/tokio-rs/tracing) - An application level tracing framework for async-aware structured logging, error handling, metrics, and more [![Build Status](https://github.com/tokio-rs/tracing/workflows/CI/badge.svg?branch=master)](https://github.com/tokio-rs/tracing/actions?query=workflow%3ACI)

### Macro

* cute

### Markup language

* CommonMark
  * [pulldown-cmark/pulldown-cmark](https://github.com/pulldown-cmark/pulldown-cmark) - [コモンマーク](https://commonmark.org/)パーサー<div><sub>Stars: 2.0k / Last Update: 2024-09-24 / Initial Date: 2015-06-03</sub></div>
* [insomnimus/tidier](https://github.com/insomnimus/tidier) [[tidier](https://crates.io/crates/tidier)] - A library to format HTML, XHTML and XML documents. [![build badge](https://github.com/insomnimus/tidier/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/insomnimus/tidier/actions)

### Mobile

* Android / iOS
* Generic
  * [redbadger/crux](https://github.com/redbadger/crux) [[crux_core](https://crates.io/crates/crux_core)] - Cross-platform app development. Crux helps you share your app's business logic and behavior across mobile (iOS/Android) and web - as a single reusable core. [![Build status](https://img.shields.io/github/actions/workflow/status/redbadger/crux/build.yaml)](https://github.com/redbadger/crux/actions)
* iOS
  * [TimNN/cargo-lipo](https://github.com/TimNN/cargo-lipo) - A cargo lipo subcommand which automatically creates a universal library for use with your iOS application.

### Network programming

* Bluetooth
  * [bluez/bluer](https://github.com/bluez/bluer) [[bluer](https://crates.io/crates/bluer)] - Official BlueZ bindings. [![build badge](https://github.com/bluez/bluer/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/bluez/bluer/actions/workflows/rust.yml)
* CoAP
  * [Covertness/coap-rs](https://github.com/Covertness/coap-rs) - A [Constrained Application Protocol(CoAP)](https://datatracker.ietf.org/doc/html/rfc7252) library.
* Docker
  * [fussybeaver/bollard](https://github.com/fussybeaver/bollard) - Docker daemon API
* FTP
* gRPC
  * [hyperium/tonic](https://github.com/hyperium/tonic) - A native gRPC client & server implementation with async/await support [![Crates.io](https://img.shields.io/crates/v/tonic)](https://crates.io/crates/tonic)
  * [tikv/grpc-rs](https://github.com/tikv/grpc-rs) - The gRPC library built on C Core library and futures
* HTTP
  * [Hurl](https://github.com/Orange-OpenSource/hurl) - Run and test HTTP requests with plain text and libcurl [![CI](https://github.com/Orange-OpenSource/hurl/workflows/CI/badge.svg)](https://github.com/Orange-OpenSource/hurl/actions)
* IPNetwork
  * [achanda/ipnetwork](https://github.com/achanda/ipnetwork) - A library to work with IP networks
* Low level
  * [actix/actix](https://github.com/actix/actix) - Actor library
  * [libpnet/libpnet](https://github.com/libpnet/libpnet) - A cross-platform, low level networking
  * [smoltcp-rs/smoltcp](https://github.com/smoltcp-rs/smoltcp) - A standalone, event-driven TCP/IP stack that is designed for bare-metal, real-time systems
* message-io
  * [lemunozm/message-io](https://github.com/lemunozm/message-io) - Event-driven message library to build network applications easy and fast. Supports TCP, UDP and WebSockets. [![build badge](https://img.shields.io/github/workflow/status/lemunozm/message-io/message-io%20ci)](https://github.com/lemunozm/message-io/actions?query=workflow%3A%22message-io+ci%22)
* MQTT
  * [bytebeamio/rumqtt](https://github.com/bytebeamio/rumqtt) - A library for developers to build applications that communicate with the [MQTT protocol](https://mqtt.org) over TCP and WebSockets, with or without TLS. [![Build and Test](https://github.com/bytebeamio/rumqtt/actions/workflows/build.yml/badge.svg)](https://github.com/bytebeamio/rumqtt/actions/workflows/build.yml)
  * [rmqtt/rmqtt](https://github.com/rmqtt/rmqtt) - MQTT Server/MQTT Broker - Scalable Distributed MQTT Message Broker for IoT in the 5G Era
* NanoMsg
  * [thehydroimpulse/nanomsg.rs](https://github.com/thehydroimpulse/nanomsg.rs) - [nanomsg](https://nanomsg.org/) バインディング<div><sub>Stars: 391 / Last Update: 2023-11-02 / Initial Date: 2013-09-07</sub></div>
* NATS
  * [nats-io/nats.rs](https://github.com/nats-io/nats.rs) - Client for NATS, the cloud native messaging system. [![Build Status](https://github.com/nats-io/nats.rs/workflows/Rust/badge.svg?branch=master)](https://github.com/nats-io/nats.rs/actions)
* Nng
  * [neachdainn/nng-rs](https://gitlab.com/neachdainn/nng-rs) [[Nng](https://crates.io/crates/nng)] - [Nng (nanomsg v2)](https://nng.nanomsg.org/index.html) バインディング [![ビルドバッジ]](https://gitlab.com/neachdainn/nng-rs/badges/master/pipeline.svg)](https://gitlab.com/neachdainn/nng-rs/-/pipelines)
* NNTP
* P2P
  * [libp2p/rust-libp2p](https://github.com/libp2p/rust-libp2p) - Implementation of libp2p networking stack. [![Circle CI](https://circleci.com/gh/libp2p/rust-libp2p.svg?style=svg)](https://app.circleci.com/pipelines/github/libp2p/rust-libp2p)
  * [n0-computer/iroh](https://github.com/n0-computer/iroh) [[iroh](https://crates.io/crates/iroh)] - crate for building on direct connections between devices [![CI](https://github.com/n0-computer/iroh/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/n0-computer/iroh/actions/workflows/ci.yml)
* POP3
* QUIC
  * [aws/s2n-quic](https://github.com/aws/s2n-quic) - An implementation of the IETF QUIC protocol ![ci](https://img.shields.io/github/actions/workflow/status/aws/s2n-quic/ci.yml?branch=main)
  * [cloudflare/quiche](https://github.com/cloudflare/quiche) - cloudflare implementation of the QUIC transport protocol and HTTP/3 ![build](https://img.shields.io/github/actions/workflow/status/cloudflare/quiche/stable.yml?branch=master)
  * [mozilla/neqo](https://github.com/mozilla/neqo) - an Implementation of QUIC
  * [quinn-rs/quinn](https://github.com/quinn-rs/quinn) - Futures-based QUIC implementation [![build badge](https://dev.azure.com/dochtman/Projects/_apis/build/status/Quinn?branchName=master)](https://dev.azure.com/dochtman/Projects/_build)
  * [tencent/tquic](https://github.com/Tencent/tquic) - A high-performance, lightweight, and cross-platform QUIC library [![Build Status](https://img.shields.io/github/actions/workflow/status/tencent/tquic/rust.yml)](https://github.com/Tencent/tquic/actions/workflows/rust.yml)
* Raknet
* RPC
  * [ENQT-GmbH/remoc](https://github.com/ENQT-GmbH/remoc) [[remoc](https://crates.io/crates/remoc)] - Remoc provides channels (broadcast, mpsc, oneshot, watch) similar to Tokio's and trait calling over any remote transport. [![build badge](https://github.com/ENQT-GmbH/remoc/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/ENQT-GmbH/remoc/actions/workflows/rust.yml)
  * [smallnest/rpcx-rs](https://github.com/smallnest/rpcx-rs) - A RPC library for developing microservices in easy and simple way.
* Socket.io
  * [1c3t3a/rust-socketio](https://github.com/1c3t3a/rust-socketio) [[rust_socketio](https://crates.io/crates/rust_socketio)] - an implementation of a [socket.io](https://socket.io) client written in Rust. [![build badge](https://github.com/1c3t3a/rust-socketio/actions/workflows/build.yml/badge.svg)](https://github.com/1c3t3a/rust-socketio/actions/workflows/build.yml)
* SSH
  * [alexcrichton/ssh2-rs](https://github.com/alexcrichton/ssh2-rs) - [libssh2](https://libssh2.org/) バインディング<div><sub>Stars: 485 / Last Update: 2024-07-31 / Initial Date: 2014-09-18</sub></div>
  * [Thrussh](https://pijul.org/thrussh) [[thrussh](https://crates.io/crates/thrussh)] - libsodium](https://doc.libsodium.org/) にバックアップされた SSH ライブラリ。
* Stomp
* VPN
  * [defguard/wireguard-rs](https://github.com/DefGuard/wireguard-rs) - A multi-platform library providing a unified high-level API for managing WireGuard interfaces using native OS kernel and userspace WireGuard protocol implementations
* Zenoh
  * [eclipse-zenoh-flow/zenoh-flow](https://github.com/eclipse-zenoh-flow/zenoh-flow) - A declarative framework for computations that span from the *Cloud* to the *Thing*
  * [eclipse-zenoh/zenoh](https://github.com/eclipse-zenoh/zenoh) - Zero Overhead Network Protocol
* ZeroMQ

### Parsing

  * [comex/rust-shlex](https://github.com/comex/rust-shlex) [[shlex](https://crates.io/crates/shlex)] - Split a string into shell words, like Python's shlex. [![build badge](https://github.com/comex/rust-shlex/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/comex/rust-shlex/actions/workflows/test.yml)
  * [Eliah-Lakhin/lady-deirdre](https://github.com/Eliah-Lakhin/lady-deirdre) - A framework for new programming languages and LSP servers.
  * [hmeyer/stl_io](https://crates.io/crates/stl_io) - STL (STereoLithography) ファイルのパーサー
  * [igumnoff/shiva](https://github.com/igumnoff/shiva) - Shiva library: Implementation in Rust of a parser and generator for documents of any type (Plain text, Markdown, HTML, PDF and etc)
  * [kevinmehall/rust-peg](https://github.com/kevinmehall/rust-peg) - Parsing Expression Grammar (PEG) parser generator
  * [lalrpop/lalrpop](https://github.com/lalrpop/lalrpop) - LR(1) parser generator
  * [Marwes/combine](https://github.com/Marwes/combine) - parser combinator library
  * [pest-parser/pest](https://github.com/pest-parser/pest) - The Elegant Parser
  * [rust-bakery/nom](https://github.com/rust-bakery/nom) - parser combinator library
  * [softdevteam/grmtools](https://github.com/softdevteam/grmtools/) - A LR parser with better error correction
  * [tree-sitter/tree-sitter](https://github.com/tree-sitter/tree-sitter) - A parser generator tool and an incremental parsing library geared towards programming tools

### Peripherals

* Fingerprint reader
  * [alvaroparker/libfprint-rs](https://github.com/alvaroparker/libfprint-rs) [[libfprint-rs](https://crates.io/crates/libfprint-rs)] - Libfprint-rs provides a wrapper around the Linux libfprint library.
* Serial Port
  * [serialport/serialport-rs](https://github.com/serialport/serialport-rs) [[serialport](https://crates.io/crates/serialport)] - A cross-platform library that provides access to a serial port

### Platform specific

* Cross-platform
  * [iddm/thread-priority](https://github.com/iddm/thread-priority/) - Simple, crossplatform thread priority management. [![CI](https://github.com/iddm/thread-priority/actions/workflows/ci.yml/badge.svg)](https://github.com/iddm/thread-priority/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/thread-priority.svg)](https://crates.io/crates/thread-priority)
  * [svartalf/rust-battery](https://crates.io/crates/battery) - ノートパソコンのバッテリーに関するクロスプラットフォーム情報
* FreeBSD
  * [fubarnetes/libjail-rs](https://github.com/fubarnetes/libjail-rs/) [[jail](https://crates.io/crates/jail)] - FreeBSD jail library
* Linux
  * [hannobraun/inotify-rs](https://github.com/hannobraun/inotify-rs) - [inotify](https://en.wikipedia.org/wiki/Inotify) バインディング [![Rust](https://github.com/hannobraun/inotify-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/hannobraun/inotify-rs/actions/workflows/rust.yml)<div><sub>Stars: 256 / Last Update: 2024-09-18 / Initial Date: 2014-04-10</sub></div>
  * [pop-os/distinst](https://github.com/pop-os/distinst/) - Linux distribution installer
* Unix-like
  * [nix-rust/nix](https://github.com/nix-rust/nix) - Unix-like API bindings [![Cirrus Build Status](https://api.cirrus-ci.com/github/nix-rust/nix.svg)](https://cirrus-ci.com/github/nix-rust/nix)
  * [rustix](https://github.com/bytecodealliance/rustix) - Safe bindings to POSIX/Unix/Linux/Winsock2 syscalls [![Actions Status](https://github.com/bytecodealliance/rustix/workflows/CI/badge.svg)](https://github.com/bytecodealliance/rustix/actions?query=workflow%3ACI)
* Windows
  * [microsoft/windows-rs](https://github.com/microsoft/windows-rs) - Rust for Windows [![Actions Status](https://github.com/microsoft/windows-rs/workflows/CI/badge.svg)](https://github.com/microsoft/windows-rs/actions)

### Scripting

[[scripting](https://crates.io/keywords/scripting)]

* [3body-lang](https://github.com/rustq/3body-lang) - The Three Body Language
* [clarkmcc/cel-rust](https://github.com/clarkmcc/cel-rust) [[cel-interpreter](https://crates.io/crates/cel-interpreter)] - Common expression language parser and interpreter
* [duckscript](https://crates.io/crates/duckscript) - [シンプルで、拡張可能で、埋め込み可能なスクリプト言語。](https://github.com/sagiegurari/duckscript) [![ビルド・バッジ](https://github.com/sagiegurari/duckscript/workflows/CI/badge.svg?branch=master)](https://github.com/sagiegurari/duckscript/actions)<div><sub>Stars: 512 / Last Update: 2024-10-04 / Initial Date: 2019-12-12</sub></div>
* [gluon-lang/gluon](https://github.com/gluon-lang/gluon) - A small, statically-typed, functional programming language
* [kcl](https://github.com/kcl-lang/kcl) - A constraint-based record & functional language mainly used in configuration and policy scenarios.
* [metacall/core](https://github.com/metacall/core) [[metacall](https://crates.io/crates/metacall)] - Cross-platform Polyglot Runtime which supports NodeJS, JavaScript, TypeScript, Python, Ruby, C#, Wasm, Java, Cobol and more. [![build badge](https://gitlab.com/metacall/core/badges/master/pipeline.svg)](https://gitlab.com/metacall/core)
* [mun](https://github.com/mun-lang/mun) - A compiled, statically-typed scripting language with first class hot reloading support
* [PistonDevelopers/dyon](https://github.com/PistonDevelopers/dyon) - A rusty dynamically typed scripting language
* [rhaiscript/rhai](https://github.com/rhaiscript/rhai) - A tiny and fast embedded scripting language resembling a combination of JavaScript and Rust [![build badge](https://github.com/rhaiscript/rhai/workflows/Build/badge.svg)](https://github.com/rhaiscript/rhai/actions)
* [rune-rs/rune](https://github.com/rune-rs/rune) - An embeddable dynamic programming language

### Simulation

[[simulation](https://crates.io/keywords/simulation)]

* [nyx-space](https://crates.io/crates/nyx-space) - 高忠実度、高速、高信頼性、検証済みの天体力学ツールキットライブラリで、宇宙船のミッション設計や軌道決定に使用される[[ビルド状況]](https://gitlab.com/nyx-space/nyx/badges/master/pipeline.svg)](https://gitlab.com/nyx-space/nyx/-/pipelines)

### Social networks

* Telegram
  * [tdilb-rs](https://github.com/FedericoBruzzone/tdlib-rs) [[tdilb-rs](https://crates.io/crates/tdlib-rs)] - Crossplatform Rust wrapper around the Telegram Database Library (TDLib) [![CI Linux](https://github.com/FedericoBruzzone/tdlib-rs/actions/workflows/ci-linux.yml/badge.svg)](https://github.com/FedericoBruzzone/tdlib-rs/actions/workflows/ci-linux.yml) [![CI macOS](https://github.com/FedericoBruzzone/tdlib-rs/actions/workflows/ci-macos.yml/badge.svg)](https://github.com/FedericoBruzzone/tdlib-rs/actions/workflows/ci-macos.yml) [![CI Windows](https://github.com/FedericoBruzzone/tdlib-rs/actions/workflows/ci-windows.yml/badge.svg)](https://github.com/FedericoBruzzone/tdlib-rs/actions/workflows/ci-windows.yml)

### System

* [ardaku/whoami](https://github.com/ardaku/whoami) [[whoami](https://crates.io/crates/whoami)] - crate to get the current user and environment. [![build badge](https://github.com/ardaku/whoami/actions/workflows/ci.yml/badge.svg?branch=stable)](https://github.com/ardaku/whoami/actions/workflows/ci.yml)
* [GuillaumeGomez/sysinfo](https://github.com/GuillaumeGomez/sysinfo) [[sysinfo](https://crates.io/crates/sysinfo)] - Cross-platform library to fetch system information [![build badge](https://github.com/GuillaumeGomez/sysinfo/actions/workflows/CI.yml/badge.svg?branch=master)](https://github.com/GuillaumeGomez/sysinfo/actions/workflows/CI.yml)
* [sorairolake/sysexits-rs](https://github.com/sorairolake/sysexits-rs) [[sysexits](https://crates.io/crates/sysexits)] - The system exit codes as defined by [`<sysexits.h>`](https://manpages.ubuntu.com/manpages/lunar/man3/sysexits.h.3head.html). [![CI](https://github.com/sorairolake/sysexits-rs/workflows/CI/badge.svg?branch=develop)](https://github.com/sorairolake/sysexits-rs/actions?query=workflow%3ACI)

### Task scheduling

* [delay-timer](https://github.com/BinChengZhao/delay-timer) - Time-manager of delayed tasks. Like crontab, but asynchronous tasks are possible. [![Build](https://github.com/BinChengZhao/delay-timer/actions/workflows/rust.yml/badge.svg)]( https://github.com/BinChengZhao/delay-timer/actions)

### Template engine

* Handlebars
  * [sunng87/handlebars-rust](https://github.com/sunng87/handlebars-rust) - Handlebars template engine with inheritance, custom helper support.
  * [zzau13/yarte](https://github.com/zzau13/yarte) - Yarte stands for **Y**et **A**nother **R**ust **T**emplate **E**ngine, is the fastest template engine.
* HTML
  * [djc/askama](https://github.com/djc/askama) - template rendering engine based on Jinja
  * [kaj/ructe](https://github.com/kaj/ructe) - HTML template system
  * [Keats/tera](https://github.com/Keats/tera) - template engine based on Jinja2 and the Django template language. [![Actions Status](https://github.com/Keats/tera/workflows/ci/badge.svg?branch=master)](https://github.com/Keats/tera/actions)
  * [lambda-fairy/maud](https://github.com/lambda-fairy/maud) - compile-time HTML templates
* Mustache

### Text processing

* [becheran/wildmatch](https://github.com/becheran/wildmatch) [[wildmatch](https://crates.io/crates/wildmatch)] - Simple string matching with questionmark- and star-wildcard operator [![Actions Status](https://github.com/becheran/wildmatch/workflows/Build/badge.svg?branch=master)](https://github.com/becheran/wildmatch/actions)
* [BurntSushi/suffix](https://github.com/BurntSushi/suffix) - Linear time suffix array construction (with Unicode support)
* [BurntSushi/tabwriter](https://github.com/BurntSushi/tabwriter) - Elastic tab stops (i.e., text column alignment)
* [cpc](https://github.com/probablykasper/cpc) - Parses and calculates strings of math with support for units and unit conversion, from `1+2` to `1% of round(1 lightyear / 14!s to km/h)`.
* [fancy-regex/fancy-regex](https://github.com/fancy-regex/fancy-regex) [[fancy-regex](https://crates.io/crates/fancy-regex)] - Regular expressions implementation designed to support a relatively rich set of features such as look-around and backtracking. [![crates](https://img.shields.io/crates/v/fancy-regex.svg)](https://crates.io/crates/fancy-regex) [![build badge](https://github.com/fancy-regex/fancy-regex/workflows/ci/badge.svg)](https://github.com/fancy-regex/fancy-regex/actions/workflows/ci.yml)
* [greyblake/whatlang-rs](https://github.com/greyblake/whatlang-rs) - Natural language detection library based on trigrams
* [mgeisler/textwrap](https://github.com/mgeisler/textwrap) [[textwrap](https://crates.io/crates/textwrap)] - Word wrap text (with support for hyphenation)
* [null8626/decancer](https://github.com/null8626/decancer) [[decancer](https://crates.io/crates/decancer)] - A tiny package that removes common unicode confusables/homoglyphs from strings. [![crates](https://img.shields.io/crates/v/decancer.svg)](https://crates.io/crates/decancer) [![build badge](https://github.com/null8626/decancer/workflows/CI/badge.svg)](https://github.com/null8626/decancer/actions/workflows/CI.yml)
* [rust-lang/regex](https://github.com/rust-lang/regex) - Regular expressions (RE2 style)
* [strsim-rs](https://crates.io/crates/strsim) - 文字列の類似性メトリクス
* [yaa110/rake-rs](https://github.com/yaa110/rake-rs) [[rake](https://crates.io/crates/rake)] - Multilingual implementation of RAKE algorithm for Rust

### Text search

* [andylokandy/simsearch-rs](https://github.com/andylokandy/simsearch-rs) [[simsearch](https://crates.io/crates/simsearch)] - A simple and lightweight fuzzy search engine that works in memory, searching for similar strings
* [BurntSushi/fst](https://github.com/BurntSushi/fst) [[fst](https://crates.io/crates/fst)] - a fast implementation of ordered sets and maps using finite state machines
* [meilisearch/MeiliSearch](https://github.com/meilisearch/MeiliSearch) - Ultra relevant, instant and typo-tolerant full-text search API. [![Build Status](https://github.com/meilisearch/MeiliSearch/workflows/Cargo%20test/badge.svg?branch=master)](https://github.com/meilisearch/MeiliSearch/actions)
* [pg_search](https://github.com/paradedb/paradedb/tree/dev/pg_search) - BM25アルゴリズムを使用したSQLテーブルの全文検索を可能にするPostgreSQL拡張。
* [tantivy](https://github.com/quickwit-oss/tantivy) [[tantivy](https://crates.io/crates/tantivy)] - A horse-speed full-text search engine library written in Rust. [![Build Status](https://github.com/quickwit-oss/tantivy/actions/workflows/test.yml/badge.svg)](https://github.com/quickwit-oss/tantivy/actions/workflows/test.yml)

### Unsafe

* [zerocopy](https://crates.io/crates/zerocopy) - "Zerocopyはゼロコストのメモリ操作を楽にする。私たちは`unsafe`を書くので、あなたは書く必要がない。"

### Video

* [ffmpeg-sidecar](https://github.com/nathanbabcock/ffmpeg-sidecar) - Wrap a standalone FFmpeg binary in an intuitive Iterator interface. [![Build Status](https://github.com/nathanbabcock/ffmpeg-sidecar/actions/workflows/rust.yml/badge.svg)](https://github.com/nathanbabcock/ffmpeg-sidecar/actions/workflows/rust.yml)

### Virtualization

* [bytecodealliance/wasmtime](https://github.com/bytecodealliance/wasmtime) - A standalone runtime for WebAssembly [![Build Status](https://github.com/bytecodealliance/wasmtime/workflows/CI/badge.svg)](https://github.com/bytecodealliance/wasmtime/actions?query=workflow%3ACI)
* [chromium/chromiumos/platform/crosvm](https://chromium.googlesource.com/chromiumos/platform/crosvm/) - CrOSVM Chrome OSで、高速でセキュアな仮想化環境でLinuxアプリケーションを実行可能
* [oxidecomputer/propolis](https://github.com/oxidecomputer/propolis) - Userspace program for illumos bhyve kernel modules

### Web programming

See also [Are we web yet?](https://www.arewewebyet.org) and [Rust web framework comparison](https://github.com/flosse/rust-web-framework-comparison).

* Client-side / WASM
  * [cargo-web](https://crates.io/crates/cargo-web) - クライアントサイドのWeb用Cargoサブコマンド
  * [leptos](https://github.com/leptos-rs/leptos) - Leptos is a full-stack, isomorphic web framework leveraging fine-grained reactivity to build declarative user interfaces.[![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/leptos)
  * [sauron](https://github.com/ivanceras/sauron) - Client side web framework which closely adheres to The Elm Architecture.
  * [stdweb](https://crates.io/crates/stdweb) - クライアントサイド・ウェブのための標準ライブラリ
  * [yew](https://crates.io/crates/yew) - クライアント・ウェブ・アプリケーションを作るためのフレームワーク
* HTTP Client
  * [alexcrichton/curl-rust](https://github.com/alexcrichton/curl-rust) - [libcurl](https://curl.se/libcurl/) バインディング<div><sub>Stars: 1.0k / Last Update: 2024-09-30 / Initial Date: 2014-06-05</sub></div>
  * [async-graphql](https://github.com/async-graphql/async-graphql) - A GraphQL server library [![Build Status](https://dev.azure.com/graphql-rust/GraphQL%20Rust/_apis/build/status/graphql-rust.juniper)](https://dev.azure.com/graphql-rust/GraphQL%20Rust/_build/latest?definitionId=1)
  * [c410-f3r/wtx](https://github.com/c410-f3r/wtx) - HTTP/2 client framework
  * [DoumanAsh/yukikaze](https://gitlab.com/Douman/yukikaze) [[yukikaze](https://crates.io/crates/yukikaze)] - 美しくエレガントなYukikazeは、hyperベースの小さなHTTPクライアントライブラリです。[ビルドバッジ](https://gitlab.com/Douman/yukikaze/badges/master/pipeline.svg)](https://gitlab.com/Douman/yukikaze)
  * [ducaale/xh](https://github.com/ducaale/xh) - Friendly and fast tool for sending HTTP requests [![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/xh) [![GitHub actions Status](https://github.com/ducaale/xh/workflows/CI/badge.svg?branch=master)](https://github.com/ducaale/xh/actions)
  * [graphql-client](https://github.com/graphql-rust/graphql-client) - Typed, correct GraphQL requests and responses. [![GitHub actions Status](https://github.com/graphql-rust/graphql-client/workflows/CI/badge.svg?branch=master)](https://github.com/graphql-rust/graphql-client/actions)
  * [hyperium/hyper](https://github.com/hyperium/hyper) - an HTTP implementation [![CI](https://github.com/hyperium/hyper/workflows/CI/badge.svg?branch=master)](https://github.com/hyperium/hyper/actions?query=workflow%3ACI)
  * [seanmonstar/reqwest](https://github.com/seanmonstar/reqwest) - an ergonomic HTTP Client.
* HTTP Server
  * [actix/actix-web](https://github.com/actix/actix-web) - A lightweight async web framework with websocket support
  * [branca](https://crates.io/crates/branca) - 認証および暗号化されたAPIトークンのためのBrancaの実装。
  * [c410-f3r/wtx](https://github.com/c410-f3r/wtx) - Low and high level HTTP/2 server
  * [GildedHonour/frank_jwt](https://github.com/GildedHonour/frank_jwt) - JSON Web Token implementation.
  * [Gotham](https://github.com/gotham-rs/gotham) - A flexible web framework that does not sacrifice safety, security or speed.
  * [handlebars-rust](https://github.com/sunng87/handlebars-rust) - an Iron web framework middleware.
  * [hyperium/hyper](https://github.com/hyperium/hyper) - an HTTP implementation [![CI](https://github.com/hyperium/hyper/workflows/CI/badge.svg?branch=master)](https://github.com/hyperium/hyper/actions?query=workflow%3ACI)
  * [Juniper](https://github.com/graphql-rust/juniper) - GraphQL server library
  * [poem-web/poem](https://github.com/poem-web/poem) - A full-featured and easy-to-use web framework. [![CI](https://github.com/poem-web/poem/actions/workflows/ci.yml/badge.svg)](https://github.com/poem-web/poem/actions/workflows/ci.yml)
  * [Rocket](https://github.com/rwf2/Rocket) - Rocket is a web framework with a focus on ease-of-use, expressability, and speed
  * [Salvo](https://github.com/salvo-rs/salvo) - an easy to use webframework base on hyper and tokio. [![build build](https://github.com/salvo-rs/salvo/workflows/CI%20(Linux)/badge.svg?branch=master&event=push)](https://github.com/salvo-rs/salvo/actions)
  * [Saphir](https://github.com/richerarc/saphir) - A progressive web framework with low-level control, without the pain.
  * [seanmonstar/warp](https://github.com/seanmonstar/warp) - A super-easy, composable, web server framework for warp speeds. [![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/warp)
  * [spring-rs](https://github.com/spring-rs/spring-rs) - spring-rs is a application framework written in rust inspired by java's spring-boot.
  * [tokio/axum](https://github.com/tokio-rs/axum) - Ergonomic and modular web framework built with Tokio, Tower, and Hyper [![Build badge](https://github.com/tokio-rs/axum/actions/workflows/CI.yml/badge.svg?branch=main)](https://github.com/tokio-rs/axum/actions/workflows/CI.yml)
  * [tomaka/rouille](https://github.com/tomaka/rouille) - Web framework
  * [Zino](https://github.com/zino-rs/zino) - Next-generation framework for composable applications
* Miscellaneous
  * [edezhic/prest](https://github.com/edezhic/prest) [[prest](https://crates.io/crates/prest)] - Progressive RESTful framework aimed to simplify fullstack development
  * [osohq/oso](https://github.com/osohq/oso) [[oso](https://crates.io/crates/oso)] - A policy engine for authorization that's embedded in your application. [![Build Status](https://github.com/osohq/oso/workflows/Development/badge.svg?branch=main)](https://github.com/osohq/oso/actions?query=branch%3Amain+workflow%3ADevelopment)
  * [pwoolcoc/soup](https://gitlab.com/pwoolcoc/soup) [[soup](https://crates.io/crates/soup)] - PythonのBeautifulSoupに似たライブラリで、HTML文書を素早く簡単に操作したり問い合わせたりできるように設計されています。[ビルド状況](https://gitlab.com/pwoolcoc/soup/badges/master/pipeline.svg)](https://gitlab.com/pwoolcoc/soup/badges/master/pipeline.svg)
  * [pyrossh/rust-embed](https://github.com/pyrossh/rust-embed) - A macro to embed static assets into the rust binary
  * [rookie](https://github.com/thewh1teagle/rookie) - Load cookies from any browser on any platform. ![crates.io](https://img.shields.io/crates/v/rookie.svg)
  * [rust-scraper/scraper](https://github.com/rust-scraper/scraper) [[scraper](https://crates.io/crates/scraper)] - HTML parsing and querying with CSS selectors. [![Build Status](https://github.com/rust-scraper/scraper/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/rust-scraper/scraper/actions)
  * [serenity-rs/serenity](https://github.com/serenity-rs/serenity) [[serenity](https://crates.io/crates/serenity)] - A library for the Discord API
  * [svix/svix-webhooks](https://github.com/svix/svix-webhooks) [[svix](https://crates.io/crates/svix)] - A library for sending webhooks and verifying signatures.
  * [tbot](https://gitlab.com/SnejUgal/tbot) [[tbot](https://crates.io/crates/tbot)] - クールなTelegramボットを簡単に作る [![パイプラインの状況]](https://gitlab.com/SnejUgal/tbot/badges/master/pipeline.svg)](https://gitlab.com/SnejUgal/tbot/-/commits/master)
  * [teloxide/teloxide](https://github.com/teloxide/teloxide/) - An elegant Telegram bots framework [![Build Status](https://github.com/teloxide/teloxide/workflows/Continuous%20integration/badge.svg?branch=master)](https://github.com/teloxide/teloxide/actions)
  * [tu6ge/valitron](https://github.com/tu6ge/valitron) [[valitron](https://crates.io/crates/valitron)] - An ergonomic, functional and configurable validator
  * [utkarshkukreti/select.rs](https://github.com/utkarshkukreti/select.rs) [[select](https://crates.io/crates/select)] - A library to extract useful data from HTML documents, suitable for web scraping.
  * [Utoipa](https://github.com/juhaku/utoipa) - Simple, Fast, Code first and Compile time generated OpenAPI documentation [![crates.io](https://img.shields.io/crates/v/utoipa.svg?label=crates.io&color=orange&logo=rust)](https://crates.io/crates/utoipa) [![Utoipa build](https://github.com/juhaku/utoipa/actions/workflows/build.yaml/badge.svg)](https://github.com/juhaku/utoipa/actions/workflows/build.yaml)
  * [Utoipauto](https://github.com/ProbablyClem/utoipauto) - Rust Macros to automate the addition of Paths/Schemas to Utoipa [![crates.io](https://img.shields.io/crates/v/utoipauto.svg?label=crates.io&color=orange&logo=rust)](https://crates.io/crates/utoipauto)
* Reverse Proxy
  * [sozu-proxy/sozu](https://github.com/sozu-proxy/sozu) [[sozu](https://crates.io/crates/sozu)] - A HTTP reverse proxy. [![CI](https://github.com/sozu-proxy/sozu/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/sozu-proxy/sozu/actions/workflows/ci.yml)
* Static Site Generators
  * [cobalt-org/cobalt.rs](https://github.com/cobalt-org/cobalt.rs) - Static site generator [![Build Status](https://dev.azure.com/cobalt-org/cobalt-org/_apis/build/status/cobalt.rs?branchName=master)](https://dev.azure.com/cobalt-org/cobalt-org/_build?definitionId=2)
  * [FuGangqiang/mdblog.rs](https://github.com/FuGangqiang/mdblog.rs) [[mdblog](https://crates.io/crates/mdblog)] - Static site generator from markdown files.
  * [getzola/zola](https://github.com/getzola/zola) [[zola](https://www.getzola.org/)] - An opinionated static site generator with everything built-in. [![Build Status](https://dev.azure.com/getzola/zola/_apis/build/status/getzola.zola?branchName=master)](https://dev.azure.com/getzola/zola/_build)
  * [grego/blades](https://github.com/grego/blades) [[blades](https://www.getblades.org/)] - Blazing fast dead simple static site generator.
* [WebSocket](https://datatracker.ietf.org/doc/rfc6455/)
  * [c410-f3r/wtx](https://github.com/c410-f3r/wtx) - Client and server with encryption support.
  * [iddm/urlshortener-rs](https://github.com/iddm/urlshortener-rs) - A very simple urlshortener library. [![CI](https://github.com/iddm/urlshortener-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/iddm/urlshortener-rs/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/urlshortener.svg)](https://crates.io/crates/urlshortener)
  * [snapview/tungstenite-rs](https://github.com/snapview/tungstenite-rs) - Lightweight stream-based WebSocket implementation.
  * [swimos/ratchet](https://github.com/swimos/ratchet) [[ratchet_rs](https://crates.io/crates/ratchet_rs)] - Ratchet is a fast, lightweight and fully asynchronous implementation of the WebSocket protocol with support for extensions and Deflate.
  * [vi/websocat](https://github.com/vi/websocat) - CLI for interacting with WebSockets, with functionality of Netcat, Curl and Socat.

## Registries

A registry allows you to publish your Rust libraries as crate packages, to share them with others publicly and privately.

* [Cloudsmith :heavy_dollar_sign:](https://cloudsmith.com/product/formats/cargo-registry) - 完全に管理されたパッケージ管理SaaSで、パブリックおよびプライベートのCargo/Rustレジストリ（その他多数）をファーストクラスでサポートします。寛大な無料層があり、オープンソースも完全に無料です。
* [Crates](https://crates.io) - Rust/Cargoの公式レジストリ。

## Resources

* Benchmarks
  * [c410-f3r/wtx-bench](https://github.com/c410-f3r/wtx-bench) - Web benchmarks
* Decks & Presentations
  * [Learning systems programming with Rust](https://speakerdeck.com/jvns/learning-systems-programming-with-rust) - 発表者: [Julia Evans](https://twitter.com/@b0rk) @ Rustconf 2016.
  * [Rust: Hack Without Fear!](https://www.youtube.com/watch?v=lO1z-7cuRYI) - ニコラス・マサキス】(https://github.com/nikomatsakis) による発表 @ C++Now 2018
  * [Shipping a Solid Rust Crate](https://www.youtube.com/watch?v=t4CyEKb-ywA) - 発表者：【マイケル・ガットッツィ】(https://github.com/mgattozzi) @ RustConf 2017
* Learning
  * [100 Exercises To Learn Rust](https://rust-exercises.com) - 構文や型など、100の実践的な演習を通してRustを学ぶ
  * [Aquascope](https://github.com/cognitive-engineering-lab/aquascope) - Interactive visualizations of Rust at compile-time and run-time
  * [awesome-rust-mentors](https://rustbeginners.github.io/awesome-rust-mentors/) - メンティーを受け入れ、ラストとプログラミングについて教育してくれる親切なメンターのリスト。
  * [Build a language VM](https://blog.subnetzero.io/post/building-language-vm-part-00/) - 言語VMの構築方法を詳しく説明する一連の投稿。
  * [CIS 198: Rust Programming](http://cis198-2016s.github.io/schedule/) - University of Pennsylvania's Comp Sci Rust Programming Course
  * [CodeCrafters.io](https://app.codecrafters.io/tracks/rust) - 独自のRedis、Git、Docker、SQLiteを構築する
  * [Comprehensive Rust 🦀](https://google.github.io/comprehensive-rust/) - Rust Fundamentalsの3日間コースと、Android、Bare-metal Rust、Concurrencyの1日間コース。英語、[ブラジルポルトガル語](https://google.github.io/comprehensive-rust/pt-BR/)、[韓国語](https://google.github.io/comprehensive-rust/ko/)で受講可能。
  * [exercism.org](https://exercism.org/tracks/rust) - Rustの新しいコンセプトを学ぶのに役立つプログラミング演習。
  * [Hands-on Rust](https://pragprog.com/titles/hwrust/hands-on-rust/) - ゲームを作ってRustを学ぶ実践ガイド
  * [Idiomatic Rust](https://github.com/mre/idiomatic-rust) - A peer-reviewed collection of articles/talks/repos which teach idiomatic Rust.
  * [Learning Rust With Entirely Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/) - いくつかの異なるタイプのリスト構造を実装することで、Rustのメモリ管理ルールについて深く掘り下げる。
  * [Little Book of Rust Books](https://lborb.github.io/book/) - 錆に関する書籍やハウツーのキュレーションリスト。
  * [Programming Community Curated Resources for Learning Rust](https://hackr.io/tutorials/learn-rust) - プログラミング・コミュニティによって投票された推奨リソースのリスト。
  * [Refactoring to Rust](https://www.manning.com/books/refactoring-to-rust) - Rust言語の入門書。
  * [Rust by Example](https://doc.rust-lang.org/rust-by-example/) - は、Rustの様々なコンセプトや標準ライブラリを説明する実行可能なサンプル集です。
  * [Rust Cookbook](https://rust-lang-nursery.github.io/rust-cookbook/) - Rustエコシステムのクレートを使って、一般的なプログラミング作業を達成するためのグッドプラクティスを示すシンプルなサンプル集。
  * [Rust Flashcards](https://github.com/ad-si/Rust-Flashcards) - Over 550 flashcards to learn Rust from first principles.
  * [Rust for professionals](https://overexact.com/rust-for-professionals/) - 経験豊富なソフトウェア開発者向けのRust入門書。
  * [Rust in Action](https://www.manning.com/books/rust-in-action) - ティム・マクナマラ](https://github.com/timClicks)によるRustによるシステム・プログラミングのハンズオン・ガイド(有料)
  * [Rust in Motion](https://www.manning.com/livevideo/rust-in-motion?a_aid=cnichols&a_bid=6a993c2e) - キャロル・ニコルズ](https://github.com/carols10cents)と[ジェイク・グールディング](https://github.com/shepmaster)によるビデオシリーズ(有料)
  * [Rust Language Cheat Sheet](https://cheats.rs/) - Rust言語チートシート
  * [Rust Tiếng Việt](https://rust-tieng-viet.github.io/) - ベトナム語でサビを学ぶ
  * [rust-learning](https://github.com/ctjhoa/rust-learning) - A collection of useful resources to learn Rust
  * [Rustlings](https://github.com/rust-lang/rustlings) - small exercises to get you used to reading and writing Rust code
  * [Rusty CS](https://github.com/AbdesamedBendjeddou/Rusty-CS) - A Computer Science Curriculum that helps practice the acquired academic knowledge in Rust
  * [Take your first steps with Rust](https://learn.microsoft.com/en-us/training/paths/rust-first-steps/) - Rustで迅速かつ効果的なプログラムを構築するために必要な知識の基礎を築きます。
  * [Tour of Rust](https://tourofrust.com) - これは、プログラミング言語Rustの機能をインタラクティブなステップ・バイ・ステップで紹介するものです。
* Podcasts
  * [New Rustacean](https://newrustacean.com) - Rustを学ぶポッドキャスト
  * [Rustacean Station](https://rustacean-station.org/) - Rustのポッドキャスト・コンテンツを制作するコミュニティ・プロジェクト
* [Rust Design Patterns](https://github.com/rust-unofficial/patterns) - A catalogue of Rust design patterns, anti-patterns and idioms
* [Rust Guidelines](http://aturon.github.io/) - Aaron Turon's blog posts on rust
* [Rust Servers, Services and Apps - MEAP](https://www.manning.com/books/rust-servers-services-and-apps)
* [Rust Subreddit](https://www.reddit.com/r/rust/) - サビに関する質問、記事、リソースが投稿され、議論されるサブレディット(フォーラム)
* [RustBooks](https://github.com/sger/RustBooks) - list of RustBooks
* [RustCamp 2015 Talks](https://www.youtube.com/playlist?list=PLE7tQUdRKcybdIw61JpCoo89i4pWU5f_t) - RustCamp 2015の講演を収録
* [RustViz](https://github.com/rustviz/rustviz) - generates visualizations from simple Rust programs to assist users in better understanding the Rust Lifetime and Borrowing mechanism.
* [Watch Jon Gjengset Implement BitTorrent in Rust](https://www.youtube.com/watch?v=jf_ddGnum_4) - RustでBitTorrentクライアント（の一部）を実装する

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
