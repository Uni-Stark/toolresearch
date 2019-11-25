# Tool Research

# 1. Intro - <i>"혼돈의 카오스를 피하자"</i>

<center><img src="./markdown/img/chaos_pic.png" width="550"/></center>

>카톡으로 파일 보내고, 어떤 이 가장 최신이냐 서로서로 물어가던 시절이 있었다. 하지만 점차 할 일이 많아지고, 다양화 되면 이러한 파일 공유나 관리는 혼돈의 카오스를 만들어 낸다. 이러한 혼돈의 카오스를 미연에 방지하고자 우리가 사용해야 할 협업 툴을 조사하여 만든 Git 저장소이다. 이 글을 보면서 어떤 것들이 좋을지에 대한 해답을 찾긴 어렵지만 실마리를 찾으면 하는 바램으로 글을 작성한다.
    

</br>


# 2. Why? - <i>"왜를 알면 효율성이 극대화된다"</i>

<center><img src="./markdown/img/efficiency_pic.png" width="450" height="400"/></center>

>막상 협업 툴을 조사하면서 우리가 왜 이러한 협업 툴을 써야 하는지에 대한 필요성을 상기시킬 필요가 있다. 그냥 쓰는것보다 왜 써야하는지 정확한 원인 파악 후 사용하면, 더욱 효율적으로 쓸 수 있게된다. 무작정 쓰라고 해서 협업툴을 사용한다면, 이걸 왜 사용해야 하는지에 대한 필요성이나, 장점들을 모른 채 넘어갈 수 있다. 그래서 내가 생각하는 협업툴을 사용해야 하는 필요성에 대하여 생각해서 나열해 보았다.

</br>

1. 효율적인 프로젝트 관리
    >자주 있는 예를 들겠다. 이사님께서 나에게 파일을 받았냐고 물어보시고, 나는 다시 이 파일에 대하여 임대리님한테 물어보고 임대리님은 또 송상무님에게 물어보는 상황이 발생할 수 있다. 물론 사무실 특성상 이는 조금 더 쉽게 이루어질 수 있는 대화일 수 있다. 하지만 이러한 대화는 "이 파일 제가 어제 수정했어요!", "내가 어제 작성해서 누구한테 보냈는데!?" 라는 코멘트가 붙으며, 최신 파일은 누구에게 있는지 파일을 서로 비교해보고 대조해보는 상황이 발생할 수 있다. 이러한 상황은 프로젝트 관리 Tool을 사용하여 항상 최신을 유지해 파일을 비교 대조해보는 상황을 피할 수 있게 된다.

2. 다양한 피드백의 보존
    >서류작성, 자료조사, 코딩 등과 같은 프로젝트와 관련된 업무를 진행할 떄 우리는 파일을 공유하고, 그 파일에 대한 피드백을 서면이 아닌 구두로 전한다. 이러한 피드백은 구두로만 전해지기 때문에 피드백에 대한 내용의 변질, 혹은 잘못된 이해가 생길 수 있다. 이러한 상황을 보존된 피드백을 통하여 방지할 수 있다.


3. 스케쥴 관리의 간편화
    >자잘한 개인의 스케쥴이 아닌, 회사 팀원끼리 공유해야할 스케쥴이 있다면, 협업툴에 해당 날짜에 무슨 이슈가 있는지 등록하고 간단한 구두로 전하면 된다. 스케쥴의 내용은 내용을 등록하며 디테일하게, 스케쥴에 대한 언급은 간단히 구두로 전하면 회사 스케쥴관리를 간편화할 수 있게된다.

</br>

# 3. Which? - <i>"그럼 뭘 써야 할까요?"</i>

<center><img src="./markdown/img/which_pic.png" width="550"/></center>

>이제 왜 써야 하는지 알았다면, 우리에게 가장 알맞는 툴이 무엇이 있는지 알아볼 시간이다. 소개할 툴은 n가지로써 내가 생각해보고 이 툴은 괜찮을 것 같다고 한것들만 선별한 것이다. 이제 그 툴들에 대하여 설명해보겠다.

</br>

*****

</br>

<center><img src="./markdown/img/git_pic.png" width="550"/></center>


<h2> Git - <i>"개발자들이라면 누구나 다 아는 프로젝트 관리 툴" </i></h2>

<h3> <i>About Git</i></h3>

>가장 먼저 소개할 것은 Git이다. Git은 컴퓨터 파일의 변경사항을 추적하고 여러 명의 사용자들 간에 해당 파일들의 작업을 조율하기 위한 분산 버전 관리 시스템이다. 많은 사람들이 지칭하는 `Github는 Git을 쉽게 관리하기 위한 웹 호스팅 서비스`이다. 쉽게 말하자면 Git을 관리하기 위해 웹 사이트로 만들어 놓은 UI/UX이다.₩

