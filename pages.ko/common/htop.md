# htop

> 실행 중인 프로세스에 대한 동적 실시간 정보를 표시합니다. `top`의 향상된 버전입니다.
> 더 많은 정보: <https://htop.dev/>.

- `htop` 시작:

`htop`

- 특정 사용자가 소유한 프로세스를 표시하는 `htop`을 시작합니다:

`htop --user {{사용자 이름}}`

- 지정된 `sort_item`을 기준으로 프로세스를 정렬합니다(사용 가능한 옵션을 보려면 `htop --sort help`을 사용):

`htop --sort {{sort_item}}`

- 업데이트 사이에 지정된 지연(10분의 1초)으로 `htop`을 시작(예: 50 = 5초):

`htop --delay {{50}}`

- htop을 실행하는 동안 대화형 명령 확인:

`?`

- 다른 탭으로 전환:

`tab`

- 도움말 표시:

`htop --help`