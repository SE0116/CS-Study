- append와 extend
  - append : 추가하고자 하는 매개변수를 통으로 넣음
  - extend : 추가하고자 하는 매개변수를 풀어서 각각의 엘리먼트로 처리
  - ex) append([2, 3]) : [1, [2, 3]] / extend([2, 3]) : [1, 2, 3]

- Dictionary, List, Set, tupple
  - Dictionary : `key`와 `value`를 한 쌍으로 저장, key값 중복 x, O(1)
  - Set : 별도의 인덱스가 없음, 동일한 값이 두 개 이상 들어갈 수없음, O(1)
  - List : 해당하는 값의 변동 가능, O(n)
  - tupple : 해당하는 값의 변동 불가능