<h3> <i>Git's advantage</i></h3>

1. 저장소를 무제한으로 생성가능하다.

	> Git을 사용하면 저장소라는 개념을 쓰며 하나의 저장소를 프로젝트를 관리하는 폴더라고 생각하면 된다.
	> 이때 Git에서는 이러한 저장소를 생성하는데 제한을 두지 않고,`무제한으로 생성이 가능하다.`따라서 각 프로젝트마다 저장소가 구분이 되어있어 관리하기가 편하며, 무제한으로 생성할 수 있어 제한성이 없는 장점이 있다.
	> <img src="./markdown/img/git_repo.png"/>

2. 요금을 납부해서 사용하는 것과 큰 차이가 없다.

	> 앞서 1번에서 설명했던 것과 같이 저장소를 무제한으로 만들 수 있다는 장점이 Git에 있다. 이와 더불어`Git은 요금을 지불하지 않아도 파일을 업로드할 수 있는 용량이 제한되어있지 않다.` 따라서 문서작업이 주된 업무를 이룬다면, 파일이 업로드 되지 않을거라는 부담이 크게 줄어든다.

3. 파일의 버전관리가 쉽다.
	>명령어 혹은 UI를 통해 `파일을 올리면 해당 파일이 가장 최신의 파일`이 된다. 그렇기 때문에 업무 상 파일의 버전때문에 야기되는 혼동을 피할 수 있게 된다.
	><img src="./markdown/img/git_version_mgmt.png"/>


<h3> <i>Git's disadvantage</i></h3>

1. Private한 저장소를 만들려면 요금제 가입이 필수다.

	>우리 회사는 프로젝트 특성상 Open Source가 아닌 private한 저장소를 많이 만들어야 한다. 하지만 Private한 저장소를 만들기 위해서는 요금제 가입이 필수이기 때문에, 요금제를 꼭 가입해야한다. 그래서 아래 사진과 같은 요금들이 매달 부과된다. 만약 작은 단위에서 할 때는 필자가 현재 요금제 상품을 사용하기 때문에 커버가 가능하다. 하지만 점점 팀이 늘어나게 된다면, 요금제 가입은 필수가 된다.
<img src="./markdown/img/github_price_policy.png" />

</br>

2. Git을 이용하기 위한 조작방법을 익히는게 어려울 수 있다.

    >Git을 주로 사용하는 직군은 개발자 직군이 많다. 개발자들에게 있어서 GUI보다 CLI가 익숙한 경우가 있다. 그래서 GUI(Graphic User Interface)보다 CLI(Command Line Interface)를 이용해서 Git을 관리하는 경우도 존재한다. 그래서 송상무님이나 신이사님이 이용하기에는 다소 무리가 있을 수 있다.	물론 아래 Sourcetree사진을 보면 UI/UX를 통하여 관리할 수 있지만, 새로운걸 배워야 한다는 진입장벽이 존재하기 때문에 팔자가 문서를 잘 만들면 극복할 수 있다고 생각된다.</br></br>
    ><h4>Git bash</h4>
    ><div>Git bash를 이용하기 위해서는 이와같이 명령어를 입력해 주어야한다.</div>
    ><img src="./markdown/img/git_bash_pic.png" width="600"/></br></br>
    ><h4>Sourcetree</h4>
    ><div>명령어나 CLI를 잘 다루지 못한다면 위 사진과 같은 GUI로 Git 저장소를 관리할 수 있다.</div>
    ><img src="./markdown/img/sourcetree_pic.png" width="600"/>

<!-- 수정이 약간은 필요한 부분 -->

<h3> <i>Git이 우리회사랑 잘 어울릴까?</i></h3>

>`Git은 우리 회사에 잘 어울릴까`라는 표현보다는 우리 회사에 필요하다. 그 이유는 단연 `프로젝트 관리의 간편화`이다. Git은 프로젝트 관리가 너무 편하다. Branch를 두어 따로 기능을 만들고, Pull Request를 보내고, Issue Tracking을하는 등 너무 다양한 영역에서 편리성을 제공해준다. 또한 필자가 Git에 사용법에 자세히 알기 때문에 User Guide를 만들기에 수월하다. 그렇기 때문에 향후 계획된 개발 프로젝트를 위해서라도 Git은 반드시 사용해야 한다.

</br></br>

*****

</br>

<center><img src="./markdown/img/collabee_logo.png" width="300"/></center>

<h2> Collabee - "여러가지 업무용 툴의 Collaboration" </h2>

