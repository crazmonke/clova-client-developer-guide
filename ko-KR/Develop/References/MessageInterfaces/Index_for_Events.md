# 이벤트 메시지 색인

| 네임스페이스         | 메시지 이름       | 설명                                             |
|-------------------|----------------|-------------------------------------------------|
| Alerts            | [`AlertStarted`](/Develop/References/MessageInterfaces/Alerts.md#AlertStarted)                 | 알람이 시작되었음을 CLOVA에 보고합니다. |
| Alerts            | [`AlertStopped`](/Develop/References/MessageInterfaces/Alerts.md#AlertStopped)                 | 알람이 중지되었음을 CLOVA에 보고합니다. |
| Alerts            | [`DeleteAlertFailed`](/Develop/References/MessageInterfaces/Alerts.md#DeleteAlertFailed)       | 클라이언트에 설정된 특정 알람을 삭제하는데 실패했음을 CLOVA에 보고합니다. |
| Alerts            | [`DeleteAlertSucceeded`](/Develop/References/MessageInterfaces/Alerts.md#DeleteAlertSucceeded) | 클라이언트에 설정된 특정 알람을 삭제하는데 성공했음을 CLOVA에 보고합니다. |
| Alerts            | [`RequestAlertStop`](/Develop/References/MessageInterfaces/Alerts.md#RequestAlertStop)         | 클라이언트가 현재 울리고 있는 알람을 중지하도록 CLOVA에 요청합니다.  |
| Alerts            | [`RequestDeleteAlert`](/Develop/References/MessageInterfaces/Alerts.md##RequestDeleteAlert)    | 클라이언트에 등록되어 있는 알람을 삭제하도록 CLOVA에 요청합니다.  |
| Alerts            | [`RequestSynchronizeAlert`](/Develop/References/MessageInterfaces/Alerts.md#RequestSynchronizeAlert) | CLOVA의 클라우드 환경에 저장된 사용자의 알람 정보가 클라이언트에 동기화되도록 CLOVA에 요청합니다. |
| Alerts            | [`SetAlertFailed`](/Develop/References/MessageInterfaces/Alerts.md#SetAlertFailed)             | 클라이언트가 특정 알람을 추가 또는 수정하는데 실패했음을 CLOVA에 보고합니다. |
| Alerts            | [`SetAlertSucceeded`](/Develop/References/MessageInterfaces/Alerts.md#SetAlertSucceeded)       | 클라이언트가 특정 알람을 추가 또는 수정하는데 성공했음을 CLOVA에 보고합니다. |
| AudioPlayer       | [`PlaybackQueueCleared`](/Develop/References/MessageInterfaces/AudioPlayer.md#PlaybackQueueCleared) | 클라이언트가 CLOVA로부터 [`AudioPlayer.ClearQueue`](/Develop/References/MessageInterfaces/AudioPlayer.md#ClearQueue) 지시 메시지를 받은 후 재생 대기열(queue)를 초기화했음을 CLOVA에 보고합니다.    |
| AudioPlayer       | [`PlayFinished`](/Develop/References/MessageInterfaces/AudioPlayer.md#PlayFinished) | 클라이언트가 오디오 스트림 재생을 완료할 때 재생 완료된 오디오 스트림 정보를 CLOVA에 보고합니다.        |
| AudioPlayer       | [`PlayPaused`](/Develop/References/MessageInterfaces/AudioPlayer.md#PlayPaused)     | 클라이언트가 오디오 스트림 재생을 일시 정지할 때 일시 정지된 오디오 스트림 정보를 CLOVA에 보고합니다.    |
| AudioPlayer       | [`PlayResumed`](/Develop/References/MessageInterfaces/AudioPlayer.md#PlayResumed)   | 클라이언트가 오디오 스트림 재생을 재개할 때 재개된 오디오 스트림 정보를 CLOVA에 보고합니다.            |
| AudioPlayer       | [`PlayStarted`](/Develop/References/MessageInterfaces/AudioPlayer.md#PlayStarted)   | 클라이언트가 오디오 스트림 재생을 시작할 때 재생이 시작된 오디오 스트림 정보를 CLOVA에 보고합니다.       |
| AudioPlayer       | [`PlayStopped`](/Develop/References/MessageInterfaces/AudioPlayer.md#PlayStopped)   | 클라이언트가 오디오 스트림 재생을 중지할 때 재생이 중지된 오디오 스트림 정보를 CLOVA에 보고합니다.       |
| AudioPlayer       | [`ProgressReportDelayPassed`](/Develop/References/MessageInterfaces/AudioPlayer.md#ProgressReportPositionPassed) | 오디오 스트림 재생이 시작된 후 지정된 시간만큼 시간이 지났을 때 현재 재생 상태([`AudioPlayer.PlaybackState`](/Develop/References/Context_Objects.md#PlaybackState))를 CLOVA에 보고합니다. |
| AudioPlayer       | [`ProgressReportIntervalPassed`](/Develop/References/MessageInterfaces/AudioPlayer.md#ProgressReportPositionPassed)| 오디오 스트림 재생이 시작된 후 지정된 시간 간격마다 현재 재생 상태([`AudioPlayer.PlaybackState`](/Develop/References/Context_Objects.md#PlaybackState))를 CLOVA에 보고합니다. |
| AudioPlayer       | [`ProgressReportPositionPassed`](/Develop/References/MessageInterfaces/AudioPlayer.md#ProgressReportPositionPassed) | 오디오 스트림 재생이 시작된 후 지정된 시점에 현재 재생 상태([`AudioPlayer.PlaybackState`](/Develop/References/Context_Objects.md#PlaybackState))를 CLOVA에 보고합니다. |
| AudioPlayer       | [`ReportPlaybackState`](/Develop/References/MessageInterfaces/AudioPlayer.md#ReportPlaybackState) | 클라이언트의 현재 음원 재생 상태를 CLOVA에 보고합니다.  |
| AudioPlayer       | [`RequestPlaybackState`](/Develop/References/MessageInterfaces/AudioPlayer.md#RequestPlaybackState) | 클라이언트의 음원 재생 상태를 CLOVA에 요청합니다.   |
| AudioPlayer       | [`StreamRequested`](/Develop/References/MessageInterfaces/AudioPlayer.md#StreamRequested) | 오디오 스트림 재생을 위해 실제 스트리밍 URL과 같은 정보를 추가로 CLOVA에 요청합니다. |
| Clova             | [`ProcessDelegatedEvent`](/Develop/References/MessageInterfaces/Clova.md#ProcessDelegatedEvent)                          | [위임된 사용자 요청](/Develop/Guides/Handle_Delegation.md)에 대한 결과를 CLOVA에 요청합니다.  |
<<<<<<< HEAD
| DeviceControl     | [`ActionExecuted`](/Develop/References/MessageInterfaces/DeviceControl.md#ActionExecuted) | 클라이언트가 기기 제어를 정상적으로 수행했음을 보고하기 위해 사용됩니다.                               |
| DeviceControl     | [`ActionFailed`](/Develop/References/MessageInterfaces/DeviceControl.md#ActionFailed) | 클라이언트는 기기 제어를 수행할 수 없거나 수행에 실패했음을 CIC에 보고하기 위해 사용됩니다.                   |
| DeviceControl     | [`BtRequestForPINCode`](/Develop/References/MessageInterfaces/DeviceControl.md#BtRequestForPINCode) | 클라이언트는 블루투스 기기가 PIN 코드 입력 요청을 할 때 이 메시지를 사용하여 CIC에 요청을 전달해야 합니다.       |
| DeviceControl     | [`BtRequestToCancelPINCodeInput`](/Develop/References/MessageInterfaces/DeviceControl.md#BtRequestToCancelPINCodeInput) | 클라이언트는 CIC에 PIN 코드 입력 요청을 취소하고자 할 때 이 메시지를 사용해야 합니다. |
| DeviceControl     | [`ReportState`](/Develop/References/MessageInterfaces/DeviceControl.md#ReportState)   | 클라이언트는 기기의 현재 상태를 CIC로 보고할 때 이 메시지를 사용해야 합니다.                              |
| DeviceControl     | [`RequestDeviceList`](/Develop/References/MessageInterfaces/DeviceControl.md#RequestDeviceList)                      | 클라이언트는 사용자 계정에 등록된 클라이언트 기기 목록과 각 클라이언트의 식별 정보를 파악하고자 할 때 이 이벤트 메시지를 CIC로 전송합니다. |
| DeviceControl     | [`RequestStateSynchronization`](/Develop/References/MessageInterfaces/DeviceControl.md#RequestStateSynchronization) | 사용자의 계정에 등록된 다른 클라이언트 기기의 현재 상태를 파악하고자 할 때 이 이벤트 메시지를 CIC로 전송합니다.  |
=======
| Clova             | [`RequestSuggestion`](/Develop/References/MessageInterfaces/Clova.md#RequestSuggestion)    | 클라이언트가 화면에 표시할 추천 키워드를 CLOVA에 요청합니다. |
| Clova             | [`TextMessage`](/Develop/References/MessageInterfaces/Clova.md#TextMessage)          | CLOVA 앱 또는 연동 앱(companion app)이 기기 형태의 특정 클라이언트에 TTS 음성 메시지를 보내도록 CLOVA에 요청합니다.  |
| Clova             | [`VoiceMessage`](/Develop/References/MessageInterfaces/Clova.md#VoiceMessage)         | CLOVA 앱 또는 연동 앱(companion app)이 기기 형태의 특정 클라이언트에 사용자가 입력한 음성 메시지를 보내도록 CLOVA에 요청합니다.     |
| DeviceControl     | [`ActionExecuted`](/Develop/References/MessageInterfaces/DeviceControl.md#ActionExecuted) | 기기 제어 작업이 정상적으로 수행되었음을 CLOVA에 보고합니다.               |
| DeviceControl     | [`ActionFailed`](/Develop/References/MessageInterfaces/DeviceControl.md#ActionFailed) | 기기 제어 작업을 수행할 수 없거나 실패했음을 CLOVA에 보고합니다.      |
| DeviceControl     | [`BtRequestForPINCode`](/Develop/References/MessageInterfaces/DeviceControl.md#BtRequestForPINCode) | 외부 블루투스 기기가 PIN 코드 입력 요청을 할 때 해당 PIN 코드를 CLOVA에 전달합니다.       |
| DeviceControl     | [`BtRequestToCancelPINCodeInput`](/Develop/References/MessageInterfaces/DeviceControl.md#BtRequestToCancelPINCodeInput) | PIN 코드 입력을 취소하도록 CLOVA에 요청합니다. |
| DeviceControl     | [`ClockInfoChanged`](/Develop/References/MessageInterfaces/DeviceControl.md#ClockInfoChanged)   | 시계의 표시 대상이 변경되었음을 CLOVA에 보고합니다.                    |
| DeviceControl     | [`ReportSmartCommandSettings`](/Develop/References/MessageInterfaces/DeviceControl.md#ReportSmartCommandSettings)   | 기기의 스마트 버튼 설정 결과를 CLOVA에 보고합니다.                     |
| DeviceControl     | [`ReportState`](/Develop/References/MessageInterfaces/DeviceControl.md#ReportState)   | 기기의 현재 상태를 CLOVA에 보고합니다.                              |
| DeviceControl     | [`RequestDeviceList`](/Develop/References/MessageInterfaces/DeviceControl.md#RequestDeviceList)                      | 사용자 계정에 등록된 클라이언트 기기 목록과 각 클라이언트의 식별 정보를 CLOVA에 요청합니다. |
| DeviceControl     | [`RequestSmartCommandList`](/Develop/References/MessageInterfaces/DeviceControl.md#RequestSmartCommandList) | 특정 클라이언트 기기의 스마트 버튼에 등록 가능한 명령 목록을 CLOVA에 요청합니다.  |
| DeviceControl     | [`RequestStateSynchronization`](/Develop/References/MessageInterfaces/DeviceControl.md#RequestStateSynchronization) | 사용자의 계정에 등록된 다른 클라이언트 기기의 현재 상태를 CLOVA에 요청합니다.  |
| DeviceControl     | [`SmartButtonIssued`](/Develop/References/MessageInterfaces/DeviceControl.md#SmartButtonIssued)      | 기기의 스마트 버튼이 눌렸거나 그에 준하는 사용자의 UI 조작이 있었음을 CLOVA에 보고합니다.  |
| Downchannel       | [`RequestDirectiveSubscription`](/Develop/References/MessageInterfaces/Downchannel.md#RequestDirectiveSubscription)  | Downchannel을 통해 클라이언트가 구독할 지시 메시지를 조정합니다.      |
| E2ESecuredDataExchange | [`ReportData`](/Develop/References/MessageInterfaces/E2ESecuredDataExchange.md#ReportData)           | [`E2ESecuredDataExchange.ExpectReportData`](/Develop/References/MessageInterfaces/E2ESecuredDataExchange.md#ExpectReportData) 지시 메시지를 받은 후 요청된 암호화 데이터를 CLOVA에 공유합니다. |
| E2ESecuredDataExchange | [`RequestData`](/Develop/References/MessageInterfaces/E2ESecuredDataExchange.md#RequestData)         | 대상 클라이언트가 암호화 데이터를 보내도록 CLOVA에 요청합니다.  |
| E2ESecuredDataExchange | [`RequestEnd`](/Develop/References/MessageInterfaces/E2ESecuredDataExchange.md#RequestEnd)           | 대상 클라이언트가 암호화 통신 세션을 종료하도록 CLOVA에 요청합니다. |
| E2ESecuredDataExchange | [`RequestReady`](/Develop/References/MessageInterfaces/E2ESecuredDataExchange.md#RequestReady)       | 대상 클라이언트가 암호화 통신을 준비하도록 CLOVA에 요청합니다.           |
| E2ESecuredDataExchange | [`RequestReturnResult`](/Develop/References/MessageInterfaces/E2ESecuredDataExchange.md#RequestReturnResult) | 암호화 통신과 관련된 작업을 수행한 후 조건에 따라 그 결과를 CLOVA에 보고합니다.  |
| E2ESecuredDataExchange | [`RequestSendData`](/Develop/References/MessageInterfaces/E2ESecuredDataExchange.md#RequestSendData) | 대칭키로 암호화된 데이터를 대상 클라이언트에게 보내도록 CLOVA에 요청합니다. |
| LineApp           | [`RequestSynthesizerTTS`](/Develop/References/MessageInterfaces/LineApp.md#RequestSynthesizerTTS) | 통합 검색 서비스로부터 전달받은 텍스트에 대한 음성 합성을 CLOVA에 요청합니다. |
| Music             | [`RequestPanel`](/Develop/References/MessageInterfaces/Music.md#RequestPanel) | 화면에 표시해야 하는 뮤직 패널을 CLOVA에 요청합니다. |
| MusicRecognizer    | [`Recognize`](/Develop/References/MessageInterfaces/MusicRecognizer.md#Recognize)  | 사용자가 입력한 오디오 데이터를 이용하여 음악을 인식하도록 CLOVA에 요청합니다.          |
| MusicRecognizer    | [`RequestPlaylists`](/Develop/References/MessageInterfaces/MusicRecognizer.md#Recognize#RequestPlaylists) | 음악 인식 서비스가 제공하는 재생 목록을 CLOVA에 요청합니다. |
| MusicRecognizer    | [`Search`](/Develop/References/MessageInterfaces/MusicRecognizer.md#Search)  | 음악 ID(`trackId`)에 해당하는 곡 정보를 CLOVA에 요청합니다.           |
| Naver              | [`SearchMusic`](/Develop/References/MessageInterfaces/Naver.md#SearchMusic) | **(Deprecated)** 인식한 음악에 대한 검색 결과를 CLOVA에 요청합니다. |
>>>>>>> 8d2b188e9 (Update description pattern for DeviceControl namespaces)
| PlaybackController | [`CustomCommandIssued`](/Develop/References/MessageInterfaces/PlaybackController.md#CustomCommandIssued)               | 사용자가 클라이언트 기기의 단축 버튼 중 하나를 눌렀을 때 이를 CLOVA에 보고합니다.  |
| PlaybackController | [`NextCommandIssued`](/Develop/References/MessageInterfaces/PlaybackController.md#NextCommandIssued)                   | 클라이언트에서 다음 버튼(Next)이 눌렸거나 그에 준하는 사용자의 UI 조작이 있었음을 CLOVA에 보고합니다. |
| PlaybackController | [`PauseCommandIssued`](/Develop/References/MessageInterfaces/PlaybackController.md#PauseCommandIssued)                 | 클라이언트에서 일시 정지 버튼(Pause)이 눌렸거나 그에 준하는 사용자의 UI 조작이 있었음을 CLOVA에 보고합니다.  |
| PlaybackController | [`PlayCommandIssued`](/Develop/References/MessageInterfaces/PlaybackController.md#PlayCommandIssued)                   | 클라이언트에서 재생 버튼(Play)이 눌렸거나 그에 준하는 사용자의 UI 조작이 있었음을 CLOVA에 보고합니다.  |
| PlaybackController | [`PreviousCommandIssued`](/Develop/References/MessageInterfaces/PlaybackController.md#PreviousCommandIssued)           | 클라이언트에서 이전 버튼(Previous)이 눌렸거나 그에 준하는 사용자의 UI 조작이 있었음을 CLOVA에 보고합니다. |
| PlaybackController | [`ResumeCommandIssued`](/Develop/References/MessageInterfaces/PlaybackController.md#ResumeCommandIssued)               | 클라이언트에서 재개 버튼(Resume)이 눌렸거나 그에 준하는 사용자의 UI 조작이 있었음을 CLOVA에 보고합니다.  |
| PlaybackController | [`SetRepeatModeCommandIssued`](/Develop/References/MessageInterfaces/PlaybackController.md#SetRepeatModeCommandIssued) | 클라이언트에서 반복 재생 버튼(Repeat)이 눌렸거나 그에 준하는 사용자의 UI 조작이 있었음을 CLOVA에 보고합니다.  |
| PlaybackController | [`StopCommandIssued`](/Develop/References/MessageInterfaces/PlaybackController.md#StopCommandIssued)                   | 클라이언트에서 중지 버튼(Stop)이 눌렸거나 그에 준하는 사용자의 UI 조작이 있었음을 CLOVA에 보고합니다.  |
| Settings          | [`Report`](/Develop/References/MessageInterfaces/Settings.md#Report)                                                    | 클라이언트의 현재 설정 정보를 CLOVA에 보고합니다.  |
| Settings          | [`RequestVersionSpec`](/Develop/References/MessageInterfaces/Settings.md#RequestVersionSpec)   | 추가 설정 정보를 CLOVA에 요청합니다. |
| SpeechRecognizer  | [`Recognize`](/Develop/References/MessageInterfaces/SpeechRecognizer.md#Recognize)  | 입력되는 사용자의 음성을 전달하여 음성 인식을 CLOVA에 요청합니다.                                          |
| SpeechSynthesizer | [`Request`](/Develop/References/MessageInterfaces/SpeechSynthesizer.md#Request)     | 특정 텍스트를 TTS로 생성하도록 CLOVA에 요청합니다.                                             |
| SpeechSynthesizer | [`SpeechFinished`](/Develop/References/MessageInterfaces/SpeechSynthesizer.md#SpeechFinished)   | TTS 재생을 완료했음을 CLOVA에 보고합니다.                                 |
| SpeechSynthesizer | [`SpeechStarted`](/Develop/References/MessageInterfaces/SpeechSynthesizer.md#SpeechStarted)     | TTS 재생을 시작했음을 CLOVA에 보고합니다.                                 |
| SpeechSynthesizer | [`SpeechStopped`](/Develop/References/MessageInterfaces/SpeechSynthesizer.md#SpeechStopped)     | TTS 재생을 중지했음을 CLOVA에 보고합니다.                                 |
| System          | [`RequestSynchronizeState`](/Develop/References/MessageInterfaces/System.md#RequestSynchronizeState) | 시스템 관련 정보를 동기화하기 위해 관련 정보를 CLOVA에 요청합니다. |
| TemplateRuntime    | [`LikeCommandIssued`](/Develop/References/MessageInterfaces/TemplateRuntime.md#LikeCommandIssued) | 클라이언트의 미디어 플레이어에서 특정 미디어 콘텐츠에 대해 좋아요 버튼(Like)이 눌렸거나 그에 준하는 사용자의 UI 조작이 있었음을 CLOVA에 보고합니다. |
| TemplateRuntime    | [`MoreCommandIssued`](/Develop/References/MessageInterfaces/TemplateRuntime.md#MoreCommandIssued) | 클라이언트의 미디어 플레이어에서 특정 미디어 콘텐츠에 대해 더보기 버튼(More)이 눌렸거나 그에 준하는 사용자의 UI 조작이 있었음을 CLOVA에 보고합니다. |
| TemplateRuntime    | [`RequestPlayerInfo`](/Develop/References/MessageInterfaces/TemplateRuntime.md#RequestPlayerInfo) | 클라이언트의 미디어 플레이어에 표시할 재생 목록, 앨범 이미지, 가사와 같은 재생 메타 정보를 CLOVA에 요청합니다. |
| TemplateRuntime    | [`SelectCommandIssued`](/Develop/References/MessageInterfaces/TemplateRuntime.md#SelectCommandIssued) | 사용자가 재생 목록 화면에서 하나의 아이템을 선택했음을 CLOVA에 보고합니다.  |
| TemplateRuntime    | [`SubscribeCommandIssued`](/Develop/References/MessageInterfaces/TemplateRuntime.md#SubscribeCommandIssued) | 클라이언트의 미디어 플레이어에서 특정 미디어 콘텐츠에 대해 구독 버튼(Subscribe)이 눌렸거나 그에 준하는 사용자의 UI 조작이 있었음을 CLOVA에 보고합니다.  |
| TemplateRuntime    | [`UnlikeCommandIssued`](/Develop/References/MessageInterfaces/TemplateRuntime.md#UnlikeCommandIssued) | 클라이언트의 미디어 플레이어에서 특정 미디어 콘텐츠에 대해 좋아요 취소(Unlike)이 눌렸거나 그에 준하는 사용자의 UI 조작이 있었음을 CLOVA에 보고합니다. |
| TemplateRuntime    | [`UnsubscribeCommandIssued`](/Develop/References/MessageInterfaces/TemplateRuntime.md#UnsubscribeCommandIssued) | 클라이언트의 미디어 플레이어에서 특정 미디어 콘텐츠에 대해 구독 취소(Unsubscribe)이 눌렸거나 그에 준하는 사용자의 UI 조작이 있었음을 CLOVA에 보고합니다. |
| TextRecognizer  | [`Recognize`](/Develop/References/MessageInterfaces/TextRecognizer.md#Recognize)      | 사용자 텍스트 입력을 전달하여 텍스트 인식을 CLOVA에 요청합니다.                           |
