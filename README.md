# leveldb

同步自https://github.com/google/leveldb

## 编译

git clone https://github.com/google/leveldb.git

cd leveldb

修改CM艾克Lists.txt，将c++11更新为c++17

mkdir build

cd build

cmake -DCMAKE_BUILD_TYPE=Release .. && cmake --build .

