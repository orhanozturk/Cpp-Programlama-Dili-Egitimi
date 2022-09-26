# C++ Programlama Dili Egitimi İçeriği (Düzenlenmektedir)
### İçerik, Ders işleme sırası ile birebir değildir. Konu akışı farklılık gösterebilir. <br>

	Ortalama 2 dersten sonra Oyun Quizleri yapılacaktır.

## 📌C++ Dilinin Genel Tanıtımı
- C++ dilinin tarihçesi<br>
- C++ dili ve programlama paradigmaları<br>
- C++ dili standartları<br>
- C++98 – 03<br>
- C++11<br>
- C++14<br>
- C++17<br>
- C++20<br>
- eski C++ ve modern C++<br>

## 📌C Dili ve C++ İçindeki C Dili _(C in C++)_
- C dilinden C++ diline geçiş<br>
- işlev bildirimleri ve tanımlamalarına ilişkin farklılıklar<br>
- türlere ve tür dönüşümlerine ilişkin farklılıklar<br>
- C’de geçerli C++’da geçersiz durumlar<br>
- C99 ve C++<br>

## 📌Temel Kavramlar _(Basic Concepts)_
- tamamlanmış ve eksik türler _(complete & incomplete types)_<br>
- tek tanımlama kuralı _(one definition rule)_<br>
- ifadelerin değer kategorileri _(value categories)_<br>
- tanımsız davranış _(undefined behavior)_ <br>
- derleyiciye bağlı davranışlar. _(implementation defined & implementaion specified)_<br>
- derleyici eklentileri _(compiler extensions)_ <br>
- kapsam _(scope)_ ve isim arama _(name lookup)_ <br>
- erişim kontrolü _(access control)_ <br>
- çift anlamlılık hatası _(ambiguity)_ <br>

## 📌İlk Değer Verme _(Initialization)_
- eş biçimli ilk değer verme _(uniform initialization)_<br>
- daraltıcı dönüşümler _(narrowing conversions)_ <br>
- most vexing parse <br>
- doğrudan ilk değer verme _(direct intialization)_ <br>
- değerle başlatma _value initialization_<br>
- kopyalama ile ilk değer verme _(copy initialization)_ <br>
- varsayılan ilk değer verme _(default initialization)_ <br>
- bileşiklere ilk değer verme _(aggregate initialization)_ <br>

## 📌Tür Çıkarımı _(Type Deduction)_
- auto belirteci ile tür çıkarımı _(auto type deduction)_ <br>
- decltype belirteci ile tür çıkarımı _(decltype type deduction)_ <br>
- sonradan gelen geri dönüş türü _(trailing  return type)_ <br>
- auto geri dönüş değeri türü _(auto return type)_ <br>
- decltype auto tür çıkarımı _(decltype auto)_ <br>

## 📌Kapsamlandırılmış enum türleri _(scoped enums)_
- geleneksel enum türleri _(conventional enum types)_ <br>
- baz tür seçimi _(underlying type)_ <br>
- tür dönüşümleri _(type conversions)_ <br>
- enum türleri kapsam _(enum classes & scope)_ <br>
- using enum declarations (C++20) <br>

## 📌Sabit İfadeleri _(Constant Expressions)_
- const anahtar sözcüğü ve const semantiği _(const keyword & const semantics)_<br>
- const nesneler _(const objects)_<br>
- constexpr anahtar sözcüğü _(constexpr keyword)_<br>
- constexpr işlevler _(constexpr functions)_<br>
- consteval işlevler - C++20 _(consteval functions - C++20)_<br>
- constinit anahtar sözcüğü - C++20

## 📌İşlevlerin Varsayılan Argüman Alması _(Default Arguments)_

## 📌Referans Semantiği (Reference Semantics)
- sol taraf referansları _(L value references)_<br>
- sağ taraf referansları _(R value references)_<br>
- referanslar ve const semantiği _(references & const semantics)_<br>
- referanslar ile göstericilerin _(pointer)_ karşılaştırılması<br>
- parametresi referans olan işlevler<br>
- referans döndüren işlevler<br>
- referanslar ve _life extension_ <br>

