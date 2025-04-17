브랜치 관리 - 서로의 작업에 영향을 주지 않기 위해
브랜치 분리. main 브랜치는 배포를 위해 관리하기 때문에 철저히 안전한 관리가 필요함.
브랜치 보호 규칙 - 브랜치를 안전하게 관리하기 위해 필요.
브랜치 전략 - Git Flow, GitHub Flow (이 두개 외에도 다양한 방법 존재)
Git Flow - 크게 5가지 브랜치로 나눔. Main Branches 는 절대 지우지 않음. supporting branches 는 사용한 후 지움. 
main - 기본 브랜치. 브랜치 보호 규칙 적용. 
develop - feature 브랜치의 기반.
feature - develop에서 분기하여 작업. 작업 후 develop으로 다시 병합.
release - 배포를 위한 브랜치.
hotfix - 급한 수정. main 브랜치에서 분기.
Git Flow 단점 - 배포가 수시로 이뤄지는 현재의 웹앱과는 부적합함.
GitHub Flow - 책임이 좀 더 필요한 과정.