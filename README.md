# 옆집 싸움구경

버섯들이 뿅망치와 물총으로 벌이는 최대 4인 온라인 난투 게임 (Windows).

- 다운로드 페이지: https://zzangyool.github.io/TheyFight/
- 최신 버전 바로 받기: https://github.com/zzangyool/TheyFight/releases/latest/download/TheyFight-Windows.zip

## 이 저장소

- `index.html`, `img/`: GitHub Pages 다운로드 페이지
- 게임 파일(zip)은 저장소가 아니라 **GitHub Releases**에 올린다. 다운로드 버튼은 항상 최신 릴리스의 `TheyFight-Windows.zip`을 가리킨다.

## 새 버전 올리기

1. 원본 Unity 프로젝트에서 `PartyGame > Build Windows (Client + Server)` → `Builds/TheyFight-Windows.zip` 생성
2. `gh release create v0.x.y Builds/TheyFight-Windows.zip --repo zzangyool/TheyFight --title "v0.x.y" --notes "바뀐 점"`
3. 필요하면 `index.html`의 버전/크기 표시를 고치고 push
