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

### **Concurrency (NSOperationQueue와 GCD)**

| 질문 | 답변 |
| --- | --- |
| NSOperationQueue와 GCD Queue 차이점 | NSOperationQueue는 GCD 위에 구축된 고수준 API로 작업을 관리하는 데 사용되며, GCD는 낮은 수준의 C 기반 API로 작업을 병렬로 수행하는 데 사용됩니다. |
| GCD API 동작과 중요성 설명 | GCD는 작업을 효율적으로 병렬로 처리하는 데 사용되며, 병렬로 작업을 수행하는 간단하고 효율적인 방법을 제공합니다. |
| Global Dispatch Queue의 QoS 수준 | GCD의 글로벌 대기열에는 userInteractive, userInitiated, default, utility, background와 같은 QoS 수준이 있으며, 이 수준은 작업 우선 순위를 결정합니다. |

### **프레임워크**

| 질문 | 답변 |
| --- | --- |
| iOS 앱 개발에 필수적인 프레임워크 이름 | iOS 앱의 사용자 인터페이스를 생성하고 사용자 상호작용을 처리하는 데 필수적인 프레임워크는 UIKit입니다. |
| Foundation Kit 설명 | Foundation Kit은 데이터, 문자열, 컬렉션 등을 처리하는 필수 클래스를 제공하는 프레임워크입니다. 이에는 NSString, NSArray, NSDictionary 등의 클래스가 포함됩니다. |
| 델리게이트와 메모리 관리 설명 | 델리게이트는 한 객체가 특정 작업을 다른 객체에 위임하는 디자인 패턴이며, 델리게이트는 일반적으로 강한 참조로 보관하지 않아 강한 참조 순환을 피합니다. |
| NotificationCenter 동작과 활용 설명 | NotificationCenter는 앱 내에서 통지를 브로드캐스트하고 수신하기 위한 메커니즘으로, 앱의 다양한 부분 간의 통신에 사용됩니다. |
| UIKit 클래스의 애플리케이션 스레드 이름 | UIKit 클래스는 주로 메인 스레드(또는 메인 큐)에서 사용해야 하며, 이렇게 함으로써 스레드 안전성을 보장합니다. |
| App Bundle 구조와 역할 설명 | 앱 번들은 앱 실행 파일과 리소스를 포장하는 디렉토리 구 |

