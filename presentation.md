# [fit] :wave:
# Меня зовут @folone

![](https://cdn.eyeem.com/thumb/900/900/875ca603aa93985dfba529d82407d198ef9cad3d?highRes=true)

http://j.mp/tlc-talk

https://github.com/folone/scalaua

---

![fit](https://avatars2.githubusercontent.com/u/366132?v=3&s=1240)

---

![fit](http://i.imgur.com/RRDslOj.png)

---

![](https://dl.dropboxusercontent.com/u/4274210/sc_cmyk_white.ai)

---

![fill inline](https://i1.sndcdn.com/avatars-000115643651-71o36c-t500x500.jpg)![fill inline](https://i1.sndcdn.com/artworks-000037484402-x8gfft-t500x500.jpg)![fill inline](https://i1.sndcdn.com/avatars-000138955484-r3yxsu-t500x500.jpg)![fill inline](https://i1.sndcdn.com/avatars-000114613706-sva2ir-t500x500.jpg)
![fill inline](https://i1.sndcdn.com/avatars-000109087465-2uqbx8-t500x500.jpg)![fill inline](https://i1.sndcdn.com/avatars-000055035285-1i17eh-t500x500.jpg)![fill inline](https://i1.sndcdn.com/avatars-000077357035-7tbvde-t500x500.jpg)![fill inline](https://i1.sndcdn.com/artworks-000146844911-mgxgza-t500x500.jpg)

---

* 12 часов звуков ~10 миллионов создателей аплоадят каждую минуту
* ~35k лет прослушивания ежемесячно
* >125M треков (в.т.ч. контент от мейджор лейблов: Sony/Universal/Warner)
* ~170M активных пользователей каждый месяц

![left](https://cdn.eyeem.com/thumb/900/900/72a3ad530c5b60e4b6077536aecce56cbdf526c0?highRes=true)

^ в уникальной позиции мейджор лейблы и черный андерграунд, рассказать про лорде
^ 4x spotify audio (>1PB vs >5PB, 30M tracks vs 125M tracks)
^ 10x меньше людей чем в спотифае
^ гораздо более интерактивная платформа: пользователи напрямую интерактят с артистами
^ by a huge margin bigger than any competitor in both usage and amount of data (collection size)
^ except for youtube: that's bigger, but they aren't in the audio business per se

---

![](https://s3.amazonaws.com/f.cl.ly/items/0L1T380N1X3l262F3n3q/Image%202015-08-28%20at%203.51.58%20pm.png)

^ благодаря очень социальной натуре платформы, у нас бывает множество таких вот моментов
^ Drake vs Meek Mill

---

![fill](https://dl.dropboxusercontent.com/u/4274210/sc_cmyk_white.ai)

:heart:

![fill](http://www.scala-lang.org/resources/img/smooth-spiral@2x.png)

^ история про рейлз-апп, микросервисы, бфф
^ also clojure/jruby

---

# [fit] TLC
:ghost:

![](https://avatars3.githubusercontent.com/u/3731824)

---

# [fit] T-L-_шта?_[^0]
# [fit] *ಠ_ಠ*

![](https://cdn.eyeem.com/thumb/900/900/cb2220a35cd33c137a8e096e6471550253d80fe0?highRes=true)

[^0]: http://typelevel.org/blog/2014/09/02/typelevel-scala.html

^ TLC -- сокращение для "typelevel compiler". Имя активно эндорсится Дениелом Спиваком.
^ A scala fork made by the typelevel organization, to scratch an itch.
^ Typelevel Scala and the future of the Scala ecosystem

---

# [fit] Мы :heart: ![Скалу](http://www.scala-lang.org/resources/img/smooth-spiral@2x.png)

:ghost:

[Roll your own Scala](https://meta.plasm.us/posts/2015/07/11/roll-your-own-scala/)

![](https://cdn.eyeem.com/thumb/900/900/dba3443e5728917676bece667743d0762005145e?highRes=true)

^ В итоге, мы взяли пару довольно базовых (но все еще довольно таки поломанных) фич языка - синглтон-типы, рефайнмент типы, проэкции типов и имплиситную резолюцию - и с болью в глазах построили для себя надстройку над языком, которая по меньшей мере выглядит как нечто поддерживающее частичное применение типов, унификацию высшего уровня и несколько секций с имплиситными параметрами.

^ To recap: we’ve taken a few basic (but still pretty broken) Scala language features — singleton types, refinement types, type projections, and the implicit resolution system — and we’ve very painfully built a language for ourselves that at least kind of looks like it supports partial type parameter application, higher-order unification, and multiple implicit parameter sections.
 

---

# [fit] Мне кажется что это довольно прикольно.
# [fit] Но я также могу понять почему
# [fit] Многим это кажется
# [fit] удручающим.
-- Travis Brown

![](https://cdn.eyeem.com/thumb/900/900/934c62c288e50e609e02e11d584f3b8ea6651c78?highRes=true)

^ I think that’s pretty neat, but I can also understand why almost everyone else would find it horrifying.

^ Это не то почему люди начинают интересоваться скалой
^ но это то почему некоторые из них продолжают ей интересоваться (а не уходят в хаскелль например)

---

# [fit] TLC
:ghost:

![](https://avatars3.githubusercontent.com/u/3731824)

^ Для тех кто ностальгирует по дням до 2.10
^ Инкубатор новых идей
^ Полезен для тайпсейфа (лайтбенда): они не рискуют добавить бажную фичу которую потом некому будет саппортить
^ хорошие новости: скала скоро будет идеальной из-за эффекта третией системы (google it)
^ Мы не компайлер-девелоперы (пока что), все работаем на работах, и абсолютно не знаем что делаем. Так что не воспринимайте то что я рассказываю как нечто финальное, етс. Вся идея этого доклада - вдохновить сотрудничество вокруг скала-компилятора.
^ Also don't rely on our support for the same set of reasons
^ Обратная совместимость с тайпсейф-скалой

---

# [fit] scalaVersion        := "2.11.7"
# [fit] scalaOrganization   := "org.typelevel"

^ sbt is awesome, works starting from 0.13.6
^ 2.11.8-SNAPSHOT is published as well
^ 2.11.9-SNAPSHOT is published as well

---

# [some] Features

- Type lambdas
- `@implicitAmbiguous` (coming to 2.12 #4673)
- Прямая поддержка синглтон-типов
- -Zirrefutable-generator-patterns
- Прочие няшки

![left](https://cdn.eyeem.com/thumb/900/900/4c78f4df5242de6c55a02a8bad5345b766e66463?highRes=true)

---

# Type lambdas

```scala
trait Functor[F[_]] {
  def map[A, B](fa: F[A])(fn: A => B): F[B]
}

trait LeftFunctor[R] extends
  Functor[({type U[x] = Either[x, R]})#U]

trait RightFunctor[L] extends
  Functor[[y] => Either[L, y]]
```

---

# Type lambdas

```scala
[x] => (x, x)
[x, y] => (x, Int) => y
[x[_]] => x[Double]
[+x, -y] => Function1[y, x]
```

---

# [fit] Тайп-лямбды
# [fit] классные, и все дела,
# [fit] но в компиляторе нет ни единой
# [fit] строчки кода написанного
# [fit] для их поддержки
-- Paul Phillips (SI-6895)

^ Type lambdas are cool and all, but not a single line of the compiler was ever written with them in mind

![](https://cdn.eyeem.com/thumb/900/900/615f30b66478a6218aa3439bad83f5be9427481c?highRes=true)

---

# `@implicitAmbiguous`[^1]

```scala
// Encoding for "A is not a subtype of B"
trait <:!<[A, B]
 
// Uses ambiguity to rule out the cases we're trying to exclude
implicit def nsub[A, B] : A <:!< B = null
@typelevel.annotation.implicitAmbiguous("Returning ${B} is forbidden.")
implicit def nsubAmbig1[A, B >: A] : A <:!< B = null
implicit def nsubAmbig2[A, B >: A] : A <:!< B = null
 
// Type alias for context bound
type |¬|[T] = {
  type λ[U] = U <:!< T
}
 
```

[^1]: https://gist.github.com/milessabin/c9f8befa932d98dcc7a4

---

# `@implicitAmbiguous`

```scala
def foo[T, R : |¬|[Unit]#λ](t: T)(f: T => R) = f(t)
 
foo(23)(_ + 1)   // OK
foo(23)(println) // Doesn't compile: "Returning Unit is forbidden."
```

---

# Singleton types[^2]

```scala
trait Assoc[K] { type V ; val v: V }
 
def mkAssoc[K, V0](k: K, v0: V0): Assoc[k.type] { type V = V0 } =
  new Assoc[k.type] {type V = V0 ; val v = v0}
def lookup[K](k: K)(implicit a: Assoc[k.type]): a.V = a.v
```

[^2]: Требует флаг `-Xexperimental`

^ Adriaan's implementation

---

# Singleton types

```scala
implicit def firstAssoc = mkAssoc(1, "Panda!")
//> firstAssoc : Assoc[Int(1)]{type V = String}
implicit def secondAssoc = mkAssoc(2, 2.0)
//> secondAssoc : Assoc[Int(2)]{type V = Double}

implicit def ageAssoc = mkAssoc("Age", 3)
//> ageAssoc : Assoc[String("Age")]{type V = Int}
implicit def nmAssoc = mkAssoc("Name", "Jane")
//> nmAssoc : Assoc[String("Name")]{type V = String}
```

---

# Singleton types

```scala
lookup(1)
// > res1: String = Panda!
lookup(2)
// > res2: Double = 2.0
lookup("Age")
// > res3: Int = 3
lookup("Name")
// > res4: String = Jane
```

---

# Irrefutable generator patterns

```scala
  for {
    (x, _) <- Option((1, 2))
  } yield x
```

---

# Desugars to

```scala
Some(scala.Tuple2(1, 2))
  .withFilter(((check$ifrefutable$1) =>
    check$ifrefutable$1: @scala.unchecked match {
      case scala.Tuple2((x @ _), _) => true
      case _ => false
    })).map(((x$1) => x$1: @scala.unchecked match {
      case scala.Tuple2((x @ _), _) => x
    }))
```

---

# With irrefutable patterns

```scala
Some(scala.Tuple2(1, 2)).map(((x$1) => x$1 match {
  case scala.Tuple2((x @ _), _) => x
}))
```

^ Во втором варианте есть несколько явных разниц поведения:

^ Без флага, незаматченные значения будут отфильтрованы
^ С флагом, частичные паттерны выдадут warning, и могут бросить MatchError в рантайме
^ Без флага, слева нельзя иметь паттерны, если у штуки справа не заимплеменчен withFilter
^ С флагом, withFilter понадобится только если использовать guard (if)

---

# Няшки
```scala
def fib(n: Int) = {
  def fib'(n: Int, next: Int, £: Int): Int =
    n match {
      case 0 => £
      case _ => fib'(n - 1, next + £, next)
    }
  fib'(n, 1, 0)
}

val £': Byte  = 127z
```

![right](https://cdn.eyeem.com/thumb/900/900/10765bfb0c32a665f78ad5d90cebbb0f20672917?highRes=true)

^ Mention some nifty things added to the fork

---

# [fit] Общее виденье
:syringe: :mount_fuji:

![](https://cdn.eyeem.com/thumb/900/900/858bc4fabdc72956e045aadf29e0b58fa5162909?highRes=true)

^ никаких релизова 2.10
^ планируем скоро дропнуть 2.11, только 2.12, а то и прямиком на дотти (забутстрапился уже ж)
^ point is being on the bleeding edge
^ как видите, мы в основном добавляем небольшие штуки, и тестируем их
^ среди нас нет компайлер-разработчиков
^ когда-нибудь мы планируем стать лучше, и работать над более интересными вещами, имеющими большой эффект
^ compiler plugins

---

# [fit] Low-hanging fruits

* конвертация тестов из partest в junit
* документация
* репорт багов
* багфикс
* бекпорт изменений из тайпсейф-скалы

![right](https://cdn.eyeem.com/thumb/900/900/1e1b4616c6ba643147ff572c9592d981557470bf?highRes=true)

---

# [fit] Давайте пофантазируем

![](https://i.imgur.com/Ei14dfw.png)

^ Don't over-promise
^ Note: we aren't compiler devs yet, we have full time jobs, and really don't know what we're doing. So don't take anything here as a promise or a final dicision or anything that has any level of commitement. The whole point of this talk is to inspire collaboration.
^ This is just an exploration of possible ideas, no commitments, etc.
^ Никаких коммитментов, только фантазии

---

# [fit] Рефайнмент типы

^ can base them on top of literal-based singleton types
^ going to an external SMT like z3 to prove things about types
^ talked about this last year at scala.exchange
^ generally relying on something external to figure out types would allow us to get the benifits of external research for free as well

![](http://drorbn.net/bbs/shots/Itai-111108-131013.jpg)

---

# [fit] Рефайнмент типы

```scala
val x: 7.type = 7
```

![](http://drorbn.net/bbs/shots/Itai-111108-131013.jpg)

---

# [fit] Рефайнмент типы

```scala
val x: (t => 7).type = 7
```

![](http://drorbn.net/bbs/shots/Itai-111108-131013.jpg)

---

# [fit] Рефайнмент типы

```scala
val x: (t => t < 10 && t > 5).type = 7
```

![](http://drorbn.net/bbs/shots/Itai-111108-131013.jpg)

---

# [fit] Эксперименты со
# [fit] стандартной библиотекой

![](https://camo.githubusercontent.com/c7a1d594954b34a8277bce52343fe731b14870ad/687474703a2f2f706c61737469632d69646f6c617472792e636f6d2f6572696b2f63617473322e706e67)
![](https://camo.githubusercontent.com/c7a1d594954b34a8277bce52343fe731b14870ad/687474703a2f2f706c61737469632d69646f6c617472792e636f6d2f6572696b2f63617473322e706e67)

---

# [fit] Интегрейшн с
# [fit] альтернативным реплом

![](http://lihaoyi.github.io/Ammonite/GettingStarted.png)

^ Ammonite repl

---

# Продумать заново как работают имплиситы[^3]

![left](http://orig03.deviantart.net/870c/f/2013/141/2/6/mr__spock__zachary_quinto__by_lei_feiyang-d65xp7b.jpg)

[^3]: https://github.com/typelevel/scala/issues/28 -- `@implicitWeight`

There's a Prolog in your Scala

^ Презентация Адриаана
^ There's a prolog in your scala

---

```scala
scalaVersion      := "2.11.7"
scalaOrganization := "org.typelevel"
```

^ скомпилировали shapeless и cats этой версией
^ также работает со scala.js
^ если у кого-нибудь есть 2.11-only проект

---

# [fit] Как мне законтрибьютить?

`sbt compile`
`sbt test`
`sbt partest`

^ Компиляция со старта ~5mins
^ ant билд - легаси
^ `sbt publish-local`
^ `sbt test` ~3 minutes
^ `sbt partest` ~1-2 hours

![](https://cdn.eyeem.com/thumb/900/900/b3e399eb305e00d673d8db4d2a7e4a9506dbb140?highRes=true)

---
# `./tools/partest-ack`

![](https://cdn.eyeem.com/thumb/900/900/b3e399eb305e00d673d8db4d2a7e4a9506dbb140?highRes=true)

---

# [fit] В итоге

^ Beneficial for typesafe and typelevel
^ No community splitting
^ Bleeding edge
^ Try now, contribute
^ We'll be reviving the project, marking low-hanging fruit tasks, etc.

![](https://cdn.eyeem.com/thumb/900/900/df7222e32cfeba37071041878bf50cb62e709b06?highRes=true)

---

# [fit] Спасибо!

![](https://cdn.eyeem.com/thumb/900/900/cf7f3b70599927b329a4e56040f11e92084a0b40?highRes=true)