## 📌İşlev Yüklemesi _(Function Overloading)_
- genel kurallar <br>
- yüklenmiş işlev çözümlenmesi _(function overload resolution)_<br>
- const yüklemesi _(const overloading)_<br>
- extern "C" bildirimi _(extern C declarations)_<br>
- işlev yüklemesinde dikkat edilmesi gereken durumlar<br>

## 📌Tür Dönüştürme Operatörleri _(Type-cast Operators)_
- static_cast<> operatörü<br>
- const_cast<> operatörü<br>
- reinterpret_cast<> operatörü<br>
- dynamic_cast<> operatörü _(kalıtım başlığı altında)_<br>

## 📌inline işlevler ve inline değişkenler
- inline işlevler _(inline functions)_ <br>
- inline değişkenler (C++17) _(inline variables)_ <br>

## 📌Sınıflara giriş _(Introduction to Classes)_
- sınıf kapsamı _(class scope)_ <br>
- sınıflar ve isim arama _(name lookup)_<br>
- erişim kontrolü _(access control)_ ve veri gizleme _(data hiding)_<br>
&emsp;&emsp;- public öğeler _(public members)_<br>
&emsp;&emsp;- private öğeler _(private members)_<br>
&emsp;&emsp;- protected öğeler _(protected members)_<br>
- sınıfların öğeleri _(class members)_<br>
&emsp;&emsp;- sınıfların veri öğeleri _(data members)_<br>
&emsp;&emsp;&emsp;&emsp;-  non-static veri öğeleri<br>
&emsp;&emsp;&emsp;&emsp;-  mutable veri öğeleri<br>
&emsp;&emsp;&emsp;&emsp;-  static veri öğeleri<br>
&emsp;&emsp;- sınıfların üye işlevleri<br>
&emsp;&emsp;&emsp;&emsp;- non-static üye işlevler<br>
&emsp;&emsp;&emsp;&emsp;- const üye işlevler<br>
&emsp;&emsp;&emsp;&emsp;- static üye işlevler<br>
&emsp;&emsp;- this göstericisi ve \*this<br>
&emsp;&emsp;- sınıfların tür öğeleri _(type members)_<br>
- sınıfların kurucu işlevleri _(constructors)_<br>
&emsp;&emsp;- kurucu işlev ilk değer verme listesi _(constructor initializer list)_<br>
&emsp;&emsp;- delege eden kurucu işlevler _(delegating constructors)_<br>
&emsp;&emsp;- explicit kurucu işlevler _(explicit constructors)_<br>
- sınıfların sonlandırıcı işlevleri _(destructors)_<br>
- üye işlevlerin çağrılması<br>
- sınıflar ve const doğruluğu _(classes & const correctness)_<br>
&emsp;&emsp;- const sınıf nesneleri _(const objects)_<br>
&emsp;&emsp;- const üye fonksiyonlar _(const member fuctions)_<br>
- geçici sınıf nesneleri _(temporary objects)_<br>
- otomatik tür dönüşümleri _(implicit type conversions)_ <br>
- mutable anahtar sözcüğü<br>
- friend bildirimi _(friend declarations)_ <br>
&emsp;&emsp;- friend bildirimi ve veri gizleme<br>
&emsp;&emsp;- global işlevlere friend bildirimi<br>
&emsp;&emsp;- sınıfların üye işlevlerine friend bildirimi<br>
&emsp;&emsp;- sınıflara friend bildirimi<br>
&emsp;&emsp;- attorney client idiyomu<br>

