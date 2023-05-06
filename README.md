# 실시간 감정 인식

컨볼루션 신경망을 사용한 실시간 얼굴 감정 및 성별 인식 프로젝트 입니다.

감정을 판별하는 CNN모델과 성별을 판별하는 CNN모델을 각각 학습시킨뒤, openCV를 사용하여 실시간  

## Tools

- NumPy
- Tensorflow
- OpenCV

## Dataset

   - !kaggle competitions download -c challenges-in-representation-learning-facial-expression-recognition-challenge
   - kaggle Dender Classification dataset download

## Test
![IMG_0922](https://user-images.githubusercontent.com/80025812/236636134-702ecb95-006b-404e-b0b2-1bb1f6c204c3.jpg)         ![IMG_0923](https://user-images.githubusercontent.com/80025812/236636140-a29c4ddb-d76a-4331-a0d9-0d9baa2a03b8.jpg)         ![IMG_0925](https://user-images.githubusercontent.com/80025812/236636146-5ed61024-b38b-42fb-8972-dc9f13efa05a.jpg)         ![IMG_0928](https://user-images.githubusercontent.com/80025812/236636154-3b635ec3-a208-4da2-8ddd-f432aad4af1e.jpg)         ![IMG_0931](https://user-images.githubusercontent.com/80025812/236636160-75478b6c-2a8d-4353-8610-7b3e63e8ec57.jpg)         ![IMG_0932](https://user-images.githubusercontent.com/80025812/236636169-a0c5a9a7-c816-4b59-8b8d-4ab308475a68.jpg)         ![IMG_0934](https://user-images.githubusercontent.com/80025812/236636170-797c2645-dd66-45ca-9bd6-5165b00436ac.jpg)
---------------------------------------
![Female-Neutral](https://user-images.githubusercontent.com/80025812/236636466-8b0b9704-7773-4100-9a2d-2c2dbbb287b7.png)
![Female-Happy](https://user-images.githubusercontent.com/80025812/236636457-cd43edf4-085f-41b1-b559-5899b5fbb919.png)
![Male-Surpring](https://user-images.githubusercontent.com/80025812/236636484-07f11bba-a0ef-4c4b-a1a8-216d4f82ce5c.png)
![Male-Disgusting](https://user-images.githubusercontent.com/80025812/236636488-4a83e8a8-0e5d-478f-8a2f-8e941f773874.png)
![Female-Sad](https://user-images.githubusercontent.com/80025812/236636497-23eef9d2-1366-4db2-93e0-7571c491ce06.png)
![Femal-Fearful](https://user-images.githubusercontent.com/80025812/236636500-25ef1f5e-9e7d-41df-a4e8-aa50e02133c6.png)
![Female-Angry](https://user-images.githubusercontent.com/80025812/236636503-db3f16c2-4671-4699-b0e2-6bad1b8b7d95.png)
