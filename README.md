# Console SCP
<i><h1>Design Document</i></h1>
<i><h1>Copyright info and credits and whatnot</i></h1>


### Игровой мир

Цели игры<br>
Цель №1: разбор и осмотр работы консольной программы, осмотр материалов.<br>
Цель №2: поиск материалов по объектам имеющих номера SCP-001.<br>
Цель №3: после события _______ главному герою предстоит параллельно с целью №2 разузнать о произошедшем инциденте.<br>
##### Сюжет
Сюжет
v.1 (Гора) 
*Все названия утилит условны*
В начале игры небольшой туториал где ГГ знакомят с интерфейсом игры (можно сделать всплывающие подсказки наподобие справок в интерфейсе TF2). В этой части мы просто мистер Инкогнито, который используя системные утилиты оформляет аккаунт на форуме F и проходит онлайн-курс по заполнению резюме (игрока учат взаимодействию с командной строкой и утилитами mail, copy, start, close, browse).
Гик U
Во время лазания по форуму, U получает сообщение от какого-нибудь xXx_super_secret_mlg_doc_xXx с просьбой сохранить у себя архив euf7r3f7r3fhu33o299.zip и никому его не передавать. На вопрос "где данные" не отвечать и всё в таком духе. После этого U обнаруживает что аккаунт xXx_super_secret_mlg_doc_xXx был "заблокирован требованием совета нац безопасности ООН" (можно и ФСБ РФ, и ЦРУ США, главное чтоб шишка большая была). U понимает, что здесь что-то не чисто, и запихивает euf7r3f7r3fhu33o299.zip на один из своих древних девайсов (какой-нибудь Sony Ericson, не знаю). Во время одного из походов в магазин, U преследуют, но он отрывается от погони (это можно расписать в своеобразном дневнике. Мол, он гик и писать дневник ему легче в своей ПеКарне)этой погони U ставит себе цель - за 4 дня выяснить что ему грозит. Отключившись от сети, он начинает изучать содержимое архива и обнаруживает файлы ОУС, протоколы экспериментов и т.п.
##### Условные обозначения
Условное обозначение  - обозначение, являющееся условным.

### Игровая механика/логика

##### Функции
Описано в блок схеме - <a href="https://drive.google.com/file/d/1oz3-kOTxENuFBddj-yefvJBvohPK-Q-N/view?usp=sharing">Console SCP Diagram</a>
##### События
1.

##### Уровни
Основные уровни игрового процесса заключены в уровне допуска персонализации фонда (Уровень допуска сотрудника Фонда соответствует максимальному уровню секретности информации, к которой он может получить доступ. Однако это не означает автоматического получения доступа ко всей соответствующей информации: доступ к данным предоставляется по принципу служебной необходимости и на усмотрение сотрудников конкретных отделов, уполномоченных раскрывать эту информацию.).
###### Уровни допуска:
<b>Уровень 0</b> (Для общего пользования)<br>
Уровень допуска 0 выдаётся сотрудникам, не представляющим особой ценности, которым не требуется доступ к информации об аномальных артефактах или существах, содержащихся Фондом. Как правило, уровень допуска 0 имеется у сотрудников, занимающих должности в канцелярии и отделе снабжения учреждений, непосредственно не связанных с содержанием объектов, а также у обслуживающего персонала таких учреждений.<br>
<b>Уровень 1</b> (Для служебного пользования)<br>
Уровень допуска 1 выдаётся сотрудникам, работающим в непосредственной близости от аномальных объектов или существ, но не обладающих к ним прямым, непрямым или информационным доступом, а также сотрудникам, имеющим дело с засекреченной информацией. Как правило, уровень допуска 1 имеется у сотрудников, занимающих должности в канцелярии и отделе снабжения учреждений, непосредственно занимающихся содержанием объектов, а также у обслуживающего персонала таких учреждений.<br>
<b>Уровень 2</b> (Для ограниченного пользования)<br>
Уровень допуска 2 выдаётся сотрудникам службы безопасности и научным сотрудникам, которым необходим прямой доступ к базовой информации касательно аномальных объектов или существ, находящихся на содержании. Большинство научных сотрудников, полевых агентов и специалистов по содержанию обладают уровнем допуска 2.<br>
<b>Уровень 3</b> (Секретно)<br>
Уровень допуска 3 выдаётся старшим сотрудникам службы безопасности и научным сотрудникам, которым необходим доступ к подробной информации касательно аномальных объектов или существ, находящихся на содержании, включая их происхождение, обстоятельства изъятия и долгосрочные планы на них. Большинство старших научных сотрудников, руководителей проектов, офицеров службы безопасности, членов групп реагирования и оперативников МОГ обладают уровнем допуска 3.<br>
<b>Уровень 4</b> (Совершенно секретно)<br>
Уровень допуска 4 выдается старшему управленческому персоналу, которому необходим доступ ко всей информации отдельного учреждения и/или региона, а также к долгосрочным планам касательно операций и научных проектов Фонда. Как правило, 4 уровнем допуска обладают только руководители Зон, руководители служб безопасности учреждений и командующие МОГ.<br>
<b>Уровень 5</b> (Таумиэль)<br>
Уровень допуска 5 выдаётся сотрудникам высшего управленческого звена Фонда и гарантирует практически полный доступ ко всей стратегической и секретной информации. Как правило, уровнем допуска 5 обладают только члены Совета O5.<br>

