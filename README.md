# MultiFuzz
Fuzzing Multiparty Protocols like Pub/Sub Protocols

## Usage
MultiFuzz needs to work with [desockmulti](https://github.com/zyingp/desockmulti). Please install it first.

Then, similar with [AFL](https://github.com/google/AFL), run MultiFuzz as follows:

`LD_PRELOAD=/path/to/desockmulti/desockmulti.so ./afl-fuzz -d -i testcase_dir -o findings_dir –-/path/to/program [...params...]`

We also put some testcases we used under ./testcases/MultiFuzz/ if you are interested in.

## Others
If you use MutiFuzz/desockmulti, please kindly help to cite our paper:

Yingpei Zeng, Mingmin Lin, Shanqing Guo, Yanzhao Shen, Tingting Cui, Ting Wu, Qiuhua Zheng, Qiuhua Wang, MultiFuzz: A Coverage-Based Multiparty-Protocol Fuzzer for IoT Publish/Subscribe Protocols, Sensors, Vol.20, No.18, 5194, 2020.
