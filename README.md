# GitHub 실습 가이드 📘

이 저장소는 GitHub의 기본적인 기능인 커밋, 머지, 브랜치를 연습하기 위한 가이드입니다. `test.txt` 파일을 사용하여 각 기능을 실습해 보겠습니다.

## 시작하기 전에 🚀
- 이 저장소를 자신의 계정으로 포크(Fork)하세요.
- 포크한 저장소를 자신의 로컬 컴퓨터로 클론(Clone)합니다.

`git clone <https://github.com/yeajongcheol/GitPractice>`

## 브랜치 생성 및 변경사항 적용하기 🌿

1. 새로운 브랜치를 생성합니다.
`git branch new-branch`

2. 생성한 브랜치로 이동합니다.
`git checkout new-branch`

3. 'test.txt' 파일을 열고 추가적인 내용을 기록합니다.
   
4. 변경사항을 커밋합니다.
`git add test.txt`
`git commit -m "Add more text to test.txt on new-branch"`

5. 변경사항을 원격 브랜치에 푸시합니다.
`git push --set-upstream origin new-branch`

## 머지하기 🔄

1. 'master' 브랜치로 이동합니다.
`git checkout master`

2. 새로운 브랜치의 변경사항을 master 브랜치에 머지합니다.
`git merge new-branch`

3. 머지된 변경사항을 원격 저장소에 푸시합니다.
`git push`

## 완료 🎉
여기까지 브랜치 생성 및 머지 기능을 연습해 보았습니다. 

## ❓참고자료
[ㄹㅇ 쉬운 깃허브 협업하기](https://youtu.be/IT41djAKUgg?si=kClqgFkmkP0eSEFD)


