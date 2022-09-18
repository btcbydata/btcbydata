# btcbydata (성균관대 이지훈 졸업작품)
[웹페이지 바로가기](https://btcbydata.ga/)

## 기획의도
> 처음 프로젝트를 계획했던 2021년 1월 당시는 암호화폐 등에 대한 관심이 최고조에 달한 시기였습니다. 기존 자산과는 달리 비교적 새롭고 인터넷 기술을 기반으로 했다는 암호화폐의 특성 상, 관련 커뮤니티가 활발하게 활성화되었고 많은 글이 올라오고 있었습니다. 특히 실시간으로 값이 변화하는 과정이 인터넷 게시판 글을 통해 그대로 표출되고 있었는데, 그렇다면 반대로 인터넷 커뮤니티의 텍스트를 분석해서 암호화폐의 변동을 추적하고, 더 나아가 값을 예측하거나 적어도 특정 암호화폐에 대해 가격 추천을 하는 시스템을 구현할 수 있지 않을까 싶어 프로젝트를 시작했습니다. 지금은 다소 그 열기가 줄어들어 분석하고 가공할 실시간 텍스트의 양은 적어졌지만, 그래도 과거의 수많은 텍스트가 여전히 존재하기에, 이를 응용해 추천 시스템을 만들어 웹 사이트를 통해 제공하고자 합니다. 
>  

## 목표
> 크롤링된 암호화폐 커뮤니티 게시판의 텍스트 분석을 통한 암호화폐 추천 웹을 개발합니다. 해당 기능의 통계적 배경을 설명하는 별도의 페이지와, 실시간 암호화폐 시세를 띄워주는 테이블도 구현합니다. 


## 저장소 구조 
> [simplescraper](https://github.com/btcbydata/simplescraper) : 인터넷 커뮤니티 텍스트 크롤러, node.js 및 python 구현 
> 
> [btcbdfront](https://github.com/btcbydata/btcbdfront) : btcbydata의 웹 프론트엔드, vue.js 및 firebase 구현
>
> [nlpmodule](https://github.com/btcbydata/nlpmodule) : 자연어처리 관련 python 프로그램들 
>
> [tempfront](https://github.com/btcbydata/tempfront) : 임시 작업 공간



## github 관리 방침
> 각 저장소별 readme.md와 체계적으로 정리화된 commit 메세지를 통해서 보는 사람으로 하여금 작업 과정을 투명하게 알 수 있도록 하겠습니다. 
