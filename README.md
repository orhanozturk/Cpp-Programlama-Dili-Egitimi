# C++ Programlama Dili Egitimi İçeriği (Düzenlenmektedir)
### İçerik, Ders işleme sırası ile birebir değildir. Konu akışı farklılık gösterebilir. <br>

	Ortalama 2 dersten sonra Oyun Quizleri yapılacaktır.

## 📌C++ Dilinin Genel Tanıtımı
➡️ C++ dilinin tarihçesi<br>
➡️ C++ dili ve programlama paradigmaları<br>
➡️ C++ dili standartları<br>
➡️ eski C++ ve modern C++ farklılıkları gösterilecektir<br>
➡️ C++98 – 03 incelenecektir<br>
➡️ C++11 incelenecektir<br>
➡️ C++14 incelenecektir<br>
➡️ C++17 incelenecektir<br>
➡️ C++20 incelenecektir<br>


## 📌C Dili ve C++ İçindeki C Dili _(C in C++)_
➡️ C dilinden C++ diline geçiş ve farklılıkları<br>
➡️ işlev bildirimleri ve tanımlamalarına ilişkin farklılıklar<br>
➡️ türlere ve tür dönüşümlerine ilişkin farklılıklar<br>
➡️ C’de geçerli C++’da geçersiz durumlar<br>
➡️ C99 ve C++<br>

## 📌Temel Kavramlar _(Basic Concepts)_
➡️ tamamlanmış ve eksik türler __(complete & incomplete types)__<br>
➡️ tek tanımlama kuralı __(one definition rule)__<br>
➡️ ifadelerin değer kategorileri __(value categories)__<br>
➡️ tanımsız davranış __(undefined behavior)__ <br>
➡️ derleyiciye bağlı davranışlar. __(implementation defined & implementaion specified)__<br>
➡️ derleyici eklentileri __(compiler extensions)__ <br>
➡️ kapsam __(scope)__ ve isim arama __(name lookup)__ <br>
➡️ erişim kontrolü __(access control)__ <br>
➡️ çift anlamlılık hatası __(ambiguity)__ <br>

## 📌İlk Değer Verme _(Initialization)_
➡️ eş biçimli ilk değer verme __(uniform initialization)__<br>
➡️ daraltıcı dönüşümler __(narrowing conversions)__ <br>
➡️ most vexing parse <br>
➡️ doğrudan ilk değer verme __(direct intialization)__ <br>
➡️ değerle başlatma __value initialization__<br>
➡️ kopyalama ile ilk değer verme __(copy initialization)__ <br>
➡️ varsayılan ilk değer verme __(default initialization)__ <br>
➡️ bileşiklere ilk değer verme __(aggregate initialization)__ <br>

## 📌Tür Çıkarımı _(Type Deduction)_
➡️ auto belirteci ile tür çıkarımı __(auto type deduction)__ <br>
➡️ decltype belirteci ile tür çıkarımı __(decltype type deduction)__ <br>
➡️ sonradan gelen geri dönüş türü __(trailing  return type)__ <br>
➡️ auto geri dönüş değeri türü __(auto return type)__ <br>
➡️ decltype auto tür çıkarımı __(decltype auto)__ <br>

## 📌Kapsamlandırılmış enum türleri _(scoped enums)_
- geleneksel enum türleri __(conventional enum types)__ <br>
- baz tür seçimi __(underlying type)__ <br>
- tür dönüşümleri __(type conversions)__ <br>
- enum türleri kapsam __(enum classes & scope)__ <br>
- using enum declarations (C++20) <br>

## 📌Sabit İfadeleri _(Constant Expressions)_
- const anahtar sözcüğü ve const semantiği __(const keyword & const semantics)__<br>
- const nesneler __(const objects)__<br>
- constexpr anahtar sözcüğü __(constexpr keyword)__<br>
- constexpr işlevler __(constexpr functions)__<br>
- consteval işlevler - C++20 __(consteval functions - C++20)__<br>
- constinit anahtar sözcüğü - C++20

