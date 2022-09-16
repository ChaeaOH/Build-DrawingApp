# 💻Build A Paint APP 
JavaScript기반의 그림판 앱으로 Canvas를 활용하여 다양한 색상으로 다양한 모양을 그리고,지우고,그린 그림을 이미지로 다운로드할 수 있습니다.


# 🔍Detail
- Canvas로 그림을 그리기 위해 canvas 요소 객체의 `getContext` 메서드를 사용하여 렌더링 컨텍스트라는 객체를 가져와 2d로 인수를 사용합니다. 
- `strokeRect` 메소드로 tool인 원형,사각형,삼각형 테두리를 그립니다.
- Path의 메소드인 `beginPath,moveTo,lineTo,closePath` 메소드를 호출하여 곡선을 그립니다.
- StrokeStyle,fillStyle 프로퍼티로 그래픽스 색상 설정을 설정합니다.
- `HTMLCanvasElement.toDataURL()`메서드를 사용하여 매개변수 에서 지정한 jpg형식의 이미지 표현을 포함하는 데이터 URL 를 반환하고, 브라우저에게 링크로 가는 대신 URL을 다운로드하도록 지시하여 그린 그림이 다운로드 됩니다. 

# 🚀Result
![function](/painapp.gif)


# 💡Review
- 즉시 실행형 저수준 api인 canvas를 실습하며 처음으로 코드를 통해 2차원 컴퓨터 그래픽스를 구현하는 방법을 배웠다.
- 웹 브라우저에서 그래픽을 처리하는게 꽤 흥미로워서 canvas요소의 여러 메서드를 활용해 적용해보고 그 다음 3차원 그래픽인 WebGL을 공부할 예정이다.
