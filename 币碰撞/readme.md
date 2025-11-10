<p align="center">
	<img alt="logo" width=200" src="../img/logo_bitcoin.png">
</p>
<h4 align="center">钱包碰撞</h4>
<h4 align="center">本系统源码下载，如有需要的请联系客服</h4>
<p align="center">
 <img src="https://img.shields.io/badge/-币安交易所-red.svg" alt="Downloads">
 <img src="https://img.shields.io/badge/-智能合约-yellow.svg" alt="Downloads">
 <img src="https://img.shields.io/badge/-合约交易-blue.svg" alt="Downloads">
 <img src="https://img.shields.io/badge/-源码出售-green.svg" alt="Downloads">
 <img src="https://img.shields.io/badge/-BTC交易所-red.svg" alt="Downloads">
 <img src="https://img.shields.io/badge/-交易所搭建-yellow.svg" alt="Downloads">
 <img src="https://img.shields.io/badge/-区块链-blue.svg" alt="Downloads">
 <img src="https://img.shields.io/badge/-币安链-green.svg" alt="Downloads">
</p>



<div align="center">
  <p>
    💻 <strong>演示地址：</strong> @dhng885</p>
  <p>
    👥 <strong>源码下载：</strong> <a href="https://t.me/coin1818">coin1818</a>
  </p>
  <p>
    👥 <strong>源码交流群：</strong> <a href="https://t.me/dhj_hw888">dhj_hw888</a>
  </p>
</div>

## 1.项目简介

比特币/以太坊钱包碰撞



# 钱包碰撞

比特币/以太坊钱包冲突（支持 Python 3.4+）

## Feature
- 支持暴力破解和字典攻击
- 多线程
- 双输出，高效钱包和带余额功能的钱包

## Dependency
比特币：

- 请求
- 少量

以太坊：

- 请求
- ecdsa
- pysha3

## 如何使用？

警告：要绕过 blockchain.info/etherchain.org API 请求限制，请申请 API 密钥。

### 蛮力攻击

`python eth.py`放手一搏吧。

它会自动生成一个随机数作为私钥。

### 字典攻击

请替换`dict.txt`为您的密码字典文件。

`python trx.py`带着你的字典一起跑。

它将使用您的口令作为私钥。

## 结果在哪里？

输出文件`found.txt`包含有关有效钱包的信息。

输出文件`fund.txt`包含有关钱包余额的信息。

以下是不同的信息说明。

### 比特币

第一列：`0: Address, 1: Compressed Address`

第 2 列：余额

第 3 列：已发送余额总额

第 4 列：私钥

第5列：地址

### 以太坊

第 1 列：余额

第 2 列：私钥

第 3 列：地址

## License
wallet-collision is published under Apache License 2.0 License. See the LICENSE file for more.