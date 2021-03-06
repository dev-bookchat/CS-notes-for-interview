### 🧢 **챕터2 <네트워크> 퀴즈 1회차** 🧢

### 1. 네트워크는 무엇입니까?

- 네트워크는 노드(node)와 링크(link)가 서로 연결되어 있거나 연결되어 있지 않은 집합체를 의미합니다. 이 네트워크를 통해서 컴퓨터를 두 대 이상 연결하여 데이터를 서로 주고 받게 됩니다. 많은 처리량을 처리할 수 있어야 하고 지연 시간이 짧아야 하며, 장애 빈도가 적고 좋은 보안을 갖춘 것을 좋은 네트워크라고 합니다.
  </br>

### 2. 노드에 대해 설명해보세요.

- 노트란 서버, 라우터, 스위치 등 네트워크 장치를 의미합니다.
  </br>

### 3. 네트워크 토폴로지에 대해 설명해보세요.

- 네트워크 토폴로지는 노드와 링크가 어떻게 배치되어 있는지에 대한 방식이며, 네트워크를 설계할 때 고려하는 요소 중에 하나입니다. 트리 형태의 트리 토폴로지와 중앙 통신 회선 하나에 여러 개의 노드가 연결되어 공유하며 근거리 통신망(LAN)에서 사용되는 버스 토폴로지, 그리고 중앙에 있는 노드에 모두 연결된 스타 토폴로지, 각각의 노드가 양 옆의 두 노드와 연결하여 고리처럼 하나의 연속된 길을 통해 통신하는 링형 토폴로지, 마지막으로 그물망처럼 서로 연결되어 있는 메시 토폴로지 등이 있습니다.

- 네트워크의 구조인 토폴로지가 중요한 이유는, 어떤 토폴로지를 갖는지를 알아야 병목 현상을 올바르게 해결할 수 있기 때문입니다.
  </br>

### 4. 네트워크를 규모를 기반으로 분류해보세요.

- 네트워크 규모를 기반으로 분류하자면, 건물이나 특정 지역을 범위로 하는 네트워크인 랜(LAN)과 지리적으로 넓은 범위에 구축된 네트워크인 왠(WAN)이 있다. 이들의 중간에 대도시 지역 같은 넓은 지역에서 운영되는 네트워크인 맨(MAN)이 있다. 규모가 크면 클 수록, 전송 속도가 느려지며 더 혼잡해진다는 특징을 가진다.
  </br>

### 5. 네트워크 병목 현상의 원인을 설명해보세요.

- 병목 현상은 전체 시스템의 성능이나 용량이 하나의 구성요소로 인해 제한을 받는 현상을 의미합니다. 어플리케이션 코드 상에는 문제가 없는데 사용자가 서비스로부터 데이터를 가져오지 못하는 상황이 발생했을 때 네트워크 병목 현상일 가능성이 높습니다. 주된 원인에는 네가지가 있는데, 네트워크 대역폭의 문제, 네트워크 토폴로지의 문제, 또는 서버 CPU와 메모리 사용량의 문제 마지막으로 비효율적인 네트워크 구성일 때 주로 발생합니다.
  => 랜선이 끊기거나 단절되었을 때도 발생함. 사용자가 많아지거나, 랜선을 적게 깔았다면 발생하는 문제.
  </br>

### 6. 네트워크 성능 분석 방법에 대해 설명해보세요.

- 네트워크 병목 현상이 발생겼을 때 네트워크 성능 분석을 해야 할 것입니다. 그 전에 네트워크 관련 테스트와 네트워크와 무관한 테스트를 통해서 '네트워크로부터 발생한 문제점'인 것을 확인하고 네트워크 성능분석에 들어갑니다. 이 성능 분석에 사용하는 명령어에는 여러가지가 있는데, 먼저 확인 대상 노드를 향해 일정의 패킷을 전송하며 패킷 수신 상태와 도달 시간 그리고 네트워크와 연결 여부를 알 수 있는 ping이라는 명령어가 있습니다. 두 번째로는 접속되어 있는 서비스들의 네트워크 상태를 체크하는 netstat이 있고 DNS에 관련된 내용을 체크하기 위해 사용하는 nslookup 과 목적지 노드까지 네트워크 경로를 체크할 때 사용하는 tracert 가 있습니다.
  </br>

### 7. 네트워크 프로토콜에 대해 설명해보세요.

- 네트워크 프로토콜이란 다른 장치들끼리 데이터를 주고 받기 위해 설정된 공통된 인터페이스를 의미합니다. 즉, 컴퓨터 간에 정보를 주고 받을 때의 통신 방법에 대한 규칙이나 표준을 의미합니다. 이 규칙은 개인이 정하는 것이 아닌 IETF 라는 표준화 단체가 지정하는 것입니다.
  </br>

### 8. 인터넷 프로토콜 스위트(internet protocol suite)를 하나 이상의 모델로 설명해보세요.(예:TCP/IP 모델)

