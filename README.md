# Chaitin-SafeLine-Plugin

雷池Waf插件

--- 

## 检测真实攻击者IP

lua语言（5.1）编写；

适用于10、20版本，针对XXF多IP导致Waf无法识别源IP的情况，默认只检测高危行为IP。在记录IP的同时也会记录攻击类型。

### 可添加白名单（在white_list中加入）

如果白名单为空，则默认匹配所有的外网攻击者IP。

如有BUG可以提Issues，不定期修复；

