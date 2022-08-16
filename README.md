# 20220816

去重，目录调整

文件目录
```bash
.
├── CTF_dict
│   └── ctf.txt
├── IDC密码
│   ├── IDC_password_1(9k).txt
│   ├── IDC_password_2(1w).txt
│   ├── IDC_password_3(9k).txt
│   ├── 刺猬IDC密码.txt
│   └── 华中IDC机房字典2.txt
├── fuzz_接口
│   ├── api
│   │   └── api(300).txt
│   ├── spring_fuzz
│   │   └── spring-configuration-metadata.txt
│   └── ssrf_fuzz
│       ├── etc(2k).txt
│       ├── log(100).txt
│       ├── proc(50).txt
│       ├── scan(300).txt
│       └── ssrf_(500).txt
├── msf_wordlists
│   ├── adobe_top100_pass.txt
│   ├── av-update-urls.txt
│   ├── av_hips_executables.txt
│   ├── burnett_top_1024.txt
│   ├── burnett_top_500.txt
│   ├── can_flood_frames.txt
│   ├── cms400net_default_userpass.txt
│   ├── common_roots.txt
│   ├── dangerzone_a.txt
│   ├── dangerzone_b.txt
│   ├── db2_default_pass.txt
│   ├── db2_default_user.txt
│   ├── db2_default_userpass.txt
│   ├── default_pass_for_services_unhash.txt
│   ├── default_userpass_for_services_unhash.txt
│   ├── default_users_for_services_unhash.txt
│   ├── dlink_telnet_backdoor_userpass.txt
│   ├── grafana_plugins.txt
│   ├── hci_oracle_passwords.csv
│   ├── http_default_pass.txt
│   ├── http_default_userpass.txt
│   ├── http_default_users.txt
│   ├── http_owa_common.txt
│   ├── idrac_default_pass.txt
│   ├── idrac_default_user.txt
│   ├── ipmi_passwords.txt
│   ├── ipmi_users.txt
│   ├── joomla.txt
│   ├── keyboard-patterns.txt
│   ├── lync_subdomains.txt
│   ├── malicious_urls.txt
│   ├── mirai_pass.txt
│   ├── mirai_user.txt
│   ├── mirai_user_pass.txt
│   ├── multi_vendor_cctv_dvr_pass.txt
│   ├── multi_vendor_cctv_dvr_users.txt
│   ├── named_pipes.txt
│   ├── namelist.txt
│   ├── oracle_default_hashes.txt
│   ├── oracle_default_passwords.csv
│   ├── oracle_default_userpass.txt
│   ├── password.lst
│   ├── piata_ssh_userpass.txt
│   ├── postgres_default_pass.txt
│   ├── postgres_default_user.txt
│   ├── postgres_default_userpass.txt
│   ├── root_userpass.txt
│   ├── routers_userpass.txt
│   ├── rpc_names.txt
│   ├── rservices_from_users.txt
│   ├── sap_common.txt
│   ├── sap_default.txt
│   ├── sap_icm_paths.txt
│   ├── scada_default_userpass.txt
│   ├── sensitive_files.txt
│   ├── sensitive_files_win.txt
│   ├── sid.txt
│   ├── snmp_default_pass.txt
│   ├── telerik_ui_asp_net_ajax_versions.txt
│   ├── telnet_cdata_ftth_backdoor_userpass.txt
│   ├── tftp.txt
│   ├── tomcat_mgr_default_pass.txt
│   ├── tomcat_mgr_default_userpass.txt
│   ├── tomcat_mgr_default_users.txt
│   ├── unix_passwords.txt
│   ├── unix_users.txt
│   ├── vnc_passwords.txt
│   ├── vxworks_collide_20.txt
│   ├── vxworks_common_20.txt
│   ├── wp-exploitable-plugins.txt
│   ├── wp-exploitable-themes.txt
│   ├── wp-plugins.txt
│   └── wp-themes.txt
├── web目录
│   ├── asp aspx
│   │   ├── asp(1.8w).txt
│   │   ├── asp(3.4w).txt
│   │   └── aspx(1w).txt
│   ├── jsp
│   │   ├── jsp(2w).txt
│   │   └── jsp(7w).txt
│   ├── php
│   │   ├── php(1w).txt
│   │   ├── php(30w).txt
│   │   ├── php(3k).txt
│   │   └── php(40w).txt
│   ├── py
│   │   └── py(5b).txt
│   ├── tomcat
│   │   └── tomcat(90).txt
│   ├── weblogic
│   │   └── weblogic(360).txt
│   ├── 后台
│   │   └── 后台.txt
│   ├── 备份
│   │   ├── back(1.3w).txt
│   │   ├── back(9k).txt
│   │   └── db(7k).txt
│   └── 目录
│       ├── dir(2w).txt
│       ├── dir(5w).txt
│       └── dirsearch.txt
├── 其它
│   ├── robots
│   │   ├── archive
│   │   │   ├── InterestingDirectories.txt
│   │   │   ├── Top10-RobotsDisallowed.txt
│   │   │   ├── Top100-RobotsDisallowed.txt
│   │   │   ├── Top1000-RobotsDisallowed.txt
│   │   │   ├── Top10000-RobotsDisallowed.txt
│   │   │   ├── Top100000-RobotsDisallowed.txt
│   │   │   ├── Top500-RobotsDisallowed.txt
│   │   │   ├── code
│   │   │   │   ├── cleanuponly.sh
│   │   │   │   ├── extractonly.sh
│   │   │   │   ├── pullrobots.sh
│   │   │   │   ├── tocomma.csv
│   │   │   │   ├── top-1m.csv
│   │   │   │   └── xargsonly.sh
│   │   │   └── raw_2019.txt
│   │   ├── curated.txt
│   │   ├── top10.txt
│   │   ├── top100.txt
│   │   ├── top1000.txt
│   │   └── top10000.txt
│   ├── webshell_pass
│   │   └── WebShell-Password（433616）.txt
│   ├── wifi密码
│   │   ├── wifi-top447_pass.txt
│   │   ├── wifi_top2000_pass.txt
│   │   ├── wifi_top4800_pass.txt
│   │   └── wifi_top62_pass.txt
│   ├── 手机
│   │   └── Test_Chinese_Mobilephonenumber.txt_OK.txt
│   ├── 日期
│   │   └── yyyymmdd-1960-2020.txt
│   └── 物联网lot
│       ├── acount.txt
│       └── password.txt
├── 国外
│   ├── Asteroids.txt
│   ├── Bacteria.txt
│   ├── Bible.txt
│   ├── Common.txt
│   ├── Crackdict.txt
│   ├── English_Common.txt
│   ├── English_Length03.txt
│   ├── English_Length04.txt
│   ├── English_Length05.txt
│   ├── English_Length06.txt
│   ├── English_Length07.txt
│   ├── English_Length08.txt
│   ├── English_Length09.txt
│   ├── English_Length10.txt
│   ├── Films.txt
│   ├── Internet_Hosts.txt
│   ├── Koran.txt
│   ├── Ok.txt
│   ├── Places.txt
│   ├── Python.txt
│   ├── Sports.txt
│   ├── Startrek.txt
│   └── Tolkien.txt
├── 弱口令
│   ├── pass
│   │   ├── TOP
│   │   │   ├── TOP(1k).txt
│   │   │   ├── TOP(1w).txt
│   │   │   ├── TOP(9k).txt
│   │   │   ├── TOP1000.txt
│   │   │   ├── TOP20000.txt
│   │   │   ├── TOP3000.txt
│   │   │   ├── TOP400.txt
│   │   │   └── TOP6000.txt
│   │   ├── 常用
│   │   │   ├── digit_and_letter_top500.txt
│   │   │   ├── keyboard_top500.txt
│   │   │   ├── pass2.5w.txt
│   │   │   ├── pass7.5w.txt
│   │   │   ├── pass7500.txt
│   │   │   ├── pass_1000.txt
│   │   │   └── pinyin_top500.txt
│   │   ├── 综合pass
│   │   │   ├── Comprehensive_password_10_En(5.5w).txt
│   │   │   ├── Comprehensive_password_11_En(6w).txt
│   │   │   ├── Comprehensive_password_1_En(3.5k).txt
│   │   │   ├── Comprehensive_password_2_En(2.5k).txt
│   │   │   ├── Comprehensive_password_3_En(2.5w).txt
│   │   │   ├── Comprehensive_password_4_En(2.5w).txt
│   │   │   ├── Comprehensive_password_5_En(1w).txt
│   │   │   ├── Comprehensive_password_6_En(6k).txt
│   │   │   ├── Comprehensive_password_7_En(1.2w).txt
│   │   │   ├── Comprehensive_password_8_En(5w).txt
│   │   │   └── Comprehensive_password_9_En(4.8w).txt
│   │   ├── 条件字典
│   │   │   ├── 3条件8位(1w).txt
│   │   │   ├── 4条件8位(1400).txt_OK.txt
│   │   │   ├── 身份ID后6位(3w).txt
│   │   │   ├── 数字字母(7500).txt_OK.txt
│   │   │   ├── 四个条件至少满足三个的8位数密码91286条.txt
│   │   │   ├── 至少存在一个字母一个数字一个特殊符号的6位数密码27566条.txt
│   │   │   ├── 至少存在一个字母一个数字一个特殊符号的8位数密码26860条.txt
│   │   │   ├── 至少存在一个大写字母一个小写字母一个数字的6位数密码75945条.txt
│   │   │   ├── 至少存在一个大写字母一个小写字母一个数字的8位数密码59995条.txt
│   │   │   ├── 至少存在一个大写字母一个小写字母一个数字不能有三个相同的字符和特殊符号的6位数密码76905条.txt
│   │   │   └── 至少存在一个大写字母一个小写字母一个数字不能有三个相同的字符和特殊符号的8位数密码60850条.txt
│   │   └── 键盘组合
│   │       ├── keyboard_1.2w.txt
│   │       ├── keyboard_top100.txt
│   │       └── keyboard_top500.txt
│   ├── user
│   │   ├── TOP
│   │   │   ├── TOP200.txt
│   │   │   ├── TOP2000.txt
│   │   │   ├── TOP60.txt
│   │   │   └── TOP9w.txt
│   │   ├── 其他
│   │   │   ├── QQ_Mail(3w).txt
│   │   │   └── user(1w).txt
│   │   └── 姓名拼音
│   │       ├── china_name_2k.txt
│   │       └── china_name_9w.txt
│   └── 通用 字母数字_拼音
│       ├── digit_and_letter_top100.txt
│       ├── digit_and_letter_top1000.txt
│       ├── digit_and_letter_top500.txt
│       ├── pinyin(5w).txt
│       ├── pinyin_top100.txt
│       └── pinyin_top500.txt
├── 服务爆破
│   ├── Mongodb_login
│   │   ├── Password.txt
│   │   └── Username.txt
│   ├── Phpmyadmin_login
│   │   ├── Password.txt
│   │   └── Username.txt
│   ├── Postgresql_login
│   │   ├── Password.txt
│   │   └── Username.txt
│   ├── Svn_login
│   │   ├── Password.txt
│   │   └── Username.txt
│   ├── Tomcat_login
│   │   ├── Password.txt
│   │   └── Username.txt
│   ├── Vnc_login
│   │   └── Password.txt
│   ├── Weblogic_login
│   │   ├── Password.txt
│   │   └── Username.txt
│   ├── ftp_login
│   │   ├── Password(150).txt
│   │   └── Username.txt_OK.txt
│   ├── memcached_login
│   │   ├── Password.txt
│   │   └── Username.txt
│   ├── mysql_login
│   │   ├── Password.txt_OK.txt
│   │   └── Username.txt
│   ├── oracle_login
│   │   ├── Password.txt_OK.txt
│   │   └── Username.txt_OK.txt
│   ├── rdp_login
│   │   ├── Password.txt_OK.txt
│   │   ├── Username.txt
│   │   └── 烟头3389爆破字典.txt
│   ├── snmp_pass
│   │   └── Snmp_password.txt
│   └── ssh_login
│       ├── Password.txt_OK.txt
│       └── Username.txt
├── 社工字典生成
│   ├── N.C.P.H社会工程学字典生成器
│   │   ├── 社会工程学字典(透明版).exe
│   │   └── 社会工程学字典.exe
│   ├── pydictor
│   │   ├── pydictor-master
│   │   │   ├── LICENSE
│   │   │   ├── README.md
│   │   │   ├── README_CN.md
│   │   │   ├── core
│   │   │   │   ├── BASE.py
│   │   │   │   ├── CHAR.py
│   │   │   │   ├── CHUNK.py
│   │   │   │   ├── CONF.py
│   │   │   │   ├── EXTEND.py
│   │   │   │   ├── PATTERN.py
│   │   │   │   ├── SEDB.py
│   │   │   │   └── __init__.py
│   │   │   ├── docs
│   │   │   │   ├── doc
│   │   │   │   │   ├── api.md
│   │   │   │   │   └── usage.md
│   │   │   │   └── screenshot
│   │   │   │       ├── conf.png
│   │   │   │       ├── extend.png
│   │   │   │       └── sedb.png
│   │   │   ├── funcfg
│   │   │   │   ├── build.conf
│   │   │   │   ├── extend.conf
│   │   │   │   ├── leet_mode.conf
│   │   │   │   ├── scratch.sites
│   │   │   │   ├── scratch_blacklist.conf
│   │   │   │   └── sedb_tricks.conf
│   │   │   ├── lib
│   │   │   │   ├── __init__.py
│   │   │   │   ├── data
│   │   │   │   │   ├── __init__.py
│   │   │   │   │   ├── data.py
│   │   │   │   │   ├── datatype.py
│   │   │   │   │   └── text.py
│   │   │   │   ├── encode
│   │   │   │   │   ├── __init__.py
│   │   │   │   │   ├── b16_encode.py
│   │   │   │   │   ├── b32_encode.py
│   │   │   │   │   ├── b64_encode.py
│   │   │   │   │   ├── des_encode.py
│   │   │   │   │   ├── execjs_encode.py
│   │   │   │   │   ├── hmac_encode.py
│   │   │   │   │   ├── md516_encode.py
│   │   │   │   │   ├── md5_encode.py
│   │   │   │   │   ├── none_encode.py
│   │   │   │   │   ├── rsa_encode.py
│   │   │   │   │   ├── sha1_encode.py
│   │   │   │   │   ├── sha256_encode.py
│   │   │   │   │   ├── sha512_encode.py
│   │   │   │   │   ├── test_encode.py
│   │   │   │   │   └── url_encode.py
│   │   │   │   ├── fun
│   │   │   │   │   ├── __init__.py
│   │   │   │   │   ├── color.py
│   │   │   │   │   ├── decorator.py
│   │   │   │   │   ├── filter.py
│   │   │   │   │   ├── fun.py
│   │   │   │   │   ├── leetmode.py
│   │   │   │   │   └── osjudger.py
│   │   │   │   └── parse
│   │   │   │       ├── __init__.py
│   │   │   │       ├── argsparse.py
│   │   │   │       ├── command.py
│   │   │   │       ├── confparse.py
│   │   │   │       └── tricksparse.py
│   │   │   ├── plugins
│   │   │   │   ├── __init__.py
│   │   │   │   ├── birthday.py
│   │   │   │   ├── ftp.py
│   │   │   │   ├── pid4.py
│   │   │   │   ├── pid6.py
│   │   │   │   ├── pid8.py
│   │   │   │   └── scratch.py
│   │   │   ├── pydictor.py
│   │   │   ├── results
│   │   │   ├── rules
│   │   │   │   ├── BaseTrick.py
│   │   │   │   ├── EB.py
│   │   │   │   ├── Mailrule.py
│   │   │   │   ├── NB.py
│   │   │   │   ├── NNrule.py
│   │   │   │   ├── SB.py
│   │   │   │   ├── SDrule.py
│   │   │   │   ├── SNrule.py
│   │   │   │   ├── SSrule.py
│   │   │   │   ├── SingleRule.py
│   │   │   │   └── __init__.py
│   │   │   ├── tools
│   │   │   │   ├── __init__.py
│   │   │   │   ├── combiner.py
│   │   │   │   ├── comparer.py
│   │   │   │   ├── counter.py
│   │   │   │   ├── handler.py
│   │   │   │   ├── hybrider.py
│   │   │   │   ├── shredder.py
│   │   │   │   ├── uniqbiner.py
│   │   │   │   └── uniqifer.py
│   │   │   └── wordlist
│   │   │       ├── App
│   │   │       ├── IoT
│   │   │       │   └── MariaBotPass.txt
│   │   │       ├── NiP
│   │   │       │   └── AwesomeSystemTestUsername.txt
│   │   │       ├── SEDB
│   │   │       │   ├── ChineseWeakPass1000.txt
│   │   │       │   └── UserCommonPass.txt
│   │   │       ├── Sys
│   │   │       │   └── SSH_Root_Weak_Pass.txt
│   │   │       ├── Web
│   │   │       │   └── CommonWebAdminPass.txt
│   │   │       └── WiFi
│   │   │           └── TinyCommonWifiWeakPass.txt
│   │   └── pydictor-master.zip
│   ├── src字典生成
│   │   ├── PwdBUD-main
│   │   │   ├── README.md
│   │   │   ├── dict
│   │   │   │   ├── birth.txt
│   │   │   │   ├── cnname.txt
│   │   │   │   ├── top1000.txt
│   │   │   │   └── topandbirth.txt
│   │   │   ├── pwdbud.py
│   │   │   └── src
│   │   │       ├── __init__.py
│   │   │       ├── __pycache__
│   │   │       │   ├── __init__.cpython-39.pyc
│   │   │       │   ├── factor2.cpython-39.pyc
│   │   │       │   ├── jobnumber.cpython-39.pyc
│   │   │       │   └── parseArgs.cpython-39.pyc
│   │   │       ├── factor2.py
│   │   │       ├── jobnumber.py
│   │   │       └── parseArgs.py
│   │   └── PwdBUD-main.zip
│   ├── 易优软件-超级字典生成器.exe
│   ├── 品轩字典生成器V0.5.exe
│   ├── 白鹿社工字典生成器
│   │   ├── Dic
│   │   │   ├── 0x00.txt
│   │   │   ├── 0x01.txt
│   │   │   ├── B1.txt
│   │   │   ├── B2.txt
│   │   │   ├── C1.txt
│   │   │   └── C2.txt
│   │   ├── config.ini
│   │   └── 白鹿社工字典生成器.exe
│   ├── 真空密码字典生成器
│   │   ├── COMCTL32.OCX
│   │   ├── COMDLG32.OCX
│   │   ├── Desktop.ini
│   │   ├── MSCOMCT2.OCX
│   │   ├── MSCOMCTL.OCX
│   │   ├── help.txt
│   │   ├── msvbvm60.dll
│   │   ├── richtx32.ocx
│   │   └── 真空密码字典生成器2.51.exe
│   ├── 黑刀超级字典生成器.exe
│   ├── 万能钥匙字典生成工具(强).exe
│   └── 亦思社会工程学字典生成器.exe
├── 设备默认密码
│   ├── route
│   │   └── 路由器默认密码.txt
│   ├── 华为
│   │   ├── 华为.png
│   │   ├── 华为产品弱口令.xlsx
│   │   └── 华为安全产品默认用户名密码速查表.xlsx
│   ├── 国内防火墙默认密码.txt
│   ├── 国内外设备默认口令整理.txt
│   ├── 常用运维系统用户名、密码.txt
│   └── 常见安全设备默认口令清单.xlsx
└── 调试辅助字典
    ├── Errors
    │   └── errors.txt
    ├── LFI
    │   └── 常见配置文件目录（249）.txt
    ├── UserAgents
    │   └── UserAgents.txt
    ├── 端口
    │   ├── IoT常见端口_42个.txt
    │   ├── Nmap_Top1000_TCP_Ports.txt
    │   ├── Nmap_Top1000_UDP_Ports.txt
    │   ├── 乌云端口.txt
    │   ├── 常见端口1.txt
    │   ├── 企业常见端口_80个.txt
    │   └── 数据库常见端口_36个.txt
    └── 万能密码
        └── 弱口令万能密码字典.txt
```









