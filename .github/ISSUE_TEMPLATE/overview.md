---
name: Overview
about: Overview necessary features & functions
title: Expense Tracker Overview
assignees: solbijae, daeho220

---

# Features
### JaeYeon
* landing *GET*
    * welcome text
    * total amount
      * SUM(income + spending)
    * total income
      * SUM(income)
    * total spending
      * SUM(spending) * -1

* total amount(detail) *GET*
    * total list
    * income listing
    * spending listing

    * add transactions
      * click event(open add transactions(detail))

* add transactions(detail) *POST*
    * date
    * details(income/spending, content)
    * amount
    * add/close

### Daeho
* 수입 기록
* 지출 기록
* 등록시 현재 시간 날짜 기록해주는 것
* 입출금시 잔액 계산해주는 것
* 가계부니까 어떤 카테고리에 지출했는지 선택할 수 있게.
* 통계 눌렀을 때 카테고리별 지출 % 도넛 그래프
* 입출금 아이콘 정하기
* 날짜별로 그룹화해서 보여주는 기능
* 수입, 지출, 전체를 볼 수 있게 고르는것 (게시판의 카테고리를 쓰면 될려나?)
---
### Combined(Final)
* landing *GET*
    * welcome text
    * total amount
      * SUM(income + spending)
    * total income
      * SUM(income)
    * total spending
      * SUM(spending) * -1

* total amount(detail) *GET*
    * total list
      * listing
    * Sort by income
      * listing
      * donut graph
         * percentage()
    * Sort by spending
      * listing
      * donut graph
         * percentage()
    * Sort by date
      * listing 

    * add transactions(Event)
      * click event(open add transactions(detail))

* add transactions(detail) *POST*
    * date
      * Datepicker
    * details(income/spending, content)
    * amount
    * spending category
    * add/close

---
# Pages
* total view page
* insert page
* modify page
