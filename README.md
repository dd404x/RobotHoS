
# ROBOT Hall of Shame

A summary showing whether a bank's online-banking site is vulnerable to [ROBOT](https://robotattack.org).

To those banks marked *bad*, shame on you!

| Name                 | Host                           |   Port | IP              | Flag         | Verdict   |
|:---------------------|:-------------------------------|-------:|:----------------|:-------------|:----------|
| 中国农业银行         | perbank.abchina.com            |    443 | 124.74.251.169  | SAFE         | Good      |
| 中国银行             | ebsnew.boc.cn                  |    443 | 219.141.226.40  | INCONSISTENT | Unsure    |
| 交通银行             | www.95559.com.cn               |    443 | 124.74.244.2    | NOTLS        | Error     |
| 中信银行             | i.bank.ecitic.com              |    443 | 219.142.124.139 | SAFE         | Good      |
| 光大银行             | www.cebbank.com                |    443 | 106.37.164.153  | VULNERABLE   | **Bad**   |
| 中国建设银行         | ibsbjstar.ccb.com.cn           |    443 | 106.120.109.66  | SAFE         | Good      |
| 华夏银行             | sbank.hxb.com.cn               |    443 | 58.210.177.133  | VULNERABLE   | **Bad**   |
| 中国工商银行         | mybank.icbc.com.cn             |    443 | 180.169.80.55   | SAFE         | Good      |
| 大连银行             | ibank.bankofdl.com             |    443 | 59.46.191.34    | VULNERABLE   | **Bad**   |
| 北京银行             | ebank.bankofbeijing.com.cn     |    443 | 219.141.230.17  | VULNERABLE   | **Bad**   |
| 渤海银行             | ebank.cbhb.com.cn              |    443 | 221.238.57.199  | SAFE         | Good      |
| 盛京银行             | newperson.shengjingbank.com.cn |  16443 | 59.46.94.53     | VULNERABLE   | **Bad**   |
| 吉林银行             | netbank.jlbank.com.cn          |    443 | 124.235.208.199 | VULNERABLE   | **Bad**   |
| 哈尔滨银行           | ibank.hrbb.com.cn              |    443 | 222.171.250.196 | VULNERABLE   | **Bad**   |
| 兴业银行             | personalbank.cib.com.cn        |    443 | 218.66.47.198   | SAFE         | Good      |
| 广发银行             | ebanks.cgbchina.com.cn         |    443 | 113.108.153.42  | VULNERABLE   | **Bad**   |
| 宁波银行             | e.nbcb.com.cn                  |    443 | 61.164.72.169   | VULNERABLE   | **Bad**   |
| 浦发银行             | ebank.spdb.com.cn              |    443 | 60.173.223.199  | VULNERABLE   | **Bad**   |
| 浙江泰隆商业银行     | ebank.zjtlcb.com               |    443 | 122.226.149.198 | VULNERABLE   | **Bad**   |
| 招商银行             | pbsz.ebank.cmbchina.com        |    443 | 180.168.0.58    | SAFE         | Good      |
| 中国民生银行         | nper.cmbc.com.cn               |    443 | 219.142.89.145  | SAFE         | Good      |
| 浙商银行             | perbank.czbank.com             |    443 | 60.191.8.56     | SAFE         | Good      |
| 平安银行             | bank.pingan.com.cn             |    443 | 202.69.23.236   | SAFE         | Good      |
| 上海银行             | ebanks.bankofshanghai.com      |    443 | 222.66.10.162   | SAFE         | Good      |
| 台州银行             | ebank.tzbank.com               |    443 | 122.226.171.71  | SAFE         | Good      |
| 泰安银行             | ebank.taccb.com.cn             |    443 | 222.173.8.202   | SAFE         | Good      |
| 微众银行             | www.webank.com                 |    443 | 211.159.212.166 | SAFE         | Good      |
| 臺灣銀行             | ebank.bot.com.tw               |    443 | 103.21.63.9     | SAFE         | Good      |
| 第一商業銀行         | ibank.firstbank.com.tw         |    443 | 23.8.228.192    | SAFE         | Good      |
| 土地銀行             | mybank.landbank.com.tw         |    443 | 202.39.57.95    | VULNERABLE   | **Bad**   |
| OCBC Bank            | internet.ocbc.com              |    443 | 23.58.251.186   | SAFE         | Good      |
| DBS Bank             | internet-banking.dbs.com.sg    |    443 | 104.72.94.241   | SAFE         | Good      |
| United Overseas Bank | pib.uob.com.sg                 |    443 | 203.116.108.248 | SAFE         | Good      |
| Maybank              | www.maybank2u.com.my           |    443 | 104.72.98.249   | SAFE         | Good      |
| Bangkok Bank         | ibanking.bangkokbank.com       |    443 | 119.46.71.60    | SAFE         | Good      |
| Indusind Bank        | indusnet.indusind.com          |    443 | 203.196.200.211 | NOTLS        | Error     |
| Wells Fargo          | connect.secure.wellsfargo.com  |    443 | 159.45.170.156  | SAFE         | Good      |
| Bank of America      | www.bankofamerica.com          |    443 | 171.161.206.100 | SAFE         | Good      |
| Citigroup            | online.citi.com                |    443 | 23.199.132.100  | SAFE         | Good      |
| JPMorgan Chase       | secure01b.chase.com            |    443 | 159.53.232.21   | SAFE         | Good      |

This file is generated authomatically with `run.py`, which in turn calls the
detection code from [this repo](https://github.com/robotattackorg/robot-detect/).

Currently I only included in `banks.csv` a dozon of banks that I know, mostly in Asia.
If you know more banks, PRs welcome.