# 第一次更新
根据自己习惯做的整合，自用字典，大部分自己做了去重

文件目录
```bash
.
├── CTF_dict
├── IDC密码
├── fuzz_接口
│   ├── api
│   ├── dict_fuzz
│   ├── spring_fuzz
│   └── ssrf_fuzz
├── web目录
│   ├── asp aspx
│   ├── jsp
│   ├── php
│   ├── py
│   ├── tomcat
│   ├── weblogic
│   ├── 后台
│   ├── 备份
│   └── 目录
├── 其它
│   ├── robots
│   │   └── archive
│   │       └── code
│   ├── webshell_pass
│   ├── wifi密码
│   ├── 手机
│   ├── 日期
│   └── 物联网lot
├── 国外
├── 弱口令
│   ├── pass
│   │   ├── TOP
│   │   ├── 常用
│   │   ├── 其它pass
│   │   ├── 综合pass
│   │   ├── 条件字典
│   │   └── 键盘组合
│   ├── user
│   │   ├── TOP
│   │   ├── 其他
│   │   ├── 常见user
│   │   └── 姓名拼音
│   └── 通用 字母数字_拼音
├── 服务爆破
│   ├── Mongodb_login
│   ├── Phpmyadmin_login
│   ├── Postgresql_login
│   ├── Svn_login
│   ├── Tomcat_login
│   ├── Vnc_login
│   ├── Weblogic_login
│   ├── ftp_login
│   ├── memcached_login
│   ├── mysql_login
│   ├── oracle_login
│   ├── rdp_login
│   ├── snmp_pass
│   └── ssh_login
├── 社工字典生成
│   ├── pydictor
│   │   └── pydictor-master
│   │       ├── core
│   │       ├── docs
│   │       │   ├── doc
│   │       │   └── screenshot
│   │       ├── funcfg
│   │       ├── lib
│   │       │   ├── data
│   │       │   ├── encode
│   │       │   ├── fun
│   │       │   └── parse
│   │       ├── plugins
│   │       ├── results
│   │       ├── rules
│   │       ├── tools
│   │       └── wordlist
│   │           ├── App
│   │           ├── IoT
│   │           ├── NiP
│   │           ├── SEDB
│   │           ├── Sys
│   │           ├── Web
│   │           └── WiFi
│   ├── src字典生成
│   │   └── PwdBUD-main
│   │       ├── dict
│   │       └── src
│   │           └── __pycache__
│   └── 白鹿社工字典生成器
│       └── Dic
├── 设备默认密码
└── 调试辅助字典
    ├── Errors
    ├── LFI
    ├── UserAgents
    ├── 端口
    └── 万能密码
```

整合以下前辈的字典与我自己的一些字典：

[https://github.com/c0ny1/upload-fuzz-dic-builder](https://github.com/c0ny1/upload-fuzz-dic-builder)

[https://github.com/danielmiessler/RobotsDisallowed](https://github.com/danielmiessler/RobotsDisallowed)

[https://github.com/danielmiessler/RobotsDisallowed](https://github.com/danielmiessler/RobotsDisallowed)

[https://github.com/3had0w/Fuzzing-Dicts](https://github.com/3had0w/Fuzzing-Dicts)

[https://github.com/TheKingOfDuck/fuzzDicts](https://github.com/TheKingOfDuck/fuzzDicts)

[https://github.com/gh0stkey/Web-Fuzzing-Box](https://github.com/gh0stkey/Web-Fuzzing-Box)

[https://github.com/mstxq17/SeCDictionary](https://github.com/mstxq17/SeCDictionary)


[https://github.com/huyuanzhi2/password_brute_dictionary](https://github.com/huyuanzhi2/password_brute_dictionary)


[https://github.com/ort4u/PwdBUD](https://github.com/ort4u/PwdBUD)


[https://github.com/LandGrey/pydictor](https://github.com/LandGrey/pydictor)