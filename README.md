# “Acquire and leave”: Effects of startups acquisitions by digital ecosystems

The repository contains [online appendix](https://annastavniychuk.shinyapps.io/antitrust_authority_burden/) to the article [“Acquire and leave”: Effects of startups acquisitions by digital ecosystems](https://doi.org/10.29141/2218-5003-2023-14-5-6).

**Abstract**

Digital ecosystems penetrate many areas of modern life, they integrate many services and are growing partially through acquiring start-ups. These can lead to a rise of their market power, which in turn has caused the increased attention of antitrust regulators in recent years . The new changes into the Russian antitrust law contain the requirement for scrutiny for mergers above 7 billion of rubbles. This additional criterion is designed to include the acquisitions of startups by digital ecosystems that currently do not need to be announced to the Russian antitrust service. As for economic literature, there is no consensus on the way mergers with startups affect markets, in particular, venture capital market. The purpose of this work is to assess the effects of mergers of digital ecosystems with Russian startups in different niches of the venture investment in these niches. Methodologically, our study is based on economic theory and particularly on industrial organisation, antitrust economics; we also use econometrics while estimating causal inferences. We perform econometric analysis of panel data and matching to evaluate the effect of mergers of digital ecosystems with startups. In our quantitative analysis we use data collected from the website Rusbase, which gathers information on deals with Russian startups building primarily on open sources. In our study, we conclude that niches where digital ecosystems more actively purchase or invest in startups tend to be lower investments, smaller total and average purchase prices, which may indicate some washing out of investments in such niches. However, the effect we see may be present due to the changing popularity of niches and/or bringing forward of investor decisions, and not to the kill zone that is claimed to be one of the downsides of such mergers, since we observe a short-term increase in the number of investment decisions in a niche during the period when a startup is acquired by the digital ecosystem.

**For citation:** *Stavniychuk А.Y., Markova О.А. (2023). “Acquire and leave”: Effects of startups acquisitions by digital ecosystems. Upravlenets/ The Manager, vol. 14, no. 5, pp. 83–105. [https://doi.org/10.29141/2218-5003-2023-14-5-6](https://doi.org/10.29141/2218-5003-2023-14-5-6)*

---

We encourage the use of our collected database in any research, but please cite the source.

Contact [annastavnychuk@gmail.com](mailto:annastavnychuk@gmail.com)

The file `rusbase_data.csv` contains data on deals (purchases and investments) with Russian startups from January 2010 to April 2023, collected from the website of the Rusbase website [https://rb.ru/deals/](https://rb.ru/deals/). The Rusbase portal collects data from open sources and provide detailed information on deals with Russian startups covered in the media. 

The file `rusbase_data.csv` contains cariables:

- **Startup details:**
   - startup_url -- startup page on the Rusbase portal
   - startup_name -- startup name
   - starlup_website -- startup website
   - startup_niche -- startup niche
   - startup_date_foundation -- year the startup was founded
   - startup_region -- startup region
   - startup_description -- description of the startup
- **Transaction details:**
   - deal_type -- deal type (purchase or investment)
   - deal_date -- deal date (different formats: it can be either the full date accurate to the day, or only the year of the deal)
   - deal_price -- deal price (different formats: can be either dollars or millions of dollars)
   - news_url -- news about the deal
- **Investor/buyer details:**
   - investor_name -- name of the investor/buyer company
   - investor_url -- website of the investor/buyer company
- **Variables created by the article authors, based on data preprocessing:**
   - tidy_deal_date_month -- deal month
   - tidy_deal_date_day -- deal day
   - tidy_deal_date_year -- deal year
   - tidy_startup_year_foundation -- year the startup was founded
   - tidy_deal_price -- deal price (USD)
   - tidy_deal_price_per_investor -- if the deal has several buyers/investors, then the deal price is divided equally in proportion to the number of buyers/investors
   - treatment_vk -- binary variable equal to one if VK is an investor/buyer company
   - treatment_yandex -- binary variable equal to one if Yandex is an investor/buyer company
   - treatment_sber -- binary variable equal to one if Sber is an investor/buyer company
   - treatment_mts -- binary variable equal to one if MTS is an investor/buyer company
   - treatment -- a binary variable equal to one if any of the digital ecosystems (VK, Yandex, Sber, MTS) is an investor/buyer company

---

# «А ты купи и отойди»: эффекты от сделок экономической концентрации цифровых экосистем со стартапами
 
Репозиторий содержит [онлайн-приложение](https://annastavniychuk.shinyapps.io/antitrust_authority_burden/) к статье [«А ты купи и отойди»: эффекты от сделок экономической концентрации цифровых экосистем со стартапами](https://doi.org/10.29141/2218-5003-2023-14-5-6).

**Аннотация**

Цифровые экосистемы объединяют комплекс сервисов и разрастаются в том числе за счет поглощения стартапов. Это потенциально может приводить к росту их рыночной власти, а следовательно, вызывает беспокойство антимонопольных регуляторов. Новые поправки в антимонопольное законодательство содержат дополнительный критерий стоимости сделки, который призван обеспечить необходимость согласования с антимонопольным органом. При этом в литературе отсутствует консенсус относительно того, как именно поглощение стартапов цифровыми экосистемами влияет на разные рынки, в частности рынок венчурных инвестиций. Статья посвящена оценке эффектов от сделок экономической концентрации цифровых экосистем с российскими стартапами для разных ниш рынка венчурного финансирования. Методологическую основу исследования составили теория организации отраслевых рынков и положения антимонопольного регулирования. Применялись эконометрический анализ панельных данных и метод мэтчинга. Информационную базу составили данные о сделках с российскими стартапами, представленные на сайте Rusbase. Сделан вывод о том, что рыночные ниши, в которых цифровые экосистемы сравнительно активнее совершают сделки (покупки и вложения), характеризуются более низкими объемами инвестиций, меньшим суммарным и средним размером покупок, что может свидетельствовать о некотором «вымывании» инвестиций. Вместе с тем это может быть связано с изменением популярности ниш и переносом решений инвесторов, а не с возникающей «зоной отчуждения» (kill zone) вокруг таких поглощений, поскольку в этот период наблюдается краткосрочный рост сделок в рыночной нише.

**Для цитирования:** *Stavniychuk А.Y., Markova О.А. (2023). “Acquire and leave”: Effects of startups acquisitions by digital ecosystems // Управленец. Т. 14, № 5. С. 83–105. [https://doi.org/10.29141/2218-5003-2023-14-5-6](https://doi.org/10.29141/2218-5003-2023-14-5-6) EDN: LLABZC.*

---

Мы максимально приветствуем использование собранной нами базы данных в любых исследованиях, однако просим указывать источник. 

Контакт для связи [annastavnychuk@gmail.com](mailto:annastavnychuk@gmail.com)

В файле `rusbase_data.csv` представлены данные о сделках (покупках и инвестициях) с российскими стартапами с января 2010 по апрель 2023 года, собранные с сайта издания Rusbase [https://rb.ru/deals/](https://rb.ru/deals/). Портал Rusbase собирает данные из открытых источников и предоставляет подробную информацию о сделках с российскими стартапами, освещаемых в СМИ.

Файл `rusbase_data.csv` содержит переменные:

- **Данные о стартапе:**
  - startup_url -- страница стартапа на портале Rusbase
  - startup_name -- название стартапа
  - starlup_website -- сайт стартапа 
  - startup_niche -- ниша стартапа 
  - startup_date_foundation -- год основания стартапа
  - startup_region -- регион стартапа 
  - startup_description -- описание стартапа
- **Данные о сделке:** 
  - deal_type -- тип сделки (покупка или инвестиция)
  - deal_date -- дата сделки (разный формат: может быть как полная дата с точностью до дня, так и только год сделки)
  - deal_price -- цена сделки (разный формат: может быть как долл., так и млн. долл.)
  - news_url -- новость о сделке 
- **Данные об инвесторе / покупателе:** 
  - investor_name -- название компании-инвестора/покупателя
  - investor_url -- сайт компании-инвестора/покупателя
- **Переменные, созданные авторами статьи, на основе предварительной обработки данных:** 
  - tidy_deal_date_month -- месяц сделки 
  - tidy_deal_date_day -- день сделки 
  - tidy_deal_date_year -- год сделки 
  - tidy_startup_year_foundation -- год основания стартапа
  - tidy_deal_price -- цена сделки (долл.)
  - tidy_deal_price_per_investor -- если у сделки несколько покупателей / инвесторов, то цена сделки делится поровну пропорционально количеству покупателей / инвесторов
  - treatment_vk -- бинарная переменная, равная единице, если VK является компанией-инвестором/покупателем
  - treatment_yandex -- бинарная переменная, равная единице, если Яндекс является компанией-инвестором/покупателем
  - treatment_sber -- бинарная переменная, равная единице, если Сбер является компанией-инвестором/покупателем
  - treatment_mts -- бинарная переменная, равная единице, если МТС является компанией-инвестором/покупателем
  - treatment -- бинарная переменная, равная единице, если любая из цифровых экосистем (VK, Яндекс, Сбер, МТС) является компанией-инвестором/покупателем