- 인터넷 프로토콜 스위트는 인터넷에서 컴퓨터들이 서로 정보를 주고 받는 데 쓰이는 프로토콜의 집합을 의미합니다. ISO에서 지정한 표준 규격인 ISO 7계층 모델과 TCP/IP 4계층 모델로 뉩니다. ISO 모델은 7계층으로 위에서부터 (응용, 표현, 세션, 전송, 네트워크, 데이터링크) 계층으로 나뉘며, TCP/IP 모델은 4계층으로 위에서부터 (응용, 전송, 인터넷, 네트워크 접속) 계층으로 나뉩니다. TCP/IP 모델은 인터넷 모델이라고도 합니다.
  </br>

### 9. TCP/IP 모델 안에서 전송 계층에 대해 설명해보세요.

- TCP/IP 4계층 모델 안에서의 전송 계층은 대표적으로 TCP와 UDP로 나뉩니다.
- 전송 계층은 목적지에 신뢰할 수 있는 데이터를 전달하기 위해 필요합니다. 전송 계층의 특징을 간단히 설명하자면, 신뢰성/정확성 과 효율성으로 구분할 수 있습니다. 신뢰성/정확성은 데이터를 목적지에 문제 없이 전달하는 것을 말하고, 효율성은 데이터를 빠르고 효율적으로 전달하는 것을 의미합니다. 여기서 신뢰할 수 있고 정확한 데이터를 전달하는 통신을 **연결형 통신(TCP)**이라고 하며, 효율적으로 데이터를 전달하는 통신을 **비연결형 통신(UDP)**이라고 합니다. 연결형 통신은 상대편과 확인해가며 통신하는 방식이며, 비연결형 통신은 상대편을 확인하지 않고 일방적으로 데이터를 전송하는 방식을 의미합니다. 연결형 통신은 신뢰성/정확성이 우선이기에 여러 번 검증 과정을 거쳐 데이터를 전송하는 데 반해, 비연결형 통신은 효율성이 우선인 통신이므로, 확인 절차 없이 일방적으로 보내는 것입니다. 두 가지 모두 장단점이 있기 때문에 각각의 장점이 필요할 때를 고려해서 연결형/비연결형 통신을 고려해서 선택하고 사용하면 됩니다.
  </br>

### 10. HTTP를 통해 웹 서버에 있는 데이터를 요청한다면, 계층 간 데이터 송수신 과정이 어떻게 진행되는지 설명해보세요.

- 데이터를 송수신 할 때는 캡슐화와 역캡슐화가 이루어집니다. 만약 A라는 컴퓨터에서 B라는 컴퓨터에 데이터를 보낸다고 가정했을 때, 이 데이터를 보내려면 데이터의 앞 부분에 접송하는데 필요한 정보를 붙여서 다음 계층으로 보내야 합니다. 이 정보를 헤더 라고 하는데 헤더에는 데이터를 전달받을 상대방에 대한 정보도 포함되어 있어야 합니다. 이처럼 헤더를 붙여서 계층으로 보내는 것을 캡슐화라고 합니다. 한편 데이터를 받는 쪽에서는 헤더를 하나씩 제거해야 하는데, 이것을 **역캡슐화** 라고 합니다. TCP로 전송하는 것을 예를 들어보자면, TCP로 전송할 때 붙이는 헤더를 TCP 헤더라고 하며 이 TCP 헤더가 붙은 데이터를 '세그먼트' 라고 합니다. 이후 인터넷 계층으로 가면서 IP 헤더가 붙으면서 '패킷화'가 되며, 링크 계층으로 전달되면서 프레임 헤더가 붙어 '프레임화'가 됩니다.
  </br>

### 11. PDU에 대해 설명해보세요.

- 네트워크의 계층에서 계층으로 데이터가 저달될 때 한 덩어리의 단위를 의미합니다. **PDU**는 제어 관련 정보가 포함된 '헤더'와 데이터를 의미하는 '페이로드'로 구성되어 있고, 계층 마다 부르는 명칭이 다릅니다. 어플리케이션 계층에서는 메세지라 불리며, 전송 계층에서는 세그먼트(TCP)/데이터그램(UDP), 인터넷 계층에서는 패킷, 그리고 링크 계층에서는 프레임(데이터 링크 계층)/비트(물리 계층)로 불립니다. PDU 중 링크 계층 내의 물리 계층인 비트로 송수신 하는 것이 모든 PDU 중 가장 빠르고 효율성이 높습니다.
  </br>

### 12. 네트워크 기기를 계층별로 나눠보세요.

- 네트워크 계층은 계층별로 처리 범위를 나눌 수 있습니다. 어플리케이션 계층 기기인 L7 스위치와 인터넷 계층 기기인 라우터, L3 스위치, 데이터 링크 계층 기기인 브리지, L2 스위치 그리고 물리 계층 기기인 NIC, 리피터, AP 로 나뉩니다.
  </br>

