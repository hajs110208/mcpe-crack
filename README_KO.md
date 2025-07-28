# mcpe-crack
마인크래프트 안드로이드 버전용 크랙 코드

# 주의할 점
마크 구매 하신 분들만 쓰세요. 단순한 복돌 유저들을 위한 가이드가 아닙니다.

# 그건 알겠고, 어떻게 하나요?
MT Manager이나 Apktool M과 같은 도구들을 사용하세요

1. MT Manager 열어서 apk파일 선택하고 "VIEW" 버튼을 누르세요.

2. classes.dex 누르고 "Dex Editor plus"로 파일을 여세요.

3. com/mojang/minecraftpe/store/googleplay 에서 GooglePlayStore를 선택하세요.

4. "hasverifiedlicense"라는 글씨가 있는 부분을 찾으세요.

5. sget-boolean으로 시작하는 줄을 const/4 v0, 0x1로 바꾸세요.

6. 파일을 저장하고 "AUTO SIGN"을 켜고 파일을 업데이트하세요.

7. 설치할때 악성 앱 의심 경고로 깔리지 않을때는 Apktool M으로 직접 서명키를 만들어서 서명해야 합니다.

8. Settings > Sign > Create a Key File 눌러서 직접 키 만들 수 있습니다. 만들고 나서 아까 수정한 파일 누르고 Sign 누르고 키를 사용자 지정 서명 파일로 바꾸고 버튼 누르면 서명됩니다.

10. 이름 뒤에 _sign으로 되어있는거 눌러서 세션으로 설치 눌러서 설치하시면 됩니다.

# ㅊㅋ!
실행이 성공적으로 되면 성공한 겁니다. 코드 수정이 너무 어려우면 smali 파일을 그냥 복사해서 붙여넣으세요. 그럴 일은 없겠지만.

