# redux

리덕스 스토어에 API로 값을 넣어주는 경우, 항목이 빠져있으면 최신화가 제대로 이루어 지지않는다. 값이 바뀌는 경우 추적을 해주는 것이라서 리턴되는 결과값에 값이 없어 항목 자체를 받지 못하면, 그 전에 리덕스 스토어가 저장하고 있던 값을 계속 가지고 있는다.  
그래서 계속 추적할 값이라면 값이 있든 없든 무조건 리턴 항목에 추가를 해줘야한다는 것이 너무 중요하다!! 꼭 잊으면 안 된다.