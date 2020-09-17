

# Utils

## Test page  
지금과 같은 test page의 경우 파일제목 형식에 맞지 않게 파일명을 작성하면 github에 올라가더라도 blog에는 보이지 않게 됨  
(파일명 형식 : 2020-09-01-title.md)  
technical writing을 쉽게 하기 위한 Utils  

fastBook 폴더 전체를 google drive에 복사  
하나의 ipynb 마다 공부(update)한 후 실행 결과가 포함된 ipynb 파일을 github의 notebook 폴더에 업로드  

그래프, 실행 결과 등은 모드 포함되지만 image의 경우 colab cell에 바로 embedding되어 보여지지 않는 문제현상 발견  

## image를 Colab에 포함 시키기  
우선 gdrive의 그림 파일의 sharable link(for anyone)을 추출  
그러면 https://drive.google.com/file/d/1vz-y-TLHjvNmQT68KIdh7x2FMMhRCj1S/view?usp=sharing와 같은 링크를 얻을 수 있음.  
하지만 이 링크를 바로 markdown에 삽입하면 보이지 않는다. 위 링크에서 image id만 잘라서 https://drive.google.com/uc?id=XXX의 XXX 부분에 포함

최종적으로 다음과 같은 형태가 되면 colab cell에서 바로 보임  
![ee](https://drive.google.com/uc?id=1mKl2qiTlt-uBHkKf5D1_zJvY6l_UHzf8)