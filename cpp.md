# 🔥 Roadmap C++
---

## ⚠️ PRÉ-REQUISITOS ASSUMIDOS

Este roadmap **NÃO é para iniciantes absolutos em programação**. Antes de começar, você PRECISA ter:

### 🎯 Essenciais (Obrigatórios)
- **Lógica de programação sólida**
  - Entender algoritmos básicos (ordenação, busca)
  - Conhecer estruturas de dados fundamentais (arrays, listas, pilhas, filas, árvores, grafos)
  - Resolver problemas algorítmicos básicos (nível Beecrowd/LeetCode easy)
  
- **Experiência prévia com programação**
  - Pelo menos 6-12 meses em QUALQUER linguagem (Python, Java, JavaScript, etc)
  - Já ter feito projetos completos (mesmo que pequenos)
  - Entender conceitos como variáveis, funções, loops, condicionais
  
- **Inglês técnico intermediário**
  - 90%+ da documentação, livros e recursos são em inglês
  - Capacidade de ler docs e stackoverflow
  - Entender error messages do compilador

### 💻 Conhecimentos Técnicos Base
- **Linha de comando básica**
  - Navegar diretórios (cd, ls/dir, pwd)
  - Criar/deletar arquivos
  - Rodar programas da linha de comando
  - Entender PATH e variáveis de ambiente
  
- **Noções de sistemas operacionais**
  - O que é um processo
  - O que é memória RAM vs storage
  - Conceito de arquivos e diretórios
  - Permissões básicas (Linux/Mac)

- **Git básico (desejável)**
  - clone, add, commit, push, pull
  - Não precisa ser expert, mas ajuda MUITO

### 🧮 Matemática e CS Fundamentals
- **Matemática do ensino médio**
  - Álgebra básica
  - Logaritmos (para análise de complexidade)
  - Noções de probabilidade (para algorithms)
  
- **Estruturas de dados (conceitual)**
  - Complexidade Big O (O(1), O(n), O(log n), O(n²))
  - Arrays vs Linked Lists
  - Hash tables (conceito)
  - Trees (binary, BST)
  - Graphs (conceito)
  
- **Algoritmos fundamentais (conceitual)**
  - Busca linear e binária
  - Algoritmos de ordenação (bubble, insertion, merge, quick)
  - Recursão
  - BFS/DFS básico

### 🚫 O que NÃO é necessário (mas ajuda)
- ❌ Conhecer C (mas se souber, ajuda 80%)
- ❌ Ter diploma em CS (autodidatas bem-vindos)
- ❌ Saber Assembly
- ❌ Ter trabalhado profissionalmente
- ❌ Matemática avançada (cálculo, álgebra linear) - só pra domínios específicos

### 🔥 Mindset Necessário
- **Paciência infinita** - C++ vai te frustrar MUITO
- **Gostar de entender "como as coisas funcionam"** - Low-level mindset
- **Não ter medo de ler documentação densa**
- **Aceitar que vai passar horas debugando** - Isso é normal
- **Curiosidade técnica** - Querer saber "por que" isso dá segfault

---

## 🛤️ Caminhos Alternativos

### Se você é TOTAL INICIANTE:
1. **Aprenda Python ou JavaScript primeiro** (6-12 meses)
   - Domine lógica de programação
   - Faça 50+ exercícios de algoritmos
   - Construa 5+ projetos completos
   
2. **Depois considere C antes de C++** (2-3 meses)
   - "The C Programming Language" (K&R)
   - Aprenda ponteiros, memória, arrays em C puro
   - Isso vai fazer C++ fazer MUITO mais sentido

3. **Então volte aqui** e comece na Fase 1

### Se você vem de linguagens de alto nível:
- **De Python/JavaScript/Ruby → C++:**
  - ATENÇÃO: vai ser choque cultural GIGANTE
  - Esqueça garbage collection, existe delete aqui
  - Esqueça duck typing, C++ é strongly typed
  - Performance é TUDO aqui
  
