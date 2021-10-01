# 지시 메시지 색인

| 네임스페이스          | 메시지 이름       | 설명                                             |
|--------------------|----------------|-------------------------------------------------|
| Alerts             | [`DeleteAlert`](/Develop/References/MessageInterfaces/Alerts.md#DeleteAlert)             | 클라이언트가 특정 알람을 삭제하도록 지시합니다. |
| Alerts             | [`SetAlert`](/Develop/References/MessageInterfaces/Alerts.md#SetAlert)                   | 클라이언트가 알람을 새로 추가하거나 특정 알람을 수정하도록 지시합니다. |
| Alerts             | [`StopAlert`](/Develop/References/MessageInterfaces/Alerts.md#StopAlert)                 | 클라이언트가 특정 알람을 중지하도록 지시합니다.  |
| Alerts             | [`SynchronizeAlert`](/Develop/References/MessageInterfaces/Alerts.md#SynchronizeAlert)   | 클라이언트가 이 메시지에 포함된 사용자의 알람 데이터를 동기화하도록 지시합니다.  |
| AudioPlayer        | [`ClearQueue`](/Develop/References/MessageInterfaces/AudioPlayer.md#ClearQueue)          | 클라이언트가 오디오 스트림 재생 대기열(queue)을 초기화하도록 지시합니다.                              |
| AudioPlayer        | [`ExpectReportPlaybackState`](/Develop/References/MessageInterfaces/AudioPlayer.md#ExpectReportPlaybackState) | 클라이언트가 현재 재생 상태를 보고하도록 지시합니다. |
| AudioPlayer        | [`Play`](/Develop/References/MessageInterfaces/AudioPlayer.md#Play)                      | 클라이언트가 특정 오디오 스트림을 재생하거나 재생 대기열에 추가하도록 지시합니다.                          |
| AudioPlayer        | [`StreamDeliver`](/Develop/References/MessageInterfaces/AudioPlayer.md#StreamDeliver)    | 클라이언트가 오디오 스트림 정보를 교체하여 재생하도록 지시합니다. |
| Clova              | [`ExpectLogin`](/Develop/References/MessageInterfaces/Clova.md#ExpectLogin)              | 클라이언트가 사용자로부터 {{ book.ServiceEnv.OrientedService }} 계정 인증(login)을 받도록 지시합니다.          |
| Clova              | [`FinishExtension`](/Develop/References/MessageInterfaces/Clova.md#FinishExtension)      | 클라이언트가 특정 Extension을 종료하도록 지시합니다.                                             |
| Clova              | [`HandleDelegatedEvent`](/Develop/References/MessageInterfaces/Clova.md#HandleDelegatedEvent) | 클라이언트가 CLOVA 앱으로부터 [위임된 사용자의 요청을 처리](/Develop/Guides/Handle_Delegation.md)하도록 지시합니다.   |
| Clova              | [`Hello`](/Develop/References/MessageInterfaces/Clova.md#Hello)                          | [Downchannel 연결 설정](/Develop/Guides/Interact_with_CIC.md#CreateConnection)이 완료되었음을 알립니다.                                       |
| Clova              | [`Help`](/Develop/References/MessageInterfaces/Clova.md#Help)                            | 클라이언트가 미리 준비해 둔 도움말 정보를 제공하도록 지시합니다.                                       |
| Clova              | [`LaunchURI`](/Develop/References/MessageInterfaces/Clova.md#LaunchURI)                  | 클라이언트가 URI로 표현되는 사이트 혹은 앱을 열거나 실행하도록 지시합니다.       |
| Clova              | [`RenderTemplate`](/Develop/References/MessageInterfaces/Clova.md#RenderTemplate)        | 클라이언트가 [content template](/Develop/References/Content_Templates.md)을 표시하도록 지시합니다.                                                     |
| Clova              | [`RenderText`](/Develop/References/MessageInterfaces/Clova.md#RenderText)                | 클라이언트가 메시지에 포함된 텍스트를 표시하도록 지시합니다.                                                     |
| Clova              | [`StartExtension`](/Develop/References/MessageInterfaces/Clova.md#StartExtension)        | 클라이언트가 특정 Extension을 시작하도록 지시합니다.                                             |
<<<<<<< HEAD
| DeviceControl      | [`BtConnect`](/Develop/References/MessageInterfaces/DeviceControl.md#BtConnect)          | CLOVA가 특정 블루투스 기기와 연결을 설정하도록 클라이언트에 지시합니다.                                       |
| DeviceControl      | [`BtConnectByPINCode`](/Develop/References/MessageInterfaces/DeviceControl.md#BtConnectByPINCode) | CLOVA가 PIN 코드를 요청한 블루투스 기기와 연결하도록 클라이언트에 지시합니다.                      |
| DeviceControl      | [`BtDelete`](/Develop/References/MessageInterfaces/DeviceControl.md#BtDelete)            | CLOVA가 블루투스 페어링 목록에서 특정 기기를 제거하도록 클라이언트에 지시합니다.                        |
| DeviceControl      | [`BtDisconnect`](/Develop/References/MessageInterfaces/DeviceControl.md#BtDisconnect)    | CLOVA가 특정 블루투스 기기와 연결을 해제하도록 클라이언트에 지시합니다.                                       |
| DeviceControl      | [`BtPlay`](/Develop/References/MessageInterfaces/DeviceControl.md#BtPlay)                | CLOVA가 연결된 블루투스 기기를 통해 음악을 재생하도록 클라이언트에 지시합니다.                          |
| DeviceControl      | [`BtRescan`](/Develop/References/MessageInterfaces/DeviceControl.md#BtRescan)            | CLOVA가 블루투스 기기를 재탐지(rescan)하도록 클라이언트에 지시합니다.                               |
| DeviceControl      | [`BtStartPairing`](/Develop/References/MessageInterfaces/DeviceControl.md#BtStartPairing) | CLOVA가 블루투스 페어링을 시작하도록 클라이언트에 지시합니다.                                              |
| DeviceControl      | [`BtStopPairing`](/Develop/References/MessageInterfaces/DeviceControl.md#BtStopPairing)   | CLOVA가 블루투스 페어링을 중지하도록 클라이언트에 지시합니다.                                              |
| DeviceControl      | [`Decrease`](/Develop/References/MessageInterfaces/DeviceControl.md#Decrease)             | CLOVA가 스피커 볼륨 또는 화면 밝기를 기본 단위만큼 줄이도록 클라이언트에 지시합니다.                            |
| DeviceControl      | [`ExpectReportState`](/Develop/References/MessageInterfaces/DeviceControl.md#ExpectReportState) | CLOVA가 기기의 현재 상태를 CIC로 보고하도록 클라이언트에 지시합니다.                                  |
| DeviceControl      | [`Increase`](/Develop/References/MessageInterfaces/DeviceControl.md#Increase)             | CLOVA가 스피커 볼륨 또는 화면 밝기를 기본 단위만큼 높이도록 클라이언트에 지시합니다.                            |
| DeviceControl      | [`LaunchApp`](/Develop/References/MessageInterfaces/DeviceControl.md#LaunchApp)           | **(Deprecated)** CLOVA가 특정 앱을 실행하도록 클라이언트에 지시합니다.                                                    |
| DeviceControl      | [`Open`](/Develop/References/MessageInterfaces/DeviceControl.md#Open)                     | CLOVA가 특정 화면을 표시하도록 클라이언트에 지시합니다.  |
| DeviceControl      | [`OpenScreen`](/Develop/References/MessageInterfaces/DeviceControl.md#OpenScreen)         | **(Deprecated)** CLOVA가 설정 화면을 열도록 클라이언트에 지시합니다.                                                     |
| DeviceControl      | [`RenderDeviceList`](/Develop/References/MessageInterfaces/DeviceControl.md#RenderDeviceList)       | CLOVA가 사용자 계정에 등록된 클라이언트 기기 목록을 표시하도록 클라이언트에 지시합니다.  |
| DeviceControl      | [`SetValue`](/Develop/References/MessageInterfaces/DeviceControl.md#SetValue)            | CLOVA가 스피커 볼륨 또는 화면 밝기를 지정한 값으로 설정하도록 클라이언트에 지시합니다.                           |
| DeviceControl      | [`SynchronizeState`](/Develop/References/MessageInterfaces/DeviceControl.md#SynchronizeState) | CLOVA가 사용자 계정에 등록된 또 다른 클라이언트 기기의 상태를 업데이트하도록 클라이언트에 지시합니다.           |
| DeviceControl      | [`TurnOff`](/Develop/References/MessageInterfaces/DeviceControl.md#TurnOff)               | CLOVA가 지정한 기능이나 모드를 끄거나 비활성화하도록 클라이언트에 지시합니다.                                  |
| DeviceControl      | [`TurnOn`](/Develop/References/MessageInterfaces/DeviceControl.md#TurnOn)                 | CLOVA가 지정한 기능을 켜거나 활성화하도록 클라이언트에 지시합니다.                                          |
=======
| ClovaInternal      | [`Reboot`](/Develop/References/MessageInterfaces/ClovaInternal.md#Reboot)                | 클라이언트가 기기를 재시작하도록 지시합니다.                                             |
| ClovaInternal      | [`RestartProcess`](/Develop/References/MessageInterfaces/ClovaInternal.md#RestartProcess) | 클라이언트가 실행 중인 프로세스를 재시작하도록 지시합니다.                                             |
| ClovaInternal      | [`SetEventBurstPrevention`](/Develop/References/MessageInterfaces/ClovaInternal.md#SetEventBurstPrevention) | CLOVA가 특정 이벤트를 서버로 전송하지 않도록 클라이언트에 지시합니다.                                             |
| DeviceControl      | [`BtConnect`](/Develop/References/MessageInterfaces/DeviceControl.md#BtConnect)          | 클라이언트가 블루투스 기기와 연결을 설정하도록 지시합니다.                                       |
| DeviceControl      | [`BtConnectByPINCode`](/Develop/References/MessageInterfaces/DeviceControl.md#BtConnectByPINCode) | 클라이언트가 PIN 코드를 요청한 블루투스 기기와 연결하도록 지시합니다.                      |
| DeviceControl      | [`BtDelete`](/Develop/References/MessageInterfaces/DeviceControl.md#BtDelete)            | 클라이언트가 블루투스 페어링 목록에서 특정 기기를 제거하도록 지시합니다.                        |
| DeviceControl      | [`BtDisconnect`](/Develop/References/MessageInterfaces/DeviceControl.md#BtDisconnect)    | 클라이언트가 연결된 블루투스 기기와 연결을 끊도록 지시합니다.                                       |
| DeviceControl      | [`BtPlay`](/Develop/References/MessageInterfaces/DeviceControl.md#BtPlay)                | 클라이언트가 연결된 블루투스 기기를 통해 오디오 콘텐츠를 재생하도록 지시합니다.                  |
| DeviceControl      | [`BtRescan`](/Develop/References/MessageInterfaces/DeviceControl.md#BtRescan)            | 클라이언트가 블루투스 기기를 재탐지(rescan)하도록 지시합니다.                               |
| DeviceControl      | [`BtStartPairing`](/Develop/References/MessageInterfaces/DeviceControl.md#BtStartPairing) | 클라이언트가 블루투스 페어링을 시작하도록 지시합니다.                                              |
| DeviceControl      | [`BtStopPairing`](/Develop/References/MessageInterfaces/DeviceControl.md#BtStopPairing)   | 클라이언트가 블루투스 페어링을 중지하도록 지시합니다.                                              |
| DeviceControl      | [`Decrease`](/Develop/References/MessageInterfaces/DeviceControl.md#Decrease)             | 클라이언트가 스피커 볼륨 또는 화면 밝기를 기본 단위만큼 줄이도록 지시하거나, TV 채널을 이전 채널로 변경하도록 지시합니다.                            |
| DeviceControl      | [`ExpectReportState`](/Develop/References/MessageInterfaces/DeviceControl.md#ExpectReportState) | 기기의 현재 상태를 CLOVA에 보고합니다.                                  |
| DeviceControl      | [`Increase`](/Develop/References/MessageInterfaces/DeviceControl.md#Increase)             | 클라이언트가 스피커 볼륨 또는 화면 밝기를 기본 단위만큼 높이도록 지시하거나, TV 채널을 다음 채널로 변경하도록 지시합니다.                            |
| DeviceControl      | [`LaunchApp`](/Develop/References/MessageInterfaces/DeviceControl.md#LaunchApp)           | **(Deprecated)** 클라이언트가 특정 앱을 실행하도록 지시합니다.                                                    |
| DeviceControl      | [`Open`](/Develop/References/MessageInterfaces/DeviceControl.md#Open)                     | 클라이언트가 특정 화면을 표시하도록 지시합니다.  |
| DeviceControl      | [`OpenScreen`](/Develop/References/MessageInterfaces/DeviceControl.md#OpenScreen)         | **(Deprecated)** 클라이언트가 설정 화면을 열도록 지시합니다.                                                     |
| DeviceControl      | [`RenderDeviceList`](/Develop/References/MessageInterfaces/DeviceControl.md#RenderDeviceList)       | 클라이언트가 사용자 계정에 등록된 클라이언트 기기 목록을 표시하도록 지시합니다.  |
| DeviceControl      | [`RenderSmartCommandList`](/Develop/References/MessageInterfaces/DeviceControl.md#RenderSmartCommandList) | 클라이언트가 스마트 버튼에 설정할 수 있는 명령 목록을 표시하도록 지시합니다.  |
| DeviceControl      | [`SetValue`](/Develop/References/MessageInterfaces/DeviceControl.md#SetValue)            | 클라이언트가 스피커 볼륨 또는 화면 밝기를 지정한 값으로 설정하거나 특정 TV 채널로 변경하도록 지시합니다.                           |
| DeviceControl      | [`ShowClock`](/Develop/References/MessageInterfaces/DeviceControl.md#ShowClock)                 | 클라이언트가 시간, 타이머, 또는 스톱워치를 표시하도록 지시합니다.                      |
| DeviceControl      | [`SynchronizeState`](/Develop/References/MessageInterfaces/DeviceControl.md#SynchronizeState) | 클라이언트가 사용자 계정에 등록된 또 다른 클라이언트 기기의 상태 정보를 업데이트하도록 지시합니다.            |
| DeviceControl      | [`TurnOff`](/Develop/References/MessageInterfaces/DeviceControl.md#TurnOff)               | 클라이언트가 지정한 기능이나 모드를 끄거나 비활성화하도록 지시합니다.                                  |
| DeviceControl      | [`TurnOn`](/Develop/References/MessageInterfaces/DeviceControl.md#TurnOn)                 | 클라이언트가 지정한 기능이나 모드를 켜거나 활성화하도록 지시합니다.                                          |
| E2ESecuredDataExchange | [`End`](/Develop/References/MessageInterfaces/E2ESecuredDataExchange.md#End)                           | 클라이언트가 암호화 통신 세션을 종료하도록 지시합니다. |
| E2ESecuredDataExchange | [`ExpectReportData`](/Develop/References/MessageInterfaces/E2ESecuredDataExchange.md#ExpectReportData) | 클라이언트가 요청된 데이터를 대칭키로 암호화하여 공유하도록 지시합니다. |
| E2ESecuredDataExchange | [`HandleData`](/Develop/References/MessageInterfaces/E2ESecuredDataExchange.md#HandleData)             | 클라이언트가 이 메시지가 포함하고 있는 암호화 데이터를 처리하도록 지시합니다. |
| E2ESecuredDataExchange | [`Ready`](/Develop/References/MessageInterfaces/E2ESecuredDataExchange.md#Ready)                       | 클라이언트가 암호화 통신을 준비하도록 지시합니다. |
| E2ESecuredDataExchange | [`ReturnResult`](/Develop/References/MessageInterfaces/E2ESecuredDataExchange.md#ReturnResult)         | 클라이언트가 암호화 통신과 관련된 작업의 수행 결과를 확인한 후 그에 대응되는 작업을 처리하도록 지시합니다. |
| LineApp            | [`LaunchURI`](/Develop/References/MessageInterfaces/LineApp.md#LaunchURI)                 | 클라이언트가 URI로 표현되는 사이트 혹은 앱을 LINE 앱에서 열거나 실행하도록 지시합니다.                   |
| LineApp            | [`MakeCall`](/Develop/References/MessageInterfaces/LineApp.md#MakeCall)                 | 클라이언트가 LINE 앱의 음성/화상 통화 연결을 시도하도록 지시합니다.   |
| LineApp            | [`RenderHTML`](/Develop/References/MessageInterfaces/LineApp.md#RenderHTML)               | 클라이언트가 HTML로 표현된 웹 기반의 콘텐츠를 표시하도록 지시합니다.                   |
| LineApp            | [`RenderMessageConfirmation`](/Develop/References/MessageInterfaces/LineApp.md#RenderMessageConfirmation) | 클라이언트가 LINE 메시지 최종 확인 화면을 표시하도록 지시합니다. |
| LineApp            | [`RenderMessageInput`](/Develop/References/MessageInterfaces/LineApp.md#RenderMessageInput)   | 사용자가 LINE 메시지를 전송할 수 있게 만들기 위해 클라이언트가 메시지 입력 UI를 표시하도록 지시합니다. |
| LineApp            | [`RenderSentMessageResult`](/Develop/References/MessageInterfaces/LineApp.md#RenderSentMessageResult) | 클라이언트가 LINE 메시지 전송 결과 화면을 표시하도록 지시합니다. |
| LineApp            | [`RenderTTSPlayback`](/Develop/References/MessageInterfaces/LineApp.md#RenderTTSPlayback)       | 클라이언트가 TTS 재생 동안 오디오 재생 상태를 표시하도록 지시합니다.   |
| LineApp            | [`RenderVoiceAssistantGuideText`](/Develop/References/MessageInterfaces/LineApp.md#RenderVoiceAssistantGuideText) | 클라이언트가 사용자 음성 입력과 관련된 도움 메시지를 LINE 앱의 Voice Assistant 설명 영역에 표시하도록 지시합니다.  |
| Music             | [`RenderPanel`](/Develop/References/MessageInterfaces/Music.md#RenderPanel) | 클라이언트가 뮤직 패널을 표시하도록 지시합니다. |
| MusicRecognizer    | [`ExpectMusic`](/Develop/References/MessageInterfaces/MusicRecognizer.md#ExpectMusic)     | 클라이언트가 마이크를 활성화하여 음악 입력을 받도록 지시합니다.            |
| MusicRecognizer    | [`RenderFailure`](/Develop/References/MessageInterfaces/MusicRecognizer.md#RenderFailure) | CLOVA가 [`MusicRecognizer.Recognize`](/Develop/References/MessageInterfaces/MusicRecognizer.md#Recognize) 이벤트 메시지에 의해 입력된 오디오 데이터를 인식하는데 실패했을 때 이를 클라이언트에 알립니다.      |
| MusicRecognizer    | [`RenderPlaylists`](/Develop/References/MessageInterfaces/MusicRecognizer.md#RenderPlaylists) | 클라이언트가 음악 재생 목록을 표시하도록 지시합니다. |
| MusicRecognizer    | [`StopCapture`](/Develop/References/MessageInterfaces/MusicRecognizer.md#StopCapture)      | 클라이언트가 음악을 그만 입력받도록 지시합니다. |
| Naver              | [`AddSearchHistory`](/Develop/References/MessageInterfaces/Naver.md#AddSearchHistory) | 클라이언트가 CLOVA에서 제공하는 항목을 검색 이력에 추가하도록 지시합니다. |
| Naver              | [`ExpectRecognizeMusic`](/Develop/References/MessageInterfaces/Naver.md#ExpectRecognizeMusic) | **(Deprecated)** 클라이언트가 음악 인식을 시작하도록 지시합니다. |
| Naver              | [`LaunchURI`](/Develop/References/MessageInterfaces/Naver.md#LaunchURI) | 클라이언트가 URI로 표현되는 사이트 혹은 앱을 NAVER 앱에서 열거나 실행하도록 지시합니다. |
| Naver              | [`Log`](/Develop/References/MessageInterfaces/Naver.md#Log) | 클라이언트가 이 메시지에 포함된 정보를 이용하여 LCS 이력을 남기도록 지시합니다. |
| Naver              | [`MoveCardIndex`](/Develop/References/MessageInterfaces/Naver.md#MoveCardIndex) | 클라이언트가 기존 화면에 표시되어 있는 카드 중에서 특정 카드로 이동하도록 지시합니다. |
| Naver              | [`RenderGreenDotSuggestion`](/Develop/References/MessageInterfaces/Naver.md#RenderGreenDotSuggestion) | 클라이언트가 Green Dot 피드 화면을 표현하도록 지시합니다. |
| Naver              | [`RenderHTML`](/Develop/References/MessageInterfaces/Naver.md#RenderHTML) | 클라이언트가 HTML로 표현한 내용을 화면에 표시하도록 지시합니다. |
>>>>>>> 8d2b188e9 (Update description pattern for DeviceControl namespaces)
| Notifier           | [`ClearIndicator`](/Develop/References/MessageInterfaces/Notifier.md#ClearIndicator)      | 클라이언트가 알림을 나타내는 표시를 모두 끄도록 지시합니다.                                         |
| Notifier           | [`Notify`](/Develop/References/MessageInterfaces/Notifier.md#Notify)                      | 클라이언트가 알림 내용을 사용자에게 전달하도록 지시합니다.                                          |
| Notifier           | [`SetIndicator`](/Develop/References/MessageInterfaces/Notifier.md#SetIndicator)          | 클라이언트가 사용자가 읽지 않은 알림이 있음을 표시하도록 지시합니다.                                  |
| PlaybackController | [`ExpectNextCommand`](/Develop/References/MessageInterfaces/PlaybackController.md#ExpectNextCommand)         | 클라이언트가 다음 버튼(Next)을 누른 것처럼 동작하도록 지시합니다.  |
| PlaybackController | [`ExpectPauseCommand`](/Develop/References/MessageInterfaces/PlaybackController.md#ExpectPauseCommand)       | 클라이언트가 일시 정지 버튼(Pause)을 누른 것처럼 동작하도록 지시합니다.  |
| PlaybackController | [`ExpectPlayCommand`](/Develop/References/MessageInterfaces/PlaybackController.md#ExpectPlayCommand)         | 클라이언트가 재생 버튼(Play)을 누른 것처럼 동작하도록 지시합니다.  |
| PlaybackController | [`ExpectPreviousCommand`](/Develop/References/MessageInterfaces/PlaybackController.md#ExpectPreviousCommand) | 클라이언트가 이전 버튼(Previous)을 누른 것처럼 동작하도록 지시합니다.  |
| PlaybackController | [`ExpectResumeCommand`](/Develop/References/MessageInterfaces/PlaybackController.md#ExpectResumeCommand)     | 클라이언트가 재개 버튼(Resume)을 누른 것처럼 동작하도록 지시합니다.  |
| PlaybackController | [`ExpectStopCommand`](/Develop/References/MessageInterfaces/PlaybackController.md#ExpectStopCommand)         | 클라이언트가 중지 버튼(Stop)을 누른 것처럼 동작하도록 지시합니다.  |
| PlaybackController | [`Mute`](/Develop/References/MessageInterfaces/PlaybackController.md#Mute)               | 클라이언트가 오디오 플레이어의 볼륨을 음소거하도록 지시합니다.                                                |
| PlaybackController | [`Next`](/Develop/References/MessageInterfaces/PlaybackController.md#Next)               | 클라이언트가 재생 대기열에 있는 다음 오디오 스트림을 재생하도록 지시합니다.                               |
| PlaybackController | [`Pause`](/Develop/References/MessageInterfaces/PlaybackController.md#Pause)             | 클라이언트가 재생 중인 오디오 스트림을 일시 정지하도록 지시합니다.                                    |
| PlaybackController | [`Previous`](/Develop/References/MessageInterfaces/PlaybackController.md#Previous)       | 클라이언트가 재생 대기열에 있는 이전 오디오 스트림을 재생하도록 지시합니다.                              |
| PlaybackController | [`Replay`](/Develop/References/MessageInterfaces/PlaybackController.md#Replay)           | 클라이언트가 오디오 스트림을 처음부터 다시 재생하도록 지시합니다.                                     |
| PlaybackController | [`Resume`](/Develop/References/MessageInterfaces/PlaybackController.md#Resume)           | 클라이언트가 오디오 스트림 재생을 재개하도록 지시합니다.                                            |
| PlaybackController | [`SetRepeatMode`](/Develop/References/MessageInterfaces/PlaybackController.md#SetRepeatMode) | 클라이언트가 지정된 반복 모드로 재생 상태를 변경하도록  지시합니다.                                |
| PlaybackController | [`Stop`](/Develop/References/MessageInterfaces/PlaybackController.md#Stop)               | 클라이언트가 오디오 스트림 재생을 중지하도록 지시합니다.                                            |
| PlaybackController | [`TurnOffRepeatMode`](/Develop/References/MessageInterfaces/PlaybackController.md#TurnOffRepeatMode) | **(Deprecated)** 클라이언트가 한 곡 반복 재생 모드를 해제하도록 지시합니다.                |
| PlaybackController | [`TurnOnRepeatMode`](/Develop/References/MessageInterfaces/PlaybackController.md#TurnOnRepeatMode) | **(Deprecated)** 클라이언트가 한 곡 반복 재생 모드를 설정하도록 지시합니다.                  |
| PlaybackController | [`Unmute`](/Develop/References/MessageInterfaces/PlaybackController.md#Unmute)           | 클라이언트가 오디오 플레이어 볼륨의 음소거를 해제하도록 지시합니다.                                           |
| PlaybackController | [`VolumeDown`](/Develop/References/MessageInterfaces/PlaybackController.md#VolumeDown)   | **(Deprecated)** 클라이언트가 오디오 플레이어 볼륨을 낮추도록 지시합니다.                                                   |
| PlaybackController | [`VolumeUp`](/Develop/References/MessageInterfaces/PlaybackController.md#VolumeUp)       | **(Deprecated)** 클라이언트가 오디오 플레이어 볼륨을 높이도록 지시합니다.                                                   |
| Settings           | [`ExpectReport`](/Develop/References/MessageInterfaces/Settings.md#ExpectReport)                                                 | 클라이언트가 현재 설정 정보를 보고하도록 지시합니다. |
| Settings           | [`Update`](/Develop/References/MessageInterfaces/Settings.md#Update)                                                             | 클라이언트가 `payload`에 포함된 내용을 설정에 반영하도록  지시합니다.  |
| Settings           | [`UpdateVersionSpec`](/Develop/References/MessageInterfaces/Settings.md#UpdateVersionSpec)  | 클라이언트가 `payload`에 포함된 설정 항목을 설정 메뉴에 반영하도록 지시합니다. |
| SpeechRecognizer   | [`ExpectSpeech`](/Develop/References/MessageInterfaces/SpeechRecognizer.md#ExpectSpeech) | 클라이언트가 마이크를 활성화하여 사용자의 음성 입력을 받도록 클라이언트에 지시합니다.                                         |
| SpeechRecognizer   | [`KeepRecording`](/Develop/References/MessageInterfaces/SpeechRecognizer.md#KeepRecording) | 클라이언트가 사용자의 음성 입력을 계속 받도록 클라이언트에 지시합니다.                                                |
| SpeechRecognizer   | [`ShowRecognizedText`](/Develop/References/MessageInterfaces/SpeechRecognizer.md#ShowRecognizedText) | 클라이언트가 텍스트로 인식된 사용자 음성을 실시간으로 표시하도록 지시합니다.        |
| SpeechRecognizer   | [`StopCapture`](/Develop/References/MessageInterfaces/SpeechRecognizer.md#StopCapture)   | 클라이언트가 사용자의 음성 입력 수신을 중지하도록 지시합니다.                                            |
| SpeechSynthesizer  | [`Speak`](/Develop/References/MessageInterfaces/SpeechSynthesizer.md#Speak)                 | 클라이언트가 합성된 TTS를 스피커로 출력하도록 지시합니다.                                |
| System             | [`SynchronizeState`](/Develop/References/MessageInterfaces/System.md#SynchronizeState) | 클라이언트가 이 메시지에 포함된 데이터를 동기화하도록 지시합니다.                                   |
| TemplateRuntime    | [`ExpectRequestPlayerInfo`](/Develop/References/MessageInterfaces/TemplateRuntime.md#ExpectRequestPlayerInfo)  | 클라이언트가 재생 목록, 앨범 이미지, 가사와 같은 오디오 재생 관련 메타 정보를 요청하도록 지시합니다.  |
| TemplateRuntime    | [`RenderPlayerInfo`](/Develop/References/MessageInterfaces/TemplateRuntime.md#RenderPlayerInfo)                | 클라이언트가 미디어 플레이어에 표시할 재생 목록, 앨범 이미지, 가사와 같은 재생 메타 정보를 표시하도록 지시합니다. |
| TemplateRuntime    | [`RenderPlaylist`](/Develop/References/MessageInterfaces/TemplateRuntime.md#RenderPlaylist)                | 클라이언트가 재생 목록 화면을 표시하도록 지시합니다. |
| TemplateRuntime    | [`UpdateLike`](/Develop/References/MessageInterfaces/TemplateRuntime.md#UpdateLike)                            | 클라이언트가 미디어 플레이어에서 특정 미디어 콘텐츠에 대한 사용자의 좋아요(like) 표시 상태를 지정된 값으로 업데이트하도록 지시합니다.  |
| TemplateRuntime    | [`UpdateSubscribe`](/Develop/References/MessageInterfaces/TemplateRuntime.md#UpdateSubscribe)                  | 클라이언트가 미디어 플레이어에서 특정 미디어 콘텐츠에 대한 사용자의 구독(subscribe) 여부 표시 상태를 지정된 값으로 업데이트하도록 지시합니다.   |
