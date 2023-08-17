git hub 특강 리뷰

git 등록

```git init```

git hub 원격 저장소 생성
- new repository
- 주소생성 https://github.com/JsLeelee/"프로젝트이름"
- 이후 버전 관리

git hub 원격저장소 연동

```python
 git remote add origin <원격 저장소 URL>
```

git 커밋

```python
git add . #저장
git commit -m "커밋 메시지" #메세지 기록

```

git 푸시

```python
git push origin 브랜치 # 브랜치설정은 git branch <브랜치이름>
```

git 머지
```python
git checkout 브렌치 이름(sub) #타겟을 메인에 병합 것을 지정
git merge 브랜치 이름(main) #메인으로 합치기
```

git 포크
- 프로젝트 포크
- 개인이 프로젝트 수정
- 깃에 저장 후 원작자에게 리퀘스트

깃 이외에 여러것들

- chatgpt의 중요성을 알게됨
- 프로젝트의 순서도와 현업에서 어떻게 가는지 알 수 있었음
- 내용이 어렵지 않고 따라가기 쉬웠음