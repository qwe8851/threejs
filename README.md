 
https://www.youtube.com/watch?v=CojyGfCMvuU&ab_channel=%EC%BD%94%EB%94%A9%EC%95%A0%ED%94%8C

 ## 3D model 브라우저에 보여주는 법
 1. 장면을 만들고
 2. 브라우저에 렌더링 하기


 ### 카메라 종류
 `let camera = new THREE.PerspectiveCamera(30, 1);`
 이런식으로 해주면 카메라를 소환할 수 있는데 
 카메라는 두가지 종류가 있음
 
 1. PerspectiveCamera : 원근법 적용 o
 2. OrthographicCamera : 원근법 적용 x


 ### 조명 종류
 1. AmbientLight
 2. PointLight
 3. DirectonalLight


 ## 마우스 컨트롤
 - Three.js 내의 OrbitControl 쓰면 됨

