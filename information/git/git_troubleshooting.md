
# The file will have its original line endings in your working directory warning: LF will be replaced by CRLF in
### 플랫폼(OS)마다 줄바꿈을 바라보는 문자열이 다르기에 Git이 바라볼 땐 어느 쪽을 선택할지 몰라 경고 메세지를 띄워준 것이다.
### 해결방안은 autocrlf를 사용하는 것이다.
> git config --global core.autocrlf true  
> 시스템 전체에 적용하고 싶다면 --global 옵션을 추가하고 전체가 아닌 해당 프로젝트에만 적용하고 싶다면 옵션을 빼주면 된다.

&nbsp;  
# This is larger than GitHub's recommended maximum file size of 50.00 MB
### Github에서는 하나의 파일이 100MB 제한이 있다.
### 50MB에서는 Warning을 표시하고, 100MB에서는 Error를 표시한다.