<p align="center"><img width="386" alt="image" src="https://user-images.githubusercontent.com/90603530/202847951-58d5c192-8575-4670-8e81-8a0e5a16c03b.png"></p>

> ## 3D 모델링 진행 방식 
'독도'를 예시로 나타내었음

### 1) BlenderGIS로 독도 평면 가져오기
(.blender로 저장되었음)
![](https://velog.velcdn.com/images/dudskrla/post/2b5c8364-3c20-4050-bb2c-6868af609a05/image.png)
- 옆에서 본 모습 (평면 형태)

![](https://velog.velcdn.com/images/dudskrla/post/d5d7c1d1-566f-404e-8d2a-4b1e7254ab5a/image.png)
- 위에서 본 모습 (넓은 지역 표현)

### 2) MapsModelsImporter로 독도 3D 지형 가져오기
(.obj로 추출했음)
![](https://velog.velcdn.com/images/dudskrla/post/56532d2a-afe4-4618-be2a-b4225c4177db/image.png)


### 3) 평면과 3D 지형 합치기
(.blender 위에 .obj 파일을 얹는 형태)
![](https://velog.velcdn.com/images/dudskrla/post/492b9544-f91e-4db6-8781-00cca4ad47be/image.png)
- 옆에서 본 모습 (3D 지형 표현)

![](https://velog.velcdn.com/images/dudskrla/post/846a6852-130b-4ca8-8165-2d4a1983d4e0/image.png)
- 위에서 본 모습 (넓은 지역 표현)              
 



> ## More
더 자세한 내용은 기술 블로그에 작성해두었음 ➡️
[BlenderGIS와 MapsModelsImporter로 도시 모델링](https://velog.io/@dudskrla/BlenderGIS%EC%99%80MapsModelsImporter%EB%A1%9C%EB%8F%84%EC%8B%9C%EB%AA%A8%EB%8D%B8%EB%A7%81)
