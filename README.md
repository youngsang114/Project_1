# Project_1
VAR, VARMAX, LSTM 모델을 이용한 "코스피 200 경기 소비재 지수" 예측
<br>

# **프로젝트 개요**
- kospi종가와 경기선지수순환변동치와 유미한 동행관계가 있다고 판단
- 경기선행지수순환변동치 및 여러 거시경제변수의 한달 시차의 시계열 데이터를 이용해 경기 민감지수인 코스피200경기 소비재 지수를 예측해보자

# **목적**
- 어떤 경기 지표가 코스피 200 경기 소비재 지수에 유의미한 영향을 미치는지 찾는다
- VAR,VARMAX 모델의 이해


## PPT
![image](https://github.com/youngsang114/Project_1/assets/127286621/8a1a6fa8-a32d-42fa-94c2-5e093a22cbe6)
![image](https://github.com/youngsang114/Project_1/assets/127286621/bb235f70-59be-4e87-abab-f91a736d7f09)
![image](https://github.com/youngsang114/Project_1/assets/127286621/4d65b8cd-c172-41a3-928c-104ac4a66e04)
![image](https://github.com/youngsang114/Project_1/assets/127286621/626931f5-b4e8-4211-b188-05f069edb76f)
![image](https://github.com/youngsang114/Project_1/assets/127286621/2e0d3e29-b54e-4237-af3e-cee041974215)
![image](https://github.com/youngsang114/Project_1/assets/127286621/27f3af46-aa04-493b-a68a-7f00e98ffeb9)
![image](https://github.com/youngsang114/Project_1/assets/127286621/fafaea7d-7dc4-46e6-a400-91e864b5140d)
![image](https://github.com/youngsang114/Project_1/assets/127286621/cada35ae-b1d1-400c-a0cc-2c17aadb656a)
![image](https://github.com/youngsang114/Project_1/assets/127286621/08817fe1-bcf0-4595-bd12-7b78caa7e851)
![image](https://github.com/youngsang114/Project_1/assets/127286621/ea4a4231-67ef-4470-98b6-fbf3e2de70ad)
![image](https://github.com/youngsang114/Project_1/assets/127286621/1152d2c3-b64c-44e2-88ab-3de2b181d212)
![image](https://github.com/youngsang114/Project_1/assets/127286621/0bcd0cde-becd-470b-987f-d071da0c5175)
![image](https://github.com/youngsang114/Project_1/assets/127286621/80b009a8-9837-4710-9006-709dd3a4e995)
![image](https://github.com/youngsang114/Project_1/assets/127286621/fa50591b-a1ca-4b9f-8d5c-c2c90b54f9ae)
![image](https://github.com/youngsang114/Project_1/assets/127286621/2a4b251b-03f3-453b-a74e-18ed0f81d986)
![image](https://github.com/youngsang114/Project_1/assets/127286621/d47e9ad9-6335-40a0-9bb1-2c6b47615bf0)
![image](https://github.com/youngsang114/Project_1/assets/127286621/3eb9b365-5c23-4577-beb9-17f890c0ab00)
![image](https://github.com/youngsang114/Project_1/assets/127286621/9841de97-6183-4a35-b586-b48e2c7c9e51)
![image](https://github.com/youngsang114/Project_1/assets/127286621/a47b7dcc-c641-4a9b-b115-4e30915bbadd)
![image](https://github.com/youngsang114/Project_1/assets/127286621/da770ba1-c980-416f-8d03-37ddcc343391)
![image](https://github.com/youngsang114/Project_1/assets/127286621/440b1510-8e1d-4e5f-9d55-bc544cc724f7)
![image](https://github.com/youngsang114/Project_1/assets/127286621/f436a16d-581d-4e9c-9de0-d5af914f1773)
![image](https://github.com/youngsang114/Project_1/assets/127286621/72ca331e-729a-4ce0-8d0a-a7ff9cffaf4f)
![image](https://github.com/youngsang114/Project_1/assets/127286621/6b3ff1ca-ceff-4a38-bcde-6a70ffd1408e)
![image](https://github.com/youngsang114/Project_1/assets/127286621/d3742c43-8b49-4da5-8cc6-bbcea1fff8f2)
![image](https://github.com/youngsang114/Project_1/assets/127286621/a16029dc-3a18-4482-94f5-19b1c6cddbfb)
![image](https://github.com/youngsang114/Project_1/assets/127286621/c962bf42-9fde-47ef-a07e-0de0cb8f3efb)
![image](https://github.com/youngsang114/Project_1/assets/127286621/da5495d1-33de-4eb5-b892-acc203b293ca)
![image](https://github.com/youngsang114/Project_1/assets/127286621/b131f6a2-08ee-42f5-874e-21db8533ab44)
![image](https://github.com/youngsang114/Project_1/assets/127286621/1133e090-d0d1-4369-8cd8-f20d58de693e)
![image](https://github.com/youngsang114/Project_1/assets/127286621/a9547c18-5932-4bc4-9119-c4bb50a25ad3)
![image](https://github.com/youngsang114/Project_1/assets/127286621/b82951da-abe2-4f1e-9980-cb374f70b486)
![image](https://github.com/youngsang114/Project_1/assets/127286621/791a547e-bdbc-4a9c-b701-714f389f4ece)
![image](https://github.com/youngsang114/Project_1/assets/127286621/aa1500b2-f070-4f72-9ff6-8e7535feb14a)
![image](https://github.com/youngsang114/Project_1/assets/127286621/a4863202-e048-403d-8d13-eb5697652531)
![image](https://github.com/youngsang114/Project_1/assets/127286621/1a716831-4309-49b5-b543-3f57c4613753)
![image](https://github.com/youngsang114/Project_1/assets/127286621/e6b9544d-2d28-4ef8-a337-3f78f387bae2)
![image](https://github.com/youngsang114/Project_1/assets/127286621/d28e043b-7314-490a-ab7c-8296352d10f9)
![image](https://github.com/youngsang114/Project_1/assets/127286621/01297623-bad7-42d6-9de3-cbe7371fcf70)
![image](https://github.com/youngsang114/Project_1/assets/127286621/f21aad0f-fa14-4a43-a734-bca34728731c)
![image](https://github.com/youngsang114/Project_1/assets/127286621/a9b3b6a6-4ad6-4829-a1e7-fb7ceeaeb13d)
![image](https://github.com/youngsang114/Project_1/assets/127286621/1f557a96-a78f-4120-a914-eca6a3714a0f)
![image](https://github.com/youngsang114/Project_1/assets/127286621/f7118fd1-4614-4d6e-8f6e-3a7bc0c2d1e8)
![image](https://github.com/youngsang114/Project_1/assets/127286621/163557f2-28b9-4315-8591-b28279a3d9ea)
![image](https://github.com/youngsang114/Project_1/assets/127286621/06b1ade6-8092-4e43-a5c7-bf0f9613ccfe)
![image](https://github.com/youngsang114/Project_1/assets/127286621/288b2d42-b84e-4e75-8dff-ac942dc3a124)
![image](https://github.com/youngsang114/Project_1/assets/127286621/079f8526-83a9-405e-8e30-a86366762700)
![image](https://github.com/youngsang114/Project_1/assets/127286621/f7e09b8c-db38-4ca1-8a3d-11c5a86a1820)
![image](https://github.com/youngsang114/Project_1/assets/127286621/e4102937-7476-4657-861a-9f45ffeaac48)
![image](https://github.com/youngsang114/Project_1/assets/127286621/0a63007a-257e-4a1f-b4a1-e5fe1d1109c4)
![image](https://github.com/youngsang114/Project_1/assets/127286621/d8a756bd-eba9-463d-b906-d028e2bca67c)
![image](https://github.com/youngsang114/Project_1/assets/127286621/47c2a9cb-2737-47b6-b7bf-ea24b8d0001a)
![image](https://github.com/youngsang114/Project_1/assets/127286621/27a19f4f-8b39-4dda-91b9-6077053c47fd)
![image](https://github.com/youngsang114/Project_1/assets/127286621/5ba88280-835a-479b-be54-1f8ff41077e1)
![image](https://github.com/youngsang114/Project_1/assets/127286621/972cc19a-b064-45a1-8811-a57684854a6f)
![image](https://github.com/youngsang114/Project_1/assets/127286621/4df0e160-5b5f-4a4e-998c-278afbc64fae)


































































































