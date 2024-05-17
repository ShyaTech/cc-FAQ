# cc-FAQ
В этом FAQ мы постарались ответить на самые популярные вопросы. Найдёшь устаревшую/неправильную инфу или есть что дополнить - создай issue.
### <h2 align="center"><img width=20px src="https://cdn-icons-png.flaticon.com/128/7425/7425907.png"> FAQ</h2>

<details><summary><b> Что такое криптовалюта?</b></summary>
Это цифровая валюта (электронные деньги), которая работает в полностью автоматическом режиме, а всю ответственность за свои средства несёт сам пользователь.
 <br>Сам термин «криптовалюта» закрепился за биткоином в 2011 году, спустя 3 года после появления биткоина. До тех пор, в основном использолся термин «electronic cash» (электронная наличность).
</details>




<details><summary><b> Когда появилась криптовалюта, в чём отличие от любых других электронных денег?</b></summary>
Большое влияние на появление электронной наличности оказали считьи Дэвида Чома 1982 года:
 <a href=https://web.archive.org/web/20141218034712/http://www.hit.bme.hu/%7Ebuttyan/courses/BMEVIHIM219/2009/Chaum.BlindSigForPayment.1982.PDF>Blind signatures for untraceable payments</a> и 
 <a href=https://web.archive.org/web/20110903023027/http://blog.koehntopp.de/uploads/chaum_fiat_naor_ecash.pdf>Untracable electronic cash</a>  
<br>
<br>Было много разных попыток создания электронных денег, но все они сталкивались с одними и теми же проблемами:
<br>
-пользователи часто теряли свои деньги из-за разного рода мошенничества создателей электронных денег/сайта/приложения и т.д.
 <br>
-пользователи могли потерять свои деньги из-за решения суда / по требованию полиции
 <br>
-обязательно нужен посредник, которому пользователи должны были платить комиссии
<br>
-прозрачность для государства и для преступников/хакеров/воров тоже не шла на пользу обычному пользователю
<br>
<br>
Биткоин, который был создан на основе <a href=https://unenumerated.blogspot.com/2005/12/bit-gold.html>bit-gold</a>, на первых порах хорошо решал все эти проблемы, это способствовало массовому привлечению людей и соответственно резким скачкам курса, что привлекало людей, которые хотели получить прибыль на этом. Получился эффект снежного кома, при этом люди которым действительно была нужна крипта как электронные деньги стали почти незаметны в общей массе и на момент 2024 года мы имеем репутацию криптовалюты не как электронной валюты, а как средство преумножения своих средств и электронного казино с огромным количеством разного скама, обмана и возможностей обнуления.
</details>
















