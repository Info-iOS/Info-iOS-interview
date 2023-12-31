# info iOS 면접 질문 정리

## **소개**
```
하루에 5개씩 정리하는 면접 질문 모음 🥊
```
### **iOS**

| 질문 | 답변 | 답변자 |
| --- | --- | --- |
| Bounds와 Frame의 차이 | | |
| 앱 콘텐츠나 데이터 저장 객체 | | |
| 앱 화면 콘텐츠 표시 및 관리 객체 | | |
| App thinning 설명 | | |
| UIApplicationMain에서 생성되는 객체 | | |
| @Main 설명 | | |
| Foreground 및 Background 상태 제약사항 | | |
| 앱 상태 변화 처리를 위한 앱 델리게이트 메서드 설명 | | |
| In-Active 앱 상태 시나리오 설명 | | |
| UIApplication 객체의 역할 위치 |  | |
| 앱 상태 (Not running, Inactive, Active, Background, Suspended) 설명 | | |
| NSOperationQueue 와 GCD Queue 의 차이점을 설명하시오. | | |
| GCD API 동작 방식과 필요성에 대해 설명하시오. | | |
| Global DispatchQueue 의 Qos 에는 어떤 종류가 있는지, 각각 어떤 의미인지 설명하시오. | | |
| iOS 앱을 만들고, User Interface를 구성하는 데 필수적인 프레임워크 이름은 무엇인가? | | |
| Foundation Kit은 무엇이고 포함되어 있는 클래스들은 어떤 것이 있는지 설명하시오. | | |
| Delegate란 무엇인지 설명하고, retain 되는지 안되는지 그 이유를 함께 설명하시오. | | |
| NotificationCenter 동작 방식과 활용 방안에 대해 설명하시오. |  | |
| UIKit 클래스들을 다룰 때 꼭 처리해야하는 애플리케이션 쓰레드 이름은 무엇인가? | | |
| App Bundle의 구조와 역할에 대해 설명하시오. | | |
| 모든 View Controller 객체의 상위 클래스는 무엇이고 그 역할은 무엇인가? | [답변](https://github.com/Info-iOS/Info-iOS-interview/tree/main/Interview/모든%20View%20Controller%20객체의%20상위%20클래스는%20무엇이고%20그%20역할은%20무엇인가%3F) | 박준하 |
| 자신만의 Custom View를 만들려면 어떻게 해야하는지 설명하시오. | | |
| View 객체에 대해 설명하시오. | | |
| UIView 에서 Layer 객체는 무엇이고 어떤 역할을 담당하는지 설명하시오. | | |
| UIWindow 객체의 역할은 무엇인가? | | |
| UINavigationController 의 역할이 무엇인지 설명하시오. |  | |
| TableView를 동작 방식과 화면에 Cell을 출력하기 위해 최소한 구현해야 하는 DataSource 메서드를 설명하시오. | | |
| 하나의 View Controller 코드에서 여러 TableView Controller 역할을 해야 할 경우 어떻게 구분해서 구현해야 하는지 설명하시오. |  | |
| setNeedsLayout와 setNeedsDisplay의 차이에 대해 설명하시오. | | |
| NSCache와 딕셔너리로 캐시를 구성했을때의 차이를 설명하시오. | | |
| URLSession에 대해서 설명하시오. | | |
| prepareForReuse에 대해서 설명하시오. |  | |
| 다크모드를 지원하는 방법에 대해 설명하시오. | | |
| ViewController의 생명주기를 설명하시오. |  | |
| TableView와 CollectionView의 차이점을 설명하시오. | | |
| 실제 디바이스가 없을 경우 개발 환경에서 할 수 있는 것과 없는 것을 설명하오. | [답변](https://github.com/Info-iOS/Info-iOS-interview/tree/main/Interview/실제%20디바이스가%20없을%20경우%20개발%20환경에서%20할%20수%20있는%20것과%20없는%20것을%20설명하오) |박준하, 은호|

### **Autolayout**

| 질문 | 답변 | 답변자 |
| --- | --- | --- |
| 오토레이아웃을 코드로 작성하는 방법은 무엇인가? (3가지) | | |
| hugging, resistance에 대해서 설명하시오. | | |
| Intrinsic Size에 대해서 설명하시오. | | |
| 스토리보드를 이용했을때의 장단점을 설명하시오. | [답변](https://github.com/Info-iOS/Info-iOS-interview/tree/main/Interview/스토리보드의%20장단점) | 박준하, 이은호 |
| Safearea에 대해서 설명하시오. | | |
| Left Constraint 와 Leading Constraint 의 차이점을 설명하시오. | | |

### **Swift**

| 질문 | 답변 | 답변자 |
| --- | --- | --- |
| struct와 class와 enum의 차이를 설명하시오. | | |
| class의 성능을 향상 시킬수 있는 방법들을 나열해보시오. | | |
| Copy On Write는 어떤 방식으로 동작하는지 설명하시오. | | |
| Convenience init에 대해 설명하시오. | | |
| AnyObject에 대해 설명하시오. | | |
| Optional 이란 무엇인지 설명하시오. | [답변](https://github.com/Info-iOS/Info-iOS-interview/tree/main/Interview/Optional%20이란%20무엇인지%20설명하시오) | 박준하 |
| Struct 가 무엇이고 어떻게 사용하는지 설명하시오. | | |
| Subscripts에 대해 설명하시오. | | |
| String은 왜 subscript로 접근이 안되는지 설명하시오. | | |
| instance 메서드와 class 메서드의 차이점을 설명하시오. | | |
| class 메서드와 static 메서드의 차이점을 설명하시오. | | |
| Delegate 패턴을 활용하는 경우를 예를 들어 설명하시오. | | |
| Singleton 패턴을 활용하는 경우를 예를 들어 설명하시오. | | |
| KVO 동작 방식에 대해 설명하시오. | | |
| Delegates와 Notification 방식의 차이점에 대해 설명하시오. | | |
| 멀티 쓰레드로 동작하는 앱을 작성하고 싶을 때 고려할 수 있는 방식들을 설명하시오. | | |
| MVC 구조에 대해 블록 그림을 그리고, 각 역할과 흐름을 설명하시오. | | |
| 프로토콜이란 무엇인지 설명하시오. | | |
| Protocol Oriented Programming과 Object Oriented Programming의 차이점을 설명하시오. | | |
| Hashable이 무엇이고, Equatable을 왜 상속해야 하는지 설명하시오. | | |
| mutating 키워드에 대해 설명하시오. | | |
| 탈출 클로저에 대하여 설명하시오. | | |
| Extension에 대해 설명하시오. | | |
| Extension 내부에서 함수를 override할 수 있는지 설명하시오. | | |
| 접근 제어자의 종류엔 어떤게 있는지 설명하시오. | | |
| defer란 무엇인지 설명하시오. | | |
| defer가 호출되는 순서는 어떻게 되고, defer가 호출되지 않는 경우를 설명하시오. | | |
| property wrapper에 대해서 설명하시오. | | |
| Generic에 대해 설명하시오. | | |
| some 키워드에 대해 설명하시오. | | |
| Result타입에 대해 설명하시오. | | |
| Codable에 대하여 설명하시오. | | |
| Closure에 대하여 설명하시오. | | |
| Closure와 함수와의 관계에 대해 설명하시오. | | |

### **ARC**

| 질문 | 답변 | 답변자 |
| --- | --- | --- |
| ARC란 무엇인지 설명하시오. | | |
| Retain Count 방식에 대해 설명하시오. | | |
| Strong 과 Weak 참조 방식에 대해 설명하시오. | | |
| 순환 참조에 대하여 설명하시오. | | |
| 강한 순환 참조 (Strong Reference Cycle) 는 어떤 경우에 발생하는지 설명하시오. | | |

### **Functional Programming**
| 질문 | 답변 | 답변자 |
| --- | --- | --- |
| 순수함수란 무엇인지 설명하시오. | | |
| 함수형 프로그래밍이 무엇인지 설명하시오. | | |
| 고차 함수가 무엇인지 설명하시오. | | |
| Swift Standard Library의 map, filter, reduce, compactMap, flatMap에 대하여 설명하시오. | | |

### **Functional Programming**
| 질문 | 답변 | 답변자 |
| --- | --- | --- |
| MVVM, MVI, Ribs, VIP 등 자신이 알고있는 아키텍쳐를 설명하시오. | | |
| 의존성 주입에 대하여 설명하시오. | | |

### **SwiftUI**
| 질문 | 답변 | 답변자 |
| --- | --- | --- |
| @State에 대해서 설명하시오. | | |

### **Combine**
| 질문 | 답변 | 답변자 |
| --- | --- | --- |
| PassthroughSubject에 대해서 설명하시오. | | |
| @Published에 대해서 설명하시오. | | |
| AnyCancellable에 대해서 설명하시오. | | |
| sink에 대해서 설명하시오 | | |
| throttle과 debounce의 차이점을 설명하시오. | | |

### **RxSwift**
| 질문 | 답변 | 답변자 |
| --- | --- | --- |
| Reactive Programming이 무엇인지 설명하시오. | | |
| RxSwift를 왜 사용하는지 설명하시오. | | |
| RxSwift의 단점을 설명하시오. | | |
| RxSwift에서 Hot Observable과 Cold Observable의 차이를 설명하시오. | | |
| Subject의 종류와 차이점에 대해 설명하시오. | | |
| Subject와 Driver의 차이를 설명하시오. | | |
| Single, Completable, Maybe의 차이점에 대해 설명하고, 언제 적용하면 좋을지 설명하시오. | | |

### **MRC**
| 질문 | 답변 | 답변자 |
| --- | --- | --- |
| ARC 대신 Manual Reference Count 방식으로 구현할 때 꼭 사용해야 하는 메서드들을 쓰고 역할을 설명하시오. | | |
| retain 과 assign 의 차이점을 설명하시오. | | |
| 특정 객체를 autorelease 하기 위해 필요한 사항과 과정을 설명하시오. | | |
| Autorelease Pool을 사용해야 하는 상황을 두 가지 이상 예로 들어 설명하시오. | | |
| 다음 코드를 실행하면 어떤 일이 발생할까 추측해서 설명하시오. | | |

### **Advanced**

| 질문 | 답변 | 답변자 |
| --- | --- | --- |
| method swizzling이 무엇이고, 어떨 때 사용하는지 설명하시오. | | |
| NSCoder 클래스는 어떤 상황에서 어떻게 써야 하는지 설명하시오. | | |
| Responder Chain 구조에 대해 설명하고, First Responder 역할에 대해 설명하시오. | | |
| NSObject부터 UIButton 까지 상속 과정의 계층과 역할을 설명하시오. | | |
| shallow copy와 deep copy의 차이점을 설명하시오. | | |
| Push Notification 방식에 대해 설명하시오. | | |
| Foundation 과 Core Foundation 프레임워크의 차이점을 설명하시오. | | |
| NSURLConnection 에서 사용하는 Delegate 메서드들에 대해 설명하시오. | | |
| Synchronous 방식과 Asynchronous 방식으로 URL Connection을 처리할 경우의 장단점을 비교하시오. | | |
| Plist 파일 구조와 Plist 파일에 저장된 데이터를 다루기 적합한 클래스를 설명하시오. | | |
| Core Data와 Sqlite 같은 데이터 베이스의 차이점을 설명하시오. | | |
| JSON 데이터를 처리하는 방식과 파서, 객체 변환 방식에 대해 설명하시오. | | |
| 웹 서버와 HTTP 연결을 사용해서 데이터를 주거나 받으려면 사용해야 하는 클래스와 동작을 설명하시오. | | |
| Protocol에서는 왜 var만 되는지 설명하시요. | | |
| DispatchQueue.main.sync를 사용하는 상황을 설명하시오. | | |
| Run Loops에 대해 설명하시오. | | |

