---
sidebar_position: 1
---

# Golang 学习总结

Linux 安装 Golang（国内）
>go语言中文网：https://studygolang.com/dl

```bash
# 下载 Go1.20.10
wget -c https://studygolang.com/dl/golang/go1.20.10.linux-amd64.tar.gz -O - | sudo tar -xz -C /usr/local
# 添加环境变量
echo "export PATH=$PATH:/usr/local/go/bin" >> ~/.bashrc && source ~/.bashrc
```

