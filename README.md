- 👋 Hi, I’m @chojaechun
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
chojaechun/chojaechun is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

﻿


Java spring framework ( Version. 3.2.9 )

: Spring Boot 를 사용하고 있지는 않지만, Control, Service, dao의 bean을 하나하나 설정함으로서

기본적인 규칙을 이해 중


Common에 속해있는 Constants 를 이해하도록 해보자

Bundle Plugin 설정은 Web modules에 Deployment Assembly에 정상 설정이 되어있는지 체크 ( 배포시에 properties 에 포함되어있는지도 체크 )

개발 협업시 우선 회사에서 추구하는 개발 로직을 이해하는게 중요


2021. 10 ~ 

React 개발을 진행 중 

Version : 
  React : 17.0.2
  Mobx : 6.3.7
  framework7 : 6.3.9
  axios : 0.24.0
  vite : 2.6.14
  
  
  
현재 특이 사항

  Mobx의 Commponent 관리가 잘되는 것 같다. ( observerble, computed, action )
    observable : State의 상태를 감시한다.
    computed : State의 정보가 변경되면 그 값을 저장하고 다른 정보로 변경될때까지 그 값을 갖고있는다.
    action : State는 action에서만 변경하여야 위 두가지를 사용하여 효과적으로 State를 관리 할 수 있다.


2021. 10 ~ 11 
  Mobx6 로 변경 되면서 decorators가 빠진걸 뒤늦게 알게 되었다..
    ( 공식 문서에는 자바스크립트의 정식 기능이 아니라서 정식 기능이 될때까지 지양한다고 한다.. )
  억지로 데코레이터를 사용하게 만들었지만, 정석대로 사용하는게 맞는거 같아서 전부 변경..
  
  
2021. 12 ~ 현재
  Java Spring MVC 패턴 처럼 구현 해보려 노력 중
  Model - getter, setter 구현 ( 변수에는 observable, getter에는 computed를 설정 )
  Repository - Like DAO
  Store - Control and Service
  
  Store에선 Data converting 을 하려했으나.. 
  observable로 관리하기 위해서는 Store에서 관리하는게 편하다고 판단,
  변수를 설정하고 해당 변수를 observable로 설정
  
  의문.. 
  서버에서 받은 데이터들 ( Model list )을 List화 하여 observable, computed로 설정, 데이터를 관리하는데
  이게 맞는건지... ( State가 변경될때마다 화면에 정상적으로 비동기 변경되긴 함.. )
  
 
  for ( i=0; i<obj.length; i++ ) {
    for ( var key in obj[i] ) {
      const model = new Model();
      model[key] = obj[i][key]
      objList.pust(model);
    }
  }
  
  
  makeObservable(this, {
    objList: observable,
    getObjList: computed,
  
  });
  
  getObjList 사용하면 정상적으로 observer 관리가 되긴하는데... 부하가 없으려나..

﻿
