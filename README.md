# 336:60 GitHub → Cloudflare Pages

업로드 구조:

- index.html
- images/
  - 33660-wrap-cheese.webp
  - 33660-wrap-spicy.webp
  - 33660-soymilk.webp
  - 33660-interior.webp
  - 33660-sign.webp
  - 33660-dryaging.webp
  - 33660-dryaging-window.webp

Cloudflare Pages 설정 권장값:

- Production branch: main
- Framework preset: None
- Build command: exit 0
- Build output directory: .

주의: ZIP 자체를 GitHub에 올리지 말고 압축을 푼 뒤 `index.html`과 `images` 폴더를 저장소 최상단에 올립니다.
