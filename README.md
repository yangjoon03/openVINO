## 1.openVINO 설치
  * [openVINO] Archives 다운로드
  * 압축 해제후 C/Progra Files *86/Intel
  * ✔Intel파일은 수동 생성


## 2.환경변수 설정(수동,가상 환경)
  * 가상환경 생성 후
  * cd "C:~~~~ /openViNO/setupvars.bat" 실행
```bush
python (version)
[setupvars.bat] openVINO enviroment initialized
```
  * 정상 작동


## 3.openVINO 모델 확장자 변환
  * 코드 참조
  * 2. 가상환경에 작성 : mo --input_model yolov8n.onnx --output_dir yolov8_openvino
  * 해당 코드는 chatgpt 질문시 해줌.
  * pt > onnx > xml,bin
  * ✨에러 발생시 처음부터 다시 시작.


## 환경변수 설정(수동,가상 환경)
  * 가상환경 생성 후
  * cd "C:~~~~ /openViNO/setupvars.bat" 실행


## serial 통신
 * 무선 ESP32, ESS8266 모듈 필요(라즈베리,라떼판다는 해당 모듈 X)
 * 유선 USB등 선이 필요함.
 * serial통신은 비트단위로 데이터를 전송하는 방식이다.


## wifi 통신
 * TCP를 통해서 소켓 코딩이 가능함.

## openVINO face-detection-adas-0001 모델 사용
 * openVINO 전용 모델로 확장자 변환 필요없음
 * 추론 과정 슬라이딩 윈도우 방식으로 추론을 진행하게됨
 * [sliding_window] 2가지 방식(여러형태 윈도우,이미지 스케일 줄이기)



[openVINO]: https://www.intel.com/content/www/us/en/developer/tools/openvino-toolkit/download.html?PACKAGE=OPENVINO_BASE&VERSION=v_2025_0_0&OP_SYSTEM=WINDOWS&DISTRIBUTION=ARCHIVE****
[sliding_window]: https://developer-lionhong.tistory.com/35
