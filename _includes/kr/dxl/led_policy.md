{% capture dxl_led_policy %}  
**참고** : 장치의 상태(조건)에 따른 LED의 동작입니다.

| 상태                  | LED 동작      |
|:---------------------:|:-------------:|
| 부팅                  | 1회 점멸      |
| 공장 초기화           | 4회 점멸      |
| 알람                  | 점멸          |
| 슬레이브 모드(MX-106) | 3회 점멸      |
| 부트 모드             | 점등          |

{% endcapture %}
<div class="notice">{{ dxl_led_policy | markdownify }}</div>