- **De Java/C# → C++:**
  - Transição mais suave (OOP similar)
  - MAS: sem garbage collector, cuidado com memória
  - MAS: templates ≠ generics (muito mais poderosos e complexos)
  - MAS: multiple inheritance existe (com todos os problemas)

- **De C → C++:**
  - Você tem VANTAGEM GIGANTE
  - Já entende ponteiros e memória
  - Aprenda a "desaprender" alguns C-isms
  - C++ não é "C com classes", é outra linguagem

---

## 📋 Estrutura do Roadmap

Este roadmap está dividido em 7 fases progressivas. Cada fase constrói sobre a anterior e aumenta exponencialmente em complexidade. 

**Estimativa total: 2-4 anos de estudo intensivo** (assumindo os pré-requisitos acima).

---

## 🌱 Fase 1: Fundamentos Sólidos (3-4 meses)

### Sintaxe e Conceitos Básicos
- **Tipos de dados primitivos e compostos**
  - Entender representação em memória de cada tipo
  - Signed vs unsigned, overflow, underflow
  - Conversões implícitas e explícitas (casting)
  
- **Controle de fluxo**
  - if/else, switch, loops (for, while, do-while)
  - break, continue, goto (e por que evitar goto)
  
- **Funções**
  - Declaração vs definição
  - Protótipos
  - Passagem por valor vs referência vs ponteiro
  - Inline functions
  - Function overloading
  - Default arguments

### Ponteiros e Memória
- **Ponteiros básicos**
  - Declaração, inicialização, dereferenciação
  - Aritmética de ponteiros
  - Ponteiros para ponteiros
  - Ponteiros para funções
  - Arrays e sua relação com ponteiros
  
- **Gerenciamento manual de memória**
  - Stack vs Heap
  - new/delete, new[]/delete[]
  - Memory leaks e como evitá-los
  - Valgrind para detecção de leaks

### Arrays e Strings
- Arrays estáticos e dinâmicos
- Strings C-style (char arrays)
- String manipulation básica
- std::string introduction

### Estruturas de Controle Avançadas
- Structs básicos
- Enums
- Unions (e quando usar)

**Projetos Práticos:**
1. Calculadora científica com histórico
2. Sistema de gerenciamento de biblioteca (CRUD básico)
3. Jogo da velha com IA básica
4. Analisador de texto (contador de palavras, frequência)

**Recursos:**
- Livro: "C++ Primer" (Stanley Lippman) - Capítulos 1-7
- Online: learncpp.com (até capítulo 11)

---

## 🏗️ Fase 2: POO e STL Essencial (4-5 meses)

### Programação Orientada a Objetos
- **Classes e Objetos**
  - Encapsulamento, membros public/private/protected
  - Construtores (default, parametrizado, copy, move)
  - Destrutor e RAII (Resource Acquisition Is Initialization)
  - this pointer
  - const member functions
  - static members
  - friend functions e classes
  
- **Herança**
  - Single inheritance
  - Multiple inheritance e problemas do diamante
  - Virtual inheritance
  - Acesso: public, protected, private inheritance
  
- **Polimorfismo**
  - Function overriding
  - Virtual functions e vtables
  - Pure virtual functions e classes abstratas
  - Virtual destructors (CRÍTICO)
  - Slicing problem
  
- **Operator Overloading**
  - Operators aritméticos, comparação, atribuição
  - Stream operators (<<, >>)
  - Subscript operator []
  - Function call operator ()
  - Conversion operators

### STL - Standard Template Library
- **Containers Sequenciais**
  - std::vector (o mais usado)
  - std::deque
  - std::list
  - std::forward_list
  - std::array
  - Quando usar cada um (complexidade)
  
- **Containers Associativos**
  - std::set / std::multiset
  - std::map / std::multimap
  - std::unordered_set / std::unordered_multiset
  - std::unordered_map / std::unordered_multimap
  - Hash functions e colisões
  
