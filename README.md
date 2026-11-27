<img width="458" height="665" alt="image" src="https://github.com/user-attachments/assets/0ba17c84-b285-411a-81ed-5926e797ed63" />

# on-writing

스티븐 킹의 『유혹하는 글쓰기』에서 소개한 집필/퇴고 원칙을 소설, 에세이, 리서치 아티클에 적용하는 한국어 Agent Skill입니다. 메모를 주면 초안을 쓰고, 원고를 주면 필자의 어조를 살려 고칩니다. 피드백만 요청하면 독자가 어디에서 멈칫할지 짚어 줍니다.

## Codex에 설치하기

터미널에서 다음 명령을 실행하면 내 계정의 여러 프로젝트에서 사용할 수 있습니다.

```sh
mkdir -p "$HOME/.agents/skills"
git clone https://github.com/rejamong/on-writing-kor.git "$HOME/.agents/skills/on-writing"
```

ZIP 파일로 받았다면 압축을 푼 뒤 `on-writing` 폴더를 `~/.agents/skills/` 아래에 복사해도 됩니다.

설치한 뒤 Codex 대화에서 `$on-writing`과 함께 요청을 입력하세요. 다른 설치 위치는 [공식 스킬 가이드](https://developers.openai.com/codex/skills/)에서 확인할 수 있습니다.

## Claude에 설치하기

Claude Code에서는 `on-writing` 폴더를 `~/.claude/skills/` 아래에 두면 됩니다.

```sh
mkdir -p "$HOME/.claude/skills"
git clone https://github.com/rejamong/on-writing-kor.git "$HOME/.claude/skills/on-writing"
```

Claude 앱에서는 `on-writing` 폴더를 ZIP으로 묶어 설정의 스킬 메뉴에서 올립니다. Claude에서는 `$on-writing` 없이 “유혹하는 글쓰기 방식으로 퇴고해 줘”처럼 책이나 스티븐 킹을 지정해 요청하세요.

## 사용 예시

- **소설** · `$on-writing 폐업을 앞둔 세탁소에 마지막 손님이 들어오는 장면을 네 문장으로 써 줘.`
- **에세이** · `$on-writing 이 초안에서 독자가 다음 문단을 궁금해할 만한 지점을 찾아 줘. 지금은 피드백만 줘.`
- **리서치** · `$on-writing 아래 도입부를 퇴고해 줘. 표본 범위, 수치, 출처와 추정의 강도는 살려 줘.`

가령 “수수료 개편이 이루어진 이후 거래 건수가 약 20% 정도 증가하는 모습을 보였다”는 “수수료 개편 후 거래 건수는 약 20% 늘었다”로 다듬습니다. 고친 문장에도 시점과 ‘약’이 남아 있습니다.

## 출처와 라이선스

킹의 책과 공개 자료에서 확인한 창작 원칙을 바탕으로 한국어 지침과 예문을 작성했습니다. 리서치에서 수치와 근거를 다루는 절차, 한국어 번역투 목록, 피동과 부사에 둔 예외는 이 프로젝트의 응용입니다. [전체 지침과 참고 자료](SKILL.md#원칙의-출처)

이 저장소의 지침과 예문은 [MIT 라이선스](LICENSE)로 배포합니다. 링크된 책과 외부 자료에는 각 자료의 이용 조건이 적용됩니다.
