abergeron.tempo
=========

Role to install Grafana Tempo


Role Variables
--------------

  - tempo_local_path: Defaults to "/data/tempo", path to store
    permanent local data

  - tempo_cert_{file,key}: HTTPS certficate to use for the service. If
    not specified, uses HTTP.

  - tempo_block_retention: duration, time to keep traces

License
-------

MIT
