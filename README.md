# DS-Starter-Kit
DS-Starter 수업용 스타터킷 ZIP 배포 (Storybook Starter Kit download)

최신 ZIP: https://github.com/DearKim/DS-Starter-Kit/releases/latest/download/DS-Starter.zip

## 릴리스는 자동으로 올라갑니다

1. `DearKim/DS-Starter`의 `education` 브랜치에 push 하면, 그 저장소의 워크플로가 이 저장소의 `release-request.json`에 커밋을 기록합니다.
2. 이 저장소의 워크플로(`.github/workflows/publish-starter-zip.yml`)가 그 커밋으로 `git archive` ZIP을 만듭니다.
3. 최신 릴리스와 파일 이름·크기·CRC가 다를 때만 `education-<커밋>` 릴리스를 새로 올립니다.

사전 준비 페이지의 버전 표시(커밋·날짜)는 새 릴리스가 올라오면 손으로 맞춰야 합니다.
