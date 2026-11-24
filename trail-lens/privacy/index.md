---
---

# Trail Lens 개인정보처리방침 / Privacy Policy

시행일 / Effective: 2026-11-22 · 개발자 / Developer: SummerRiversound

## 한국어

Trail Lens(이하 "앱")의 개발자는 계정이나 이름 같은 개인정보를 받지 않습니다. 앱이 기기 밖으로 보내는 것은 주변 장소를 받기 위한 지도 칸 번호뿐이고, 앱에 포함된 Google의 ARCore SDK는 아래와 같이 일부 정보를 Google로 보냅니다.

- **위치.** 달리기 거리와 페이스를 재고 빛을 실제 자리에 세우려고 정밀 위치 권한을 요청합니다. 위치는 기기 안에서만 쓰이고 개발자에게 보내지 않습니다. 앱이 화면에 없을 때는 위치를 받지 않습니다.
- **주변 장소 받기.** 주변 장소(강, 다리, 산, 역 등)를 빛기둥으로 세우려고, 현재 위치가 속한 지도 칸과 그 이웃 칸의 번호를 개발자의 장소 파일 서버(Cloudflare)에 HTTPS로 요청합니다. 칸 하나는 위도·경도 0.1°(한국에서 약 9 × 11 km)라 칸 번호로는 대략적인 지역만 알 수 있습니다. 요청에는 칸 번호 외의 정보가 없지만, 모든 인터넷 요청처럼 서버는 기기의 IP 주소를 봅니다. 개발자는 이 요청을 따로 기록하거나 보관하지 않습니다. 받은 장소 파일은 기기에 두고 30일마다 새로 받으며, 새로 받지 못하면 갖고 있던 파일을 계속 씁니다. 앱 삭제나 저장공간 지우기로 지워집니다.
- **달리기 기록.** 지난 기록과 같이 달리도록 달린 길(위치와 시간)을 기기 안에만 저장합니다. 최근 20개까지 두고, 준비 화면의 "기록 지우기"나 앱 삭제로 지워집니다. 클라우드 백업과 새 기기로의 이전에서 제외합니다.
- **머리 추적.** 빛을 제자리에 세우려고 머리 추적 권한(`android.permission.HEAD_TRACKING`)을 요청합니다. 머리 위치와 방향은 그 자리에서 쓰고 저장하거나 보내지 않습니다. 거부해도 수치만으로 달릴 수 있습니다.
- **ARCore가 수집하는 정보.** 앱에 포함된 Google Play 서비스 AR(ARCore) SDK는 ARCore 기능 사용 여부와 관계없이 사용자 ID(Google 계정으로 로그인한 경우) 또는 기기 ID, 성능 및 기타 진단 데이터, API 사용 및 앱 활동 데이터를 분석과 AR 경험 개선을 위해 Google로 전송합니다. 이 정보는 전송 중 암호화되고 앱에서 끌 수 없습니다. Google은 이 중 진단 데이터와 API 사용 데이터를 제3자와 공유하지 않는다고 밝힙니다. 개발자는 이 정보를 받지 않으며, 처리는 [Google 개인정보처리방침](https://policies.google.com/privacy)에 따릅니다.
- **Google Play 서비스 AR(ARCore).** 이 앱은 Google이 제공하는 Google Play 서비스 AR(ARCore)에서 실행되며, [Google 개인정보처리방침](https://policies.google.com/privacy)이 적용됩니다.
- **없는 것.** 계정, 광고, 분석 도구, 오류 보고 도구가 없습니다. 앱 안에는 결제가 없고, 앱 구매는 Google Play가 처리하며 개발자는 결제 정보를 받지 않습니다.
- **제3자 제공 없음.** 개발자는 정보를 제3자에게 제공하거나 판매하지 않습니다. 장소 파일 서버는 개발자가 쓰는 Cloudflare 서비스이며, 칸 번호 요청을 처리하는 데만 쓰입니다.
- **장소 데이터의 출처.** 장소 이름과 위치는 OpenStreetMap에서 왔습니다. © OpenStreetMap contributors, [ODbL](https://opendatacommons.org/licenses/odbl/) 라이선스([openstreetmap.org/copyright](https://www.openstreetmap.org/copyright)). 앱이 쓰는 장소 데이터베이스(칸 파일)는 ODbL 1.0으로 [summerriversound.github.io/xr-app-policies/trail-lens/data/](https://summerriversound.github.io/xr-app-policies/trail-lens/data/)에서 받을 수 있습니다.
- **아동.** 앱은 아동을 대상으로 하지 않습니다.
- **변경.** 이 방침이 바뀌면 이 페이지에 새 시행일과 함께 게시합니다.
- **문의.** summer.riversound@gmail.com

## English

The developer of Trail Lens ("the app") does not receive personal details such as an account or a name. The only thing the app itself sends off the device is a map cell number, to download nearby places; the bundled Google ARCore SDK sends some information to Google as described below.

- **Location.** The app asks for precise location to measure distance and pace and to stand its light at real places. Location is used on the device only and is never sent to the developer. The app does not receive location while it is off the screen.
- **Downloading nearby places.** To stand light pillars at nearby places (rivers, bridges, peaks, stations and the like), the app requests, over HTTPS, the files for the map cell you are in and its neighbours from the developer's place-file server (Cloudflare). A cell is 0.1° of latitude and longitude (about 9 × 11 km in Korea), so a cell number tells only the rough area. The request carries nothing but the cell number, although, like any internet request, the server sees the device's IP address. The developer does not log or keep these requests. Downloaded place files stay on the device and are fetched again every 30 days; if that fails, the files already there keep being used. Uninstalling the app or clearing its storage deletes them.
- **Run records.** So you can run alongside your last run, the route you ran (positions and times) is stored on the device only. The newest 20 runs are kept; "Delete runs" on the ready panel or uninstalling the app deletes them. They are excluded from cloud backup and from transfer to a new device.
- **Head tracking.** The app asks for head-tracking permission (`android.permission.HEAD_TRACKING`) to keep its light in place. Head position and direction are used in the moment and never stored or sent. Without it you can still run with numbers only.
- **Data collected by ARCore.** The Google Play Services for AR (ARCore) SDK bundled in the app, regardless of which ARCore features the app uses, sends Google a user ID (when signed in with a Google account) or a device ID, performance and other diagnostic data, and API usage and app activity data, for analytics and to improve AR experiences. It is encrypted in transit and cannot be switched off in the app. Google states that it does not share the diagnostic and API usage data with third parties. The developer does not receive it; it is handled under the [Google Privacy Policy](https://policies.google.com/privacy).
- **Google Play Services for AR (ARCore).** This application runs on Google Play Services for AR (ARCore), which is provided by Google and governed by the [Google Privacy Policy](https://policies.google.com/privacy).
- **What there is not.** No account, ads, analytics or crash reporting. There are no purchases inside the app; Google Play handles the app's purchase and the developer receives no payment details.
- **No sharing.** The developer does not share or sell any data. The place-file server is a Cloudflare service the developer uses only to answer cell requests.
- **Source of place data.** Place names and positions come from OpenStreetMap. © OpenStreetMap contributors, licensed under the [ODbL](https://opendatacommons.org/licenses/odbl/) ([openstreetmap.org/copyright](https://www.openstreetmap.org/copyright)). The place database the app uses (the cell files) is available under ODbL 1.0 at [summerriversound.github.io/xr-app-policies/trail-lens/data/](https://summerriversound.github.io/xr-app-policies/trail-lens/data/).
- **Children.** The app is not directed at children.
- **Changes.** Any change to this policy will be posted on this page with a new effective date.
- **Contact.** summer.riversound@gmail.com
