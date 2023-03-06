# tencent_cloud_cpp_sample

```shell
PRODUCT_NAME="lighthouse"

# 编译依赖
git clone https://github.com/TencentCloud/tencentcloud-sdk-cpp
cd tencentcloud-sdk-cpp
mkdir sdk_build
cd sdk_build
cmake -DBUILD_MODULES="$PRODUCT_NAME" ..
make
sudo make install

# 编译源码
cd ../
mkdir build
cd build
cmake ..
make
export LD_LIBRARY_PATH=/usr/local/lib:$LD_LIBRARY_PATH

# 运行
./tencent_cloud_cpp_sample
```