## Sınıfların Özel Üye İşlevleri ve Kopyalama İşlemleri _(Special Member Functions & Copy Control)_
- sınıfların özel işlevleri _(special member functions)_<br>
&emsp;&emsp;- default constructor _(varsayılan kurucu işlev)_<br>
&emsp;&emsp;- destructor _(sonlandırıcı işlev)_<br>
&emsp;&emsp;- copy constructor _(kopyalayan kurucu işlev)_<br>
&emsp;&emsp;- move constructor _(taşıyan kurucu işlev)_<br>
&emsp;&emsp;- copy assignment _(kopyalayan atama işlevi)_<br>
&emsp;&emsp;- move assignment _(taşıyan atama işlevi)_<br>
- özel işlevlerin default edilmesi<br>
- özel işlevlerin delete edilmesi<br>
- sınıflar ve taşıma semantiği _(move semantics)_<br>
- _rule of zero_<br>
- _rule of five_<br>
- kopyala takas et idiyomu _(copy & swap idiom)_<br>
- kopyalamanın eliminasyonu _(copy elision)_<br>
&emsp;&emsp;- geçici nesneler yoluyla kopyalama eliminasyonu _(copy elision by temporaries)_<br>
&emsp;&emsp;- RVO (return value optimization)<br>
&emsp;&emsp;- NRVO (names return value optimization)<br>
&emsp;&emsp;- zorunlu kopyalama eliminasyonu _(mandatory copy elision)_<br>

## 📌Operatör Yüklemesi _(Operator Overloading)_
- operatör yüklemesine ilişkin genel kurallar<br>
- üye operatör fonksiyonları _(member operator functions)_<br>
- global operatör fonksiyonları _(global operator functions)_<br>
- aritmetik operatörlerin yüklenmesi<br>
- karşılaştırma operatörlerinin yüklenmesi<br>
- 3 yollu karşılaştırma operatörü _(3-way comparision operator)_ C++20<br>
- "++" ve "--" operatörlerinin yüklenmesi<br>
- ok operatörü ve içerik operatörlerinin yüklenmesi _(overloading of arrow and dereferencing operators)_<br>
- [] operatörünün yüklenmesi _(overloading of subscript operator)_<br>
- fonksiyon çağrı operatörünün yüklenmesi  _(overloading of function call operator)_<br>
- tür dönüştürme operatör fonksiyonları _(type-cast operator functions)_<br>
- programcının tanımladığı sabitler _(user-defined literals)_<br>

## 📌Dinamik Ömürlü Nesneler _(Dynamic Objects)_
- new ve delete ifadeleri _(new & delete expressions)_ <br>
- new[] ve delete [] ifadeleri<br>
- operator new işlevleri<br>
- operator delete işlevleri<br>
- operator new ve operator delete işlevlerinin yüklenmesi<br>
- std::bad_alloc<br>
- std::set_new_handler ve std::get_new_handler işlevleri<br>
- placement new operatörleri<br>
- nothrow new<br>

## 📌Tür Eş İsimleri _(Type Alias)_
- typedef bildirimleri <br>
- using bildirimleri <br>

## 📌İsim Alanları _(Namespaces)_
- isim alanlarının oluşturulması <br>
- isim alanları ve isim arama _(namespaces & name lookup)_ <br>
- çözünürlük operatörü ve isim alanları _(scope resoşution operator & namespaces)_ <br>
- using bildirimi _(using declaration)_<br>
- using namespace direktifi _(using namespace directive)_ <br>
- argümana bağlı isim arama _(argument dependent lookup)_<br>
- isimsiz isim alanı _(unnamed namespace)_<br>
- içsel isim alanları _(nested namespaces)_<br>
- inline isim alanları _(inline namespaces)_<br>
- isim alanı eş ismi _(namespace alias)_<br>
- işlev yüklemesi ve isim alanları _(function overloading & namespaces)_ <br>

