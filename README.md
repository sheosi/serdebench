# Results as of 2021-7-11

```
Benchmarking all/sr.json
Benchmarking all/sr.json: Warming up for 3.0000 s
Benchmarking all/sr.json: Collecting 100 samples in estimated 5.0004 s (38M iterations)
Benchmarking all/sr.json: Analyzing
all/sr.json             time:   [130.22 ns 130.38 ns 130.55 ns]
                        change: [-0.7192% -0.4933% -0.2894%] (p = 0.00 < 0.05)
                        Change within noise threshold.
Found 7 outliers among 100 measurements (7.00%)
  6 (6.00%) high mild
  1 (1.00%) high severe
json: 100 bytes
Benchmarking all/de.json
Benchmarking all/de.json: Warming up for 3.0000 s
Benchmarking all/de.json: Collecting 100 samples in estimated 5.0010 s (13M iterations)
Benchmarking all/de.json: Analyzing
all/de.json             time:   [383.44 ns 383.81 ns 384.31 ns]
                        change: [-0.9309% -0.5762% -0.2456%] (p = 0.00 < 0.05)
                        Change within noise threshold.
Found 22 outliers among 100 measurements (22.00%)
  4 (4.00%) low mild
  5 (5.00%) high mild
  13 (13.00%) high severe
Benchmarking all/sr.simd-json
Benchmarking all/sr.simd-json: Warming up for 3.0000 s
Benchmarking all/sr.simd-json: Collecting 100 samples in estimated 5.0000 s (125M iterations)
Benchmarking all/sr.simd-json: Analyzing
all/sr.simd-json        time:   [39.923 ns 40.006 ns 40.097 ns]
                        change: [-0.5120% -0.0854% +0.3327%] (p = 0.69 > 0.05)
                        No change in performance detected.
Found 2 outliers among 100 measurements (2.00%)
  2 (2.00%) high mild
simd-json: 100 bytes
Benchmarking all/de.simd-json
Benchmarking all/de.simd-json: Warming up for 3.0000 s
Benchmarking all/de.simd-json: Collecting 100 samples in estimated 5.0011 s (12M iterations)
Benchmarking all/de.simd-json: Analyzing
all/de.simd-json        time:   [426.10 ns 426.37 ns 426.67 ns]
                        change: [-4.6677% -4.4375% -4.2331%] (p = 0.00 < 0.05)
                        Performance has improved.
Found 8 outliers among 100 measurements (8.00%)
  6 (6.00%) high mild
  2 (2.00%) high severe
simd-json: 100 bytes
Benchmarking all/sr.yaml
Benchmarking all/sr.yaml: Warming up for 3.0000 s
Benchmarking all/sr.yaml: Collecting 100 samples in estimated 5.0044 s (2.1M iterations)
Benchmarking all/sr.yaml: Analyzing
all/sr.yaml             time:   [2.3566 us 2.3580 us 2.3597 us]
                        change: [-0.9380% -0.6461% -0.4011%] (p = 0.00 < 0.05)
                        Change within noise threshold.
Found 10 outliers among 100 measurements (10.00%)
  7 (7.00%) high mild
  3 (3.00%) high severe
yaml: 99 bytes
Benchmarking all/de.yaml
Benchmarking all/de.yaml: Warming up for 3.0000 s
Benchmarking all/de.yaml: Collecting 100 samples in estimated 5.0017 s (874k iterations)
Benchmarking all/de.yaml: Analyzing
all/de.yaml             time:   [5.7123 us 5.7166 us 5.7218 us]
                        change: [-5.1276% -4.8735% -4.6503%] (p = 0.00 < 0.05)
                        Performance has improved.
Found 12 outliers among 100 measurements (12.00%)
  7 (7.00%) high mild
  5 (5.00%) high severe
Benchmarking all/sr.ron
Benchmarking all/sr.ron: Warming up for 3.0000 s
Benchmarking all/sr.ron: Collecting 100 samples in estimated 5.0004 s (9.9M iterations)
Benchmarking all/sr.ron: Analyzing
all/sr.ron              time:   [501.55 ns 502.22 ns 503.01 ns]
                        change: [-6.0073% -4.4559% -3.3882%] (p = 0.00 < 0.05)
                        Performance has improved.
Found 10 outliers among 100 measurements (10.00%)
  6 (6.00%) high mild
  4 (4.00%) high severe
ron: 91 bytes
Benchmarking all/de.ron
Benchmarking all/de.ron: Warming up for 3.0000 s
Benchmarking all/de.ron: Collecting 100 samples in estimated 5.0032 s (6.4M iterations)
Benchmarking all/de.ron: Analyzing
all/de.ron              time:   [776.74 ns 777.21 ns 777.69 ns]
                        change: [-0.4972% -0.2763% -0.0382%] (p = 0.02 < 0.05)
                        Change within noise threshold.
Found 10 outliers among 100 measurements (10.00%)
  1 (1.00%) low mild
  5 (5.00%) high mild
  4 (4.00%) high severe
Benchmarking all/sr.bincode
Benchmarking all/sr.bincode: Warming up for 3.0000 s
Benchmarking all/sr.bincode: Collecting 100 samples in estimated 5.0001 s (289M iterations)
Benchmarking all/sr.bincode: Analyzing
all/sr.bincode          time:   [17.289 ns 17.311 ns 17.339 ns]
                        change: [-0.5465% -0.2533% +0.0225%] (p = 0.08 > 0.05)
                        No change in performance detected.
Found 13 outliers among 100 measurements (13.00%)
  1 (1.00%) low mild
  5 (5.00%) high mild
  7 (7.00%) high severe
bincode: 58 bytes
Benchmarking all/de.bincode
Benchmarking all/de.bincode: Warming up for 3.0000 s
Benchmarking all/de.bincode: Collecting 100 samples in estimated 5.0002 s (61M iterations)
Benchmarking all/de.bincode: Analyzing
all/de.bincode          time:   [81.793 ns 81.837 ns 81.884 ns]
                        change: [-1.2450% -1.0400% -0.8597%] (p = 0.00 < 0.05)
                        Change within noise threshold.
Found 8 outliers among 100 measurements (8.00%)
  4 (4.00%) high mild
  4 (4.00%) high severe
Benchmarking all/sr.msgpack
Benchmarking all/sr.msgpack: Warming up for 3.0000 s
Benchmarking all/sr.msgpack: Collecting 100 samples in estimated 5.0002 s (90M iterations)
Benchmarking all/sr.msgpack: Analyzing
all/sr.msgpack          time:   [55.673 ns 55.717 ns 55.766 ns]
                        change: [-14.624% -14.368% -14.114%] (p = 0.00 < 0.05)
                        Performance has improved.
Found 12 outliers among 100 measurements (12.00%)
  9 (9.00%) high mild
  3 (3.00%) high severe
msgpack: 24 bytes
Benchmarking all/de.msgpack
Benchmarking all/de.msgpack: Warming up for 3.0000 s
Benchmarking all/de.msgpack: Collecting 100 samples in estimated 5.0003 s (37M iterations)
Benchmarking all/de.msgpack: Analyzing
all/de.msgpack          time:   [136.10 ns 136.31 ns 136.58 ns]
                        change: [-1.2135% -0.9537% -0.6849%] (p = 0.00 < 0.05)
                        Change within noise threshold.
Found 11 outliers among 100 measurements (11.00%)
  1 (1.00%) high mild
  10 (10.00%) high severe
Benchmarking all/sr.cbor.minicbor
Benchmarking all/sr.cbor.minicbor: Warming up for 3.0000 s
Benchmarking all/sr.cbor.minicbor: Collecting 100 samples in estimated 5.0000 s (101M iterations)
Benchmarking all/sr.cbor.minicbor: Analyzing
all/sr.cbor.minicbor    time:   [49.096 ns 49.150 ns 49.214 ns]
                        change: [-0.1834% +0.0637% +0.3206%] (p = 0.62 > 0.05)
                        No change in performance detected.
Found 7 outliers among 100 measurements (7.00%)
  5 (5.00%) high mild
  2 (2.00%) high severe
cbor.minicbor: 26 bytes
Benchmarking all/de.cbor.minicbor
Benchmarking all/de.cbor.minicbor: Warming up for 3.0000 s
Benchmarking all/de.cbor.minicbor: Collecting 100 samples in estimated 5.0004 s (34M iterations)
Benchmarking all/de.cbor.minicbor: Analyzing
all/de.cbor.minicbor    time:   [144.41 ns 144.62 ns 144.79 ns]
                        change: [-7.3715% -7.1436% -6.9475%] (p = 0.00 < 0.05)
                        Performance has improved.
Found 9 outliers among 100 measurements (9.00%)
  1 (1.00%) low severe
  5 (5.00%) high mild
  3 (3.00%) high severe
Benchmarking all/sr.cbor.ciborium
Benchmarking all/sr.cbor.ciborium: Warming up for 3.0000 s
Benchmarking all/sr.cbor.ciborium: Collecting 100 samples in estimated 5.0003 s (30M iterations)
Benchmarking all/sr.cbor.ciborium: Analyzing
all/sr.cbor.ciborium    time:   [164.93 ns 165.05 ns 165.21 ns]
                        change: [-0.6675% -0.4661% -0.2781%] (p = 0.00 < 0.05)
                        Change within noise threshold.
Found 9 outliers among 100 measurements (9.00%)
  1 (1.00%) low mild
  6 (6.00%) high mild
  2 (2.00%) high severe
cbor.ciborium: 72 bytes
Benchmarking all/de.cbor.ciborium
Benchmarking all/de.cbor.ciborium: Warming up for 3.0000 s
Benchmarking all/de.cbor.ciborium: Collecting 100 samples in estimated 5.0019 s (6.7M iterations)
Benchmarking all/de.cbor.ciborium: Analyzing
all/de.cbor.ciborium    time:   [740.39 ns 740.71 ns 741.08 ns]
                        change: [-1.0216% -0.7646% -0.5290%] (p = 0.00 < 0.05)
                        Change within noise threshold.
Found 9 outliers among 100 measurements (9.00%)
  6 (6.00%) high mild
  3 (3.00%) high severe
Benchmarking all/sr.postcard
Benchmarking all/sr.postcard: Warming up for 3.0000 s
Benchmarking all/sr.postcard: Collecting 100 samples in estimated 5.0002 s (97M iterations)
Benchmarking all/sr.postcard: Analyzing
all/sr.postcard         time:   [51.258 ns 51.382 ns 51.520 ns]
                        change: [-0.4203% +0.0001% +0.5582%] (p = 1.00 > 0.05)
                        No change in performance detected.
Found 11 outliers among 100 measurements (11.00%)
  2 (2.00%) high mild
  9 (9.00%) high severe
postcard: 41 bytes
Benchmarking all/de.postcard
Benchmarking all/de.postcard: Warming up for 3.0000 s
Benchmarking all/de.postcard: Collecting 100 samples in estimated 5.0003 s (37M iterations)
Benchmarking all/de.postcard: Analyzing
all/de.postcard         time:   [134.20 ns 134.31 ns 134.46 ns]
                        change: [-0.8922% -0.5845% -0.3039%] (p = 0.00 < 0.05)
                        Change within noise threshold.
Found 7 outliers among 100 measurements (7.00%)
  1 (1.00%) low mild
  2 (2.00%) high mild
  4 (4.00%) high severe
Benchmarking all/ser.flexbuffers
Benchmarking all/ser.flexbuffers: Warming up for 3.0000 s
Benchmarking all/ser.flexbuffers: Collecting 100 samples in estimated 5.0035 s (4.0M iterations)
Benchmarking all/ser.flexbuffers: Analyzing
all/ser.flexbuffers     time:   [1.2542 us 1.2561 us 1.2584 us]
                        change: [-1.1448% -0.8134% -0.4717%] (p = 0.00 < 0.05)
                        Change within noise threshold.
Found 7 outliers among 100 measurements (7.00%)
  2 (2.00%) high mild
  5 (5.00%) high severe
flexbuffers: 41 bytes
Benchmarking all/de.flexbuffers
Benchmarking all/de.flexbuffers: Warming up for 3.0000 s
Benchmarking all/de.flexbuffers: Collecting 100 samples in estimated 5.0015 s (7.2M iterations)
Benchmarking all/de.flexbuffers: Analyzing
all/de.flexbuffers      time:   [697.74 ns 698.16 ns 698.74 ns]
                        change: [-0.0272% +0.1852% +0.3981%] (p = 0.09 > 0.05)
                        No change in performance detected.
Found 9 outliers among 100 measurements (9.00%)
  3 (3.00%) high mild
  6 (6.00%) high severe
Benchmarking all/sr.flatbuffers
Benchmarking all/sr.flatbuffers: Warming up for 3.0000 s
Benchmarking all/sr.flatbuffers: Collecting 100 samples in estimated 5.0001 s (35M iterations)
Benchmarking all/sr.flatbuffers: Analyzing
all/sr.flatbuffers      time:   [141.50 ns 141.73 ns 142.02 ns]
                        change: [-0.7448% -0.3659% -0.0719%] (p = 0.03 < 0.05)
                        Change within noise threshold.
Found 7 outliers among 100 measurements (7.00%)
  3 (3.00%) high mild
  4 (4.00%) high severe
flatbuffers: 104 bytes
Benchmarking all/de.flatbuffers
Benchmarking all/de.flatbuffers: Warming up for 3.0000 s
Benchmarking all/de.flatbuffers: Collecting 100 samples in estimated 5.0004 s (63M iterations)
Benchmarking all/de.flatbuffers: Analyzing
all/de.flatbuffers      time:   [78.893 ns 78.939 ns 78.996 ns]
                        change: [-3.0954% -2.8457% -2.5919%] (p = 0.00 < 0.05)
                        Performance has improved.
Found 3 outliers among 100 measurements (3.00%)
  1 (1.00%) low mild
  1 (1.00%) high mild
  1 (1.00%) high severe
Benchmarking all/sr.capnproto.unpacked
Benchmarking all/sr.capnproto.unpacked: Warming up for 3.0000 s
Benchmarking all/sr.capnproto.unpacked: Collecting 100 samples in estimated 5.0003 s (33M iterations)
Benchmarking all/sr.capnproto.unpacked: Analyzing
all/sr.capnproto.unpacked
                        time:   [150.18 ns 150.30 ns 150.43 ns]
                        change: [-0.5706% -0.3041% -0.0731%] (p = 0.01 < 0.05)
                        Change within noise threshold.
Found 8 outliers among 100 measurements (8.00%)
  4 (4.00%) high mild
  4 (4.00%) high severe
capnproto.unpacked: 96 bytes
Benchmarking all/de.capnproto.unpacked
Benchmarking all/de.capnproto.unpacked: Warming up for 3.0000 s
Benchmarking all/de.capnproto.unpacked: Collecting 100 samples in estimated 5.0003 s (18M iterations)
Benchmarking all/de.capnproto.unpacked: Analyzing
all/de.capnproto.unpacked
                        time:   [275.03 ns 275.19 ns 275.39 ns]
                        change: [-2.1692% -1.5892% -1.1546%] (p = 0.00 < 0.05)
                        Performance has improved.
Found 12 outliers among 100 measurements (12.00%)
  7 (7.00%) high mild
  5 (5.00%) high severe
Benchmarking all/sr.capnproto.packed
Benchmarking all/sr.capnproto.packed: Warming up for 3.0000 s
Benchmarking all/sr.capnproto.packed: Collecting 100 samples in estimated 5.0007 s (21M iterations)
Benchmarking all/sr.capnproto.packed: Analyzing
all/sr.capnproto.packed time:   [239.02 ns 239.14 ns 239.30 ns]
                        change: [-0.9203% -0.7034% -0.4985%] (p = 0.00 < 0.05)
                        Change within noise threshold.
Found 7 outliers among 100 measurements (7.00%)
  4 (4.00%) high mild
  3 (3.00%) high severe
capnproto.packed: 39 bytes
Benchmarking all/de.capnproto.packed
Benchmarking all/de.capnproto.packed: Warming up for 3.0000 s
Benchmarking all/de.capnproto.packed: Collecting 100 samples in estimated 5.0015 s (13M iterations)
Benchmarking all/de.capnproto.packed: Analyzing
all/de.capnproto.packed time:   [399.55 ns 399.94 ns 400.36 ns]
                        change: [+0.2280% +0.5115% +0.7810%] (p = 0.00 < 0.05)
                        Change within noise threshold.
Found 6 outliers among 100 measurements (6.00%)
  4 (4.00%) high mild
  2 (2.00%) high severe
Benchmarking all/sr.proto3
Benchmarking all/sr.proto3: Warming up for 3.0000 s
Benchmarking all/sr.proto3: Collecting 100 samples in estimated 5.0005 s (36M iterations)
Benchmarking all/sr.proto3: Analyzing
all/sr.proto3           time:   [138.80 ns 138.89 ns 139.00 ns]
                        change: [-0.4225% -0.2246% -0.0522%] (p = 0.02 < 0.05)
                        Change within noise threshold.
Found 6 outliers among 100 measurements (6.00%)
  2 (2.00%) high mild
  4 (4.00%) high severe
proto3: 23 bytes
Benchmarking all/de.proto3
Benchmarking all/de.proto3: Warming up for 3.0000 s
Benchmarking all/de.proto3: Collecting 100 samples in estimated 5.0005 s (36M iterations)
Benchmarking all/de.proto3: Analyzing
all/de.proto3           time:   [138.87 ns 138.97 ns 139.09 ns]
                        change: [-1.1099% -0.5750% -0.1904%] (p = 0.01 < 0.05)
                        Change within noise threshold.
Found 6 outliers among 100 measurements (6.00%)
  2 (2.00%) high mild
  4 (4.00%) high severe
Benchmarking all/sr.abomonation
Benchmarking all/sr.abomonation: Warming up for 3.0000 s
Benchmarking all/sr.abomonation: Collecting 100 samples in estimated 5.0000 s (544M iterations)
Benchmarking all/sr.abomonation: Analyzing
all/sr.abomonation      time:   [9.1701 ns 9.1783 ns 9.1881 ns]
                        change: [-5.3867% -5.1742% -4.9757%] (p = 0.00 < 0.05)
                        Performance has improved.
Found 7 outliers among 100 measurements (7.00%)
  4 (4.00%) high mild
  3 (3.00%) high severe
abomonation: 116 bytes
Benchmarking all/de.abomonation
Benchmarking all/de.abomonation: Warming up for 3.0000 s
Benchmarking all/de.abomonation: Collecting 100 samples in estimated 5.0000 s (480M iterations)
Benchmarking all/de.abomonation: Analyzing
all/de.abomonation      time:   [10.417 ns 10.422 ns 10.428 ns]
                        change: [-0.5161% -0.3097% -0.1274%] (p = 0.00 < 0.05)
                        Change within noise threshold.
Found 7 outliers among 100 measurements (7.00%)
  3 (3.00%) high mild
  4 (4.00%) high severe
Benchmarking all/sr.rkyv
Benchmarking all/sr.rkyv: Warming up for 3.0000 s
Benchmarking all/sr.rkyv: Collecting 100 samples in estimated 5.0014 s (18M iterations)
Benchmarking all/sr.rkyv: Analyzing
all/sr.rkyv             time:   [277.88 ns 278.00 ns 278.14 ns]
                        change: [-9.1361% -8.7507% -8.4235%] (p = 0.00 < 0.05)
                        Performance has improved.
Found 5 outliers among 100 measurements (5.00%)
  2 (2.00%) high mild
  3 (3.00%) high severe
rkyv: 72 bytes
Benchmarking all/de.rkyv (unvalidated)
Benchmarking all/de.rkyv (unvalidated): Warming up for 3.0000 s
Benchmarking all/de.rkyv (unvalidated): Collecting 100 samples in estimated 5.0000 s (5.7B iterations)
Benchmarking all/de.rkyv (unvalidated): Analyzing
all/de.rkyv (unvalidated)
                        time:   [870.03 ps 870.85 ps 871.83 ps]
                        change: [-4.9657% -4.1902% -3.5107%] (p = 0.00 < 0.05)
                        Performance has improved.
Found 8 outliers among 100 measurements (8.00%)
  4 (4.00%) high mild
  4 (4.00%) high severe
Benchmarking all/de.rkyv (validated)
Benchmarking all/de.rkyv (validated): Warming up for 3.0000 s
Benchmarking all/de.rkyv (validated): Collecting 100 samples in estimated 5.0001 s (186M iterations)
Benchmarking all/de.rkyv (validated): Analyzing
all/de.rkyv (validated) time:   [26.714 ns 26.745 ns 26.780 ns]
                        change: [-0.4612% -0.2470% -0.0637%] (p = 0.01 < 0.05)
                        Change within noise threshold.
Found 2 outliers among 100 measurements (2.00%)
  1 (1.00%) high mild
  1 (1.00%) high severe

```
