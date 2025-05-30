---
title: "객체 생성"
images: []
menu:
docs:
weight: 30
---

테스트 데이터 생성은 테스트 작성 과정에서 가장 중요하고 시간이 많이 소요되는 부분 중 하나입니다. Fixture Monkey는 이 작업을 단순화하여 어떤 복잡도의 테스트 객체든 쉽고 유연하게 생성할 수 있는 방법을 제공합니다.

이 섹션에서는 다음 내용을 다룹니다:
- FixtureMonkey 인스턴스 생성 - 테스트 객체 생성을 위한 주요 진입점
- 간단하고 일반적인 사용 사례를 위한 기본 객체 생성 메서드
- 인터페이스 및 제네릭 타입과 같은 복잡한 타입 처리
- 객체가 생성되고 초기화되는 방식 커스터마이징

간단한 POJO가 필요하든 특정 제약 조건이 있는 복잡한 객체 그래프가 필요하든, Fixture Monkey의 직관적인 API는 테스트 데이터 생성을 간단하고 유지 관리하기 쉽게 만들어 줍니다.
