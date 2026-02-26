## 전개연산자와 배열의 filter
+ filter()는 배열의 각 요소 검사
+ filter()는 삭제, 조회, 수정 등 상황에서 사용하기 

```
function deleteTodo(id) {
  const resultArr = arr.filter(todo => todo.id !== id)
  setArr(resultArr)
}
```
