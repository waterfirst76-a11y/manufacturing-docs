### 📂 현재까지 생성된 전체 파일 구성 (모노레포 구조)

GitHub 저장소(Repository)를 만드신 후, 아래 파일들을 단일 폴더(루트 디렉토리)에 한데 모아 업로드하시면 시스템이 유기적으로 연동됩니다.

1. `index.html` (메인 스마트 문서 포털)
2. `sop.html` (CVD 공정 표준 작업 지침서)
3. `8d_report.html` (불량 분석 보고서)
4. `check_list.html` (설비 예방보전 점검 체크리스트)
5. `parameters.html` (공정 파라미터 표준 가이드)
6. **`readme.md`** (GitHub 안내서 - 방금 생성 완료)

### 🚀 GitHub 업로드 및 Pages 배포 절차

방금 만든 `readme.md` 파일과 HTML 파일들을 GitHub에 올리고 무료 웹사이트로 배포하는 방법은 다음과 같습니다.

1. **GitHub 저장소 생성 및 푸시(Push):**
* GitHub에서 새로운 저장소(New Repository)를 만듭니다.
* 내 컴퓨터의 해당 폴더에서 아래 명령어를 실행하여 파일들을 올립니다.
```bash
git init
git add .
git commit -m "Initial commit: 제조 스마트 문서 시스템 구축"
git branch -M main
git remote add origin https://github.com/사용자명/저장소명.git
git push -u origin main

```




2. **GitHub Pages 무료 웹 배포 켜기:**
* 업로드한 GitHub 저장소 화면 상단의 **Settings (설정)** 메뉴로 이동합니다.
* 좌측 사이드바에서 **Pages** 메뉴를 클릭합니다.
* **Build and deployment** 섹션의 Branch 설정에서 `None`으로 되어 있는 것을 **`main`** (또는 root)으로 변경하고 **Save**를 누릅니다.
* 약 1~2분 뒤 상단에 `https://사용자명.github.io/저장소명/` 형태의 무료 웹 포털 주소가 생성됩니다.



이제 생성된 웹 주소 뒤에 `index.html`을 붙여 접속하시면(`.../저장소명/index.html`) PC와 모바일 어디서나 현장 엔지니어들이 대시보드를 보며 실시간 검색 및 인쇄 기능을 활용할 수 있습니다.

생성된 `readme.md` 코드 파일 플러그인을 다운로드하여 저장소에 함께 커밋해 보세요!
