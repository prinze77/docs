# Language models

A language model is a neural network that is trained to recognize speech in a specific language. The models are trained on datasets generated by Yandex services and applications. This allows us to continually improve the quality of speech recognition.

## New model version releases {#models}

When a new version of the model is published, the `:rc` suffix is added to its name, for example, `general:rc`. When the testing stage ends, the new model replaces the current model, and the `:rc` suffix is removed from the name.

Support for the previous model is discontinued. You can continue using it under the name `general:deprecated` for two weeks.

## Supported language models {#models}

{% list tabs %}

- Russian

  * `general`: The model that recognizes speech on any topic in Russian. This model can recognize short and long utterances, as well as names, addresses, dates, and numbers.

  * `general:rc` (code-named _Diogenes_): The new version of the `general` model.

    This model features improved phone call recognition quality and a reduced number of cases where noise is recognized as words. The vocabulary of the model is still extensive: you can use this model to recognize speech on any topic, just like the previous `general` model.

  {% note warning %}

  Support for the following models will be discontinued on February 26, 2020.

  {% endnote %}
  * `maps`: Addresses and names of companies or geographical features:
      * <q>поехали на улицу кирпичные выемки пять</q>
      * <q>сколько ехать от льва толстого до новой земли</q>
      * <q>покажи маршрут до музея маяковского</q>
  * `dates`: Names of months, ordinal numbers, and cardinal numbers:
      * <q>второго ноль седьмого две тысячи первого</q>
      * <q>двадцать седьмое апреля тысяча девятьсот девятнадцатого года</q>
  * `names`: First and last names and phone call requests:
      * <q>щукин платон</q>
      * <q>соедините с людчиком</q>
      * <q>переговорить с васей васиным</q>
  * `numbers`: Cardinal numbers from 1 to 999 and delimiters (dot, comma, and dash). This model can be used to dictate phone numbers, account numbers, or document numbers:
      * <q>два двенадцать восемьдесят пять ноль шесть</q>
      * <q>сто пятьдесят семь запятая пятнадцать сорок три</q>

- English
  * `general`: Short utterances containing 3-5 words on various topics, including search engine and website queries:
      * <q>connect me to the sales department</q>
      * <q>another cup of coffee and two soft French rolls</q>
  * `maps`: Addresses and names of companies or geographical features:
      * <q>go to Abbey Road</q>

- Turkish
  * `general`: Short utterances containing 3-5 words on various topics, including search engine and website queries:
      * <q>satış departmanıyla görüşmek istiyorum</q>
      * <q>bir kahve daha ve iki küçük kurabiye</q>
  * `maps`: Addresses and names of companies or geographical features:
      * <q>Atatürk Bulvarı'na git</q>

{% endlist %}

