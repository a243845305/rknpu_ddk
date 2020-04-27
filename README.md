# RKNPU DDK
  RKNPU DDK is provide advanced interface to access Rockchip NPU.

## Support Platform

- RK1808
- RK1806

Note: RK3399Pro platform is not supported.

## Support OPs
- ADD
- MULTIPLY
- CONV2D
- FULLCONNECT
- SOFTMAX
- POOL
- LEAKY_RELU
- CONCAT
- BATCH_NORM
- RESHAPE
- PERMUTE
- RELU
- SUBTRACT
- RELU6
- DATACONVERT
- SLICE
- CLIP
- GATHER

## Document
There are manuals generated by doxgen under the doc directory. For more information, please check the "doc/index.html" page.
Users can also use the following commands to generate the latest documentation:
```
./tools/doxygen/run_doxygen.sh
```


## System dependence
 - RK1808 system firmware version needs to be greater than 1.15. Users can download the source code of RK1808 using the following command:
 ```
 repo init --repo-url=https://github.com/rockchip-linux/repo -u https://github.com/rockchip-linux/manifests -b master -m rk1808_linux_release.xml
 repo sync
```

- Users can download pre-compiled firmware from BaiduNetDisk:
BaiduNetDisk: https://eyun.baidu.com/s/3nwewb2L key: rknn
