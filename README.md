🕰️ Retro Weather Clock 
> OpenWeather API를 활용한 빈티지 아날로그 감성 날씨 웹사이트

실제 빈티지 날씨 시계의 디자인에서 영감을 받아 제작한 날씨 검색 웹사이트입니다. 
단순한 텍스트 나열이 아닌, 레트로한 UI와 LED 점등 애니메이션을 통해 현재 날씨를 시각적으로 보여줍니다.

## 🔗 Live Demo
[내 웹사이트 구경하기](https://zioo04.github.io)
*(위 주소를 클릭하면 실제 작동하는 페이지로 연결됩니다)*

## 🛠️ 주요 기능
- **실시간 날씨 데이터:** OpenWeatherMap API를 사용하여 전 세계 도시의 날씨 정보를 가져옵니다.
- **감성 UI:** 빈티지 시계 디자인을 HTML/CSS로 재현했습니다.
- **상태 표시 LED:** 날씨 상태(맑음, 구름, 흐림, 비)에 따라 해당하는 칸의 LED에 불이 들어오는 시각적 효과를 구현했습니다.

## 💻 사용 기술
- **Frontend:** HTML5, CSS3 (Flexbox, CSS Variables), JavaScript (ES6+)
- **API:** [OpenWeatherMap API](https://openweathermap.org/)
- **Deployment:** GitHub Pages

## 💡 개발 포인트
- `Fetch API`를 사용해 비동기로 날씨 데이터를 처리하는 법을 익혔습니다.
- 데이터의 `Weather Condition` 값에 따라 조건문(`if-else`)을 활용해 특정 DOM 요소의 클래스를 제어하고, LED 애니메이션을 활성화했습니다.
- 외부 이미지 소스 없이 CSS만을 사용하여 아날로그 장비 특유의 질감과 그림자 효과(box-shadow)를 구현했습니다.

