# programming-playground

## Rust 설치


Linux에서 rustup 러스트 버전 및 러스트 관련 도구 관리 커멘드 라인 도구 설치 방법

```bash
$ curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh
```

업데이트

```bash
$ rustup update
```

삭제 방법

```bash
$ rustup self uninstall
```

rustc 설치 방법

```bash
$ rustc main.rs

Command 'rustc' not found, but can be installed with:
sudo snap install rustup  # version 1.29.0, or
sudo apt  install rustc   # version 1.75.0+dfsg0ubuntu1-0ubuntu7.4
sudo apt  install rustup  # version 1.26.0-5ubuntu0.1
See 'snap info rustup' for additional versions.
```
