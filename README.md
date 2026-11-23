# bokjikkultong-media

복지꿀통 발행 미디어 공개 호스팅 — Instagram · Threads Graph API 가 직접 내려받는 **공개 URL** 제공용.

- URL 규칙: `https://gimdevelope.github.io/bokjikkultong-media/episodes/<회차 슬러그>/<파일명>`
- 올리기: `python3 work/bokjikkultong-video/scripts/media_host.py push --episode <슬러그> --file <파일> ...`
- 확인: `python3 work/bokjikkultong-video/scripts/media_host.py check --url <URL>` (200 이면 정상)
- `.nojekyll` 이 있어 Jekyll 처리를 끕니다. 없으면 `_` 로 시작하는 폴더(`episodes/_selftest` 등)가 빌드에서 빠져 404 가 됩니다.
- 용량 참고: Pages 권고 1GB. 하루 mp4 1개 + png 4장 ≈ 10MB → 3개월마다 오래된 회차 정리.
- 공개 저장소다. 발행본만 올린다. 원본 편집 파일·개인정보 파일 금지.

개인정보처리방침: https://gimdevelope.github.io/bokjikkultong-media/privacy.html
