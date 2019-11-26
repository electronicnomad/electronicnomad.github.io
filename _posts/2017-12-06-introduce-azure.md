---
layout: post
title: Microsoft Azure 간단 설명
author: Kwanghoon Jhin
---

Microsoft Azure에 대한 짧은 이야기 (오류를 포함하고 있을 가능성을 배제할 수는 없습니다)

### 먼저
Microsoft Cloud = Azure라고 보는 건 약간의 오류가 있다. 합집합이 아니다. Microsoft Cloud라 함은 Office 365, Microsoft 365, Dynamics 365 등과 Azure를 함께 포함하여 말한다. 그래서 Azure는 Microsoft Cloud의 한 부분이라고 생각하는 것이 맞겠다.

### 의미있는 변화
現 Microsoft Azure는 2010년 2월 1일 정식 서비스를 시작했다. 그 때 이름은, Windows Azure였다. 거창한 시작과는 다르게, 시장의 반응은 냉담하였고, Microsoft도 '거대한' 투자를 하겠다고 했지만, 적극적이지 않았다. 이 상황이 전환된 계기는, 現 Microsoft CEO, [Satya Nadella](https://en.wikipedia.org/wiki/Satya_Nadella)의 등장이라고 할 수 있다. Satya Nadella는 2014년 2월 4일 공식적으로 CEO로 취임하면서 Microsoft는 일대 대전환기를 맞는다. 

사실상, Microsoft는 Satya Nadella의 이전과 이후로 나누어 평가할 수 있으며, 지금까지 우리가 알고 있던 Microsoft는 [Steve Ballmer](https://en.wikipedia.org/wiki/Steve_Ballmer)의 퇴장과 함께, 혹은, Satya Nadella의 등장과 함께 사라졌다고 봐도 무관하다.

現 CEO 취임 두 달 남짓한, 2014년 3월 35일 Windows Azure는 Microsoft Azure로 재명명(再命名)되었다. 그리고 Azure는 종례의 '내가 법을 만드니 넌 그냥 쓰면 됨'에서 본격적인 '고객이 원하신다면 뭐든 제공해 드립니다' 자세를 취하기 시작했다. Linux와 Open source communities에 대한 구애는 이 때부터라고 봐야 한다.

Microsoft Azure는 짧은 기간 급속 성장을 이루고 있으며, 현재 전세계 42개 [regions](https://azure.microsoft.com/en-us/regions/)를 보유하고 있다. 이는 경쟁사 비하여 2배에서 7배 많은 수이다. 

### 표기
Azure는 Azure로 표기한다. 세상 모든 언어에서도 Azure로 표기한다. 따로 다른 언어로 번역하여 적지 않는다. Microsoft도 공식적으로는 세상 모든 언어권에서 그냥, Microsoft로 적는 것을 원칙으로 하고 있다.

### 발음
Azure는 /애-저:/로 발음한다고 한다. 하지만, 많은 사람들이 /애-저:/라고 발음하지 않더라. 이웃나라에서는 /애주-라/, 유럽쪽 어디에서는 /아주-라/ 그리고 어떤 사람은 애주르 또는 /아주-ㄹ/라고도 하더라. 아무튼, 의도하고 있는 발음은 /애-저:/라고 한다.

공료롭게, 우리나라에서 '애저'라고 하면, 돼지 猪자를 쓰는 '애저'가 있다. (태어나기 전의) 새끼[애] 돼지[저]를 지칭하는 단어인데, 요리와 음식에서 쓰이는 말로, Azure와는 이미지가 전혀 다른 동음이의어가 되겠다. 애저구이와 애저찜이 대표적인 요리이다.

### 리전 Regions 이름 
Microsoft Azure의 regions의 이름을 보면, 초기 Azure에 대한 사업을 구상한 사람들이 全세계적인 혹은 전세계 곳곳에 진출하는 서비스를 염두해 두지 않았다는 것을 알 수 있다. 다음을 보자, Azure regions 이름과 지역 위치 정보이다. 출처: [Azure locations](https://azure.microsoft.com/en-us/global-infrastructure/locations/) 

| Region Name | Location |
|-------------|----------|
| East US | Virginia |
| West US | California |
| Central US | Iowa |
| North Europe | Ireland |
| West Europe | Netherlands| 
| East Asia | Hong Kong |
| Southeast Asia | Singapore |

Windows Azure 시절의 초기 regions의 이름은 위와 같았다. 뭔가 확장 가능한 명명방식은 아니라는 것이 느껴질 것이다, 그저 영미권으로 대표되는 서양의 주소형식과 닮아 있다. 이후, 다음과 같은 이름으로 regions가 발표 되었다.

| Region Name | Location |
|-------------|----------|
| Korea Central | Seoul |
| Korea South | Busan |
| Japan East | Tokyo |
| UK South | London |
| Germany Central | Frankfrut |
| France Central | Paris |

한 번 정해진 region의 이름을 변경하는 것은 혼란스러운 일일 것이다, 그래서인지 예전에 명명된 regions의 이름은 그대로 유지하고 있다. 이제는 두 가지 명명방식의 region 이름이 공존하고 있다. 아래의 것, 그러니까 현재의 명명방식이 바르다.

### 데이터센터

Microsoft는 풍부한 자본력을 바탕으로 대지를 매입해서 터를 마련하고 데이터센터를 건립하고 설비를 갖추고 region을 출시하는 것을 원칙으로 하고 있다. 그럴만한 대지가 없으면 현지 통신사업자의 시설을 임대한다. 다른 사업자들은 자사의 데이터센터에 고객이 방문하는 것을 허락하지 않지만, Microsoft는 투어 프로그램을 가지고 있다. Azure의 데이터센터가 궁금하면 담당자를 통해서 예약하고 방문할 수 있다. 무언가에 대한 강력한 자신감이라고 해석할 수도 있겠다.

### 주소
공식적으로 Microsoft Azure의 웹 주소는 [azure.com](http://azure.com)이다. azure.com은, [azure.microsoft.com](http://azure.microsoft.com)으로 연결된다. 실제 사용자가 리소스와 서비스를 제어하는 곳은 Azure Portal이라고 부르며, [portal.azure.com](http://portal.azure.com)이라는 주소를 가지고 있다.

### 로고 
![Azure Logos - Old and New](/media/common/azure_logos.png){: height="150px" style="float:right; padding:5px"}

2017년 9월 25일 Microsoft Ignite 2017 행사 중에 Azure의 로고가 변경되었다는 것을 시중에 알렸다. 그리고 [Azure Manifesto도 YouTube를 통해 공개](https://youtu.be/05935OAqxJQ)하였는데, 이 두가지 사실을 모두 아는 사람은 드물다. Azure Manifesto는 업로드된 2017년 9월 25일부터 이 글을 적고 있는 2017년 11월 6일까지 7,902 회 조회되었다. 

### 조금 다른 점
Azure는 한 지역에 2개의 region을 동시에 선보인다. 이를 paired region이라고 부르는데, disaster recovery, availablity 등을 보장하기 위한 설계 철학이다. 초기에는 AWS나 GCP가 가지고 있는 Availablity Zone이라는 것을 철저하게 무시했다. 대신 Availablity Set이라는 개념으로 시장에 호소했지만, 반응이 그렇게 좋지는 않았다. 만약 태초에 Microsoft Azure의 Availability Set이 있었고, 시장을 선도했다면 AWS와 GCP의 Availability Zone은 웃기는 이야기가 되었을 것이지만, 현실은 달랐다. 결국 Microsoft Azure도 Availability Zone을 도입했고, Availability Set과 함께 공존하고 있다. 물론, paired region도 유지하고 있다. 결과적으로 지구상의 클라우드 사업자들 중에서 가장 높은 가용성을 제공하는 회사가 되었다.

