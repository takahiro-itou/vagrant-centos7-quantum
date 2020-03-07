
# vagrant-centos7-quantum

## 準備

ボックスを作成しておく
- https://gitlab.com/takahiro-itou/vagrant-box-centos7-quantum
- vagrant box list を実行して takahiro-itou/centos7-quantum が入ってれば OK.

```bash
vagrant box list
(snip)
takahiro-itou/centos7-quantum (virtualbox, 0)
```

## クローン

```bash
git clone https://gitlab.com/takahiro-itou/vagrant-centos7-quantum.git
cd  vagrant-centos7-quantum
```

## 実行

```bash
cd vagrant/
vagrant up
```

## ログイン

```bash
vagrant ssh
```
