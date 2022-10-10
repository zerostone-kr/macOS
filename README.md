# macOS
맥 os 사용에 익숙치 않아서 작성하는 페이지


# 경로 추가하기

## profile open
open .bash_profile

## 경로 추가
export PATH=${PATH}:(추가할 경로)
예) export PATH=${PATH}:/Users/zerostone/development/flutter/bin

## profile 적용 및 확인
source .bash_profile
echo $PATH
