# Factom tooling (SDKs, libraries)

Information about tools available to work with Factom blockchain, and 2nd layer projects (FAT, PegNet, etc)

## Factom API client libraries

| # | Language | Developer        |State | Repository | Version | License | Coverage |
|---|----------|------------------|------|------------|---------|---------|----------|
| 1 | Go       | Factom, Inc      |Ref | | | | |
| 2 | Java     | BIF              |Prod | [factom-java](https://github.com/bi-foundation/factom-java)| 0.2.1|![GitHub](https://img.shields.io/github/license/bi-foundation/factom-java) | Unknown
| 3 | C#       | Factoid Authority|Prod |[FactomSharp](https://github.com/FactoidAuthority/FactomSharp) | ![Nuget](https://img.shields.io/nuget/v/FactomSharp) | [![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/kompendium-ano/factom-php/blob/master/LICENSE)| Unknown
| 4 | Php      | Kompendium       |Prod | [![Build Status](https://travis-ci.com/kompendium-ano/factom-php-client.svg?branch=master)](https://travis-ci.com/kompendium-ano/factom-php-client)| ![Packagist Version](https://img.shields.io/packagist/v/kompendium-ano/factom-php-client)| [![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/kompendium-ano/factom-php/blob/master/LICENSE)| [![Coverage Status](https://camo.githubusercontent.com/45094f7a0289badb21060cd3c127f3bbced18180/68747470733a2f2f636f766572616c6c732e696f2f7265706f732f7a656e646672616d65776f726b2f7a656e642d636f64652f62616467652e7376673f6272616e63683d6d6173746572)](https://coveralls.io/github/kompendium-ano/factom-ruby-client?branch=master)|
| 5 | Ruby     | Kompendium       |Prod | [![Build Status](https://travis-ci.com/kompendium-ano/factom-ruby-client.svg?branch=master)](https://travis-ci.com/kompendium-ano/factom-ruby-client)| [![Gem](https://img.shields.io/gem/v/factom-rb.svg?style=flat)](http://rubygems.org/gems/factom-rb "View this project in Rubygems") |[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/kompendium-ano/factom-php/blob/master/LICENSE) |[![Coverage Status](https://camo.githubusercontent.com/e952701cdf1177e284bbc22087860757252ebb6f/68747470733a2f2f636f766572616c6c732e696f2f7265706f732f7a656e646672616d65776f726b2f7a656e642d636f6e6669672f62616467652e7376673f6272616e63683d646576656c6f70)](https://coveralls.io/github/kompendium-ano/factom-ruby-client?branch=master) |
| 6 | Rust     | Kompendium       | Prod | [![Build Status](https://travis-ci.com/kompendium-ano/factom-rust-client.svg?branch=master)](https://travis-ci.com/kompendium-ano/factom-rust-client)| [![Crates.io](https://img.shields.io/crates/v/factom.svg)](https://crates.io/crates/factom) |[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/kompendium-ano/factom-php/blob/master/LICENSE) | Unknown |
| 7 | Rust-Ng  | Kompendium       | WIP | [![Build Status](https://travis-ci.com/kompendium-ano/factom-rust-client-ng.svg?branch=master)](https://travis-ci.com/kompendium-ano/factom-rust-client-ng)| [![Crates.io](https://img.shields.io/crates/v/factom-api.svg)](https://crates.io/crates/factom-api) |[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/kompendium-ano/factom-php/blob/master/LICENSE) | Unknown |
| 8 | Swift    | Kompendium       | Prod | [![Build Status](https://travis-ci.com/kompendium-ano/factom-swift-client.svg?branch=master)](https://travis-ci.com/kompendium-ano/factom-swift-client)| ![Cocoapods](https://img.shields.io/cocoapods/v/SearchEmojiOnString)|[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/kompendium-ano/factom-php/blob/master/LICENSE) | [![Coverage Status](https://camo.githubusercontent.com/275ed9ffa38cbe3b7080582a63b11457161071ec/68747470733a2f2f636f766572616c6c732e696f2f7265706f732f6769746875622f6464696d617269612f6b6f612d747970657363726970742d737461727465722f62616467652e7376673f6272616e63683d646576656c6f70)](https://coveralls.io/github/kompendium-ano/factom-ruby-client?branch=master)|
| 9 | Haskell  | Kompendium       | Prod | [![Build Status](https://travis-ci.com/kompendium-ano/factom-haskell-client.svg?branch=master)](https://travis-ci.com/kompendium-ano/factom-haskell-client)| ![Hackage](https://img.shields.io/hackage/v/api-rpc-factom)|[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/kompendium-ano/factom-php/blob/master/LICENSE) | [![Coverage Status](https://camo.githubusercontent.com/97fc12d3a3ca2613e37adcdc75afbb7e760acc10/687474703a2f2f696d672e736869656c64732e696f2f636f766572616c6c732f74726175746f6e656e2f636f766572616c6c732d6d6176656e2d706c7567696e2f6d61737465722e737667)](https://coveralls.io/github/kompendium-ano/factom-haskell-client?branch=master) |
| 10 | OCaml    | Kompendium       | WIP | [![Build Status](https://travis-ci.com/kompendium-ano/factom-swift-client.svg?branch=master)](https://travis-ci.com/kompendium-ano/factom-swift-client)| 0.4 |[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/kompendium-ano/factom-php/blob/master/LICENSE) | Unknown

## PegNet API client libraries

| # | Language | Developer        |State       | Repository | Version | License | Coverage |
----|----------|------------------|------------|------------|---------|---------|----------|
| 1 | Go       | PegNet community |Ref   | | | | |
| 2 | Rust     | Kompendium       |Prod | [![Build Status](https://travis-ci.com/kompendium-ano/factom-rust-client.svg?branch=master)](https://travis-ci.com/kompendium-ano/factom-rust-client)|[![Crates.io](https://img.shields.io/crates/v/pegnetd.svg)](https://crates.io/crates/pegnetd) | [![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/kompendium-ano/factom-php/blob/master/LICENSE) | Unknown
| 3 | Haskell  | Kompendium       |Prod | [![Build Status](https://travis-ci.com/kompendium-ano/factom-haskell-client.svg?branch=master)](https://travis-ci.com/kompendium-ano/pegnet-haskell-client)| 0.9 | [![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/kompendium-ano/factom-php/blob/master/LICENSE) | Unknown
| 4 | OCaml    | Kompendium       | WIP | [![Build Status](https://travis-ci.com/kompendium-ano/factom-swift-client.svg?branch=master)](https://travis-ci.com/kompendium-ano/factom-swift-client)| 0.2 |[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/kompendium-ano/factom-php/blob/master/LICENSE) | Unknown

## FAT API client libraries

| # | Language  | Developer        |State       | Repository | Version | License | Coverage |
----|-----------|------------------|------------|------------|---------|---------|----------|
| 1 | JavaScript| DBGrow           |Prod | [fat-js](https://github.com/Factom-Asset-Tokens/fat-js/) | 1.3.0 | | |
| 2 | Python    | Canonical Ledgers|Prod| [fat-py](https://github.com/samuelvanderwaal/fat-py/)     | 0.1.2 | | |
| 3 | Rust      | Kompendium       |Prod | [![Build Status](https://travis-ci.com/kompendium-ano/fat-rust.svg?branch=master)](https://travis-ci.com/kompendium-ano/fat-rust)|0.1 | [![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/kompendium-ano/factom-php/blob/master/LICENSE) | Unknown
| 4 | Haskell   | Kompendium       |Prod | [![Build Status](https://travis-ci.com/kompendium-ano/fat-haskell.svg?branch=master)](https://travis-ci.com/kompendium-ano/fat-haskell)| 0.1 | [![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/kompendium-ano/factom-php/blob/master/LICENSE) | Unknown

## DiDs

| # | Language  | Developer        |State       | Repository | Version | License | Coverage |
----|-----------|------------------|------------|------------|---------|---------|----------|
| 1 | Python    | Factomatic       | REF        | [py-factom-did](https://github.com/factomatic/py-factom-did) | | | |
| 2 | Go        | De Facto         | Prod       | [go-factom-did](https://github.com/DeFacto-Team/go-factom-did) | 0.5.0a | MIT | |
| 3 | Haskell   | Kompendium       | WIP        | [factom-did-haskell](https://github.com/kompendium-ano/factom-did-haskell) | 0.4 | MIT | |
| 4 | Haskell   | Kompendium       | WIP        | [factom-did-rust](https://github.com/kompendium-ano/factom-did-rust) | 0.4 | MIT | |


## VCs

| #  | Language  | Developer        |State       | Repository | Version | License | Coverage |
|----|-----------|------------------|------------|------------|---------|---------|----------|
| 1  | Rust      | Kompendium       | REF, WIP   | [factom-vc-rust](https://github.com/kompendium-ano/factom-vc-rust)| 0.1 | MIT | |
| 1  | Haskell   | Kompendium       | WIP        | [factom-vc-haskell](https://github.com/kompendium-ano/factom-vc-haskell) | 0.1 | MIT | |

## Learning resources

- [Accessing the Factom blockchain from different programming languages](https://medium.com/kompendium-developments/accessing-factom-blockchain-from-different-programming-languages-7f09030efe16)
- [Building simple blockchain game with Factom](https://medium.com/kompendium-developments/accessing-factom-blockchain-from-different-programming-languages-7f09030efe16)