- **Container Adapters**
  - std::stack
  - std::queue
  - std::priority_queue
  
- **Iteradores**
  - Input, Output, Forward, Bidirectional, Random Access
  - begin(), end(), rbegin(), rend()
  - Iterator invalidation

- **Algoritmos STL**
  - std::sort, std::stable_sort
  - std::find, std::binary_search
  - std::copy, std::move
  - std::transform
  - std::accumulate
  - Predicates e comparadores customizados

### Exception Handling
- try/catch/throw
- Exception hierarchy
- std::exception e classes derivadas
- Exception safety guarantees (basic, strong, nothrow)
- RAII para exception safety
- noexcept specifier

**Projetos Práticos:**
1. Sistema bancário OOP completo (contas, transações, herança)
2. Engine de jogo 2D básico com hierarquia de objetos
3. Biblioteca de estruturas de dados customizadas
4. Simulador de ecossistema com polimorfismo

**Recursos:**
- Livro: "Effective C++" (Scott Meyers)
- Livro: "C++ Primer" - Capítulos 8-16
- cppreference.com para STL

---

## ⚡ Fase 3: C++ Moderno (C++11/14/17) (4-6 meses)

### Smart Pointers e Ownership
- **std::unique_ptr**
  - Move semantics
  - Custom deleters
  - std::make_unique
  
- **std::shared_ptr**
  - Reference counting
  - Control block
  - std::make_shared
  - Circular reference problem
  
- **std::weak_ptr**
  - Breaking cycles
  - Observer pattern
  
- **Ownership models**
  - Unique ownership
  - Shared ownership
  - Borrow (referências)

### Move Semantics e Perfect Forwarding
- **Rvalue references (&&)**
- **std::move e std::forward**
- **Move constructors e move assignment**
- **Rule of Zero/Three/Five**
- **Return Value Optimization (RVO) e NRVO**
- **Copy elision**

### Templates Intermediários
- **Function templates**
- **Class templates**
- **Template specialization (full e partial)**
- **Variadic templates**
- **Template template parameters**
- **SFINAE (Substitution Failure Is Not An Error)**
- **std::enable_if**
- **Type traits**

### Lambdas e Functional Programming
- **Lambda syntax**
- **Capture lists (=, &, this)**
- **Mutable lambdas**
- **Generic lambdas (C++14)**
- **std::function**
- **std::bind**
- **Higher-order functions**

### Novos Recursos C++11/14/17
- **auto e decltype**
- **Range-based for loops**
- **nullptr**
- **constexpr**
- **enum class (scoped enums)**
- **std::optional**
- **std::variant**
- **std::any**
- **Structured bindings (C++17)**
- **if constexpr (C++17)**
- **Fold expressions (C++17)**
- **std::string_view**
- **std::filesystem**

### Concorrência Básica
- **std::thread**
- **std::mutex e std::lock_guard**
- **std::unique_lock**
- **std::condition_variable**
- **std::atomic**
- **Memory ordering basics**
- **Race conditions e deadlocks**
- **std::async e std::future**

**Projetos Práticos:**
1. Memory pool allocator customizado
2. Thread-safe queue e object pool
3. Sistema de eventos com lambdas e callbacks
4. Parser de JSON moderno
5. Servidor HTTP multithreaded básico

**Recursos:**
- Livro: "Effective Modern C++" (Scott Meyers)
- Livro: "C++ Concurrency in Action" (Anthony Williams) - Primeiros capítulos
- Videos: CppCon talks sobre move semantics e templates

---

## 🧠 Fase 4: Templates Avançados e Metaprogramação (5-6 meses)

### Template Metaprogramming (TMP)
- **Compile-time computation**
- **Type computation**
- **Template recursion**
- **Value computations em compile-time**
- **Conditional compilation**
- **constexpr programming**
- **consteval e constinit (C++20)**