##### Классы:
<b>Класс A</b><br>
Класс A присваивается сотрудникам, которые считаются жизненно важными для стратегических операций Фонда, вследствие чего им запрещен какой-либо прямой доступ к аномальным объектам. Если персоналу класса A по какой-либо причине необходимо находиться поблизости от подобных аномалий (например, в случае их работы в учреждении, занимающемся содержанием), они обязаны постоянно пребывать в защищенных областях, доступ в места непосредственного содержания объектов для них закрыт. В чрезвычайных ситуациях сотрудников класса A надлежит немедленно эвакуировать в заранее установленную и безопасную область вне данного учреждения. Членам Совета O5 класс A присваивается на постоянной основе.<br>
<b>Класс B</b><br>
Класс B присваивается сотрудникам, которые считаются важными для локальных операций Фонда. Им разрешён доступ только к тем аномальным объектам, существам и явлениям, которые были подвергнуты карантину и мерам по блокировке возможного ментального или меметического воздействия. В случае нарушения условий содержания или враждебных действий против учреждения Фонда сотрудников класса B надлежит как можно скорее эвакуировать в заранее установленную и безопасную область вне данного учреждения.<br>
<b>Класс C</b><br>
Класс C присваивается сотрудникам с прямым доступом к большинству аномалий, не представляющих опасности или не проявляющих враждебности. Сотрудники класса C, прямо контактировавшие с потенциальными источниками ментального или меметического воздействия, могут быть подвергнуты обязательному карантину или психиатрическому обследованию, на усмотрение службы безопасности. В случае нарушения условий содержания или враждебных действий против учреждения Фонда небоевой персонал класса С должен или прибыть в безопасную зону учреждения, или, в случае массового нарушения условий содержания или другого катастрофического события, произвести эвакуацию, на усмотрение местной службы безопасности.<br>
<b>Класс D</b><br>
Класс D присваивается расходному персоналу, используемому для работ с крайне опасными аномалиями. Им запрещён какой-либо контакт с сотрудниками класса A или B. Сотрудники класса D обычно набираются из заключённых во всех странах мира, предпочтение отдается осужденным за насильственные преступления и особенно приговоренным к смертной казни. В случае крайней необходимости может быть приведён в исполнение Протокол 12, предусматривающий набор сотрудников из альтернативных источников - например, среди политических заключенных, беженцев и других гражданских лиц. Набранные сотрудники перевозятся в учреждения Фонда под достоверным предлогом. Сотрудников класса D необходимо регулярно подвергать обязательным психиатрическим обследованиями, а в конце месяца - или обрабатывать амнезиаком класса B (или более сильным), или ликвидировать, на усмотрение местной службой безопасности или медицинской службы. В случае возникновения в учреждении катастрофического события все местные сотрудники класса D подлежат немедленному уничтожению, если только местная служба безопасности не примет иное решение.<br>
<b>Класс E</b><br>
Класс E - это временное обозначение, присваиваемое полевым агентам и персоналу, участвующему в содержании, если во время постановки нового объекта на содержание они подверглись потенциально опасным эффектам. Сотрудников класса E необходимо как можно скорее поместить в карантин, после чего установить за ними наблюдение на предмет появления в их поведении, личности или физиологии потенциально вредоносных изменений. Такие сотрудники могут вернуться к исполнению своих обязанностей только после полного допроса, медицинского осмотра и психиатрического освидетельствования.<br>
##### Персонал учреждений
**Специалисты по содержанию**
Специалисты по содержанию в учреждениях Фонда играют две основные роли. В первую очередь команды содержания отправляются в места проявления подтвержденной аномальной активности, чтобы обезопасить потенциальный SCP-объект, обеспечить первоначальные условия его содержания и осуществить его транспортировку в ближайшее учреждение содержания Фонда.
Кроме того, инженеры и техники Фонда занимаются разработкой, усовершенствованием и обслуживанием камер, а также других средств, необходимых для содержания аномальных объектов, существ или явлений.<br>
**Научные сотрудники**<br>
Научные сотрудники отвечают за исследовательскую деятельность Фонда, они набираются из самых одарённых и квалифицированных ученых по всему миру. Среди них есть специалисты во всех возможных областях знаний, начиная с химии и ботаники и заканчивая такими малоизвестными и узкоспециализированными областями, как теоретическая физика и ксенобиология. Целью исследовательских проектов Фонда является лучшее понимание необъяснимых аномалий и принципов их действия.<br>
**Сотрудники службы безопасности**<br>
Служба безопасности учреждений (часто называемая просто "охраной") занимается обеспечением физической и информационной безопасности проектов, операций и персонала Фонда. Сотрудники службы безопасности набираются главным образом из военных, сотрудников правоохранительных органов и персонала исправительных учреждений. Они владеют многими видами оружия, а также обучены действовать в целом ряде чрезвычайных ситуаций, включая как нарушения условий содержания, так и враждебные действия. Сотрудники службы безопасности также ответственны за информационную безопасность, в частности, за защиту компьютерных систем учреждения от вторжения извне, а также за сохранность физических копий секретной документации. Кроме того, сотрудники службы безопасности часто оказываются первой линией обороны в случае враждебного вторжения в учреждение Фонда.<br>
**Члены групп реагирования**<br>
Группы реагирования или тактические группы - это высококвалифицированные и тяжеловооруженные воинские подразделения, сопровождающие команды по содержанию в тех случаях, когда приходится иметь дело с агрессивно настроенными аномальными сущностями или представителями враждебных связанных организаций. Также они занимаются охраной учреждений Фонда от враждебных вмешательств. Группы реагирования имеются во всех основных учреждениях Фонда и всегда готовы выступить по первому требованию.
##### Управленческий персонал
**Руководители Зон**<br>
Руководители Зон осуществляют управление основными учреждениями Фонда и являются самыми высокопоставленными сотрудниками в регионах их размещения. Они ответственны за непрерывное безопасное функционирование своего учреждения, содержание всех находящихся в нём аномалий, а также проведение связанных с ними проектов. Главы всех основных местных служб отчитываются перед руководителем Зоны, который, в свою очередь, отчитывается перед Советом O5.<br>
**Члены Совета O5**<br>
Совет O5 - это комитет руководителей Фонда высшего звена. Они обладают полным доступом ко всей информации, касающейся находящихся на содержании аномалий, осуществляют контроль за всеми глобальными операциями Фонда, а также занимаются долгосрочным стратегическим планированием. Учитывая важность их положения, членам Совета O5 не дозволяется контактировать с какими-либо аномальными объектами, существами или явлениями. Кроме того, личности всех членов Совета засекречены, используются только их числовые обозначения (с O5-1 по O5-13).<br>
**Администратор**<br>
[Данные удалены] 

### Интерфейс


Размеры элементов интерфейса будут рассчитаны, предположительно, на данные разрешения экрана:
- 144-360
- 480-720
- 1080-2к<br>
**Меню**<br>
Главное меню<br>
Меню паузы<br>
Меню исследований<br>
Меню карты<br>

**Статичные элементы**<br>
Элемент<br>
Элемент 2<br>

**Элементы ввода**<br>
Элемент<br>
Элемент 2<br>

**Динамические элементы**<br>
Элемент<br>
Элемент 2<br>



### Роадмап

Цели поставленные перед игрой для систематизирования всех хотелок в одном месте.
- Добавление интерфейса
- Сбор тестовой версии
- Выход в релиз


### Геймплей

Вид рабочего пространства игры:
1.

### Текстуры объектов

Описание всех текстур применяемых в игре.

### Изменения

Список изменений (включая номер и/или билд версии)

V.0.0.1 - Создание прототипа<br>
V.0.0.2 - Добавление материала и текстур<br>
V.0.0.3 - Изменение некоторых функций<br>
