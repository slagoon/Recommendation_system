# **프로젝트 이름**

<p align="center">
  <br>
  
  ### 외국인 여행객을 위한 국내 관광지 추천 시스템
  
  <br>
</p>




# 프로젝트 소개

<p align="justify">
  
 코로나가 끝나 엔데믹으로 가고 있는 추세에서 여행이 주는 의미는 크게 작용한다. 많은 사람들이 그동안 가지 못한 여행을 꿈꾸며 한국에 대한 관심도 커져 가고 있다. 국내 여행지로는 다양한 여행지가 있지만 외국인 관광객이 왔을 떄 좀 더 효과적인 여행지 추천을 위해 이번 프로젝트를 진행하게 되었다. 

 외국인 관광객이라는 점에 초점을 두어 대중적이고 한국적인 특징을 느낄 수 있는 장소로 프로젝트를 진행하였으며 여러 카테고리 중 원하는 카테고리에 관련된 여행지가 추천되도록 프로젝트를 진행하였다.
</p>

<p align="center">
  
</p>

<br>

# 기술 스택
<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"><img src = "https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black"><img src = "https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white"><img src = "https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white">



<br>

# 프로젝트 과정 

1. 전국의 수많은 여행지 중 대상 여행지를 나무위키의 '죽기 전에 꼭 가봐야 할 국내 여행지 1001'로 한정한 후 리스트 크롤링 진행

2. 트립 어드바이저 사이트에서 각 여행지 들에 대한 리뷰, 평점, 주소, 카테고리 등을 수집

3. 각 여행지별 리뷰에 대한 감정분석을 통해 실제 평점과의 차이를 분석하여 좀 더 솔직한 평점 시스템 구축

4. TF-IDF를 통해 각 카테고리 별의 특정 키워드가 무엇인지 추출

5. 이후 주소, 평점, 카테고리, 키워드를 코사인 유사도를 통해 추천시스템을 구축
   
<br>

## 아쉬운 점

<p align="justify">

### 아쉬운 점

  추천 시스템을 웹이나 앱 형태의 서비스로 구현하면 어땠을까 라는 회고를 남기고 싶다. 좋은 프로젝트 였지만 좋은 결과를 보여주는 데에 한계가 있다는 점에서 아쉬움이 남는다. 좀 더 보충해 서비스로 구현을 한다면 좋을 것 같다. 
  현재는 여행지를 입력하면 관련된 여행지를 추천해 주지만 필터를 추가하여 카테고리 선택 및 주소 선택 등을 통해 좀 더 세분화된 추천 시스템을 구현하면 어떨까 라는 한계점이 있다.
</p>

<br>

