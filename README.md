# CleanArchitecture-Hilt
Hilt 의존성 주입을 통한 클린아키텍쳐 보일러 프로젝트입니다.

1. CleanArchitecture
2. Hilt
3. KTS

# CleanArchitecture?

좋은 프로젝트가 되기 위한 조건 -> 읽기 쉬워야한다. 유지보수가 쉬워야한다.

프로젝트가 커질 수록 코드를 파악하기가 어려워질 것이다.

각 파일들이 서로 간에 연결이 되있다면 한 파일을 이해하기 위해 여러 파일들을 꼬리물어 확인을 해야 할 것이다.

이해 필요한 것이 프로젝트의 독립적인 구성이다. 

UI 별로, DataBase 별로, 각 모듈별로 독립적으로 존재할 필요가 있다는 것이다.

읽기 쉬워지고 유지보수, 테스트가 쉬워질 것이다.


이에 Clean Architecture 을 이해하고 이에 맞게 프로젝트를 구성할 줄 알아야한다.


Entity, UseCase, interface ...

# Hilt?
의존성 주입 방법 중 하나이다. 
지금까지 koin을 사용해왔는데 Hilt로 프로젝트를 구성해보자.

# KTS?

https://developer.android.com/studio/build/migrate-to-kts?hl=ko

Groovy -> (KTS == Kotlin DSL) 빌드 구성 마이그레이션

더 나은 컴파일 시간 확인과 IDE 지원을 제공하기 때문입니다.
가독성
빌드속도 느림

앞으로 KTS는 Gradle 스크립트를 작성하는 데 Groovy보다 선호됩니다.