### Type Traits e SFINAE Avançado
- **Criando seus próprios type traits**
- **std::is_same, std::is_base_of, etc.**
- **std::enable_if_t, std::void_t**
- **Detection idiom**
- **Tag dispatching**
- **if constexpr para substituir SFINAE**

### Concepts (C++20)
- **Definindo concepts**
- **Requires clauses**
- **Requires expressions**
- **Standard library concepts**
- **Subsumption**
- **Concept composition**

### Variadic Templates Avançado
- **Parameter packs**
- **Pack expansion**
- **Fold expressions avançadas**
- **std::tuple implementation**
- **std::apply e std::invoke**

### Template Design Patterns
- **CRTP (Curiously Recurring Template Pattern)**
- **Policy-based design**
- **Expression templates**
- **Tag dispatching**
- **Type erasure**
- **Mixins**

### Ranges (C++20)
- **Range concepts**
- **Views e adaptors**
- **Range algorithms**
- **Lazy evaluation**
- **Composing views**
- **Custom ranges**

**Projetos Práticos:**
1. Biblioteca de serialização type-safe
2. Expression template library para álgebra linear
3. Compile-time regex matcher
4. Type-safe units library (dimensões físicas)
5. Custom STL-like container com full iterator support

**Recursos:**
- Livro: "C++ Templates: The Complete Guide" (Vandevoorde, Josuttis)
- Livro: "Modern C++ Design" (Andrei Alexandrescu)
- Papers: C++20 ranges papers

---

## 🏆 Fase 5: Performance e Otimização (4-5 meses)

### Arquitetura de Computador Relevante
- **Cache hierarchy (L1, L2, L3)**
- **Cache lines e false sharing**
- **Prefetching**
- **Branch prediction**
- **SIMD (SSE, AVX)**
- **Memory alignment**
- **Data-oriented design**

### Profiling e Benchmarking
- **Ferramentas:**
  - perf (Linux)
  - Valgrind (cachegrind, callgrind)
  - Google Benchmark
  - Intel VTune
  - gprof
  
- **Metodologia:**
  - Microbenchmarks vs macrobenchmarks
  - Overhead measurement
  - Statistical significance
  - Avoiding optimizer tricks

### Otimizações de Compilador
- **Optimization flags (-O0, -O1, -O2, -O3, -Ofast)**
- **Link Time Optimization (LTO)**
- **Profile-Guided Optimization (PGO)**
- **Inlining strategies**
- **Vectorization (auto-vectorization)**
- **Compiler intrinsics**
- **Reading assembly output**

### Memory Optimization
- **Memory layout optimization**
- **Struct packing e padding**
- **Small String Optimization (SSO)**
- **Custom allocators**
- **Memory pools**
- **Arena allocators**
- **Stack allocators**
- **PMR (Polymorphic Memory Resources)**

### Algoritmo e Estrutura de Dados Optimization
- **Cache-friendly data structures**
- **B-trees vs binary trees**
- **Hash table optimization**
- **String optimization (interning, SSO)**
- **Flat containers vs node-based**
- **SoA vs AoS (Structure of Arrays vs Array of Structures)**

### Low-Level Optimization Techniques
- **Loop unrolling**
- **Strength reduction**
- **Dead code elimination**
- **Common subexpression elimination**
- **Constant folding**
- **Tail call optimization**
- **Bit manipulation tricks**

### SIMD Programming
- **Intrinsics (SSE, AVX, AVX-512)**
- **Auto-vectorization**
- **Data alignment para SIMD**
- **Horizontal vs vertical operations**
- **Libraries: xsimd, highway**

**Projetos Práticos:**
1. Implementar std::vector otimizado competitivo
2. High-performance hash table
3. SIMD-optimized image processing library
4. Memory allocator benchmark suite
5. Database-style query engine com column store

**Recursos:**
- Livro: "Optimizing C++" (Agner Fog) - GRATUITO online
- Website: agner.org/optimize
- Livro: "Data-Oriented Design" (Richard Fabian)
- Talks: Chandler Carruth sobre optimization

