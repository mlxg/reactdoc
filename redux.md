# Redux

##### `reducer(state, action) → store.dispatch(action) → final state`

store管理状态的盒子 →`getState() dispatch(action)分发`

> const store = redux.createStore\(reducer, \[\]\)

→ reducer用来修改state的方法,返回state

→ action改变的状态,`{type: 'xxx'，text: ‘xxx’}`

 

