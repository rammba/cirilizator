# Ћирилизатор - Ćirilizator - Cyrillizer

Browser extension that transliterates Serbian web pages from Latin to [Cyrillic alphabet](https://en.wikipedia.org/wiki/Serbian_Cyrillic_alphabet).

Екстензија за веб прегледаче која пресловљава српске странице са латинице на ћирилицу.

Компатибилна са следећим веб прегледачима:
- [Google Chrome](https://chrome.google.com/webstore/detail/%D1%9B%D0%B8%D1%80%D0%B8%D0%BB%D0%B8%D0%B7%D0%B0%D1%82%D0%BE%D1%80/nfagbfefkkolkkkanihlahcbdokheeha?hl=sr)
- [Mozilla Firefox](https://addons.mozilla.org/en-US/firefox/addon/cirilizator/)
- [Microsoft Edge](https://microsoftedge.microsoft.com/addons/detail/%D1%9B%D0%B8%D1%80%D0%B8%D0%BB%D0%B8%D0%B7%D0%B0%D1%82%D0%BE%D1%80/omgjhijgcbibdkmdjlnbmgiglkpmikok)

Поред наведених десктоп прегледача, Google Chrome екстензију на Андроид мобилним уређајима може да покрене и [Kiwi Browser](https://play.google.com/store/apps/details?id=com.kiwibrowser.browser).


## Упутство за употребу

Након инсталације, на траци са алаткама (toolbar), појавиће се иконица која вам омогућава да једним кликом пресловите тренутну страницу са латинице на ћирилицу.

Екстензија ће упамтити одабир па ће надаље све странице са истог сајта пресловљавати аутоматски.

Поновни клик на исто дугме вратиће страницу у оригинално стање и искључиће даље аутоматско пресловљавање.

Одмах након инсталације, пресловљавање ће аутоматски бити укључено за неке од најпосећенијих српских сајтова.

У случају да сајт садржи и ћириличну и латиничну верзију, екстензија ће аутоматски преусмерити корисника на ћириличну верзију.


## Напомена

Пре локалног покретања или дистрибуирања екстензије, потребно је садржај фајла `manifest-chrome.json` или `manifest-firefox.json`
копирати у `manifest.json`, зависно од прегледача који користите.


## Аутори

- [Јован Турањанин](https://github.com/turanjanin)
- [Сви сарадници](../../contributors)


## Лиценца

Ово је софтвер отвореног кода, који се слободно може користити у оквиру [MIT лиценце](LICENSE.md).