## 📌İşlevlerin Varsayılan Argüman Alması _(Default Arguments)_

## 📌Referans Semantiği (Reference Semantics)
- sol taraf referansları __(L value references)__<br>
- sağ taraf referansları __(R value references)__<br>
- referanslar ve const semantiği __(references & const semantics)__<br>
- referanslar ile göstericilerin __(pointer)__ karşılaştırılması<br>
- parametresi referans olan işlevler<br>
- referans döndüren işlevler<br>
- referanslar ve __life extension__ <br>

## 📌İşlev Yüklemesi _(Function Overloading)_
- genel kurallar <br>
- yüklenmiş işlev çözümlenmesi __(function overload resolution)__<br>
- const yüklemesi __(const overloading)__<br>
- extern "C" bildirimi __(extern C declarations)__<br>
- işlev yüklemesinde dikkat edilmesi gereken durumlar<br>

## 📌Tür Dönüştürme Operatörleri _(Type-cast Operators)_
- static_cast<> operatörü<br>
- const_cast<> operatörü<br>
- reinterpret_cast<> operatörü<br>
- dynamic_cast<> operatörü <br>

## 📌inline işlevler ve inline değişkenler
- inline işlevler __(inline functions)__ <br>
- inline değişkenler (C++17) __(inline variables)__ <br>

## 📌Sınıflara giriş _(Introduction to Classes)_
- sınıf kapsamı __(class scope)__ <br>
- sınıflar ve isim arama __(name lookup)__<br>
- erişim kontrolü __(access control)__ ve veri gizleme __(data hiding)__<br>
&emsp;&emsp;- public öğeler __(public members)__<br>
&emsp;&emsp;- private öğeler __(private members)__<br>
&emsp;&emsp;- protected öğeler __(protected members)__<br>
- sınıfların öğeleri __(class members)__<br>
&emsp;&emsp;- sınıfların veri öğeleri __(data members)__<br>
&emsp;&emsp;&emsp;&emsp;-  non-static veri öğeleri<br>
&emsp;&emsp;&emsp;&emsp;-  mutable veri öğeleri<br>
&emsp;&emsp;&emsp;&emsp;-  static veri öğeleri<br>
&emsp;&emsp;- sınıfların üye işlevleri<br>
&emsp;&emsp;&emsp;&emsp;- non-static üye işlevler<br>
&emsp;&emsp;&emsp;&emsp;- const üye işlevler<br>
&emsp;&emsp;&emsp;&emsp;- static üye işlevler<br>
&emsp;&emsp;- this göstericisi ve \*this<br>
&emsp;&emsp;- sınıfların tür öğeleri __(type members)__<br>
- sınıfların kurucu işlevleri __(constructors)__<br>
&emsp;&emsp;- kurucu işlev ilk değer verme listesi __(constructor initializer list)__<br>
&emsp;&emsp;- delege eden kurucu işlevler __(delegating constructors)__<br>
&emsp;&emsp;- explicit kurucu işlevler __(explicit constructors)__<br>
- sınıfların sonlandırıcı işlevleri __(destructors)__<br>
- üye işlevlerin çağrılması<br>
- sınıflar ve const doğruluğu __(classes & const correctness)__<br>
&emsp;&emsp;- const sınıf nesneleri __(const objects)__<br>
&emsp;&emsp;- const üye fonksiyonlar __(const member fuctions)__<br>
- geçici sınıf nesneleri __(temporary objects)__<br>
- otomatik tür dönüşümleri __(implicit type conversions)__ <br>
- mutable anahtar sözcüğü<br>
- friend bildirimi __(friend declarations)__ <br>
&emsp;&emsp;- friend bildirimi ve veri gizleme<br>
&emsp;&emsp;- global işlevlere friend bildirimi<br>
&emsp;&emsp;- sınıfların üye işlevlerine friend bildirimi<br>
&emsp;&emsp;- sınıflara friend bildirimi<br>
&emsp;&emsp;- attorney client idiyomu<br>

