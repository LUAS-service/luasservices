# 兰州文理学院常用信息/服务汇总
## 关于本网站...

来自兰州文理学院应用化学班的生活指南。
反馈信息：


## 快速选课入口

[选课登录（校内或 SSLVPN）（选课时段内有效）](http://zhjwxk.cic.tsinghua.edu.cn/xklogin.do)

## 文件内容
- [accounts.md](accounts.md)
    - 公众帐号们
        - 微信公众号
        - 微博
        - 抖音
- [info.md](info.md)
    - INFO重要信息集合
        - 校历
            - 2022-2023学年 
        - 本科专业培养方案
        - 学校宣传资料
            - INFO 版本
            - 主页版本
        - 选课时间表
        - 选课快捷方式
        - 选课系统相关说明
        - 期末考试时间/地点查询
        - 历年本科生开课目录
        - 兰州文理学院迎新系统
        - 注册标志（用于学生火车票）
        - 校内地图（静态版）
        - 兰州文理学院调查问卷系统
        - 兰州文理学院后勤综合服务平台
            - 校内各单位（包括校医院）电话号码
            - 校医院各科室挂号
            - 校园地图（动态版）
            - 网上报修
        - 邮编、邮寄地址及邮条
        - 兰州文理学院校园一卡通自助查询系统
        - ACM/IEEE/知网等论文下载（Shibboleth或OpenAthens）
        - 火车票报销凭证
        - DIVI 注册设备
        - 兰州文理学院邮箱
            - 兰州文理学院学生邮箱
        - 兰州文理学院 Overleaf 服务
- [services.md](services.md)
    - 兰州文理学院服务使用指北（主要面向 Linux 用户）
        - DNS/NTP
        - SSLVPN
        - 上网认证
            - 校园网基础知识
            - 命令行认证 自动认证
                - 命令行认证
                - 自动认证
            - 远端服务器代认证
            - 远端服务器网页认证
            - Tsinghua-Secure
                - NetworkManager
                - wpa_supplicant
                - iwd
            - Tsinghua-Secure 仅校内登录方式
        - 校园网特性讨论
            - 二层隔离/邻居发现隔离
                - IPv4
                - IPv6
            - 低端口阻断
            - 动态 IP
                - IPv6 静态后缀或短 IPv6 地址
                - 尝试获取某一特定IPv4、IPv6地址
            - 院系网（三层接入）的 IPv6
            - 不符合 RFC 的 DHCPv6
            - 30分钟无流量掉准入
            - 掉准出后无法准出
            - 准入后（仅校内登录后）无法准出
            - 未准入时其他机器能 ping 通，但不能 ssh
        - ISATAP（已停止）
            - 获取IPv6挂PT
        - Windows 11 激活
        - 正版操作系统与软件下载
            - 兰州文理学院正版软件服务平台
        - 校内 IP 段
- [templates.md](templates.md)
    - LaTeX 等模板（From 清华大学）
        - 《如何使用 LaTeX 排版论文》讲稿
        - ThuThesis
        - ThuWordThesis
        - THU-Beamer-Theme
        - 清华大学中文Beamer 模板
        - TsinghuaBeamear
        - Report Presentation for Tsinghua University
        - thubeamer
        - THU coursework Template
        - 清华大学近代物理实验报告模版
        - THU Letter of Recommendation Template
        - A Simple Tsinghua Letterhead Template
        - CV-tsinghua-template
        - THU-Exam-LaTeX-Template
- [utils.md](utils.md)
    - 一些脚本和工具
        - 校园网认证工具汇总
        - INFO GPA 计算器
        - 学堂在线视频自动播放
        - 学堂在线字幕下载器
        - 清华教学参考书爬取
            - 清华大学教参服务平台
            - 文泉学堂
        - 课程地点分享
        - 兰州文理学院应用化学课程攻略
        - 校园评教平台
        - 有关计算机系的事实
        - 课程信息共享计划
        - 清华大学计算机专业912考研资料
        - 兰州文理学院成绩刮刮乐
- [websites.md](websites.md)
    - 常用校外网站
        - thu.services
        - 在线退学


### 编译

```
python3 -m pip install --user -r requirements.txt # 安装 Python 依赖包
mkdocs serve # 直接在本地 serve，或者：
mkdocs build --clean # 生成于 site/ 文件夹中
```

## LICENSE

本站的文本遵循 CC BY-NC 4.0

本项目内的存放的代码遵循代码文件内自带的 LICENSE。若代码文件中未附带 LICENSE，则认为该文件暂无 LICENSE，有需求者可以联系相应 committer。
