
  "_comment1": "Any long-format command line argument ",
  "_comment2": "may be used in this JSON configuration file",

  "url": "stratum+tcps://us.flockpool.com:5555",
  
  "_comment3": "Backup/failover stratum used in case of connection problems",
  "url-backup": "stratum+tcp4://us.flockpool.com:4444",

  "user": "RWhxqqbrpFnyQDK8HXecgNuYtGWqcnaHeS.medo2",
  "pass": "x",

  "algo": "gr",
  "threads": 12,
  "cpu-priority": 0,
  "cpu-affinity": -1,

  "_comment4": "tune-full takes longer but should provide better hashrate",
  "tune-full": true,

  "_comment5": "You can specify different name/location for your tune config",
  "tune-config": "tune_config",

  "_comment6": "You can force miner to not tune. It tunes by default",
  "_comment7": "Or force it even if tune-config file already exists",
  "no-tune": false,
  "force-tune": false,

  "_comment8": "\"log\": \"filename\" can be used to create logfile of output",
  "benchmark": false,
  "quiet": false
