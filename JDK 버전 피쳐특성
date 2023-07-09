### JDK 11
|Type|Features|Content|
|:---:|:---|:---|
|패키지|Jigsaw 모듈 시스템|모듈을 만들고 해당 모듈은 외부에서 호출할 수 있는 API를 제공하여, 언어레벨에선 직접적으로 해당 모듈에 접근이 불가능|
|패키지|**New Garbage Collector, ZGC 추가**|새로운 Garbage Collector 도입|
|패키지|Thread-Local Handshakes|GC 실행 전 우선 발생하는 "STOP-THE-WORLD" 발생 시 이전에는 모든 Thread가 동시에 중단이 되었다면, 이제는 Thread 개별로 중단 가능|
|패키지|JVM 힙 영역을 시스템 메모리가 아닌 다른 종류의 메모리 할당|HotSpot JVM 이 사용자가 지정한 대체 메모리 장치 또는 서로 다른 메모리장치를 이용해서 JVM Heap 영역의 메모리를 할당|
|패키지|Multi-Release JAR File|JAR파일 형식을 확장하여 여러 버전의 클래스 파일을 하나의 JAR안에 공존 가능|
|지원 도구|jlink|JRE를 생성해주는 도구|
|지원 도구|JShell|메인 Method 없이 자바 코드를 넣고 즉석에서 실행 가능한 도구|
|기능|**Collection Factory Method 기능 강화**|List, Set, Map 인터페이스에 immutable 생성을 할 수 있는 새로운 Method 추가|
|기능|Interface, Private Method 도입|인터페이스 내 private Method 사용 가능|
|기능|Optional ifPresentOrElse Method 추가|기존 ifPresent Method 경우 Optional 객체가 값을 담고 있는 경우만 처리를 하였으나, 추가 된 ifPresentOrElse Method는 해당 객체가 값이 없을 경우 처리할 내용까지 정의가 가능|
|기능|HTML5 Javadoc|javadoc 생성 시, 이전에는 HTML4 형식을 사용하였으나, JDK 9 부터는 HTML5 마크업으로 생성이 가능|
|기능|HTTP 2 Client|http2를 구현하는 신규 클라이언트 API 제공, 기존 HttpURLConnection API 대체 가능|
|기능|**Reactive Stream**|Non-Blocking Backpressure를 이용한 비동기 스트림 처리 지원 API 추가|
|기능|**로컬 변수 타입 추론 "var"**|로컬 변수 선언 시 "타입 추론"을 이용한 명시적 타입 선언이 없어도 변수 선언이 가능한 "var" 키워드 추가|
|기능|**신규 문자열 Method 추가**|isBlank, lines, strip, stripLeading, stripTrailing, repeat 등 신규 String Method 추가|

### JDK 17
|Type|Features|Content|
|:---:|:---|:---|
|패키지|향상된 의사 난수 생성기|의사 난수 생성기(Pseudo-Random Number Generator)를 위한 새로운 인터페이스 타입과 구현을 제공|
|패키지|신규 Mac OS 렌더링 파이프라인|Apple 메탈 API를 사용하는 Mac OS용 Java  파이프라인을 구현|
|기능|**텍스트 블록 기능 추가**|기존 String을 여러 줄 작성할 때 사용 가능한 기능, 가독성 있는 코드 지원|
|기능|Switch 표현식 기능 향상|Switch 문 이용 시 값을 반환하여 이용 가능 하며, 람다 스타일 구문을 사용 가능|
|기능|**Record Data class 추가**|immutable 객체를 생성하는 새로운 유형의 클래스로 기존 toString, equals, hashCode Method에 대한 구현을 자동 제공|
|기능|Instanceof 매칭|이전 버전 경우 Instanceof 내부에서 객체를 캐스팅 하는 과정이 필요하였으나, 캐스팅 과정을 내부에서 지원할 수 있도록 변경|
|기능|NumberFormat 클래스 기능 향상|기존 숫자 Format 클래스(NumberFormat) 내 Method 추가(getCompactNumberInstance)|
|기능|DateTimeFormatter 클래스 기능 향상|기존 날짜 Format 클래스(DateTimeFormatter) 내 패턴 Method 형식 추가("B")|
|기능|봉인(Sealed) 클래스|무분별한 상속을 막기 위한 목적으로 등장한 기능으로 지정한 클래스 외 상속을 허용하지 않으며, 지정한 클래스 외 상속 불가능|
|기능|Stream.toList() 기능 추가|기존, Stream을 List로 변환 시 Collectors에서 기능을 찾아 사용했다면 Java17 부터는 Collectors호출 없이 toList()만으로 변환이 가능|