## 📌Sınıflar ve Kalıtım _(Classes & Inheritance)_
- nesne yönelimli programlama ve kalıtım _(OOP & inheritance)_ <br>
- public kalıtımı _(public inheritance)_<br>
- çalışma zamanı çok biçimliliği _(runtime polymorphism)_<br>
&emsp;&emsp;- dinamik ve statik tür bilgisi _(static & dynamic type)_<br>
&emsp;&emsp;- sanal işlevler _(virtual function)_<br>
&emsp;&emsp;- saf sanal işlevler _(pure virtual function)_<br>
&emsp;&emsp;- sanal sonlandırıcı işlev _(virtual destructor)_<br>
&emsp;&emsp;- sanal kurucu işlev idiyomu _(virtual constructor idiom)_<br>
&emsp;&emsp;- override bağlamsal anahtar sözcüğü<br>
&emsp;&emsp;- sanal gönderim mekanizmasının implementasyonu _(implementation of virtual dispatch mechanism)_<br>
&emsp;&emsp;- nesne dilimlenmesi _(object slicing)_<br>
&emsp;&emsp;- sanal olmayan arayüz idiyomu _(non-virtual interface idiom)_<br>
- final bağlamsal anahtar sözcüğü _(final contextual keyword)_ <br>
&emsp;&emsp;- final sınıflar _(final classes)_<br>
&emsp;&emsp;- _final override_<br>
- çoklu kalıtım _multiple inheritance)_<br>
&emsp;&emsp;- çoklu kalıtımda kapsam ve isim arama_(multiple inheritance & name lookup)_ <br>
&emsp;&emsp;- çoklu kalıtımda sınıfın özel işlevleri<br>
&emsp;&emsp;- elmas formasyonu _(diamond formation)_<br>
&emsp;&emsp;- sanal kalıtım _(virtual inheritance)_<br>
&emsp;&emsp;- çoklu kalıtım ve kalıtımla alınan kurucu işlevler<br>
&emsp;&emsp;- çoklu kalıtımda kopyalama ve taşıma işlemleri<br>
- private kalıtımı _(private inheritance)_<br>
&emsp;&emsp;- implementaion inheritance<br>
&emsp;&emsp;- empty base optimization<br>
- protected kalıtımı _(protected inheritance)_<br>
- sınıf içi using bildirimi <br>
- kalıtımla alınan kurucu işlevler _(inherited constructors)_<br>
- mixin sınıflar _(mixin classes)_<br>

## 📌Olağan Dışı Durumların İşlenmesi _(Exception Handling)_
- exception güvenliği _(exception safety)_<br>
- hata nesnelerinin gönderilmesi _(throwing exception objects)_<br>
&emsp;&emsp;- throw deyimi _(throw statement)_<br>
&emsp;&emsp;- rethrow deyimi _(rethrow statement)_<br>
- try blokları<br>
- catch blokları<br>
&emsp;&emsp;- catch all <br>
- yakalanamayan hata nesnesi _(uncaught exception)_<br>
- std::terminate ve std::set_terminate işlevleri<br>
- hata nesnesinin yeniden gönderilmesi _(rethrow statement)_<br>
- yığının geri sarımı _(stack unwinding)_<br>
- kurucu işlevlerden exception gönderimi<br>
- sonlandırıcı işlevler ve hata gönderimi<br>
- exception handling ve kalıtım _(eception handling & inheritance)_<br>
- exception handling ve dinamik ömürlü sınıf nesneleri _(eception handling & dynamic objects)_<br>
- exception  güvenliği için akıllı göstericilerin kullanımı _(eception handling & smart pointers)_<br>
- işlev try blokları _(function try block)_<br>
- noexcept belirleyicisi _(noexcept specifier)_<br>
- beklenmeyen hata nesnesi _(unexpected excetion)_<br>
- std::unexpected_exception<br>
- std::exception sınıfı ve hiyerarşisi<br>
&emsp;&emsp;- std::exception sınıfı ve what sanal fonksiyonu<br>
&emsp;&emsp;- std::logic_error<br>
&emsp;&emsp;&emsp;&emsp;- std::invalid_argument, std::domain_error, std::length_error<, std::out_of_range, std::future_error sınıfları <br>
&emsp;&emsp;- std::runtime_error<br>
&emsp;&emsp;&emsp;&emsp;- std::range_error, std::overflow_error, std::underflow_error sınıfları <br>
&emsp;&emsp;- std::system_error<br>
&emsp;&emsp;- std::regex_error<br>
&emsp;&emsp;- std::bad_alloc<br>
&emsp;&emsp;- std::bad_typeid<br>
&emsp;&emsp;- std::bad_cast<br>
&emsp;&emsp;- std::bad_exception<br>
&emsp;&emsp;- std::bad_weak_ptr<br>
&emsp;&emsp;- std::bad_function_call<br>
- kendi hata sınıflarımızı oluşturmak _(custom exception classes)_<br>
- exception garantileri _(eception guarantees)_<br>
&emsp;&emsp;- _basic exception guarantee_<br>
&emsp;&emsp;- _strong exception guarantee_<br>
&emsp;&emsp;- _no throw guarantee_<br>
- std::current_exception<br>
- std::exception_ptr<br>
- std::rethrow_exception<br>