<h3><i> About Collabee</i></h3>

> 콜라비팀은 콜라비를 만들 때 `시간을 돌려준다` 라는 비전으로 툴을 만들었다. 필자가 해석한 이 '시간을 돌려준다'라는 의미는, 여러 기능을 한데 묶어서 시간을 '절약'한다 라는 의미로 받아들였다. 그에 걸맞게 콜라비는 Calendar, Issue Tracking, 칸반보드, File Upload 등의 기능을 녹여넣었다.


<h3><i> Collabee's Advantage </i></h3>

1.  다양한 기능의 존재
    > 콜라비에는 정말 다양한 기능들이 한 곳에 모여있다. 칸반보드, File Management, Calendar, Issue Tracking 등이 한 곳에 보여있다. 내가 필요한 기능들이 한자리에 모여있기 때문에 편하게 이용하기만 하면 된다. </br></br>
    > <h3>협업공간 및 칸반보드</h3>
    > <div>원하는 부서 / 프로젝트 별 협업공간을 따로 만들어서 칸반보드를 이용할 수 있다. 부서, 프로젝트 별 칸반보드를 따로 제공해서 TODO-List 작성이 한결 간편해진다.</div></br>
    ><img src="./markdown/img/collabee_kanban.png"/></br></br>
    ><h3> 켈린더를 통한 Calendar 관리</h3>
    ><div>콜라비에서는 협업공간 각기 다른 캘린더 설정이 가능하다. 또한 그 캘린더들을 한번에 관리해주는 통합 캘린더가 존재한다. 그래서 일정관리가 훨씬 수월해진다.</div></br>
    ><img src="./markdown/img/collabee_todo_list.png" /></br>
    ><img src="./markdown/img/collabee_calendar.png"/></br></br>
    ><h3>Issue Tracking</h3>
    ><div>Iusse Tracking을 통해 수정해야할 내용, 등을 확인할 수 있다. 또한 협업공간, 프라이빗 공간 등을 통하여 각각의 공간마다 Issue Tracking을 할 수 있고 모든 Issue를 한번에 확인할 수 있다 </div></br>
    ><img src="./markdown/img/collabee_issue_tracking.png" />
    ></br>
    ><h3>Google Drive 연동</h3>
    ><div>콜라비는 File Upload가 가능한데, Local에서 뿐만아니라 Google Drive를 연동할 수 있어서 쉽고 빠르게 File Upload가 가능하다.</div>
    ><center><div><img src="./markdown/img/collabee_google_drive.png" width='550'/></div></center>


2. 시간절약
	>1번에서 보여주었 듯 다양한 기능이 존재한다는 것은 해당 기능을 사용하기 위해서 `A라는 툴에서 B라는 툴로 옮겨 가는 시간을 줄여준다.` 또한 A라는 툴을 사용하기 위한 사용법, B라는 툴을 사용하기 위한 사용법을 각각 익힐 필요없이 `콜라비 툴 하나의 사용법만 익혀야 되서 시간을 절약`해준다.

</br>

<h3> <i>Collabee's Disadvantage</i></h3>

1. 툴의 미완성
	> 콜라비는 아직 갈길이 멀다. 왜냐하면 아직 툴의 많인 기능들이 구현중에 있기 때문이다. 
	> <img src="./markdown/img/collabee_price_policy.png"/> 여기서 보면 '외부 서비스 연동', '이메일 연동'과 같은 중요한 부분들이 아직 준비중 단계에 있기 때문에 `툴의 기능 미완성은 큰 단점`으로 자리 잡는다.

</br>

<h3> <i>Collabee가 우리회사랑 잘 어울릴까?</i></h3>

> 콜라비는 2%가 아쉬운 툴이다. 왜냐하면 툴을 왔다갔다하는 시간, 툴 사용법을 익히는 시간을 줄여주는 것은 분명 강점이고 좋은점이다. 하지만 `아직 개발 진행중인 기능들이 많기 때문에 우리 회사에 어울리는 좋은 툴이지만 2%가 부족한 툴이다.`

</br></br>

*****

<img src="./markdown/img/slack_pic.png" width="550"/>

<h2> <i>Slack - "세계적으로 이용하는 커뮤니케이션 툴"</i></h2>

<h3> <i> About Slack</i></h3>

> 슬랙은 기업용 메신저로, Tiny Speck이라는 게임 회사에서 내부 커뮤니케이션을 위해 만들었는데, 실리콘밸리에서 엄청난 호응을 얻어서 게임 개발을 접고 슬랙을 본업으로 바꾸었다고 한다.

</br>

<h3> <i>Slack's Advantage</i></h3>

