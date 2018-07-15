[180715 케블리 활동 글 초안]


# [케블리] #57. 블록체인 시대의 UX(User Experience) - "신뢰"를 디자인하기

일전에 코드박스 컨퍼런스를 갔다온 적이 있습니다. 코드박스는 세계 최초로 구글 플레이, 애플 앱스토어에 동시 출시한 블록체인 게임인 고크립토봇(GoCryptobot)의 개발과 서비스 과정에서 배운 교훈에 대해 발표했습니다. 그 중 가장 인상깊었던 교훈은 다음과 같습니다.
<br>
<br>


![codebox](https://user-images.githubusercontent.com/36020880/42731612-a4de9f24-884b-11e8-9eda-0c5041c1198c.png)
\[코드체인 커넥트 제2회 코드박스 블록체인 컨퍼런스 : “Blockchain games and GoCryptobot: lessons learned"]
<br>
<br>

> UX(user experience)는 경제적 유인보다 훨씬 더 중요하다.

결국, 블록체인이라도 프로덕트를 잘 만들어야 토큰 이코노미나 거버넌스 같은 체제가 작동할 수 있습니다. 블록체인이 미들맨(Middle man)을 없애고 탈중앙화된 보상체계를 이룰 수 있다는 측면에서 많은 플랫폼이 나왔지만, 정작 플랫폼이 정거장처럼 덩그러니 있을뿐, 가치 있는 컨텐츠는 없는 경우가 많습니다. 컨텐츠가 없다면, 일반 사용자에게까지 닿을 수 없습니다. 비록 많은 사람들이 작년 하반기 비트코인의 가격 폭등으로 블록체인을 접했으나, 비개발자인 일반 사람들은 블록체인의 작동 원리를 명확히 파악하지 못하며, 블록체인의 가장 큰 강점인 **탈중앙화**에 대해 공감하지 않는 경우도 많습니다. 아무리 새로운 기술을 사용한 서비스를 내세워도 사용자가 불편함을 느낀다면, **결국 그것이 사용자에게 효용(ex. 경제적 이익)을 준다 할지라도 버려지기 마련입니다.** 지금까지 나왔던 수많은 블록체인 프로젝트들이 그랬듯이 말입니다.

블록체인 서비스가 일상에서 쓰이기 위해서는 결국 **사용자가 사용할 수 있을만한** 수준이 되어야 하며, 그 과정에서 UX는 고려해야 할 필수요소입니다. 그러나 아직까지는 블록체인 기술의 미성숙으로 인해 UX에 대한 논의는 거의 이루어지지 않은 실정입니다. 그러므로 여기에서는, Web 3.0시대의 대표적인 기술로 불리우는 블록체인 UX가 Web 2.0의 UX와 다르게 어떤 점을 고려해야 하는지를 중점으로, UX설계에 대한 기본적인 내용을 다룰 예정입니다.
<br>
<br>

## 블록체인에서의 UX

> "*Just because blockchain technology is built to eliminate the reliance on trust doesn't mean users will trust the machine or network. (Jonny Howle, UX/UI Designer)*"

오늘날 블록체인 서비스(이하 DApp)은 스마트 컨트랙트를 토대로 인터랙션이 이루어집니다. 비록 그 기능은 아직은 미숙해 DApp이 상용화되기 까지는 상당히 오랜 시간이 걸릴 듯이 보이지만 말입니다. 실제로 현재 출시되는 기존의 DApp의 UX는 **사용자가 보기에** 알 수 없는 해시 코드와 개인 키 등의 데이터를 화면에 띄우는 것 외에는 Web 2.0 시대 앱과 별반 차이가 없어 보이는 경우가 대부분입니다.

하지만, 블록체인에서의 UX는 이전의 Web 2.0 시대의 UX와는 다른 차별점을 가져야 합니다. 일명 Web 3.0으로 일컬어지는 블록체인은 이전 Web 2.0과는 확연히 차별화된 가치인 탈중앙화, 개인화, 공개, 투명, 보상의 공정한 분배와 같은 특징을 갖고 있기 때문입니다. 그러므로, 블록체인에 대한 이해도는 사용자 개개인마다 제각기 다르겠지만 최소한 모든 사용자가 블록체인 기반의 프로덕트가 신뢰할 수 있는 안정적인 서비스라고 인지하게 만들어야 합니다. **다시 말하면, DApp에서는 사용자가 블록체인 시스템을 신뢰하도록 UX를 설계해야 합니다.**
<br>
<br>


![web3](https://user-images.githubusercontent.com/36020880/42731944-ab980880-8852-11e8-8bb7-591a046bef8b.jpg)

\[Web 3.0  |  출처: AD4th]
<br>
<br>

## 어떻게 신뢰를 설계할까?
> 본 파트는 Blockchain Design Principles(https://medium.com/design-ibm/blockchain-design-principles-599c5c067b6e)를 토대로 작성했습니다.

앞에서 보았듯이 블록체인 이전의 중앙화된 인터넷과는 다른 특징을 갖고 있습니다. UX설계에 대해 다루기 전에, 일반적인 사용자가 DApp을 사용할 때 가질 수 있는 궁금증들은 다음과 같은 것들이 있습니다. 
<br>
<br>


>  - 과연 이 인터랙션을 하는 것이 안전할까?
>  - 블록체인의 데이터는 어디에 저장되는 것일까?
>  - 나의 데이터는 안전한가? 혹은, 다른 사람들이 나의 데이터를 식별할 수 있는가?
>  - 이 인터랙션을 한 이후에 어떤 일이 벌어질 것인가? 무언가 중요한 과정이 블록체인 back단에서 돌아가지 않을까?
>  - 블록체인의 데이터는 신뢰할 수 있는 것이라 들었는데, 어떤 데이터가 '진짜로' 신뢰 가능한 데이터인가? 과연 모든 데이터를 신뢰할 수 있는가?
>  - 어떤 데이터가 블록체인에서 오는가?
>  - 만약 데이터를 잘못 입력했을 경우, 나의 계정(혹은 계좌)에 문제가 생기는가? 생긴다면, 어떤 문제가 생기는가?
>  - 데이터를 입력하면 그 데이터는 어디에서 어떻게 열람할 수 있는가?
>  - 블록체인 코드는 어떤 프로세스에서 작동하는가? 등
<br>
<br>

우리는 사용자의 질문을 사전에 예측하고, 이에 대한 솔루션을 제공해 결과적으로 **블록체인은 믿을 수 있고, 신뢰할 수 있으며, 안정적인 시스템이라는 점을 인지하게 만들어야 합니다.** IBM은 **블록체인에서 신뢰를 설계하는 방법(Designing for Trust)** 에서 다음과 같은 5가지 방법을 제시합니다.
<br>
<br>

> 1. 데이터 노출 Data Exposure
> 2. 일관성 Consistency
> 3. 피드백 Feedback
> 4. 실수를 예상하기 Anticipating Mistakes
> 5. 서비스에 대한 적극적인 지침 Active Guidance
<br>
<br>

### 데이터 노출 Data Exposure
많은 사람들은 어떻게 블록체인 기술이 이전의 앱과 다른지, 그리고 이 기술이 정말 신뢰할 수 있는 기술인지 알고 싶을 것입니다. 이러한 맥락에서 볼 때, 블록체인의 데이터를 사용자에게 **어느 정도** 보여주는 것은 DApp이 어떻게 작동하는지 이애하게 도와줍니다. 예를 들어, 데이터를 보여주는 것은 어떤 함수가 작동하는지, 혹은 이 데이터가 어떻게 암호학적으로 안전한지 보여주는 지표가 될 수 있습니다. 다시 말해, 사용자들은 **블록체인이 어떻게 작동하는지** 보고 싶어하기 때문에, 의외로 앱 사용에 필요하지 않은 데이터를 들여다보고 싶어할 수 있습니다.

![dataexposure](https://user-images.githubusercontent.com/36020880/42732107-c8053760-8855-11e8-88b7-e593bfd1be42.png)
\[출처: IBM medium]

그러면 **어떤 데이터**를 사용자에게 보여주어야 할까요? 우선적으로 사용자에게 보여지는 데이터는 **사용자가 실행할 수 있는 종류의 데이터여야 하며, 만약 데이터가 실행되지 않는 raw data라 하더라도, 그 데이터가 신뢰를 형성하게 도와주거나 블록체인을 이해하게 도와준다면** 노출하는 것이 좋습니다. 
<br>
<br>

### 일관성 Consistency
여기서 말하는 일관성은, 글씨 폰트와 색깔보다는 시각적 언어(visual language)의 측면에서 말하는 것입니다. 블록체인에서 사용되는 시각적 언어(ex. 아이콘)은 아직 정립되지 않았으며, 사용자는 가스(Gas), 세그윗(Segwit)과 같은 블록체인만의 용어를 이해하는 데에 어려움을 겪고 있습니다.

그러므로 DApp에 사용되는 언어는 최대한 전문 용어를 배제해야 하며, 사용자들이 관습적으로 익숙한 형태로 표현하는 것이 가장 중요합니다. 일례로, Coinbase는 사용자에게 이미 친숙한 증권 앱과 유사한 UX를 취해, DApp에 대한 부담감을 낮추고 친숙한 User experience를 구현할 수 있었습니다.

![Coinbase](https://user-images.githubusercontent.com/36020880/42732216-399c2616-8858-11e8-9879-c463bfaa05b2.png)
\[Coinbase]
<br>
<br>

### 지속적인 피드백 Constant Feedback
DApp에서의 트랜잭션은 중앙화된 네트워크보다 더 많은 시간이 걸리며, 사용자는 그 많은 로딩 시간에 블록체인에서 어떤 일이 진행되고 있는지 알아야 합니다. 특히, 사용자는 몇백분의 일의 속도로 처리되는 앱에 익숙해져 있기에, 블록체인 트랜잭션 시 오랜 시간이 걸린다면 서비스가 제대로 작동하지 않는다고 오해할 수 있습니다. 그러므로 블록체인 상의 어떠한 작업 때문에 얼마나 시간이 걸리는지 사용자에게 실시간으로 알려주는 작업이 필요합니다.





