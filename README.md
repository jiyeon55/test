Last login: Tue May 21 16:38:07 on ttys005

~
❯ cd pilot-web-test

~/pilot-web-test QAWEBTEST-29
❯ ls
README.md       ceo-desktop-web commons         gradlew         settings.gradle
build.gradle    ceo-mobile-web  gradle          gradlew.bat

~/pilot-web-test QAWEBTEST-29
❯ pwd
/Users/woowahan/pilot-web-test

~/pilot-web-test QAWEBTEST-29
❯ vi README.md








 1 README.md                                                         Buffers 
1   /**                                                                         
  1  * @author  jiyeon55@woowahan.com
  2  * @since   2019.05.21_복습
  3  */
  4 
  5 # 웹 테스트 코드 저장소
  6 품질개선팀에서 파일럿 프로젝트로 사장님사이트 웹 테스트를 작성하고 관리하는↷
  7 
  8 ## 테스트 실행
  9 
 10 ``` shell
 11 # mobile web 
 12 $ ./gradlew clean test -pceo-mobile-web
 13 
 14 # desktop web
 15 $ ./gradlew clean test -pceo-desktop-web
 16 ```
 17 
 18 ## 추가적인 테스트 실행 옵션
 19 명시적으로 빌드 실행 옵션을 추가할 수 있습니다.
 20 
 ❶  - 3.2k README.md  markdown  ❖ ⓢ                         | utf-8  Top 

