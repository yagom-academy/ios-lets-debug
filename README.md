아래의 문제를 해결하기 위해서 참고할 기본 자료는 [LLDB 공식 문서](https://lldb.llvm.org/)입니다.  
필요하다면 [야곰닷넷의 LLDB 정복 강좌](https://yagom.net/courses/start-lldb/)를 참고할 수 있습니다.
위의 두 곳에서 찾을 수 없으면 아래 참고할 WWDC 세션까지만 허용합니다.   
문제대 대한 답을 찾아갈 때는 LLDB 문서 -> LLDB 정복 강좌 -> WWDC 순서로 찾아보세요.    
다른 곳에서 자료를 찾는 것은 반칙입니다. 여러분의 양심에 맡깁니다.   

### 참고할 WWDC 세션 힌트

* Debugging Tips and Tricks
* Debugging with Xcode 9
* Visual Debugging with Xcode
* LLDB: Beyond "po"



### 문제

- ViewController.swift 파일의 23번째 줄에 브레이크 포인트를 설정하려면 입력해야 하는 LLDB 명령어는? 
- `changeTextColor`라는 심볼에 브레이크 포인트를 설정하기 위해 입력해야 하는 LLDB 명령어는? 
- LLDB의 특정 명령어의 별칭을 설정해줄 수 있는 명령어는 무엇일까요?
- Breakpoint Navigator를 통해 `titleLabel`의 `text`가 `"두 번째 뷰 컨트롤러!"`인 경우에만 작동을 일시정지하고 `titleLabel`의 `text`를 출력하는 액션을 실행하도록 설정해보세요
- 오류(Error) 혹은 익셉션(Exception)이 발생한 경우 프로세스의 동작을 멈추도록 하는 방법에 대해 알아봅시다
- View Controller의 뷰 위에는 사용자 눈에 보이지 않는 뷰가 있습니다. 이 뷰의 오토레이아웃 제약을 확인해서 알려주세요
- 디버그 모드로 실행중인 상태에서 사용자 눈에 보이지 않는 뷰의 색상을 분홍색으로 변겅해보세요
- LLDB의 `v`, `po`, `p` 명령어의 차이에 대해 알아봅시다
- 두 번째 뷰 컨트롤러의 뷰가 화면에 표시된 상태에서, 두 번째 뷰 컨트롤러 까지의 메모리 그래프를 캡쳐해보세요
