---
title: Voice Shift Player 개인정보처리방침 / Privacy Policy
permalink: /voiceshift/privacy/
---

# Voice Shift Player 개인정보처리방침 / Privacy Policy

시행일 / Effective date: 2026-09-28

[한국어](#한국어) · [English](#english)

## 한국어

Voice Shift Player(Google Play 이름: "Voice Shift: 키 변경·보컬 제거", 이하 "앱")는 개인 개발자 jhS(이하 "개발자")가 만든 뮤직 플레이어입니다.
앱에는 계정이 없고 개발자가 운영하는 서버도 없습니다. 개발자는 이용자가 보낸 문의 메일 외에는 이용자의 개인정보를 받지 않습니다.
다만 앱에 들어 있는 광고·결제 기능은 Google이 제공하며, Google이 아래와 같이 일부 정보를 처리합니다.

### 1. 기기 안에서 처리하는 정보
- **음악·동영상 파일**: 기기의 오디오 파일과 그 정보(제목, 아티스트, 앨범, 폴더, 재생 시간)를 읽어 목록을 보여 주고 재생합니다.
  동영상은 이용자가 "동영상 파일 추가"로 직접 고른 파일만 읽으며, 라이브러리에서 제거할 때까지 그 파일의 읽기 권한을 유지합니다.
- **AI 기능**: 보컬 분리(ONNX Runtime)와 AI 가사 만들기·AI 싱크(Whisper)는 진행 알림을 띄우고 백그라운드에서 계속될 때도 모두 기기 안에서 실행됩니다. 음원과 그 내용은 어디에도 업로드되지 않습니다.
- **가사 폴더**: 설정에서 가사 폴더를 고르면 그 폴더의 .lrc/.txt 파일을 읽을 수 있는 권한을 유지하며, 폴더를 바꾸거나 지우면 권한을 돌려줍니다.
- **앱이 만든 데이터**: 설정, 재생목록, 숨긴 폴더, 분리한 음원, 만든 가사, AI 기능 무료 체험 남은 횟수, 구매 상태(광고 제거·Pro)와 6항에 적은 그 밖의 항목은 기기의 앱 저장 공간에 저장되며, 6항(백업)에서 설명하는 범위에서 Android 백업에도 포함됩니다.
- 앱을 삭제하거나 앱 데이터를 지우면 위 정보는 모두 삭제됩니다.

### 2. 인터넷을 사용하는 경우
- **AI 모델 내려받기**: 이용자가 내려받기를 누르면 보컬 분리 모델과 Whisper 음성 인식 모델을 Hugging Face(huggingface.co) 또는 GitHub(github.com)에서 내려받습니다.
  일반적인 인터넷 요청과 마찬가지로 해당 서버는 IP 주소와 기본 요청 정보(User-Agent)를 알 수 있습니다. 앱은 그 밖의 정보를 보내지 않습니다.
- **온라인 가사 찾기(선택)**: 가사 찾기에서 "온라인에서 찾기"를 누를 때만, 입력칸의 곡 제목과 가수를 독립 커뮤니티 가사 서비스 LRCLIB(lrclib.net)에 암호화된 연결로 보내고, 이용자가 고른 가사를 기기에만 저장합니다. 음악 파일과 그 내용은 보내지 않습니다. LRCLIB는 IP 주소와 앱 이름·버전(User-Agent)도 알 수 있습니다.
- **웹에서 검색(선택)**: 가사 찾기에서 "웹에서 검색"을 누르면 입력칸의 곡 제목과 가수, "가사"라는 낱말을 기기의 검색 앱(없으면 브라우저의 Google 검색)으로 넘깁니다. 그 뒤로는 그 앱의 방침에 따라 처리됩니다.
- **광고(Google AdMob)**: 무료 버전은 라이브러리·플레이어 화면에 배너 광고를 보여 주고, 이용자가 원할 때만 보상형 광고를 보여 줍니다.
  Google은 광고 제공·측정과 부정 사용 방지를 위해 광고 ID, 기기·앱 정보, 대략적인 위치(IP 주소 기반), 광고와의 상호작용, 진단 정보를 수집할 수 있으며, 이 정보는 전송 중 암호화됩니다.
  - 유럽경제지역(EEA)·영국·스위스 이용자에게는 Google User Messaging Platform으로 동의를 받습니다. 일부 미국 주의 주민은 맞춤형 광고를 위한 개인정보 판매·공유를 거부할 수 있습니다. 이 선택은 앱 설정의 "광고 개인정보 설정"(해당 지역에서만 표시)에서 언제든 바꿀 수 있습니다.
  - 광고 ID는 기기 설정(개인정보 보호 > 광고)에서 재설정하거나 삭제할 수 있습니다.
  - Pro를 구매하면 앱은 더 이상 광고를 요청하지 않습니다. 광고 제거를 구매하면 배너 광고는 요청하지 않지만, AI 기능의 무료 체험 화면이 열리면 Google에 보상형 광고를 요청하며, 이 광고는 직접 보기를 선택할 때만 표시됩니다.
  - 자세한 내용: [Google 개인정보처리방침](https://policies.google.com/privacy?hl=ko), [Google 서비스를 사용하는 앱의 정보 사용 방식](https://policies.google.com/technologies/partner-sites?hl=ko)
- **구매(Google Play 결제)**: 광고 제거와 Pro는 Google Play 결제로 판매합니다. 결제 수단 등 결제 정보는 Google이 처리하며 개발자에게 전달되지 않습니다.
  앱은 구매 여부만 기기에 저장해 오프라인에서도 기능이 유지되게 합니다.
- **Google Play 평가 카드**: AI 기능을 몇 번 쓴 뒤 Google Play 평가 카드가 뜰 수 있습니다. 이 카드는 Google Play가 띄우고 처리하며, 앱은 평가 내용을 받지 않습니다.

### 3. 제3자 수집 및 국외 이전
개발자는 이용자의 개인정보를 다른 사람에게 제공하지 않습니다. 다만 아래 서비스는 이용자가 앱을 쓰거나 개발자에게 메일을 보낼 때 정보를 직접 받습니다.
받는 곳이 국외에 있으면 정보는 그 나라로 이전됩니다.

- **Google LLC**: 광고(AdMob)와 광고 동의(User Messaging Platform)
  - 연락처: [Google 개인정보처리방침](https://policies.google.com/privacy?hl=ko)
  - 국가: 미국
  - 항목: 광고 ID·앱 세트 ID, IP 주소(대략적인 위치), 기기·앱 정보, 광고와의 상호작용(조회·클릭), 진단 정보
  - 시기·방법: Pro를 사지 않았다면, 앱을 시작할 때(광고 동의 확인)와 광고를 불러오거나 보여 줄 때 앱에 들어 있는 Google SDK가 암호화된 연결로 보냅니다.
  - 목적: 광고 동의 확인, 광고 제공·측정, 부정 사용 방지
  - 보유·이용 기간: Google 개인정보처리방침에 따릅니다.
  - 거부 방법과 효과: 광고 ID를 삭제하거나 "광고 개인정보 설정"(해당 지역)에서 거부하면 맞춤형 광고에 쓰이는 정보가 줄어듭니다(4항). 이때도 앱은 그대로 쓸 수 있고, 광고는 맞춤형이 아닐 수 있습니다. Pro를 구매하면 앱은 광고를 요청하지 않으며, 광고 제거는 배너 광고 요청만 멈춥니다.

- **LRCLIB(lrclib.net)**: 개인이 운영하는 커뮤니티 가사 서비스
  - 연락처: [lrclib.net](https://lrclib.net)
  - 국가: 공개되지 않음(국외일 수 있음)
  - 항목: 입력칸의 곡 제목과 가수, IP 주소, 앱 이름·버전(User-Agent)
  - 시기·방법: 가사 찾기에서 "온라인에서 찾기"를 누를 때만 암호화된 연결(HTTPS)로 보냅니다.
  - 목적: 가사 검색
  - 보유·이용 기간: LRCLIB의 운영 방식에 따릅니다.
  - 거부 방법과 효과: "온라인에서 찾기"를 누르지 않으면 전송되지 않습니다. 이때는 온라인 가사 찾기만 쓸 수 없습니다.

- **Hugging Face, Inc.(huggingface.co), GitHub, Inc.(github.com)**: AI 모델 내려받기
  - 연락처: privacy@huggingface.co, privacy@github.com
  - 국가: 미국
  - 항목: IP 주소, 기본 요청 정보(User-Agent)
  - 시기·방법: 이용자가 AI 모델 내려받기를 누를 때만 암호화된 연결(HTTPS)로 보냅니다.
  - 목적: 모델 파일 제공
  - 보유·이용 기간: 각 회사의 개인정보처리방침에 따릅니다.
  - 거부 방법과 효과: 모델을 내려받지 않으면 전송되지 않습니다. 이때 AI 가사와 AI 싱크는 쓸 수 없고, 보컬 분리는 설정에서 모델 파일을 직접 가져와야 쓸 수 있습니다.

- **Google LLC**: Gmail(개발자의 메일함)
  - 연락처: [Google 개인정보처리방침](https://policies.google.com/privacy?hl=ko)
  - 국가: 미국
  - 항목: 보낸 사람의 이메일 주소와 이름, 메일 내용
  - 시기·방법: 이용자가 개발자에게 메일을 보낼 때 이메일로 전송됩니다.
  - 목적: 문의 답변과 환불 처리
  - 보유·이용 기간: 문의가 끝난 뒤 1년, 환불·분쟁 기록은 3년이 지나면 삭제합니다.
  - 거부 방법과 효과: 메일을 보내지 않으면 전송되지 않습니다. 앱 기능에는 영향이 없습니다.

결제(2항)는 Google Play가 Google 개인정보처리방침에 따라 직접 처리하며, 그 과정에서 국외(예: 미국)로 전송될 수 있습니다. 결제 정보는 개발자에게 전달되지 않습니다.

### 4. 맞춤형 광고와 행태정보
Pro를 사지 않았다면, 앱은 Google(AdMob)이 광고 ID와 앱 이용 기록(광고 조회·클릭 등)을 수집해 맞춤형 광고와 광고 측정에 쓰도록 허용합니다. Google은 이 정보를 다른 앱·웹사이트에서의 활동과 함께 쓸 수 있습니다. 개발자는 이 정보를 받지 않습니다.

거부하려면 기기 설정(개인정보 보호 > 광고)에서 광고 ID를 삭제하거나, 앱 설정의 "광고 개인정보 설정"(해당 지역에서만 표시)에서 선택을 바꾸면 됩니다. Pro를 구매하면 앱은 광고를 요청하지 않습니다.

앱은 '추적 안 함(Do Not Track)' 신호에 반응하지 않습니다. 대신 이 항의 방법으로 거부할 수 있습니다.

### 5. 앱이 하지 않는 것
- 계정 생성이나 로그인을 요구하지 않습니다.
- 마이크, 카메라, 연락처, 정확한 위치, 사진에 접근하지 않습니다.
- 음악·동영상 파일을 업로드하지 않습니다(온라인 가사 찾기는 2항의 검색어만 보냅니다).
- 개발자는 분석 도구나 오류 보고 도구를 쓰지 않습니다. ONNX Runtime에 들어 있는 원격 측정(텔레메트리) 기능은 꺼 두었습니다.

### 6. 백업
Android 백업이 켜져 있으면 시스템이 설정, 재생목록, 숨긴 폴더, 추가한 동영상 파일 목록, 분리한 곡 목록, AI 기능 무료 체험 남은 횟수, Play 평가 요청 시점을 정하는 데 쓰는 횟수, 구매 상태를 이용자의 Google 계정에 백업할 수 있습니다. AI 모델, 분리한 음원, 만든 가사, 끝나지 않은 AI 가사 작업, 이어 듣기용 재생 정보(마지막 재생 대기열과 위치)는 백업에서 제외됩니다.

### 7. 보유 기간과 파기
- 기기 안의 정보(1항)는 앱을 삭제하거나 앱 데이터를 지우면 곧바로 삭제됩니다. 백업본(6항)은 이용자 Google 계정의 백업 설정을 따릅니다.
- 문의 메일은 문의가 끝난 뒤 1년(환불·분쟁 기록은 3년)이 지나면 메일함과 휴지통에서 영구 삭제합니다.
- 개발자는 Google Play Console에서 주문 번호·상품·결제 국가·날짜 같은 주문 정보와 Google Play 리뷰를 볼 수 있으며, 환불·세무 처리와 리뷰 답변에만 씁니다. 이 정보는 Google이 보관합니다.

### 8. 안전성 확보 조치
- 앱의 모든 인터넷 요청은 암호화된 연결(HTTPS)을 씁니다.
- 앱이 만든 데이터는 다른 앱이 읽을 수 없는 기기의 앱 전용 저장 공간에 둡니다.
- ONNX Runtime에 들어 있는 원격 측정(텔레메트리) 기능은 꺼 두었습니다.
- 보컬 분리 모델은 내려받은 뒤 SHA-256 값으로 확인하고, 값이 다르면 지웁니다.

### 9. 앱 접근권한
- **필수**: 음악 및 오디오(READ_MEDIA_AUDIO). 기기의 음악 목록을 만들고 재생하는 데 씁니다. 허용하지 않으면 라이브러리를 보여 줄 수 없습니다.
- **선택**: 알림(POST_NOTIFICATIONS). 보컬 분리와 AI 가사의 진행 알림에 씁니다. 허용하지 않아도 앱을 쓸 수 있습니다.
- 동영상과 가사 폴더는 권한 없이, 이용자가 직접 고른 파일과 폴더만 읽습니다.

### 10. 아동
앱은 아동을 대상으로 하지 않습니다. 여기서 아동은 대한민국에서는 만 14세 미만, 그 밖의 나라에서는 만 13세 또는 그 나라 법이 정한 나이 미만을 말합니다. 개발자는 아동의 개인정보를 알면서 수집하지 않습니다.

### 11. 이용자의 선택과 권리
이용자는 개발자가 가진 자신의 개인정보(문의 메일)에 대해 열람·정정·삭제·처리정지를 이메일로 요청할 수 있고, 개발자는 10일 안에 답합니다. 법정대리인도 같은 권리를 행사할 수 있습니다.
기기에 저장된 데이터는 앱을 삭제하거나 기기 설정(애플리케이션 > Voice Shift Player > 저장공간 > 데이터 삭제)에서 지울 수 있습니다.
Google이 처리하는 정보는 [Google 계정](https://myaccount.google.com)과 [내 광고 센터](https://myadcenter.google.com)에서 관리할 수 있습니다.

### 12. 권익침해 구제 방법
개인정보 침해로 상담이나 피해 구제가 필요하면 아래 기관에 문의할 수 있습니다.

- 개인정보분쟁조정위원회: (국번 없이) 1833-6972, www.kopico.go.kr
- 개인정보침해신고센터: (국번 없이) 118, privacy.kisa.or.kr
- 대검찰청: (국번 없이) 1301, www.spo.go.kr
- 경찰청: (국번 없이) 182, ecrm.police.go.kr

### 13. 방침의 변경
내용이 바뀌면 이 문서와 앱 안의 방침을 함께 고치고 시행일을 새로 적습니다.

이전 버전: 2026-09-26

### 14. 문의(개인정보 보호책임자)
개발자: jhS · 이메일: jhsong8804@gmail.com

---

## English

Voice Shift Player (on Google Play: "Voice Shift: Key+Vocal Remover"; the "App") is a music player made by an individual developer, jhS (the "developer").
The App has no accounts and the developer runs no servers. Apart from emails you send, the developer does not receive any personal information about you.
The advertising and purchase features in the App are provided by Google, which processes some information as described below.

### 1. Information processed on your device
- **Music and video files**: the App reads your audio files and their details (title, artist, album, folder, duration) to list and play them.
  Videos are read only when you pick them with "Add video files", and the App keeps read access to those files until you remove them from the library.
- **AI features**: vocal separation (ONNX Runtime) and AI lyrics and AI lyric sync (Whisper) run entirely on your device, also while they continue in the background with a progress notification. Your audio and its contents are never uploaded.
- **Lyrics folder**: if you pick a lyrics folder in Settings, the App keeps read access to its .lrc/.txt files and gives it back when you change or clear the folder.
- **Data the App creates**: settings, playlists, hidden folders, separated audio, created lyrics, remaining free AI uses, your purchase status (Remove Ads / Pro) and the other items listed in section 6 are stored in the App's storage on your device and included in Android backup to the extent described in section 6.
- Uninstalling the App or clearing its data deletes all of this.

### 2. When the App uses the internet
- **AI model downloads**: when you tap Download, the App fetches the vocal separation model and the Whisper speech recognition models from Hugging Face (huggingface.co) or GitHub (github.com).
  As with any web request, those servers see your IP address and a standard request header (user agent). The App sends nothing else.
- **Online lyrics search (optional)**: only when you tap "Search online" in Find lyrics, the App sends the title and artist in the search fields to LRCLIB (lrclib.net), an independent community lyrics service, over an encrypted connection, and saves the lyrics you pick on your device only. Your music files and their contents are never sent. LRCLIB also sees your IP address and the App's name and version (user agent).
- **Search the web (optional)**: when you tap "Search the web" in Find lyrics, the App passes the title and artist in the search fields and the word "lyrics" to your device's search app (or, if there is none, Google Search in your browser). That app then handles it under its own policy.
- **Ads (Google AdMob)**: the free version shows banner ads on the library and player screens and, only when you ask for one, rewarded ads.
  To serve and measure ads and to prevent fraud, Google may collect the advertising ID, device and app information, approximate location (from your IP address), interactions with ads and diagnostic information. This data is encrypted in transit.
  - Users in the European Economic Area, the UK and Switzerland are asked for consent through Google's User Messaging Platform. Residents of certain US states can opt out of the sale or sharing of their personal information for targeted advertising. You can change these choices at any time with "Ad privacy settings" in the App's settings (shown only where required).
  - You can reset or delete your advertising ID in your device settings (Privacy > Ads).
  - After you buy Pro, the App no longer requests ads. After you buy Remove Ads, it no longer requests banner ads; when a free-try screen for an AI feature opens, it still requests a rewarded ad from Google, which is shown only if you choose to watch it.
  - More information: [Google Privacy Policy](https://policies.google.com/privacy), [How Google uses information from apps that use its services](https://policies.google.com/technologies/partner-sites)
- **Purchases (Google Play billing)**: Remove Ads and Pro are sold through Google Play. Google processes your payment details; the developer never receives them.
  The App stores only whether you own a product, so it keeps working offline.
- **Google Play rating card**: after you have used the AI features a few times, Google Play may show its rating card. Google Play shows and handles the card; the App never receives your rating.

### 3. Third-party collection and international transfer
The developer does not share your personal information with anyone. The services below receive information directly when you use the App or email the developer.
Where a service is outside your country, the information is transferred there.

- **Google LLC**: ads (AdMob) and ad consent (User Messaging Platform)
  - Contact: [Google Privacy Policy](https://policies.google.com/privacy)
  - Country: USA
  - Items: advertising ID and app set ID, IP address (approximate location), device and app information, interactions with ads (views, clicks), diagnostic information
  - When and how: unless you own Pro, the Google SDK in the App sends them over an encrypted connection when the App starts (to check ad consent) and when it loads or shows an ad.
  - Purpose: checking ad consent, serving and measuring ads, preventing fraud
  - Retention: under Google's privacy policy
  - How to refuse, and the effect: deleting your advertising ID or declining in "Ad privacy settings" (where shown) reduces the information used for personalized ads (section 4). You can still use the App, and ads may not be personalized. After you buy Pro, the App no longer requests ads; Remove Ads stops only banner requests.

- **LRCLIB (lrclib.net)**: a community lyrics service run by an individual
  - Contact: [lrclib.net](https://lrclib.net)
  - Country: not disclosed (may be outside your country)
  - Items: the title and artist in the search fields, IP address, the App's name and version (user agent)
  - When and how: only when you tap "Search online" in Find lyrics, over an encrypted connection (HTTPS)
  - Purpose: finding lyrics
  - Retention: as LRCLIB runs its service
  - How to refuse, and the effect: if you don't tap "Search online", nothing is sent. Only the online lyrics search is then unavailable.

- **Hugging Face, Inc. (huggingface.co) and GitHub, Inc. (github.com)**: AI model downloads
  - Contact: privacy@huggingface.co, privacy@github.com
  - Country: USA
  - Items: IP address, a standard request header (user agent)
  - When and how: only when you tap Download for an AI model, over an encrypted connection (HTTPS)
  - Purpose: providing the model files
  - Retention: under each company's privacy policy
  - How to refuse, and the effect: if you don't download the models, nothing is sent. AI lyrics and AI lyric sync then can't be used, and vocal separation works only with a model file you import in Settings.

- **Google LLC**: Gmail (the developer's mailbox)
  - Contact: [Google Privacy Policy](https://policies.google.com/privacy)
  - Country: USA
  - Items: your email address and name, and your message
  - When and how: by email, when you write to the developer
  - Purpose: answering you and handling refunds
  - Retention: deleted one year after the conversation ends; refund or dispute records after three years
  - How to refuse, and the effect: if you don't email the developer, nothing is sent. The App works the same.

Purchases (section 2) are handled by Google Play directly under Google's privacy policy, and the information may be transferred outside your country (for example, to the USA). The developer never receives your payment details.

### 4. Personalized ads and behavioral information
Unless you own Pro, the App lets Google (AdMob) collect your advertising ID and how you use the App (such as ads viewed and clicked) for personalized ads and ad measurement. Google may use this together with your activity in other apps and websites over time. The developer does not receive this information.

To refuse, delete your advertising ID in your device settings (Privacy > Ads), or change your choice in "Ad privacy settings" in the App's settings (shown only where required). After you buy Pro, the App no longer requests ads.

The App does not respond to "Do Not Track" signals; use the controls in this section instead.

### 5. What the App does not do
- No accounts or sign-in.
- No access to the microphone, camera, contacts, precise location or photos.
- No upload of your music or video files (the online lyrics search sends only the search terms in section 2).
- No analytics or crash-reporting tools of the developer. The telemetry built into ONNX Runtime is turned off.

### 6. Backups
If Android backup is on, the system may back up your settings, playlists, hidden folders, the list of video files you added, the list of songs you separated, remaining free AI uses, the counts the App uses to time its Play rating request, and purchase status to your Google Account. AI models, separated audio, created lyrics, unfinished AI lyrics runs and the saved playback session (last queue and position) are excluded from backups.

### 7. Retention and deletion
- Information on your device (section 1) is deleted as soon as you uninstall the App or clear its data. Backups (section 6) follow the backup settings of your Google Account.
- Emails are permanently deleted from the mailbox and trash one year after the conversation ends (three years for refund or dispute records).
- In Google Play Console, the developer can see order information, such as the order number, product, country and date, and Google Play reviews. The developer uses them only for refunds, taxes and replies to reviews. Google keeps this information.

### 8. Security
- All of the App's web requests use encrypted connections (HTTPS).
- Data the App creates stays in its private storage on your device, which other apps cannot read.
- The telemetry built into ONNX Runtime is turned off.
- After download, the vocal separation model is checked against its SHA-256 hash and deleted if it does not match.

### 9. App permissions
- **Required**: Music and audio (READ_MEDIA_AUDIO), to list and play the music on your device. Without it, the App cannot show your library.
- **Optional**: Notifications (POST_NOTIFICATIONS), for progress notifications of vocal separation and AI lyrics. You can use the App without it.
- Videos and the lyrics folder need no permission: the App reads only the files and the folder you pick.

### 10. Children
The App is not directed at children. Here, children means users under 14 in South Korea, and under 13 or the age set by local law in other countries. The developer does not knowingly collect personal information from children.

### 11. Your choices and rights
You can ask the developer by email to access, correct or delete the personal information the developer holds about you (your emails), or to stop processing it. The developer answers within 10 days. Your legal representative can also make these requests.
To delete the data on your device, uninstall the App or clear its storage in Android settings (Apps > Voice Shift Player > Storage > Clear data).
Information processed by Google can be managed in your [Google Account](https://myaccount.google.com) and [My Ad Center](https://myadcenter.google.com).

### 12. Legal bases (EEA, UK, Switzerland)
- Personalized ads, and storing or reading information on your device for ads: your consent, which you can withdraw at any time in Ad privacy settings.
- Online lyrics search and model downloads: to provide the feature you asked for.
- Emails: to answer you.

You can complain to your local data protection authority.

### 13. Changes
If this policy changes, the updated version will be published here and in the App with a new effective date.

Previous version: 2026-09-26

### 14. Contact
Developer: jhS · Email: jhsong8804@gmail.com