## Sınıfların Özel Üye İşlevleri ve Kopyalama İşlemleri __(Special Member Functions & Copy Control)__
- sınıfların özel işlevleri __(special member functions)__<br>
&emsp;&emsp;- default constructor __(varsayılan kurucu işlev)__<br>
&emsp;&emsp;- destructor __(sonlandırıcı işlev)__<br>
&emsp;&emsp;- copy constructor __(kopyalayan kurucu işlev)__<br>
&emsp;&emsp;- move constructor __(taşıyan kurucu işlev)__<br>
&emsp;&emsp;- copy assignment __(kopyalayan atama işlevi)__<br>
&emsp;&emsp;- move assignment __(taşıyan atama işlevi)__<br>
- özel işlevlerin default edilmesi<br>
- özel işlevlerin delete edilmesi<br>
- sınıflar ve taşıma semantiği __(move semantics)__<br>
- _rule of zero_<br>
- _rule of five_<br>
- kopyala takas et idiyomu __(copy & swap idiom)__<br>
- kopyalamanın eliminasyonu __(copy elision)__<br>
&emsp;&emsp;- geçici nesneler yoluyla kopyalama eliminasyonu __(copy elision by temporaries)__<br>
&emsp;&emsp;- RVO __(return value optimization)__<br>
&emsp;&emsp;- NRVO __(names return value optimization)__<br>
&emsp;&emsp;- zorunlu kopyalama eliminasyonu __(mandatory copy elision)__<br>

## 📌Operatör Yüklemesi _(Operator Overloading)_
- operatör yüklemesine ilişkin genel kurallar<br>
- üye operatör fonksiyonları __(member operator functions)__<br>
- global operatör fonksiyonları __(global operator functions)__<br>
- aritmetik operatörlerin yüklenmesi<br>
- karşılaştırma operatörlerinin yüklenmesi<br>
- 3 yollu karşılaştırma operatörü __(3-way comparision operator)__ C++20<br>
- "++" ve "--" operatörlerinin yüklenmesi<br>
- ok operatörü ve içerik operatörlerinin yüklenmesi __(overloading of arrow and dereferencing operators)__<br>
- [] operatörünün yüklenmesi __(overloading of subscript operator)__<br>
- fonksiyon çağrı operatörünün yüklenmesi  __(overloading of function call operator)__<br>
- tür dönüştürme operatör fonksiyonları __(type-cast operator functions)__<br>
- programcının tanımladığı sabitler __(user-defined literals)__<br>

## 📌Dinamik Ömürlü Nesneler _(Dynamic Objects)_
- new ve delete ifadeleri __(new & delete expressions)__ <br>
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
- isim alanları ve isim arama __(namespaces & name lookup)__ <br>
- çözünürlük operatörü ve isim alanları __(scope resoşution operator & namespaces)__ <br>
- using bildirimi __(using declaration)__<br>
- using namespace direktifi __(using namespace directive)__ <br>
- argümana bağlı isim arama __(argument dependent lookup)__<br>
- isimsiz isim alanı __(unnamed namespace)__<br>
- içsel isim alanları __(nested namespaces)__<br>
- inline isim alanları __(inline namespaces)__<br>
- isim alanı eş ismi __(namespace alias)__<br>
- işlev yüklemesi ve isim alanları __(function overloading & namespaces)__ <br>

