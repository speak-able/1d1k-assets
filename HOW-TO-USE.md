# 1d1k-assets 사용 가이드

## 이 폴더는?
캐릭터 이미지를 GitHub Pages로 호스팅하기 위한 폴더예요.
여기에 이미지를 넣고 push하면 웹 URL로 접근할 수 있어요.

## 이미지 URL 규칙
```
https://speak-able.github.io/1d1k-assets/{폴더}/{파일명}
```

예시:
- `economy/cat-economy.png` → `https://speak-able.github.io/1d1k-assets/economy/cat-economy.png`


## 새 이미지 추가하는 법 (3단계)

### 1단계: 파일 넣기
해당 폴더에 이미지 파일을 복사해요.
- 경제 관련 → `economy/`
- 영어 관련 → `english/`
- 새 카테고리 → 폴더 새로 만들면 돼요

### 2단계: 터미널에서 업로드
```bash
cd "C:/Users/insig/OneDrive/[Claude]/assets"
git add .
git commit -m "Add 새이미지 설명"
git push
```

### 3단계: 확인
브라우저에서 URL 열어서 이미지 잘 보이는지 확인!


## 현재 이미지 목록

### economy/
| 파일 | 설명 | 크기 |
|------|------|------|
| cat-economy.png | 넥타이+계산기 경제냥 | 27KB |
| cat-celebrate.png | 동전+축하 경제냥 | 33KB |
| cat-stock.png | 안경+차트 주식냥 | 21KB |

### english/
| 파일 | 설명 | 크기 |
|------|------|------|
| cat-bbc.png | 헤드셋 BBC냥 | 11KB |
| cat-friends.png | 소파 프렌즈냥들 | 15KB |
| cat-harry.png | 목도리 해리포터냥 | 8KB |
| cat-office.png | 사무실 오피스냥들 | 88KB |
| cat-pride.png | 빅토리안 오만과편견냥들 | 126KB |


## 참고
- 이 폴더는 `speak-able/1d1k-assets` (public) 리포의 클론이에요
- `[Claude]/` 루트의 `1d1k-content` (private) 리포와는 별개예요
- `.gitignore`에 `assets/` 추가되어 있어서 서로 충돌 없어요
