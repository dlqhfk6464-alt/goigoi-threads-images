# goigoi-threads-images

`@goigoi.pick` Threads 자동 발행용 공개 이미지 저장소입니다.

- `images/` : 발행에 쓰는 사진 (파일명은 `주제_YYYYMMDD.jpg`)
- Threads API 는 공개 URL 만 받을 수 있어서, 스케줄러(`goigoi-threads-scheduler`)가 아래 형식의 raw 주소를 `image_url` 로 사용합니다.

```
https://raw.githubusercontent.com/dlqhfk6464-alt/goigoi-threads-images/main/images/<파일명>.jpg
```

사진은 일상 실사 스냅 기준(흰 배경 제품 누끼컷·영어 라벨·워터마크·얼굴 없음)으로 검수한 것만 올립니다.
