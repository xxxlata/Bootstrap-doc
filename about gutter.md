# gutters

거터는 열 사이의 패딩으로, Bootstrap 그리드 시스템에서 콘텐츠의 간격을 맞추고 정렬하는 데에 사용된다.

------------------------
#### 작동 원리
거터는 가로 padding에 의해 생성되는 열 콘텐츠 사이의 간격이다.<br>
각 열에 padding-right 및 padding-left를 설정하고 음수 margin을 사용하여 각 행의 시작과 끝에서 이를 오프셋하여 콘텐츠를 정렬해준다.<br>
거터의 너비는 1.5rem (24px)에서 시작합니다. 이를 통해 그리드를 패딩 및 마진 스페이서 스케일과 일치시킬 수 있다.<br>
거터는 반응형으로 조정될 수 있다. 중단점별 (breakpoint-specific) 거터 클래스를 사용하여 세로 거터, 가로 거터 및 모든 거터를 수정할 수 있다.

--------------------------------
#### 수평 거터
.gx-* 클래스를 사용하여 수평 거터 너비를 제어할 수 있다.<br>
.container 또는.container-fluid 부모는 일치하는 패딩 유틸리티를 사용하여 원하지 않는 오버플로를 방지하기 위해 더 큰 거터를 사용하는 경우 조정해야할 수 있다.

#### 수직 거터
.gy-* 클래스는 세로 거터 너비를 제어할 수 있다. <br> 
가로 거터와 마찬가지로 세로 거터는 페이지 끝의 .row 아래에 약간의 오버플로를 유발할 수 있다. 이 경우 .overflow-hidden 클래스로.row 주위에 래퍼를 추가한다.

#### 수평 & 수직 거터
.g-* 클래스를 사용하여 가로 & 세로 거터 너비를 제어할 수 있다.
다음 예시에서는 더 작은 거터 너비를 사용하므로 .overflow-hidden 래퍼 클래스를 추가할 필요가 없다.

