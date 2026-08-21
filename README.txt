아콩이네 공동가계부🫛 version 2.1

원인 수정
- v1.3부터 실수로 삭제되어 있던 핵심 함수 복구
  · renderSettings()
  · populateSelects()
  · openTx()
  · editTx()
  · updateTxTypeUI()
  · openAccount()
  · editAccount()
- 이 누락 때문에 앱 실행 중 JavaScript가 중단되어 데이터 관리 버튼까지 실행되지 않던 문제 수정
- v1.1에서 정상 동작했던 CSV/JSON 데이터 관리 코드는 그대로 유지
- v1.3 이후 초기자산 기능 및 현재 UI 유지
- 모든 데이터 초기화 유지
