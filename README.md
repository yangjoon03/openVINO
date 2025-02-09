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







[openVINO]: https://www.intel.com/content/www/us/en/developer/tools/openvino-toolkit/download.html?PACKAGE=OPENVINO_BASE&VERSION=v_2025_0_0&OP_SYSTEM=WINDOWS&DISTRIBUTION=ARCHIVE****
