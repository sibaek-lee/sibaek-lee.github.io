# Keyword Color Mapping

이 파일은 키워드별 색상 매핑을 관리합니다.

## 현재 할당된 키워드 (1-20)

| 키워드 | 색상 번호 | 색상 |
|--------|-----------|------|
| nerf | 1 | Blue (#007bff) |
| 3d representation | 2 | Green (#28a745) |
| bayesian learning | 3 | Cyan (#17a2b8) |
| vision language model | 4 | Yellow (#ffc107) |
| robot navigation | 5 | Red (#dc3545) |
| 3d perception | 6 | Gray (#6c757d) |
| embedded systems | 7 | Orange (#fd7e14) |
| gaussian process | 8 | Purple (#6f42c1) |
| scene representation | 9 | Pink (#e83e8c) |
| loop closing | 10 | Teal (#20c997) |
| place recognition | 11 | Dark Gray (#495057) |
| deep learning | 12 | Saddle Brown (#8B4513) |
| slam | 13 | Sea Green (#2E8B57) |
| computer vision | 14 | Tomato (#FF6347) |
| machine learning | 15 | Steel Blue (#4682B4) |
| robotics | 16 | Medium Purple (#9370DB) |
| neural networks | 17 | Lime Green (#32CD32) |
| optimization | 18 | Deep Pink (#FF1493) |
| sensor fusion | 19 | Dark Turquoise (#00CED1) |
| autonomous systems | 20 | Dark Orange (#FF8C00) |

## 새 키워드 추가하기

1. `_layouts/bib.liquid`의 `keyword_map` 변수에 `new_keyword:번호` 추가
2. `_includes/selected_papers.liquid`에 필터 버튼 추가
3. 필요시 `_sass/_keyword-filter.scss`에 새 색상 클래스 추가

## 코드 위치

- **키워드 매핑**: `_layouts/bib.liquid:192`
- **필터 버튼**: `_includes/selected_papers.liquid:1-15`
- **색상 정의**: `_sass/_keyword-filter.scss:1-21`