# web_get_api

## 프로젝트 개요
api data를 받아와서 웹으로 출력해보기

### 사용된 기술 스택

- **Python:** 3.8
- **Django:** 3.1.5
- **django-bootstrap4:** 2.3.1
- **geopy:** 2.1.0
- **pandas**
- **requests**

## 사용 api
- **openweathermap**: 날씨 데이터 api

## 테스트 방법
```python
# 프로젝트 클론
git clone https://github.com/dnlpys/web_get_api.git

# 필요한 패키지 설치
pip install -r requirements.txt

# 서버 실행
python manage.py runserver

# 브라우저에서 다음 주소로 접속
http://127.0.0.1:8000/weathers/
