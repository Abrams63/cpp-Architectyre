# c-Architectyre
Roadmap 
* **C++**
* стандарт
* Comeau
* 1TBS
* Страустрап/D&E/Джосаттіс/Вандервуд
* Дьюхерст/Мейєрс/Саттер
* RAII/copy-and-swap/exception-safety
* Правило п'яти
* Александреску/Абрахамс-Гуртовий
* type erasure
* CRTP
* NVI
* SFINAE
* Koenig lookup
* Duff's device
* Boost
* Сік-Ламсдейн/Карлссон
* TR on C++ performance
* тест Степанова
* forwarding problem/move semantics
* SPECS
* GotW
* Meyer's singleton
* cppgm
* **Компілятори С++**
* особливості реалізації стандарту
* обмеження реалізації
* інтринсики
* Відмінності стандартних бібліотек (контейнери, rand)
* ABI
* реалізація віртуальних функцій, віртуального успадкування, винятків, RTTI, switch, покажчиків на функції та методи
* оптимізації
* copy elision (RVO, NRVO)
* sizeof на різних платформах
* Дефайни компілятора та середовища
* __declspec
* ключі компілятора
* empty-base optimization
* Статична та динамічна лінківка
* манглінг
* розподілена компіляція
* precompiled header
* single compilation unit
* (strict) aliasing/restrict
* inline/_forceinline
* volatile
* швидке обчислення математичних функцій через бітхаки
* linkers & loaders by Levine
* **Мультитредність**
* Обідаючі філософи
* deadlock/livelock/race condition/starvation
* атомарність
* lock інструкції процесора
* Memory model/barrier/ordering
* CAS або LL/SC
* wait/lock/obstruction-free
* ABA problem
* написання lock-free контейнерів
* spin-lock
* TLS/per-thread data
* Закон Амдала
* OpenMP
* MPI
* map-reduce
* critical section/mutex/semaphore/condition variable
* WaitForSingleObject/WaitForMultipleObjects
* green thread/coroutine
* pthreads
* future/deferred/promise
* модель акторів
* parameter server
* RDD (as seen in sparks)
* downpour SGD
* wait-free
* stackful vs stackless
* **Мова асемблера**
* Зубків/Хайд/Дреппер/Касперський/Фог/Абраш
* x86
* FPU/MMX/SSEn/AVX
* AT&T та Intel-синтаксис
* masm32
* макроси
* стек
* купа / менеджери купи
* Угоди виклику
* hex-коди
* машинне подання даних
* IEEE754
* little/big endian
* SIMD
* апаратні винятки
* переривання
* Віртуальна пам'ять
* реверсинг
* Зрив стеку та купи
* return oriented programming
* alphanumeric shellcode
* L1/L2/RAM/page fault та їх таймінг
* мова асемблера ARM
* **Апаратне забезпечення**
* Хоровіц-Хілл/Тітце-Шенк/Від фізики до Сі від panchul
* напівпровідникова електроніка/спінтроніка/фотоніка
* транзистор
* тригер
* схемотехніка
* мікрокод
* технологія створення процесорів
* logic synthesis
* static timing analysis
* FPGA
* Verilog/VHDL/SystemC
* SISAL
* Arduino
* пристрої пам'яті (ROM → EEPROM, RAM, SSD, HDD, DVD)
* RISC/CISC
* Flynn's taxonomy ([SM]I[SM]D)
* принстонський та гарвардський підхід
* архітектури процесорів
* архітектури x86
* VID/PID
* **Процесори**
* конвеєризація
* hyper-threading
* алгоритм томасуло
* спекулятивне виконання
* static/dynamic branch prediction
* Префетчинг
* множинний асоціативний кеш
* кеш-лінія/кеш-промах
* такти
* кільця захисту
* пам'ять у мультипроцесорних системах (SMP/NUMA)
* Таймінг пам'яті
* intel optimization manuals
* performance counters
* **Дискретна математика**
* K2
* Теорема Посту
* схеми
* кінцеві автомати (ДКА та НДКА)
* автомат Калашнікова
* клітинні автомати
* **Обчислюваність**
* машина Тьюринга
* нормальні алгоритми Маркова
* машина Поста
* діофантові рівняння Матіясевича
* лямбда-функції Черча
* частково рекурсивні функції Кліні
* комбінаторне програмування Шейнфінкелю
* Brainfuck
* еквівалентність тьюрингових трясин
* проблема зупинки та самозастосовності
* рахунковість безлічі обчислюваних функцій
* RAM-машина
* алгоритм Тарського
* SAT/SMT-солвери
* теорія формальних систем
* Interactive proofs
* Теорема Левіна-Кука
* 3SAT
* PSPACE = NPSPACE
* #P
* **Мови програмування**
* Граматики
* ієрархія Хомського
* Теорема Майхілла-Нероуда
* лема про накачування та лема Огдена
* алгебра Кліні
* НДКА → ДКА
* алгоритмічно нерозв'язні завдання у формальних мовах
* Драгонбук
* Фрідл
* регекспи та їх складність
* PCRE
* БНФ
* Boost.Spirit + Karma + Qi / Ragel
* LL
* LR/SLR/LALR/GLR
* PEG/packrat
* yacc/bison/flex/antlr
* Статичний аналіз коду
* компіляція/декомпіляція/обфускація/деобфускація
* Clang/LLVM/XMLVM/Emscripten
* GCCXML
* OpenC++
* Побудова віртуальних машин
* JiT/AoT/GC
* DSL/DSEL
* on-stack replacement
* type checking/type inference алгоритми
* CYK parser
* Advanced compiler design and implementation by Muchnick
* **Алгоритми та комбінаторна оптимізація**
* Кормен/Скієна/Седжвік/Кнут/Ахо-Хопкрофт-Ульман/Пападимитріу/Шрайвер-Голдберг/Препарата-Шеймос/e-maxx.ru
* структури даних, алгоритми, складність
* символіка Ландау
* теорема Акра-Баззі
* time-space tradeoff
* класи складності
* NP-повні завдання
* КМП
* графи та дерева
* потоки в мережах
* матриця Кірхгофа
* дерева пошуку (особливо RB-дерево та B-дерево)
* occlusion detection
* купа
* хеш-таблиці та ідеальний хеш
* мережі Петрі
* алгоритм російського селянина
* метод Карацуби та матричне множення Винограда-Штрассена
* сортування
* жадібні алгоритми та матроїди
* динамічне програмування
* лінійне програмування
* diff-алгоритми
* рандомізовані алгоритми та алгоритми нечіткого пошуку
* псевдовипадкові числа
* нечітка логіка
* gusfield (suffix tree, string alignment)
* motif search
* scanning line
* cache oblivious
* Funnel sorting
* VEB-layout
* коренева оптимізація
* алгоритми для динамічних графів
* моделі обчислення (RAM-machine/pointer machine/decision trees і т.д.)
* алгоритми в ієрархіях пам'яті/стрімінгові алгоритми
* time forward processing
* range & rank
* LSM-trees
* buffered ab-trees
* toku trees
* персистентні структури
* succint-структури
* lossy-струтури (bloom/bloomier filter, hash-tables with false positives)
* locality sensitive hashing
* space-time tradeoff в хеш-таблицях
* scheduling strategies
* **Чисельні методи**
* Дихотомія / метод Ньютона
* інтер- та екстраполяція
* сплайни
* метод Гауса / Якобі / Зейделя
* QR та LU-декомпозиція
* SVD
* МНК
* методи Рунге-Кутти
* метод Адамса
* Формули Ньютона-Котеса
* метод Ритца
* метод Бубнова-Галеркіна
* метод кінцевих різниць/елементів
* FFT/STFT
* збіжність та стійкість
* l-bfgs та інші квазиньютонівські методи
* adagrad
* PARAFAC
* cassowary
* interior point methods
* варіаційні методи для байєсовського висновку
* Nesterov
* автоматичне диференціювання
* alternating least squares
* What every computer scientist should know o floating point arithmetics by Goldberg
* Nocedal & Wright/Boyd & Vandenberghe
* **Машинне навчання**
* Тібширані/Bishop
* підходи до моделювання AI
* перенавчання/кросвалідація
* байєсовські мережі
* нейромережі
* мережі Кохонена
* Restricted Boltzmann machine
* градієнтний спуск/hill climbing
* стохастична оптимізація (метод Монте-Карло, метод відпалу, генетичні алгоритми, мурашині алгоритми)
* SVM
* gradient boosting
* кластерний аналіз
* Метод основних компонент
* LSH
* Навчання з підкріпленням
* MDP
* Information retrieval/data mining/natural language processing
* машинний зір
* Szeliski
* OpenCV
* image processing
* OCR
* фільтри Собеля
* каскад Хаара
* Viola-Jones framework
* SURF
* Введення в психофізіологію зору
* IPython/pandas/scikit-learn
* (ME) HMM
* CRF
* label bias problem
* Stacked NN
* LeToR
* factorization machines
* autoencoders
* RNN/CNN
* замість NLP краще окремі задачі (language modelling, co-reference detection, text chunking, POS-tagging, probabilistic parsing, статистична машина translation, misspell correction, question answering, NER, collocation detection, text summarization, speech recognition, fact extra analysis)
* ефективне обчислення softmax
* розробка/вибір функцій
* оцінка якості
* Меннінг/Джурафскі/МакКаллум/Кен
* приховані теми (LDA, китайський ресторан, pLSI)
* паралельні координати
* обітниця wabbit
* NLTK
* структуроване навчання
* EM-алгоритм
* контрастивна дивергенція
* оптимальна операція на мозку
* поширення переконань
* напівконтрольоване навчання
* індуктивне проти трансдуктивного навчання
* хитрість ядра
* дискримінаційні/генеративні пари (як це бачать Ng & Jordan)
* послідовність навчання
* укладання в мішки
* аналіз соціальних графів
* рекомендаційні системи/collaborative filtering
* multimodal learning
* **Теорія інформації**
* стиск
* Хаффман
* RLE
* BWT
* LZ
* коди корекції помилок
* стиск із втратами (зображення, аудіо, відео)
* інформаційна ентропія
* формула Шеннона
* складність Колмогорова
* maximum entropy problem
* kullback-leibler divergence
* elias/shannon-elias encoding
* **Криптографія**
* Шнайєр/Ященко
* Принцип Керкгоффса
* симетрична (DES, AES)
* асиметрична (RSA)
* якість ГПСЧ
* алгоритм Діффі-Хеллмана
* еліптичні криві
* хешування (MD5, SHA, CRCn)
* DHT
* криптостійкість
* криптоатаки (атака гросмейстера)
* WEP/WPA/WPA2 та атаки на них
* цифровий підпис та сертифікати
* PKI
* HTTPS/SSL
* доказ з нульовим розголошенням
* Порогова схема
* murmurhash/cityhash
* DKIM
* **Математика**
* Кнут-Грехем-Паташник/Зорич/Вінберг
* Spivak/Dummit-Foote
* матан
* Лінал
* Комплан
* функан
* диффгем
* теорія чисел
* дифури/інтури/урчпи/варіаційне обчислення/оптимальне управління
* Виробляють функції
* ряди
* комбінаторика
* теорвер/матстат/столби/теорія масового обслуговування
* Ланцюги Маркова
* Інтегральні перетворення (Фур'є, Лаплас, вейвлет)
* NZQRCHOS
* матпакети (Mathematica, Maple)
* теорія категорій
* **Фізика**
* правила Кірхгофа
* Закон Джоуля-Ленца
* комплексний опір
* швидкість та частота світла
* Рівняння Максвелла
* лагранжіан та гамільтоніан
* quantum tunnelling/hot electron injection :)
* **Хімія**
* стехіометрія
* Хімія кремнію :)
* **Архітектура та стиль коду**
* Макконнелл/Фаулер/Лебланк/Гамма/Александреску-Саттер/Буч
* захисне програмування
* Патерни
* SOLID/GRASP/KISS DRY SPOT/YAGNI
* UML
* OOP (Smalltalk)
* OOD/OOA
* метрики коду
* uncle Bob
* **Методології розробки**
* Waterfall/RUP/Agile/Scrum/Kanban/XP
* TDD/BDD
* CASE
* **Тестування**
* юніт-тести
* функціональне, навантажувальне, інтеграційне тестування
* Тестування UI
* mocks/stubs/spies
* fixture
* запахи та патерни тестів (Osherove/Meszaros)
* **Інструментальні засоби розробки**
* IDE
* IntelliSense
* відладчики (VS/Olly/WinDbg/kdb/gdb) та трейсери (strace/ltrace)
* DWARF debug information format
* дизассемблери та декомпілятори (IDA/HexRays/Reflector)
* Системи контролю версій (SVN, GIT)
* merge/branch/trunk
* системи іменування файлів та бранчів
* continuous integration
* ant
* code coverage
* Статичний аналіз (lint, cppcheck)
* динамічний аналіз (valgrind, фазінг)
* верифікація та валідація ПЗ (Frama-C, RAISE (RSL), Coq)
* профайлінг
* Багтрекери
* документування коду
* системи збирання (CMake)
* пакетні менеджери (NuGet)
* **Фреймворки**
* Qt
* moc та метаінформація
* Концепція слот-сигнал
* Саммерфілд-Бланшет/Шлей
* PoCo
* Промислові бібліотеки: GMP, i18n, lapack, fftw, pcre
* **Операційні системи**
* Silberschatz/Ріхтер/Соломон-Руссинович/Робачевський/Вахалія/Стивенс/Таненбаум/Love/Linux Kernel Internals
* менеджер пам'яті
* менеджер купи та її пристрій (LAL/LFH/slab)
* менеджер пристроїв
* менеджер процесів
* context switch
* реальний та захищений режим
* Виконані файли (PE/ELF/Mach)
* об'єкти ядра
* налагоджувальні механізми (strace/ptrace/dtrace/pydbg, Debug API) та мінідампи
* bash
* мережевий стек та високопродуктивні сервери
* netgraph
* CR0
* IPC
* віконна підсистема
* система безпеки: ACE/ACL та права доступу
* технології віртуалізації
* RTOS (QNX)
* програмування драйверів
* IRQL
* IRP
* файлові системи
* BigTable
* NDIS/miniport/FS drivers/filter driver
* Mm-, Io-, Ldr-функції
* DKOM і руткіти
* GDT/IDT/SDT
* ядра Windows/Linux/BSD
* POSIX
* TRIM
* **Компонентно-орієнтовані моделі**
* Роджерсон/Таварес
* COM/OLE/ActiveX/COM+/DCOM RPC
* ATL
* апартменти
* Монікери
* MIDL
* XPCOM
* CORBA
* TAO
* D-Bus
* **Мережа**
* Стівенс
* OSI model/Internet model
* Ethernet
* TCP/IP
* TCP window
* алгоритм Нейгла
* Сокети
* Protocol buffers/Thrift/Avro/ASN.1
* AMQP
* ICMP
* роутинг/BGP/OSPF
* ARP
* атака Митника
* syn flood
* HTTP/FTP
* P2P/DHT
* DHCP
* SMB/NBNS
* IRC/XMPP
* POP3/SMTP/ESMTP/IMAP
* DNS
* WiFi/WiMax/GSM/CDMA/EDGE/Bluetooth/GPS
* ACE
* Wireshark
* **Графіка та GPGPU**
* алгоритм Брезенхема
* колірні моделі
* трасування променів vs полігональна графіка
* OpenGL/GLSL/Open Inventor
* DirectX/DirectShow/DirectAudio/HLSL
* stencil/depth/alpha-test
* графічний конвеєр у DirectX 11
* шейдери
* моделі освітлення (Фонг)
* пропускна спроможність
* fillrate
* OpenCL/CUDA/AMP
* ландшафти
* човни
* тіні
* deferred shading
* текстурування та фільтрація
* Антіаліасінг
* HDR
* tone mapping
* virtual/augmented reality
* **Формати**
* XML/XSLT/XPath/XMLStarlet/DOM/SAX
* RTF/ODF
* JSON/BSON/bencode
* YAML
* JPEG/PNG/WebP
* AVI/MPEG/RIFF/WAV/MP3/OGG/WebM
* SVG
* Unicode
* кодування однобайтні/UTF-8/UTF-16/UCS-2/UTF-32
* проблеми довжини та порівняння Unicode-рядків
* base64
* markdown
* **Бази даних/Розподілені системи**
* Грубер/Дейт
* ANSI SQL
* T-SQL
* ODBC
* MySQL/PostgreSQL/MS SQL/BDB/SQLite/Sphinx
* Збережені процедури
* тригери
* алгебра Кодда/А
* Tutorial D
* нормальні форми
* оптимізація та виконання запитів
* структури даних індексів
* транзакції та ACID
* CAP-теорема Брюєра
* graph DB
* document store
* wide column store
* key-value storage
* теорія розподілених систем
* CRDT
* net split проблема
* протоколи консенсусу
* теорія шардингу/реплікації
* ORM (C++ ODB)
* ERD
* OLAP
* Семантична мережа
* Triplestore
* RDF/Turtle
* SPARQL
* OWL
* Semanticscience Integrated Ontology
* reasoner
* DBpedia
* big table/hbase vs. dynamodb/cassandra/riak
* 2/3PC
* chubby/zoo keeper
* leader election (paxos/raft)
* hdfs/gfs/glusterfs
* deduplication problem
* causality detection (vector clock/stamps)
* R/W quorum
* load balancing
* пристрій індексів пошукових систем
* event sourcing
* CRDT
* дизайн протоколів та принципи комунікації з погляду еволюції, розширюваності, надійності
* дизайн програмних інтерфейсів (API)
* **Прикладне програмування**
* C#/F#
* Шілдт/Троелсен/Ріхтер
* генерики
* yield
* linq/plinq
* рефлексія
* AST
* WCF
* WinForms/WPF/Silverlight
* AOP
* фреймворки логування
* .NET assembly
* Scala
* Хорстманн/Одерськи
* pattern matching
* макроси/квазіцитати
* **Квантові обчислення**
* алгоритм Шора
* квантова криптографія
* **Функціональне програмування**
* Haskell/Ocaml/Scheme/Alice або Oz
* SICP/TaPL/YAHT/Purely Functional Data Structures/Харрісон-Філд
* HOF (map/fold/filter)
* система типів Хіндлі-Мілнера
* монади
* тайпкласи
* АТД
* dependent types
* лінивість/енергійність
* Логічне програмування (Prolog або Mercury)
* Конкурентне програмування (Erlang або Oz)
* **Веб-програмування та скриптові мови**
* Фланаган/Zend PHP5 Certification Course + Study Guide
* Apache/nginx
* CGI/FastCGI
* PHP/Zend Framework/ReactPHP/Zend Engine/Doctrine або Propel/CodeIgniter або Symphony або Yii
* Python/Django/Twisted
* Ruby/RoR
* ASP.NET MV*
* JavaScript/jQuery/React/Google Closure/ExtJS/node.js
* ООП в JavaScript
* HTML5
* CSS3/таблична та блочна верстка
* RSS
* canvas/WebGL
* Ajax/WebSockets
* питання безпеки (XSS, SQL injection, CSRF)
* highload
* C10k problem
* SWIG
* CDN
* shadow DOM
* квірки браузерів
* real time bidding/trading
* anomaly detection
* архітектура single page apps
* пристрій веб-краулерів
* web/social graph random walk
* asm.js та компіляція в js
* v8/spidermonkey internals
* PaaS/IaaS
* SPDY
* **Проектування GUI та подання інформації**
* Раскін/Тафті
* юзабіліті
* основи дизайну та друкарні
* Закон Фіттса
* основи верстки
* LaTeX
* алгоритми візуалізації даних (as seen in d3)
* subpixel rendering

