# Watcher
VS-Code 리눅스 인스턴스에서의 작업 내역 추적 시스템

## Author
전북대학교 컴퓨터공학부 박현찬
hyunchan.park@jbnu.ac.kr


## WATCHER
### What is Watcher
Watcher 는 프로그래밍 과제의 공정한 진행을 돕기 위해 만들어졌습니다.

전북대 컴퓨터공학부에서는 J-Cloud 상에 동작하는 VS-Code WebIDE 환경을 제공하고 있습니다.
이러한 Web IDE는 편리하고 일관된 개발 환경을 제공하고, 
교수자 및 수업 조교에게 학생들의 코드에 쉽게 접근하도록 하여 보다 간편하게 학생들 작업을 도울 수 있습니다.

Watcher 는 학생들이 VS-Code 에서 작업하는 코드의 변경 이력을 추적할 수 있습니다.
학생 각각의 코드 변경 사항을 1초마다 기록하여 Watcher 서버에 전송함으로써,
코드가 변경되어온 이력을 모두 확인해볼 수 있습니다.

이력 변경 내용은 아래와 같이 Animated GIF로 자동 변환되어 보관되고,
교수자 및 수업 조교가 시각적으로 쉽게 이상 유무를 파악할 수 있습니다.
이에 더해 소스 파일들의 변경 내용을 분석하여 이상 유무를 즉각 리포팅 하는 기능도 준비 중입니다.

![Animated GIF example](https://raw.githubusercontent.com/hyunchan-park/JBNU-Watcher/master/test/code.gif)

이러한 시스템은 학생들의 과제 수행 내역을 보다 공정하게 평가하는데 도움을 주고,
결국 학생들에게 프로그래밍 수업의 평가가 공정하게 이루어지고 있다는 신뢰를 줄 수 있습니다.
또한 교수자에게는 부정 행위를 검사하기 위한 수고를 줄여줄 수 있습니다.

### Status

2020년 11월 현재, 초기 파일럿 버전을 개발 완료하여
박현찬 교수가 운영하는 유닉스 프로그래밍 수업에 일부 활용하고 있으며,
향후 지속적으로 보완해나갈 예정입니다.

이를 위해 학부생들의 참여를 독려하고 있으며,
3학년 오픈소스 SW 개발 수업에서 몇몇 학생들이 참여하여 프로젝트에 기여하고 있습니다.
다른 관심있는 학생들도 GitHub를 통해 얼마든지 참여할 수 있으니 연락주시기 바랍니다.

## Related Links
J-Cloud: http://jcloud.jbnu.ac.kr
J-Cloud help page: https://jcloud-devops.github.io/
