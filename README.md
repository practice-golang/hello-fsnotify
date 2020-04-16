# MariaDB(MySQL) 이벤트 발생시 변동 파일

* `table_name/*.frm` : 테이블 스키마. 테이블 구조 생성/변경시
* `table_name/*.ibd` : 테이블 데이터. 데이터 입력/변경시
* `innodb 파일` : ib_logfile0, ibdata1. 거의 모든 이벤트
