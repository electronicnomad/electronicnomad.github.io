## 클라우드 컴퓨팅의 시작

처음 Compaq이 이것을 내부에서 논의만 했고, 많은 사람들이 정확한 실체 없이 유사 개념을 쏟아내었지만, 실현은 Sun Microsystems가 해 내었다. 하지만, 성공적인 상업화는 Amazon Web Services의 몫이었다. 그리고 여러 사업체들이 한 발, 혹은 여러 발 늦게 시장에 진입했다. 경쟁은 치열해 보였지만, 현재 두각을 나타내는 곳은 Amazon Web Services, Microsoft Azure, 그리고 Google Cloud Platform 정도이다. 

Salesforce.com의 경우는 특화된 business model에서는 독보적 성공을 이루고 있지만, 전반적인 IT 인프라를 아우르지는 못 하기 때문에 논의에서 벗어난다. IBM은 자사의 다양한 software와 hardware를 바탕으로 클라우드 전도사를 자임하며 Softlayer 등의 인수로 의욕을 비추었지만, Bluemix를 거쳐 IBM Cloud라는 브랜드 이름을 정할 때까지도 실체를 확인하기 힘든 지경이다.

아무튼 2017년 겨울, 시장 상황은 이러하다.

### 정의 definition 

클라우드 컴퓨팅은 간단히 소유하지 아니하고 자원을 사용하는 것이다.

#### NIST

클라우드 컴퓨팅에 대한 정의는 NIST의 그것을 대부분 준용(準用)하고 있다.

- [The NIST Definition of Cloud Computing](https://www.nist.gov/publications/nist-definition-cloud-computing)


#### CAPEX to OPEX

소유하지 않기 때문에 사용한 만큼 사용료를 내게 되는 구조이다.
조금 복잡하게 이야기하면, 사용자의 IT에 대한 태도를 '투자비용(capital expenditures)'에서 '운영비용(operational expenditures)'으로 변화시킨 것이다. 


#### 누가 먼저 클라우드 컴퓨팅이란 말을 쓰기 시작했는가?

클라우드 컴퓨팅의 시작은, Compaq의 내부회의(내부회의가 아니면 어디서 시작되었겠는가)라고 알려져 있다. [Who Coined 'Cloud Computing'?](https://www.technologyreview.com/s/425970/who-coined-cloud-computing/) - MIT Technology Review. 그리고 그 회의에서 사용된 [문서](http://www.technologyreview.com/files/74481/compaq_CST_1996.pdf)(PDF)도 아직 남아 있다. 기록은 소중하고, 기록을 보존하는 것은 더 중요하다.

#### CES 2008, 빌 게이츠
지금 돌아보면, [2008년 CES에서 키노트 발표를 한 빌 게이츠의 해안](https://www.youtube.com/watch?v=nknxWKLgKfw)은 더욱 두드러진다 하겠다. 그는 고해상도 영상출력, 엣지 디바이스의 소프트 키와 터치 스크린 그리고 클라우드 컴퓨팅 중심의 혁명을 예고했다. 관련기사: [빌 게이츠 “클라우드 컴퓨팅 혁명 예고”](http://www.sciencetimes.co.kr/?news=%EB%B9%8C-%EA%B2%8C%EC%9D%B4%EC%B8%A0-%ED%81%B4%EB%9D%BC%EC%9A%B0%EB%93%9C-%EC%BB%B4%ED%93%A8%ED%8C%85-%ED%98%81%EB%AA%85-%EC%98%88%EA%B3%A0)
클라우드 컴퓨팅이라는 용어를 본격적으로 업계가 받아드린 시점도 바로 이 키노트였다고 난 판단한다.

### Players

클라우드 컴퓨팅 시장에서는 Amazon Web Services, Microsoft Azure, Google Cloud Platform 그리고 Salesforce.com이 선두에서 각 분야에서 두각을 나타내고 있다. Softlayer에서 Bluemix로 다시 IBM Cloud로 이름 변경에만 신경을 쏟은 그들이 여전히 검토할만한 대안으로 자리하고 있으며, 한정적 시장에서 그들만의 리그를 만들고 있는 Alibaba Cloud도 괜찮은 매출을 기록하고 있다고 한다. Rackspace, Joyent 등 다른 업체는 시장의 판도를 변화시킬 만한 동력이 있어 보이지는 않는다.

AWS는 함께 시장을 개척한 Sun Microsystems의 퇴장 이후 독보적인 존재감을 여전히 드러내고 있다. 하지만, 그들의 힘은 전통 IT 인프라의 전환(transformation)에 그치고 있어 미래를 장담하기 힘들다. Microsoft Azure는 한 차례의 각성 이후 자신들만의 길을 찾은 것 같다. PaaS와 Networking 그리고 운영체제, 개발도구에서부터 Productivity Software까지 진정한 클라우드 컴퓨팅의 A2Z를 보유한 유일한 업체로 Synerge에 정성을 쏟았고, 결과가 들어나는 중이다. GCP는 뚜렸한 성장세를 유지하고 있다. 이렇게 3개의 업체가 시장의 방향을 결정한다고 말해도 과언은 아니다.

## the Next 

Microsoft는 다른 사업자와는 조금 다른 시각으로 클라우드 컴퓨팅을 바라봤다. 처음부터는 아니었겠지만, Windows Azure에서 Microsoft Azure로 재명명할 무렵과 클라우드 컴퓨팅에 대한 새로운 접근이 시작될 때가 비슷한 시기였다. 그 모토는 infrastructure as a code이다.

### 옛것의 퇴장과 퇴장하지 않을 것들의 부각

클라우드 컴퓨팅의 이상은 (어쩌면) [the Network is the Computer](https://en.wikipedia.org/wiki/John_Gage)에서 찾아야 할지도 모르겠다. Sun Microsystems는 자유로운 네트워크 접속이 가능한 워크스테이션을 최초로 상용화하여 판매하였고, 모든 기술의 중심에는 '네트워크'가 가능한 시스템 개발에 있었다. UUCP, 진보된 TCP/IP, NFS, YP 혹은 LDAP 등 지금도 누리고 있는 기초적인 네트워크 구성들은 눈부실 정도이다. 또한 Java 또한 그런 network computing의 한 가닥으로 해석해도 괜찮을 듯 하다. Sun Microsystems가 선보인 network computing의 첫 결실은, [Sun Ray](https://en.wikipedia.org/wiki/Sun_Ray) 시리즈라고 평가할 수 있고, 두 번째 결실은 [network.com](https://en.wikipedia.org/wiki/Sun_Cloud) 으로 알려진 최초의 클라우드 컴퓨팅의 상용 모델일 것이다. 

> 아직 난 집 구석에 Sun Ray 1, 1g 그리고 2를 가지고 있다. 사실 난, Sun SPARCstation 5와 Sun Ultra 60 3D Creator도 가지고 있다. (아직 전기만 넣어주면 잘 돌아간다, SCSI 디스크의 특유한 굉음은 덤이다)

network.com의 결실 중에 아직도 open source 진영에서 흔희 사용하는 영상인, Big Buck Bunny가 있다.


