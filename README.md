# LanPebble-Releases
Official Windows installers, portable downloads, and release notes for LanPebble.

LanPebble은 같은 네트워크에서 PC·휴대폰 간 파일을 간편하게 공유하는 Windows 앱입니다.

## 다운로드 / Downloads

[GitHub Releases에서 다운로드](https://github.com/jonghyeok/LanPebble-Releases/releases)

| 파일 | 사용 방법 |
| --- | --- |
| `*-win-x64-Setup.exe` | 설치형. 시작 메뉴 등록, 바탕 화면 바로가기 선택 가능 |
| `*-win-x64.zip` | 포터블. 전체 압축 해제 후 `LanPebble.Desktop.exe` 실행 |
| `*.sha256` | 다운로드한 파일의 SHA-256 무결성 확인용 |

Windows 10 버전 2004 이상 / Windows 11, **x64** 환경을 지원합니다. 필요한 런타임이 포함되며 관리자 권한 없이 현재 사용자에게 설치합니다. 미리보기 버전은 `Pre-release`로 표시합니다. 현재 빌드는 코드 서명 전이므로 Windows가 게시자 경고를 표시할 수 있습니다.

## 사용하기

1. PC 앱에서 **파일 공유**를 열고 공유 폴더를 추가한 뒤 공유를 켭니다.
2. 다른 PC에서는 주변 기기를 선택하고 호스트의 PIN을 입력합니다.
3. 휴대폰·Mac은 호스트 앱의 **웹 접속**을 켜고 QR/URL로 접속한 뒤 PIN을 입력합니다.
4. 업로드는 호스트가 허용한 폴더에서 가능합니다.

웹 접속은 HTTP를 사용하므로 신뢰할 수 있는 로컬 네트워크에서 사용하세요. 일반 QR에는 PIN이 포함되지 않습니다.

## 업데이트와 제거

전송을 완료하고 LanPebble을 완전히 종료한 뒤 새 설치 파일을 실행하세요. 기존 설치 경로와 설정을 유지합니다. Windows 설정의 설치된 앱에서 제거할 수 있으며, 사용자 설정·기기 인증 정보와 실제 공유 파일은 유지합니다.

버전별 변경 사항은 `notes/`, 다운로드 URL과 해시는 `versions/`에 저장합니다. `latest-preview.json`과 `latest-stable.json`은 각 배포 채널의 최신 정보를 제공합니다. 해당 채널의 첫 배포 전에는 파일이 없을 수 있습니다.

English: Choose the setup EXE for per-user installation or extract the complete portable ZIP. Close LanPebble before upgrading. Required runtimes are included. Preview builds are unsigned; browser access uses HTTP on trusted local networks. Release assets include SHA-256 checksums.
