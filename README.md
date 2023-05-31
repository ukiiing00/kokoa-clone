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

## order
order CSS 속성은 플렉스 또는 그리드 컨테이너에 항목을 배치할 순서를 설정합니다. 컨테이너의 항목은 오름차순 값을 기준으로 정렬된 다음 소스 코드 순서에 따라 정렬됩니다.

## @keyframes
키프레임 CSS at-규칙은 애니메이션 시퀀스에서 키프레임(또는 웨이포인트)에 대한 스타일을 정의하여 CSS 애니메이션 시퀀스의 중간 단계를 제어합니다. 이를 통해 애니메이션 시퀀스의 중간 단계를 트랜지션보다 더 강력하게 제어할 수 있습니다.

## transform
변형 CSS 속성을 사용하면 요소를 회전, 크기 조정, 기울이기 또는 번역할 수 있습니다. CSS 시각적 서식 모델의 좌표 공간을 수정합니다.

## animation
The animation shorthand CSS property applies an animation between styles. It is a shorthand for animation-name, animation-duration, animation-timing-function, animation-delay, animation-iteration-count, animation-direction, animation-fill-mode, and animation-play-state.

## will-change
변경 예정 CSS 속성은 요소가 어떻게 변경될지 브라우저에 힌트를 줍니다. 브라우저는 요소가 실제로 변경되기 전에 최적화를 설정할 수 있습니다. 이러한 종류의 최적화는 실제로 필요하기 전에 잠재적으로 비용이 많이 드는 작업을 수행하여 페이지의 응답성을 높일 수 있습니다.

Warning: will-change is intended to be used as a last resort, in order to try to deal with existing performance problems. It should not be used to anticipate performance problems.

## transition
Transitions enable you to define the transition between two states of an element. Different states may be defined using pseudo-classes like :hover or :active or dynamically set using JavaScript.

## focus-within
The :focus-within CSS pseudo-class matches an element if the element or any of its descendants are focused. In other words, it represents an element that is itself matched by the :focus pseudo-class or has a descendant that is matched by :focus. (This includes descendants in shadow trees.)

## @media
미디어 CSS at-규칙은 하나 이상의 미디어 쿼리 결과를 기반으로 스타일시트의 일부를 적용하는 데 사용할 수 있습니다. 이 규칙을 사용하면 미디어 쿼리가 콘텐츠가 사용 중인 디바이스와 일치하는 경우에만 문서에 적용할 미디어 쿼리와 CSS 블록을 지정할 수 있습니다.


