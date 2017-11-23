# 自分用ansible

- 以下で実行（iでホストファイル指定、uはユーザー名、Kはsudoのパスワード指定（sudoになるためのパスワードがないならいらない））

```bash
$ ansible-playbook -i hosts default.yml -u keisuke -K
```
