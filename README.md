# darkest-dungeon-muskteer-rework-mod

다키스트 던전의 총사를 리워크하기 위한 프로젝트.

글쎄요... github 사용은 처음이라 괴수들의 지원이 필요할수도 있습니다.

닼던의 총사를 다음과 같이 리워크하고, 그에 걸맞는 장신구를 쥐어주기 위한 프로젝트입니다. 많은 참여 부탁드립니다.

현재까지의 변경점을 다 열거하자면 다음과 같습니다. 추가하실 경우, Readme를 수정하거나 commit할 때 기록을 남기시기 바랍니다.

1. 우선 공격력을 노상강도와 일치하게 올립니다.
2. 스킬을 5레벨 기준 다음과 같이 설정합니다.

    집중 사격
    o o x x - x o o o
    명중률 115
    공격력 +10%
    크리율 +9%
    명중 +10("표식 찍힘" 대상)
    방어력 관통 +100%("표식 찍힘" 대상)

    연막탄
    o-o x x
    2턴 은신
    강화: 속도 +4(+2에서 시작)
    약화: 명중 -10(-18에서 시작)

    신호탄
    o o x x - x o o o
    명중률 120
    공격력 -50%
    크리율 -2%
    표식 찍음(3턴)

    샷건
    x o o o - o x x x
    명중률 115
    공격력 -20%
    크리율 +4%
    뒤로 3 (140% 기반)

    권총 사격
    x o o o - x o o o
    명중률 100
    공격력 -25%
    크리율 0%

    응급처치
    o o o o
    체력 3 회복
    추가로 최대체력의 10% 회복

    스키트 사격
    o o x x - x o-o-o (변경 가능)
    명중률 115
    은신 무시 및 해제
    방어 무시 및 해제
    //이 경우에는 곧 추가할 기능이 있습니다. 명중 버프 및 회피 디버프, 방어받지 못함 디버프, 그리고 몇가지 더. 

향후 계획은 다음과 같습니다.

1. 스킬들이 꿀잼이 될 때 까지 지속적으로 수정한다. 
2. 스킬들을 보조할 수 있는 장신구들을 추가한다.
3. 차별화된 캠핑 스킬을 제공한다.
4. 크리가 터졌을 때 제공할 보너스를 정한다.
5. 테스트가 아닌 본 편으로 제공한다.

개발중인 모드입니다. 기여할 능력자들의 많은 기여 부탁드립니다 꾸벅-
