# hanssam 공유 문서

이 저장소는 HTML 문서를 GitHub Pages로 자동 배포합니다.

## 새 문서 배포

1. 공유 승인을 받은 HTML 파일을 이 폴더에 추가합니다.
2. `index.html`에서 새 문서로 연결합니다.
3. 변경 사항을 `main` 브랜치에 커밋하고 푸시합니다.
4. GitHub Actions의 **Deploy GitHub Pages**가 완료되면 공개 주소에서 확인합니다.

> 성도 개인정보, 심방·상담 내용, 비공개 설교 원고는 이 공개 저장소에 올리지 않습니다.

## 로컬 명령

```bash
git add .
git commit -m "Publish HTML document"
git push origin main
```