<details><summary><b> Как работает криптовалюта?</b></summary>
<br>Криптовалюта - это цифровая валюта, которая использует <a href=https://www.youtube.com/watch?v=ytMoCcir5bw>эллиптическую криптографию</a> для обеспечения безопасности своих транзакций и контроля над созданием дополнительных монет. Классический подход представляет собой ограниченную эмиссию – заранее заданное количество монет отдаётся майнарам до тех пор, пока все монеты не будут намайнены. Например, у биткоина максимальное количество монет – <a href=https://habr.com/ru/articles/686446/>21 млн</a>. Криптовалюта базируется на технологии блокчейн (за исключением криптовалюты на основе  <a href=https://www.tinkoff.ru/invest/education/courses/8df8b1c8-c769-4d33-992c-0f7deef1518b/4558ba3a-0155-445b-acc2-7d204b70fb16//>DAG</a>), которая представляет собой распределенную базу данных, которая хранит все транзакции в сети. По сути блокчейн это такая общая распределенная книга учёта, в которой посредством приватных ключей пользователь может вносить коррективы. Владение криптой это не монеты в кошельке, а записи в блокчейне, которые навечно в нем, пока хотя бы один валидатор/майнер сети поддерживает сеть (блокчейн биткоина может работать и с одним майнером, теоретическая возможность этого это – огромная уязвимость).
<br>После того, как транзакция подтверждена, она добавляется в блок, который затем добавляется в блокчейн. Каждый блок содержит информацию о предыдущем блоке, что делает блокчейн невозможным для изменения или подделки (правда при соблюдении некоторых условий можно произвести атаку 51% и нарисовать себе любое количество монет, цену атаки можно посмотреть <a href=https://www.crypto51.app/>тут</a>).  
Транзакции с криптовалютой происходят между двумя сторонами без участия третьих лиц (если не считать валидаторов сети или майнеров за третьих лиц, но они функционально внутренний механизм сети, который никак не влияет на транзакцию между двумя сторонами), таких как банки или правительства. 
</details>







<details><summary><b> Что такое блокчейн и какие основные алгоритмы работы блокчейнов?</b></summary>
<br>Сам по себе блокчейн это просто набор данных, который хранится распределенно. Для функционирования блокчейна нужна сеть, то есть сама функция передачи информации между узлами.
<br>Сетей великое множество, основные на данный момент Bitcoin, Ethereum, Binance Smart Chain, Solana, Polygon, Tron. Каждая сеть работает на своем собственном стандарте токенов, по дефолту стандарты не взаимозаменяемы, поэтому отправить напрямую 1 биткоин из сети биткоина в сеть эфира чтобы получить условно 1 эфир не получится. Также есть варианты кроссчейн сетей, когда есть сеть блокчейна, которая соединяет несколько блокчейнов для операций (пример: есть сеть Flux с нативным токеном Flux, помимо этого Flux существует в нескольких других популярных сетях в эквиваленте 1 к 1, например FLUX в BSC и FLUX в Tron, это позволяет без особых усилий гонять монетки Flux между сетями для разных нужд).
<br>
<br>Основной и базовый это POW - proof of work, доказательство работы (топ монет на основе POW можно посмотреть <a href=https://coinmarketcap.com/view/pow/>тут</a>).  Касается всех базовых криптовалют типа Биткоина. Транзакции проверяются и подтверждаются сетью пользователей, которые используют свою вычислительную мощность для решения сложных математических задач. Этот процесс называется майнингом.
<br>Второй базовый это POS - proof of stake, доказательство доли владения. Транзакции проверяются и подтверждаются сетью пользователей-валидаторов, которые владеют каким-то количеством монет сети. Монеты блокируются в сети до отзыва стейкинга - человек становится валидатором. Для примера на эфире минимальный стейк для роли валидатора это 32 эфира. За роль валидатора начисляются комиссионные.
<br>Есть и другие алгоритмы, например POH (proof of history),  PoU (proof of utility), или PoUW (proof of useful work), по сути майнинг 2.0, где майнеры отдают мощности не на абстрактное решение формул в никуда, а на вычисление протеинов например.
<br>
<br>Главное отличие POS от POW это сила централизации, у POS она очевидно выше, потому что меньшее количество людей могут быть валидаторами.
</details>



<details><summary><b> Что такое блоктайм?</b></summary>
Время блока в блокчейне относится к интервалу времени между созданием двух последовательных блоков в блокчейне. Время блока зависит от определенных параметров, таких как сложность вычислений, мощность вычислительных ресурсов, и другие факторы.
<br>Время блока является важным параметром для блокчейн-платформ, так как оно определяет скорость создания новых блоков и, следовательно, скорость обработки транзакций в блокчейне. Время блока также влияет на безопасность блокчейн-платформы, так как более длинное время блока делает блокчейн более устойчивым к атакам 51%.
<br>Время блока может быть различным для различных блокчейн-платформ. Например, время блока в блокчейне Bitcoin составляет около 10 минут, в блокчейне Ethereum - около 15 секунд, а в блокчейне Binance Smart Chain - около 5 секунд.
<br>То есть, упрощая, чем выше скорость генерации новых блоков в сети, тем больше ее пропускная способность для количества транзакций.
</details>


<details><summary><b> Что такое валидация?</b></summary>
Валидация (подтверждение, или по другому конфирмация/confirmation time) в блокчейне относится к процессу подтверждения и проверки транзакций и блоков данных, которые добавляются в блокчейн. Этот процесс гарантирует, что все транзакции и блоки соответствуют правилам и стандартам сети блокчейна.
<br>Когда транзакция или блок данных успешно проходит процесс валидации, она добавляется в блокчейн и становится частью его истории. Этот процесс гарантирует, что все транзакции и блоки данных в блокчейне являются достоверными и не могут быть изменены или удалены без согласия всех участников сети.
<br>В обычном пользовании на время/процесс валидации можно не обращать внимание, например время валидации транзы в BSC это 2 блока (10 секунд). В основном на время валидации нужно обращать внимание, когда гоняешь монетки с биржи и на биржу, потому что биржи чисто для себя ставят валидацию для зачисления монет на твой счет выше, чем время валидации сети.
</details>

<details><summary><b> Что такое газ?</b></summary>
Это комиссия, которую платит пользователь для совершения транзакции. В основном газ платится в тех же самых монетах, что и главные оперируемые монеты сети. То есть за передачу токена PERDEZH по сети BSC нужно будет заплатить комиссию в токене BNB.
</details>

<details><summary><b> Что такое контракты?</b></summary>
Контракты в блокчейне, также известные как умные контракты (smart contracts), представляют собой "программы", которые автоматически выполняют определенные действия при выполнении определенных условий. Они хранятся на блокчейне и выполняются на основе кода, заложенного в них. В основном контракты используют для развертывания на основе блокчейн сети дополнительных токенов сети, то есть буквально ты можешь спокойно выпустить свою собственную криптовалюту в конкретной сети, используя смарт-контракт. Но у контрактов есть и другие более специфические функции, например их используют для займов и кредитования. По сути смарт-контракт это цифровой договор, который выполняется автоматически.
</details>

<details><summary><b> Что такое Layer?</b></summary>
Внезапно, это слои блокчейна. Если не углубляться, то:
<br>Layer 1 - основная сеть блокчейна, для примера берем биткоин - это L1. Но у биткоина есть также Lightning Network (протокол для быстрых дешевых платежей внутри сети биткоина) - это уже Layer 2. 
<br>Layer 0 - инфраструктурный слой блокчейнов, направленный на совместимость сетей Layer 1.
<br>В общем и целом, лееры это про расширение возможностей сетей и их масштабируемость. Что интересно, L1 был создан раньше всех, это уже потом начали придумывать как решать вскрывшиеся проблемы L1 сетей и приделывать пятое колесо из-за высокой комиссии и низкой скорости.
</details>

<details><summary><b> Что такое обертки в блокчейне?</b></summary>
Обертки (wrapped) в блокчейне относятся к концепции "обернутых" или "замороженных" токенов, которые представляют собой токены на одной блокчейн-платформе, но обернутые или замороженные на другой блокчейн-платформе.
<br>Обычно это делается для того, чтобы обеспечить совместимость между различными блокчейн-платформами и позволить пользователям использовать токены на различных платформах. Например, если пользователь хочет использовать токены, основанные на блокчейне Ethereum, на блокчейне Binance Smart Chain, он может обернуть или заморозить свои токены Ethereum и получить аналогичные токены на блокчейне Binance Smart Chain.
</details>

<details><summary><b> Что такое свап?</b></summary>
Свап токенов в криптовалюте относится к процессу обмена одного типа токенов на другой тип токенов на определенном рынке или платформе. Этот процесс обычно происходит на криптовалютных биржах или decentralized exchanges (DEX), где пользователи могут обменивать свои токены на другие токены, используя различные механизмы обмена.
</details>




<details><summary><b> Я хочу углубиться в историю денег и подробнее почитать про биткоин</b></summary>
Довольно хорошо описана история денег и технические особенности в книге:
<br>Cейфедин Аммус – Краткая история денег, или Все, что нужно знать о биткоине <a href=https://docs.f2c.dev/Oris_Lab/The_Bitcoin_Standard_The_Decentralized_Alternative_To_Central_Banking.pdf>скачать</a>
<br>После этой книги можно стать крипто-макси, готовьтесь к изменению своего мировоззрения...
<br>
<br>В этой книге рассказываются подробности создания биткоина, формирования коммьюнити, начало использования и прочее:
<br>Поппер Н. - Цифровое золото. Невероятная история биткоина <a href=https://vk.com/doc310230351_450966910?hash=F7QSBDZvoPJDupZxU4C8uVbCGlPqpEqvkeZcZMsGfqX>скачать</a> 
<br>
<br>Ещё книги можно найти тут: https://bitcointalk.org/index.php?topic=1820209.0 (для просмотра может потребоваться впн/прокси)
<br>
<br>Техническое описание биткоина – (white paper) (eng): https://bitcoin.org/bitcoin.pdf и (ru): https://bitcoin.org/files/bitcoin-paper/bitcoin_ru.pdf
<br>
<br>
Кратко можно почитать на лурке или на википедии:
<br> http://www.lurklurk.com/bitcoin
<br>
https://ru.wikipedia.org/wiki/Биткойн
<br>
https://ru.wikipedia.org/wiki/Электронные_деньги
<br>
https://ru.wikipedia.org/wiki/Криптовалюта
<br><br>Тут можно найти все сообщения самого Satoshi Nakamoto: https://bitcointalk.org/index.php?action=profile;u=3 (для просмотра может потребоваться впн/прокси)
</details>


<details><summary><b> Что такое стейблкоины, какие они бывают, как купить, как использовать?</b></summary>
Stablecoin - это вид криптовалюты, который привязан к стабильной валюте или ценному товару, такому как доллар США или золото. Это делает их менее восприимчивыми к колебаниям рынка, чем другие криптовалюты, такие как биткойн или эфириум. <br>Стейблы используются для создания стабильности в криптоиндустрии и для упрощения транзакций между различными криптовалютами. Большинство операций в крипте происходит по отношению к USDT.
<br>Основные стейблкоины на 2024 год - USDT, USDC и DAI. 
<br>В общем и целом нужно знать, что большинство стейблов являются ультрацентрализованными, могут быть удаленно заморожены компанией, занимающейся эмиссией и прочие подобные приколы. Но есть и децентрализованные решения по типу DAI, которые работают на разных автоматических принципах сохранения цены, что тоже имеет свои минусы в виде возможной потери стабильности и т.н. анпега (unpeg - когда 1 доллар стоит не 1 доллар). История знает про крах стейблкоина UST, можете почитать отдельно. Есть мнения, что такой же крах неизбежно ждёт и остальные стейбоины, потому что они фактически печатаются из воздуха и держатся только за счёт того, что все пользователи не приходят сразу за всеми своими монетами.
<br>Еще есть немного устаревший обзор стейблов https://teletype.in/@notothemoon/vk0N8jdiqGd , тоже будет полезно почитать для общего образования.
<br>Помимо этого использование стейблов напрямую связано с выводом крипты в обычные (фиатные) деньги и вводом обычных денег в крипторынок через биржи, буквально 90% P2P торговли крутится вокруг продажи/покупки USDT.
</details>

<details><summary><b> Где купить криптовалюту?</b></summary>
Вариант №1 – https://www.bestchange.ru/
<br>Вариант №2 – На бирже. Представляет собой p2p, в котором могут кинуть, не смотря на кажущаюся надежность.
<br>Вариант №3 – Криптоматы
<br>Можно посмотреть на различных картах, например: https://coinmap.org/view/#/world/-2.63578857/4.74609375/2/atm
<br>По криптоматам ситуация в РФ напряженная, их часто демонтируют как незаконные. И не все криптоматы есть на карте. Из работающих и пока ещё не демонтированных есть https://criptamat.ru/.
<br>Количество криптоматов в мире <a href=https://coinatmradar.com/charts/growth/>растёт</a>, что не может не радовать.
<br>Вариант №4 – p2p через https://localmonero.co/ (не для всех стран может работать, сейчас не работает в РФ и Беларуси)
<br>Вариант №5 – Купить через p2p-маркет в телеграме во встроенном кошельке (@wallet)
<br>Вариант №6 – Прочее. Часто крипту можно купить с рук у различных барыг с форумов вроде https://bitcointalk.org/ или на каких-то малоизвестных обменниках, например на https://simpleswap.io/ https://changenow.io/ https://monero.com/ и т.д.
</details>





<details><summary><b> Что такое KYC, AML</b></summary>
KYC – Know Your Client – знай своего клиента
<br>На https://www.bestchange.ru/ обменники, которые требуют KYC, имеют знак человечка:

![image](https://github.com/ShyaTech/cc-FAQ/assets/121751505/61e7ca0e-5344-4237-b2ce-b50adf165952)
<br>AML – Anti-Money Laundering – противодействие отмыванию денег
<br>На https://www.bestchange.ru/ обменники, которые требуют AML (сфоткать свою банковскую картну на фоне экрана с заявкой, имя и фамилию можно закрыть пальцем), имеют знак карточки:
![image](https://github.com/ShyaTech/cc-FAQ/assets/121751505/bb213a25-eaab-4f17-b284-184d74522bb4)
<br>
<br>По своему опыту можем сказать, что вся инфа с обменников с bestchange.ru сливается и спустя время на телефон нонстоп начинают звонить мошенники, поэтому выбирайте для себя что удобнее – выгодный курс, но с KYC/AML или не такой выгодый, без KYC/AML, но без нонстоп звонков на телефон.

<br> Биржи в основном требуют KYC, а ещё они имеют свойство сотрудничать с органами. 
<br> Топ популярных бирж в РФ – Bybit, HTX, Deribit, MEXC, Bitget, Kucoin, OKX, Gate и CommEX. Из них торговать и вводить/выводить без KYC можно только на и Bybit, но до определённого предела, на Bybit вывод без KYC – до 20к$ в сутки. KYC могут затребовать и до достижения этих пределов.

<br>https://nonkyc.io – биржа, которая заявляет, что работает вообще без KYC.
</details>




<details><summary><b> Какие сейчас комиссии у криптовалют?</b></summary>
У всей крипты комиссии это буквально сотые доли копейки. Исключения – биткоин и эфир. Если в кошельке не выставить низкий «приоритет транзакции» (чем быстрее, тем дороже) и иметь отрицательный бафф на удачу, то переведёшь биткоин за 5+$, а эфир за 200+$ . В зависимости приоритета транзакции, от ситуации на рынке и даже в зависимости от времени дня, комиссии могут отличаться в 10 раз.
<br>
<br>Для сравнения есть https://cryptostreets.io/
<br>Для выставления подходящей комиссии по биткоину есть https://mempool.space/ru/
</details>






<details><summary><b> Где посмотреть графики цены криптовалюты?</b></summary>
Смотреть средне-взвешенную цену удобно на аггрегаторах, например:
<br>https://coinmarketcap.com/
<br>https://www.tradingview.com/markets/cryptocurrencies/prices-all/
<br>https://www.coingecko.com/
<br>https://coinpaprika.com/
</details>


<details><summary><b>Как самому создать адрес на который можно переводить криптовалюту? Где хранить криптовалюту? Какие есть кошельки? </b></summary>
Один из самых простых способов «создать себе адрес» это использовать генератор из html-страницы. Страницу можно скачать, перекинуть на какое угодно устройство которому доверяете и сгенерировать кошелёк. Интернет для генерации не нужен и скорее даже вреден.
<br>Для биткоина можно использовать: https://www.bitaddress.org/
<br>Для монеро можно использовать: https://xmr.llcoins.net/
<br>Для litecoin можно использовать: https://liteaddress.org/
<br>Публичный ключ можно давать кому угодно, обменникам, биржам и т.д.
<br>Mnemonic seed (либо private key у биткоина) надо записать себе, зашифровать, скопировать и т.д. – на что фантазии хватит – каждый сам себе банк.
<br>
<br>Во всех кошельках есть встроенный генератор адреса – это удобно, но очевидно, менее безопастно.
<br>
<br>Хранить надёжнее всего на холодных кошельках: это может быть созданная вручную пара публичный ключ-приватный ключ и записанная на бумагу либо покупной аппаратный кошелёк.
<br>Наиболее популярные кошельки это Trezon и Ledger. Даже с ними стоит быть осторожным: Trezor использует Chainalysis для анализа транзакций и может заблокировать, если помечена красным флагом. Ledger был замечен в отправлении сид-фразы на свои сервера. Доставляется не во все страны, если неофициальный поставщик, то есть шанс взять палёный кошелёк. 
<br>Сравнение всех (почти) аппаратных кошельков есть тут: https://thebitcoinhole.com/hardware-wallets
<br>

<br>Горячие Кошельки есть кастодиальные (у тебя нет ключей) и некастодиальные (у тебя есть ключи).
<br>Хорошие, известные некастодиальные кошельки:
<br>https://cakewallet.com/ (Andoid, iOS) – Хороший кошелёк, открытый исходный код. В подозрительных мутных движения замечен не был. Работает только на смартфонах.
<br>https://www.exodus.com/ (Windows, macOS, Linux, Andoid, iOS, расширение для браузера) – Популярный удобный кошелёк, но исходный код закрытый. Плохая техническая поддержка.
<br>https://trustwallet.com/ (Android, iOS, расширение для браузера) – Открытый исходный код, фактически кошелёк биржи binance. Есть API.
<br>https://metamask.io/ (расширение для браузера) – Удобен для эфира и токенов на нём. <a href=https://cointelegraph.com/news/metamask-will-start-collecting-user-ip-addresses/>Собирает</a> ip адреса пользователей и метаданные.
<br>https://phantom.app/ (Android, iOS, расширение для браузера) – Популярный удобный кошелёк, но часто подвергается различного вида атакам. Много жалоб на фишинг и различные вирусы (болезнь всех кошельков в виде расширения для браузеров).
<br>https://zelcore.io/ (Windows, Linux, macOS, Android, iOS) – Мультивалютный кошелёк, открытый исходный код.
<br>https://coin98.com/ (Android, iOS, расщирение для браузера) – Мультивалютный кошелёк, открытый исходный код. Поддерживает Defi. Создатели из Вьетнама.
<br>https://safepal.com/ (Android, iOS, расширение для браузера) – Мультивалютный кошелёк, созданный биржей binance. Закрытый исходный код. Находили некоторые <a href=https://blog.kraken.com/product/security/kraken-security-labs-finds-flaws-in-safepal-s1-hardware-wallet>уязвимости</a>. 



<br>Для биткоина самый популярный кошелёк это https://electrum.org/, для монеро https://featherwallet.org/, https://mymonero.com/ и https://www.getmonero.org/downloads/, для litecoin: https://litewallet.io/
<br>Кошельки для соланы можно найти тут: https://solana.com/ecosystem/explore?categories=wallet&nextInternalLocale=en
</details>
<details><summary><b> Как обменять одну криптовалюту на другую криптовалюту?</b></summary>
Вариант №1 – На биржах, централизованных (CEX) и децентрализованных (DEX). Список CEX: https://www.coingecko.com/en/exchanges. Список DEX:https://www.coingecko.com/en/exchanges/decentralized
<br>Вариант №2 – Попробовать атомарные свопы. https://unstoppableswap.net/ Без комиссий, но пока что работает только bitcoin -> monero.
<br>Вариант №3 – На обменниках из выдачи на https://www.bestchange.ru/ (тут будут комиссии, ваши данные могут слить мошенникам, налоговой, полиции и прочим) 
<br>Вариант №4 – Некоторые кошельки позволяют покупать с банковской карты. Работает не для всех стран. Такая возможность заявлена, например у Trust wallet, metamask, cake wallet и т.д.

 <br>https://bisq.network/ – Открытый исходный код, ты имеешь ключи от монет, нет KYC.
 <br> https://basicswapdex.com/ – Открытый исходный код, ты имеешь ключи от монет, нет KYC.
 <br>https://hodlhodl.com/ – Ты имеешь ключи от монет, нет KYC.
 <br>
 <br>Полный список всех DEX можно найти тут: https://www.coingecko.com/en/exchanges/decentralized
</details>



<details><summary><b> Какие биржи посоветуете?</b></summary>
Никакие.
 <br>
<br> Две самые популярные биржи из прошлого благополучно обнулились (btc-e и mtgox).
 <br>Самые топовые биржи регулярно закрываются или «взламываются» и пользователям ничего не возмещают. Храня средства на централизованных биржах (CEX) следует помнить, что «not your keys not your crypto». Поспекулировать - выбирай любую, но большие суммы не храни. Биржи созданы не для хранения средств мимокроков, а для прибыли владельцев биржи. Самые проверенные биржи могут внезапно запросить подтверждение личности (KYC) или перестать работать в страна_нейм.
 <br>
<br> Если предостерегающий абзац тебя не вразумил и ты отчаянно хочешь стать ресурсным, то все централизованные биржи (CEX) тут: https://www.coingecko.com/en/exchanges 
 <br> А без KYC до высоких лимитов это https://www.kraken.com/ и https://www.bybit.com/
 <br> Чуть ли не ежедневно выходят новости о том, что биржа_нейм анально огородилась от страна_нейм или «временно запрещен вывод». Это стоит закладывать в свои риски. Пожаловаться будет некому, весь интернет завален такими «жалобами».
 <br>
 <br> Несколько особняком стоят DEX (децентрализованные биржи), это в некотором смысле более безопастный вариант, но на них меньше возможностей (меньше торгуемых пар, нет фьючерсов, меньше ликвидность).
 <br>Отметить можно следующие:
 <br>https://bisq.network/ – Открытый исходный код, ты имеешь ключи от монет, нет KYC.
 <br> https://basicswapdex.com/ – Открытый исходный код, ты имеешь ключи от монет, нет KYC.
 <br>https://hodlhodl.com/ Ты имеешь ключи от монет, нет KYC.
 <br>
 <br>Полный список всех DEX можно найти тут: https://www.coingecko.com/en/exchanges/decentralized
</details>





<details><summary><b> Что такое токен и как его купить?</b></summary>
Токен, это актив, по сути сам не являющийся криптовалютой, но который можно обменять на криптовалюту на базе которой он создан.
 Например токен  <a href=https://coinmarketcap.com/currencies/bonk1/>Bonk</a> создан на блокчейне соланы, по стрелочке виден номер контракта:
 <br>

 ![image](https://github.com/ShyaTech/cc-FAQ/assets/121751505/c67bbda3-f885-4b9f-9ce7-5136f0a56ea7)

Покупка токенов это ещё более рискованное действие, чем покупка криптовалюты, поэтому если токена нет на аггрегаторах (https://coinmarketcap.com/, https://coinpaprika.com/, https://www.coingecko.com/) то будьте очень осторожны: у токена очень маленькая капитализация. Буквально за пару часов (и даже минут) можно получить -99,99% от вложений в этот токен, создатель токена как правило имеет запас монет на разных не связанных кошельках и в автоматическом режиме может обвалить курс или создать видимость покупки. Создатели токенов создают их буквально за 5 минут, у многих этот процесс автоматизирован, с токенами варианты скамы очень разнообразны и постоянно появлются новые методы. Можно попытаться обезопасить себя и проверить токен на сайте-анализаторе либо в ботах в телеграме. Для соланы есть такие анализаторы токенов: https://rugcheck.xyz/ и https://www.solsniffer.com/, а в телеграме можно попытаться проанализировать продаёт ли разраб свои токены или всё ещё холдит: @is_dev_selling_bot
<br>Найти все токены и посмотреть графики можно тут:
<br>https://birdeye.so/ – хороший старый сайт, чаще всего корректно отображает покупки-продажи какого-то адреса. Но нет секундного таймфрейма, поэтому он скорее информативный.
<br>https://www.dextools.io/app/en/pairs – аналогичный birdeye, но есть секундный таймфрейм, графики обновляются быстро, как правило, быстрее, чем на dexscreener.
<br>https://dexscreener.com/ – удобный сайт, аналогичный birdeye и dextools, графики несколько запаздывают от реальности.
<br>https://www.lynxs.io/ – аггрегатор новых токенов, показывает сразу степень риска при покупке
Непосредственные попытки купить на дне и продать на хаях на всех этих 4-х сайтах несколько сложноваты, не стоит рассчитывать, что будешь первым.
<br>Для почти мгновенных графиков есть https://photon.tinyastro.io/ - он работает для таких токенов как ETH, BLAST, SOL, BASE. Для логина надо привязать кошелёк https://phantom.app/, поэтому будьте осторожны и не привязывайте кошелёк на котором много средств. Для пользования сайтом подойдёт любая сумма, даже 0,0001 SOL.
<br>
<br> Купить токены можно несколькими путями:
<br>Вариант №1 – самый безопастный и быстрый – биржа. На биржи попадают только токены с крупной капитализацией либо токены, которые крупно занесли бирже. Узнать на какой бирже есть токен, можно на https://coinmarketcap.com/ под графиком цены.
<br>Вариант №2 – безопастный, но медленный. Любой токен можно купить дав кошельку контракт токена. Из хороших кошельков можно порекомендовать https://phantom.app/
<br>Вариант №3 – безопастный, но медленный. Покупка напрямую у пула. Необходимо зайти на сайт пула, например https://raydium.io/ и привязать кошелёк (например phantom).
<br>Вариант №4 – небезопастный, очень быстрый, есть комиссии. Это телеграм-боты. Все они имеют схожий функционал, выбор это скорее дело вкуса. Большие суммы хранить не стоит, не раз их «взламывали».
<br>Более или менее известные: @solana_trojanbot @SolTradingBot @bonkbot_bot @maestro @maestropro @BananaGunSolana_bot @magnum_trade_bot @stonks_sniper_bot
<br>Если надо отследить какой-то кошелёк (что покупает и продаёт), то есть такой бот на солане: @solana_notify_bot
<br> Комиссии, функционал, торгуемые блокчейны, скорость могут меняться. Часто если кто-то активно предлагает вам бота, то он даёт вам его с реферальной ссылкой, так он будет иметь с вас комиссию.
<br>Вариант №5 – кастомные боты с гитхаба/гитлаба/с выдачи гугла. Часто они могут работать по скорости так же как и телеграм-боты, но приходится запускать незнакомые .exe. Есть боты без комиссий.
<br>Вариант №6 – https://photon.tinyastro.io/ – небезопастный, но очень быстрый способ. Необходимо привязать кошелёк, например тот же phantom.
<br>
<br>Так как начинающему может не очень быть понятно что купить, что продать, как вообще отбирать токены, то есть коллеры (сигнальщики). Часто им платят сами разработчики монет, чтобы они заколлили их говнину и разрабы вышли об читателей коллера. Анализатор коллеров в телеграме: @CallAnalyser
<br>
<br>Если ты преисполнился в торговле токенов на солане, например на одном адресе купил-продал уже 1000 токенов, то можно «сжечь» пустые токены, за 2 месяца неспешных торгов вернётся 1-3 соланы, сделать можно <a href=https://sol-incinerator.com//>тут</a> 
</details> 






<details><summary><b> Купить  и холдить скучно, что почитать для трейдинга? Хочу максимально быстро разбогатеть. </b></summary>
Факт №1. Если ты купил не на самом пике бычьего рынка, то вероятнее всего, выгоднее будет просто купить и держать. 
<br>Факт №2. Покупать с равными промежутками выгоднее, чем пытаться поймать дно и максимально выгодно войти.
<br>Факт №3. Если работаешь/учишься, если не дежуришь у компьютера 24/7, не готов посвящать трейдингу всё своё время, то лучше и не начинать.
</details>





<details><summary><b> Как мне купить что-то в даркнете максимально анонимно?</b></summary>
1. Купить какую угодно криптовалюту любым из способов. Можно купить сразу монеро.
<br>2. Любым из способов обменять эту криптовалюту на монеро (пропускаем, если сразу купили монеро).
<br>3. Кидаем со своего кошелька_монеро_1 на другой свой кошелёк_монеро_2.
<br>4. Со своего кошелька_монеро_2 покупаем что угодно и где угодно.
<br>
 <br>Важно! Никогда не давайте обменнику/бирже и т.д. адрес магазина в даркнете. Сначала киньте на свой монеро-адрес и только потом уже магазину.
<br>
 <br>Можно вместо монеро использовать биткоин, т.к. он больше где принимается, но биткоин надо будет прогнать через Whirlpool в кошельке под названием Samourai wallet. У биткоина дольше идут транзакции (могут идти несколько часов) и больше комиссии (может быть 5+$).
</details>

<details><summary><b> Как максимально перемешать биткоины?</b></summary> 
Лучший способ сейчас это – воспользоваться Whirlpool в кошельке под названием Samourai wallet.
 <br>
 <br> Используя биткоин для не совсем законных дел, стоит помнить, что существует много компаний, которые профессионально отслеживают биткоины, вот некоторые из них:
 <br>Ciphertrace
<br>Chainalysis
<br>Elliptic
<br>IdentityMind
<br>Elementus
<br>BlockSeer
<br>Scorechain
<br>Neutrino
<br>Crystal
<br>Blockchain Intel
</details>



<details><summary><b> Можно ли как-то использовать криптовалюту, купить что-то за неё?</b></summary>
Можно.
<br>Кроме очевидных магазинов в даркнете, есть ещё около-законные места.
<br>Тут собраны все места торговли ИРЛ за крипту: https://cryptwerk.com/
<br>Можно купить предоплаченные карты: https://www.coinsbee.com/
<br>Можно купить подарочные карты и оплатить ими в магазине: https://coincards.com/ и https://www.bitrefill.com/
<br>Монеро-маркет: https://moneromarket.io/
<br> Тут различные vps, vpn, sms и прочее: https://kycnot.me/
</details>





<details><summary><b>Что такое NFT и GameFi/SocialFi?</b></summary> 
NFT (Non-Fungible Token) - это уникальный цифровой актив, который представляет собой определенный объект, такой как картина, видео, музыка или даже твит. NFT использует блокчейн-технологию для подтверждения исключительной собственности на определенный объект. Это означает, что каждый NFT является уникальным и не может быть заменен другим NFT. NFT используются для создания цифровых коллекционных предметов, искусства и других уникальных объектов, которые могут быть проданы и куплены на различных платформах.
Концепция NFT сама по себе достаточно полезна, но ей буквально не нашли применения в реальном мире. Первый и единственный бум NFT сопровождался миллиардами копий успешных нфт коллекций, сделанных чуть ранее, в попытке запрыгнуть на хайптрейн, влет корпораций на тот же хайптрейн, всеобщим бугуртом от того, что нфт пытались приделать вообще ко всему (привет Ubisoft) и далее по списку обосрамсов. На данный момент рынок конкретно NFT мёртв и, вероятно, будет мертвым долго.
<br>
<br>Но NFT нашли себя в блокчейн играх, хотя блокчейн игры тоже скорее в мертвом состоянии из-за отсутствия как такового интересного геймплея и момента удержания игрока в 90% случаев, но не так сильно как классический NFT рыночек.
<br>
<br>GameFi/SocialFi (aka криптоигры и сервисы основанные на социальном взаимодействии) – это сочетание игр/социальных активностей и криптовалютных приколов. В основе GameFi лежит идея того, что игроки могут получать доход от своих действий в игре, используя криптовалюты и NFT. То есть концепция "прикрути в игру возможность торговать" сама по себе рабочая и существует уже давно - контерстрайк с кейсами/скинами это тот же самый принцип, но без блокчейна. Если упрощать концепт SocialFi отдельно, то это будет соцсеть, у которой криптоприкол на борту (оплата за действия, оплата за лайки, просмотры и т.д.). 
<br>
<br>У криптоигр есть несколько базовых механизмов реализации:
 <br>Play-to-Earn (P2E) – это игры, в которых игроки могут зарабатывать криптовалюту или NFT за свои действия в игре. Эти активы могут быть обменены на реальные деньги или использованы для улучшения игрового опыта. Примеры P2E-игр включают Axie Infinity, The Sandbox и Decentraland. Сюда же относится особо популярный ранее социальный "поджанр" move-to-earn, который тоже получил отдельно множество клонов. Пример игры - STEPN, где ты получаешь гиги за шаги.
<br>
<br>NFT-игры – это игры, в которых игроки могут создавать, обменивать или продавать уникальные NFT, которые представляют собой игровые предметы, землю, персонажей и т.д. Примеры NFT-игр включают CryptoKitties, Gods Unchained и Sorare.
<br>
<br>DeFi-игры – это игры, которые интегрируют DeFi-механизмы, такие как кредитование, ставки и обмен, в игровой процесс. Это позволяет игрокам получать доход от своих активов и участия в игровом экосистеме. Примеры DeFi-игр включают Aavegotchi, Alien Worlds и Yield Guild Games.
<br>
<br>Blackchain-игры – это игры, которые построены на блокчейн-платформах и используют криптовалюты и NFT для управления игровой экономикой. Все транзакции и события в игре записываются на блокчейне (а значит будут как-то требовать подключение кошекльков к игре и синхронизацию с блокчейном). Примеры игр на блокчейне включают Ethereum-игры, например CryptoKitties; игры на Binance Smart Chain, например Mobox; Sunflower Land на блокчейне Polygon. Тысячи их в общем.
<br>
<br>SocialFi не делится практически никак - это обычно просто сервис/приложение, в котором как-то впихнули крипту за активность в этом сервисе/приложении. Если очень нужен пример, то это Steemit, friend.tech, TON Place.
<br>
<br>В общем и целом, деление довольно условное и криптоигра/криптосервис может миксовать варианты реализации внутри себя как угодно.
<br>
<br>Основной минус криптоигр - они в большинстве своём скучны и примитивны, как Notcoin. Исключения составляют условные криптопокемоны и попытки в лутерные рпг, где лут очевидно нфтшный, да и соцсеточки, где есть хотя бы какой-то калтент и разнообразие.
</details>



<details><summary><b> Может есть ещё какие-то FAQ?</b></summary>
Есть.
   <br>
<a href=https://pastebin.com/mcHrtfxH>Старый FAQ</a>
<br>https://bitcoin.org/ru/faq
<br>https://academy.binance.com/ru
<br>https://github.com/snordenstorm/wiki/wiki/Майнинг-биткойнов
</details>

