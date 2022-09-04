# 0.1.1 (Dec 27, 2020)

* Update tox to 0.1.1 (#71)
* Fix bug in lan discovery usage (#70)

# 0.1.0 (Oct 7, 2020)

* Update tox to 0.1.0 (#68)

# 0.0.8 (May 27, 2019)

* Add Dockerfile (#57, #62, #63)
* We are in nixpkgs (#55)
* Add subcommand derive-pk (#51)
* Build Debian package (#50)

# 0.0.7 (January 27, 2019)

* Update dependencies (#47)
* Add unit tests for cli args parsing (#46)
* Do not require tcp-address arg (#45)
* Move to Edition 2018 (#44)
* Add limits for TCP connections count (#43)
* Remove custom deserializer for log type (#42)

# 0.0.6 (December 27, 2018)

* Fix clippy warnings (#40)
* Pretty fixes (examples, readme) (#39)
* Add subcommand config (#37)
* Use DHT ServerExt (#38)
* Use bounded streams (#36)
* Migrate to sodiumoxide 0.2 (#35)
* Add counters to motd (#35)
* Ignore bootstrap nodes with invalid address (#34)
* Do not override log level (#32)

# 0.0.5 (October 27, 2018)

* Update tox core version (#30)
* Add possibility to specify the secret key via environment variable (#29)
* Add feature for MOTD templates (#28)
* Fix deprecated item 'tokio::executor::thread_pool' (#27)
* Handle onion errors (#26)
* Use tox from github (#24)
* Validate loaded public key (#23)

# 0.0.4 (September 11, 2018)

* Use tox from crates.io (#22)

# 0.0.3 (September 7, 2018)

* download libsodium v1.0.16 (#20)
* Write logs to syslog (#19)
* Add tcp ping sender (#18)
* Use add_initial_bootstrap (#17)
* Run clippy on travis (#16)
* Enable udp ipv6 (#15)
* Update toxcore; fix nodes adding (#14)
* Use secret from arg or key file (#13)
* Make TCP and UDP servers optional (#12)
* Add CI files (#11)
* Add TCP relay (#9)
* Add options to enable/disable LAN discovery (#8)
* Dehardcode several values (#7)
* Save DHT keys to a binary file (#6)
* Update Cargo.toml to improve the package (#5)
* Add multithreading(#4)
* Typo fix (#3)
* DHT server initial implementation (#2)
* Relicense to MIT (#1)
