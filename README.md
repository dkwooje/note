SPRING BOOT를 사용하면서 모르거나 기록할 만한 문제를 기록하였습니다.
한글 2020을 사용하였습니다./


PS C:\vvv\REACT\1\01.DUKUABI> npm install npm : 이 시스템에서 스크립트를 실행할 수 없으므로 C:\Program Files\nodejs\npm.ps1 파일을 로드할 수 없습니다. 자세한 내용은 about_Execution_Policies(https://go.microsoft.com/fwlink/?LinkID=135170)를 참조하십시오. + npm install + ~~~ + CategoryInfo : 보안 오류: (:) [], PSSecurityException + FullyQualifiedErrorId : UnauthorizedAccess

해결법: 

터미널에 다음과 같은 문자를 입력한다.
Get-ExecutionPolicy
Set-ExecutionPolicy RemoteSigned
