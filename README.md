# 336:60 GitHub / Cloudflare Pages 배포용

이 폴더 안의 **내용물만** GitHub 저장소 루트에 업로드하세요.

구조:

```
index.html
images/
  33660-wrap-cheese.webp
  33660-wrap-spicy.webp
  33660-soymilk.webp
  33660-interior.webp
  33660-sign.webp
  33660-dryaging.webp
  33660-dryaging-window.webp
```

## GitHub 업로드
1. 저장소의 Upload files 화면에서 ZIP을 압축 해제한 뒤 `index.html`과 `images` 폴더를 함께 드래그합니다.
2. 아래 `Commit changes`를 눌러 업로드합니다.

## Cloudflare Pages
- Framework preset: None
- Build command: 비워두기
- Build output directory: `/` 또는 비워두기(현재 UI에 따라 다름)

## 배포 후 권장
실제 도메인이 정해지면 `index.html`의 canonical과 OG 이미지 URL을 절대주소로 바꾸는 것이 좋습니다.
