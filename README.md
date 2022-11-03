# Business Analytics
# **[Ch.2] Kernel-based Learning**
>👨‍🏫 본 tutorial은 고려대학교 산업경영공학과 강필성 교수님의 [Business Analytics](https://github.com/pilsung-kang/Business-Analytics-IME654-) 수업을 기반으로 작성되었습니다.


## 📂 Contents
-----------------------------
* Background
* Support Vector Machine
* Dataset
* Result
* Analysis

-----------------------------
### :pushpin: Background

* Kernel
> 비선형 데이터를 잘 다루기 위해 kernel을 이용하고자 하고 있습니다. 
> kernel의 종류는 다음과 같이 linear, polynomial, Radial Basis Function (RBF) 등이 있습니다.

|Linear Kernel|Polynomial Kernel|Radial Basis Function Kernel|

* Support Vector Machine
  * Support Vector
  * Margin
   - Hard
   - Soft

## :books: Support Vector Machine
-----------------------------
#### 💬 Questions
- [x] Soft Margin 이용시 penalty term C가 과연 정말 효과적일까?
- 
#### [Tutorial]

### 📂 Dataset
----------------------------
* Star Dataset for Stellar Classification [download](https://www.kaggle.com/datasets/vinesmsuic/star-categorization-giants-and-dwarfs)

### :bar_chart: Result
-----------------------------
- accuracy : 0.8911
- Standard Scaler : 0.8911
- MinMaxScaler : 0.8930
- Robust Scaler : 0.8928

### 📊 Analysis
------------------------------
scaling을 진행하지 않은 경우에는 0.8911, standardscaler를 이용한 경우 0.8911, MinMaxScaler를 이용한 경우 0.8930, Robust scaler를 이용한 경우 0.8920으로 약강의 성능 향상이 있긴 했으나 생각보다 크게 차이가 많이 나지 않는 모습을 보였습니다. 데이터 자체의 분포에서 taget이 많이 balancing 되어있었기 때문에 이러한 결과가 나타난 것으로 생각됩니다.



### 📂 References
------------------------------
* https://github.com/pilsung-kang/Business-Analytics-IME654-
