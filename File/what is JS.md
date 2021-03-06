# 자바 스크립트?

웹 페이지에 생동감을 불어넣기 위해 만들어진 프로그래밍 언어

자바스크립트로 작성한 프로그램 = 스크립트

스크립트는 특별한 준비나 컴파일 없이 문자 형태로 작성할 수 있고, 실행도 가능하다.

> 자바스크립트는 자바와는 매우 다른 언어

자바스크립트는 브라우저뿐만 아니라 서버에서도 실행할 수 있다. **자바스크립트 엔진**이라 불리는 특별한 프로그램이 들어 있는 모든 디바이스에서도 동작한다.

엔진의 종류는 다양한데, 엔진마다 특유의 코드네임이 있다.

- V8 - Chrome과 Opera에서 쓰인다.
- SpiderMonkey - Firefox에서 쓰인다.
- IE는 버전에 따라 **Trident**나 **Chakra**라 불리는 엔진을 사용, ChakraCore는 Microsoft Edge에 사용, SquirrelFish는 Safari에 사용된다.

> 엔진의 간단한 동작원리
>
> 1. 엔진이 스크립트를 읽는다(파싱)
> 2. 읽어 들인 스크립트를 기계어로 전환한다(컴파일)
> 3. 기계어로 전환된 코드가 실행된다. 기계어로 전환되었기 때문에 실행 속도가 빠르다.

# 브라우저에서 할 수 있는 일

자바스크립트는 메모리나 CPU같은 저수준 영역의 조작을 허용하지 않는 **브라우저를 대상으로 만든 언어**

브라우저 환경에선 웹페이지 조작, 클라이언트와 서버의 상호작용에 관한 모든 일이 가능

- 페이지에 새로운 HTML을 추가하거나 기존 HTML, 혹은 스타일 수정하기
- 마우스 클릭이나 포인터의 움직임, 키ㅗ드 키 눌림 등과 같은 사용자 행동에 반응하기
- 네트워크를 통해 원격 서버에 요청을 보내거나, 파일 다운로드, 업로드하기
- 쿠키를 가져오거나 설정하기, 사용자에게 질문을 건내거나 메세지 보여주기
- 클라이언트 측에 데이터 저장하기

# 브라우저에서 할 수 없는 일

브라우저는 보안을 위해 자바스크립트의 기능에 제약을 걸어두었다. 악성 웹 페이지가 개인 정보에 접근하거나 사용자의 데이터를 손상하는 것을 막기 위해 만들어졌다.

- 디스크에 저장된 임의의 파일을 읽거나 쓰고, 복사하거나 실행할 때 제약을 받을 수 있다. 운영체제가 지원하는 기능을 브라우저가 직접 쓰지 못하게 막혀있다.

- 브라우저 내 탭과 창은 대개 서로의 정보를 알 수 없다. 그런데 자바스크립트를 사용해 한 창에서 다른 창을 열 때는 예외가 적용된다. 하지만 이 경우에서 도메인이나 프로토콜, 포트가 다르다면 페이지에 접근할 수 없다.

- 자바스크립트를 이용하며 페이지를 생성한 서버와 쉽게 정보를 주고받을 수 있다. 하지만 타 사이트나 도메인에서 데이터를 받아오는건 불가능하다. 가능하다 할지라도 원격 서버에서 명확히 승인을 해줘야 한다. 이 역시 보안을 위해 만들어진 제약사항이다.

# 자바스크립트의 강점

> - HTML/CSS와 완전히 통합될 수 있다.
> - 간단한 일을 간단하게 처리할 수 있게 해준다.
> - 모든 주요 브라우저에서 지원하고, 기본 언어로 사용된다.

위 세 가지를 모두 지원하는 브라우저 관련 기술은 자바스크립트 뿐이다.
