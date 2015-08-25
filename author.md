# 作者
本手冊由YMSer台灣社群共同編輯。

主要內容皆來自網友無私的資訊分享，所有文章內容使用知識共享署名-相同方式共享（CC BY-SA 4.0）協議。以下列出所有參與本手冊撰寫的貢獻者（依英文字母順序排列）
  - 貢獻者(Contributors)：主要提供編輯、排版、上稿等程序的網友
  - 內容提供者(Content Providers)：主要提供文章內容、心得分享、當地資訊的網友
  - 社群(Communities)：彙整英國打共渡假情報的FB社團、Line群組、實體社群

## 貢獻者(Contributors)
{% for contributor in book.contributors %}
  - [{{ contributor.name }}]({{ contributor.link }})
{% endfor %}

## 內容提供者(Content Providers)
{% for provider in book.providers %}
  - [{{ provider.name }}]({{ provider.link }})
{% endfor %}

## 社群(Communities)
{% for community in book.communities %}
  - [{{ community.name }}]({{ community.link }})
{% endfor %}