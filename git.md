# Git

1. 저장소 (repository) 만들기 - git이 관리하는 폴더 (directory)

   ```bash
   $ git init
   ```

2. 파일을 스테이징하기

   ```bash
   $ git add 파일명
   ```

3. 파일을 커밋하기

   ```bash
   $ git commit -m '커밋할 메세지 내용 (변경사항 요약 기록)'
   ```

- 상태 확인하기

  ```bash
  $ git status
  ```

- 내가 누군지 정보 입력하기

  ```bash
  $ git config --global user.name 유저이름
  $ git config --global user.email 유저이메일
  ```

- 커밋 기록 확인하기

  ```bash
  $ git log --oneline (옵션)
  ```



## 원격(remote) 저장소

- github - 무료, 개인

- gitlab(SSAFY) - 유료, 회사, 조직

  폴더 (respository) 단위로 관리됨



원격 저장소를 지정: origin이라고 하겠다 그 주소는 https://github.com/dk-yoon/TIL.git

```shell
$ git remote add origin https://github.com/dk-yoon/TIL.git
```

