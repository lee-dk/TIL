# Branch

## 1. Branch basic command

> - 브랜치 생성
>
> ```shell
> (master) $ git branch [branch name]
> ```
>
> - 브랜치 이동
>
> ```shell
> (master) $ git checkout [branch name]
> ```
> - 브랜치 생성 및 이동
> ```shell
> (master) $ git checkout -b [branch name]
> ```
>
> - 브랜치 목록
>
> ```shell
> (master) $ git branch
> ```
>
> - 브랜치 삭제
>
> ```shell
> (master) $ git branch -d [branch name]
> ```

## 2. Branch merge

- 각 branch작업을 한 이후 이력을 합치기위해 일반적으로 merge명령어를 사용한다.

  병합을 진행할 때, 만약 서로 다른 commit에서 동일한 파일을 수정한 경우 충돌이 발생할 수 있다.

  이 경우에는 반드시 직접 수정을 진행해야 한다.



