# SuperRace Store Images

네이버 스마트스토어 상세페이지 이미지 호스팅 저장소

## 이미지 URL 형식

```
https://raw.githubusercontent.com/minsuk888/superrace-store-images/main/[경로]
```

---

## 폴더 구조

```
superrace-store-images/
└── hat/                    # 레이싱 캡
    ├── hero/               # 히어로 배너, 로고
    ├── main/               # 메인 제품샷 (860×860 권장)
    ├── gallery/            # 앵글 갤러리 (front, side, back, detail)
    └── thumb/              # 썸네일
```

---

## 이미지 슬롯별 URL 목록

### 🧢 레이싱 캡 (hat)

| 슬롯 | 경로 | 권장 크기 | Raw URL |
|------|------|-----------|---------|
| 로고 | `hat/hero/logo.png` | 200×60 | `https://raw.githubusercontent.com/minsuk888/superrace-store-images/main/hat/hero/logo.png` |
| 메인샷 | `hat/main/main.jpg` | 860×860 | `https://raw.githubusercontent.com/minsuk888/superrace-store-images/main/hat/main/main.jpg` |
| 정면 | `hat/gallery/front.jpg` | 600×600 | `https://raw.githubusercontent.com/minsuk888/superrace-store-images/main/hat/gallery/front.jpg` |
| 측면 | `hat/gallery/side.jpg` | 600×600 | `https://raw.githubusercontent.com/minsuk888/superrace-store-images/main/hat/gallery/side.jpg` |
| 후면 | `hat/gallery/back.jpg` | 600×600 | `https://raw.githubusercontent.com/minsuk888/superrace-store-images/main/hat/gallery/back.jpg` |
| 디테일1 | `hat/gallery/detail-1.jpg` | 600×600 | `https://raw.githubusercontent.com/minsuk888/superrace-store-images/main/hat/gallery/detail-1.jpg` |
| 디테일2 | `hat/gallery/detail-2.jpg` | 600×600 | `https://raw.githubusercontent.com/minsuk888/superrace-store-images/main/hat/gallery/detail-2.jpg` |
| 디테일3 | `hat/gallery/detail-3.jpg` | 600×600 | `https://raw.githubusercontent.com/minsuk888/superrace-store-images/main/hat/gallery/detail-3.jpg` |
| 썸네일 | `hat/thumb/thumb.jpg` | 300×300 | `https://raw.githubusercontent.com/minsuk888/superrace-store-images/main/hat/thumb/thumb.jpg` |

---

## 이미지 업로드 방법

1. GitHub 웹에서 해당 폴더로 이동
2. `Add file` → `Upload files` 클릭
3. 파일 업로드 후 `Commit changes`
4. 위 URL 표의 Raw URL을 HTML `src=""` 에 붙여넣기
