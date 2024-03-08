
# Awesome Quant [! [Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github. com/sindresorhus/awesome)

Starannie dobrany indeks zasobów związanych z Quant w języku chińskim.

## Spis treści

* Źródła danych](#Data Sources)
* [Baza danych](#Database)
* [Quantitative Trading Platform](#Quantitative Trading Platform)
* [Strategia](#Strategy)
* [Backtest](#Backtest)
* [Trading API](#Trading api)
* [Programowanie](#Programming)
    * [Python](#python)
    * [R](#r)
    * [C++](#c)
    * [Julia](#julia)
* [Forum](#forum)
* [Książki](#books)
* [Eseje](#essays)
* [Polityka](#policy)
* [Źródła warte uwagi](#Noteworthy Sources)
* [Indeks innych źródeł danych](#Index of Other Quant Sources)

## Źródła danych
* [TuShare](http://tushare.org/) - chiński pakiet interfejsu danych finansowych
* [Quandl](https://www.quandl.com/) - Międzynarodowe dane finansowe i ekonomiczne
* [Wind Info - Ekonomiczna baza danych](http://www.wind.com.cn/NewSite/edb.html) - płatne
* [RESET Data - Home](http://www.resset.cn/) - za opłatą
* [Cathay Pacific Data Service Centre](http://www.gtarsc.com/Home) - płatne
* [Hang Seng API](https://open.hscloud.cn/cloud/open/apilibrary/queryLibraryMenu.html?parent_id=100313&menu_id=100307) - płatne
* [Bloomberg API](https://www.bloomberglabs.com/api/libraries/) - Opłata pobierana
* [Digital Library Financial Data and In-depth Analytics API Service](http://developer.chinascope.com/) - Płatne
* [Źródła danych historycznych](http://quantpedia.com/Links/HistoricalData) - indeks źródeł danych
* [Python TDX Data Interface](https://github.com/rainx/pytdx) - darmowe źródło danych TDX
* [fooltrader](https://github.com/foolcage/fooltrader) - duży projekt ilościowy open source, utrzymują zintegrowane źródło danych z całego rynku.
* [zvt](https://github.com/zvtvz/zvt) - ZVT to projekt ilościowy napisany po przemyśleniu na podstawie fooltradera, który zawiera skalowalny rejestrator danych, api, obliczenia czynników, selekcję akcji, backtesting, pozycjonowanie dla niskiej i średniej częstotliwości, wielopoziomową, wieloprzedmiotową, ogólnorynkową analizę i ramy handlowe.
* [JoinQuant/jqdatasdk](https://github.com/JoinQuant/jqdatasdk) - jqdatasdk to zestaw SDK, który zapewnia użytkownikom dostęp do zagregowanych, szerokich danych finansowych.
* [MiBasket's RQData data interface](https://www.ricequant.com/introduce_rqdata) - Charge for it
* AkShare](https://github.com/jindaxiang/akshare) - darmowa biblioteka interfejsu danych finansowych typu open source, obecnie zawiera najbardziej kompletny interfejs danych w chińskiej domenie.

## Baza danych

* [manahl/arctic: wysokowydajny magazyn danych dla szeregów czasowych i danych tickowych](https://github.com/manahl/arctic) - wysokowydajny szereg czasowy i tickowy oparty na mongodb i pythonie. datastore
* [kdb | The Leader in High-Performance Tick Database Technology | Kx Systems](https://kx.com/) - Oparte na opłatach rozwiązanie dla wysokowydajnych baz danych serii finansowych
* [MongoDB Blog](http://blog.mongodb.org/post/65517193370/schema-design-for-time-series-data-in-mongodb) - Przechowywanie danych szeregów czasowych za pomocą mongodb
* [InfluxDB - Time-Series Data Storage | InfluxData](https://www.influxdata.com/time-series-platform/influxdb/) - Rozproszone szeregi czasowe napisane przez Go Baza danych.
* OpenTSDB/opentsdb: skalowalna, rozproszona baza danych szeregów czasowych](https://github.com/OpenTSDB/opentsdb) - baza danych szeregów czasowych oparta na HBase.
* [kairosdb/kairosdb: Szybka skalowalna baza danych szeregów czasowych](https://github.com/kairosdb/kairosdb) - Baza danych szeregów czasowych oparta na Cassandrze.
* [timescale/timescaleb: Baza danych szeregów czasowych o otwartym kodzie źródłowym zoptymalizowana pod kątem szybkiego pozyskiwania i złożonych zapytań. Opracowana na podstawie PostgreSQL, spakowana jako rozszerzenie.]() - Oparta na Cassandrze. spakowane jako rozszerzenie.](https://github.com/timescale/timescaledb) - Baza danych szeregów czasowych oparta na PostgreSQL.

## Platforma handlu ilościowego

* [JoinQuant - zagregowana, szeroka platforma handlu ilościowego](https://www.joinquant.com/) - oparta na Pythonie platforma handlu ilościowego online.
* [YouMine - Tonglian Quant Lab](https://uqer.io/home/) - oparta na Pythonie internetowa platforma handlu ilościowego.
* [Ricequant Quantitative Trading Platform](https://www.ricequant.com/) - internetowa platforma handlu ilościowego z obsługą Pythona i Javy.
* [Nuggets Quant](http://www.myquant.cn/) - ilościowa platforma handlowa obsługująca C/C++, C#, MATLAB, Python i R.
* [Auto-Trader](http://www.atrader.com.cn/portal.php) - ilościowa platforma transakcyjna oparta na MATLAB.
* [MultiCharts China Edition - oprogramowanie do handlu programowanego](https://www.multicharts.cn/)
* [BotVS - pierwsza platforma ilościowa obsługująca tradycyjne kontrakty futures i kapitałowe papiery wartościowe z walutami cyfrowymi](https://www.botvs.com/)
* [Tradeblazer(TB) - Trade Blazer](http://www.tradeblazer.net/) - platforma oprogramowania do programowego handlu kontraktami futures
* [MetaTrader 5](https://www.metatrader5.com/en) - platforma transakcyjna dla wielu aktywów
* [BigQuant](https://bigquant.com) - platforma sztucznej inteligencji/uczenia maszynowego skupiająca się na inwestycjach ilościowych
* [TqSdk](https://github.com/shinnytech/tqsdk-python) - pakiet rozwoju ilościowego Python, darmowe kontrakty terminowe, opcje, dane giełdowe, wsparcie handlu na żywo/historycznego backtestingu.
* [Nutrino](https://guorn.com/) - platforma, której główną cechą jest selekcja akcji + analiza ilościowa, większość operacji ilościowych i backtestingowych można wykonać bez pisania kodów.

## Strategia
* [JoinQuant聚宽: Quantitative Learning Materials, Classic Trading Strategies, Introduction to Python - 雪球](https://xueqiu.com/8287840120/65009358)
* [myquant/strategy: Nuggets Strategy Collection](https://github.com/myquant/strategy)
* [Index of UMine Community Content](https://uqer.io/community/share/58243e7d228e5b91df6d5d19)
* [RiceQuant myquant quantitative community summary of excellent strategies and research since April 2016](https://www.ricequant.com/community/topic/1863//3)
* [Snowball Stock Picks](https://xueqiu.com/9796081404)
* [botvs/strategies: quantitative trading with Javascript OR Python](https://github.com/botvs/strategies)

## Backtesting
* [Zipline](https://github.com/quantopian/zipline) - framework do backtestingu w Pythonie
* [pyalgotrade](https://github.com/gbeced/pyalgotrade) - oparty na zdarzeniach framework do backtestingu dla Pythona
* [pyalgotrade-cn](https://github.com/Yam-cn/pyalgotrade-cn) - Pyalgotrade-cn dodaje historyczny backtesting akcji A do oryginalnego pyalgotrade i integruje tushare, aby zapewnić notowania w czasie rzeczywistym.
* [ricequant/rqalpha](https://github.com/ricequant/rqalpha) - RQalpha: open source'owy silnik Ricequant do backtestingu oparty na Pythonie.
* [quantdigger](https://github.com/QuantFans/quantdigger) - oparty na Pythonie system ilościowego backtestingu, zapożyczony z głównego nurtu komercyjnego oprogramowania (takiego jak TB, piramida) zwięzła składnia strategii.
* [pyktrader](https://github.com/harveywwu/pyktrader) - platforma handlowa w Pythonie oparta na interfejsie pyctp i wykorzystująca eventEngine vnpy, wykorzystująca tkinter jako GUI.
* [QuantConnect/Lean](https://github.com/QuantConnect/Lean) - Lean Algorithmic Trading Engine firmy QuantConnect (C#, Python, F#, VB, Java).
* QUANTAXIS](https://github.com/yutiansut/QUANTAXIS) - QUANTAXIS Quantitative Financial Strategy Framework - rozwiązanie dla małych i średnich zespołów strategicznych.
* [Hikyuu](http://hikyuu.org) - oparty na Python/C++ framework do ilościowych badań tradingowych.
* [StarQuant](https://github.com/physercoe/starquant) - Zintegrowany system/platforma do ilościowego testowania transakcji oparta na Python/C++.

## API handlowe
* [Shanghai Futures Information Technology Co., Ltd CTP API](http://www.sfit.com.cn/5_2_DocumentDown.htm) - API dostarczane przez giełdę kontraktów terminowych.
* [Pegasus Fast Trading Platform - Shanghai Financial Futures Information Technology Co. Ltd](http://www.cffexit.com.cn/static/3000201.html) - Pegasus
* [Dalian Feicuang Information Technology Co Ltd](http://www.dfitc.com.cn/portal/cate?cid=1364967839100#1) - Feicuang
* [vnpy](https://github.com/vnpy/vnpy) - oparta na Pythonie platforma rozwoju platform transakcyjnych typu open source
* [QuantBox/XAPI2](https://github.com/QuantBox/XAPI2) - ujednolicony interfejs notowań i handlu w wersji 2
* [easytrader](https://github.com/shidenggui/easytrader) - zapewnia brokera Huatai / skarb prowizji / galaxy / guangfa / fundusz śnieżki, automatyczny zaprogramowany handel akcjami, ilościowe komponenty handlowe
* [StrategyEasy](http://www.iguuu.com/e) ([SDK](https://github.com/sinall/StrategyEase-Python-SDK)) - zarządza klientami handlowymi, zapewnia API RESTFul oparte na protokole HTTP; główne internetowe platformy handlu ilościowego. Rozwiązania do automatyzacji strategii
* [IB API | Interactive Brokers](https://www.interactivebrokers.com.hk/cn/index.php?f=5234&ns=T) - API transakcyjne dla PCCW Securities
* [FutunnOpen/futuquant](https://github.com/FutunnOpen/futuquant) - API platformy Futuquant.


## Programowanie

### Python
#### Instalacja
* [Anaconda](https://www.continuum.io/downloads) - zalecane do pobrania i zainstalowania przez [Tsinghua University Mirror](https://mirrors.tuna.tsinghua.edu.cn/help/anaconda/)
* [Python Extension Packages for Windows - Christoph Gohlke](http://www.lfd.uci.edu/~gohlke/pythonlibs/) - Użytkownicy Windows mogą pobrać stąd prekompilowane pakiety wielu bibliotek Pythona.

#### Tutoriale
* Python | Codecademy](https://www.codecademy.com/learn/python)
* [Playing with Data in Python - Nanjing University | Coursera](https://www.coursera.org/learn/hipython)
* [Introduction to Data Science in Python - University of Michigan | Coursera](https://www.coursera.org/learn/python-data-analysis)
* [Samouczek Pythona - dokumentacja Python 3.5.2](https://docs.python.org/3/tutorial/)
* [Python for Finance](https://book.douban.com/subject/25921015/)
* [Myślenie algorytmiczne](https://www.coursera.org/learn/algorithmic-thinking-1) - Szkolenie z myślenia algorytmicznego w Pythonie

#### biblioteka
* [awesome-python: Wyselekcjonowana lista niesamowitych frameworków, bibliotek, oprogramowania i zasobów Pythona](https://github.com/vinta/awesome-python)
* [pandas](http://pandas.pydata.org) - podstawa Pythona do analizy danych
* [pyql: Cython QuantLib wrappers](https://github.com/enthought/pyql)
* [ffn](http://pmorissette.github.io/ffn/quick.html) - ocena wydajności
* [ta-lib: Python wrapper dla TA-Lib (http://ta-lib.org/)] (https://github.com/mrjbq7/ta-lib) - wskaźniki techniczne
* [StatsModels: Statystyka w Pythonie - dokumentacja statsmodels](http://statsmodels.sourceforge.net/) - Popularne modele statystyczne
* [arch: ARCH models in Python](https://github.com/bashtage/arch) - szeregi czasowe
* [pyfolio: Portfolio and risk analytics in Python](https://github.com/quantopian/pyfolio) - ocena ryzyka portfela
* [twosigma/flint: A Time Series Library for Apache Spark](https://github.com/twosigma/flint) - biblioteka szeregów czasowych na Apache Spark
* PyFlux](https://github.com/RJT1990/pyflux) - modelowanie szeregów czasowych w Pythonie (częstotliwościowe i bayesowskie)  

### R

#### Instalacja
* [The Comprehensive R Archive Network](https://mirrors.tuna.tsinghua.edu.cn/CRAN/) - Pobierz i zainstaluj z chińskiego mirrora Tsinghua.
* RStudio](https://www.rstudio.com/products/rstudio/download/) - wspólna platforma programistyczna R do pobrania.

#### Samouczki
* [Free Introduction to R Programming Online Course](https://www.datacamp.com/courses/free-introduction-to-r) - datacamp online learning
* [R Programming - Johns Hopkins University | Coursera](https://www.coursera.org/learn/r-programming)
* [Intro to Computational Finance with R](https://www.datacamp.com/community/open-courses/computational-finance-and-financial- econometrics-with-r) - Obliczeniowa analiza finansowa z R

#### biblioteki
* [CRAN Task View: Empirical Finance](https://cran.r-project.org/web/views/Finance.html) - oficjalne zestawienie pakietów związanych z finansami dla R w CRAN.
* [qinwf/awesome-R: A curated list of awesome R packages, frameworks and software.](https://github.com/qinwf/awesome-R) - Pakiety R dla niesamowitości.

### C++
#### Samouczki
* Programowanie w C++](http://www.xuetangx.com/courses/course-v1:PekingX+04831750.1x+2015T1/about) - Guo Wei, Peking University.
* [Linux-based C++](http://www.xuetangx.com/courses/course-v1:TsinghuaX+20740084X+sp/about) - Qiao Lin, Uniwersytet Tsinghua
* Programowanie obiektowe (C++)](http://www.xuetangx.com/courses/course-v1:TsinghuaX+30240532X+sp/about) - Xu Mingxing, Uniwersytet Tsinghua
* Wzorce projektowe C++ i wycena instrumentów pochodnych](https://book.douban.com/subject/1485468/) - Wzorce projektowe C++
* [C++ Reference - cppreference.com](http://en.cppreference.com/w/cpp) - dokumentacja online

Biblioteki ####
* [fffaraz/awesome-cpp: A curated list of awesome C/C++ frameworks, libraries, resources, and shiny things.](https://github.com/fffaraz/awesome -cpp) - wyselekcjonowane biblioteki C++
* [rigtorp/awesome-modern-cpp: Zbiór zasobów na temat nowoczesnego C++](https://github.com/rigtorp/awesome-modern-cpp) - organizacja nowoczesnych bibliotek C++.
* [QuantLib: wolna/otwarta biblioteka dla finansów ilościowych](http://quantlib.org/index.shtml)
* [libtrading/libtrading: Libtrading, biblioteka łączności handlowej o bardzo niskich opóźnieniach dla C i C++]. (https://github.com/libtrading/libtrading)

### Julia
#### Samouczki
* [Learning Julia](http://julialang.org/learning/) - oficjalna kompilacja
* [QUANTITATIVE ECONOMICS with Julia](http://quant-econ.net/_static/pdfs/jl-quant-econ.pdf) - Laureat ekonomicznego Nobla Thomas Sargent uczy [Julia](http:// julialang.org/) w zakresie ekonomii ilościowej.

#### biblioteka
* [Quantitative Finance in Julia](https://github.com/JuliaQuant) - głównie prace w toku, dla zainteresowanych!

### Fora programistyczne
- Stack Overflow](http://stackoverflow.com/) - tag dla odpowiedniego języka
- SegmentFault](https://segmentfault.com/) - tagi dla odpowiednich języków

### Szkolenie online z umiejętności programowania

* [Solve Programming Questions | HackerRank](https://www.hackerrank.com/domains) - Zawiera powszechnie używane języki (C++, Java, Python, Ruby, SQL) i powiązane techniki aplikacji komputerowych (algorytmy, struktury danych, matematyka, AI, Linux Shell, systemy rozproszone, wyrażenia regularne, bezpieczeństwo).
* [LeetCode Online Judge](https://leetcode.com/) - Szkolenie online z programowania w językach C, C++, Java, Python, C#, JavaScript, Ruby, Bash, MySQL.

## Forum.
* [Quantitative Finance StackExchange](http://quant.stackexchange.com/) - forum ilościowe dla serii stackexchange.
* [JoinQuant Community](https://www.joinquant.com/community) - Społeczność JoinQuant
* [YouMine Community](https://uqer.io/community/list) - społeczność YouMine.
* [RiceQuant Quantitative Community](https://www.ricequant.com/community/) - społeczność RiceQuant Quantitative Community
* [Nuggets Quantitative Community](http://forum.myquant.cn/) - Społeczność ilościowa Nuggets
* [Tsinghua University Student Economic and Financial Forum](http://forum.thuquant.com/) - Organizowane przez Tsinghua University Student Financial Data and Quantitative Investment Association.

## Książki
* [My Life as a Quant: Reflections on Physics and Finance](http://www.amazon.com/My-Life-Quant-Reflections-Physics/dp/0470192739) - W książce My Life as a Quant a Quant, Emanuel Derman przeżywa swoją ekscytującą podróż jako jeden z pierwszych fizyków cząstek wysokoenergetycznych, który wyemigrował na Wall Street.
* [Quantitative Trading](https://book.douban.com/subject/25878150/) - Teoria inwestycji ilościowych autorstwa Ernesta P. Chana.
* [Quantitative Investing and Hedge Fund Series: Volatility Trading](https://book.douban.com/subject/25711100/)
* [Podążanie za trendem](https://book.douban.com/subject/19990593/)
* [Wnioskowanie statystyczne](https://book.douban.com/subject/1464795/) - Wprowadzenie do wnioskowania statystycznego
* [Cała statystyka nieparametryczna](https://book.douban.com/subject/4251603/) - Wprowadzenie do statystyki nieparametrycznej
* [The Elements of Statistical Learning](https://book.douban.com/subject/3294335/) - Eksploracja danych, wnioskowanie i przewidywanie
* [Analiza finansowych szeregów czasowych](https://book.douban.com/subject/4719140/) - Analiza szeregów czasowych autorstwa Ruey S. Tsay
* Opcje, kontrakty terminowe i inne instrumenty pochodne](https://book.douban.com/subject/6127888/) - Opcje, kontrakty terminowe i inne instrumenty pochodne



## Praca dyplomowa
* [awesome-quant/papers.md](https://github.com/thuquant/awesome-quant/blob/master/papers.md)

## Awesome-quant źródła informacji
* [Quantitative Finance arxiv](https://arxiv.org/archive/q-fin)
* [snowballengineer1](http://xueqiu.com/engineer) - konto związane z kwestiami ilościowymi na finansowym portalu społecznościowym Snowball.
* [Ricequant Quantitative](http://xueqiu.com/ricequant) - konto Snowball dla platformy ilościowej Ricequant.
* [Quant Bro - Uqer Uqer](http://xueqiu.com/4105947155) - konto Snowball dla platformy ilościowej Uqer.
* [Kuanke (Quant) - Index - 知乎](https://www.zhihu.com/topic/19557481)
* Inwestycje ilościowe i uczenie maszynowe - numer publiczny wechat
* THU Quantitative Association - 微信公众号
* U-Mine Quant Lab - 微信公众号
* Ricequant - 微信公众号
* Lumine Quantitative All View - numer publiczny WeChat


## Polityka
* [Chińska Komisja Nadzoru Papierów Wartościowych](http://www.csrc.gov.cn/pub/newsite/)
* [Rejestracja egzaminu - Chińskie Stowarzyszenie Papierów Wartościowych](http://www.sac.net.cn/cyry/kspt/ksbm/) - Rejestracja kwalifikacji papierów wartościowych
* [China Securities Investment Funds Association](http://www.amac.org.cn/) - Wewnątrz odpowiednich przepisów wejście do edukacji i rejestracji kwalifikacji praktyków
* [Dalian Commodity Exchange](http://www.dce.com.cn/)
* [Shanghai Futures Exchange Home](http://www.shfe.com.cn/)
* [Strona internetowa giełdy towarowej w Zhengzhou](http://www.czce.com.cn/portal/index.htm)
* [Shanghai Stock Exchange](http://www.sse.com.cn/)
* [Shenzhen Stock Exchange](http://www.szse.cn/)

# Indeks innych zasobów Quant

* [Quantitative Finance Reading List - QuantStart](https://www.quantstart.com/articles/Quantitative-Finance-Reading-List#general-quant- finance-reading)
* [Master reading list for Quants, MFE (Financial Engineering) students | QuantNet Community](https://www.quantnet.com/threads/master-reading- list-for-quants-mfe-financial-engineering-students.535/)

# Inne niesamowite listy
* angielska wersja awesome-quant [wilsonfreitas/awesome-quant: A curated list of insanely awesome libraries, packages and resources for Quants (Quantitative Finanse)](https://github.com/wilsonfreitas/awesome-quant)
* Inne niesamowite listy [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness).
* Jeszcze więcej list [awesome](https://github.com/sindresorhus/awesome).
* Kolejna lista [list](https://github.com/jnv/lists) * WTF!
* WTF! [awesome-awesome-awesome](https://github.com/t3chnoboy/awesome-awesome-awesome).
* Analityka [awesome-analytics](https://github.com/onurakpolat/awesome-analytics).
