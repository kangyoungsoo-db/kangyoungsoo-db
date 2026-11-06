# 강영수 Kang Young Soo

신입 DBA를 준비하고 있다. Oracle과 PostgreSQL을 직접 설치하고, 백업하고, 일부러 망가뜨린 뒤 되살리며 운영을 익히고 있다.

## 개인 실습 저장소

| 저장소 | 내용 |
|---|---|
| [3tier-postgresql-ha](https://github.com/kangyoungsoo-db/3tier-postgresql-ha) | Rocky Linux 10 위 Apache, Tomcat, PostgreSQL 16 3계층 폐쇄망 구축. Pacemaker 이중화, 스트리밍 복제, 수동 페일오버, PITR, 논리 백업 자동화, PAF DB 자동 전환을 직접 검증. 교육과정 중 따로 진행한 개인 프로젝트 |
| [postgresql-patroni-ha](https://github.com/kangyoungsoo-db/postgresql-patroni-ha) | PostgreSQL 17 스트리밍 복제 위에 Patroni, etcd, PgBouncer, pgBackRest, MinIO, Prometheus, Grafana를 올린 고가용성 실습 환경. 구축 코드와 검증 결과를 올렸고 수동 실습 기록은 진행 중 |
| [oracle19c-install](https://github.com/kangyoungsoo-db/oracle19c-install) | Oracle 19c 수동 구축 30단계와 Ansible 자동화 비교. 재부팅 후 점검 17항목 통과, 같은 구성을 Ansible로 29분 만에 재현, SELinux 실행 차단을 라벨 복원으로 해결 |
| [oracle19c-backup-recovery](https://github.com/kangyoungsoo-db/oracle19c-backup-recovery) | RMAN 증분 백업(주 1회 Level 0, 매일 Level 1), 압축, 7일 보관으로 4.7GB를 660MB로 백업. 장애 5가지 복구, RTO 1~6분, 리두 로그 유무로 손실 0건과 1건이 갈림 |
| [linux-ops-scripts](https://github.com/kangyoungsoo-db/linux-ops-scripts) | 서버 점검, 디스크 준비, 기본 설정, RMAN 백업 셸 스크립트 |

## 팀 프로젝트

| 프로젝트 | 링크 |
|---|---|
| ChargeOps | [github.com/raspberry-2jo/chargeops](https://github.com/raspberry-2jo/chargeops) |

## 다루는 것

| 분야 | 도구 |
|---|---|
| DB | Oracle 19c (RMAN, Flashback), PostgreSQL 16, 17 (스트리밍 복제, PITR, Patroni, PAF, pgBackRest, PgBouncer) |
| OS | Oracle Linux 8, Rocky Linux 10 (LVM, systemd, SELinux, firewalld, nmcli bonding) |
| 자동화, HA | Ansible, Vagrant, Bash, PowerShell, Pacemaker, Corosync |
| 모니터링 | Prometheus, Grafana |