---

## 🔮 Fase 6: Concorrência Avançada e Sistemas (5-7 meses)

### Memory Model e Atomics
- **Happens-before relationship**
- **Memory orderings:**
  - memory_order_relaxed
  - memory_order_consume
  - memory_order_acquire
  - memory_order_release
  - memory_order_acq_rel
  - memory_order_seq_cst
  
- **Atomic operations**
- **CAS (Compare-And-Swap)**
- **ABA problem**
- **Memory barriers/fences**

### Lock-Free Programming
- **Lock-free vs wait-free**
- **Lock-free data structures:**
  - Queue
  - Stack
  - Hash table
  - List
  
- **Hazard pointers**
- **RCU (Read-Copy-Update)**
- **Epoch-based reclamation**

### Advanced Threading
- **Thread pools**
- **Work stealing**
- **Coroutines (C++20)**
- **std::jthread (C++20)**
- **std::latch e std::barrier (C++20)**
- **std::counting_semaphore (C++20)**

### Asynchronous Programming
- **Futures e promises avançado**
- **Continuations**
- **std::async policies**
- **Packaged tasks**
- **Callback hell e soluções**

### Systems Programming
- **System calls**
- **File I/O (POSIX, Windows)**
- **Memory-mapped files**
- **Sockets e networking**
- **Process management**
- **Signals (Unix)**
- **Interprocess communication:**
  - Pipes
  - Shared memory
  - Message queues
  - Semaphores
  
### Debugging Avançado
- **GDB avançado**
- **Core dumps analysis**
- **Memory sanitizers:**
  - AddressSanitizer (ASan)
  - MemorySanitizer (MSan)
  - ThreadSanitizer (TSan)
  - UndefinedBehaviorSanitizer (UBSan)
  
- **Static analysis:**
  - clang-tidy
  - cppcheck
  - PVS-Studio

**Projetos Práticos:**
1. Lock-free queue production-ready
2. Actor model framework
3. Async I/O library (epoll/kqueue/IOCP)
4. Task scheduler com work stealing
5. Distributed key-value store básico

**Recursos:**
- Livro: "C++ Concurrency in Action" (Anthony Williams) - COMPLETO
- Livro: "The Art of Multiprocessor Programming" (Herlihy, Shavit)
- Paper: "Hazard Pointers: Safe Memory Reclamation for Lock-Free Objects"
- Blog: preshing.com

---

## 🌌 Fase 7: God Level - Mastery (Ongoing)

### Compiler Development
- **Lexical analysis**
- **Parsing (recursive descent, LR)**
- **Abstract Syntax Trees (AST)**
- **Semantic analysis**
- **Intermediate representations**
- **Code generation**
- **Register allocation**
- **Estudar LLVM e Clang source code**

### Standard Library Implementation
- **Estudar implementações:**
  - libstdc++ (GCC)
  - libc++ (LLVM)
  - MSVC STL
  
- **Implementar do zero:**
  - std::vector
  - std::string
  - std::unique_ptr / std::shared_ptr
  - std::function
  - std::map (Red-Black tree)
  - std::unordered_map

### C++ Standard Evolution
- **Ler papers do WG21**
- **Entender o processo de standardization**
- **Estudar propostas rejeitadas e aceitas**
- **Contribuir para discussões**
- **Principais features futuras (C++23, C++26)**

### Advanced Design Patterns
- **Modern C++ Patterns:**
  - RAII variants
  - PIMPL idiom
  - Copy-and-swap idiom
  - Non-copyable/movable classes
  - Resource handles
  
- **Concurrency Patterns:**
  - Producer-consumer
  - Read-write locks
  - Monitor pattern
  - Active object
  
- **Generic Programming Patterns:**
  - Policy-based design
  - Traits
  - Tag dispatching
  - Type erasure
  - Dependency injection

