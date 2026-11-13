# 몰아보기 플래너

영화관·영화제 상영 시간을 직접 입력해 상영관별 시간표로 모아 보고, 볼 영화를 담으면 시간이 겹치는지 알려주는 페이지입니다.
파일 하나(`index.html`)로 동작하며 서버가 필요 없습니다. 입력한 내용은 사용하는 브라우저에만 저장됩니다.

## GitHub Pages로 공개하기

1. GitHub에 로그인 → 오른쪽 위 **+** → **New repository**
2. Repository name에 `marathon-planner` 입력, **Public** 선택 → **Create repository**
3. 새 저장소 화면에서 **uploading an existing file** 클릭
4. `index.html`과 `README.md`를 끌어다 놓고 → 아래 **Commit changes**
5. 저장소 상단 **Settings** → 왼쪽 **Pages**
6. Source: **Deploy from a branch**, Branch: **main** / **/(root)** → **Save**
7. 1~2분 뒤 `https://<GitHub 아이디>.github.io/marathon-planner/` 에서 열립니다

## 수정할 때

저장소에서 `index.html` 클릭 → 연필 아이콘(Edit) → 고친 뒤 **Commit changes**.
또는 새 `index.html`을 다시 업로드하면 덮어씌워집니다. 반영까지 1~2분 걸립니다.

## 입력 형식 (붙여넣기)

엑셀·구글 시트에서 아래 순서의 열을 복사해 붙여넣습니다. 탭이나 쉼표로 구분합니다.

```
날짜        시작   끝     제목   극장·상영관      예매 링크(선택)
2026-11-21  10:30  12:21  하녀   서울아트시네마   https://...
```