## 📌Sınıflar ve Kalıtım _(Classes & Inheritance)_
- nesne yönelimli programlama ve kalıtım __(OOP & inheritance)__ <br>
- public kalıtımı __(public inheritance)__<br>
- çalışma zamanı çok biçimliliği __(runtime polymorphism)__<br>
&emsp;&emsp;- dinamik ve statik tür bilgisi __(static & dynamic type)__<br>
&emsp;&emsp;- sanal işlevler __(virtual function)__<br>
&emsp;&emsp;- saf sanal işlevler __(pure virtual function)__<br>
&emsp;&emsp;- sanal sonlandırıcı işlev __(virtual destructor)__<br>
&emsp;&emsp;- sanal kurucu işlev idiyomu __(virtual constructor idiom)__<br>
&emsp;&emsp;- override bağlamsal anahtar sözcüğü<br>
&emsp;&emsp;- sanal gönderim mekanizmasının implementasyonu __(implementation of virtual dispatch mechanism)__<br>
&emsp;&emsp;- nesne dilimlenmesi __(object slicing)__<br>
&emsp;&emsp;- sanal olmayan arayüz idiyomu __(non-virtual interface idiom)__<br>
- final bağlamsal anahtar sözcüğü __(final contextual keyword)__ <br>
&emsp;&emsp;- final sınıflar __(final classes)__<br>
&emsp;&emsp;- __final override__<br>
- çoklu kalıtım _multiple inheritance)_<br>
&emsp;&emsp;- çoklu kalıtımda kapsam ve isim arama __(multiple inheritance & name lookup)__ <br>
&emsp;&emsp;- çoklu kalıtımda sınıfın özel işlevleri<br>
&emsp;&emsp;- elmas formasyonu __(diamond formation)__<br>
&emsp;&emsp;- sanal kalıtım __(virtual inheritance)__<br>
&emsp;&emsp;- çoklu kalıtım ve kalıtımla alınan kurucu işlevler<br>
&emsp;&emsp;- çoklu kalıtımda kopyalama ve taşıma işlemleri<br>
- private kalıtımı __(private inheritance)__<br>
&emsp;&emsp;- implementaion inheritance<br>
&emsp;&emsp;- empty base optimization<br>
- protected kalıtımı __(protected inheritance)__<br>
- sınıf içi using bildirimi <br>
- kalıtımla alınan kurucu işlevler __(inherited constructors)__<br>
- mixin sınıflar __(mixin classes)__<br>

## 📌Olağan Dışı Durumların İşlenmesi _(Exception Handling)_
- exception güvenliği __(exception safety)__<br>
- hata nesnelerinin gönderilmesi __(throwing exception objects)__<br>
&emsp;&emsp;- throw deyimi __(throw statement)__<br>
&emsp;&emsp;- rethrow deyimi __(rethrow statement)__<br>
- try blokları<br>
- catch blokları<br>
&emsp;&emsp;- catch all <br>
- yakalanamayan hata nesnesi __(uncaught exception)__<br>
- std::terminate ve std::set_terminate işlevleri<br>
- hata nesnesinin yeniden gönderilmesi __(rethrow statement)__<br>
- yığının geri sarımı __(stack unwinding)__<br>
- kurucu işlevlerden exception gönderimi<br>
- sonlandırıcı işlevler ve hata gönderimi<br>
- exception handling ve kalıtım __(eception handling & inheritance)__<br>
- exception handling ve dinamik ömürlü sınıf nesneleri __(eception handling & dynamic objects)__<br>
- exception  güvenliği için akıllı göstericilerin kullanımı __(eception handling & smart pointers)__<br>
- işlev try blokları __(function try block)__<br>
- noexcept belirleyicisi __(noexcept specifier)__<br>
- beklenmeyen hata nesnesi __(unexpected excetion)__<br>
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
- kendi hata sınıflarımızı oluşturmak __(custom exception classes)__<br>
- exception garantileri __(eception guarantees)__<br>
&emsp;&emsp;- __basic exception guarantee__<br>
&emsp;&emsp;- __strong exception guarantee__<br>
&emsp;&emsp;- __no throw guarantee__<br>
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
- karşılaştırma işlevleri __(comparision functions)__<br>
- sayısal dönüşüm işlevleri __(numeric conversions)__<br>
- küçük string optimizasyonu __(small string optimization)__<br>
- bir STL kabı olaral string sınıfı __(string class as STL container)__ <br>

