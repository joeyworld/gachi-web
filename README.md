# Gachi - web

## 사이트 URL
(아직 배포를 안 올려놔서 로컬에서 무조건 진행현황을 보셔야 할 것 같아요)

## 같이 작업할 때

Git을 설치해 주세요. 그 다음,

```
$ git clone https://github.com/bbjmining/gachi-web
```

해당 명령어로 이 레포를 클론하시면 소스 코드를 내려받으실 수 있어요.  

다음에는 가상 환경을 만들어주셔야 해요. 가상 환경 만드는 방법 다 아시죠?  
가상 환경 만드셨으면 필요한 패키지(장고 등) 을 설치해주셔야 되는데, 
```
$ pip install -r requirements.txt
```
명령어로 설치를 해 주시면 됩니다!

## 작업 후에 변경 사항 적용하실 때

GitHub 에 보면 `branch` 가 있는데, 새로운 브랜치를 꼭 만드셔서 해당 브랜치에다 변경사항 적용하신 후에, PR 날려주시면 제가 머지(merge) 하는 식으로 하겠습니다.  
**절대로** `master` 브랜치에 바로 커밋하지 말아주세요! 변경사항이 다 날라갈 수 있어요.