# Symptom image index

문제 인지 및 진단 단계에서 확보한 이미지의 이름과 설명을 정리한다.

| 기존 파일명 | 새 파일명 | 설명 |
| --- | --- | --- |
| `Eventlog.png` | `event-viewer-kernel-boot.png` | Event Viewer에서 Kernel-Boot 관련 이벤트와 세부 정보를 확인한 화면. 명확한 펌웨어 오류는 발견되지 않았다. |
| `M_bios.jpg` | `bios-chip-location.jpeg` | 기존 파일은 2바이트의 빈 파일이어서 제거하고, 그래픽카드를 제거한 메인보드와 BIOS 칩 영역 사진으로 교체했다. |
| `enum firmware.png` | `bcdedit-firmware-entries.png` | `bcdedit /enum firmware`로 Firmware Boot Manager, Windows Boot Manager와 UEFI USB 관련 항목을 확인한 화면. |
| `msinfo32.png` | `system-information-uefi-bios-f5a.png` | Windows가 UEFI 모드로 부팅 중이며 BIOS 버전이 F5a임을 확인한 시스템 정보 화면. |
| `shutdown.png` | `shutdown-firmware-error-203.png` | `shutdown /r /fw /t 0` 실행 시 “요청된 부트 옵션을 찾을 수 없습니다. (203)” 오류가 발생한 화면. |

문서에서 이미지를 사용할 때는 파일명만 나열하지 않고 이미지가 보여주는 사실과 해석의 한계를 함께 설명한다.
