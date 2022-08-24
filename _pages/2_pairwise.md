---
layout: questions
title: "溯溪問卷-😌滿意度調查"
nextButton: 帶我到下一頁~
pageNo: 2
---

{% likert name:"agenda_morning" %}
# 早上的活動👣
[](str_agree) 很滿意🤩
[](agree) 還算滿意😊
[](neutral) 沒想法~✔️
[](disagree) 有點不滿意🤔
[](str_disagree) 非常不滿意😠
{% endlikert %}

{% likert name:"agenda_afternoon" %}
# 下午的活動👥
[](str_agree) 很滿意🤩
[](agree) 還算滿意😊
[](neutral) 沒想法~✔️
[](disagree) 有點不滿意🤔
[](str_disagree) 非常不滿意😠
{% endlikert %}

{% likert name:"price" %}
# 價格💰
[](str_agree) 很滿意🤩
[](agree) 還算滿意😊
[](neutral) 沒想法~✔️
[](disagree) 有點不滿意🤔
[](str_disagree) 非常不滿意😠
{% endlikert %}

{% likert name:"food" %}
# 食物🍔
[](str_agree) 很滿意🤩
[](agree) 還算滿意😊
[](neutral) 沒想法~✔️
[](disagree) 有點不滿意🤔
[](str_disagree) 非常不滿意😠
{% endlikert %}

{% likert name:"traffic" %}
# 交通安排🚌
[](str_agree) 很滿意🤩
[](agree) 還算滿意😊
[](neutral) 沒想法~✔️
[](disagree) 有點不滿意🤔
[](str_disagree) 非常不滿意😠
{% endlikert %}

{% text_input name:"page_2_clarification" type:"textarea" %}
[有需要的話可以在此補充說明~](page_2_clarification)
{% endtext_input %}
