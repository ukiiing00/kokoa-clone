# Kokoa Clone 2023 

My first HTML & CSS


## Block_Element--Modifier (BEM)

## Position : absolute
이 요소는 일반 문서 흐름에서 제거되며 페이지 레이아웃에서 해당 요소를 위한 공백이 생성되지 않습니다. 가장 가까운 위치에 있는 조상이 있는 경우 그 조상을 기준으로 배치되며, 그렇지 않은 경우 처음 포함된 블록을 기준으로 배치됩니다. 최종 위치는 위쪽, 오른쪽, 아래쪽, 왼쪽 값에 의해 결정됩니다.

position : relative; 조상에서 설정 

## Margin : auto
브라우저는 사용할 적절한 여백을 선택합니다. 예를 들어 특정 경우 이 값을 사용하여 요소를 가운데에 배치할 수 있습니다.

## z-index : auto, integer
z-index CSS 속성은 배치된 요소와 그 하위 요소 또는 플렉스 항목의 z 순서를 설정합니다. z-인덱스가 큰 요소와 겹치는 요소는 작은 요소를 덮습니다.

위치가 지정된 상자(즉, 정적이 아닌 다른 위치의 상자)의 경우 z-index 속성이 지정합니다:

현재 스택 컨텍스트에서 상자의 스택 레벨입니다.
상자가 로컬 스택 컨텍스트를 설정하는지 여부입니다.

## display : flex
can you explain more why message bubble and message time have different heights when you apply 'display: flex; on their parent?

Because the bubbles are spans, so they are inline, but when I make their parent flex they are not inline anymore and box model applies.