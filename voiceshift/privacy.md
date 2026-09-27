---
title: Voice Shift Player 개인정보처리방침 / Privacy Policy
permalink: /voiceshift/privacy/
---

# Voice Shift Player 개인정보처리방침 / Privacy Policy

시행일 / Effective date: 2026-09-26

[한국어](#한국어) · [English](#english)

## 한국어

Voice Shift Player(Google Play 이름: "Voice Shift: 키 변경·보컬 제거", 이하 "앱")는 개인 개발자 jhS(이하 "개발자")가 만든 뮤직 플레이어입니다.
앱에는 계정이 없고 개발자가 운영하는 서버도 없습니다. 개발자는 이용자의 개인정보를 수집하거나 전달받지 않습니다.
다만 앱에 들어 있는 광고·결제 기능은 Google이 제공하며, Google이 아래와 같이 일부 정보를 처리합니다.

### 1. 기기 안에서 처리하는 정보
- **음악·동영상 파일**: 기기의 오디오 파일과 그 정보(제목, 아티스트, 앨범, 폴더, 재생 시간)를 읽어 목록을 보여 주고 재생합니다.
  동영상은 이용자가 "동영상 파일 추가"로 직접 고른 파일만 읽으며, 라이브러리에서 제거할 때까지 그 파일의 읽기 권한을 유지합니다.
- **AI 기능**: 보컬 분리(ONNX Runtime)와 AI 가사 만들기·AI 싱크(Whisper)는 진행 알림을 띄우고 백그라운드에서 계속될 때도 모두 기기 안에서 실행됩니다. 음원과 그 내용은 어디에도 업로드되지 않습니다.
- **가사 폴더**: 설정에서 가사 폴더를 고르면 그 폴더의 .lrc/.txt 파일을 읽을 수 있는 권한을 유지하며, 폴더를 바꾸거나 지우면 권한을 돌려줍니다.
- **앱이 만든 데이터**: 설정, 재생목록, 숨긴 폴더, 분리한 음원, 만든 가사, AI 기능 무료 체험 남은 횟수, 구매 상태(광고 제거·Pro)와 5항에 적은 그 밖의 항목은 기기의 앱 저장 공간에 저장되며, 5항(백업)에서 설명하는 범위에서 Android 백업에도 포함됩니다.
- 앱을 삭제하거나 앱 데이터를 지우면 위 정보는 모두 삭제됩니다.

### 2. 인터넷을 사용하는 경우
- **AI 모델 내려받기**: 이용자가 내려받기를 누르면 보컬 분리 모델과 Whisper 음성 인식 모델을 Hugging Face(huggingface.co) 또는 GitHub(github.com)에서 내려받습니다.
  일반적인 인터넷 요청과 마찬가지로 해당 서버는 IP 주소와 기본 요청 정보(User-Agent)를 알 수 있습니다. 앱은 그 밖의 정보를 보내지 않습니다.
- **온라인 가사 찾기(선택)**: 가사 찾기에서 "온라인에서 찾기"를 누를 때만, 입력칸의 곡 제목과 가수를 독립 커뮤니티 가사 서비스 LRCLIB(lrclib.net)에 암호화된 연결로 보내고, 이용자가 고른 가사를 기기에만 저장합니다. 음악 파일과 그 내용은 보내지 않습니다. LRCLIB는 IP 주소와 앱 이름·버전(User-Agent)도 알 수 있습니다.
- **광고(Google AdMob)**: 무료 버전은 라이브러리·플레이어 화면에 배너 광고를 보여 주고, 이용자가 원할 때만 보상형 광고를 보여 줍니다.
  Google은 광고 제공·측정과 부정 사용 방지를 위해 광고 ID, 기기·앱 정보, 대략적인 위치(IP 주소 기반), 광고와의 상호작용, 진단 정보를 수집할 수 있으며, 이 정보는 전송 중 암호화됩니다.
  - 유럽경제지역(EEA)·영국·스위스와 일부 미국 주의 이용자에게는 Google User Messaging Platform으로 동의를 받습니다. 선택은 앱 설정의 "광고 개인정보 설정"(해당 지역에서만 표시)에서 언제든 바꿀 수 있습니다.
  - 광고 ID는 기기 설정(개인정보 보호 > 광고)에서 재설정하거나 삭제할 수 있습니다.
  - Pro를 구매하면 앱은 더 이상 광고를 요청하지 않습니다. 광고 제거를 구매하면 배너 광고는 요청하지 않지만, AI 기능의 무료 체험 화면이 열리면 Google에 보상형 광고를 요청하며, 이 광고는 직접 보기를 선택할 때만 표시됩니다.
  - 자세한 내용: [Google 개인정보처리방침](https://policies.google.com/privacy?hl=ko), [Google 서비스를 사용하는 앱의 정보 사용 방식](https://policies.google.com/technologies/partner-sites?hl=ko)
- **구매(Google Play 결제)**: 광고 제거와 Pro는 Google Play 결제로 판매합니다. 결제 수단 등 결제 정보는 Google이 처리하며 개발자에게 전달되지 않습니다.
  앱은 구매 여부만 기기에 저장해 오프라인에서도 기능이 유지되게 합니다.

### 3. 제3자 제공 및 국외 이전
개발자는 이용자의 개인정보를 누구에게도 제공하지 않습니다. 광고와 결제 과정의 정보는 Google LLC(미국)가 Google 개인정보처리방침에 따라 직접 수집·처리하며,
그 과정에서 국외(예: 미국)로 전송될 수 있습니다. 광고 동의를 거부하거나 광고 ID를 삭제하면 맞춤 광고에 쓰이는 정보가 줄어듭니다. 이용자가 온라인 가사 찾기를 쓰면 검색어는 LRCLIB(해외 서버일 수 있음)로 전송됩니다.

### 4. 앱이 하지 않는 것
- 계정 생성이나 로그인을 요구하지 않습니다.
- 마이크, 카메라, 연락처, 정확한 위치, 사진에 접근하지 않습니다.
- 음악·동영상 파일을 업로드하지 않습니다(온라인 가사 찾기는 2항의 검색어만 보냅니다).
- 개발자는 분석 도구나 오류 보고 도구를 쓰지 않습니다. ONNX Runtime에 들어 있는 원격 측정(텔레메트리) 기능은 꺼 두었습니다.
- 앱이 만든 데이터는 기기의 앱 전용 저장 공간에 두며, 앱의 인터넷 요청은 모두 암호화된 연결(HTTPS)을 씁니다.

### 5. 백업
Android 백업이 켜져 있으면 시스템이 설정, 재생목록, 숨긴 폴더, 추가한 동영상 파일 목록, 분리한 곡 목록, AI 기능 무료 체험 남은 횟수, Play 평가 요청 시점을 정하는 데 쓰는 횟수, 구매 상태를 이용자의 Google 계정에 백업할 수 있습니다. AI 모델, 분리한 음원, 만든 가사, 끝나지 않은 AI 가사 작업, 이어 듣기용 재생 정보(마지막 재생 대기열과 위치)는 백업에서 제외됩니다.

### 6. 아동
앱은 만 13세 미만 아동을 대상으로 하지 않습니다. 개발자는 나이를 포함해 어떤 이용자의 개인정보도 수집하지 않습니다.

### 7. 이용자의 선택과 권리
개발자는 이용자의 개인정보를 보관하지 않으므로 열람·정정·삭제를 요청받을 정보가 없습니다.
기기에 저장된 데이터는 앱을 삭제하거나 기기 설정(애플리케이션 > Voice Shift Player > 저장공간 > 데이터 삭제)에서 지울 수 있습니다.
Google이 처리하는 정보는 [Google 계정](https://myaccount.google.com)과 [내 광고 센터](https://myadcenter.google.com)에서 관리할 수 있습니다.

### 8. 방침의 변경
내용이 바뀌면 이 문서와 앱 안의 방침을 함께 고치고 시행일을 새로 적습니다.

### 9. 문의(개인정보 보호책임자)
개발자: jhS · 이메일: jhsong8804@gmail.com

---

## English

Voice Shift Player (on Google Play: "Voice Shift: Key+Vocal Remover"; the "App") is a music player made by an individual developer, jhS (the "developer").
The App has no accounts and the developer runs no servers. The developer does not collect or receive any personal information about you.
The advertising and purchase features in the App are provided by Google, which processes some information as described below.

### 1. Information processed on your device
- **Music and video files**: the App reads your audio files and their details (title, artist, album, folder, duration) to list and play them.
  Videos are read only when you pick them with "Add video files", and the App keeps read access to those files until you remove them from the library.
- **AI features**: vocal separation (ONNX Runtime) and AI lyrics and AI lyric sync (Whisper) run entirely on your device, also while they continue in the background with a progress notification. Your audio and its contents are never uploaded.
- **Lyrics folder**: if you pick a lyrics folder in Settings, the App keeps read access to its .lrc/.txt files and gives it back when you change or clear the folder.
- **Data the App creates**: settings, playlists, hidden folders, separated audio, created lyrics, remaining free AI uses, your purchase status (Remove Ads / Pro) and the other items listed in section 5 are stored in the App's storage on your device and included in Android backup to the extent described in section 5.
- Uninstalling the App or clearing its data deletes all of this.

### 2. When the App uses the internet
- **AI model downloads**: when you tap Download, the App fetches the vocal separation model and the Whisper speech recognition models from Hugging Face (huggingface.co) or GitHub (github.com).
  As with any web request, those servers see your IP address and a standard request header (user agent). The App sends nothing else.
- **Online lyrics search (optional)**: only when you tap "Search online" in Find lyrics, the App sends the title and artist in the search fields to LRCLIB (lrclib.net), an independent community lyrics service, over an encrypted connection, and saves the lyrics you pick on your device only. Your music files and their contents are never sent. LRCLIB also sees your IP address and the App's name and version (user agent).
- **Ads (Google AdMob)**: the free version shows banner ads on the library and player screens and, only when you ask for one, rewarded ads.
  To serve and measure ads and to prevent fraud, Google may collect the advertising ID, device and app information, approximate location (from your IP address), interactions with ads and diagnostic information. This data is encrypted in transit.
  - Users in the European Economic Area, the UK, Switzerland and certain US states are asked for consent through Google's User Messaging Platform. You can change your choice at any time with "Ad privacy settings" in the App's settings (shown only where required).
  - You can reset or delete your advertising ID in your device settings (Privacy > Ads).
  - After you buy Pro, the App no longer requests ads. After you buy Remove Ads, it no longer requests banner ads; when a free-try screen for an AI feature opens, it still requests a rewarded ad from Google, which is shown only if you choose to watch it.
  - More information: [Google Privacy Policy](https://policies.google.com/privacy), [How Google uses information from apps that use its services](https://policies.google.com/technologies/partner-sites)
- **Purchases (Google Play billing)**: Remove Ads and Pro are sold through Google Play. Google processes your payment details; the developer never receives them.
  The App stores only whether you own a product, so it keeps working offline.

### 3. Sharing and international transfer
The developer does not share your personal information with anyone. For ads and purchases, Google LLC (USA) collects and processes the information above directly under Google's privacy policy,
and it may be transferred outside your country (for example, to the USA). Declining ad consent or deleting your advertising ID reduces the information used for personalized ads. When you use the online lyrics search, your search terms go to LRCLIB, whose servers may be outside your country.

### 4. What the App does not do
- No accounts or sign-in.
- No access to the microphone, camera, contacts, precise location or photos.
- No upload of your music or video files (the online lyrics search sends only the search terms in section 2).
- No analytics or crash-reporting tools of the developer. The telemetry built into ONNX Runtime is turned off.
- Data the App creates stays in its private storage on your device, and all of the App's web requests use encrypted connections (HTTPS).

### 5. Backups
If Android backup is on, the system may back up your settings, playlists, hidden folders, the list of video files you added, the list of songs you separated, remaining free AI uses, the counts the App uses to time its Play rating request, and purchase status to your Google Account. AI models, separated audio, created lyrics, unfinished AI lyrics runs and the saved playback session (last queue and position) are excluded from backups.

### 6. Children
The App is not directed at children under 13. The developer does not collect personal information from users of any age.

### 7. Your choices and rights
The developer holds no personal information about you, so there is nothing to access, correct or delete on the developer's side.
To delete the data on your device, uninstall the App or clear its storage in Android settings (Apps > Voice Shift Player > Storage > Clear data).
Information processed by Google can be managed in your [Google Account](https://myaccount.google.com) and [My Ad Center](https://myadcenter.google.com).

### 8. Changes
If this policy changes, the updated version will be published here and in the App with a new effective date.

### 9. Contact
Developer: jhS · Email: jhsong8804@gmail.com