1. 무료 버전으로 가입해도 인원수와 기능에 제한이 없다.
	>Slack은 얼마든지 무료로 사용이 가능하다. 커뮤니케이션 툴에 걸맞게 `인원제한, 기능에 큰 제한 없이 무료로 사용이 가능`하다. 다만 유료회원으로 전환이 되면, 많은 기능이 제공되는데, 그 기능들 중 일부는 아래와 같다. (참고링크 : <a href="https://slack.com/intl/en-kr/pricing" target="_blank">여기</a>)</br>
	><img src='./markdown/img/slack_price.png' /></br>
	><img src="./markdown/img/slack_advanced_func.png" /></br>

2. 기존 솔루션과의 연결성
	> `Slack은 다른 업무 툴과의 연결성이 굉장히 좋다.` 구글드라이브, 드롭박스, 트렐로 등과 연동이 되어, 연결된 구글드라이브나 트렐로에 새로운 파일, 일정 등과 같은 이벤트가 발생하면 알람으로 보내주어서 일일이 다른 사람들에게 이벤트 발생에 대한 내용을 보내지 않아도 공유가 가능하다.

</br>

<h3> <i>Slack's Disadvantage</i></h3>

1. 커뮤니케이션 툴, 딱 거기까지.
	> Slack은 커뮤니케이션 툴 그 이상 그 이하도 아니다. 그래서 `다른 여러가지 업무를 하려면 결국 다른 업무용 툴을 사용해야 한다는 한계점이 존재`한다. 그래서 우리에게 있어, 카카오톡 같이 친숙한 존재도 아니고 다른 기능들은 존재하지 않는 애매한 커뮤니케이션 툴일 수 있다.

</br>

<h3><i>Slack이 우리 회사에 어울릴까?</i></h3>

> `Unbound tech 팀과의 커뮤니케이션을 고려했을 때, 우리에게 있어서 Slack은 사용해야할 수 밖에 없는 커뮤니케이션 툴`이다. 물론 Unbound 팀과의 연락을 제외하면 사실상 사용할 일이 많지 않겠지만, Unbound팀과의 원활한 커뮤니케이션을 위하여 Slack을 알아야 하고 사용해 볼 필요성은 존재한다.
> <img src="./markdown/img/slack_communication.png"/>


*****
<img src="./markdown/img/trello_logo.png" width="600'"/>

<h2> <i>Trello - "프로젝트 관리 대표 툴"</i></h2>

<h3> <i> About Trello </i></h3>

> 트렐로는 웹기반 프로젝트 관리 비쥬얼 프로그램이다. 개인, 팀의 프로젝트 효율성을 높이기 위해 이용되는 업무용 툴로서, 2011년 포그 크리크 소프트웨어에서 개발했으며 후에 아틀라시안에 인수되었다. 이후 2014년 5월 기준으로 전 세계 백 만명이 넘는 사람들이 트렐로를 사용하며, 명실상부 대표적인 프로젝트 관리 툴로서 자리잡았다.

<h3> <i> Trello's Advantage </i></h3>

1. 사용 및 조작이 굉장히 쉽다.
	>사용법을 익히는데 큰 시간을 할애하지 않아도 될 정도로 사용법이 굉장히 간단하다. 단순히 `마우스만 가지고 쉽게 조작할 수 있어서 처음 사용하는 사람들도 큰 무리 없이 트렐로를 사용할 수 있다.` 아래 사진처럼 원하는 객체를 드래그해서 위치를 옮길 수 있다. </br>
	><img src="./markdown/img/trello_func2.png"/></br></br> 이런 간단한 사용법은 사용자가에게 툴을 익히는데 걸리는 시간 또한 줄여주기 때문에 장점으로 작용하게 된다.

2. 다양한 기능 & 다른 툴과의 연동성
	> <img src="./markdown/img/trello_func.png"/></br>
	> 트렐로는 List를 만들어 Card를 추가하고, 그 Card를 기준으로 프로젝트를 칸반보드에서 관리한다. 이러한 기능을 트렐로가 대표적인 프로젝트 관리 툴로서 자리잡을 수 있게 만든 것은 바로 다양한 기능이다. 하나의 카드에서 `CheckList를 만들고, 파일을 첨부하고, 해당 카드의 종료일까지 설정`할 수 있다. 또한 파일을 첨부할 때는 Google Drive, Dropbox, OneDrive 등 다양한 외부 툴과의 연동성도 뛰어나다. 또한 앞서 소개한 슬랙과의 연동이 가능해서, 트렐로에서의 변동점이 바로 슬랙에 반영되기도 하다. 이러한 다양한 기능들은 트렐로가 가지는 큰 장점중에 하나이다.