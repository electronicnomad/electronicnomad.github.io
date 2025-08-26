---
layout: post
title: Veo 데모, 동일한 프롬프트를 사용하여 모델(버전)별 결과 비교.
author: 주인장
tags:
- veo
- GenAI
- AI
- testing
- generative
- gemini
- demo
---

Veo 데모, 동일한 프롬프트를 사용하여 모델(버전)별 결과 비교.

# Veo를 테스트했던 목적

저는 엔터테인먼트 업계의 한 고객사에 Official Visualization이라는 
카테고리의 뮤직비디오를 만드는 작업에  Veo의 사용을 제안했습니다. 
Veo는 매우 적합해 보이는 솔루션이었고 실제 전문 제작사에 비해서 
절대적으로 낮은 가격으로 짧은 시간에 레이블이 원하는 결과를 얻기에 충분하다고 판단했습니다.

아래의 5가지 프롬프트로 데모를 만들어 최상위 의사결정자들과 프로덕션 
그리고 IT 필라에 속하는 고객들에게 선보였습니다.
선보인 결과는 첫번째 Veo의 0815 모델로 제작했습니다.

그리고 그 이후, Veo 2, Veo 3로 발전되면서 같은 프롬프트를 입력하면 
어떤 차이가 만들어 졌는지 공유하며 저의 경험을 나누고 싶습니다.

# Veo의 데모 비디오들

### 사용한 프롬프트들

- A wide shot of a lone person riding a classic motorbike across a vast, sun-drenched prairie, with a dramatic sky filled with fluffy clouds in the background. The person is silhouetted against the setting sun, creating a sense of epic scale and adventure.

- A low-angle shot of a person stepping into a room, with the doors closing behind them, creating a sense of anticipation and mystery. The focus is on the person's silhouette against the bright light from the hallway, emphasizing the contrast between the enclosed space and the open world beyond. 

- A hand runs through the soft dirt, before reaching over with a spade and digging. The hands place a small flowering plant in the hole and cover it up. They pat the soil around the plant until it is firm.

- Two young men sit on a bench in a lively marketplace, each holding a cup of coffee in take-out type and engaged in a conversation. One man, with dark skin, a strong jawline and a serious expression, wears a green shirt, while the other man, with light skin, a friendly smile and stylish hair, wears a white polo. Intimate close-up shots, lit with soft, natural light, alternate between the men's faces, their expressions revealing the delicious conversation about chocolate. Award winning advertisement, cinematic style, in focus, both are in screen.

- a member of a \{ girl \| k-pop \} group looks at the camera, speaking with a serious expression on her face.

## Motorbike | 이륜차

*Prompt: A wide shot of a lone person riding a classic motorbike across a vast, sun-drenched prairie, with a dramatic sky filled with fluffy clouds in the background. The person is silhouetted against the setting sun, creating a sense of epic scale and adventure.* 

<hr />
- Veo-Preview-0815
{% include youtube.html id="QLgVPWDGoj4" %}
<hr />

- veo-2.0-gnerate-002
{% include youtube.html id="mYU53MRt3z0" %}
<hr />

- veo-3.0-generate-preview 
{% include youtube.html id="iJmLHMRJFp8" %}
<hr />

Veo 1(Veo 1이라는 명칭은 공식적으로 존재하지 않지만, Veo 2와 Veo 3와 구분하기 위하여 사용하겠습니다)에서 가장 쉽게 결과를 얻을 수 있었던 프롬프트입니다. 그리고 가장 극적인 연출이 있었기에 매우 만족할 수 있었습니다.

Veo 2는 Veo 1에 비하여 상대적으로 고배율 렌즈를 사용하는 느낌이었습니다. Veo 1이 24mm 광각렌즈라면, Veo 2는 50mm 표준렌즈를 쓰는 느낌이었습니다. 

Veo 3는 대부분 첫 시도에서 상당히 만족스러운 결과를 얻을 수 있었다는 점이 놀라웠습니다. 

## A person stepping into a room | 방 안으로 걸음을 옮기는 사람

*Prompt: A low-angle shot of a person stepping into a room, with the doors closing behind them, creating a sense of anticipation and mystery. The focus is on the person's silhouette against the bright light from the hallway, emphasizing the contrast between the enclosed space and the open world beyond.*

