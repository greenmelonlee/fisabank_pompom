# fisabank_pompom

<img width="450" alt="image" src="https://github.com/user-attachments/assets/abd99edb-5113-4507-8f90-689a8cb5df73"> </br>
- 우리fisa 3기 AI 엔지니어링 </br>
- 프로젝트 날짜: 2024.09.19

</div>

---

# ML MINI PROJECT - BANK DATASET 🗃️
Bank Dataset을 활용하여 최적의 Deposit 결과를 내는 분류기를 만든다.

</br>

## 주요 단계 📈

1. 알고리즘(모델 차원)
    1. AutoML (Pycaret) </br>
        <img width="700" alt="image" src="https://github.com/user-attachments/assets/f8faeb0f-9168-4195-939d-9ea1819120fb"></br>
        <img width="700" alt="image" src="https://github.com/user-attachments/assets/df4b3047-df57-4268-966a-c902d9014593"></br>
        <img width="700" alt="image" src="https://github.com/user-attachments/assets/fb129d4a-aedf-4023-95c8-62d5e9557dc1"></br>
        -> Gradient Boosting Classifier 를 baseline 모델로 선택
        </br></br>
    2. Hyperparameter Tuning (by grid search)</br>
        <img width="700" alt="image" src="https://github.com/user-attachments/assets/fd17140f-305d-4d9f-a916-82aef08f83e0"></br>


---

## 트러블 슈팅 💥
1. Hyperparameter Tuning - 최적화된 모델이 오히려 성능이 낮다. </br></br>

    |before|after|
    |:---:|:---:|
    |<img width="500" alt="image" src="https://github.com/user-attachments/assets/c5b9dbd9-e96a-4a51-9ba8-cc3f02557610">|<img width="500" alt="image" src="https://github.com/user-attachments/assets/f57948c0-198c-47ed-8f19-debd648972f8">|
    |<img width="500" alt="image" src="https://github.com/user-attachments/assets/728c8d3a-706f-47e4-b92c-cfe7abca309e">|<img width="500" alt="image" src="https://github.com/user-attachments/assets/a5f01a39-ea44-4568-9ec8-a7018294aec0">|
    |<img width="500" alt="image" src="https://github.com/user-attachments/assets/fd846258-f8f8-427e-b596-e8af610c3d1a">|<img width="500" alt="image" src="https://github.com/user-attachments/assets/b780014c-a093-4456-9192-14bca21ef43b">|
    
2. Ensemble Model 활용시 성능이 더 떨어지는 문제가 있었다. </br></br>
   <img width="500" alt="image" src="https://github.com/user-attachments/assets/9d90c193-a8a0-4fcf-915a-9adb2d76f3bf"></br>
   |Top 3 Model|Ensemble Model 적합|
   |:--:|:--:|
   |<img width="500" alt="image" src="https://github.com/user-attachments/assets/f8585db6-b9fb-415a-926e-9944350157ba">|<img width="500" alt="image" src="https://github.com/user-attachments/assets/037d7034-b778-4f03-83af-5f06219ac419">|

---

## 꿀팁 🍯
<img width="500" alt="image" src="https://github.com/user-attachments/assets/aefd7140-c54f-4af1-b111-2968d3e21671"></br>

## Stacks 📚
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)</br>
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)</br>

## 데이터셋 출처 
- [Bank Marketing Data Set(https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)

---

## Team 🧑‍🧑‍🧒‍🧒

|<img src="https://avatars.githubusercontent.com/u/174994389?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/97214987?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/79956717?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/133483250?v=4" width="150" height="150"/>|
|:-:|:-:|:-:|:-:|
|Jinwon<br/>[@yonggaljjw](https://github.com/yonggaljjw)|Juran<br/>[@juuurr](https://github.com/juuurr)|Gunwoo<br/>[@rhrjsdn3853](https://github.com/rhrjsdn3853)|Yehee<br/>[@greenmelonlee](https://github.com/greenmelonlee)|