### Specific Domains (escolha 1-2)
- **Game Development:**
  - Entity Component System (ECS)
  - Engine architecture
  - Graphics programming (Vulkan, DirectX)
  - Physics engines
  
- **High-Performance Computing:**
  - MPI programming
  - CUDA/GPU programming
  - Distributed systems
  
- **Systems Programming:**
  - Operating system development
  - Device drivers
  - Embedded systems
  
- **Financial Systems:**
  - Ultra-low latency
  - Quantitative finance libraries
  
- **Computer Graphics:**
  - Ray tracing
  - Rasterization
  - Shaders

### Open Source Contribution
- **Estudar projetos grandes:**
  - LLVM/Clang
  - Chromium
  - Qt
  - Boost
  - Unreal Engine (se tiver acesso)
  
- **Contribuir:**
  - Bug fixes
  - Performance improvements
  - New features
  - Documentation

### Continuous Learning
- **Acompanhar:**
  - CppCon talks (ANUAL)
  - Meeting C++ talks
  - C++ Weekly (Jason Turner)
  - /r/cpp no Reddit
  - isocpp.org
  
- **Ler código de experts:**
  - Sean Parent
  - Chandler Carruth
  - Andrei Alexandrescu
  - Herb Sutter
  - Bjarne Stroustrup

**Projetos God-Level:**
1. Seu próprio mini-compilador de C++ subset
2. Game engine 3D completo
3. High-frequency trading system simulator
4. Custom memory allocator competitivo com tcmalloc/jemalloc
5. Contribuição significativa para projeto open source major
6. Database engine from scratch
7. JIT compiler para linguagem própria

**Recursos:**
- Todo CppCon no YouTube (centenas de horas)
- Livro: "Elements of Programming" (Stepanov)
- Livro: "From Mathematics to Generic Programming" (Stepanov)
- Standard Drafts: eel.is/c++draft
- Compiler Explorer: godbolt.org (vida toda)

---

## 📚 Bibliografia Essencial (Leia Tudo)

### Fundamentais
1. **"C++ Primer"** - Stanley Lippman
2. **"Effective C++"** - Scott Meyers
3. **"More Effective C++"** - Scott Meyers
4. **"Effective Modern C++"** - Scott Meyers
5. **"Effective STL"** - Scott Meyers

### Avançado
6. **"C++ Templates: The Complete Guide"** - Vandevoorde, Josuttis, Gregor
7. **"Modern C++ Design"** - Andrei Alexandrescu
8. **"C++ Concurrency in Action"** - Anthony Williams
9. **"The C++ Programming Language"** - Bjarne Stroustrup
10. **"Optimizing C++"** - Agner Fog (FREE)

### Design e Arquitetura
11. **"Design Patterns"** - Gang of Four
12. **"Large-Scale C++ Software Design"** - John Lakos
13. **"C++ Coding Standards"** - Sutter & Alexandrescu

### Especializado
14. **"Real-Time C++"** - Christopher Kormanyos
15. **"Beautiful C++"** - J. Guy Davidson & Kate Gregory
16. **"Data-Oriented Design"** - Richard Fabian

---

## 🛠️ Ferramentas Essenciais

### Compiladores (domine os 3)
- **GCC** (g++)
- **Clang** (clang++)
- **MSVC** (cl.exe)

### Build Systems
- **CMake** (ESSENCIAL)
- **Make**
- **Ninja**
- **Meson**

### Debuggers
- **GDB** (Linux)
- **LLDB** (macOS/Linux)
- **Visual Studio Debugger** (Windows)
- **RR** (record-replay debugger)

### Profilers
- **perf** (Linux)
- **Valgrind** (memcheck, cachegrind, callgrind)
- **Google Benchmark**
- **Intel VTune**

### Static Analysis
- **clang-tidy**
- **cppcheck**
- **PVS-Studio**
- **Coverity**

### Sanitizers
- **AddressSanitizer**
- **ThreadSanitizer**
- **MemorySanitizer**
- **UndefinedBehaviorSanitizer**