### 13. 홉바이홉 통신을 설명해보세요.

- IP 주소를 통해 통신하는 과정을 홉바이홉이라고 합니다. 즉, 통신 장치에 있는 라우팅 테이블의 IP 를 통해 시작 주소부터 시작해서 다음 IP로 계속해서 이동하는 '라우팅' 과정을 거쳐 '패킷'에 최종 목적지까지 도달하는 통신을 의미합니다.
  </br>

### 14. NAT의 단점에 대해 설명해보세요.

- IP 주소 체계의 종류 중에 하나인 NAT(ex. 공유기)는 패킷이 라우팅 장치를 통해 전송되는 동안 패킷의 IP 주소 정보를 수정해서 IP 주소를 다른 주소로 매핑하는 방법입니다. 많은 주소들을 감당하기 위해 공인 IP와 사설 IP로 나눠서 많은 주소를 처리합니다. 예를 들면, 인터넷 회선 하나를 개통한 뒤 NAT 기능이 탑재된 인터넷 공유기를 달아서 여러 PC를 연결해서 사용하는 방법 같은 것입니다. 단점이 있다면, 여러 명이 동시에 인터넷을 접속하게 됐을 때 실제로 접속하는 호스트 숫자에 따라서 접속 속도가 느려진다는 점입니다.
  => 공유기는 IP 주소 할당 체계를 클래스 기반 할당 방식으로 나누자면 클래스 C에 해당한다.
  </br>

### 15. 멀티플렉싱에 대해 설명해보세요.

- HTTP/2 프로토콜이 지원하는 여러 개의 스트림을 사용해서 송수신하는 기능입니다. 여러 개의 스트림이 있기 때문에 특정 스트림의 패킷이 손실되어도 해당 스트림에만 영향을 미칠 뿐 나머지 스트림은 이와 관련 없이 동작한다는 특징이 있습니다. 이를 통해서 HTTP/1.1 프로토콜의 이슈 중에 하나였던 HOL Blocking(네트워크에서 같은 큐에 있는 패킷이 그 첫번째 패킷에 의해 지연될 때 발생하는 성능 저하 현상을 의미)을 해결할 수 있게 되었습니다.
  => 여러 개의 스트림을 발생시켜서 데이터를 전송시킬 수 있다.
  </br>

### 16. HTTPS 구축 방법에 대해 설명해보세요.

- 구축 방법에는 세가지가 있습니다. 직접 CA에서 구매한 인증키를 기반으로 HTTPS 서비스를 구축하거나 서버 앞단의 HTTPS 를 제공하는 로드밸런서를 두거나, 서버 앞단에 HTTPS 를 제공하는 CDN을 둬서 구축하는 방법입니다.
  => 인터넷 컨텐츠의 상당 부분이 CDN(콘텐츠 전송 테트워크)을 통해 전송된다. CDN의 미션은 '지연 시간'을 줄이는 것입니다.
  => Content Delivery Network의 약자인 CDN은 지리적 제약 없이 전 세계 사용자에게 빠르고 안전하게 콘텐츠를 전송할 수 있는 콘텐츠 전송 기술을 의미합니다. CDN은 서버와 사용자 사이의 물리적인 거리를 줄여 콘텐츠 로딩에 소요되는 시간을 최소화합니다. CDN은 각 지역에 캐시 서버(PoP, Points of presence)를 분산 배치해, 근접한 사용자의 요청에 원본 서버가 아닌 캐시 서버가 콘텐츠를 전달합니다. 예를 들어 미국에 있는 사용자가 한국에 호스팅 된 웹 사이트에 접근하는 경우 미국에 위치한 PoP 서버에서 웹사이트 콘텐츠를 사용자에게 전송하는 방식입니다.
  => [CDN이란 무엇인가](https://library.gabia.com/contents/infrahosting/8985/)
  </br>

### 17. HTTP/2를 설명하고 장점 두가지를 설명하세요.(책에 나온 문제)

- HTTP/2는 HTTP/1.1과는 다르게 요청을 보낸 순서대로 응답을 반환하지 않아도 된다는 특징이 있습니다. 크게 몇 가지로 장점을 나눌 수 있는데 그 중 두가지를 말하자면 **멀티플렉싱** 과 **서버 푸시**입니다. **멀티플렉싱**은 여러 개의 스트림을 사용하여 송수신하여, 해당 스트림이 손실되어도 다른 스트림에는 영향을 미치지 않아 정상적으로 구동할 수 있다는 것입니다. 두번째 장점인 **서버 푸시**는 클라이언트가 요청 없이도 서버가 바로 리소스를 푸시하는 것을 말합니다. html을 읽으면서 그 안에 들어있던 css 파일을 서버에서 푸시해서 클라이언트에 사전에 전달할 수 있는 기능입니다.
  </br>