## 📌Bileşik Nesneler _(Composition)_
- öğe olan nesneler ve özel işlevler, kopyalama kontrolü.<br>
- öğe olan nesneler ve erişim kontrolü<br>
- bileşik nesnelerin kullanıldığı temalar<br>

## 📌İçsel türler _(Type Members)_
- sınıf içinde yapılan eş isim bildirimleri<br>
- içsel sınıflar __(nested classes)__<br>
&emsp;&emsp;- erişim kontrolü __(access control)__<br>
&emsp;&emsp;- _pimpl_ idiyomu __(pimpl idiom)__

## 📌Şablonlar _(Templates)_
- şablon tür parametreleri __(template type parameters)__ <br>
- şablon sabit parametreleri __(template non-type parameters)__<br>
- şablon şablon parametreleri __(template template parameters)__<br>
- şablon argümanları __(template arguments)__<br>
&emsp;&emsp;- belirtilmiş template argümanları __(explicit template arguments)__<br>
&emsp;&emsp;- varsayılan template argümanları __(default template arguments)__<br>
- şablonlardan kod üretimi __(template instantiation)__<br>
- fonksiyon şablonları __(function templates)__<br>
&emsp;&emsp;- fonksiyon şablonlarında tür çıkarımı __(function template argument deduction)__<br>
&emsp;&emsp;- fonksiyon şablonlarının yüklenmesi __(function template overloading)__<br>
- sınıf şablonları __(class templates)__<br>
- kurucu işlev ile tür çıkarımı __(CTAD)__ (C++17)<br>
- üye şablonlar __(member templates)__<br>
- şablonların özelleştirilmesi __(template specialization)__<br>
&emsp;&emsp;- tam özelleştirme __(explicit/full specialization)__<br>
&emsp;&emsp;- kısmi özelleştirme __(partial specialization)__<br>
- __sfinae__<br>
- değişken sayıda parametreli şablonlar __(variadic templates)__<br>
- mükemmel gönderim __(perfect forwarding)__<br>
- katlama ifadeleri(C++17) __(fold expressions)__<br>
- __if constexpr__<br>
- değişken şablonları __(variable templates)__<br>
- eş isim şablonları __(alias templates)__<br>

## 📌İteratörler _(Iterators)_
- aralık kavramı __(ranges)__<br>
- iteratörlerin kategorileri __(iterator categories)__<br>
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
- iterator uyumlandırıcıları __(iterator adaptors)__<br>
&emsp;&emsp;- akım iteratörleri __(stream iterators)__<br>
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
- STL kapları ve veri yapıları __(STL containers & data structures)__ <br>
- sıralı kaplar __(sequence containers)__<br>
&emsp;&emsp;- std::vector<br>
&emsp;&emsp;- std::deque<br>
&emsp;&emsp;- std::string<br>
&emsp;&emsp;- std::array<br>
&emsp;&emsp;- std::list<br>
&emsp;&emsp;- std::forward_list<br>
- ilişkisel kaplar __(associative containers)__<br>
&emsp;&emsp;- std::set<br>
&emsp;&emsp;- std::multiset<br>
&emsp;&emsp;- std::map<br>
&emsp;&emsp;- std::multimap<br>
- sırasız ilişkisel kaplar __(unordered containers)__<br>
&emsp;&emsp;- std::unordered_set<br>
&emsp;&emsp;- std::unordered_multiset<br>
&emsp;&emsp;- std::unordered_map<br>
&emsp;&emsp;- std::unordered_multimap<br>
- kapların tür öğeleri __(type members of containers)__<br>
- kapların emplace işlevleri<br>

## 📌Kap Uyumlandırıcıları _(Container Adaptors)_
- std::stack<br>
- std::queue<br>
- std::priority_queue<br>