## 📌Çalışma Zamanında Tür Belirlenmesi _(RTTI)_
- dynamic_cast operatörü<br>
- typeid operatörü<br>
- std::typeinfo sınıfı<br>
- std::bad_typeid<br>

## 📌std::string sınıfı
- genel kavramlar <br>
- string::size_type<br>
- string::npos<br>
- arama işlevleri<br>
- set işlemleri<br>
- erişim işlemleri<br>
- karşılaştırma işlevleri _(comparision functions)_<br>
- sayısal dönüşüm işlevleri _(numeric conversions)_<br>
- küçük string optimizasyonu _(small string optimization)_<br>
- bir STL kabı olaral string sınıfı _(string class as STL container)_ <br>

## 📌Bileşik Nesneler _(Composition)_
- öğe olan nesneler ve özel işlevler, kopyalama kontrolü.<br>
- öğe olan nesneler ve erişim kontrolü<br>
- bileşik nesnelerin kullanıldığı temalar<br>

## 📌İçsel türler _(Type Members)_
- sınıf içinde yapılan eş isim bildirimleri<br>
- içsel sınıflar _(nested classes)_<br>
&emsp;&emsp;- erişim kontrolü _(access control)_<br>
&emsp;&emsp;- _pimpl_ idiyomu _(pimpl idiom)_

## 📌Şablonlar _(Templates)_
- şablon tür parametreleri _(template type parameters)_ <br>
- şablon sabit parametreleri _(template non-type parameters)_<br>
- şablon şablon parametreleri _(template template parameters)_<br>
- şablon argümanları _(template arguments)_<br>
&emsp;&emsp;- belirtilmiş template argümanları _(explicit template arguments)_<br>
&emsp;&emsp;- varsayılan template argümanları _(default template arguments)_<br>
- şablonlardan kod üretimi _(template instantiation)_<br>
- fonksiyon şablonları _(function templates)_<br>
&emsp;&emsp;- fonksiyon şablonlarında tür çıkarımı _(function template argument deduction)_<br>
&emsp;&emsp;- fonksiyon şablonlarının yüklenmesi _(function template overloading)_<br>
- sınıf şablonları _(class templates)_<br>
- kurucu işlev ile tür çıkarımı _(CTAD)_ (C++17)<br>
- üye şablonlar _(member templates)_<br>
- şablonların özelleştirilmesi _(template specialization)_<br>
&emsp;&emsp;- tam özelleştirme _(explicit/full specialization)_<br>
&emsp;&emsp;- kısmi özelleştirme _(partial specialization)_<br>
- _sfinae_<br>
- değişken sayıda parametreli şablonlar _(variadic templates)_<br>
- mükemmel gönderim _(perfect forwarding)_<br>
- katlama ifadeleri(C++17) _(fold expressions)_<br>
- _if constexpr_<br>
- değişken şablonları _(variable templates)_<br>
- eş isim şablonları _(alias templates)_<br>

