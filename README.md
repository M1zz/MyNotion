# 📚 MyNotion

> `mizzking75@gmail.com` 계정의 Notion 워크스페이스를 GitHub으로 이관한 저장소

## 📁 폴더 구조

```
docs/
├── README.md          # 전체 목차
├── Meta/              # 큰 그림, 메타데이터
├── Community/         # 커뮤니티 관련
├── Course/            # 강의 커리큘럼
├── Dev/               # 개발 학습 자료
├── Marketing/         # 앱 마케팅/운영
└── Design/            # 디자인 관련
```

## 🔄 추후 자동 동기화

이 저장소에 Notion 자동 동기화를 설정하려면:

1. [Notion 통합 만들기](https://www.notion.so/my-integrations) → API 키 발급
2. GitHub repo → **Settings → Secrets → Actions** → `NOTION_API_KEY` 등록
3. `.github/workflows/notion-sync.yml` 활성화

---

*최초 이관일: 2026-03-05*  
*원본 Notion 루트: https://www.notion.so/leeo75/6ec8d1cbf1ea43148fbb17cbc8339d3e*
