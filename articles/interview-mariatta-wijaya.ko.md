---
title: Python Community Interview With Mariatta Wijaya
source-url: https://realpython.com/interview-mariatta-wijaya/
---

# 마리아타 위자야와 함께한 파이썬 커뮤니티 인터뷰

이번주의 커뮤니티 인터뷰는, [마리아타 위자야](https://translate.google.com/)와 함께합니다.
마리아타는 Zapier에서 웹 개발자로 일하면서, 파이썬 커뮤니티를 위한 자발적 활동에 많은 시간을 할애하고 있습니다. 또한 파이썬의 코어 개발자로 활동하며 컨퍼런스와 세미나를 위해 공헌하고 있습니다.
마리아타의 이야기가 즐거웠다면, [\#icecreamselfie](https://mariatta.ca/category/icecreamselfie.html)를 통해 더 알아보거나 깃헙(GitHub)에서 동작하는 그의 봇과 얘기해보세요. 마리아타와 연락할 수 있는 링크를 인터뷰 끝에 마련해 놓았습니다.

### **릭키:** 쉬운 것부터 시작해보겠습니다. 어떻게 프로그래밍을 시작하게 되었고, 언제부터 파이썬을 쓰고 있나요?
**마리아타:** 중학교 시절에 시작했습니다. 학교에서 특활 활동이 있었는데, 그 중에 하나가 “컴퓨터” 수업이었습니다. 처음에 MS-DOS와 윈도우에 대한 소개에 이어 워드스타와 로터스 스프레드시트를 어떻게 쓰는지 배웠습니다. (제가 좀 늙었습니다.)
그 후에 QBASIC으로 프로그래밍을 하게 되었습니다. 그리고 “월드 와이드 웹”을 소개 받고는 HTML을 배우고 어떻게 제 홈페이지를 만드는지 알게 되었습니다. 고등학교를 마친 뒤에 캐나다로 가서 컴퓨터 과학을 전공했구요.
파이썬을 사용하기 전에는 .NET 프레임워크와 C#으로 윈도우와 임베딩 애플리케이션들을 만들었습니다. 2008년에 윈도우 프로젝트를 진행하는 스타트업 회사에 있었는데, 프로젝트가 끝나고 나서 다른 팀으로 옮겨야 했습니다.
옮긴 팀에서는 웹 기반의 앱을 파이썬, [장고](https://realpython.com/tutorials/django/), 그리고 [구글 앱 엔진](https://realpython.com/python-web-applications/#google-app-engine)으로 만들고 있었습니다. 그 때 다른 회사를 알아보고 싶지 않아서, 그 팀에 머물러 파이썬을 배우며 웹 개발자로의 새로운 경력을 시작했습니다.

### **릭키:** 대부분은 당신을 파이썬 코어 개발자로 알고 있을겁니다. 올해 파이콘에서 [What is a Python Core Developer?](https://www.youtube.com/watch?v=hhj7eb6TrtI)라는 발표를 하기도 했고요. 발표를 듣지 못한 분들을 위해, 내용을 간단하게 얘기해주실 수 있을까요? 또, 코어 개발자로 당신의 역할에 대해서도요.
**마리아타:** 줄여서 얘기하자면, 파이썬 코어 개발자는 CPython에 코드를 작성하는 것 이상으로 많은 책임감을 필요로 한다는 것입니다. 사실 요즘에는 코어 개발자에게 코드를 작성하는 것을 별로 기대하지 않습니다. 코어 개발자는 직접 Pulll request를 작성하는 것보다 코드 리뷰, 멘토링, 피드백을 주고 의사 결정을 하는 일이 더 많습니다.
제가 강조하고 싶은 것은, 우리 모두 자원 봉사로 하고 있다는 것입니다. 저는 파이썬 코어 개발자로 [The PSF](https://www.python.org/psf-landing/)를 포함한 그 어떤 회사에도 고용되어 있지 않습니다. 아직 많은 분들이 이 점을 모르고 있습니다. 고객 지원 부서에 연락하듯 버그 트래커에 글을 남기고, 즉각적인 응답을 기대하고, 답을 하지 않으면서, 여러 문제로 우리를 비난하는 분들이 종종 있습니다. 우리는 자원봉사로 제한된 여가 시간에 이 일을 할 뿐인데, 몇 명 안되는 우리에 비해 사용자와 기여자는 수 백 수 천 명으로 너무 많습니다.
코어 개발자로서 저는 일의 진행을 돕는데 집중하고 있습니다. 특히 다른 코어 개발자와 기여자들이 더 쉽게 기여하고 협업할 수 있도록 하고 있습니다. 이를 위해서 [cherry_picker](https://pypi.org/project/cherry-picker/), [miss-islington](https://github.com/python/miss-islington) 같은 도구와, 최근에 [check_python_cla](https://check-python-cla.herokuapp.com/) 웹사이트도 만들었습니다.
그리고 첫 기여자들과 문서화와 관련된 이슈를 보고 있습니다. 저는 개발자 가이드 문서가 최신을 유지하도록 힘을 쏟는 것을 좋아하는데, 이는 기여자들이 작업하며 문제가 생겼을 때 가장 먼저 찾아볼 곳이기 때문입니다.
주간 파이썬 상담 시간(Python office hours)을 Zulipchat을 통해 진행하고 있습니다. **목요일 오후 7시(PST)**에 하고 있습니다. 상담 시간 동안 DM을 보내셔도 됩니다. 가능하면 실시간으로 답하고 도와드리려고 합니다. 다른 시간에는 Zulip을 하루에 한 번 정도 방문하는 편입니다.

### **릭키:** 파이 레이디스 밴쿠버 밋업과 파이 캐스케이드(PyCascades) 컨퍼런스의 운영자로도 활동하느라 몸이 여러 개여도 모자를 것 같습니다. 어떻게 이런 활동과 연관이 되었는지, 또 이런 모임에 참석한다면 어떤 걸 기대해도 좋을지 조금만 알려주실 수 있을까요?
**마리아타:** [파이 캐스케이드(PyCascades)](https://2019.pycascades.com/)가 어떻게 만들졌는지는 저조차도 확실치 않습니다. 제가 아는 것은 Seb이 저에게 이메일을 보냈고, 그래서 다른 사람들(Alan, Eric, Don, 그리고 Bryan)에게 저를 소개한 것 뿐입니다. 그 이메일 타래에 “태평양 북서부에서 파이썬 컨퍼런스를 해볼까요.” 라고 적힌게 전부입니다.
저는 곧바로 회신을 했습니다. 이 일에 대해 얼마나 책임져야 하는지, 또 얼마나 많은 노력을 기울여야 하는지 생각하지 않았었습니다. 그저 “왜 안돼?” 라고 했을 뿐이죠. 몇 주만에 밴쿠버에서 장소를 물색하지 시작했고, 나머지도 술술 굴러가기 시작했습니다.
파이 캐스케이드도 컨퍼런스의 한 종류입니다. 처음으로 발표하는 사람들과 태평양 북서부 지역의 커뮤니티의 발표자들을 중점적으로 다룹니다. 파이 캐스케이드 2019년의 발표자 모집(CFP)은 8월 20일부터 10월 말까지입니다. 여러분도 꼭 등록해주세요! 올해는 프로그램 선정 위원회에 참여하는대신 발표자를 지원하는 일을 맡았는데, 처음 발표하는 사람들과 잘 드러나지 않은 그룹에서 온 사람들에게 초점을 맞추려고 합니다.
파이 레이디스 [밴쿠버](http://www.pyladies.com/locations/vancouver/)를 도운지는 2년 밖에 되지 않았습니다. 처음에는 겨우 두 명이 – 그나마 있던 한 명도 그만두고 – 준비위원회를 모집했습니다. 당시 많은 모임에 참가하지는 않았지만, 파이콘에 참석하기 위한 재정지원을 받는데 파이 레이디스로부터 충분한 도움을 받았습니다. 도움을 받은 것을 커뮤니티에 갚기 위한 좋은 기회로 생각되어, 밴쿠버 파이 레이디스 커뮤니티에 지속적이며 적극적으로 참여하게 되었습니다. 다음 모임을 그저 앉아서 기다리는 대신에요.
저희 커뮤니티는 점점 커져가고 있습니다. 수 년간 있었던 저희의 이벤트들을 돌아보았는데, 정말 좋은 발표와 워크샵이 많았습니다. 저희 행사에도 파이썬 코어 개발자와 해외의 파이콘 발표자들도 참석하고 있고요. 자랑스럽게 생각합니다.

### **릭키:** 당신의 깃헙을 좀 살펴봤는데요, 봇(bot)과 제법 친하게 지내시는 것 같더군요. 깃헙에 있는 파이썬 코어 개발에도 두 개를 관리하고, 당신 계정에는 더 많고요. 이런 것들에 왜 매력을 느끼는지 여쭤봐도 될까요?
**마리아타:** 제가 처음으로 깃헙 봇을 소개하게 된건 2년 전에 coala에 기여하면서부터 입니다. 그 프로젝트는 봇을 관리자들을 돕는 개인 비서처럼 쓰고 있습니다. 봇은 항상 작동하고 있고, 댓글과 반응을 보입니다. 그때까진 봇이 이런 일들을 모두 할 수 있는지 몰랐었기 때문에 꽤 감동적이었고 어떻게 작동하는지 이해하는데 빠져들었습니다. 봇이 정말 복잡한 시스템이라고 생각했었거든요.
파이썬의 깃헙 봇을 만들고 관리하기 시작하면서, 봇의 구조에 대해 더 잘 이해하게 되었고, 깃헙 봇이 어떻게 동작하는지에 대한 제 호기심도 충족할 수 있었습니다.
그때부터 다르게 생각해보게 되었습니다. 이제 어떻게 동작하는지 알고, 어떤 깃헙 API를 사용할 수 있는지 알고나니, 스스로에게 계속 되물었습니다. “뭘 자동화 할 수 있을까? 봇에게 뭘 더 위임할 수 있지? 자동화의 정점에 이른건 아니겠지?” 자동화를 할 수 있는 훨씬 더 많은 일들이 있었고, 제가 필요한건 파이썬이면 충분했습니다. 이젠 어떤 일들을 봇으로 자동화 할 수 있는지 알게되다보니, 따분한 일을 해야할 때 아무래도 성질이 나빠지게 됩니다.

### **릭키:** 당신과 인터뷰 하면서 아무래도 아이스크림 셀카를 얘기하지 않을 수 없는데요. 이젠 당신의 상징과도 같아졌습니다. 아직 잘 모르는 독자가 있을 수도 있으니, 아이스크림 셀카 – [\#icecreamselfie](https://mariatta.ca/category/icecreamselfie.html)에 대해 설명을 부탁드립니다.
**마리아타:** 첫번째 [\#icecreamselfie](https://mariatta.ca/category/icecreamselfie.html)는 필라델피아에서 2016년 7월에 열린 장고콘(DjangoCon)에서 였습니다. 생에 처음으로 컨퍼런스에서 발표를 했었고 기분이 너무 좋아 축하해야겠다는 생각이 들었습니다. 그리고 엄청 더운 날이기도 했죠. 그래서 호텔 근처의 아이스크림 가게로 찾아갔습니다. 어쩐지, 아이스크림을 들고 셀카를 찍고 싶어졌습니다. 평소에는 잘 하지 않는데 말이죠. 보통은 셀카를 찍지 않고 음식을 찍는 편입니다.
다음 발표는 푸에르토리코의 파이 캐리비안이었습니다. 아이스크림은 생각조차 하지 않고, 저와 제 룸메이트, 다른 발표자였던 Kim Crayton과 해변을 즐기고 있었습니다. 근데 갑자기 아이스크림 카트가 짠–하고 나타난거죠. 
그 다음에는 장고콘 유럽과 파이콘 이탈리아를 위해 이탈리아를 방문했습니다. 물론 젤라또를 먹었습니다. 그러지 않고는 이탈리아를 여행했다고 할 수 없으니까요. 그 때만 해도 #icecreamselfie가 전통이 될 줄 몰랐습니다. 셀카는 이제 우연한 일 이상이 되었습니다.
꽤나 감정적인 발표였던 파이콘 US의 발표를 마친 후에 제 머릿속에는 아이스크림 밖에 없었습니다. 그래서 제 친구 제프가 포틀랜드에서 그가 알고 있는 곳으로 저를 데려갔습니다. 아이스크림을 먹고 나니 기분이 좋아졌습니다! 그때부터는 #icecreamselfie 가 저의 공식적인 전통이 되었고, 발표가 정해지기만 하면 최고의 아이스크림을 찾는데 굉장히 공을 들이고 있습니다.

### **릭키:** 자, 이제 마지막 질문입니다. 파이썬 외에 다른 취미나 흥미가 있다면? 공유하거나 연결해주고 싶은 사람이 있을까요?
**마리아타:** 저는 걷고, 여행하고 캠핑하는 것을 좋아합니다. 제 음식을 찍어 인스타그램에 올리는 기이한 취미를 가지고 있고요. 다른 취미로는 마작을 합니다. 보통의 마작 게임이 아니라 홍콩 스타일의 마작입니다. 저 말고 이 게임을 하는 사람을 찾기가 어렵네요.
저를 돕는데 관심이 있는 분은, [happiness packet](https://www.happinesspackets.io/)를 보내주시거나, [Patreon](https://www.patreon.com/Mariatta)을 통해 후원해주셔도 되고, [just say thanks](https://saythanks.io/to/Mariatta)만 해주셔도 좋습니다.

----

인터뷰를 해준 마리아타에게 감사합니다. 마리아타에게 더 궁금한 것이 있다면 마리아타의 [트위터](https://twitter.com/mariatta)와 [홈페이지](https://mariatta.ca/)를 찾아보세요.