## 📌Algoritmalar _(Algorithms)_
- algoritmaların temel özellikleri ve genel ilkeler <br>
- salt okuyan algoritmalar __non-modifying algorithms)__<br>
- kap öğelerini değiştiren algoritmalar __(modifying algorithms)__<br>
- kap öğelerini konumlandıran algoritmalar __(mutating algorithms)__<br>
- sıralama ile ilgili algoritmalar __(sorting algorithms)__<br>
- sıralanmış aralıklar üzerinde koşturulan algoritmalar __(sorted range algorithms)__<br>
- nümerik algoritmalar __(numeric algorithms)__<br>
- algoritmaların lambda ifadelerini kullanması<br>

## 📌Lambda İfadeleri _(Lambda Expressions)_
- kapanış türleri ve kapanış nesneleri __(closure types and closure objects)__<br>
- lambda ifadeleri ve tür çıkarımı __(lambda expressions and type deduction)__<br>
- lambda yakalama ifadeleri __(lambda captures)__<br>
- _lambda init capture_<br>
- capture this <br>
- capture __*this__<br>
- mutable lambdalar<br>
- trailing return type<br>
- genelleştirilmiş lambda ifadeleri __(generalized lambda expressions)__<br>
- algoritmalarda lambda ifadelerinin kullanımı<br>
- lambda ifadeleri C++11/14/17/20<br>
- lambda idiyomları __(lambda idioms)__<br>

## 📌Akıllı Gösterici Sınıfları _(Standard Smart Pointer Classes)_
- std::unique_ptr sınıfı <br>
&emsp;&emsp;- std::make_unique işlev şablonu <br> 
&emsp;&emsp;- std::default_delete ve custom deleters <br>
&emsp;&emsp;- tipik hatalar <br>
- std::shared_ptr sınıfı<br>
&emsp;&emsp;- referans sayımı __(reference counting)__<br>
&emsp;&emsp;- std::make_shared işlev şablonu<br>
&emsp;&emsp;- std::weak_ptr sınıfı<br>

## 📌Standart Giriş Çıkış Kütüphanesi _(iostream Library)_
- giriş çıkış akımlarına ilişkin standart sınıflar __(standard stream classes)__ <br>
- global akım nesneleri __(global stream objects)__<br>
- formatlı giriş çıkış işlemleri __(formatted input output)__<br>
- << ve >> operatörlerinin yüklenmesi __(inserter & extractors)__<br>
- formatlama ve formatlama işlemleri __(formatting)__<br>
- manipülatörler __(manipulators)__<br>
- akımın durumu __(condition states)__<br>
- string akımları __(string streams)__<br>
- dosya işlemleri __(file operations)__<br>
- formatsız giriş ve çıkış işlemleri __(unformatted input output)__<br>
- bellek üstünde yapılan giriş çıkış işlemleri __(in-memory input output operations)__<br>

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
- aralık tabanlı for döngüleri __(range based for loops)__<br>
- ilk değer vermeli if ve switch deyimleri __(if/switch with initializers)__<br>
- static_assert <br>
- decltype(auto) tür çıkarımı<br>
- std::declval<br>
- üye fonksiyon göstericileri __(member function pointers)__<br>
- ham string sabitleri __(raw string literals)__<br>
- ikilik sayı sisteminde yazılan sabitler __(binary literals)__<br>
- basamak ayırıcısı __(digit seperator)__<br>
- ilk değer vermeli if deyimi (C++17) __(if with initializer)__<br>
- ilk değer vermeli switch  deyimi (C++17) __(if with initializer)__<br>
- alignas belirteci __(alignas specifier)__<br>
- alignof operatörü __(alignof operator)__<br>
- yapısal bağlama (C++17)__(structural binding)__<br>
- attribute’lar __(attributes)__<br>

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
- atomik türler __(atomic types)__<br>
- görev tabanlı __(task based)__ programlama<br>
- std::packaged_task sınıfı<br>
- paralel STL algoritmaları<br>
