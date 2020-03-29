---
title: 연동 점수(Quality Scale)
description: "Details about the classification of integrations."
---

통합구성요소 품질 척도는 코드 품질과 사용자 경험에 따라 각 통합구성요소의 점수를 매깁니다. 연동이 모든 요구사항과 일치하면 해당 수준에 도달한 것으로 간주합니다.

개발자를  위한 [연동 품질 척도](https://developers.home-assistant.io/docs/en/integration_quality_scale_index.html)

## No score

이 연동은 최소한의 요구 사항을 충족시킵니다. 이정도가 홈어시스턴트에 도입될 때 대부분의 연동 수준입니다. 그것들이 나쁘거나 버그가 있다는 것을 의미하는 것은 아니며, `configuration.yaml` 파일의 항목으로 설정해야한다는 것을 의미합니다.

## Silver 🥈

이러한 연동은 상황이 잘못될 때 대처할 수 있습니다. 예외를 출력하지 않으며 재시도로 로그를 채울 수 없습니다. 또한 홈어시스턴트를 시작할 때 장치가 오프라인이거나 준비되지 않은 경우 표시됩니다.

## Gold 🥇

이는 열악한 조건에서도 견딜 수 있고 사용자 인터페이스를 통해 설정할 수있는 견고한 연동입니다.

## Platinum 🏆

최고 중의 최고. 연동은 완전히 비동기적이며 매우 빠르며 뛰어난 사용자 경험을 제공합니다.

## Internal 🏠

**Internal**로 표시된 모든 통합은 Home Assistant의 일부입니다.
