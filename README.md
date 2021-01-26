# minasender :  TESTworld 批量转账 !


# minasender
一个可以批量转账mina的脚本 ( https://github.com/MinaProtocol/mina )。
脚本的输入变量?:

- [x] -发送的mina数量

- [x] -转账费用

- [x] -解锁账户的密码

- [x] -20个测试网的账户地址

注意: 请在 ~/.bashrc 或者 ~/.profile 中填写以下配置
```
export CODA_PUBLIC_KEY=你的mina地址

export MINA_PUBLIC_KEY=你的mina地址
```
# 使用方法:
```
git clone https://github.com/cherylmu/minasender.git
cd minasender/
chmod +x minasender
bash minasender
```
