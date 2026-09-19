# Log Server 모드팩 배포

[packwiz](https://packwiz.infra.link/) 팩을 GitHub Pages 로 서빙한다.
**이 저장소는 자동 생성된다 — 직접 고치지 말 것.**

원본과 배포 스크립트는 `ServerMod/modpack/` 에 있다.

```
cd ServerMod
./gradlew build
python modpack/tools/release.py
python modpack/tools/publish.py --push
```

`.nojekyll` 은 Jekyll 이 파일을 건드리지 않게 막는 것이다. 지우지 말 것.
