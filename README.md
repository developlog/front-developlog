# Vscode Extention
- Auto import
- Eslint
- Prettier - Code formatter
- Reactjs code snippets
- vscode-styled-components

# 초기 개발 환경 작업
- node_modules 삭제
- package-lock.json 삭제
- $ npm install

# Git convention
- commit convention
  > Tag Name: Description<br>
  > ex) Feat: Add login page

| Tag Name | Description      |
| -------- | ---------------- |
| Feat     | 새로운 기능 추가  |
| Fix      | 버그 수정         |
| Docs     | 문서 수정         |
| Style    | 포맷,  세미콜론 수정, Optimize import, Code clean up 등 코드가 아닌 스타일에 관련된 수정 |
| Test     | 테스트 코드 추가   |
| chore    | 빌드 관련 업무 수정 |

- branch convention
 > ex) feature/login

# Git 사용법
1. git clone https://github.com/developlog/front-developlog.git
2. cd [project folder]
 > $ pm install
3. git branch 
 > feature/login
4. git checkout feature/login
 > git status (상태확인) 
 > git log (기록 확인, git log --graph 그래프 화)
5. 코드 작성 
6. 코드 작성 완료
7. git add . (모든 파일 스테이지로 이동)
8. git commit -m "상태: 컨벤션"
 > git commit -m "feat: Update readme.md"
9. git push origin feature/login
10. PR(pull request) 작성 
 > https://github.com/developlog/front-developlog 이동
 > Pull requests 클릭
 > New pull request 클릭
 > dev <- feature/login 으로 변경
 > commit 탭에서 의도한 커밋이 다 푸쉬 되었는지 확인
 > 컨벤션 메시지 작성
 > 개발자 타 팀원 승인 없이 merge 가능 (1인 이상 승인해야 merge 할 수 있게 하는 기능도 있음)
11. git checkout dev (로컬 dev 브런치로 이동)
12. git pull origin dev (dev 브런치에 개발한 내역을 merge 하였으므로 저장소 dev의 변경 사항 pull 받기)
13. git branch feature/[추가 개발]
14. git checkout feature/[추가 개발] - 반복