## 📌İteratörler _(Iterators)_
- aralık kavramı _(ranges)_<br>
- iteratörlerin kategorileri _(iterator categories)_<br>
&emsp;&emsp;- input iterator<br>
&emsp;&emsp;- output iterator<br>
&emsp;&emsp;- forward iterator<br>
&emsp;&emsp;- bidirectional iterator<br>
&emsp;&emsp;- random access iterator<br>
- kapların begin ve end işlevleri<br>
- global begin ve end işlevleri<br>
- iterator işlevleri<br>
&emsp;&emsp;- std::next <br>
&emsp;&emsp;- std::prev <br>
&emsp;&emsp;- std::iter_swap<br>
&emsp;&emsp;- std::advance <br>
&emsp;&emsp;- std::distance<br>
- iterator uyumlandırıcıları _(iterator adaptors)_<br>
&emsp;&emsp;- akım iteratörleri _(stream iterators)_<br>
&emsp;&emsp;&emsp;&emsp;- istream_iterator<br>
&emsp;&emsp;&emsp;&emsp;- ostream_iterator<br>
&emsp;&emsp;&emsp;&emsp;- istreambuf_iterator<br>
&emsp;&emsp;&emsp;&emsp;- ostreambuf_iterator<br>
&emsp;&emsp;- reverse iterators<br>
&emsp;&emsp;- move iterators<br>
&emsp;&emsp;- insert iterators<br>
&emsp;&emsp;&emsp;&emsp;- back_insert_iterator<br>
&emsp;&emsp;&emsp;&emsp;- front_insert_iterator<br>
&emsp;&emsp;&emsp;&emsp;- insert_iterator<br>
- iterator traits

## 📌Kaplar _(Containers)_
- STL kapları ve veri yapıları _(STL containers & data structures) _ <br>
- sıralı kaplar _(sequence containers)_<br>
&emsp;&emsp;- std::vector<br>
&emsp;&emsp;- std::deque<br>
&emsp;&emsp;- std::string<br>
&emsp;&emsp;- std::array<br>
&emsp;&emsp;- std::list<br>
&emsp;&emsp;- std::forward_list<br>
- ilişkisel kaplar _(associative containers)_<br>
&emsp;&emsp;- std::set<br>
&emsp;&emsp;- std::multiset<br>
&emsp;&emsp;- std::map<br>
&emsp;&emsp;- std::multimap<br>
- sırasız ilişkisel kaplar _(unordered containers)_<br>
&emsp;&emsp;- std::unordered_set<br>
&emsp;&emsp;- std::unordered_multiset<br>
&emsp;&emsp;- std::unordered_map<br>
&emsp;&emsp;- std::unordered_multimap<br>
- kapların tür öğeleri _(type members of containers)_<br>
- kapların emplace işlevleri<br>

## 📌Kap Uyumlandırıcıları _(Container Adaptors)_
- std::stack<br>
- std::queue<br>
- std::priority_queue<br>

## 📌Algoritmalar _(Algorithms)_
- algoritmaların temel özellikleri ve genel ilkeler <br>
- salt okuyan algoritmalar _non-modifying algorithms)_<br>
- kap öğelerini değiştiren algoritmalar _(modifying algorithms)_<br>
- kap öğelerini konumlandıran algoritmalar _(mutating algorithms)_<br>
- sıralama ile ilgili algoritmalar _(sorting algorithms)_<br>
- sıralanmış aralıklar üzerinde koşturulan algoritmalar _(sorted range algorithms)_<br>
- nümerik algoritmalar _(numeric algorithms)_<br>
- algoritmaların lambda ifadelerini kullanması<br>

## 📌Lambda İfadeleri _(Lambda Expressions)_
- kapanış türleri ve kapanış nesneleri _(closure types and closure objects)_<br>
- lambda ifadeleri ve tür çıkarımı _(lambda expressions and type deduction)_<br>
- lambda yakalama ifadeleri _(lambda captures)_<br>
- _lambda init capture_<br>
- capture this <br>
- capture _*this_<br>
- mutable lambdalar<br>
- trailing return type<br>
- genelleştirilmiş lambda ifadeleri _(generalized lambda expressions)_<br>
- algoritmalarda lambda ifadelerinin kullanımı<br>
- lambda ifadeleri C++11/14/17/20<br>
- lambda idiyomları _(lambda idioms)_<br>

