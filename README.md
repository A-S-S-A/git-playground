# Git 놀이터
Git 사용법 연습을 위한 공간

## 규칙
1. 사회적 미풍양속에 반하는 내용은 올리지 않기
    - 여기 이용자 중 군인도 있다는 사실을 명심하십시오
    - 참고로 데이터센터 서울에도 있습니다
2. 커밋을 푸시할 때 `git push --force`는 되도록 사용하지 않기
    - 나중에 커밋 히스토리 꼬여서 가지고 놀기 불편해집니다
    - 다른 사람이 나중에 에러 난다고 할 때 자기가 고쳐줄 거 아니면 하지 마세요
3. 이 README 파일은 건드리지 않기
    - ㄹㅇㅋㅋ 추가하겠다고 리드미 건드리면 안됩니다 어차피 오토 돌릴 거거든요
    - 대신 내가 ㄹㅇㅋㅋ 대신 써 줌 **_ㄹㅇㅋㅋ_**
4. 본인의 흑역사가 될 만한 내용은 쓰지 않기
    - 이거 `git push --force`로 커밋 덮어써도 커밋 리스트는 지워지지 않습니다
    - 즉 흑역사 삭제가 안 되니 알아서 잘 생각하십시오

## 사용법
1. 이 리포지토리를 클론한다
``` sh
# 2FA 설정 안 한 경우
git clone https://github.com/A-S-S-A/git-playground

# 2FA 설정한 경우
git clone git@github.com:A-S-S-A/git-playground
```
2. 리포지토리에 파일을 추가, 삭제, 변경한다
``` sh
echo "Hello, world!" > helloworld.txt
```
3. 커밋하고 푸시한다
``` sh
# 커밋할 파일 추가
git add <커밋할 파일>

# 통째로 추가하려면
git add --all

# 커밋 ㄱㄱ
git commit -m "<커밋 메시지>"

# 깃허브로 푸시
git push
```

이 이외에 [이슈를 생성하거나](https://github.com/A-S-S-A/git-playground/issues/new) 아니면 [풀 리퀘스트를 올리거나](https://github.com/A-S-S-A/git-playground/compare) 해서 아무렇게나 쓰시면 됩니다. Git 사용법을 모르겠으면 구글한테 물어보시고 알아서 공부하십시오...
