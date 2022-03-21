# deviceQuery

결과출력용
- Original_deviceQuery : 코드수정안한 오리지널 파일 
- Outputcsv_deviceQuery : 결과 csv파일로 출력하게 수정해준 deviceQuery.cpp


<수정후 확인과정>

1. deviceQuery.cpp 수정하기
2. make sudo ( 에러나면 sudo make clean )
3. ./deviceQuery

<추가해준 부분 간단히>

```
 #include <fstream> 
std::ofstream myfile;
myfile.open ("devicequery.csv");
myfile << "Maximum Texture Dimension Size (x,y,z)," << deviceProp.maxTexture1D;
myfile.close();
```

  
<CSV 파일 생성하고 권한설정>
  
printf("hohohohohoho");
printf("%d",deviceProp.multiProcessorCount);
 
  
  
  