<hr />
- Veo-Preview-0815
{% include youtube.html id="VkevA9MpbrE" %}
<hr />

- veo-2.0-gnerate-002
{% include youtube.html id="ZWet7XY1iKY" %}
<hr />

- veo-3.0-generate-preview 
{% include youtube.html id="pxcFdJ9ppb4" %}
<hr />

시네마틱 연출의 예로 아주 좋은 것이라 생각하고 도전을 했지만, Veo 1에서는 정말 헤아릴 수 없을 만큼 많은 시도가 필요했습니다.

하지만, Veo 2 그리고 Veo 3로 가면서 원하는 것을 얻을 수 있는 확률은 매우 높아졌습니다. Veo 3는 해당 영상을 첫 프롬프트로 얻었습니다. 

대부분의 Veo 1에서는 최소 서른 번 넘게 시도 했었다는 기억이 있고, Veo 2는 10회 내외, Veo 3에서는 1회에서 3회 안에 원하는 것을 얻을 수 있었습니다. 모델의 발전은 여기에서 찾을 수 있겠습니다.

하지만, 시도 횟수라는 것은 개개인이 원하는 목표에 따라서 큰 차이가 있을 수 있겠습니다. 제가 강조하고 싶은 건은 비교적 균등한 결과를 얻는데 소요된 재시도 횟수 정도로 평가해 주시면 좋겠습니다.

## A hand runs through the soft dirt | 부드러운 흙 위로 손이 움직인다

*Prompt: A hand runs through the soft dirt, before reaching over with a spade and digging. The hands place a small flowering plant in the hole and cover it up. They pat the soil around the plant until it is firm.*

<hr />
- Veo-Preview-0815
{% include youtube.html id="KBDTzHZI_b8" %}
<hr />

- veo-2.0-gnerate-002
{% include youtube.html id="EENGerYMiWw" %}
<hr />

- veo-3.0-generate-preview 
{% include youtube.html id="61VtEBSdGGQ" %}
<hr />

Veo 1이 처음 선보였을 때, 사람의 손이 나오는 데모를 반드시 만들어 보고 싶었습니다. 당시 사람의 손가락을 Gen AI가 표현하는 (영상이든 사진이든) 데에 어려움을 겪고 있었을 때였습니다.

전 이 영상을 만들었을 때 오로지 사람의 손가락 표현이 얼마나 정교한지에 대하여 보여주고 싶었습니다.

## Two young men | 젋은 두 남자들 

*Prompt: Two young men sit on a bench in a lively marketplace, each holding a cup of coffee in take-out type and engaged in a conversation. One man, with dark skin, a strong jawline and a serious expression, wears a green shirt, while the other man, with light skin, a friendly smile and stylish hair, wears a white polo. Intimate close-up shots, lit with soft, natural light, alternate between the men's faces, their expressions revealing the delicious conversation about chocolate. Award winning advertisement, cinematic style, in focus.*

<hr />
- Veo-Preview-0815
{% include youtube.html id="PXr4pHAmP68" %}
<hr />

- veo-2.0-gnerate-002
{% include youtube.html id="k11X7gXefLU" %}
<hr />

- veo-3.0-generate-preview 
{% include youtube.html id="V_RvGufnxx0" %}
<hr />

Veo 2에서 선보인 도전 중에 (짧은 시간 내이지만) 카메라 앵글을 다양하게 연출한다는 것이다. 그리고 앵글이 바뀌는 과정이 매우 자연스럽고, 바뀌기 전과 비교해서도 어색함이 전혀 없다는 것에 감탄할 수 있었습니다.

Veo 3에서 음향이 지원되는 것이 엄청난 발전 중에 하나였는데, 위 영상에서 확인할 수 있는 것과 같이 매우 자연스러운 대사를 화면 속 생성된 대상과 맞추어 연출해 주는 것은 놀라울 정도였습다.

## A member of a k-pop group | 케이팝 그룹 맴버 

*Prompt: a member of a girl group looks at the camera, speaking with a serious expression on her face.*

<hr />
- Veo-Preview-0815
{% include youtube.html id="i8-rFj6sdJc" %}
<hr />

- veo-2.0-gnerate-002

  해당 프롬프트로 Veo 2에서는 영상을 만들 수 없었습니다. 그래서, 위 프롬프트로 Imagen에서 이미지를 생성하고, 생성한 이미지를 Veo 2에 입력하여 영상을 만들었습니다.

