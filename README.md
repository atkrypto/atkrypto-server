# Environment variables

**ATKRYPTO_ATKEYS_PATH** - Path to atKey file. **Required**

**ATKRYPTO_ATSIGN** - Default atSign name. If not provided will be inferred from keys file

**ATKRYTO_PERSISTENCE_TYPE** - Type of the persistence (default: sqlite)

**ATKRYPTO_SQLITE_DB_PATH** - Path to the SQLite database file (default: data/atkrypto.sqlite)

**ATKRYPTO_ATCLIENT_STORAGE_PATH** - Path to folder where atClient Hive DB is stored (default: data)

**ATKRYPTO_RETRY_BLOCK** - Whether retry blocks that weren't added to the blockchain (default: true)

**ATKRYPTO_BLOCK_RETRIES** - How many attempts should be made to add block to the blockchain. Applies only if `ATKRYPTO_RETRY_BLOCKS` is `true` (default: 3)