## 📌Akıllı Gösterici Sınıfları _(Standard Smart Pointer Classes)_
- std::unique_ptr sınıfı <br>
&emsp;&emsp;- std::make_unique işlev şablonu <br> 
&emsp;&emsp;- std::default_delete ve custom deleters <br>
&emsp;&emsp;- tipik hatalar <br>
- std::shared_ptr sınıfı<br>
&emsp;&emsp;- referans sayımı _(reference counting)_<br>
&emsp;&emsp;- std::make_shared işlev şablonu<br>
&emsp;&emsp;- std::weak_ptr sınıfı<br>

## 📌Standart Giriş Çıkış Kütüphanesi _(iostream Library)_
- giriş çıkış akımlarına ilişkin standart sınıflar _(standard stream classes)_ <br>
- global akım nesneleri _(global stream objects)_<br>
- formatlı giriş çıkış işlemleri _(formatted input output)_<br>
- << ve >> operatörlerinin yüklenmesi _(inserter & extractors)_<br>
- formatlama ve formatlama işlemleri _(formatting)_<br>
- manipülatörler _(manipulators)_<br>
- akımın durumu _(condition states)_<br>
- string akımları _(string streams)_<br>
- dosya işlemleri _(file operations)_<br>
- formatsız giriş ve çıkış işlemleri _(unformatted input output)_<br>
- bellek üstünde yapılan giriş çıkış işlemleri _(in-memory input output operations)_<br>

## 📌Bazı önemli STL Öğelerinin Tanıtımı
- std::pair<br>
- std::tuple<br>
- std::initializer_list<br>
- std::bitset<br>
- std::regex<br>
- type_traits kütüphanesi<br>
- std::allocator<br>
- std::ratio<br>
- std::chrono<br>
- standart random kütüphanesi<br>
- std::string_view sınıfı (C++17)<br>
- std::optional sınıfı (C++17) <br>
- std::variant sınıfı (C++17)<br>
- std::any sınıfı (C++17)<br>
- std::byte (C++17)<br>
- std::invoke<br>
- std::apply<br>


## 📌Tamamlayıcı Araçlar ve Sentaks Öğeleri
- aralık tabanlı for döngüleri _(range based for loops)_<br>
- ilk değer vermeli if ve switch deyimleri _(if/switch with initializers)_<br>
- static_assert <br>
- decltype(auto) tür çıkarımı<br>
- std::declval<br>
- üye fonksiyon göstericileri _(member function pointers)_<br>
- ham string sabitleri _(raw string literals)_<br>
- ikilik sayı sisteminde yazılan sabitler _(binary literals)_<br>
- basamak ayırıcısı _(digit seperator)_<br>
- ilk değer vermeli if deyimi (C++17) _(if with initializer)_<br>
- ilk değer vermeli switch  deyimi (C++17) _(if with initializer)_<br>
- alignas belirteci _(alignas specifier)_<br>
- alignof operatörü _(alignof operator)_<br>
- yapısal bağlama (C++17)_(structural binding) _<br>
- attribute’lar _(attributes)_<br>

## 📌Concurrency
- memory model <br>
- thread’ler ve thread yönetimi<br>
- std::this_thread isim alanı<br>
- data race kavramı ve data_race’den kaçınma<br>
- standart mutex sınıfları ve mutex işlemleri<br>
- lock_guard ve unique_lock sınıfları<br>
- std::condition_variable sınıfı<br>
- std::future ve std::promise sınıfları<br>
- std::async işlevi<br>
- atomik türler _(atomic types)_<br>
- görev tabanlı _(task based)_ programlama<br>
- std::packaged_task sınıfı<br>
- paralel STL algoritmaları<br>
