예비 iOS 개발자로서 공부한 iOS 및 CS 개념들을 정리하기 위한 저장소입니다.
<br>
지금까지 작성한 블로그 포스팅과 스터디 링크를 모았습니다.
<br><br>
탐색의 용이성을 위해 한 링크에 여러 개념이 중복되어 등장하는 경우 이들을 나누어 입력했습니다.
<br>
(따라서 중복된 링크가 있을 수 있습니다.)

# iOS 🍎

### Swfit

- [기초 문법](https://inuplace.tistory.com/882?category=1034357)
- [Struct와 Class, Enum의 차이점](https://github.com/lunchScreen/Interview_Questions/issues/3)
- [ARC 메모리 관리 방식](https://github.com/lunchScreen/Interview_Questions/issues/4)
- [strong, weak, unowned](https://github.com/lunchScreen/Interview_Questions/issues/6)
- [Foundation](https://github.com/lunchScreen/Interview_Questions/issues/10)
- [Generic](https://inuplace.tistory.com/1121)
- [Codable Protocol](https://inuplace.tistory.com/895?category=1034357)
- [Dynamic Dispatch](https://inuplace.tistory.com/991?category=1034357)
- [UserDefaults](https://inuplace.tistory.com/1002?category=1034357)
- [Codable vs NSCoding](https://inuplace.tistory.com/1002?category=1034357)
- [문자열 처리](https://inuplace.tistory.com/1052?category=1034357)
- [NSCache vs NSDictionary](https://inuplace.tistory.com/1050)
- [KVC(Key-Value Coding)](https://inuplace.tistory.com/1113)
- [KVO(Key-Value Observing)](https://inuplace.tistory.com/1113)
- [async await](https://inuplace.tistory.com/1124)
- [Task](https://inuplace.tistory.com/1125?category=1034357)
- [Actor](https://inuplace.tistory.com/1126?category=1034357)
- [defer](https://github.com/lunchScreen/Interview_Questions/issues/24)
- [Convinience init](https://github.com/lunchScreen/Interview_Questions/issues/32)
- [Escaping Closure](https://github.com/lunchScreen/Interview_Questions/issues/35)
- [NotificationCenter](https://inuplace.tistory.com/1120?category=1034357)
- [sort의 내부구현](https://github.com/lunchScreen/Interview_Questions/issues/83)
- [Localizing](https://inuplace.tistory.com/1163)
- [Method Swizzling](https://inuplace.tistory.com/1165)
<!-- - GCD 동작원리 및 사용
- 함수형 프로그래밍 패러다임에 따른 불변 객체 및 순수함수 구현
- JSON 데이터 파싱 및 디코딩, 데이터 인코딩
- 구조의 단계적 분리 분리 (입력, 검증, 처리, 형식, 출력)
- SPM(Swift Package Manager) 사용 및 패키지 생성
- 여러 타입을 포함한 데이터 모델링
- 터미널 환경에서의 Swift 코드, 프로젝트 빌드 (Xcode 사용X)
- console, debugger에서의 LLDB 명령을 사용한 Swift 프로그램 디버깅
- 앱 빌드 환경을 위한 target, project, workspace 구조 이해 및 원하는 형태로 정리 -->

### iOS

- [App Bundle](https://github.com/lunchScreen/Interview_Questions/issues/30)
- [Scene delegate](https://github.com/lunchScreen/Interview_Questions/issues/41)
- [App Life Cycle (Not running, Inactive, Active, Background, Suspended)](https://github.com/lunchScreen/Interview_Questions/issues/46)
- [ApplicationDelegate](https://github.com/lunchScreen/Interview_Questions/issues/81)
- [#selector의 역할](https://inuplace.tistory.com/1072)
- [translatesAutoresizingMaskIntoConstraints](https://inuplace.tistory.com/1047?category=1029564)
- [ATS (App Transport Security)](https://inuplace.tistory.com/1222)
- [JSON Encoding / Decoding](https://inuplace.tistory.com/1223)
- [CodingKeys / Custom CodingKeys](https://inuplace.tistory.com/1224)
- [URL Loading System](https://inuplace.tistory.com/1226)
- [URLSession Cahce Policy](https://inuplace.tistory.com/1232)
- [PhotoKit](https://inuplace.tistory.com/1238)

### UIKit

- [Diffable Datasource](https://inuplace.tistory.com/929?category=1034353)
- [Frame vs Bounds](https://inuplace.tistory.com/955?category=1034353)
- [Compositional Layout](https://inuplace.tistory.com/1038?category=1034353)
- [Multiple Gesture Recognizer](https://inuplace.tistory.com/1069?category=1034353)
- [ViewController 라이프사이클 이해 및 활용](https://inuplace.tistory.com/1080?category=1034353)
- [오토레이아웃을 코드로 작성하는 방법](https://github.com/lunchScreen/Interview_Questions/issues/2)
- [Left, Right Constraint vs Leading, Trailing Constraint](https://github.com/lunchScreen/Interview_Questions/issues/11)
- [Safe Area](https://github.com/lunchScreen/Interview_Questions/issues/39)
- [스토리보드의 장단점](https://github.com/lunchScreen/Interview_Questions/issues/12)
- [Responder Chain](https://github.com/lunchScreen/Interview_Questions/issues/21)
- [First Responder](https://github.com/lunchScreen/Interview_Questions/issues/21)
- [UI를 메인스레드에서 다루는 이유](https://inuplace.tistory.com/1016?category=1029564)
- [View Drawing Cycle](https://inuplace.tistory.com/1137)
- [setNeedsDisplay, setNeedsLayout](https://inuplace.tistory.com/1137)
- [UITableView 기초부터 다시 살펴보기](https://inuplace.tistory.com/1174)
- [dequeueReusableCell (withIdentifier:for:) vs (withIdentifier:)](https://inuplace.tistory.com/1175?category=1029564)
<!-- - 스토리보드를 이용한 뷰 계층 구조 구현
- 스토리보드를 사용하지 않고 코드만으로 뷰 계층 구조 구현
- 오토레이아웃을 적용한 반응형 뷰 계층 구조 구현 (in 스토리보드, Xib, 코드)
- SwiftUI를 활용한 뷰 계층 구조 구현
- 필요한 추가 프레임워크 등록 및 빌드 환경에서 통합 빌드 설정 (in Xcode)
- URLSession을 활용한 세션 기반 인증 구현
- RESTful API에 대한 이해
- WEB API 서버와 PUT, POST로 연동
- Container ViewController 개념 이해 (포함관계 및 ToolBar, NavigationBar 동작흐름)
- CollectionView 동작 이해 및 활용 (데이터 소스 지정, 커스텀 레이아웃 구현)
- Persistance 데이터 계층 종류 및 특징, 구현방법
- StackView 동작 이해 및 활용
- 멀티 터치 이벤트 동작, Response Chain Pattern의 이해 (원하는 시점에 터치 이벤트 처리)
- CoreML 모델을 통한 텍스트 및 사진 데이터 인식
- instruments를 이용해 원하는 성능 데이터를 프로파일링
- App 라이프사이클 이해 및 백그라운드 동작에 대한 제약, 내부 데이터 아카이브
- 원하는 속성으로 애니메이션 구현 -->

### SwiftUI

- [ViewModifier](https://inuplace.tistory.com/1153)
- [View Combiner](https://inuplace.tistory.com/1153)
- [ForEach & identifiable](https://inuplace.tistory.com/1154?category=1049462)

### RxSwift

- [RxSwift?](https://inuplace.tistory.com/1009?category=1034358)
- [Observable](https://inuplace.tistory.com/1084?category=1034358)
- [Operator](https://inuplace.tistory.com/1084?category=1034358)
- [Subject](https://inuplace.tistory.com/1089?category=1034358)
- [Scheduler](https://inuplace.tistory.com/1100?category=1034358)
- [Trait (Single, Completable, Maybe)](https://inuplace.tistory.com/1099?category=1034358)
- [ControlProperty, ControlEvent](https://inuplace.tistory.com/1101?category=1034358)
- [Driver, Signal](https://inuplace.tistory.com/1102?category=1034358)
- [Relay (PublishRelay, BehaviorRelay, ReplayRelay)](https://inuplace.tistory.com/1107?category=1034358)
- [RxCocoa로 TableView 구현하기](https://inuplace.tistory.com/1201)
- [Rx로 네트워크 통신하기](https://inuplace.tistory.com/1227)

### Combine

- [Publisher](https://inuplace.tistory.com/1021?category=1034354)
- [Subscriber](https://inuplace.tistory.com/1021?category=1034354)
- [Subscription](https://inuplace.tistory.com/1021?category=1034354)
- [Subscribers.Demand](https://inuplace.tistory.com/1023?category=1034354)
- [Subject](https://inuplace.tistory.com/1024?category=1034354)
- [Operator](https://inuplace.tistory.com/1025?category=1034354)
- [timer](https://inuplace.tistory.com/1034?category=1034354)
- [share](https://inuplace.tistory.com/1035?category=1034354)
- [multicast](https://inuplace.tistory.com/1035?category=1034354)

### CoreData

- [Entity](https://inuplace.tistory.com/1005?category=1034355)
- [CRUD](https://inuplace.tistory.com/1005?category=1034355)
- [NSPredicate](https://inuplace.tistory.com/1010?category=1034355)
- [NSCompundPredicate](https://inuplace.tistory.com/1010?category=1034355)
- [NSSortDescriptor](https://inuplace.tistory.com/1010?category=1034355)
- [Entity Relationship](https://inuplace.tistory.com/1011?category=1034355)

### Architecture

- [Clean Architecture](https://inuplace.tistory.com/1049?category=1024843)
- [MVC](https://inuplace.tistory.com/1049?category=1024843)
- [MVP](https://inuplace.tistory.com/1049?category=1024843)
- [MVVM](https://inuplace.tistory.com/1049?category=1024843)
- [VIPER](https://inuplace.tistory.com/1055)
<!-- - Clean Swift
- RIBs -->

### Design Pattern
- [Delegate](https://github.com/lunchScreen/Interview_Questions/issues/13)
- [Singletone](https://github.com/lunchScreen/Interview_Questions/issues/55)
- [Facotry](https://inuplace.tistory.com/1170?category=1024843)
- [Coordinator](https://inuplace.tistory.com/1168)
- [Decorator](https://inuplace.tistory.com/1233)

<!-- 
### ETC

- Reactorkit
- Alamofire
- Kingfisher
- Carthage
- CocoaPods -->

# CS 🖥

### OOP

- [추상화, 캡슐화, 상속, 다형성](https://github.com/lunchScreen/Interview_Questions/issues/93)
- [DI (의존성주입)](https://github.com/lunchScreen/Interview_Questions/issues/5)
- [SOLID](https://inuplace.tistory.com/938)
- [SRP (Single Responsibility Principle)](https://inuplace.tistory.com/938)
- [OCP (Open-Closed Principle)](https://inuplace.tistory.com/941)
- [LSP (Liskov Substitution Principle)](https://inuplace.tistory.com/943)
- [ISP (Interface Segregation Principle)](https://inuplace.tistory.com/946)
- [DIP (Dependency Inversion Principle)](https://inuplace.tistory.com/952)

### Network


- [TCP/IP](https://inuplace.tistory.com/800?category=966976)
- [OSI 7Layer](https://inuplace.tistory.com/800?category=966976)
- [패킷](https://inuplace.tistory.com/800?category=966976)
- [IP 주소](https://inuplace.tistory.com/804?category=966976)
- [Ethernet Protocol](https://inuplace.tistory.com/803?category=966976)
- [ARP Protocol](https://inuplace.tistory.com/809?category=966976)
- [IPv4 Protocol](https://inuplace.tistory.com/816?category=966976)
- [ICMP Protocol](https://inuplace.tistory.com/816?category=966976)
- [포트](https://inuplace.tistory.com/818?category=966976)
- [TCP](https://inuplace.tistory.com/821?category=966976)
- [UDP](https://inuplace.tistory.com/819?category=966976)
- [HTTP](https://inuplace.tistory.com/823?category=966976)
- [HTTP 메서드](https://inuplace.tistory.com/847?category=966976)
- [HTTP API 설계 예시](https://inuplace.tistory.com/860?category=966976)
- [HTTP 상태코드](https://inuplace.tistory.com/865?category=966976)
- [HTTP 헤더](https://inuplace.tistory.com/869?category=966976)
- [HTTP 캐시와 조건부요청](https://inuplace.tistory.com/871?category=966976)
- [HTTPS](https://inuplace.tistory.com/1086?category=966976)
- [흐름제어](https://inuplace.tistory.com/1081?category=966976)
- [혼잡제어](https://inuplace.tistory.com/1081?category=966976)

### Operation System

- [뮤텍스 vs 세마포어](https://github.com/lunchScreen/Interview_Questions/issues/75) 
- [채널, 버퍼, 인터럽트](https://inuplace.tistory.com/279?category=884574)
- [시분할 시스템](https://inuplace.tistory.com/280?category=884574)
- [커널](https://inuplace.tistory.com/281?category=884574)
- [시스템콜](https://inuplace.tistory.com/281?category=884574)
- [입출력 시스템](https://inuplace.tistory.com/282?category=884574)
- [이중모드](https://inuplace.tistory.com/285?category=884574)
- [프로세스](https://inuplace.tistory.com/290?category=884574)
- [프로세스 Context](https://inuplace.tistory.com/290?category=884574)
- [프로세스 라이프사이클](https://inuplace.tistory.com/295?category=884574)
- [PCB (Process Control Block)](https://inuplace.tistory.com/295?category=884574)
- [스레드](https://inuplace.tistory.com/315?category=884574)
- [프로세스 스케줄링](https://inuplace.tistory.com/318?category=884574)
- [임계구역](https://inuplace.tistory.com/335?category=884574)
- [상호배제](https://inuplace.tistory.com/335?category=884574)
- [세마포어](https://inuplace.tistory.com/336?category=884574)
- [교착상태 (DeadLock)](https://inuplace.tistory.com/338?category=884574)
- [페이징](https://inuplace.tistory.com/346?category=884574)
- [페이징 테이블](https://inuplace.tistory.com/352?category=884574)
- [세그멘테이션](https://inuplace.tistory.com/353?category=884574)
- [가상메모리](https://inuplace.tistory.com/362?category=884574)
- [페이지 대치 알고리즘](https://inuplace.tistory.com/363?category=884574)
- [프레임개수와 페이지크기](https://inuplace.tistory.com/371?category=884574)
- [쓰레싱](https://inuplace.tistory.com/374?category=884574)
- [디스크 스케줄링](https://inuplace.tistory.com/390?category=884574)
- [RAID](https://inuplace.tistory.com/394?category=884574)
- [IPC](https://inuplace.tistory.com/1039?category=884574)
<!-- - 멀티프로세스
- 파일시스템  -->

### Data Base

- [NoSQL vs RDBMS](https://github.com/lunchScreen/Interview_Questions/issues/65)
- [트랜잭션](https://inuplace.tistory.com/1000?category=911622)
- [ACID](https://inuplace.tistory.com/1000?category=911622)
- [Index](https://inuplace.tistory.com/1058?category=911622)

### Data Structure

- [배열](https://inuplace.tistory.com/169?category=884573)
- [링크드 리스트](https://inuplace.tistory.com/172?category=884573)
- [해시 테이블](https://inuplace.tistory.com/176?category=884573)
- [추상자료형](https://inuplace.tistory.com/180?category=884573)
- [트리](https://inuplace.tistory.com/185?category=884573)
- [힙](https://inuplace.tistory.com/190?category=884573)
- [그래프](https://inuplace.tistory.com/198?category=884573)
- [Queue by Swift](https://inuplace.tistory.com/1188)

### Algorithm

- [다익스트라](https://inuplace.tistory.com/870?category=884573)
- [플로이드워셜](https://inuplace.tistory.com/870?category=884573)
- [순열과 조합 by Swift](https://inuplace.tistory.com/1189?category=1034357)

<!-- # Experience

- 개인 단위 앱 서비스 개발 경험
- 팀 단위 앱 서비스 개발 경험
- 백엔드를 고려하지 않은 앱 서비스 개발 가능
- 데이터베이스와 서버를 포함한 앱 서비스 개발 가능
- 앱 스토어 등록 경험
- SNS 앱 서비스(로그인, 친구 공개, 전체 공개, 이미지 업로드, 댓글, 대댓글 가능) 개발 가능
- 기획서 분석능력
- 개발프로젝트 분석 및 시간배분
- Git Branch 전략
- 마일스톤 단위 일정수립
- Clean code
- 단위테스트 및 통합테스트
- 페어프로그래밍 경험
- 커뮤니케이션
- 애자일 개발 방법 경험 (데일리 스크럼, 회고 활동)
- 하이브리드앱 개발경험 -->
