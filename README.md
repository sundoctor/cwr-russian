# cwr-russian
CWR (CISAC) Standard on Russian with comments

В данном проекте представлен перевод стандарта www.cisac.org
"CWR19-0478 Functional specifications: Common Works Registration Version 3.0 Revision 0"
вместе с комментариями и дополнениями переводчика.

Перевод вольный, быстрый, свободный, выполненный буквально за два майских праздника - поэтому не судите строго.

CWR - это западный стандарт обмена авторскими правами на произведения. Стандарт признан и широко используется
на территории США, Евросоюза, и по-тихоньку начинает использоваться в странах бывшего СНГ.

В качестве произведений рассматриваются: текст, музыка, песни, оперы, балеты, концерты, постановки, звукозаписи, видеоклипы и т.д.
вместе с авторами-создателями этих произведений, а также их вкладами в создание композиции.

В техническом представлении CWR - это заархивированный (zip) текстовый файл, состоящий из записей, каждая из которых,
в свою очередь, состоит из полей разной фиксированной длины с определенными правилами упаковки данных в эти поля.

Стандарт CWR определяет стратегию обмена транзакциями. В числе допустимых транзакций:
* Транзакция регистрации произведения в Авторском Обществе (РАО и аналоги РАО)
* Транзакция о лицензировании произведения для звукозаписи или аудио-визуального продукта
* Транзакция о соответствии транзакции регистрации всем требованиям и условиям регистрации в Обществе
* Транзакция подтверждения о совершенной регистрации или отказе от регистрации (В Авторском Обществе)
* Транзакция на получение/выделение ISWC-кода для регистрируемого произведения

В качестве "материала" для регистрации используются:
* Произведение и авторы этого произведения
* Авторские доли (%) и территории, на которых допустим сбор авторского вознаграждения
* Оригинальные издатели и субиздатели, выполняющие сбор авторского вознаграждения на указанных территориях
* Сведения о существующих звукозаписях (о треках, mp3, wav) и исполнителях произведения
* Сведения о аудио-визуальных продуктах (о видеоклипах, фильмах, сериалах, постановках), в которых использовано произведение

Все используемые элементы данных стандартизированы в соответствии с:
* Набор символов: от ISO-8859-1 до ISO-8859-10
* Коды языков:  ISO-639-1
* Коды письменностей: ISO-15924
* Коды территории: TIS (расширение стандарта ISO 3166-1)
* Коды диалентов языков: ISO-639-2

Кодификация сущностей, используемых в стандарте CWR, выполнена на основании кодов:
* ISWC (International Standard Work Code)
* IPI (Interested Party Identifier) (Бывший CAE)
* ISNI (International Standard Name Identifier)
* ISRC (Internatioanl Standard Recording Code)
* Sender Work Code (Произвольный уникальный код отправителя)
* Sender Catalogue Code (Каталожный код отправителя)

Кроме указанных допустимо сопровождение данных и другими вспомогательными кодами (UPC,EAN,GRID и т.п)

Данных о смежных правах в стандарте CWR нет! Только авторские!
Передача исходника (source material) в CWR не предусмотрена - только метаданные по авторским правам!

Дополнительные комментарии и особенности CWR - в файле cwr-rus.pdf

*Artix*
