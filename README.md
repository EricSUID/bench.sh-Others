# bench.sh-Others
分享几个常用的Linux服务器测试脚本
感谢博主https://www.openos.org/post/106/

wget -qO- bench.sh | bash

wget -qO- git.io/superbench.sh | bash

使用参数的方法：
这个脚本主要测试中国网络运营商的上传和下载速度
```shell
wget git.io/superbench.sh; chmod +x superbench.sh
```
```shell
./superbench.sh info
./superbench.sh io
./superbench.sh speed
./superbench.sh share
```

---

怀恋上一版的请使用：
```shell
wget -qO- git.io/superbench_old.sh | bash
```

作者网站
https://www.oldking.net/599.html

另加一个测试脚本, 这个脚本对全球各地区都有比较详细的网络测试
```shell
curl -LsO git.io/bench.sh; chmod +x bench.sh && ./bench.sh -a share
```

---

还有一个
- 中文版: 
```shell
wget -N --no-check-certificate https://raw.githubusercontent.com/FunctionClub/ZBench/master/ZBench-CN.sh && bash ZBench-CN.sh
```
- 英文版: 
```shell
wget -N --no-check-certificate https://raw.githubusercontent.com/FunctionClub/ZBench/master/ZBench.sh && bash ZBench.sh
```
