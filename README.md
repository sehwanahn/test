---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: false
---

# 카카오비즈니스 가이드

**RCS Biz Center**를 똑똑하게 이용하는 법    ㅡㅓㅓㅓㅏ\
이용가이드로 확인해 보세요!

<figure><img src=".gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

카카오에서 처음 비즈니스를 시작하더라도 쉽게 따라할 수 있고, 궁금한 점이 있을 때는 빠르게 해결할 수 있도록 유용한 가이드와 자주 묻는 질문을 모아두었습니다.



## **RCS Biz Center 어디까지 활용할 수 있`나요`**

<table data-header-hidden><thead><tr><th></th><th data-type="content-ref"></th></tr></thead><tbody><tr><td>🔍 카카오비즈니스 시작하기</td><td></td></tr><tr><td><strong>STEP 1 카카오 계정을 만드는 방법을 알아보세요</strong> <a href="https://kakaobusiness.gitbook.io/main/undefined/untitled">자세히보기 ＞</a></td><td><a href="rcs/">rcs</a></td></tr><tr><td><strong>STEP 2 카카오톡 비즈니스 채널을 만들어보세요</strong> <a href="https://kakaobusiness.gitbook.io/main/channel/start">자세히보기 ＞</a></td><td></td></tr><tr><td><strong>STEP 3 광고를 연결하여 더 많은 사용자에게 도달해보세요</strong> <a href="https://kakaobusiness.gitbook.io/main/ad/moment/start">자세히보기 ＞</a></td><td></td></tr></tbody></table>

<figure><img src=".gitbook/assets/image.avif" alt=""><figcaption></figcaption></figure>

카카오톡 채널은 고객과 커뮤니케이션을 하는 카카오톡 내비즈니스 홈입니다. \
[카카오톡 채널 관리자센터](https://center-pf.kakao.com/profiles)에서 손쉽게 당신의 비즈니스 홈을 만들고, 활용할 수 있습니다.

## Create a new user

<mark style="color:green;">`POST`</mark> `/users`

\<Description of the endpoint>

**Headers**

| Name          | Value              |
| ------------- | ------------------ |
| Content-Type  | `application/json` |
| Authorization | `Bearer <token>`   |

**Body**

| Name   | Type   | Description      |
| ------ | ------ | ---------------- |
| `name` | string | Name of the user |
| `age`  | number | Age of the user  |

**Response**

{% tabs %}
{% tab title="200" %}
```json
{
  "id": 1,
  "name": "John",
  "age": 30
}
```
{% endtab %}

{% tab title="400" %}
```json
{
  "error": "Invalid request"
}
```
{% endtab %}
{% endtabs %}

{% hint style="danger" %}
dsfasdafsdf
{% endhint %}

<details>

<summary><a data-mention href="rcs/">rcs</a></summary>

/

</details>
