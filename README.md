# Gemini Robotics-ER 1.5 API Test

Google Deepmind의 VLM모델인 Gemini Robotics-ER 1.5를 API를 통해 사용한 간단한 테스트 결과 및 코드를 공유합니다. 

아래와 같이 구글 드라이브 폴더에 테스트 코드, 이미지 및 비디오를 업로드 한 후 Google Colab을 통해 실행해 보실 수 있습니다.

```bash
my_project/                  # 프로젝트 최상위 폴더
│
├── gemini_er_img_test.ipynb     # 이미지 테스트용 노트북 (Point, Box, Segmentation 등)
├── gemini_er_video_test.ipynb   # 비디오 테스트용 노트북
│
└── assets/                      # 리소스 저장 폴더
    │
    ├── image.png                # 테스트 할 이미지 파일
    └── video.mp4                # 테스트 할 비디오 파일
```

## 이미지 테스트트

### 원본 이미지
![원본 이미지](src/original_img.png)

### Bounding Box
![Bounding Box](src/bb.png)

### Object Labeling
![객체 인식](src/objects.png)

### Segmentation
![세그멘테이션](src/segmentation.png)

### Trajectory Generation
![궤적](src/traj.png)

## 비디오 테스트

### 원본 비디오
<video controls>
  <source src="src/original_video.mp4" type="video/mp4">
  비디오를 지원하지 않는 브라우저입니다.
</video>


## 참고

* Model Info: [DeepMind Gemini Robotics-ER](https://deepmind.google/models/gemini-robotics/gemini-robotics-er/)
* API Documentation: [Gemini API Robotics Overview (KO)](https://ai.google.dev/gemini-api/docs/robotics-overview?hl=ko)
* Official Cookbook: [Gemini Robotics-ER Quickstart](https://github.com/google-gemini/cookbook/blob/main/quickstarts/gemini-robotics-er.ipynb)