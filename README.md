# 파일 설명

이미지 유사도를 측정하고 측정된 값이 기준값보다 작을 경우 이미지의 틀린 부분을 추출하는 파일

cv2, PythonImageLibrary, numpy, matplotlib를 설치함

1비교할 이미지 두 개를 받아와서 히스토그램으로 바꾼다
2바꾼 정보를 BHATTACHARYYA 방식으로 저장한 후 비교한다
3\-1비교한 값이 기준 값보다 작은 경우에 비교 이미지들을 다른 변수에 다시 저장한다
3\-2두 개의 이미지를 함수를 사용해서 비교하고 정보를 새로운 변수에 저장한다
3\-3새로운 변수를 출력한다

참고 링크\: https://nadocoding.tistory.com/97
