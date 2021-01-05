# 마크다운( markdown ) 사용법(문법)  
마크다운을 좀 더 잘 활용해보고 싶은데, 매번 검색하기 귀찮아서 내가 자주 쓸만한 것을 정리해놓은 것이다.  

## 0. 마크다운에 대해서  
* 마크다운의 장점  

      1. 문법이 쉽다.  
      2. 관리가 쉽다.  
      3. 지원 가능한 플랫폼과 프로그램이 다양하다.  
      
* 마크다운의 단점  

      1. 표준이 없어 사용자마자 문법이 상이할 수 있다.  
      2. 모든 HTML 마크업을 대신하지 못한다.  

## 1. 줄 바꿈  
줄 바꿈은 띄어쓰기 3칸 이상으로 나타낼 수 있다.

    * 줄 바꿈을 하기 위해서는 문장 마지막에서 3칸 이상을 띄어쓰기 해야 한다.
    이렇게 ( 띄어쓰기 안 한 문장 )  
    * 줄 바꿈을 하기 위해서는 문장 마지막에서 3칸 이상을 띄어쓰기 해야 한다.    
    이렇게 ( 띄어쓰기 한 문장 )   

적용 예 : 
*** 
* 줄 바꿈을 하기 위해서는 문장 마지막에서 3칸 이상을 띄어쓰기 해야 한다.
  이렇게 ( 띄어쓰기 안 한 문장 )  
* 줄 바꿈을 하기 위해서는 문장 마지막에서 3칸 이상을 띄어쓰기 해야 한다.  
  이렇게 ( 띄어쓰기 한 문장 ) 
***

## 2. 헤더Headers  
h1부터 h6까지 **'#'** 을 붙여 사용 가능하다.  

    # This is a h1.
    ## This is a h2.  
    ### This is a h3.  
    #### This is a h4.  
    ##### This is a h5.  
    ###### This is a h6.  

적용 예 :   
*** 
# This is a h1.
## This is a h2.  
### This is a h3.  
#### This is a h4.  
##### This is a h5.  
###### This is a h6.  
*** 
 
## 3. 목록  
__* 순서 있는 목록 ( 순서 부여 )__     
엑셀에서 사용하는 것처럼 숫자+' . '를 사용하면 자동으로 순서가 생긴다.  

    1. 첫번째  
    2. 두번째  
    3. 세번째  

1. 첫번째  
2. 두번째  
3. 세번째  

__* 순서 없는 목록__  
순서 없는 모록에 사용 가능한 기호는 * , + , - 이다. ( 혼합하여 사용 가능 )  

    * 빨강
       * 녹색  
          * 파랑  
      
* 빨강  
   * 녹색  
      * 파랑  
     
## 4. 코드  
__4_1. 블록 만들기__  
하나의 탭 또는 4개의 공백들로 블록 안에 글씨를 쓸 수 있다. 앞뒤로 한줄씩 띄어쓰기를 해야 한다.  

    This is a normal paragraph:  
    
         This is a code block.  
         
    end code block.  
  
적용 예 :  
***  
This is a normal paragraph:  

    This is a code block.  
    
end code block.  
*** 

이때 앞뒤로 한 줄 띄어쓰기를 하지 않으면 제대로 블록이 만들어지지 않는다.

    This is a normal paragraph:  
        This is a code block.  ( 앞에 4칸 들여쓰기만 되어있고, 앞뒤로 한 줄씩은 안 띄었다. )
    end code block.  
적용 예 :  
***
This is a normal pragraph:  
    This is a code block.  
end code block.  
***

__4_2. 코드 블록__  
// 나중에 다시 작성 //  

## 5. 강조  

    *single asterisks*  
    _single underscores_  
    **double asterisks**  
    __double underscores__  
    ~~cancelline~~  
    
적용 예 :  
***  
*single asterisks - 눕히기*  
_single underscores - 눕히기_  
**double asterisks - 두껍게**  
__double underscores - 두껍게__  
~~cancelline - 취소선~~  
***  

## 6. 수평선  

    * * *   
    
    ***  
    
    *****  
    
    - - -   
    
    --------------------------------------------  
    
적용 예 :  
* * *   
***  
*****  
- - -   
---------------------------------  


참고 : <https://gist.github.com/ihoneymon/652be052a0727ad59601>
