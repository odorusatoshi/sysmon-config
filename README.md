# sysmon config 参考
- 本家SwiftOnSecurityのsysmon-configにSplunk関連のProcessCreationのみ除外(exclude)したものを用意
- 4.3以降は、olafhartong/sysmon-modularのルールを一部参考

# sysmon-configの元Version
- 4.5 (EventCode=23,24,25対応)
- 4.3 (EventCode=22対応)
- 4.0

config適用するとsplunk関連の起動プロセスのログが記録されなくなります。