{% include youtube.html id="YCI8c8gVzBM" %}
<hr />

- veo-3.0-generate-preview 
{% include youtube.html id="LQRGDAe_vRU" %}
<hr />

Veo 1에서 영상 생성 테스트를 진행했었을 때, 이 결과를 얻고 가장 만족했습다. 물론, 엄청난 횟수의 시도가 있었지만, 화면 속 인물의 얼굴 근육까지 표현되었다는 점, 그리고 짧은 프롬프트에서 매우 충실한 결과를 출력했다는 점, 그리고 girl group이라는 표현을 이해했다는 점에서 좋았습다.

하지만, girl group이라는 표현은 Veo 2부터 사용할 수 없었습다. 시스템에서 받아 들이지 않았습다. 하지만, Veo 3에서는 k-pop group으로 인식된 것에 비해,  Veo 2는 k-pop group이라는 표현도 부적절한 것으로 취급했습다.

Veo 2는 여러 면에서 매우 특이했는데, 마치 Veo 1에서 발전해 온 것이 아니라, 전혀 다른 프로젝트의 결과인데 이름은 승계한 느낌이 강했습다. 더군다나 이 모델은 ‘다양성’을 표현해 내려고 하는 의도가 매우 강해서 입출력에 제한이 많은 것도 있었고, 의도와는 다른 결과를 꼭 하나씩 후보로 출력해 주는 것도 있었습니다.

Veo 3는 음성 출력까지 모든 것이 만족스러웠는데, 다만 저 출력되는 대사는 여러차례 재시도를 해도 같았다는 점이 신기했습니다. 그리고 제시된 프롬프트가 아티스트를 인터뷰하는 순간으로 해석한 것이 좋았습니다. 

# 총평

- Veo 1은 당신의 기억보다 멋진 모델이었다.
- Veo 2는 사회적 문제가 없는 결과를 출력하기 위해 노력했다. 
- Veo 3는 그 다음은 무엇일지 궁금하게 만들었다. 놀라웠다.

Veo 1에서는 프롬프트를 얼마나 정교하게 다듬어서 입력하느냐 혹은 Veo 1과 사용자 사이에 필요한 적당한 대화법을 찾는 시간이 매우 길었습니다. 위 영상 중 어떤 것 하나는 약 100회 이상의 프롬프트 수정 포함하여 새로운 후보를 기대하며 재시도를 했던 기억이 있습니다. Veo 1과 대화법을 알게 된 이후 얻게 되는 영상의 질은 기대보다 나았습니다.

Veo 2는 다양성과 정치적 올바름에서 벗어나지 않기 위해 안간힘을 쓰는 듯 한 기분이 들었습니다. 그리고 ‘안전한’ 결과를 얻기 위해서인지 알 수는 없지만, 프롬프트의 특정 단어 등에 제한이 상대적으로 강했습니다. 하지만, 영화적 연출은 Veo 2가 최고였습니다.

Veo 3는 Veo 1에서 도저히 결과로 출력할 수 없을 것 같은 프롬프트도 사용자의 의도에 가깝게 출력해 주는 것을 볼 수 있었습니다. Veo 3의 여러 눈부신 발전 중에 가장 크게 만족스러웠던 것은 바로 이 부분이었습니다.

Veo 모델의 버전이 올라가면서 사용자가 체감하는 발전 중에 최고의 하나를 선정한다면 - 점점 더 적은 횟수의 시도로 의도에 가까운 결과를 얻을 수 있었다는 점이라고 할 수 있겠습니다.

### 그리고 뭣 좀 더 ... 

개별 영상들은 모델별로 playlist를 만들어 YouTube에 게시해 두었습니다. 그 playlists는 다음과 같습니다.

- [Veo Demo (Preview 0815)](https://youtube.com/playlist?list=PLErlU15VorUhIAtp6WSgCg-6PxkWSmJpI&feature=shared) - Veo-Preview-0815
- [Veo 2 Demo](https://youtube.com/playlist?list=PLErlU15VorUgeA5miJR7rc5iE1MeRxVyI&feature=shared)  veo-2.0-generate-002 
- [Veo 3 Demo](https://youtube.com/playlist?list=PLErlU15VorUi_0LeCtQzp_Db87Zh3IYwz&feature=shared)  veo-3.0-generate-preview
