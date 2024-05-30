# Github CLI

## Github CLI Login

```bash
$ gh auth login
```

## Generate SSH key using CMD

```bash
$ mkdir .ssh
$ cd .ssh
$ ssh-keygen -t rsa -b 4096 -C "your-email@example.com"
```

id_rsa.pub 파일에 있는 텍스트를 모두 복사해서 Github SSH key에 등록한다.

## Clone Repository

```bash
$ gh repo clone repository-name
```