### IDE/Editors
- **Visual Studio** (Windows)
- **Visual Studio Code** + extensions
- **CLion** (JetBrains)
- **Vim/Neovim** + LSP
- **Emacs** + LSP

### Version Control
- **Git** (obrigatório, nível avançado)

---

## 🎯 Milestones de Progresso

### Nível 1: Novice (3-6 meses)
- ✅ Escreve programas básicos sem consultar documentação
- ✅ Entende ponteiros e memória
- ✅ Usa arrays e strings
- ✅ Sabe quando usar struct vs class

### Nível 2: Intermediate (1-1.5 anos)
- ✅ Escreve código OOP idiomático
- ✅ Usa STL fluentemente
- ✅ Entende exception safety
- ✅ Debugga segfaults sem sofrimento
- ✅ Conhece os "gotchas" básicos do C++

### Nível 3: Advanced (2-2.5 anos)
- ✅ Domina move semantics
- ✅ Escreve templates não-triviais
- ✅ Entende smart pointers profundamente
- ✅ Programa concorrente sem data races
- ✅ Lê assembly para otimizar
- ✅ Usa concepts naturalmente

### Nível 4: Expert (3-3.5 anos)
- ✅ Escreve template metaprogramming complexo
- ✅ Implementa estruturas lock-free
- ✅ Entende memory model profundamente
- ✅ Otimiza código competitivamente
- ✅ Contribui para projetos open source grandes
- ✅ Conhece edge cases obscuros do standard

### Nível 5: GOD (4+ anos)
- ✅ Pode implementar partes do compilador
- ✅ Pode implementar partes da STL competitivamente
- ✅ Lê papers do WG21 e opina com propriedade
- ✅ Reconhecido na comunidade C++
- ✅ Outros devs te perguntam coisas
- ✅ Você é o "C++ guy" onde trabalha
- ✅ Pode explicar por que algo é undefined behavior de cabeça
- ✅ Sonha com segfaults e acorda sabendo o fix

---

## 🔥 Desafios Extremos (Para Testar God Level)

1. **Implemente std::function do zero** com small object optimization

2. **Escreva um allocator** que bata jemalloc em benchmarks específicos

3. **Crie um framework de serialização** type-safe com zero overhead

4. **Implemente coroutines** sem usar C++20 coroutines (estilo Boost.Coroutine)

5. **Escreva um JIT compiler** simples usando LLVM

6. **Crie um garbage collector** conservativo para C++

7. **Implemente std::shared_ptr** com atomic ref counting thread-safe

8. **Faça um ray tracer** que compile-time compute o máximo possível

9. **Escreva uma async runtime** estilo Tokio mas para C++

10. **Implemente expression templates** para uma DSL matemática

---

### Mindset Necessário:
- 🔥 **Resiliência brutal** - Vai ter MUITO segfault, MUITO
- 🧠 **Curiosidade infinita** - Por que isso dá segfault?
- 📖 **Leitura de código** - Leia MUITO código de experts
- 🐛 **Debug mindset** - Aprenda a amar o debugger
- ⚡ **Performance obsession** - "Por que isso é lento?"
- 📚 **Continuous learning** - C++ evolui RÁPIDO (C++11/14/17/20/23)

### Red Flags para Evitar:
- ❌ Usar `using namespace std;`
- ❌ Raw pointers quando smart pointers cabem
- ❌ Manual memory management quando RAII cabe
- ❌ Macros quando templates cabem
- ❌ C-style casts quando C++ casts cabem
- ❌ `NULL` em vez de `nullptr`
- ❌ Arrays C quando `std::array`/`std::vector` cabem

**Boa sorte, guerreiro. Você vai precisar.**

*"C gives you enough rope to hang yourself. C++ also gives you enough rope to bind and gag your neighborhood, rig the sails on a small ship, and still have enough left over to hang yourself from the yardarm."* - Author Unknown
