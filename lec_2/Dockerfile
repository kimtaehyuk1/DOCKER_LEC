# 베이스이미지
FROM ubuntu

# 파일 추가, 압축해제, URL 다운로드 후 추가

# 압축해체후 추가
ADD web.tar /home/  

# URL 다운로드 후 추가
ADD https://raw.githubusercontent.com/ultralytics/yolov5/master/requirements.txt /home/requirements.txt

# 파일 추가, 이름을 바꿔서 넣어보기
ADD readme.md /home/readme2.md

# 특정 이름으로 시작하는 모든 파일(패턴지정)
ADD po*.txt /home/

# 특정이름 + 한글자로 시작하는 모든 파일 추가
ADD to?.txt /home/