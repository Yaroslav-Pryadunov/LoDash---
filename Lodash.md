# LoDash

## Содержание

### [● Array](#array)

- [`_.chunk`](#chunk)
- [`_.compact`](#compact)
- [`_.concat`](#concat)
- [`_.difference`](#difference)
- [`_.differenceBy`](#differenceby)
- [`_.differenceWith`](#differencewith)
- [`_.drop`](#drop)
- [`_.dropRight`](#dropright)
- [`_.dropRightWhile`](#droprightwhile)
- [`_.dropWhile`](#dropwhile)
- [`_.fill`](#fill)
- [`_.findIndex`](#findindex)
- [`_.findLastIndex`](#findlastindex)
- [`_.first` -> `head`](#head)
- [`_.flatten`](#flatten)
- [`_.flattenDeep`](#flattendeep)
- [`_.flattenDepth`](#flattendepth)
- [`_.fromPairs`](#frompairs)
- [`_.head`](#head)
- [`_.indexOf`](#indexof)
- [`_.initial`](#initial)
- [`_.intersection`](#intersection)
- [`_.intersectionBy`](#intersectionby)
- [`_.intersectionWith`](#intersectionwith)
- [`_.join`](#join)
- [`_.last`](#last)
- [`_.lastIndexOf`](#lastindexof)
- [`_.nth`](#nth)
- [`_.pull`](#pull)
- [`_.pullAll`](#pullall)
- [`_.pullAllBy`](#pullallby)
- [`_.pullAllWith`](#pullallwith)
- [`_.pullAt`](#pullat)
- [`_.remove`](#remove)
- [`_.reverse`](#reverse)
- [`_.slice`](#slice)
- [`_.sortedIndex`](#sortedindex)
- [`_.sortedIndexBy`](#sortedindexby)
- [`_.sortedIndexOf`](#sortedindexof)
- [`_.sortedLastIndex`](#sortedlastindex)
- [`_.sortedLastIndexBy`](#sortedlastindexby)
- [`_.sortedLastIndexOf`](#sortedlastindexof)
- [`_.sortedUniq`](#sorteduniq)
- [`_.sortedUniqBy`](#sorteduniqby)
- [`_.tail`](#tail)
- [`_.take`](#take)
- [`_.takeRight`](#takeright)
- [`_.takeRightWhile`](#takerightwhile)
- [`_.takeWhile`](#takewhile)
- [`_.union`](#union)
- [`_.unionBy`](#unionby)
- [`_.unionWith`](#unionwith)
- [`_.uniq`](#uniq)
- [`_.uniqBy`](#uniqby)
- [`_.uniqWith`](#uniqwith)
- [`_.unzip`](#unzip)
- [`_.unzipWith`](#unzipwith)
- [`_.without`](#without)
- [`_.xor`](#xor)
- [`_.xorBy`](#xorby)
- [`_.xorWith`](#xorwith)
- [`_.zip`](#zip)
- [`_.zipObject`](#zipobject)
- [`_.zipObjectDeep`](#zipobjectdeep)
- [`_.zipWith`](#zipwith)

### [● Collection](#collection)

- [`_.countBy`](#countby)
- [`_.each` -> `forEach`](#foreach)
- [`_.eachRight` -> `forEachRight`](#foreachright)
- [`_.every`](#every)
- [`_.filter`](#filter)
- [`_.find`](#find)
- [`_.findLast`](#findlast)
- [`_.flatMap`](#flatmap)
- [`_.flatMapDeep`](#flatmapdeep)
- [`_.flatMapDepth`](#flatmapdepth)
- [`_.forEach`](#foreach)
- [`_.forEachRight`](#foreachright)
- [`_.groupBy`](#groupby)
- [`_.includes`](#includes)
- [`_.invokeMap`](#invokemap)
- [`_.keyBy`](#keyby)
- [`_.map`](#map)
- [`_.orderBy`](#orderby)
- [`_.partition`](#partition)
- [`_.reduce`](#reduce)
- [`_.reduceRight`](#reduceright)
- [`_.reject`](#reject)
- [`_.sample`](#sample)
- [`_.sampleSize`](#samplesize)
- [`_.shuffle`](#shuffle)
- [`_.size`](#size)
- [`_.some`](#some)
- [`_.sortBy`](#sortBy)

### [● Date](#date)

- [`_.now`](#now)

### [● Function](#function)

- [`_.after`](#after)
- [`_.ary`](#ary)
- [`_.before`](#before)
- [`_.bind`](#bind)
- [`_.bindKey`](#bindkey)
- [`_.curry`](#curry)
- [`_.curryRight`](#curryright)
- [`_.debounce`](#debounce)
- [`_.defer`](#defer)
- [`_.delay`](#delay)
- [`_.flip`](#flip)
- [`_.memoize`](#memoize)
- [`_.negate`](#negate)
- [`_.once`](#once)
- [`_.overArgs`](#overargs)
- [`_.partial`](#partial)
- [`_.partialRight`](#partialright)
- [`_.rearg`](#rearg)
- [`_.rest`](#rest)
- [`_.spread`](#spread)
- [`_.throttle`](#throttle)
- [`_.unary`](#unary)
- [`_.wrap`](#wrap)

### [● Lang](#lang)

- [`_.castArray`](#castarray)
- [`_.clone`](#clone)
- [`_.cloneDeep`](#clonedeep)
- [`_.cloneDeepWith`](#clonedeepwith)
- [`_.cloneWith`](#clonewith)
- [`_.conformsTo`](#conformsto)
- [`_.eq`](#eq)
- [`_.gt`](#gt)
- [`_.gte`](#gte)
- [`_.isArguments`](#isarguments)
- [`_.isArray`](#isarray)
- [`_.isArrayBuffer`](#isarraybuffer)
- [`_.isArrayLike`](#isarraylike)
- [`_.isArrayLikeObject`](#isarraylikeobject)
- [`_.isBoolean`](#isboolean)
- [`_.isBuffer`](#isbuffer)
- [`_.isDate`](#isdate)
- [`_.isElement`](#iselement)
- [`_.isEmpty`](#isempty)
- [`_.isEqual`](#isequal)
- [`_.isEqualWith`](#isequalwith)
- [`_.isError`](#iserror)
- [`_.isFinite`](#isfinite)
- [`_.isFunction`](#isfunction)
- [`_.isInteger`](#isinteger)
- [`_.isLength`](#islength)
- [`_.isMap`](#ismap)
- [`_.isMatch`](#ismatch)
- [`_.isMatchWith`](#ismatchwith)
- [`_.isNaN`](#isnan)
- [`_.isNative`](#isnative)
- [`_.isNil`](#isnil)
- [`_.isNull`](#isnull)
- [`_.isNumber`](#isnumber)
- [`_.isObject`](#isobject)
- [`_.isObjectLike`](#isobjectlike)
- [`_.isPlainObject`](#isplainobject)
- [`_.isRegExp`](#isregexp)
- [`_.isSafeInteger`](#issafeinteger)
- [`_.isSet`](#isset)
- [`_.isString`](#isstring)
- [`_.isSymbol`](#issymbol)
- [`_.isTypedArray`](#istypedarray)
- [`_.isUndefined`](#isundefined)
- [`_.isWeakMap`](#isweakmap)
- [`_.isWeakSet`](#isweakset)
- [`_.lt`](#lt)
- [`_.lte`](#lte)
- [`_.toArray`](#toarray)
- [`_.toFinite`](#tofinite)
- [`_.toInteger`](#tointeger)
- [`_.toLength`](#tolength)
- [`_.toNumber`](#tonumber)
- [`_.toPlainObject`](#toplainobject)
- [`_.toSafeInteger`](#tosafeinteger)
- [`_.toString`](#tostring)

### [● Math](#math)

- [`_.add`](#add)
- [`_.ceil`](#ceil)
- [`_.divide`](#divide)
- [`_.floor`](#floor)
- [`_.max`](#max)
- [`_.maxBy`](#maxby)
- [`_.mean`](#mean)
- [`_.meanBy`](#meanby)
- [`_.min`](#min)
- [`_.minBy`](#minby)
- [`_.multiply`](#multiply)
- [`_.round`](#round)
- [`_.subtract`](#subtract)
- [`_.sum`](#sum)
- [`_.sumBy`](#sumby)

### [● Number](#number)

- [`_.clamp`](#clamp)
- [`_.inRange`](#inrange)
- [`_.random`](#random)

### [● Object](#object)

- [`_.assign`](#assign)
- [`_.assignIn`](#assignin)
- [`_.assignInWith`](#assigninwith)
- [`_.assignWith`](#assignwith)
- [`_.at`](#at)
- [`_.create`](#create)
- [`_.defaults`](#defaults)
- [`_.defaultsDeep`](#defaultsdeep)
- [`_.entries` -> `toPairs`](#topairs)
- [`_.entriesIn` -> `toPairsIn`](#topairsin)
- [`_.extend` -> `assignIn`](#assignin)
- [`_.extendWith` -> `assignInWith`](#assigninwith)
- [`_.findKey`](#findkey)
- [`_.findLastKey`](#findlastkey)
- [`_.forIn`](#forin)
- [`_.forInRight`](#forinright)
- [`_.forOwn`](#forown)
- [`_.forOwnRight`](#forownright)
- [`_.functions`](#functions)
- [`_.functionsIn`](#functionsin)
- [`_.get`](#get)
- [`_.has`](#has)
- [`_.hasIn`](#hasin)
- [`_.invert`](#invert)
- [`_.invertBy`](#invertby)
- [`_.invoke`](#invoke)
- [`_.keys`](#keys)
- [`_.keysIn`](#keysin)
- [`_.mapKeys`](#mapkeys)
- [`_.mapValues`](#mapvalues)
- [`_.merge`](#merge)
- [`_.mergeWith`](#mergewith)
- [`_.omit`](#omit)
- [`_.omitBy`](#omitby)
- [`_.pick`](#pick)
- [`_.pickBy`](#pickby)
- [`_.result`](#result)
- [`_.set`](#set)
- [`_.setWith`](#setwith)
- [`_.toPairs`](#topairs)
- [`_.toPairsIn`](#topairsin)
- [`_.transform`](#transform)
- [`_.unset`](#unset)
- [`_.update`](#update)
- [`_.updateWith`](#updatewith)
- [`_.values`](#values)
- [`_.valuesIn`](#valuesin)

### [● Seq](#seq)

- [`_`](#lodash)
- [`_.chain`](#chain)
- [`_.tap`](#tap)
- [`_.thru`](#thru)
- [`_.prototype[Symbol.iterator]`](#prototype)
- [`_.prototype.at`](#prototype-at)
- [`_.prototype.chain`](#prototype-chain)
- [`_.prototype.commit`](#prototype-commit)
- [`_.prototype.next`](#prototype-next)
- [`_.prototype.plant`](#prototype-plant)
- [`_.prototype.reverse`](#prototype-reverse)
- [`_.prototype.toJSON` -> `value`](#prototype-value)
- [`_.prototype.value`](#prototype-value)
- [`_.prototype.valueOf` -> `value`](#prototype-value)

### [● String](#string)

- [`_.camelCase`](#camelcase)
- [`_.capitalize`](#capitalize)
- [`_.deburr`](#deburr)
- [`_.endsWith`](#endswith)
- [`_.escape`](#escape)
- [`_.escapeRegExp`](#escaperegexp)
- [`_.kebabCase`](#kebabcase)
- [`_.lowerCase`](#lowercase)
- [`_.lowerFirst`](#lowerfirst)
- [`_.pad`](#pad)
- [`_.padEnd`](#padend)
- [`_.padStart`](#padstart)
- [`_.parseInt`](#parseint)
- [`_.repeat`](#repeat)
- [`_.replace`](#replace)
- [`_.snakeCase`](#snakecase)
- [`_.split`](#split)
- [`_.startCase`](#startcase)
- [`_.startsWith`](#startswith)
- [`_.template`](#template)
- [`_.toLower`](#tolower)
- [`_.toUpper`](#toupper)
- [`_.trim`](#trim)
- [`_.trimEnd`](#trimend)
- [`_.trimStart`](#trimstart)
- [`_.truncate`](#truncate)
- [`_.unescape`](#unescape)
- [`_.upperCase`](#uppercase)
- [`_.upperFirst`](#upperfirst)
- [`_.words`](#words)

### [● Утилиты](#утилиты)

- [`_.attempt`](#attempt)
- [`_.bindAll`](#bindall)
- [`_.cond`](#cond)
- [`_.conforms`](#conforms)
- [`_.constant`](#constant)
- [`_.defaultTo`](#defaultto)
- [`_.flow`](#flow)
- [`_.flowRight`](#flowright)
- [`_.identity`](#identity)
- [`_.iteratee`](#iteratee)
- [`_.matches`](#matches)
- [`_.matchesProperty`](#matchesproperty)
- [`_.method`](#method)
- [`_.methodOf`](#methodof)
- [`_.mixin`](#mixin)
- [`_.noConflict`](#noconflict)
- [`_.noop`](#noop)
- [`_.nthArg`](#ntharg)
- [`_.over`](#over)
- [`_.overEvery`](#overevery)
- [`_.overSome`](#oversome)
- [`_.property`](#property)
- [`_.propertyOf`](#propertyof)
- [`_.range`](#range)
- [`_.rangeRight`](#rangeright)
- [`_.runInContext`](#runincontext)
- [`_.stubArray`](#stubarray)
- [`_.stubFalse`](#stubfalse)
- [`_.stubObject`](#stubobject)
- [`_.stubString`](#stubstring)
- [`_.stubTrue`](#stubtrue)
- [`_.times`](#times)
- [`_.toPath`](#topath)
- [`_.uniqueId`](#uniqueid)

### [● Свойства](#свойства)

- [`_.VERSION`](#version)
- [`_.templateSettings`](#templatesettings-imports)
- [`_.templateSettings.escape`](#templatesettings-escape)
- [`_.templateSettings.evaluate`](#templatesettings-evaluate)
- [`_.templateSettings.imports`](#templatesettings-imports)
- [`_.templateSettings.interpolate`](#templatesettings-interpolate)
- [`_.templateSettings.variable`](#templatesettings-variable)

### [● Методы](#методы)

- [`_.templateSettings.imports`](#templatesettings)

## Array

### chunk

#### `_.chunk(array, [size=1])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L6839) | [npm package](https://www.npmjs.com/package/lodash.chunk)

Создает массив элементов, разделенных на группы длиной `size`. Если `array` нельзя разделить поровну, последний фрагмент будет состоять из оставшихся элементов.

#### С версии

3.0.0

#### Аргументы

1. `array` `(Array)`: Массив для обработки.
2. `[size=1]` (number): Длина каждого куска.

#### Возвращает

`(Array)`: Returns the new array of chunks.

#### Пример

```javascript
_.chunk(['a', 'b', 'c', 'd'], 2);
// => [['a', 'b'], ['c', 'd']]

_.chunk(['a', 'b', 'c', 'd'], 3);
// => [['a', 'b', 'c'], ['d']]
```

### compact

#### `_.compact(Array)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L6874) | [npm package](https://www.npmjs.com/package/lodash.compact)

Создает массив, из которого удалены все ложные значения. Значения `false`, `null`, `0`, `""`, `undefined` и `NaN` являются ложными.

#### С версии

0.1.0

#### Аргументы

1. `array `(Array)``: Массив для сжатия.

#### Возвращает

``(Array)``: Возвращает новый массив отфильтрованных значений.

#### Пример

```javascript
_.compact([0, 1, false, 2, '', 3]);
// => [1, 2, 3]
```

### concat

#### `_.concat(array, [values])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L6911) | [npm package](https://www.npmjs.com/package/lodash.concat)

Создает новый массив `array`, объединяющий массив с любыми дополнительными массивами и/или значениями.

#### С версии

4.0.0

#### Аргументы

1. `array `(Array)``: Массив для объединения.
2. `[values] (...*)`: Значения для объединения.

#### Возвращает

`(Array)`: Возвращает новый объединенный массив.

#### Пример

```javascript
var array = [1];

var other = _.concat(array, 2, [3], [[4]]);

console.log(other);
// => [1, 2, 3, [4]]

console.log`(Array)`;
// => [1]
```

### difference

#### `_.difference(array, [values])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L6947) | [npm package](https://www.npmjs.com/package/lodash.difference)

Создает массив значений `array`, не включенных в другие заданные массивы, используя [`SameValueZero`](http://ecma-international.org/ecma-262/7.0/#sec-samevaluezero) для сравнения на равенство. Порядок и ссылки значений результата определяются первым массивом.

**Note:** В отличие от [`_.pullAll`](#pullAll), этот метод возвращает новый массив.

#### С версии

0.1.0

#### Аргументы

1. `array` `(Array)`: Массив для проверки.
2. `[values]` (...Array): Значения, которые необходимо исключить.

#### Возвращает

`(Array)`: Возвращает новый массив отфильтрованных значений.

#### Пример

```javascript
_.difference([2, 1], [2, 3]);
// => [1]
```

### differenceBy

#### `_.differenceBy(array, [values], [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L6979) | [npm package](https://www.npmjs.com/package/lodash.differenceby)

Этот метод похож на [`_.difference`](#difference), за исключением того, что он принимает `iteratee`, который вызывается для каждого элемента `array` и `values` для генерации критерия, по которому они сравниваются. Порядок и ссылки значений результата определяются первым массивом. Итератор вызывается с одним аргументом: (значение).

**Note:** В отличие от [`_.pullAllBy`](#pullAllBy), этот метод возвращает новый массив.

#### С версии

4.0.0

#### Аргументы

1. `array` `(Array)`: Массив для проверки.
2. `[values]` (...Array): Значения для исключения.
3. `[iteratee=_.identity]` (Function): Итератор, вызываемый для каждого элемента.

#### Возвращает

`(Array)`: Возвращает новый массив отфильтрованных значений.

#### Пример

```javascript
_.differenceBy([2.1, 1.2], [2.3, 3.4], Math.floor);
// => [1.2]

// The `_.property` iteratee shorthand.
_.differenceBy([{ 'x': 2 }, { 'x': 1 }], [{ 'x': 1 }], 'x');
// => [{ 'x': 2 }]
```

### differenceWith

#### `_.differenceWith(array, [values], [comparator])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7012) | [npm package](https://www.npmjs.com/package/lodash.differencewith)

Этот метод похож на [`_.difference`](#difference), за исключением того, что он принимает `comparator`, который вызывается для сравнения элементов `array` с `values`. Порядок и ссылки значений результата определяются первым массивом. Компаратор вызывается с двумя аргументами: (arrVal, othVal).

**Note:** В отличие от [`_.pullAllWith`](#pullAllWith), этот метод возвращает новый массив.

#### С версии

4.0.0

#### Аргументы

1. `array` `(Array)`: Массив для проверки.
2. `[values]` (...Array): Значения, которые необходимо исключить.
3. `[comparator]` (Function): Компаратор, вызываемый для каждого элемента.

#### Возвращает

`(Array)`: Возвращает новый массив отфильтрованных значений.

#### Пример

```javascript
var objects = [{ 'x': 1, 'y': 2 }, { 'x': 2, 'y': 1 }];

_.differenceWith(objects, [{ 'x': 1, 'y': 2 }],_.isEqual);
// => [{ 'x': 2, 'y': 1 }]
```

### drop

#### `_.drop(array, [n=1])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7047) | [npm package](https://www.npmjs.com/package/lodash.drop)

Создает фрагмент массива с `n` элементами, удаленными с начала.

#### С версии

0.5.0

#### Аргументы

1. `array` `(Array)`: Массив для запроса.
2. `[n=1]` (number): Количество отбрасываемых элементов.

#### Возвращает

`(Array)`: Возвращает фрагмент массива.

#### Пример

```javascript
_.drop([1, 2, 3]);
// => [2, 3]

_.drop([1, 2, 3], 2);
// => [3]

_.drop([1, 2, 3], 5);
// => []

_.drop([1, 2, 3], 0);
// => [1, 2, 3]
```

### dropRight

#### `_.dropRight(array, [n=1])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7081) | [npm package](https://www.npmjs.com/package/lodash.dropright)

Создает фрагмент массива с `n` элементами, отброшенными с конца.

#### С версии

3.0.0

#### Аргументы

1. `array` `(Array)`: Массив для запроса.
2. `[n=1]` (number): Количество отбрасываемых элементов.

#### Возвращает

`(Array)`: Возвращает фрагмент массива.

#### Пример

```javascript
_.dropRight([1, 2, 3]);
// => [1, 2]

_.dropRight([1, 2, 3], 2);
// => [1]

_.dropRight([1, 2, 3], 5);
// => []

_.dropRight([1, 2, 3], 0);
// => [1, 2, 3]
```

### dropRightWhile

#### `_.dropRightWhile(array, [predicate=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7126) | [npm package](https://www.npmjs.com/package/lodash.droprightwhile)

Создает фрагмент массива, исключая элементы, удаленные с конца. Элементы отбрасываются до тех пор, пока `predicate` не вернет false. Предикат вызывается с тремя аргументами: (значение, индекс, массив).

#### С версии

3.0.0

#### Аргументы

1. `array` `(Array)`: Массив для запроса.
2. `[predicate=_.identity]` (Function): Функция, вызываемая каждую итерацию.

#### Возвращает

`(Array)`: Возвращает фрагмент массива.

#### Пример

```javascript
var users = [
  { 'user': 'barney',  'active': true },
  { 'user': 'fred',    'active': false },
  { 'user': 'pebbles', 'active': false }
];

_.dropRightWhile(users, function(o) { return !o.active; });
// => objects for ['barney']

// The `_.matches` iteratee shorthand.
_.dropRightWhile(users, { 'user': 'pebbles', 'active': false });
// => objects for ['barney', 'fred']

// The `_.matchesProperty` iteratee shorthand.
_.dropRightWhile(users, ['active', false]);
// => objects for ['barney']

// The `_.property` iteratee shorthand.
_.dropRightWhile(users, 'active');
// => objects for ['barney', 'fred', 'pebbles']
```

### dropWhile

#### `_.dropWhile(array, [predicate=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7167) | [npm package](https://www.npmjs.com/package/lodash.dropwhile)

Создает фрагмент массива, исключая элементы, удаленные с начала. Элементы отбрасываются до тех пор, пока `predicate` не вернет `false`. Предикат вызывается с тремя аргументами: (значение, индекс, массив).

#### С версии

3.0.0

#### Аргументы

1. `array` `(Array)`: Массив для запроса.
2. `[predicate=_.identity]` (Function): Функция, вызываемая каждую итерацию.

#### Возвращает

`(Array)`: Возвращает фрагмент массива.

#### Пример

```javascript
var users = [
  { 'user': 'barney',  'active': false },
  { 'user': 'fred',    'active': false },
  { 'user': 'pebbles', 'active': true }
];

_.dropWhile(users, function(o) { return !o.active; });
// => objects for ['pebbles']

// The `_.matches` iteratee shorthand.
_.dropWhile(users, { 'user': 'barney', 'active': false });
// => objects for ['fred', 'pebbles']

// The `_.matchesProperty` iteratee shorthand.
_.dropWhile(users, ['active', false]);
// => objects for ['pebbles']

// The `_.property` iteratee shorthand.
_.dropWhile(users, 'active');
// => objects for ['barney', 'fred', 'pebbles']
```

### fill

#### `_.fill(array, value, [start=0], [end=array.length])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7202) | [npm package](https://www.npmjs.com/package/lodash.fill)

Заполняет элементы массива значением от `start` до `end`, но не включая его.

**Note:** этот метод изменяет `array`.

#### С версии

3.2.0

#### Аргументы

1. `array` `(Array)`: The array to fill.
2. `value` (*): The value to fill `array` with.
3. `[start=0]` (number): Стартовая позиция.
4. `[end=array.length]` (number): Конечная позиция.

#### Возвращает

`(Array)`: Возвращает `array`.

#### Пример

```javascript
var array = [1, 2, 3];

_.fill(array, 'a');

console.log`(Array)`;
// => ['a', 'a', 'a']

_.fill(Array(3), 2);
// => [2, 2, 2]

_.fill([4, 6, 8, 10], '*', 1, 3);
// => [4, '_', '_', 10]
```

### findIndex

#### `_.findIndex(array, [predicate=_.identity], [fromIndex=0])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7249) | [npm package](https://www.npmjs.com/package/lodash.findindex)

Этот метод похож на [`_.find`](#find), за исключением того, что он возвращает индекс первого элемента. `predicate` возвращает truey for вместо самого элемента.

#### С версии

1.1.0

#### Аргументы

1. `array` `(Array)`: Массив для проверки.
2. `[predicate=_.identity]` (Function): Функция, вызываемая каждую итерацию.
3. `[fromIndex=0]` (number): Индекс начала поиска.

#### Возвращает

(number): Возвращает индекс найденного элемента, иначе `-1`.

#### Пример

```javascript
var users = [
  { 'user': 'barney',  'active': false },
  { 'user': 'fred',    'active': false },
  { 'user': 'pebbles', 'active': true }
];

_.findIndex(users, function(o) { return o.user == 'barney'; });
// => 0

// The `_.matches` iteratee shorthand.
_.findIndex(users, { 'user': 'fred', 'active': false });
// => 1

// The `_.matchesProperty` iteratee shorthand.
_.findIndex(users, ['active', false]);
// => 0

// The `_.property` iteratee shorthand.
_.findIndex(users, 'active');
// => 2
```

### findLastIndex

#### `_.findLastIndex(array, [predicate=_.identity], [fromIndex=array.length-1])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7296) | [npm package](https://www.npmjs.com/package/lodash.findlastindex)

Этот метод похож на [`_.findIndex`](#findIndex), за исключением того, что он перебирает элементы коллекции справа налево.

#### С версии

2.0.0

#### Аргументы

1. `array` `(Array)`: Массив для проверки.
2. `[predicate=_.identity]` (Function): Функция, вызываемая каждую итерацию.
3. `[fromIndex=array.length-1]` (number): Индекс начала поиска.

#### Возвращает

(number): Возвращает индекс найденного элемента, иначе `-1`.

#### Пример

```javascript
var users = [
  { 'user': 'barney',  'active': true  },
  { 'user': 'fred',    'active': false },
  { 'user': 'pebbles', 'active': false }
];

_.findLastIndex(users, function(o) { return o.user == 'pebbles'; });
// => 2

// The `_.matches` iteratee shorthand.
_.findLastIndex(users, { 'user': 'barney', 'active': true });
// => 0

// The `_.matchesProperty` iteratee shorthand.
_.findLastIndex(users, ['active', false]);
// => 2

// The `_.property` iteratee shorthand.
_.findLastIndex(users, 'active');
// => 0
```

### flatten

#### `_.flatten(array)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7325) | [npm package](https://www.npmjs.com/package/lodash.flatten)

Сглаживает `array` на один уровень глубины.

#### С версии

0.1.0

#### Аргументы

1. `array` `(Array)`: Массив, который нужно сгладить.

#### Возвращает

`(Array)`: Возвращает новый сглаженный массив.

#### Пример

```javascript
_.flatten([1, [2, [3, [4]], 5]]);
// => [1, 2, [3, [4]], 5]
```

### flattenDeep

#### `_.flattenDeep(array)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7344) | [npm package](https://www.npmjs.com/package/lodash.flattendeep)

Рекурсивно выравнивает `array`.

#### С версии

3.0.0

#### Аргументы

1. `array` `(Array)`: Массив, который нужно сгладить.

#### Возвращает

`(Array)`: Возвращает новый сглаженный массив.

#### Пример

```javascript
_.flattenDeep([1, [2, [3, [4]], 5]]);
// => [1, 2, 3, 4, 5]
```

### flattenDepth

#### `_.flattenDepth(array, [depth=1])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7369) | [npm package](https://www.npmjs.com/package/lodash.flattendepth)

Рекурсивно сгладить `array` на `depth` уровней.

#### С версии

4.4.0

#### Аргументы

1. `array` `(Array)`: Массив, который нужно сгладить.
2. `[depth=1]` (number): Максимальная глубина рекурсии.

#### Возвращает

`(Array)`: Возвращает новый сглаженный массив.

#### Пример

```javascript
var array = [1, [2, [3, [4]], 5]];

_.flattenDepth(array, 1);
// => [1, 2, [3, [4]], 5]

_.flattenDepth(array, 2);
// => [1, 2, 3, [4], 5]
```

### fromPairs

#### `_.fromPairs(pairs)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7393) | [npm package](https://www.npmjs.com/package/lodash.frompairs)

Обратный вариант [`_.toPairs`](#toPairs); этот метод возвращает объект, состоящий из пар ключ-значение.

#### С версии

4.0.0

#### Аргументы

1. `pairs` `(Array)`: Пары ключ-значение.

#### Возвращает

(Object): Возвращает новый объект.

#### Пример

```javascript
_.fromPairs([['a', 1], ['b', 2]]);
// => { 'a': 1, 'b': 2 }
```

### head

#### `_.head(array)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7423) | [npm package](https://www.npmjs.com/package/lodash.head)

Получает первый элемент `array`.

#### С версии

0.1.0

#### Псевдонимы

__.first_

#### Аргументы

1. `array` `(Array)`: Массив для запроса.

#### Возвращает

(*): Возвращает первый элемент `array`.

#### Пример

_.head([1, 2, 3]);

// => 1

_.head([]);

// => undefined

### indexOf

#### `_.indexOf(array, value, [fromIndex=0])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7450) | [npm package](https://www.npmjs.com/package/lodash.indexof)

Получает индекс, по которому в массиве обнаружено первое вхождение значения `value`, используя [`SameValueZero`](http://ecma-international.org/ecma-262/7.0/#sec-samevaluezero) для сравнения на равенство. Если `fromIndex` имеет отрицательное значение, он используется как смещение от конца массива.

#### С версии

0.1.0

#### Аргументы

1. `array` `(Array)`: Массив для проверки.
2. `value` (*): Значение для поиска.
3. `[fromIndex=0]` (number): Индекс начала поиска.

#### Возвращает

(number): Возвращает индекс совпавшего значения, иначе `-1`.

#### Пример

```javascript
_.indexOf([1, 2, 1, 2], 2);
// => 1

// Search from the `fromIndex`.
_.indexOf([1, 2, 1, 2], 2, 2);
// => 3
```

### initial

#### `_.initial(array)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7476) | [npm package](https://www.npmjs.com/package/lodash.initial)

Получает все, кроме последнего элемента `array`.

#### С версии

0.1.0

#### Аргументы

1. `array` `(Array)`: Массив для запроса.

#### Возвращает

`(Array)`: Возвращает фрагмент массива.

#### Пример

```javascript
_.initial([1, 2, 3]);
// => [1, 2]
```

### intersection

#### `_.intersection([arrays])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7498) | [npm package](https://www.npmjs.com/package/lodash.intersection)

Создает массив уникальных значений, которые включены во все заданные массивы, используя [`SameValueZero`](http://ecma-international.org/ecma-262/7.0/#sec-samevaluezero) для сравнения на равенство. Порядок и ссылки значений результата определяются первым массивом.

#### С версии

0.1.0

#### Аргументы

1. `[arrays]` (...Array): Массивы для проверки.

#### Возвращает

`(Array)`: Возвращает новый массив пересекающихся значений.

#### Пример

```javascript
_.intersection([2, 1], [2, 3]);
// => [2]
```

### intersectionBy

#### `_.intersectionBy([arrays], [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7528) | [npm package](https://www.npmjs.com/package/lodash.intersectionby)

Этот метод похож на [`_.intersection`](#intersection), за исключением того, что он принимает `iteratee`, который вызывается для каждого элемента каждого `arrays` для генерации критерия, по которому они сравниваются. Порядок и ссылки значений результата определяются первым массивом. Итератор вызывается с одним аргументом: (значение).

#### С версии

4.0.0

#### Аргументы

1. `[arrays]` (...Array): Массивы для проверки.
2. `[iteratee=_.identity]` (Function): Итератор, вызываемый для каждого элемента.

#### Возвращает

`(Array)`: Возвращает новый массив пересекающихся значений.

#### Пример

```javascript
_.intersectionBy([2.1, 1.2], [2.3, 3.4], Math.floor);
// => [2.1]

// Сокращение итерируемого элемента `_.property`.
_.intersectionBy([{ 'x': 1 }], [{ 'x': 2 }, { 'x': 1 }], 'x');
// => [{ 'x': 1 }]
```

### intersectionWith

#### `_.intersectionWith([arrays], [comparator])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7563) | [npm package](https://www.npmjs.com/package/lodash.intersectionwith)

Этот метод похож на [`_.intersection`](#intersection), за исключением того, что он принимает `comparator`, который вызывается для сравнения элементов `arrays`. Порядок и ссылки значений результата определяются первым массивом. Компаратор вызывается с двумя аргументами: (arrVal, othVal).

#### С версии

4.0.0

#### Аргументы

1. `[arrays]` (...Array): Массивы для проверки.
2. `[comparator]` (Function): Компаратор, вызываемый для каждого элемента.

#### Возвращает

`(Array)`: Возвращает новый массив пересекающихся значений.

#### Пример

```javascript
var objects = [{ 'x': 1, 'y': 2 }, { 'x': 2, 'y': 1 }];

var others = [{ 'x': 1, 'y': 1 }, { 'x': 1, 'y': 2 }];

_.intersectionWith(objects, others,_.isEqual);
// => [{ 'x': 1, 'y': 2 }]
```

### join

#### `_.join(array, [separator=','])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7591) | [npm package](https://www.npmjs.com/package/lodash.join)

Преобразует все элементы `array` в строку, разделенную `separator`.

#### С версии

4.0.0

#### Аргументы

1. `array` `(Array)`: Массив для преобразования.
2. `[separator=',']` (string): Разделитель.

#### Возвращает

(string): Возвращает объединенную строку.

#### Пример

```javascript
_.join(['a', 'b', 'c'], '~');
// => 'a~b~c'
```

### last

#### `_.last(array)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7609) | [npm package](https://www.npmjs.com/package/lodash.last)

Получает последний элемент `array`.

#### С версии

0.1.0

#### Аргументы

1. `array` `(Array)`: Массив для запроса.

#### Возвращает

(*): Возвращает последний элемент `array`.

#### Пример

```javascript
_.last([1, 2, 3]);
// => 3
```

### lastIndexOf

#### `_.lastIndexOf(array, value, [fromIndex=array.length-1])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7635) | [npm package](https://www.npmjs.com/package/lodash.lastindexof)

This method is like [`_.indexOf`](#indexOf) except that it iterates over elements of `array` from right to left.

#### С версии

0.1.0

#### Аргументы

1. `array` `(Array)`: Массив для проверки.
2. `value` (*): Значение для поиска.
3. `[fromIndex=array.length-1]` (number): Индекс начала поиска.

#### Возвращает

(number): Возвращает индекс совпавшего значения, иначе `-1`.

#### Пример

```javascript
_.lastIndexOf([1, 2, 1, 2], 2);
// => 3

// Search from the `fromIndex`.
_.lastIndexOf([1, 2, 1, 2], 2, 2);
// => 1
```

### nth

#### `_.nth(array, [n=0])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7671) | [npm package](https://www.npmjs.com/package/lodash.nth)

Получает элемент с индексом `n` из массива. Если `n` отрицательно, возвращается n-й элемент с конца.

#### С версии

4.11.0

#### Аргументы

1. `array` `(Array)`: Массив для запроса.
2. `[n=0]` (number): Индекс возвращаемого элемента.

#### Возвращает

(*): Returns the nth element of `array`.

#### Пример

```javascript
var array = ['a', 'b', 'c', 'd'];

_.nth(array, 1);
// => 'b'

_.nth(array, -2);
// => 'c';
```

### pull

#### `_.pull(array, [values])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7698) | [npm package](https://www.npmjs.com/package/lodash.pull)

Удаляет все заданные значения из `array`, используя [`SameValueZero`](http://ecma-international.org/ecma-262/7.0/#sec-samevaluezero) для сравнения на равенство.

**Note:** В отличие от [`_.without`](#without), этот метод изменяет `array`. Используйте [`_.remove`](#remove) для удаления элементов из массива по предикату.

#### С версии

2.0.0

#### Аргументы

1. `array` `(Array)`: Массив для изменения.
2. `[values]` (...*): Значения, которые нужно удалить.

#### Возвращает

`(Array)`: Возвращает `array`.

#### Пример

```javascript
var array = ['a', 'b', 'c', 'a', 'b', 'c'];

_.pull(array, 'a', 'c');

console.log`(Array)`;
// => ['b', 'b']
```

### pullAll

#### `_.pullAll(array, values)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7720) | [npm package](https://www.npmjs.com/package/lodash.pullall)

Этот метод похож на [`_.pull`](#pull), за исключением того, что он принимает массив значений для удаления.

**Note:** В отличие от [`_.difference`](#difference), этот метод изменяет `array`.

#### С версии

4.0.0

#### Аргументы

1. `array` `(Array)`: Массив для изменения.
2. `values` `(Array)`: Значения, которые нужно удалить.

#### Возвращает

`(Array)`: Возвращает `array`.

#### Пример

```javascript
var array = ['a', 'b', 'c', 'a', 'b', 'c'];

_.pullAll(array, ['a', 'c']);

console.log`(Array)`;
// => ['b', 'b']
```

### pullAllBy

#### `_.pullAllBy(array, values, [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7749) | [npm package](https://www.npmjs.com/package/lodash.pullallby)

Этот метод похож на [`_.pullAll`](#pullAll), за исключением того, что он принимает `iteratee`, который вызывается для каждого элемента `array` и `values` для генерации критерия, по которому они сравниваются. Итератор вызывается с одним аргументом: (значение).

**Note:** В отличие от [`_.differenceBy`](#differenceBy), этот метод изменяет `array`.

#### С версии

4.0.0

#### Аргументы

1. `array` `(Array)`: Массив для изменения.
2. `values` `(Array)`: Значения, которые нужно удалить.
3. `[iteratee=_.identity]` (Function): Итератор, вызываемый для каждого элемента.

#### Возвращает

`(Array)`: Возвращает `array`.

#### Пример

```javascript
var array = [{ 'x': 1 }, { 'x': 2 }, { 'x': 3 }, { 'x': 1 }];

_.pullAllBy(array, [{ 'x': 1 }, { 'x': 3 }], 'x');

console.log`(Array)`;
// => [{ 'x': 2 }]
```

### pullAllWith

#### `_.pullAllWith(array, values, [comparator])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7778) | [npm package](https://www.npmjs.com/package/lodash.pullallwith)

Этот метод похож на [`_.pullAll`](#pullAll), за исключением того, что он принимает `comparator`, который вызывается для сравнения элементов `array` с `values`. Компаратор вызывается с двумя аргументами: (arrVal, othVal).

**Note:** В отличие от [`_.differenceWith`](#differenceWith), этот метод изменяет `array`.

#### С версии

4.6.0

#### Аргументы

1. `array` `(Array)`: Массив для изменения.
2. `values` `(Array)`: Значения, которые нужно удалить.
3. `[comparator]` (Function): Компаратор, вызываемый для каждого элемента.

#### Возвращает

`(Array)`: Возвращает `array`.

#### Пример

```javascript
var array = [{ 'x': 1, 'y': 2 }, { 'x': 3, 'y': 4 }, { 'x': 5, 'y': 6 }];

_.pullAllWith(array, [{ 'x': 3, 'y': 4 }],_.isEqual);

console.log`(Array)`;
// => [{ 'x': 1, 'y': 2 }, { 'x': 5, 'y': 6 }]
```

### pullAt

#### `_.pullAt(array, [indexes])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7808) | [npm package](https://www.npmjs.com/package/lodash.pullat)

Удаляет элементы из массива, соответствующие индексам, и возвращает массив удаленных элементов.

**Note:** В отличие от [`_.at`](#at), этот метод изменяет `array`.

#### С версии

3.0.0

#### Аргументы

1. `array` `(Array)`: Массив для изменения.
2. `[indexes]` (...(number|number[])): Индексы элементов для удаления.

#### Возвращает

`(Array)`: Возвращает новый массив удаленных элементов.

#### Пример

```javascript
var array = ['a', 'b', 'c', 'd'];

var pulled = _.pullAt(array, [1, 3]);

console.log`(Array)`;
// => ['a', 'c']

console.log(pulled);
// => ['b', 'd']
```

### remove

#### `_.remove(array, [predicate=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7847) | [npm package](https://www.npmjs.com/package/lodash.remove)

Удаляет все элементы из массива, для которых `predicate` возвращает истинность, и возвращает массив удаленных элементов. Предикат вызывается с тремя аргументами: (значение, индекс, массив).

**Note:** В отличие от [`_.filter`](#filter), этот метод изменяет `array`. Используйте [`_.pull`](#pull) для извлечения элементов из массива по значению.

#### С версии

2.0.0

#### Аргументы

1. `array` `(Array)`: Массив для изменения.
2. `[predicate=_.identity]` (Function): Функция, вызываемая каждую итерацию.

#### Возвращает

`(Array)`: Возвращает новый массив удаленных элементов.

#### Пример

```javascript
var array = [1, 2, 3, 4];

var evens = _.remove(array, function(n) {
  return n % 2 == 0;
});

console.log`(Array)`;
// => [1, 3]

console.log(evens);
// => [2, 4]
```

### reverse

#### `_.reverse(array)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7891) | [npm package](https://www.npmjs.com/package/lodash.reverse)

Переворачивает `array` так, что первый элемент становится последним, второй элемент становится предпоследним и т.д.

**Note:** этот метод изменяет `array` и основан на [`Array#reverse`](https://mdn.io/Array/reverse).

#### С версии

4.0.0

#### Аргументы

1. `array` `(Array)`: Массив для изменения.

#### Возвращает

`(Array)`: Возвращает `array`.

#### Пример

```javascript
var array = [1, 2, 3];

_.reverse`(Array)`;
// => [3, 2, 1]

console.log`(Array)`;
// => [3, 2, 1]
```

### slice

#### `_.slice(array, [start=0], [end=array.length])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7911) | [npm package](https://www.npmjs.com/package/lodash.slice)

Создает фрагмент массива от `start` до `end`, но не включая его.

**Note:** Этот метод используется вместо [`Array#slice`](https://mdn.io/Array/slice), чтобы гарантировать возврат плотных массивов.

#### С версии

3.0.0

#### Аргументы

1. `array` `(Array)`: Массив, который нужно разрезать.
2. `[start=0]` (number): Стартовая позиция.
3. `[end=array.length]` (number): Конечная позиция.

#### Возвращает

`(Array)`: Возвращает фрагмент массива.

### sortedIndex

#### `_.sortedIndex(array, value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7944) | [npm package](https://www.npmjs.com/package/lodash.sortedindex)

Использует двоичный поиск для определения наименьшего индекса, по которому значение должно быть вставлено в массив, чтобы сохранить порядок сортировки.

#### С версии

0.1.0

#### Аргументы

1. `array` `(Array)`: Отсортированный массив для проверки.
2. `value` (*): Значение для оценки.

#### Возвращает

(number): Возвращает индекс, по которому `value` должно быть вставлено в массив.

#### Пример

```javascript
_.sortedIndex([30, 50], 40);
// => 1
```

### sortedIndexBy

#### `_.sortedIndexBy(array, value, [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7973) | [npm package](https://www.npmjs.com/package/lodash.sortedindexby)

Этот метод похож на [`_.sortedIndex`](#sortedIndex), за исключением того, что он принимает `iteratee`, который вызывается для `value` и каждого элемента `array` для вычисления их ранга сортировки. Итератор вызывается с одним аргументом: (значение).

#### С версии

4.0.0

#### Аргументы

1. `array` `(Array)`: Отсортированный массив для проверки.
2. `value` (*): Значение для оценки.
3. `[iteratee=_.identity]` (Function): Итератор, вызываемый для каждого элемента.

#### Возвращает

(number): Возвращает индекс, по которому `value` должно быть вставлено в массив.

#### Пример

```javascript
var objects = [{ 'x': 4 }, { 'x': 5 }];

_.sortedIndexBy(objects, { 'x': 4 }, function(o) { return o.x; });
// => 0

// The `_.property` iteratee shorthand.
_.sortedIndexBy(objects, { 'x': 4 }, 'x');
// => 0
```

### sortedIndexOf

#### `_.sortedIndexOf(array, value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L7993) | [npm package](https://www.npmjs.com/package/lodash.sortedindexof)

Этот метод похож на [`_.indexOf`](#indexOf), за исключением того, что он выполняет двоичный поиск в отсортированном массиве.

#### С версии

4.0.0

#### Аргументы

1. `array` `(Array)`: Массив для проверки.
2. `value` (*): Значение для поиска.

#### Возвращает

(number): Возвращает индекс совпавшего значения, иначе `-1`.

#### Пример

```javascript
_.sortedIndexOf([4, 5, 5, 5, 6], 5);
// => 1
```

### sortedLastIndex

#### `_.sortedLastIndex(array, value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8022) | [npm package](https://www.npmjs.com/package/lodash.sortedlastindex)

Этот метод похож на [`_.sortedIndex`](#sortedIndex), за исключением того, что он возвращает наивысший индекс, по которому `value` должно быть вставлено в `array`, чтобы сохранить порядок сортировки.

#### С версии

3.0.0

#### Аргументы

1. `array` `(Array)`: Отсортированный массив для проверки.
2. `value` (*): Значение для оценки.

#### Возвращает

(number): Возвращает индекс, по которому `value` должно быть вставлено в массив.

#### Пример

```javascript
_.sortedLastIndex([4, 5, 5, 5, 6], 5);
// => 4
```

### sortedLastIndexBy

#### `_.sortedLastIndexBy(array, value, [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8051) | [npm package](https://www.npmjs.com/package/lodash.sortedlastindexby)

Этот метод похож на [`_.sortedLastIndex`](#sortedLastIndex), за исключением того, что он принимает `iteratee`, который вызывается для `value` и каждого элемента `array` для вычисления их ранга сортировки. Итератор вызывается с одним аргументом: (значение).

#### С версии

4.0.0

#### Аргументы

1. `array` `(Array)`: Отсортированный массив для проверки.
2. `value` (*): Значение для оценки.
3. `[iteratee=_.identity]` (Function): Итератор, вызываемый для каждого элемента.

#### Возвращает

(number): Возвращает индекс, по которому `value` должно быть вставлено в массив.

#### Пример

```javascript
var objects = [{ 'x': 4 }, { 'x': 5 }];

_.sortedLastIndexBy(objects, { 'x': 4 }, function(o) { return o.x; });
// => 1

// The `_.property` iteratee shorthand.
_.sortedLastIndexBy(objects, { 'x': 4 }, 'x');
// => 1
```

### sortedLastIndexOf

#### `_.sortedLastIndexOf(array, value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8071) | [npm package](https://www.npmjs.com/package/lodash.sortedlastindexof)

Этот метод похож на [`_.lastIndexOf`](#lastIndexOf), за исключением того, что он выполняет двоичный поиск в отсортированном массиве.

#### С версии

4.0.0

#### Аргументы

1. `array` `(Array)`: Массив для проверки.
2. `value` (*): Значение для поиска.

#### Возвращает

(number): Возвращает индекс совпавшего значения, иначе `-1`.

#### Пример

```javascript
_.sortedLastIndexOf([4, 5, 5, 5, 6], 5);
// => 3
```

### sortedUniq

#### `_.sortedUniq(array)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8097) | [npm package](https://www.npmjs.com/package/lodash.sorteduniq)

Этот метод похож на [`_.uniq`](#uniq), за исключением того, что он разработан и оптимизирован для отсортированных массивов.

#### С версии

4.0.0

#### Аргументы

1. `array` `(Array)`: Массив для проверки.

#### Возвращает

`(Array)`: Возвращает новый массив без дубликатов.

#### Пример

```javascript
_.sortedUniq([1, 1, 2]);
// => [1, 2]
```

### sortedUniqBy

#### `_.sortedUniqBy(array, [iteratee])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8119) | [npm package](https://www.npmjs.com/package/lodash.sorteduniqby)

Этот метод похож на [`_.uniqBy`](#uniqBy), за исключением того, что он разработан и оптимизирован для отсортированных массивов.

#### С версии

4.0.0

#### Аргументы

1. `array` `(Array)`: Массив для проверки.
2. `[iteratee]` (Function): Итератор, вызываемый для каждого элемента.

#### Возвращает

`(Array)`: Возвращает новый массив без дубликатов.

#### Пример

```javascript
_.sortedUniqBy([1.1, 1.2, 2.3, 2.4], Math.floor);
// => [1.1, 2.3]
```

### tail

#### `_.tail(array)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8139) | [npm package](https://www.npmjs.com/package/lodash.tail)

Получает все, кроме первого элемента `array`.

#### С версии

4.0.0

#### Аргументы

1. `array` `(Array)`: Массив для запроса.

#### Возвращает

`(Array)`: Возвращает фрагмент массива.

#### Пример

```javascript
_.tail([1, 2, 3]);
// => [2, 3]
```

### take

#### `_.take(array, [n=1])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8169) | [npm package](https://www.npmjs.com/package/lodash.take)

Создает фрагмент массива с `n` элементами, взятыми с начала.

#### С версии

0.1.0

#### Аргументы

1. `array` `(Array)`: Массив для запроса.
2. `[n=1]` (number): Количество элементов, которые нужно взять.

#### Возвращает

`(Array)`: Возвращает фрагмент массива.

#### Пример

```javascript
_.take([1, 2, 3]);
// => [1]

_.take([1, 2, 3], 2);
// => [1, 2]

_.take([1, 2, 3], 5);
// => [1, 2, 3]

_.take([1, 2, 3], 0);
// => []
```

### takeRight

#### `_.takeRight(array, [n=1])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8202) | [npm package](https://www.npmjs.com/package/lodash.takeright)

Создает фрагмент массива с `n` элементами, взятыми с конца.

#### С версии

3.0.0

#### Аргументы

1. `array` `(Array)`: Массив для запроса.
2. `[n=1]` (number): Количество элементов, которые нужно взять.

#### Возвращает

`(Array)`: Возвращает фрагмент массива.

#### Пример

```javascript
_.takeRight([1, 2, 3]);
// => [3]

_.takeRight([1, 2, 3], 2);
// => [2, 3]

_.takeRight([1, 2, 3], 5);
// => [1, 2, 3]

_.takeRight([1, 2, 3], 0);
// => []
```

### takeRightWhile

#### `_.takeRightWhile(array, [predicate=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8247) | [npm package](https://www.npmjs.com/package/lodash.takerightwhile)

Создает фрагмент массива с элементами, взятыми с конца. Элементы принимаются до тех пор, пока `predicate` не вернет `ложно`. Предикат вызывается с тремя аргументами: (значение, индекс, массив).

#### С версии

3.0.0

#### Аргументы

1. `array` `(Array)`: Массив для запроса.
2. `[predicate=_.identity]` (Function): Функция, вызываемая каждую итерацию.

#### Возвращает

`(Array)`: Возвращает фрагмент массива.

#### Пример

```javascript
var users = [
  { 'user': 'barney',  'active': true },
  { 'user': 'fred',    'active': false },
  { 'user': 'pebbles', 'active': false }
];

_.takeRightWhile(users, function(o) { return !o.active; });
// => objects for ['fred', 'pebbles']

// The `_.matches` iteratee shorthand.
_.takeRightWhile(users, { 'user': 'pebbles', 'active': false });
// => objects for ['pebbles']

// The `_.matchesProperty` iteratee shorthand.
_.takeRightWhile(users, ['active', false]);
// => objects for ['fred', 'pebbles']

// The `_.property` iteratee shorthand.
_.takeRightWhile(users, 'active');
// => []
```

### takeWhile

#### `_.takeWhile(array, [predicate=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8288) | [npm package](https://www.npmjs.com/package/lodash.takewhile)

Создает фрагмент массива с элементами, взятыми с самого начала. Элементы принимаются до тех пор, пока `predicate` не вернет `ложно`. Предикат вызывается с тремя аргументами: (значение, индекс, массив).

#### С версии

3.0.0

#### Аргументы

1. `array` `(Array)`: Массив для запроса.
2. `[predicate=_.identity]` (Function): Функция, вызываемая каждую итерацию.

#### Возвращает

`(Array)`: Возвращает фрагмент массива.

#### Пример

```javascript
var users = [
  { 'user': 'barney',  'active': false },
  { 'user': 'fred',    'active': false },
  { 'user': 'pebbles', 'active': true }
];

_.takeWhile(users, function(o) { return !o.active; });
// => objects for ['barney', 'fred']

// The `_.matches` iteratee shorthand.
_.takeWhile(users, { 'user': 'barney', 'active': false });
// => objects for ['barney']

// The `_.matchesProperty` iteratee shorthand.
_.takeWhile(users, ['active', false]);
// => objects for ['barney', 'fred']

// The `_.property` iteratee shorthand.
_.takeWhile(users, 'active');
// => []
```

### union

#### `_.union([arrays])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8310) | [npm package](https://www.npmjs.com/package/lodash.union)

Создает массив уникальных значений по порядку из всех заданных массивов, используя [`SameValueZero`](http://ecma-international.org/ecma-262/7.0/#sec-samevaluezero) для сравнения на равенство.

#### С версии

0.1.0

#### Аргументы

1. `[arrays]` (...Array): Массивы для проверки.

#### Возвращает

`(Array)`: Возвращает новый массив объединенных значений.

#### Пример

```javascript
_.union([2], [1, 2]);
// => [2, 1]
```

### unionBy

#### `_.unionBy([arrays], [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8337) | [npm package](https://www.npmjs.com/package/lodash.unionby)

Этот метод похож на [`_.union`](#union), за исключением того, что он принимает `iteratee`, который вызывается для каждого элемента каждого `arrays` для генерации критерия, по которому вычисляется уникальность. Значения результата выбираются из первого массива, в котором встречается значение. Итератор вызывается с одним аргументом: (значение).

#### С версии

4.0.0

#### Аргументы

1. `[arrays]` (...Array): Массивы для проверки.
2. `[iteratee=_.identity]` (Function): Итератор, вызываемый для каждого элемента.

#### Возвращает

`(Array)`: Возвращает новый массив объединенных значений.

#### Пример

```javascript
_.unionBy([2.1], [1.2, 2.3], Math.floor);
// => [2.1, 1.2]

// The `_.property` iteratee shorthand.
_.unionBy([{ 'x': 1 }], [{ 'x': 2 }, { 'x': 1 }], 'x');
// => [{ 'x': 1 }, { 'x': 2 }]
```

### unionWith

#### `_.unionWith([arrays], [comparator])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8366) | [npm package](https://www.npmjs.com/package/lodash.unionwith)

Этот метод похож на [`_.union`](#union), за исключением того, что он принимает `comparator`, который вызывается для сравнения элементов `arrays`. Значения результата выбираются из первого массива, в котором встречается значение. Компаратор вызывается с двумя аргументами: (arrVal, othVal).

#### С версии

4.0.0

#### Аргументы

1. `[arrays]` (...Array): Массивы для проверки.
2. `[comparator]` (Function): Компаратор, вызываемый для каждого элемента.

#### Возвращает

`(Array)`: Возвращает новый массив объединенных значений.

#### Пример

```javascript
var objects = [{ 'x': 1, 'y': 2 }, { 'x': 2, 'y': 1 }];
var others = [{ 'x': 1, 'y': 1 }, { 'x': 1, 'y': 2 }];

_.unionWith(objects, others,_.isEqual);
// => [{ 'x': 1, 'y': 2 }, { 'x': 2, 'y': 1 }, { 'x': 1, 'y': 1 }]
```

### uniq

#### `_.uniq(array)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8390) | [npm package](https://www.npmjs.com/package/lodash.uniq)

Создает версию массива без дубликатов, используя [`SameValueZero`](http://ecma-international.org/ecma-262/7.0/#sec-samevaluezero) для сравнения на равенство, в котором только первое вхождение каждого значения элемента сохраняется. Порядок значений результатов определяется порядком их появления в массиве.

#### С версии

0.1.0

#### Аргументы

1. `array` `(Array)`: Массив для проверки.

#### Возвращает

`(Array)`: Возвращает новый массив без дубликатов.

#### Пример

```javascript
_.uniq([2, 1, 2]);
// => [2, 1]
```

### uniqBy

#### `_.uniqBy(array, [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8417) | [npm package](https://www.npmjs.com/package/lodash.uniqby)

Этот метод похож на [`_.uniq`](#uniq), за исключением того, что он принимает `iteratee`, который вызывается для каждого элемента в `array` для генерации критерия, по которому вычисляется уникальность. Порядок значений результатов определяется порядком их появления в массиве. Итератор вызывается с одним аргументом: (значение).

#### С версии

4.0.0

#### Аргументы

1. `array` `(Array)`: Массив для проверки.
2. `[iteratee=_.identity]` (Function): Итератор, вызываемый для каждого элемента.

#### Возвращает

`(Array)`: Возвращает новый массив без дубликатов.

#### Пример

```javascript
_.uniqBy([2.1, 1.2, 2.3], Math.floor);
// => [2.1, 1.2]

// The `_.property` iteratee shorthand.
_.uniqBy([{ 'x': 1 }, { 'x': 2 }, { 'x': 1 }], 'x');
// => [{ 'x': 1 }, { 'x': 2 }]
```

### uniqWith

#### `_.uniqWith(array, [comparator])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8441) | [npm package](https://www.npmjs.com/package/lodash.uniqwith)

Этот метод похож на [`_.uniq`](#uniq), за исключением того, что он принимает `компаратор`, который вызывается для сравнения элементов `массива`. Порядок значений результатов определяется порядком их появления в массиве. Компаратор вызывается с двумя аргументами: (arrVal, othVal).

#### С версии

4.0.0

#### Аргументы

1. `array` `(Array)`: Массив для проверки.
2. `[comparator]` (Function): Компаратор, вызываемый для каждого элемента.

#### Возвращает

`(Array)`: Возвращает новый массив без дубликатов.

#### Пример

```javascript
var objects = [{ 'x': 1, 'y': 2 }, { 'x': 2, 'y': 1 }, { 'x': 1, 'y': 2 }];

_.uniqWith(objects,_.isEqual);
// => [{ 'x': 1, 'y': 2 }, { 'x': 2, 'y': 1 }]
```

### unzip

#### `_.unzip(array)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8465) | [npm package](https://www.npmjs.com/package/lodash.unzip)

Этот метод похож на [`_.zip`](#zip), за исключением того, что он принимает массив сгруппированных элементов и создает массив, перегруппировывающий элементы в их pre-zip конфигурацию.

#### С версии

1.2.0

#### Аргументы

1. `array` `(Array)`: Массив сгруппированных элементов для обработки.

#### Возвращает

`(Array)`: Возвращает новый массив перегруппированных элементов.

#### Пример

```javascript
var zipped = _.zip(['a', 'b'], [1, 2], [true, false]);
// => [['a', 1, true], ['b', 2, false]]

_.unzip(zipped);
// => [['a', 'b'], [1, 2], [true, false]]
```

### unzipWith

#### `_.unzipWith(array, [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8502) | [npm package](https://www.npmjs.com/package/lodash.unzipwith)

Этот метод похож на [`_.unzip`](#unzip), за исключением того, что он принимает `iteratee`, чтобы указать, как следует объединять перегруппированные значения. Итератор вызывается с элементами каждой группы: (...group).

#### С версии

3.8.0

#### Аргументы

1. `array` `(Array)`: Массив сгруппированных элементов для обработки.
2. `[iteratee=_.identity]` (Function): Функция объединения перегруппированных значений.

#### Возвращает

`(Array)`: Возвращает новый массив перегруппированных элементов.

#### Пример

```javascript
var zipped = _.zip([1, 2], [10, 20], [100, 200]);
// => [[1, 10, 100], [2, 20, 200]]

_.unzipWith(zipped,_.add);
// => [3, 30, 300]
```

### without

#### `_.without(array, [values])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8535) | [npm package](https://www.npmjs.com/package/lodash.without)

Создает массив, исключая все заданные значения, используя [`SameValueZero`](http://ecma-international.org/ecma-262/7.0/#sec-samevaluezero) для сравнения на равенство.

**Note:** В отличие от [`_.pull`](#pull), этот метод возвращает новый массив.

#### С версии

0.1.0

#### Аргументы

1. `array` `(Array)`: Массив для проверки.
2. `[values]` (...*): Значения для исключения.

#### Возвращает

`(Array)`: Возвращает новый массив отфильтрованных значений.

#### Пример

```javascript
_.without([2, 1, 2, 3], 1, 2);
// => [3]
```

### xor

#### `_.xor([arrays])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8559) | [npm package](https://www.npmjs.com/package/lodash.xor)

Создает массив уникальных значений, который является [симметричной разницей](https://en.wikipedia.org/wiki/Symmetric_difference) заданных массивов. Порядок значений результатов определяется порядком их появления в массивах.

#### С версии

2.4.0

#### Аргументы

1. `[arrays]` (...Array): Массивы для проверки.

#### Возвращает

`(Array)`: Возвращает новый массив отфильтрованных значений.

#### Пример

```javascript
_.xor([2, 1], [2, 3]);
// => [1, 3]
```

### xorBy

#### `_.xorBy([arrays], [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8586) | [npm package](https://www.npmjs.com/package/lodash.xorby)

Этот метод похож на [`_.xor`](#xor), за исключением того, что он принимает `iteratee`, который вызывается для каждого элемента каждого `arrays` для генерации критерия, по которому они сравниваются. Порядок значений результатов определяется порядком их появления в массивах. Итератор вызывается с одним аргументом: (значение).

#### С версии

4.0.0

#### Аргументы

1. `[arrays]` (...Array): Массивы для проверки.
2. `[iteratee=_.identity]` (Function): Итератор, вызываемый для каждого элемента.

#### Возвращает

`(Array)`: Возвращает новый массив отфильтрованных значений.

#### Пример

```javascript
_.xorBy([2.1, 1.2], [2.3, 3.4], Math.floor);
// => [1.2, 3.4]

// The `_.property` iteratee shorthand.
_.xorBy([{ 'x': 1 }], [{ 'x': 2 }, { 'x': 1 }], 'x');
// => [{ 'x': 2 }]
```

### xorWith

#### `_.xorWith([arrays], [comparator])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8615) | [npm package](https://www.npmjs.com/package/lodash.xorwith)

Этот метод похож на [`_.xor`](#xor), за исключением того, что он принимает `comparator`, который вызывается для сравнения элементов `arrays`. Порядок значений результатов определяется порядком их появления в массивах. Компаратор вызывается с двумя аргументами: (arrVal, othVal).

#### С версии

4.0.0

#### Аргументы

1. `[arrays]` (...Array): Массивы для проверки.
2. `[comparator]` (Function): Компаратор, вызываемый для каждого элемента.

#### Возвращает

`(Array)`: Возвращает новый массив отфильтрованных значений.

#### Пример

```javascript
var objects = [{ 'x': 1, 'y': 2 }, { 'x': 2, 'y': 1 }];
var others = [{ 'x': 1, 'y': 1 }, { 'x': 1, 'y': 2 }];

_.xorWith(objects, others,_.isEqual);
// => [{ 'x': 2, 'y': 1 }, { 'x': 1, 'y': 1 }]
```

### zip

#### `_.zip([arrays])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8637) | [npm package](https://www.npmjs.com/package/lodash.zip)

Создает массив сгруппированных элементов, первый из которых содержит первые элементы заданных массивов, второй — вторые элементы заданных массивов и т.д.

#### С версии

0.1.0

#### Аргументы

1. `[arrays]` (...Array): Массивы для обработки.

#### Возвращает

`(Array)`: Возвращает новый массив сгруппированных элементов.

#### Пример

```javascript
_.zip(['a', 'b'], [1, 2], [true, false]);
// => [['a', 1, true], ['b', 2, false]]
```

### zipObject

#### `_.zipObject([props=[]], [values=[]])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8655) | [npm package](https://www.npmjs.com/package/lodash.zipobject)

Этот метод похож на [`_.fromPairs`](#fromPairs), за исключением того, что он принимает два массива: один из идентификаторов свойств и один из соответствующих значений.

#### С версии

0.4.0

#### Аргументы

1. `[props=[]]` `(Array)`: Идентификаторы свойств.
2. `[values=[]]` `(Array)`: Значения свойств.

#### Возвращает

(Object): Возвращает новый объект.

#### Пример

```javascript
_.zipObject(['a', 'b'], [1, 2]);
// => { 'a': 1, 'b': 2 }
```

### zipObjectDeep

#### `_.zipObjectDeep([props=[]], [values=[]])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8674) | [npm package](https://www.npmjs.com/package/lodash.zipobjectdeep)

This method is like [`_.zipObject`](#zipObject) except that it supports property paths.

#### С версии

4.1.0

#### Аргументы

1. `[props=[]]` `(Array)`: Идентификаторы свойств.
2. `[values=[]]` `(Array)`: Значения свойств.

#### Возвращает

(Object): Возвращает новый объект.

#### Пример

```javascript
_.zipObjectDeep(['a.b[0].c', 'a.b[1].d'], [1, 2]);
// => { 'a': { 'b': [{ 'c': 1 }, { 'd': 2 }] } }
```

### zipWith

#### `_.zipWith([arrays], [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8698) | [npm package](https://www.npmjs.com/package/lodash.zipwith)

Этот метод похож на [`_.zip`](#zip), за исключением того, что он принимает `iteratee`, чтобы указать, как следует объединять сгруппированные значения. Итератор вызывается с элементами каждой группы: (...group).

#### С версии

3.8.0

#### Аргументы

1. `[arrays]` (...Array): Массивы для обработки.
2. `[iteratee=_.identity]` (Function): The function to combine grouped values.

#### Возвращает

`(Array)`: Возвращает новый массив сгруппированных элементов.

#### Пример

```javascript
_.zipWith([1, 2], [10, 20], [100, 200], function(a, b, c) {
  return a + b + c;
});
// => [111, 222]
```

## Collection

### countBy

#### `_.countBy(collection, [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9077) | [npm package](https://www.npmjs.com/package/lodash.countby)

Создает объект, состоящий из ключей, сгенерированных в результате прохождения каждого элемента коллекции через итерируемый объект. Соответствующее значение каждого ключа — это количество раз, когда ключ был возвращен `iteratee`. Итератор вызывается с одним аргументом: (значение).

#### С версии

0.5.0

#### Аргументы

1. `collection` (Array|Object): Коллекция для перебора.
2. `[iteratee=_.identity]` (Function): Итератор для преобразования ключей.

#### Возвращает

(Object): Возвращает составной агрегированный объект.

#### Пример

```javascript
_.countBy([6.1, 4.2, 6.3], Math.floor);
// => { '4': 1, '6': 2 }

// The `_.property` iteratee shorthand.
_.countBy(['one', 'two', 'three'], 'length');
// => { '3': 2, '5': 1 }
```

### every

#### `_.every(collection, [predicate=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9126) | [npm package](https://www.npmjs.com/package/lodash.every)

Проверяет, возвращает ли `predicate` истинность для **всех** элементов `collection`. Итерация прекращается, как только `predicate` возвращает false. Предикат вызывается с тремя аргументами: (значение, индекс|ключ, коллекция).

**Note:** Этот метод возвращает `true` для [пустых коллекций](https://en.wikipedia.org/wiki/Empty_set), поскольку [все верно](https://en.wikipedia.org/wiki/Vacous_truth) элементов пустые коллекции.

#### С версии

0.1.0

#### Аргументы

1. `collection` (Array|Object): Коллекция для перебора.
2. `[predicate=_.identity]` (Function): Функция, вызываемая каждую итерацию.

#### Возвращает

(boolean): Returns `true` if all elements pass the predicate check, else `false`.

#### Пример

```javascript
_.every([true, 1, null, 'yes'], Boolean);
// => false

var users = [
  { 'user': 'barney', 'age': 36, 'active': false },
  { 'user': 'fred',   'age': 40, 'active': false }
];

// The `_.matches` iteratee shorthand.
_.every(users, { 'user': 'barney', 'active': false });
// => false

// The `_.matchesProperty` iteratee shorthand.
_.every(users, ['active', false]);
// => true

// The `_.property` iteratee shorthand.
_.every(users, 'active');
// => false
```

### filter

#### `_.filter(collection, [predicate=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9171) | [npm package](https://www.npmjs.com/package/lodash.filter)

Выполняет итерацию по элементам коллекции, возвращая массив всех элементов, для которых `predicate` возвращает истинность. Предикат вызывается с тремя аргументами: (значение, индекс|ключ, коллекция).

**Note:** В отличие от [`_.remove`](#remove), этот метод возвращает новый массив.

#### С версии

0.1.0

#### Аргументы

1. `collection` (Array|Object): Коллекция для перебора.
2. `[predicate=_.identity]` (Function): Функция, вызываемая каждую итерацию.

#### Возвращает

`(Array)`: Возвращает новый отфильтрованный массив.

#### Пример

```javascript
var users = [
  { 'user': 'barney', 'age': 36, 'active': true },
  { 'user': 'fred',   'age': 40, 'active': false }
];

_.filter(users, function(o) { return !o.active; });
// => objects for ['fred']

// The `_.matches` iteratee shorthand.
_.filter(users, { 'age': 36, 'active': true });
// => objects for ['barney']

// The `_.matchesProperty` iteratee shorthand.
_.filter(users, ['active', false]);
// => objects for ['fred']

// The `_.property` iteratee shorthand.
_.filter(users, 'active');
// => objects for ['barney']
```

### find

#### `_.find(collection, [predicate=_.identity], [fromIndex=0])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9212) | [npm package](https://www.npmjs.com/package/lodash.find)

Выполняет итерацию по элементам коллекции, возвращая первый элемент, для которого `predicate` возвращает true. Предикат вызывается с тремя аргументами: (значение, индекс|ключ, коллекция).

#### С версии

0.1.0

#### Аргументы

1. `collection` (Array|Object): Коллекция для проверки.
2. `[predicate=_.identity]` (Function): Функция, вызываемая каждую итерацию.
3. `[fromIndex=0]` (number): Индекс начала поиска.

#### Возвращает

(*): Возвращает соответствующий элемент, иначе `undefined`.

#### Пример

```javascript
var users = [
  { 'user': 'barney',  'age': 36, 'active': true },
  { 'user': 'fred',    'age': 40, 'active': false },
  { 'user': 'pebbles', 'age': 1,  'active': true }
];

_.find(users, function(o) { return o.age < 40; });
// => object for 'barney'

// The `_.matches` iteratee shorthand.
_.find(users, { 'age': 1, 'active': true });
// => object for 'pebbles'

// The `_.matchesProperty` iteratee shorthand.
_.find(users, ['active', false]);
// => object for 'fred'

// The `_.property` iteratee shorthand.
_.find(users, 'active');
// => object for 'barney'
```

### findLast

#### `_.findLast(collection, [predicate=_.identity], [fromIndex=collection.length-1])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9233) | [npm package](https://www.npmjs.com/package/lodash.findlast)

Этот метод похож на [`_.find`](#find), за исключением того, что он перебирает элементы коллекции справа налево.

#### С версии

2.0.0

#### Аргументы

1. `collection` (Array|Object): Коллекция для проверки.
2. `[predicate=_.identity]` (Function): Функция, вызываемая каждую итерацию.
3. `[fromIndex=collection.length-1]` (number): Индекс начала поиска.

#### Возвращает

(*): Возвращает соответствующий элемент, иначе `undefined`.

#### Пример

```javascript
_.findLast([1, 2, 3, 4], function(n) {
  return n % 2 == 1;
});
// => 3
```

### flatMap

#### `_.flatMap(collection, [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9256) | [npm package](https://www.npmjs.com/package/lodash.flatmap)

Создает плоский массив значений, пропуская каждый элемент в `collection` через `iteratee` и выравнивая сопоставленные результаты. Итератор вызывается с тремя аргументами: (значение, индекс|ключ, коллекция).

#### С версии

4.0.0

#### Аргументы

1. `collection` (Array|Object): Коллекция для перебора.
2. `[iteratee=_.identity]` (Function): Функция, вызываемая каждую итерацию.

#### Возвращает

`(Array)`: Возвращает новый сглаженный массив.

#### Пример

```javascript
function duplicate(n) {
  return [n, n];
}

_.flatMap([1, 2], duplicate);
// => [1, 1, 2, 2]
```

### flatMapDeep

#### `_.flatMapDeep(collection, [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9280) | [npm package](https://www.npmjs.com/package/lodash.flatmapdeep)

Этот метод похож на [`_.flatMap`](#flatMap), за исключением того, что он рекурсивно выравнивает сопоставленные результаты.

#### С версии

4.7.0

#### Аргументы

1. `collection` (Array|Object): Коллекция для перебора.
2. `[iteratee=_.identity]` (Function): Функция, вызываемая каждую итерацию.

#### Возвращает

`(Array)`: Возвращает новый сглаженный массив.

#### Пример

```javascript
function duplicate(n) {
  return [[[n, n]]];
}

_.flatMapDeep([1, 2], duplicate);
// => [1, 1, 2, 2]
```

### flatMapDepth

#### `_.flatMapDepth(collection, [iteratee=_.identity], [depth=1])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9305) | [npm package](https://www.npmjs.com/package/lodash.flatmapdepth)

Этот метод похож на [`_.flatMap`](#flatMap), за исключением того, что он рекурсивно сглаживает отображенные результаты на глубину в раз.

#### С версии

4.7.0

#### Аргументы

1. `collection` (Array|Object): Коллекция для перебора.
2. `[iteratee=_.identity]` (Function): Функция, вызываемая каждую итерацию.
3. `[depth=1]` (number): Максимальная глубина рекурсии.

#### Возвращает

`(Array)`: Возвращает новый сглаженный массив.

#### Пример

```javascript
function duplicate(n) {
  return [[[n, n]]];
}

_.flatMapDepth([1, 2], duplicate, 2);
// => [[1, 1], [2, 2]]
```

### forEach

#### `_.forEach(collection, [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9340) | [npm package](https://www.npmjs.com/package/lodash.foreach)

Перебирает элементы коллекции и вызывает итератор для каждого элемента. Итератор вызывается с тремя аргументами: (значение, индекс|ключ, коллекция). Итерированные функции могут завершить итерацию раньше, явно вернув `false`.

**Note:** Как и в случае с другими методами «Коллекции», объекты со свойством «длина» повторяются как массивы. Чтобы избежать такого поведения, используйте [`_.forIn`](#forIn) или [`_.forOwn`](#forOwn) для итерации объекта.

#### С версии

0.1.0

#### Псевдонимы

__.each_

#### Аргументы

1. `collection` (Array|Object): Коллекция для перебора.
2. `[iteratee=_.identity]` (Function): Функция, вызываемая каждую итерацию.

#### Возвращает

(*): Возвращает `collection`.

#### Пример

```javascript
_.forEach([1, 2], function(value) {
  console.log(value);
});
// => Logs `1` then `2`.

_.forEach({ 'a': 1, 'b': 2 }, function(value, key) {
  console.log(key);
});
// => Logs 'a' then 'b' (iteration order is not guaranteed).
```

### forEachRight

#### `_.forEachRight(collection, [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9365) | [npm package](https://www.npmjs.com/package/lodash.foreachright)

Этот метод похож на [`_.forEach`](#forEach), за исключением того, что он перебирает элементы коллекции справа налево.

#### С версии

2.0.0

#### Псевдонимы

__.eachRight_

#### Аргументы

1. `collection` (Array|Object): Коллекция для перебора.
2. `[iteratee=_.identity]` (Function): Функция, вызываемая каждую итерацию.

#### Возвращает

(*): Возвращает `collection`.

#### Пример

```javascript
_.forEachRight([1, 2], function(value) {
  console.log(value);
});
// => Logs `2` then `1`.
```

### groupBy

#### `_.groupBy(collection, [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9393) | [npm package](https://www.npmjs.com/package/lodash.groupby)

Создает объект, состоящий из ключей, сгенерированных в результате прохождения каждого элемента коллекции через итерируемый объект. Порядок сгруппированных значений определяется порядком их появления в коллекции. Соответствующее значение каждого ключа представляет собой массив элементов, отвечающих за генерацию ключа. Итератор вызывается с одним аргументом: (значение).

#### С версии

0.1.0

#### Аргументы

1. `collection` (Array|Object): Коллекция для перебора.
2. `[iteratee=_.identity]` (Function): Итератор для преобразования ключей.

#### Возвращает

(Object): Возвращает составной агрегированный объект.

#### Пример

```javascript
_.groupBy([6.1, 4.2, 6.3], Math.floor);
// => { '4': [4.2], '6': [6.1, 6.3] }

// The `_.property` iteratee shorthand.
_.groupBy(['one', 'two', 'three'], 'length');
// => { '3': ['one', 'two'], '5': ['three'] }
```

### includes

#### `_.includes(collection, value, [fromIndex=0])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9431) | [npm package](https://www.npmjs.com/package/lodash.includes)

Проверяет, находится ли `value` в `collection`. Если `collection` является строкой, она проверяется на наличие подстроки `value`, в противном случае для равенства используется [`SameValueZero`](http://ecma-international.org/ecma-262/7.0/#sec-samevaluezero). сравнения. Если fromIndex имеет отрицательное значение, он используется как смещение от конца коллекции.

#### С версии

0.1.0

#### Аргументы

1. `collection` (Array|Object|string): Коллекция для проверки.
2. `value` (*): Значение для поиска.
3. `[fromIndex=0]` (number): Индекс начала поиска.

#### Возвращает

(boolean): Возвращает `true`, если найдено значение, иначе — `false`.

#### Пример

```javascript
_.includes([1, 2, 3], 1);
// => true

_.includes([1, 2, 3], 1, 2);
// => false

_.includes({ 'a': 1, 'b': 2 }, 1);
// => true

_.includes('abcd', 'bc');
// => true
```

### invokeMap

#### `_.invokeMap(collection, path, [args])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9467) | [npm package](https://www.npmjs.com/package/lodash.invokemap)

Вызывает метод по пути каждого элемента коллекции, возвращая массив результатов каждого вызванного метода. Любые дополнительные аргументы предоставляются каждому вызванному методу. Если `path` — это функция, она вызывается и `this` привязана к каждому элементу в `collection`.

#### С версии

4.0.0

#### Аргументы

1. `collection` (Array|Object): Коллекция для перебора.
2. `path` (Array|Function|string): Путь к методу для вызова или функция, вызываемая каждую итерацию.
3. `[args]` (...*): Аргументы для вызова каждого метода с помощью.

#### Возвращает

`(Array)`: Возвращает массив результатов.

#### Пример

```javascript
_.invokeMap([[5, 1, 7], [3, 2, 1]], 'sort');
// => [[1, 5, 7], [1, 2, 3]]

_.invokeMap([123, 456], String.prototype.split, '');
// => [['1', '2', '3'], ['4', '5', '6']]
```

### keyBy

#### `_.keyBy(collection, [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9506) | [npm package](https://www.npmjs.com/package/lodash.keyby)

Создает объект, состоящий из ключей, сгенерированных в результате прохождения каждого элемента коллекции через итерируемый объект. Соответствующее значение каждого ключа — это последний элемент, ответственный за генерацию ключа. Итератор вызывается с одним аргументом: (значение).

#### С версии

4.0.0

#### Аргументы

1. `collection` (Array|Object): Коллекция для перебора.
2. `[iteratee=_.identity]` (Function): Итератор для преобразования ключей.

#### Возвращает

(Object): Возвращает составной агрегированный объект.

#### Пример

```javascript
var array = [
  { 'dir': 'left', 'code': 97 },
  { 'dir': 'right', 'code': 100 }
];

_.keyBy(array, function(o) {
  return String.fromCharCode(o.code);
});
// => { 'a': { 'dir': 'left', 'code': 97 }, 'd': { 'dir': 'right', 'code': 100 } }

_.keyBy(array, 'dir');
// => { 'left': { 'dir': 'left', 'code': 97 }, 'right': { 'dir': 'right', 'code': 100 } }
```

### map

#### `_.map(collection, [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9552) | [npm package](https://www.npmjs.com/package/lodash.map)

Создает массив значений, пропуская каждый элемент в `collection` через `iteratee`. Итератор вызывается с тремя аргументами:
(значение, индекс|ключ, коллекция).

Многие методы `lodash` защищены от работы в качестве итераций для таких методов, как [`_.every`](#every), [`_.filter`](#filter), [`_.map`](#map), [` _.mapValues`](#mapValues), [`_.reject`](#reject) и [`_.some`](#some).

Защищенные методы:
`ary`, `chunk`, `curry`, `curryRight`, `drop`, `dropRight`, `every`, `fill`, `invert`, `parseInt`, `random`, `range`, `rangeRight`, `repeat`, `sampleSize`, `slice`, `some`, `sortBy`, `split`, `take`, `takeRight`, `template`, `trim`, `trimEnd`, `trimStart`, and `words`

#### С версии

0.1.0

#### Аргументы

1. `collection` (Array|Object): Коллекция для перебора.
2. `[iteratee=_.identity]` (Function): Функция, вызываемая каждую итерацию.

#### Возвращает

`(Array)`: Returns the new mapped array.

#### Пример

```javascript
function square(n) {
  return n * n;
}

_.map([4, 8], square);
// => [16, 64]

_.map({ 'a': 4, 'b': 8 }, square);
// => [16, 64] (iteration order is not guaranteed)

var users = [
  { 'user': 'barney' },
  { 'user': 'fred' }
];

// The `_.property` iteratee shorthand.
_.map(users, 'user');
// => ['barney', 'fred']
```

### orderBy

#### `_.orderBy(collection, [iteratees=[_.identity]], [orders])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9586) | [npm package](https://www.npmjs.com/package/lodash.orderby)

Этот метод похож на [`_.sortBy`](#sortBy), за исключением того, что он позволяет указывать порядок сортировки итераторов для сортировки. Если параметр «orders» не указан, все значения сортируются в порядке возрастания. В противном случае укажите порядок сортировки `desc` для убывания или `asc` для сортировки соответствующих значений.

#### С версии

4.0.0

#### Аргументы

1. `collection` (Array|Object): Коллекция для перебора.
2. `[iteratees=[_.identity]]` (Array[]|Function[]|Object[]|string[]): Итераторы для сортировки.
3. `[orders]` (string[]): Порядок сортировки `iteratees`.

#### Возвращает

`(Array)`: Возвращает новый отсортированный массив.

#### Пример

```javascript
var users = [
  { 'user': 'fred',   'age': 48 },
  { 'user': 'barney', 'age': 34 },
  { 'user': 'fred',   'age': 40 },
  { 'user': 'barney', 'age': 36 }
];

// Sort by `user` in ascending order and by `age` in descending order.
_.orderBy(users, ['user', 'age'], ['asc', 'desc']);
// => objects for [['barney', 36], ['barney', 34], ['fred', 48], ['fred', 40]]
```

### partition

#### `_.partition(collection, [predicate=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9636) | [npm package](https://www.npmjs.com/package/lodash.partition)

Создает массив элементов, разделенных на две группы, первая из которых содержит элементы, для которых `predicate` возвращает `true`, для второй — элементы, для которых `predicate` возвращает `false`. Предикат вызывается с одним аргументом: (значение).

#### С версии

3.0.0

#### Аргументы

1. `collection` (Array|Object): Коллекция для перебора.
2. `[predicate=_.identity]` (Function): Функция, вызываемая каждую итерацию.

#### Возвращает

`(Array)`: Возвращает массив сгруппированных элементов.

#### Пример

```javascript
var users = [
  { 'user': 'barney',  'age': 36, 'active': false },
  { 'user': 'fred',    'age': 40, 'active': true },
  { 'user': 'pebbles', 'age': 1,  'active': false }
];

_.partition(users, function(o) { return o.active; });
// => objects for [['fred'], ['barney', 'pebbles']]

// Сокращение итерируемого элемента `_.matches`.
_.partition(users, { 'age': 1, 'active': false });
// => objects for [['pebbles'], ['barney', 'fred']]

// Сокращение итерируемого элемента `_.matchesProperty`.
_.partition(users, ['active', false]);
// => objects for [['barney', 'pebbles'], ['fred']]

// The `_.property` iteratee shorthand.
_.partition(users, 'active');
// => objects for [['fred'], ['barney', 'pebbles']]
```

### reduce

#### `_.reduce(collection, [iteratee=_.identity], [accumulator])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9677) | [npm package](https://www.npmjs.com/package/lodash.reduce)

Сокращает `collection` до значения, которое является накопленным результатом прохождения каждого элемента в `collection` через `iteratee`, где при каждом последующем вызове предоставляется возвращаемое значение предыдущего. Если аккумулятор не указан, в качестве начального значения используется первый элемент коллекции. Итератор вызывается с четырьмя аргументами: (аккумулятор, значение, индекс|ключ, коллекция).

Многие методы lodash защищены от работы в качестве итераций для таких методов, как [`_.reduce`](#reduce), [`_.reduceRight`](#reduceRight) и [`_.transform`](#transform).

Защищенные методы:
`assign`, `defaults`, `defaultsDeep`, `includes`, `merge`, `orderBy`, and `sortBy`

#### С версии

0.1.0

#### Аргументы

1. `collection` (Array|Object): Коллекция для перебора.
2. `[iteratee=_.identity]` (Function): Функция, вызываемая каждую итерацию.
3. `[accumulator]` (*): Начальное значение.

#### Возвращает

(*): Возвращает накопленное значение.

#### Пример

```javascript
_.reduce([1, 2], function(sum, n) {
  return sum + n;
}, 0);
// => 3

_.reduce({ 'a': 1, 'b': 2, 'c': 1 }, function(result, value, key) {
  (result[value] || (result[value] = [])).push(key);
  return result;
}, {});
// => { '1': ['a', 'c'], '2': ['b'] } (iteration order is not guaranteed)
```

### reduceRight

#### `_.reduceRight(collection, [iteratee=_.identity], [accumulator])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9706) | [npm package](https://www.npmjs.com/package/lodash.reduceright)

Этот метод похож на [`_.reduce`](#reduce), за исключением того, что он перебирает элементы коллекции справа налево.

#### С версии

0.1.0

#### Аргументы

1. `collection` (Array|Object): Коллекция для перебора.
2. `[iteratee=_.identity]` (Function): Функция, вызываемая каждую итерацию.
3. `[accumulator]` (*): Начальное значение.

#### Возвращает

(*): Возвращает накопленное значение.

#### Пример

```javascript
var array = [[0, 1], [2, 3], [4, 5]];

_.reduceRight(array, function(flattened, other) {
  return flattened.concat(other);
}, []);
// => [4, 5, 2, 3, 0, 1]
```

### reject

#### `_.reject(collection, [predicate=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9747) | [npm package](https://www.npmjs.com/package/lodash.reject)

Противоположность [`_.filter`](#filter); этот метод возвращает элементы коллекции, для которых предикат **не** возвращает `true`.

#### С версии

0.1.0

#### Аргументы

1. `collection` (Array|Object): Коллекция для перебора.
2. `[predicate=_.identity]` (Function): Функция, вызываемая каждую итерацию.

#### Возвращает

`(Array)`: Возвращает новый отфильтрованный массив.

#### Пример

```javascript
var users = [
  { 'user': 'barney', 'age': 36, 'active': false },
  { 'user': 'fred',   'age': 40, 'active': true }
];

_.reject(users, function(o) { return !o.active; });
// => objects for ['fred']

// The `_.matches` iteratee shorthand.
_.reject(users, { 'age': 40, 'active': true });
// => objects for ['barney']

// The `_.matchesProperty` iteratee shorthand.
_.reject(users, ['active', false]);
// => objects for ['fred']

// The `_.property` iteratee shorthand.
_.reject(users, 'active');
// => objects for ['barney']
```

### sample

#### `_.sample(collection)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9766) | [npm package](https://www.npmjs.com/package/lodash.sample)

Получает случайный элемент из `collection`.

#### С версии

2.0.0

#### Аргументы

1. `collection` (Array|Object): Коллекция для пробы.

#### Возвращает

(*): Возвращает случайный элемент.

#### Пример

```javascript
_.sample([1, 2, 3, 4]);
// => 2
```

### sampleSize

#### `_.sampleSize(collection, [n=1])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9791) | [npm package](https://www.npmjs.com/package/lodash.samplesize)

Получает n случайных элементов по уникальным ключам от `1` до `length` коллекции.

#### С версии

4.0.0

#### Аргументы

1. `collection` (Array|Object): Коллекция для пробы.
2. `[n=1]` (number): Количество элементов для выборки.

#### Возвращает

`(Array)`: Возвращает случайный элементs.

#### Пример

```javascript
_.sampleSize([1, 2, 3], 2);
// => [3, 1]

_.sampleSize([1, 2, 3], 4);
// => [2, 3, 1]
```

### shuffle

#### `_.shuffle(collection)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9816) | [npm package](https://www.npmjs.com/package/lodash.shuffle)

Создает массив перетасованных значений, используя версию [Fisher-Yates shuffle](https://en.wikipedia.org/wiki/Fisher-Yates_shuffle).

#### С версии

0.1.0

#### Аргументы

1. `collection` (Array|Object): Коллекция для перетасовки.

#### Возвращает

`(Array)`: Возвращает новый перетасованный массив.

#### Пример

```javascript
_.shuffle([1, 2, 3, 4]);
// => [4, 1, 3, 2]
```

### size

#### `_.size(collection)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9842) | [npm package](https://www.npmjs.com/package/lodash.size)

Получает размер коллекции, возвращая ее длину для значений типа массива, или количество собственных перечислимых строковых свойств для объектов.

#### С версии

0.1.0

#### Аргументы

1. `collection` (Array|Object|string): Коллекция для проверки.

#### Возвращает

(number): Возвращает размер коллекции.

#### Пример

```javascript
_.size([1, 2, 3]);
// => 3

_.size({ 'a': 1, 'b': 2 });
// => 2

_.size('pebbles');
// => 7
```

### some

#### `_.some(collection, [predicate=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9892) | [npm package](https://www.npmjs.com/package/lodash.some)

Проверяет, возвращает ли `predicate` истинность для **любого** элемента `collection`. Итерация прекращается, как только `predicate` возвращает истину. Предикат вызывается с тремя аргументами: (значение, индекс|ключ, коллекция).

#### С версии

0.1.0

#### Аргументы

1. `collection` (Array|Object): Коллекция для перебора.
2. `[predicate=_.identity]` (Function): Функция, вызываемая каждую итерацию.

#### Возвращает

(boolean): Возвращает `true`, если какой-либо элемент проходит проверку предиката, иначе — `false`.

#### Пример

```javascript
_.some([null, 0, 'yes', false], Boolean);
// => true

var users = [
  { 'user': 'barney', 'active': true },
  { 'user': 'fred',   'active': false }
];

// The `_.matches` iteratee shorthand.
_.some(users, { 'user': 'barney', 'active': false });
// => false

// The `_.matchesProperty` iteratee shorthand.
_.some(users, ['active', false]);
// => true

// The `_.property` iteratee shorthand.
_.some(users, 'active');
// => true
```

### sortBy

#### `_.sortBy(collection, [iteratees=[_.identity]])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9929) | [npm package](https://www.npmjs.com/package/lodash.sortby)

Создает массив элементов, отсортированный в порядке возрастания по результатам прохождения каждого элемента коллекции через каждую итерацию. Этот метод выполняет стабильную сортировку, то есть сохраняет исходный порядок сортировки равных элементов. Итерации вызываются с одним аргументом: (значение).

#### С версии

0.1.0

#### Аргументы

1. `collection` (Array|Object): Коллекция для перебора.
2. `[iteratees=[_.identity]]` (...(Function|Function[])): Итераторы для сортировки.

#### Возвращает

`(Array)`: Возвращает новый отсортированный массив.

#### Пример

```javascript
var users = [
  { 'user': 'fred',   'age': 48 },
  { 'user': 'barney', 'age': 36 },
  { 'user': 'fred',   'age': 40 },
  { 'user': 'barney', 'age': 34 }
];

_.sortBy(users, [function(o) { return o.user; }]);
// => objects for [['barney', 36], ['barney', 34], ['fred', 48], ['fred', 40]]

_.sortBy(users, ['user', 'age']);
// => objects for [['barney', 34], ['barney', 36], ['fred', 40], ['fred', 48]]
```

## Date

### now

#### `_.now()`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9960) | [npm package](https://www.npmjs.com/package/lodash.now)

Получает временную метку количества миллисекунд, прошедших с эпохи Unix (1 January `1970 00`:00:00 UTC).

#### С версии

2.4.0

#### Возвращает

(number): Возвращает метку времени.

#### Пример

```javascript
_.defer(function(stamp) {
  console.log(_.now() - stamp);
}, _.now());
// => Logs the number of milliseconds it took for the deferred invocation.
```

## Function

### after

#### `_.after(n, func)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9990) | [npm package](https://www.npmjs.com/package/lodash.after)

Противоположность [`_.before`](#before); этот метод создает функцию, которая вызывает func после вызова `n` или более раз.

#### С версии

0.1.0

#### Аргументы

1. `n` (number): Количество вызовов перед вызовом `func`.
2. `func` (Function): Функция ограничения.

#### Возвращает

(Function): Возвращает новую ограниченную функцию.

#### Пример

```javascript
var saves = ['profile', 'settings'];

var done = _.after(saves.length, function() {
  console.log('done saving!');
});

_.forEach(saves, function(type) {
  asyncSave({ 'type': type, 'complete': done });
});
// => Logs 'done saving!' after the two async saves have completed.
```

### ary

#### `_.ary(func, [n=func.length])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L10019) | [npm package](https://www.npmjs.com/package/lodash.ary)

Создает функцию, вызывающую `func`, с аргументами до `n`, игнорируя любые дополнительные аргументы.

#### С версии

3.0.0

#### Аргументы

1. `func` (Function): Функция для ограничения аргументов.
2. `[n=func.length]` (number): Максимальная аритиметическая граница (арность - количество получаемы аргументов).

#### Возвращает

(Function): Возвращает новую ограниченную функцию.

#### Пример

```javascript
_.map(['6', '8', '10'],_.ary(parseInt, 1));
// => [6, 8, 10]
```

### before

#### `_.before(n, func)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L10042) | [npm package](https://www.npmjs.com/package/lodash.before)

Создает функцию, которая вызывает `func`, с привязкой `this` и аргументами созданной функции, при этом она вызывается менее `n` раз. Последующие вызовы созданной функции возвращают результат последнего вызова функции.

#### С версии

3.0.0

#### Аргументы

1. `n` (number): Количество вызовов, при которых функция `func` больше не вызывается.
2. `func` (Function): Функция ограничения.

#### Возвращает

(Function): Возвращает новую ограниченную функцию.

#### Пример

```javascript
jQuery(element).on('click', _.before(5, addContactToList));
// => Allows adding up to 4 contacts to the list.
```

### bind

#### `_.bind(func, thisArg, [partials])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L10094) | [npm package](https://www.npmjs.com/package/lodash.bind)

Создает функцию, которая вызывает `func` с привязкой `this` к `thisArg` и `partials`, добавляемыми к получаемым аргументам.

Значение `_.bind.placeholder`, которое по умолчанию равно `_` в монолитных сборках, может использоваться в качестве заполнителя для частично примененных аргументов.

**Note:** В отличие от оригинальной `Function#bind`, этот метод не устанавливает свойство `length` связанных функций.

#### С версии

0.1.0

#### Аргументы

1. `func` (Function): Функция для привязки.
2. `thisArg` (*): Привязка `this` к `func`.
3. `[partials]` (...*): Аргументы, которые следует применить частично.

#### Возвращает

(Function): Возвращает новую связанную функцию.

#### Пример

```javascript
function greet(greeting, punctuation) {
  return greeting + ' ' + this.user + punctuation;
}

var object = { 'user': 'fred' };
var bound = _.bind(greet, object, 'hi');

bound('!');
// => 'hi fred!'

// Bound with placeholders.
var bound = _.bind(greet, object,_, '!');

bound('hi');
// => 'hi fred!'
```

### bindKey

#### `_.bindKey(object, key, [partials])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L10148) | [npm package](https://www.npmjs.com/package/lodash.bindkey)

Создает функцию, которая вызывает метод `object[key]` с добавлением `partials` к полученным аргументам.

Этот метод отличается от [`_.bind`](#bind) тем, что позволяет связанным функциям ссылаться на методы, которые могут быть переопределены или еще не существуют. Дополнительную информацию см. в [статье Питера Мишо](http://peter.michaux.ca/articles/lazy-function-definition-pattern).

Значение `_.bindKey.placeholder`, которое по умолчанию равно `_` в монолитных сборках, может использоваться в качестве заполнителя для частично примененных аргументов.

#### С версии

0.10.0

#### Аргументы

1. `object` (Object): Объект, для которого вызывается метод.
2. `key` (string): Ключ метода.
3. `[partials]` (...*): Аргументы, которые следует применить частично.

#### Возвращает

(Function): Возвращает новую связанную функцию.

#### Пример

```javascript
var object = {
  'user': 'fred',
  'greet': function(greeting, punctuation) {
    return greeting + ' ' + this.user + punctuation;
  }
};

var bound = _.bindKey(object, 'greet', 'hi');
bound('!');
// => 'hi fred!'

object.greet = function(greeting, punctuation) {
  return greeting + 'ya ' + this.user + punctuation;
};
bound('!');
// => 'hiya fred!'

// Связывание с заполнителями.
var bound = _.bindKey(object, 'greet',_, '!');
bound('hi');
// => 'hiya fred!'
```

### curry

#### `_.curry(func, [arity=func.length])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L10198) | [npm package](https://www.npmjs.com/package/lodash.curry)

Создает функцию, которая принимает аргументы `func` и либо вызывает `func`, возвращая ее результат, если было предоставлено хотя бы `arity` количество аргументов, либо возвращает функцию, которая принимает оставшиеся аргументы `func` и так далее. Арность `func` может быть указана, если `func.length` недостаточно.

Значение `_.curry.placeholder`, которое по умолчанию равно `_` в монолитных сборках, может использоваться в качестве заполнителя для предоставленных аргументов.

**Note:** Этот метод не устанавливает свойство `length` каррированных функций.

#### С версии

2.0.0

#### Аргументы

1. `func` (Function): Функция каррирования.
2. `[arity=func.length]` (number): Арность `func`.

#### Возвращает

(Function): Возвращает новую каррированную функцию.

#### Пример

```javascript
var abc = function(a, b, c) {
  return [a, b, c];
};

var curried = _.curry(abc);

curried(1)(2)(3);
// => [1, 2, 3]

curried(1, 2)(3);
// => [1, 2, 3]

curried(1, 2, 3);
// => [1, 2, 3]

// Каррирование с заполнителями.
curried(1)(_, 3)(2);
// => [1, 3, 2]
```

### curryRight

#### `_.curryRight(func, [arity=func.length])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L10243) | [npm package](https://www.npmjs.com/package/lodash.curryright)

Этот метод похож на [`_.curry`](#curry), за исключением того, что аргументы применяются к `func` способом [`_.partialRight`](#partialRight) вместо [`_.partial`](# частичный).

Значение `_.curryRight.placeholder`, которое по умолчанию равно `_` в монолитных сборках, может использоваться в качестве заполнителя для предоставленных аргументов.

**Note:** Этот метод не устанавливает свойство `length` каррированных функций.

#### С версии

3.0.0

#### Аргументы

1. `func` (Function): Функция каррирования.
2. `[arity=func.length]` (number): Арность `func`.

#### Возвращает

(Function): Возвращает новую каррированную функцию.

#### Пример

```javascript
var abc = function(a, b, c) {
  return [a, b, c];
};

var curried = _.curryRight(abc);

curried(3)(2)(1);
// => [1, 2, 3]

curried(2, 3)(1);
// => [1, 2, 3]

curried(1, 2, 3);
// => [1, 2, 3]

// Каррирование с заполнителями.
curried(3)(1, _)(2);
// => [1, 2, 3]
```

### debounce

#### `_.debounce(func, [wait=0], [options={}])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L10304) | [npm package](https://www.npmjs.com/package/lodash.debounce)

Создает функцию устранения дребезга, которая откладывает вызов `func` до тех пор, пока не истечет миллисекунда `wait` с момента последнего вызова функции устранения дребезга. Функция debounced имеет метод `cancel` для отмены отложенных вызовов `func` и метод `flush` для их немедленного вызова. Предоставьте `options`, чтобы указать, следует ли вызывать `func` в начале и/или конце тайм-аута `wait`. `Func` вызывается с последними аргументами, переданными в функцию debounced. Последующие вызовы функции устранения дребезга возвращают результат последнего вызова функции.

**Note:** Если параметры `leading` и`trailing` имеют значение true, `function` вызывается по окончании таймаута только в том случае, если функция устранения дребезга вызывается более одного раза в течение таймаута `wait`.

Если `wait` равен `0`, а `leading` имеет значение `false`, вызов `func` откладывается до следующего тика, аналогично `setTimeout` с таймаутом `0`.

См. [статью Дэвида Корбачо](https://css-tricks.com/debouncing-throttling-explained-examples/) для получения подробной информации о различиях между [`_.debounce`](#debounce) и [`_.throttle` ](#дроссель).

#### С версии

0.1.0

#### Аргументы

1. `func` (Function): Функция устранения дребезга.
2. `[wait=0]` (number): Количество миллисекунд задержки.
3. `[options={}]` (Object): Объект параметров.
4. `[options.leading=false]` (boolean): Укажите вызов по переднему фронту тайм-аута.
5. `[options.maxWait]` (number): Максимальное время задержки `func` перед ее вызовом.
6. `[options.trailing=true]` (boolean): Укажите вызов по заднему фронту тайм-аута.

#### Возвращает

(Function): Returns the new debounced function.

#### Пример

```javascript
// Avoid costly calculations while the window size is in flux.
jQuery(window).on('resize', _.debounce(calculateLayout, 150));

// Invoke `sendMail` when clicked, debouncing subsequent calls.
jQuery(element).on('click', _.debounce(sendMail, 300, {
  'leading': true,
  'trailing': false
}));

// Ensure `batchLog` is invoked once after 1 second of debounced calls.
var debounced = _.debounce(batchLog, 250, { 'maxWait': 1000 });
var source = new EventSource('/stream');

jQuery(source).on('message', debounced);

// Cancel the trailing debounced invocation.
jQuery(window).on('popstate', debounced.cancel);
```

### defer

#### `_.defer(func, [args])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L10447) | [npm package](https://www.npmjs.com/package/lodash.defer)

Откладывает вызов функции до тех пор, пока текущий стек вызовов не очистится. Любые дополнительные аргументы передаются функции при ее вызове.

#### С версии

0.1.0

#### Аргументы

1. `func` (Function): Функция отсрочки.
2. `[args]` (...*): Аргументы для вызова `func`.

#### Возвращает

(number): Возвращает идентификатор таймера.

#### Пример

```javascript
_.defer(function(text) {
  console.log(text);
}, 'deferred');
// => Logs 'deferred' after one millisecond.
```

### delay

#### `_.delay(func, wait, [args])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L10470) | [npm package](https://www.npmjs.com/package/lodash.delay)

Вызывает `func` через `wait` миллисекунд ожидания. Любые дополнительные аргументы передаются функции `func` при ее вызове.

#### С версии

0.1.0

#### Аргументы

1. `func` (Function): Задерживаемая функция.
2. `wait` (number): Количество миллисекунд для задержки вызова.
3. `[args]` (...*): Аргументы для вызова `func`.

#### Возвращает

(number): Возвращает идентификатор таймера.

#### Пример

```javascript
_.delay(function(text) {
  console.log(text);
}, 1000, 'later');
// => Logs 'later' after one second.
```

### flip

#### `_.flip(func)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L10492) | [npm package](https://www.npmjs.com/package/lodash.flip)

Создает функцию, которая вызывает `func` с обратными аргументами.

#### С версии

4.0.0

#### Аргументы

1. `func` (Function): Функция, для которой переворачиваются аргументы.

#### Возвращает

(Function): Возвращает новую перевернутую функцию.

#### Пример

```javascript
var flipped = _.flip(function() {
  return _.toArray(arguments);
});

flipped('a', 'b', 'c', 'd');
// => ['d', 'c', 'b', 'a']
```

### memoize

#### `_.memoize(func, [resolver])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L10540) | [npm package](https://www.npmjs.com/package/lodash.memoize)

Создает функцию, которая запоминает результат func. Если указан `resolver`, он определяет ключ кэша для хранения результата на основе аргументов, предоставленных запоминаемой функции. По умолчанию первый аргумент, предоставленный запоминаемой функции, используется в качестве ключа кэша карты. `Func` вызывается с привязкой `this` к запоминаемой функции.

**Note:** Кэш отображается как свойство кэша запоминаемой функции. Его создание можно настроить, заменив конструктор `_.memoize.Cache` на конструктор, экземпляры которого реализуют [`Map`](http://ecma-international.org/ecma-262/7.0/#sec-properties-of -the-map-prototype-object) интерфейс методов `clear`, `delete`, `get`, `has` и `set`.

#### С версии

0.1.0

#### Аргументы

1. `func` (Function): Функция, вывод которой запоминается.
2. `[resolver]` (Function): Функция для разрешения ключа кэша.

#### Возвращает

(Function): Возвращает новую сохраненную функцию.

#### Пример

```javascript
var object = { 'a': 1, 'b': 2 };
var other = { 'c': 3, 'd': 4 };
var values = _.memoize(_.values);

values(object);
// => [1, 2]

values(other);
// => [3, 4]

object.a = 2;
values(object);
// => [1, 2]

// Modify the result cache.
values.cache.set(object, ['a', 'b']);

values(object);
// => ['a', 'b']

// Replace `_.memoize.Cache`.
_.memoize.Cache = WeakMap;
```

### negate

#### `_.negate(predicate)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L10583) | [npm package](https://www.npmjs.com/package/lodash.negate)

Создает функцию, которая обращает в противоположное значение результат выполнения предиката `func`. Предикат `func` вызывается с связанным значением `this` и аргументами созданной функции.

#### С версии

3.0.0

#### Аргументы

1. `predicate` (Function): Функция для негатива.

#### Возвращает

(Function): Возвращает новую негативную функцию.

#### Пример

```javascript
function isEven(n) {
  return n % 2 == 0;
}

_.filter([1, 2, 3, 4, 5, 6],_.negate(isEven));
// => [1, 3, 5]
```

### once

#### `_.once(func)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L10617) | [npm package](https://www.npmjs.com/package/lodash.once)

Создает функцию, которая может вызывать `func` только один раз. Повторные вызовы функции возвращают значение первого вызова. Вызывается `func` с привязкой `this` и аргументами созданной функции.

#### С версии

0.1.0

#### Аргументы

1. `func` (Function): Функция ограничения.

#### Возвращает

(Function): Возвращает новую ограниченную функцию.

#### Пример

```javascript
var initialize = _.once(createApplication);

initialize();

initialize();
// => `createApplication` is invoked once
```

### overArgs

#### `_.overArgs(func, [transforms=[_.identity]])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L10652) | [npm package](https://www.npmjs.com/package/lodash.overargs)

Создает функцию, которая вызывает `func` с преобразованными аргументами.

#### С версии

4.0.0

#### Аргументы

1. `func` (Function): Функция для оборачивания.
2. `[transforms=[_.identity]]` (...(Function|Function[])): Трансформирование аргументов.

#### Возвращает

(Function): Возвращает новую функцию.

#### Пример

```javascript
function doubled(n) {
  return n * 2;
}

function square(n) {
  return n * n;
}

var func = _.overArgs(function(x, y) {
  return [x, y];
}, [square, doubled]);

func(9, 3);
// => [81, 6]

func(10, 5);
// => [100, 10]
```

### partial

#### `_.partial(func, [partials])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L10702) | [npm package](https://www.npmjs.com/package/lodash.partial)

Создает функцию, которая вызывает `func` с добавлением частичных аргументов к полученным аргументам. Этот метод похож на [`_.bind`](#bind), за исключением того, что он **не** изменяет привязку `this`.

Значение `_.partial.placeholder`, которое по умолчанию равно `_` в монолитных сборках, может использоваться в качестве заполнителя для частично примененных аргументов.

**Note:** Этот метод не устанавливает свойство `length` частично применяемых функций.

#### С версии

0.2.0

#### Аргументы

1. `func` (Function): Функция, к которой частично применяются аргументы.
2. `[partials]` (...*): Аргументы, которые следует применить частично.

#### Возвращает

(Function): Возвращает новую частично примененную функцию.

#### Пример

```javascript
function greet(greeting, name) {
  return greeting + ' ' + name;
}

var sayHelloTo = _.partial(greet, 'hello');

sayHelloTo('fred');
// => 'hello fred'

// Partially applied with placeholders.
var greetFred = _.partial(greet,_, 'fred');

greetFred('hi');
// => 'hi fred'
```

### partialRight

#### `_.partialRight(func, [partials])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L10739) | [npm package](https://www.npmjs.com/package/lodash.partialright)

Этот метод похож на [`_.partial`](#partial), за исключением того, что частично примененные аргументы добавляются к полученным аргументам.

Значение `_.partialRight.placeholder`, которое по умолчанию равно `_` в монолитных сборках, может использоваться в качестве заполнителя для частично примененных аргументов.

**Note:** Этот метод не устанавливает свойство `length` частично применяемых функций.

#### С версии

1.0.0

#### Аргументы

1. `func` (Function): Функция, к которой частично применяются аргументы.
2. `[partials]` (...*): Аргументы, которые следует применить частично.

#### Возвращает

(Function): Возвращает новую частично примененную функцию.

#### Пример

```javascript
function greet(greeting, name) {
  return greeting + ' ' + name;
}

var greetFred = _.partialRight(greet, 'fred');

greetFred('hi');
// => 'hi fred'

// Partially applied with placeholders.
var sayHelloTo = _.partialRight(greet, 'hello',_);

sayHelloTo('fred');
// => 'hello fred'
```

### rearg

#### `_.rearg(func, indexes)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L10766) | [npm package](https://www.npmjs.com/package/lodash.rearg)

Создает функцию, которая вызывает `func` с аргументами, упорядоченными в соответствии с указанными индексами, где значение аргумента по первому индексу предоставляется в качестве первого аргумента, значение аргумента по второму индексу предоставляется в качестве второго аргумента и т.д.

#### С версии

3.0.0

#### Аргументы

1. `func` (Function): Функция, для которой нужно переупорядочить аргументы.
2. `indexes` (...(number|number[])): Упорядоченные индексы аргументов.

#### Возвращает

(Function): Возвращает новую функцию.

#### Пример

```javascript
var rearged = _.rearg(function(a, b, c) {
  return [a, b, c];
}, [2, 0, 1]);

rearged('b', 'c', 'a')
// => ['a', 'b', 'c']
```

### rest

#### `_.rest(func, [start=func.length-1])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L10795) | [npm package](https://www.npmjs.com/package/lodash.rest)

Создает функцию, вызывающую `func`, с привязкой `this` созданной функции и аргументами от `start` и далее, представленными в виде массива.

**Note:** Этот метод основан на [параметре rest](https://mdn.io/rest_parameters).

#### С версии

4.0.0

#### Аргументы

1. `func` (Function): Функция, к которой применяется параметр rest.
2. `[start=func.length-1]` (number): Стартовая позиция параметра rest.

#### Возвращает

(Function): Возвращает новую функцию.

#### Пример

```javascript
var say = _.rest(function(what, names) {
  return what + ' ' + _.initial(names).join(', ') +
    (_.size(names) > 1 ? ', & ' : '') +_.last(names);
});

say('hello', 'fred', 'barney', 'pebbles');
// => 'hello fred, barney, & pebbles'
```

### spread

#### `_.spread(func, [start=0])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L10837) | [npm package](https://www.npmjs.com/package/lodash.spread)

Создает функцию, которая вызывает `func` с привязкой `this` функции создания и массивом аргументов, очень похожим на [`Function#apply`](http://www.ecma-international.org/ecma-262/7.0). /#sec-function.prototype.apply).

**Note:** Этот метод основан на [операторе spread](https://mdn.io/spread_operator).

#### С версии

3.2.0

#### Аргументы

1. `func` (Function): Функция для распределения аргументов.
2. `[start=0]` (number): Стартовая позиция распределения.

#### Возвращает

(Function): Возвращает новую функцию.

#### Пример

```javascript
var say = _.spread(function(who, what) {
  return who + ' says ' + what;
});

say(['fred', 'hello']);
// => 'fred says hello'

var numbers = Promise.all([
  Promise.resolve(40),
  Promise.resolve(36)
]);

numbers.then(_.spread(function(x, y) {
  return x + y;
}));
// => a Promise of 76
```

### throttle

#### `_.throttle(func, [wait=0], [options={}])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L10897) | [npm package](https://www.npmjs.com/package/lodash.throttle)

Создает регулируемую функцию, которая вызывает `func` не чаще одного раза за каждые `wait` миллисекунд ожидания. Дросселируемая функция имеет метод `cancel` для отмены отложенных вызовов `func` и метод `flush` для их немедленного вызова. Предоставьте `options`, чтобы указать, следует ли вызывать `func` в начале и/или конце тайм-аута `wait`. Вызывается `func` с последними аргументами, предоставленными регулируемой функции. Последующие вызовы регулируемой функции возвращают результат последнего вызова функции.

**Note:** Если параметры `leading` и`trailing` имеют значение `true`, `func` вызывается по окончании таймаута только в том случае, если регулируемая функция вызывается более одного раза в течение таймаута `wait`.

Если `wait` равен `0`, а `leading` имеет значение `false`, вызов func` откладывается до следующего тика, аналогично `setTimeout` с таймаутом `0`.

Смотри [статью Дэвида Корбачо](https://css-tricks.com/debouncing-throttling-explained-examples/) для получения подробной информации о различиях между [`_.throttle`](#throttle) и [`_.debounce` ](#debounce).

#### С версии

0.1.0

#### Аргументы

1. `func` (Function): Дросселируемая функция.
2. `[wait=0]` (number): Задержка вызова в миллисекундах.
3. `[options={}]` (Object): Объект параметров.
4. `[options.leading=true]` (boolean): Укажите вызов по переднему фронту тайм-аута.
5. `[options.trailing=true]` (boolean): Укажите вызов по заднему фронту тайм-аута.

#### Возвращает

(Function): Возвращает новую регулируемую функцию.

#### Пример

```javascript
// Avoid excessively updating the position while scrolling.
jQuery(window).on('scroll', _.throttle(updatePosition, 100));

// Invoke `renewToken` when the click event is fired, but not more than once every 5 minutes.
var throttled = _.throttle(renewToken, 300000, { 'trailing': false });

jQuery(element).on('click', throttled);

// Cancel the trailing throttled invocation.
jQuery(window).on('popstate', throttled.cancel);
```

### unary

#### `_.unary(func)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L10930) | [npm package](https://www.npmjs.com/package/lodash.unary)

Создает функцию, которая принимает до одного аргумента, игнорируя любые дополнительные аргументы.

#### С версии

4.0.0

#### Аргументы

1. `func` (Function): Функция для ограничения аргументов.

#### Возвращает

(Function): Возвращает новую ограниченную функцию.

#### Пример

```javascript
_.map(['6', '8', '10'],_.unary(parseInt));
// => [6, 8, 10]
```

### wrap

#### `_.wrap(value, [wrapper=identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L10956) | [npm package](https://www.npmjs.com/package/lodash.wrap)

Создает функцию, которая передает `value` в `wrapper` в качестве первого аргумента. Любые дополнительные аргументы, предоставленные функции, добавляются к аргументам, предоставленным оболочке. Обертка вызывается с привязкой `this` созданной функции.

#### С версии

0.1.0

#### Аргументы

1. `value` (*): Значение для переноса.
2. `[wrapper=identity]` (Function): Функция-обертка.

#### Возвращает

(Function): Возвращает новую функцию.

#### Пример

```javascript
var p = _.wrap(_.escape, function(func, text) {
  return '<p>' + func(text) + '</p>';
});

p('fred, barney, & pebbles');
// => '<p>fred, barney, &amp; pebbles</p>'
```

## Lang

### castArray

#### `_.castArray(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L10995) | [npm package](https://www.npmjs.com/package/lodash.castarray)

Приводит `value` к типу `array`, если это не так.

#### С версии

4.4.0

#### Аргументы

1. `value` (*): Значение для приведения к массиву.

#### Возвращает

`(Array)`: Возвращает приведенный массив.

#### Пример

```javascript
_.castArray(1);
// => [1]

_.castArray({ 'a': 1 });
// => [{ 'a': 1 }]

_.castArray('abc');
// => ['abc']

_.castArray(null);
// => [null]

_.castArray(undefined);
// => [undefined]

_.castArray();
// => []

var array = [1, 2, 3];

console.log(_.castArray`(Array)` === array);
// => true
```

### clone

#### `_.clone(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11029) | [npm package](https://www.npmjs.com/package/lodash.clone)

Создает поверхностный клон `value`.

**Note:** Этот метод во многом основан на [алгоритме структурированного клонирования] (https://mdn.io/Structured_clone_algorithm) и поддерживает клонирование массивов, бинарных массивов, логических значений, объектов даты, карт, чисел, объектов `object`, регулярных выражений, наборов, строк, символов и типизированных массивов. Собственные перечислимые свойства объектов аргументов клонируются как простые объекты. Пустой объект возвращается для неклонируемых значений, таких как объекты ошибок, функции, узлы DOM и WeakMaps.

#### С версии

0.1.0

#### Аргументы

1. `value` (*): Значение для клонирования.

#### Возвращает

(*): Возвращает клонированное значение.

#### Пример

```javascript
var objects = [{ 'a': 1 }, { 'b': 2 }];
var shallow = _.clone(objects);

console.log(shallow[0] === objects[0]);
// => true
```

### cloneDeep

#### `_.cloneDeep(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11087) | [npm package](https://www.npmjs.com/package/lodash.clonedeep)

Этот метод похож на [`_.clone`](#clone), за исключением того, что он рекурсивно клонирует `value`.

#### С версии

1.0.0

#### Аргументы

1. `value` (*): Значение для рекурсивного клонирования.

#### Возвращает

(*): Возвращает глубоко клонированное значение.

#### Пример

```javascript
var objects = [{ 'a': 1 }, { 'b': 2 }];
var deep = _.cloneDeep(objects);

console.log(deep[0] === objects[0]);
// => false
```

### cloneDeepWith

#### `_.cloneDeepWith(value, [customizer])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11119) | [npm package](https://www.npmjs.com/package/lodash.clonedeepwith)

Этот метод похож на [`_.cloneWith`](#cloneWith), за исключением того, что он рекурсивно клонирует `value`.

#### С версии

4.0.0

#### Аргументы

1. `value` (*): Значение для рекурсивного клонирования.
2. `[customizer]` (Function): Функция настройки клонирования.

#### Возвращает

(*): Возвращает глубоко клонированное значение.

#### Пример

```javascript
function customizer(value) {
  if (_.isElement(value)) {
    return value.cloneNode(true);
  }
}

var el = _.cloneDeepWith(document.body, customizer);

console.log(el === document.body);
// => false

console.log(el.nodeName);
// => 'BODY'

console.log(el.childNodes.length);
// => 20
```

### cloneWith

#### `_.cloneWith(value, [customizer])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11064) | [npm package](https://www.npmjs.com/package/lodash.clonewith)

Этот метод похож на [`_.clone`](#clone), за исключением того, что он принимает функцию `customizer`, которая вызывается для создания клонированного значения. Если `customizer` возвращает `undefined`, вместо этого клонирование обрабатывается методом. `customizer` вызывается с четырьмя аргументами; (значение [, индекс|ключ, объект, стек]).

#### С версии

4.0.0

#### Аргументы

1. `value` (*): Значение для клонирования.
2. `[customizer]` (Function): Функция настройки клонирования.

#### Возвращает

(*): Возвращает клонированное значение.

#### Пример

```javascript
function customizer(value) {
  if (_.isElement(value)) {
    return value.cloneNode(false);
  }
}

var el = _.cloneWith(document.body, customizer);

console.log(el === document.body);
// => false

console.log(el.nodeName);
// => 'BODY'

console.log(el.childNodes.length);
// => 0
```

### conformsTo

#### `_.conformsTo(object, source)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11148) | [npm package](https://www.npmjs.com/package/lodash.conformsto)

Проверяет, соответствует ли объект источнику, вызывая свойства предиката источника с соответствующими значениями свойств объекта.

**Note:** Этот метод эквивалентен [`_.conforms`](#conforms), когда `source` применяется частично.

#### С версии

4.14.0

#### Аргументы

1. `object` (Object): Объект проверки.
2. `source` (Object): Предикаты свойства объекта, которым необходимо соответствовать.

#### Возвращает

(boolean): Возвращает `true`, если объект соответствует, иначе — `false`.

#### Пример

```javascript
var object = { 'a': 1, 'b': 2 };

_.conformsTo(object, { 'b': function(n) { return n > 1; } });
// => true

_.conformsTo(object, { 'b': function(n) { return n > 2; } });
// => false
```

### eq

#### `_.eq(value, other)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11184) | [npm package](https://www.npmjs.com/package/lodash.eq)

Выполняет сравнение [`SameValueZero`](http://ecma-international.org/ecma-262/7.0/#sec-samevaluezero) между двумя значениями, чтобы определить, эквивалентны ли они.

#### С версии

4.0.0

#### Аргументы

1. `value` (*): Значение для сравнения.
2. `other` (*): Другое значение для сравнения.

#### Возвращает

(boolean): Возвращает `true`, если объект соответствует, иначе — `false`.

#### Пример

```javascript
var object = { 'a': 1 };
var other = { 'a': 1 };

_.eq(object, object);
// => true

_.eq(object, other);
// => false

_.eq('a', 'a');
// => true

_.eq('a', Object('a'));
// => false

_.eq(NaN, NaN);
// => true
```

### gt

#### `_.gt(value, other)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11211) | [npm package](https://www.npmjs.com/package/lodash.gt)

Проверяет, больше ли `value`, чем `other`.

#### С версии

3.9.0

#### Аргументы

1. `value` (*): Значение для сравнения.
2. `other` (*): Другое значение для сравнения.

#### Возвращает

(boolean): Возвращает `true`, если `value` больше, чем `other`, иначе — `false`.

#### Пример

```javascript
_.gt(3, 1);
// => true

_.gt(3, 3);
// => false

_.gt(1, 3);
// => false
```

### gte

#### `_.gte(value, other)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11236) | [npm package](https://www.npmjs.com/package/lodash.gte)

Проверяет, больше или равно `value`, чем `other`.

#### С версии

3.9.0

#### Аргументы

1. `value` (*): Значение для сравнения.
2. `other` (*): Другое значение для сравнения.

#### Возвращает

(boolean): Возвращает `true`, если `value` больше или равно `other`, иначе — `false`.

#### Пример

```javascript
_.gte(3, 1);
// => true

_.gte(3, 3);
// => true

_.gte(1, 3);
// => false
```

### isArguments

#### `_.isArguments(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11258) | [npm package](https://www.npmjs.com/package/lodash.isarguments)

Проверяет, является ли `value` объектом `arguments`.

#### С версии

0.1.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` является объектом аргументов, иначе — `false`.

#### Пример

```javascript
_.isArguments(function() { return arguments; }());
// => true

_.isArguments([1, 2, 3]);
// => false
```

### isArray

#### `_.isArray(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11286) | [npm package](https://www.npmjs.com/package/lodash.isarray)

Проверяет, классифицируется ли `value` как объект `Array`.

#### С версии

0.1.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` — массив, иначе — `false`.

#### Пример

```javascript
_.isArray([1, 2, 3]);
// => true

_.isArray(document.body.children);
// => false

_.isArray('abc');
// => false

_.isArray(_.noop);
// => false
```

### isArrayBuffer

#### `_.isArrayBuffer(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11305) | [npm package](https://www.npmjs.com/package/lodash.isarraybuffer)

Проверяет, является ли `value` бинарным массивом.

#### С версии

4.3.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` является бинарным массивом, иначе — `false`.

#### Пример

```javascript
_.isArrayBuffer(new ArrayBuffer(2));
// => true

_.isArrayBuffer(new Array(2));
// => false
```

### isArrayLike

#### `_.isArrayLike(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11332) | [npm package](https://www.npmjs.com/package/lodash.isarraylike)

Проверяет, является ли `value` массивом. Значение считается подобным массиву, если оно не является функцией и имеет `value.length`, представляющее собой целое число, большее или равное `0`, и меньшее или равное `Number.MAX_SAFE_INTEGER`.

#### С версии

4.0.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` подобен массиву, иначе — `false`.

#### Пример

```javascript
_.isArrayLike([1, 2, 3]);
// => true

_.isArrayLike(document.body.children);
// => true

_.isArrayLike('abc');
// => true

_.isArrayLike(_.noop);
// => false
```

### isArrayLikeObject

#### `_.isArrayLikeObject(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11361) | [npm package](https://www.npmjs.com/package/lodash.isarraylikeobject)

Этот метод похож на [`_.isArrayLike`](#isArrayLike), за исключением того, что он также проверяет, является ли `value` объектом.

#### С версии

4.0.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` — подобный массиву объект, иначе — `false`.

#### Пример

```javascript
_.isArrayLikeObject([1, 2, 3]);
// => true

_.isArrayLikeObject(document.body.children);
// => true

_.isArrayLikeObject('abc');
// => false

_.isArrayLikeObject(_.noop);
// => false
```

### isBoolean

#### `_.isBoolean(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11382) | [npm package](https://www.npmjs.com/package/lodash.isboolean)

Проверяет, классифицируется ли `value` как логический примитив или объект.

#### С версии

0.1.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` — логическое значение, иначе — `false`.

#### Пример

```javascript
_.isBoolean(false);
// => true

_.isBoolean(null);
// => false
```

### isBuffer

#### `_.isBuffer(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11404) | [npm package](https://www.npmjs.com/package/lodash.isbuffer)

Проверяет, является ли `value` буфером.

#### С версии

4.3.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` является буфером, иначе — `false`.

#### Пример

```javascript
_.isBuffer(new Buffer(2));
// => true

_.isBuffer(new Uint8Array(2));
// => false
```

### isDate

#### `_.isDate(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11423) | [npm package](https://www.npmjs.com/package/lodash.isdate)

Проверяет, классифицируется ли `value` как объект `Date`.

#### С версии

0.1.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` является объектом даты, иначе — `false`.

#### Пример

```javascript
_.isDate(new Date);
// => true

_.isDate('Mon April 23 2012');
// => false
```

### isElement

#### `_.isElement(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11442) | [npm package](https://www.npmjs.com/package/lodash.iselement)

Проверяет, является ли `value` элементом DOM.

#### С версии

0.1.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` является элементом DOM, иначе — `false`.

#### Пример

```javascript
_.isElement(document.body);
// => true

_.isElement('<body>');
// => false
```

### isEmpty

#### `_.isEmpty(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11479) | [npm package](https://www.npmjs.com/package/lodash.isempty)

Проверяет, является ли `value` пустым объектом, коллекцией, Map или Set.

Объекты считаются пустыми, если они не имеют собственных перечислимых свойств со строковыми ключами.

Значения, подобные массивам, такие как объекты аргументов, массивы, буферы, строки или коллекции типа `jQuery`, считаются пустыми, если их длина равна `0`. Аналогично, карты и наборы считаются пустыми, если их `length` равен `0`.

#### С версии

0.1.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` пусто, иначе — `false`.

#### Пример

```javascript
_.isEmpty(null);
// => true

_.isEmpty(true);
// => true

_.isEmpty(1);
// => true

_.isEmpty([1, 2, 3]);
// => false

_.isEmpty({ 'a': 1 });
// => false
```

### isEqual

#### `_.isEqual(value, other)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11531) | [npm package](https://www.npmjs.com/package/lodash.isequal)

Выполняет глубокое сравнение двух значений, чтобы определить, эквивалентны ли они.

**Note:** Этот метод поддерживает сравнение массивов, бинарных массивов, логических значений, объектов даты, объектов ошибок, карт, чисел, объектов `Object`, регулярных выражений, наборов, строк, символов и типизированных массивов. Объекты `Object` сравниваются по своим собственным, а не унаследованным перечислимым свойствам. Функции и узлы DOM сравниваются по принципу строгого равенства, т.е. `===`.

#### С версии

0.1.0

#### Аргументы

1. `value` (*): Значение для сравнения.
2. `other` (*): Другое значение для сравнения.

#### Возвращает

(boolean): Возвращает `true`, если объект соответствует, иначе — `false`.

#### Пример

```javascript
var object = { 'a': 1 };
var other = { 'a': 1 };

_.isEqual(object, other);
// => true

object === other;
// => false
```

### isEqualWith

#### `_.isEqualWith(value, other, [customizer])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11567) | [npm package](https://www.npmjs.com/package/lodash.isequalwith)

Этот метод похож на [`_.isEqual`](#isEqual), за исключением того, что он принимает `customizer`, который вызывается для сравнения значений. Если `customizer` возвращает `undefined`, вместо этого сравнения обрабатываются методом. `customizer` вызывается с использованием до шести аргументов: (objValue, othValue [, index|key, object, Other, stack]).

#### С версии

4.0.0

#### Аргументы

1. `value` (*): Значение для сравнения.
2. `other` (*): Другое значение для сравнения.
3. `[customizer]` (Function): Функция настройки сравнения.

#### Возвращает

(boolean): Возвращает `true`, если объект соответствует, иначе — `false`.

#### Пример

```javascript
function isGreeting(value) {
  return /^h(?:i|ello)$/.test(value);
}

function customizer(objValue, othValue) {
  if (isGreeting(objValue) && isGreeting(othValue)) {
    return true;
  }
}

var array = ['hello', 'goodbye'];
var other = ['hi', 'goodbye'];

_.isEqualWith(array, other, customizer);
// => true
```

### isError

#### `_.isError(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11591) | [npm package](https://www.npmjs.com/package/lodash.iserror)

Проверяет, является ли `value` объектом `Error`, `EvalError`, `RangeError`, `ReferenceError`, `SyntaxError`, `TypeError` или `URIError`.

#### С версии

3.0.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` является объектом ошибки, иначе — `false`.

#### Пример

```javascript
_.isError(new Error);
// => true

_.isError(Error);
// => false
```

### isFinite

#### `_.isFinite(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11626) | [npm package](https://www.npmjs.com/package/lodash.isfinite)

Проверяет, является ли `value` конечным примитивным числом.

**Note:** Этот метод основан на [`Number.isFinite`](https://mdn.io/Number/isFinite).

#### С версии

0.1.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` — конечное число, иначе — `false`.

#### Пример

```javascript
_.isFinite(3);
// => true

_.isFinite(Number.MIN_VALUE);
// => true

_.isFinite(Infinity);
// => false

_.isFinite('3');
// => false
```

### isFunction

#### `_.isFunction(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11647) | [npm package](https://www.npmjs.com/package/lodash.isfunction)

Проверяет, классифицируется ли `value` как объект `Function`.

#### С версии

0.1.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` — функция, иначе — `false`.

#### Пример

```javascript
_.isFunction(_);
// => true

_.isFunction(/abc/);
// => false
```

### isInteger

#### `_.isInteger(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11683) | [npm package](https://www.npmjs.com/package/lodash.isinteger)

Проверяет, является ли `value` целым числом.

**Note:** Этот метод основан на [`Number.isInteger`](https://mdn.io/Number/isInteger).

#### С версии

4.0.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` — целое число, иначе — `false`.

#### Пример

```javascript
_.isInteger(3);
// => true

_.isInteger(Number.MIN_VALUE);
// => false

_.isInteger(Infinity);
// => false

_.isInteger('3');
// => false
```

### isLength

#### `_.isLength(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11713) | [npm package](https://www.npmjs.com/package/lodash.islength)

Проверяет, является ли `value` допустимой `length` массивоподобных объектов.

**Note:** Этот метод во многом основан на [`ToLength`](http://ecma-international.org/ecma-262/7.0/#sec-tolength).

#### С версии

4.0.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` имеет допустимую длину, иначе — `false`.

#### Пример

```javascript
_.isLength(3);
// => true

_.isLength(Number.MIN_VALUE);
// => false

_.isLength(Infinity);
// => false

_.isLength('3');
// => false
```

### isMap

#### `_.isMap(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11793) | [npm package](https://www.npmjs.com/package/lodash.ismap)

Проверяет, классифицируется ли `value` как объект `Map`.

#### С версии

4.3.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает true, если `value` — карта, иначе — `false`.

#### Пример

```javascript
_.isMap(new Map);
// => true

_.isMap(new WeakMap);
// => false
```

### isMatch

#### `_.isMatch(object, source)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11823) | [npm package](https://www.npmjs.com/package/lodash.ismatch)

Выполняет частичное глубокое сравнение между `object` и `source`, чтобы определить, содержит ли объект эквивалентные значения свойств.

**Note:** Этот метод эквивалентен [`_.matches`](#matches), когда `source` применяется частично.

Частичные сравнения будут сопоставлять значения пустого массива и пустого объекта `source` с любым значением массива или объекта соответственно. См. [`_.isEqual`](#isEqual) для списка поддерживаемых сравнений значений.

#### С версии

3.0.0

#### Аргументы

1. `object` (Object): Объект проверки.
2. `source` (Object): Объект значений свойств, которые необходимо сопоставить.

#### Возвращает

(boolean): Возвращает `true`, если объект соответствует, иначе — `false`.

#### Пример

```javascript
var object = { 'a': 1, 'b': 2 };

_.isMatch(object, { 'b': 2 });
// => true

_.isMatch(object, { 'b': 1 });
// => false
```

### isMatchWith

#### `_.isMatchWith(object, source, [customizer])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11859) | [npm package](https://www.npmjs.com/package/lodash.ismatchwith)

Этот метод похож на [`_.isMatch`](#isMatch), за исключением того, что он принимает `customizer`, который вызывается для сравнения значений. Если `customizer` возвращает `undefined`, вместо этого сравнения обрабатываются методом. Вызывается `customizer` с пятью аргументами: (objValue, srcValue, index|key, object, source).

#### С версии

4.0.0

#### Аргументы

1. `object` (Object): Объект проверки.
2. `source` (Object): Объект значений свойств, которые необходимо сопоставить.
3. `[customizer]` (Function): Функция настройки сравнения.

#### Возвращает

(boolean): Возвращает `true`, если объект соответствует, иначе — `false`.

#### Пример

```javascript
function isGreeting(value) {
  return /^h(?:i|ello)$/.test(value);
}

function customizer(objValue, srcValue) {
  if (isGreeting(objValue) && isGreeting(srcValue)) {
    return true;
  }
}

var object = { 'greeting': 'hello' };
var source = { 'greeting': 'hi' };

_.isMatchWith(object, source, customizer);
// => true
```

### isNaN

#### `_.isNaN(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11892) | [npm package](https://www.npmjs.com/package/lodash.isnan)

Проверяет, является ли значение `NaN`.

**Note:** Этот метод основан на [`Number.isNaN`](https://mdn.io/Number/isNaN) и отличается от глобального [`isNaN`](https://mdn.io/isNaN), который возвращает `true` для `undefined` и других нечисловых значений.

#### С версии

0.1.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если значение равно `NaN`, иначе — `false`.

#### Пример

```javascript
_.isNaN(NaN);
// => true

_.isNaN(new Number(NaN));
// => true

isNaN(undefined);
// => true

_.isNaN(undefined);
// => false
```

### isNative

#### `_.isNative(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11925) | [npm package](https://www.npmjs.com/package/lodash.isnative)

Проверяет, является ли `value` чистой собственной функцией.

**Note:** Этот метод не может надежно обнаружить собственные функции при наличии пакета core-js, поскольку core-js обходит этот тип обнаружения. Несмотря на многочисленные запросы, сопровождающий core-js ясно дал понять: любая попытка исправить обнаружение будет пресечена. В результате у нас не остается другого выбора, кроме как выдать ошибку. К сожалению, это также влияет на такие пакеты, как [babel-polyfill](https://www.npmjs.com/package/babel-polyfill), которые полагаются на core-js.

#### С версии

3.0.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` — встроенная функция, иначе — `false`.

#### Пример

```javascript
_.isNative(Array.prototype.push);
// => true

_.isNative(_);
// => false
```

### isNil

#### `_.isNil(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11973) | [npm package](https://www.npmjs.com/package/lodash.isnil)

Проверяет, является ли `value` `null` или `undefined`.

#### С версии

4.0.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если значение `nil`, иначе — `false`.

#### Пример

```javascript
_.isNil(null);
// => true

_.isNil(void 0);
// => true

_.isNil(NaN);
// => false
```

### isNull

#### `_.isNull(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11949) | [npm package](https://www.npmjs.com/package/lodash.isnull)

Проверяет, имеет ли значение значение `null`.

#### С версии

0.1.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если значение равно `null`, иначе — `false`.

#### Пример

```javascript
_.isNull(null);
// => true

_.isNull(void 0);
// => false
```

### isNumber

#### `_.isNumber(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12003) | [npm package](https://www.npmjs.com/package/lodash.isnumber)

Проверяет, классифицируется ли `value` как примитив или объект `Number`.

**Note:** Чтобы исключить `Infinity`, `-Infinity` и `NaN`, которые классифицируются как числа, используйте метод [`_.isFinite`](#isFinite).

#### С версии

0.1.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` — число, иначе — `false`.

#### Пример

```javascript
_.isNumber(3);
// => true

_.isNumber(Number.MIN_VALUE);
// => true

_.isNumber(Infinity);
// => true

_.isNumber('3');
// => false
```

### isObject

#### `_.isObject(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11743) | [npm package](https://www.npmjs.com/package/lodash.isobject)

Проверяет, является ли `value` [типом языка](http://www.ecma-international.org/ecma-262/7.0/#sec-ecmascript-language-types) `Object`. (например, массивы, функции, объекты, регулярные выражения, `new Number(0)` и `new String('')`)

#### С версии

0.1.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` является типом языка, иначе — `false`.

#### Пример

```javascript
_.isObject({});
// => true

_.isObject([1, 2, 3]);
// => true

_.isObject(_.noop);
// => true

_.isObject(null);
// => false
```

### isObjectLike

#### `_.isObjectLike(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L11772) | [npm package](https://www.npmjs.com/package/lodash.isobjectlike)

Проверяет, является ли `value` объектным. Значение является объектноподобным, если оно не равно `null` и имеет результат `typeof` как "object".

#### С версии

4.0.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` подобен объекту, иначе — `false`.

#### Пример

```javascript
_.isObjectLike({});
// => true

_.isObjectLike([1, 2, 3]);
// => true

_.isObjectLike(_.noop);
// => false

_.isObjectLike(null);
// => false
```

### isPlainObject

#### `_.isPlainObject(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12036) | [npm package](https://www.npmjs.com/package/lodash.isplainobject)

Проверяет, является ли `value` простым объектом, то есть объектом, созданным конструктором `Object`, или объектом с `[[Prototype]]` равным `null`.

#### С версии

0.8.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` — простой объект, иначе — `false`.

#### Пример

```javascript
function Foo() {
  this.a = 1;
}

_.isPlainObject(new Foo);
// => false

_.isPlainObject([1, 2, 3]);
// => false

_.isPlainObject({ 'x': 0, 'y': 0 });
// => true

_.isPlainObject(Object.create(null));
// => true
```

### isRegExp

#### `_.isRegExp(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12066) | [npm package](https://www.npmjs.com/package/lodash.isregexp)

Проверяет, классифицируется ли `value` как объект `RegExp`.

#### С версии

0.1.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` является регулярным выражением, иначе — `false`.

#### Пример

```javascript
_.isRegExp(/abc/);
// => true

_.isRegExp('/abc/');
// => false
```

### isSafeInteger

#### `_.isSafeInteger(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12095) | [npm package](https://www.npmjs.com/package/lodash.issafeinteger)

Проверяет, является ли `value` безопасным целым числом. Целое число безопасно, если оно представляет собой число двойной точности IEEE-754, которое не является результатом округленного небезопасного целого числа.

**Note:** Этот метод основан на [`Number.isSafeInteger`](https://mdn.io/Number/isSafeInteger).

#### С версии

4.0.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` — безопасное целое число, иначе — `false`.

#### Пример

```javascript
_.isSafeInteger(3);
// => true

_.isSafeInteger(Number.MIN_VALUE);
// => false

_.isSafeInteger(Infinity);
// => false

_.isSafeInteger('3');
// => false
```

### isSet

#### `_.isSet(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12116) | [npm package](https://www.npmjs.com/package/lodash.isset)

Проверяет, классифицируется ли `value` как объект `Set`.

#### С версии

4.3.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` — набор, иначе — `false`.

#### Пример

```javascript
_.isSet(new Set);
// => true

_.isSet(new WeakSet);
// => false
```

### isString

#### `_.isString(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12135) | [npm package](https://www.npmjs.com/package/lodash.isstring)

Проверяет, классифицируется ли `value` как примитив или объект `String`.

#### С версии

0.1.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` — строка, иначе — `false`.

#### Пример

```javascript
_.isString('abc');
// => true

_.isString(1);
// => false
```

### isSymbol

#### `_.isSymbol(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12157) | [npm package](https://www.npmjs.com/package/lodash.issymbol)

Проверяет, классифицируется ли `value` как примитив или объект `Symbol`.

#### С версии

4.0.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если значение является символом, иначе — `false`.

#### Пример

```javascript
_.isSymbol(Symbol.iterator);
// => true

_.isSymbol('abc');
// => false
```

### isTypedArray

#### `_.isTypedArray(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12179) | [npm package](https://www.npmjs.com/package/lodash.istypedarray)

Проверяет, классифицируется ли `value` как типизированный массив.

#### С версии

3.0.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` — типизированный массив, иначе — `false`.

#### Пример

```javascript
_.isTypedArray(new Uint8Array);
// => true

_.isTypedArray([]);
// => false
```

### isUndefined

#### `_.isUndefined(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12198) | [npm package](https://www.npmjs.com/package/lodash.isundefined)

Проверяет, является ли значение `undefined`.

#### С версии

0.1.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если значение `undefined`, иначе — `false`.

#### Пример

```javascript
_.isUndefined(void 0);
// => true

_.isUndefined(null);
// => false
```

### isWeakMap

#### `_.isWeakMap(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12219) | [npm package](https://www.npmjs.com/package/lodash.isweakmap)

Проверяет, классифицируется ли `value` как объект `WeakMap`.

#### С версии

4.3.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если `value` имеет тип `WeakMap`, иначе — `false`.

#### Пример

```javascript
_.isWeakMap(new WeakMap);
// => true

_.isWeakMap(new Map);
// => false
```

### isWeakSet

#### `_.isWeakSet(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12240) | [npm package](https://www.npmjs.com/package/lodash.isweakset)

Проверяет, классифицируется ли `value` как объект `WeakSet`.

#### С версии

4.3.0

#### Аргументы

1. `value` (*): Значение для проверки.

#### Возвращает

(boolean): Возвращает `true`, если значение является `WeakSet`, иначе — `false`.

#### Пример

```javascript
_.isWeakSet(new WeakSet);
// => true

_.isWeakSet(new Set);
// => false
```

### lt

#### `_.lt(value, other)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12267) | [npm package](https://www.npmjs.com/package/lodash.lt)

Проверяет, меньше ли `value`, чем `other`.

#### С версии

3.9.0

#### Аргументы

1. `value` (*): Значение для сравнения.
2. `other` (*): Другое значение для сравнения.

#### Возвращает

(boolean): Возвращает true, если значение меньше другого, иначе — false.

#### Пример

```javascript
_.lt(1, 3);
// => true

_.lt(3, 3);
// => false

_.lt(3, 1);
// => false
```

### lte

#### `_.lte(value, other)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12292) | [npm package](https://www.npmjs.com/package/lodash.lte)

Проверяет, меньше ли `value`, чем `other` или равно ему.

#### С версии

3.9.0

#### Аргументы

1. `value` (*): Значение для сравнения.
2. `other` (*): Другое значение для сравнения.

#### Возвращает

(boolean): Возвращает `true`, если `value` больше или равно `other`, иначе — `false`.

#### Пример

```javascript
_.lte(1, 3);
// => true

_.lte(3, 3);
// => true

_.lte(3, 1);
// => false
```

### toArray

#### `_.toArray(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12319) | [npm package](https://www.npmjs.com/package/lodash.toarray)

Преобразует `value` в массив.

#### С версии

0.1.0

#### Аргументы

1. `value` (*): Значение для преобразования.

#### Возвращает

`(Array)`: Возвращает преобразованный массив.

#### Пример

```javascript
_.toArray({ 'a': 1, 'b': 2 });
// => [1, 2]

_.toArray('abc');
// => ['a', 'b', 'c']

_.toArray(1);
// => []

_.toArray(null);
// => []
```

### toFinite

#### `_.toFinite(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12358) | [npm package](https://www.npmjs.com/package/lodash.tofinite)

Преобразует `value` в конечное число.

#### С версии

4.12.0

#### Аргументы

1. `value` (*): Значение для преобразования.

#### Возвращает

(number): Возвращает преобразованное число.

#### Пример

```javascript
_.toFinite(3.2);
// => 3.2

_.toFinite(Number.MIN_VALUE);
// => 5e-324

_.toFinite(Infinity);
// => 1.7976931348623157e+308

_.toFinite('3.2');
// => 3.2
```

### toInteger

#### `_.toInteger(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12396) | [npm package](https://www.npmjs.com/package/lodash.tointeger)

Преобразует `value` в целое число.

**Note:** Этот метод во многом основан на [`ToInteger`](http://www.ecma-international.org/ecma-262/7.0/#sec-tointeger).

#### С версии

4.0.0

#### Аргументы

1. `value` (*): Значение для преобразования.

#### Возвращает

(number): Возвращает преобразованное целое число.

#### Пример

```javascript
_.toInteger(3.2);
// => 3

_.toInteger(Number.MIN_VALUE);
// => 0

_.toInteger(Infinity);
// => 1.7976931348623157e+308

_.toInteger('3.2');
// => 3
```

### toLength

#### `_.toLength(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12430) | [npm package](https://www.npmjs.com/package/lodash.tolength)

Преобразует `value` в целое число, подходящее для использования в качестве длины объекта, подобного массиву.

**Note:** Этот метод основан на [`ToLength`](http://ecma-international.org/ecma-262/7.0/#sec-tolength).

#### С версии

4.0.0

#### Аргументы

1. `value` (*): Значение для преобразования.

#### Возвращает

(number): Возвращает преобразованное целое число.

#### Пример

```javascript
_.toLength(3.2);
// => 3

_.toLength(Number.MIN_VALUE);
// => 0

_.toLength(Infinity);
// => 4294967295

_.toLength('3.2');
// => 3
```

### toNumber

#### `_.toNumber(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12457) | [npm package](https://www.npmjs.com/package/lodash.tonumber)

Преобразует `value` в число.

#### С версии

4.0.0

#### Аргументы

1. `value` (*): Значение для обработки.

#### Возвращает

(number): Возвращает число.

#### Пример

```javascript
_.toNumber(3.2);
// => 3.2

_.toNumber(Number.MIN_VALUE);
// => 5e-324

_.toNumber(Infinity);
// => Infinity

_.toNumber('3.2');
// => 3.2
```

### toPlainObject

#### `_.toPlainObject(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12502) | [npm package](https://www.npmjs.com/package/lodash.toplainobject)

Преобразует `value` в простой объект, выравнивая унаследованные перечислимые строковые свойства `value` в собственные свойства простого объекта.

#### С версии

3.0.0

#### Аргументы

1. `value` (*): Значение для преобразования.

#### Возвращает

(Object): Возвращает преобразованный простой объект.

#### Пример

```javascript
function Foo() {
  this.b = 2;
}

Foo.prototype.c = 3;

_.assign({ 'a': 1 }, new Foo);
// => { 'a': 1, 'b': 2 }

_.assign({ 'a': 1 },_.toPlainObject(new Foo));
// => { 'a': 1, 'b': 2, 'c': 3 }
```

### toSafeInteger

#### `_.toSafeInteger(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12530) | [npm package](https://www.npmjs.com/package/lodash.tosafeinteger)

Преобразует `value` в безопасное целое число. Безопасное целое число можно сравнить и представить правильно.

#### С версии

4.0.0

#### Аргументы

1. `value` (*): Значение для преобразования.

#### Возвращает

(number): Возвращает преобразованное целое число.

#### Пример

```javascript
_.toSafeInteger(3.2);
// => 3

_.toSafeInteger(Number.MIN_VALUE);
// => 0

_.toSafeInteger(Infinity);
// => 9007199254740991

_.toSafeInteger('3.2');
// => 3
```

### toString

#### `_.toString(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12557) | [npm package](https://www.npmjs.com/package/lodash.tostring)

Преобразует `value` в строку. Пустая строка возвращается для значений `null` и `undefined`. Знак `-0` сохраняется.

#### С версии

4.0.0

#### Аргументы

1. `value` (*): Значение для преобразования.

#### Возвращает

(string): Возвращает преобразованную строку.

#### Пример

```javascript
_.toString(null);
// => ''

_.toString(-0);
// => '-0'

_.toString([1, 2, 3]);
// => '1,2,3'
```

## Math

### add

#### `_.add(augend, addend)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L16192) | [npm package](https://www.npmjs.com/package/lodash.add)

Складывает два числа.

#### С версии

3.4.0

#### Аргументы

1. `augend` (number): Первое слагательное.
2. `addend` (number): Второе слагательное.

#### Возвращает

(number): Возвращает сумму.

#### Пример

```javascript
_.add(6, 4);
// => 10
```

### ceil

#### `_.ceil(number, [precision=0])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L16217) | [npm package](https://www.npmjs.com/package/lodash.ceil)

Вычисляет `number`, округляемое вверх до точности `precision`.

#### С версии

3.10.0

#### Аргументы

1. `number` (number): Число, которое нужно округлить в бо́льшую сторону.
2. `[precision=0]` (number): Точность округления.

#### Возвращает

(number): Возвращает округленное число.

#### Пример

```javascript
_.ceil(4.006);
// => 5

_.ceil(6.004, 2);
// => 6.01

_.ceil(6040, -2);
// => 6100
```

### divide

#### `_.divide(dividend, divisor)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L16234) | [npm package](https://www.npmjs.com/package/lodash.divide)

Делит число `dividend` на `divisor`.

#### С версии

4.7.0

#### Аргументы

1. `dividend` (number): Делимое.
2. `divisor` (number): Делитель.

#### Возвращает

(number): Возвращает частное.

#### Пример

```javascript
_.divide(6, 4);
// => 1.5
```

### floor

#### `_.floor(number, [precision=0])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L16259) | [npm package](https://www.npmjs.com/package/lodash.floor)

Вычисляет `number`, округляемое вниз до точности `precision`.

#### С версии

3.10.0

#### Аргументы

1. `number` (number): Число, которое нужно округлить в меньшую сторону.
2. `[precision=0]` (number): Точность округления.

#### Возвращает

(number): Возвращает округленное число.

#### Пример

```javascript
_.floor(4.006);
// => 4

_.floor(0.046, 2);
// => 0.04

_.floor(4060, -2);
// => 4000
```

### max

#### `_.max(array)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L16279) | [npm package](https://www.npmjs.com/package/lodash.max)

Вычисляет максимальное значение массива. Если массив пуст или имеет ложное значение, возвращается неопределенное значение.

#### С версии

0.1.0

#### Аргументы

1. `array` `(Array)`: Массив, по которому необходимо выполнить итерацию.

#### Возвращает

(*): Возвращает максимальное значение.

#### Пример

```javascript
_.max([4, 2, 8, 6]);
// => 8

_.max([]);
// => undefined
```

### maxBy

#### `_.maxBy(array, [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L16308) | [npm package](https://www.npmjs.com/package/lodash.maxby)

Этот метод похож на [`_.max`](#max), за исключением того, что он принимает `iteratee`, который вызывается для каждого элемента в `array` для генерации критерия, по которому ранжируется значение. Итератор вызывается с одним аргументом: (значение).

#### С версии

4.0.0

#### Аргументы

1. `array` `(Array)`: Массив, по которому необходимо выполнить итерацию.
2. `[iteratee=_.identity]` (Function): Итератор, вызываемый для каждого элемента.

#### Возвращает

(*): Возвращает максимальное значение.

#### Пример

```javascript
var objects = [{ 'n': 1 }, { 'n': 2 }];

_.maxBy(objects, function(o) { return o.n; });
// => { 'n': 2 }

// The `_.property` iteratee shorthand.
_.maxBy(objects, 'n');
// => { 'n': 2 }
```

### mean

#### `_.mean(array)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L16328) | [npm package](https://www.npmjs.com/package/lodash.mean)

Вычисляет среднее значение значений в массиве.

#### С версии

4.0.0

#### Аргументы

1. `array` `(Array)`: Массив, по которому необходимо выполнить итерацию.

#### Возвращает

(number): Возвращает среднее значение.

#### Пример

```javascript
_.mean([4, 2, 8, 6]);
// => 5
```

### meanBy

#### `_.meanBy(array, [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L16355) | [npm package](https://www.npmjs.com/package/lodash.meanby)

Этот метод похож на [`_.mean`](#mean), за исключением того, что он принимает `iteratee`, который вызывается для каждого элемента в `array` для генерации усредняемого значения. Итератор вызывается с одним аргументом: (значение).

#### С версии

4.7.0

#### Аргументы

1. `array` `(Array)`: Массив, по которому необходимо выполнить итерацию.
2. `[iteratee=_.identity]` (Function): Итератор, вызываемый для каждого элемента.

#### Возвращает

(number): Возвращает среднее значение.

#### Пример

```javascript
var objects = [{ 'n': 4 }, { 'n': 2 }, { 'n': 8 }, { 'n': 6 }];

_.meanBy(objects, function(o) { return o.n; });
// => 5

// The `_.property` iteratee shorthand.
_.meanBy(objects, 'n');
// => 5
```

### min

#### `_.min(array)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L16377) | [npm package](https://www.npmjs.com/package/lodash.min)

Вычисляет минимальное значение массива. Если массив пуст или имеет ложное значение, возвращается неопределенное значение.

#### С версии

0.1.0

#### Аргументы

1. `array` `(Array)`: Массив, по которому необходимо выполнить итерацию.

#### Возвращает

(*): Возвращает минимальное значение.

#### Пример

```javascript
_.min([4, 2, 8, 6]);
// => 2

_.min([]);
// => undefined
```

### minBy

#### `_.minBy(array, [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L16406) | [npm package](https://www.npmjs.com/package/lodash.minby)

Этот метод похож на [`_.min`](#min), за исключением того, что он принимает `iteratee`, который вызывается для каждого элемента в `array` для генерации критерия, по которому ранжируется значение. Итератор вызывается с одним аргументом: (значение).

#### С версии

4.0.0

#### Аргументы

1. `array` `(Array)`: Массив, по которому необходимо выполнить итерацию.
2. `[iteratee=_.identity]` (Function): Итератор, вызываемый для каждого элемента.

#### Возвращает

(*): Возвращает минимальное значение.

#### Пример

```javascript
var objects = [{ 'n': 1 }, { 'n': 2 }];

_.minBy(objects, function(o) { return o.n; });
// => { 'n': 1 }

// The `_.property` iteratee shorthand.
_.minBy(objects, 'n');
// => { 'n': 1 }
```

### multiply

#### `_.multiply(multiplier, multiplicand)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L16427) | [npm package](https://www.npmjs.com/package/lodash.multiply)

Умножает два числа.

#### С версии

4.7.0

#### Аргументы

1. `multiplier` (number): Первый множитель.
2. `multiplicand` (number): Второй множитель.

#### Возвращает

(number): Возвращает произведение.

#### Пример

```javascript
_.multiply(6, 4);
// => 24
```

### round

#### `_.round(number, [precision=0])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L16452) | [npm package](https://www.npmjs.com/package/lodash.round)

Вычисляет `number`, округленное до точности `precision`.

#### С версии

3.10.0

#### Аргументы

1. `number` (number): Число для округления.
2. `[precision=0]` (number): Точность округления.

#### Возвращает

(number): Возвращает округленное число.

#### Пример

```javascript
_.round(4.006);
// => 4

_.round(4.006, 2);
// => 4.01

_.round(4060, -2);
// => 4100
```

### subtract

#### `_.subtract(minuend, subtrahend)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L16469) | [npm package](https://www.npmjs.com/package/lodash.subtract)

Вычитает `subtrahend` из `minuend`.

#### С версии

4.0.0

#### Аргументы

1. `minuend` (number): Уменьшаемое.
2. `subtrahend` (number): Вычитаемое.

#### Возвращает

(number): Разность.

#### Пример

```javascript
_.subtract(6, 4);

// => 2
```

### sum

#### `_.sum(array)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L16487) | [npm package](https://www.npmjs.com/package/lodash.sum)

Вычисляет сумму значений в массиве.

#### С версии

3.4.0

#### Аргументы

1. `array` `(Array)`: Массив, по которому необходимо выполнить итерацию.

#### Возвращает

(number): Возвращает сумму.

#### Пример

```javascript
_.sum([4, 2, 8, 6]);
// => 20
```

### sumBy

#### `_.sumBy(array, [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L16516) | [npm package](https://www.npmjs.com/package/lodash.sumby)

Этот метод похож на [`_.sum`](#sum), за исключением того, что он принимает `iteratee`, который вызывается для каждого элемента в `array` для генерации суммируемого значения. Итератор вызывается с одним аргументом: (значение).

#### С версии

4.0.0

#### Аргументы

1. `array` `(Array)`: Массив, по которому необходимо выполнить итерацию.
2. `[iteratee=_.identity]` (Function): Итератор, вызываемый для каждого элемента.

#### Возвращает

(number): Возвращает сумму.

#### Пример

```javascript
var objects = [{ 'n': 4 }, { 'n': 2 }, { 'n': 8 }, { 'n': 6 }];

_.sumBy(objects, function(o) { return o.n; });
// => 20

// The `_.property` iteratee shorthand.
_.sumBy(objects, 'n');
// => 20
```

## Number

### clamp

#### `_.clamp(number, [lower], upper)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13981) | [npm package](https://www.npmjs.com/package/lodash.clamp)

Сжимает `number` по границам диапазона `lower` - `upper`.

#### С версии

4.0.0

#### Аргументы

1. `number` (number): Число для обрезки.
2. `[lower]` (number): Нижняя граница.
3. `upper` (number): Верхняя граница.

#### Возвращает

(number): Возвращает зафиксированное число.

#### Пример

```javascript
_.clamp(-10, -5, 5);
// => -5

_.clamp(10, -5, 5);
// => 5
```

### inRange

#### `_.inRange(number, [start=0], end)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14035) | [npm package](https://www.npmjs.com/package/lodash.inrange)

Проверяет, находится ли `n` между `start` и `end`, но не включая `end`. Если `end` не указан, для него устанавливается значение `start`, а `start`, а затем `0`. Если `start` больше `end`, параметры меняются местами для поддержки отрицательных диапазонов.

#### С версии

3.3.0

#### Аргументы

1. `number` (number): The number to check.
2. `[start=0]` (number): Начало диапазона.
3. `end` (number): Конец диапазона.

#### Возвращает

(boolean): Возвращает `true`, если число находится в диапазоне, иначе — `false`.

#### Пример

```javascript
_.inRange(3, 2, 4);
// => true

_.inRange(4, 8);
// => true

_.inRange(4, 2);
// => false

_.inRange(2, 2);
// => false

_.inRange(1.2, 2);
// => true

_.inRange(5.2, 4);
// => false

_.inRange(-3, -2, -6);
// => true
```

### random

#### `_.random([lower=0], [upper=1], [floating])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14078) | [npm package](https://www.npmjs.com/package/lodash.random)

Создает случайное число между включенной `lower` и `upper` границами. Если указан только один аргумент, возвращается число от «0» до заданного числа. Если значение `floating` равно `true` или либо `lower`, либо `upper` являются числами с плавающей запятой, вместо целого числа возвращается число с плавающей запятой.

**Note:** JavaScript соответствует стандарту IEEE-754 для разрешения значений с плавающей запятой, что может привести к неожиданным результатам.

#### С версии

0.7.0

#### Аргументы

1. `[lower=0]` (number): Нижняя граница.
2. `[upper=1]` (number): Верхняя граница.
3. `[floating]` (boolean): Флаг числа с плавающей запятой.

#### Возвращает

(number): Возвращает случайное число.

#### Пример

```javascript
_.random(0, 5);
// => an integer between 0 and 5

_.random(5);
// => also an integer between 0 and 5

_.random(5, true);
// => a floating-point number between 0 and 5

_.random(1.2, 5.2);
// => a floating-point number between 1.2 and 5.2
```

## Object

### assign

#### `_.assign(object, [sources])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12595) | [npm package](https://www.npmjs.com/package/lodash.assign)

Назначает целевому объекту собственные перечислимые строковые свойства исходных объектов. Исходные объекты применяются слева направо. Последующие источники перезаписывают назначения свойств предыдущих источников.

**Note:** Этот метод изменяет `object` и во многом основан на [`Object.assign`](https://mdn.io/Object/assign).

#### С версии

0.10.0

#### Аргументы

1. `object` (Object): Целевой объект.
2. `[sources]` (...Object): Исходные объекты.

#### Возвращает

(Object): `object`.

#### Пример

```javascript
function Foo() {
  this.a = 1;
}

function Bar() {
  this.c = 3;
}

Foo.prototype.b = 2;
Bar.prototype.d = 4;

_.assign({ 'a': 0 }, new Foo, new Bar);
// => { 'a': 1, 'c': 3 }
```

### assignIn

#### `_.assignIn(object, [sources])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12638) | [npm package](https://www.npmjs.com/package/lodash.assignin)

Этот метод похож на [`_.assign`](#assign), за исключением того, что он перебирает собственные и унаследованные исходные свойства.

**Note:** Этот метод мутирует `object`.

#### С версии

4.0.0

#### Псевдонимы

__.extend_

#### Аргументы

1. `object` (Object): Целевой объект.
2. `[sources]` (...Object): Исходные объекты.

#### Возвращает

(Object): `object`.

#### Пример

```javascript
function Foo() {
  this.a = 1;
}

function Bar() {
  this.c = 3;
}

Foo.prototype.b = 2;
Bar.prototype.d = 4;

_.assignIn({ 'a': 0 }, new Foo, new Bar);
// => { 'a': 1, 'b': 2, 'c': 3, 'd': 4 }
```

### assignInWith

#### `_.assignInWith(object, sources, [customizer])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12671) | [npm package](https://www.npmjs.com/package/lodash.assigninwith)

Этот метод похож на [`_.assignIn`](#assignIn), за исключением того, что он принимает `customizer`, который вызывается для получения назначенных значений. Если `customizer` возвращает `undefined`, вместо этого назначение обрабатывается методом. «Настройщик» вызывается с пятью аргументами: (objValue, srcValue, key, object, source).

**Note:** Этот метод мутирует `object`.

#### С версии

4.0.0

#### Псевдонимы

__.extendWith_

#### Аргументы

1. `object` (Object): Целевой объект.
2. `sources` (...Object): Исходные объекты.
3. `[customizer]` (Function): Функция настройки присвоенных значений.

#### Возвращает

(Object): `object`.

#### Пример

```javascript
function customizer(objValue, srcValue) {
  return _.isUndefined(objValue) ? srcValue : objValue;
}

var defaults = _.partialRight(_.assignInWith, customizer);

defaults({ 'a': 1 }, { 'b': 2 }, { 'a': 3 });
// => { 'a': 1, 'b': 2 }
```

### assignWith

#### `_.assignWith(object, sources, [customizer])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12703) | [npm package](https://www.npmjs.com/package/lodash.assignwith)

Этот метод похож на [`_.assign`](#assign), за исключением того, что он принимает `customizer`, который вызывается для получения назначенных значений. Если `customizer` возвращает `undefined`, вместо этого назначение обрабатывается методом. «Настройщик» вызывается с пятью аргументами: (objValue, srcValue, key, object, source).

**Note:** Этот метод мутирует `object`.

#### С версии

4.0.0

#### Аргументы

1. `object` (Object): Целевой объект.
2. `sources` (...Object): Исходные объекты.
3. `[customizer]` (Function): Функция для настройки назначенных значений.

#### Возвращает

(Object): `object`.

#### Пример

```javascript
function customizer(objValue, srcValue) {
  return _.isUndefined(objValue) ? srcValue : objValue;
}

var defaults = _.partialRight(_.assignWith, customizer);

defaults({ 'a': 1 }, { 'b': 2 }, { 'a': 3 });
// => { 'a': 1, 'b': 2 }
```

### at

#### `_.at(object, [paths])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12724) | [npm package](https://www.npmjs.com/package/lodash.at)

Создает массив значений, соответствующих путям объекта.

#### С версии

1.0.0

#### Аргументы

1. `object` (Object): Объект для итерации.
2. `[paths]` (...(string|string[])): Пути к свойствам для выбора.

#### Возвращает

`(Array)`: Возвращает выбранные значения.

#### Пример

```javascript
var object = { 'a': [{ 'b': { 'c': 3 } }, 4] };

_.at(object, ['a[0].b.c', 'a[1]']);
// => [3, 4]
```

### create

#### `_.create(prototype, [properties])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12760) | [npm package](https://www.npmjs.com/package/lodash.create)

Создает объект, который наследуется от объекта `prototype`. Если задан объект `properties`, созданному объекту присваиваются его собственные перечислимые свойства с строковыми ключами.

#### С версии

2.3.0

#### Аргументы

1. `prototype` (Object): Объект для наследования.
2. `[properties]` (Object): Свойства, которые нужно присвоить объекту.

#### Возвращает

(Object): Возвращает новый объект.

#### Пример

```javascript
function Shape() {
  this.x = 0;
  this.y = 0;
}

function Circle() {
  Shape.call(this);
}

Circle.prototype = _.create(Shape.prototype, {
  'constructor': Circle
});

var circle = new Circle;

circle instanceof Circle;
// => true

circle instanceof Shape;
// => true
```

### defaults

#### `_.defaults(object, [sources])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12786) | [npm package](https://www.npmjs.com/package/lodash.defaults)

Назначает собственные и унаследованные свойства исходных объектов с перечисляемыми строковыми ключами целевому объекту для всех целевых свойств, которые разрешаются как `undefined`. Исходные объекты применяются слева направо. После установки свойства дополнительные значения того же свойства игнорируются.

**Note:** Этот метод мутирует `object`.

#### С версии

0.1.0

#### Аргументы

1. `object` (Object): Целевой объект.
2. `[sources]` (...Object): Исходные объекты.

#### Возвращает

(Object): Возвращает `object`.

#### Пример

```javascript
_.defaults({ 'a': 1 }, { 'b': 2 }, { 'a': 3 });
// => { 'a': 1, 'b': 2 }
```

### defaultsDeep

#### `_.defaultsDeep(object, [sources])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12836) | [npm package](https://www.npmjs.com/package/lodash.defaultsdeep)

Этот метод похож на [`_.defaults`](#defaults), за исключением того, что он рекурсивно присваивает свойства по умолчанию.

**Note:** Этот метод мутирует `object`.

#### С версии

3.10.0

#### Аргументы

1. `object` (Object): Целевой объект.
2. `[sources]` (...Object): Исходные объекты.

#### Возвращает

(Object): Возвращает `object`.

#### Пример

```javascript
_.defaultsDeep({ 'a': { 'b': 2 } }, { 'a': { 'b': 1, 'c': 3 } });
// => { 'a': { 'b': 2, 'c': 3 } }
```

### findKey

#### `_.findKey(object, [predicate=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12876) | [npm package](https://www.npmjs.com/package/lodash.findkey)

Этот метод похож на [`_.find`](#find), за исключением того, что он возвращает ключ первого элемента. `predicate` возвращает truey for вместо самого элемента.

#### С версии

1.1.0

#### Аргументы

1. `object` (Object): Объект проверки.
2. `[predicate=_.identity]` (Function): Функция, вызываемая каждую итерацию.

#### Возвращает

(*): Возвращает ключ соответствующего элемента, иначе — `undefined`.

#### Пример

```javascript
var users = {
  'barney':  { 'age': 36, 'active': true },
  'fred':    { 'age': 40, 'active': false },
  'pebbles': { 'age': 1,  'active': true }
};

_.findKey(users, function(o) { return o.age < 40; });
// => 'barney' (iteration order is not guaranteed)

// The `_.matches` iteratee shorthand.
_.findKey(users, { 'age': 1, 'active': true });
// => 'pebbles'

// The `_.matchesProperty` iteratee shorthand.
_.findKey(users, ['active', false]);
// => 'fred'

// The `_.property` iteratee shorthand.
_.findKey(users, 'active');
// => 'barney'
```

### findLastKey

#### `_.findLastKey(object, [predicate=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12915) | [npm package](https://www.npmjs.com/package/lodash.findlastkey)

Этот метод похож на [`_.findKey`](#findKey), за исключением того, что он перебирает элементы коллекции в обратном порядке.

#### С версии

2.0.0

#### Аргументы

1. `object` (Object): Объект проверки.
2. `[predicate=_.identity]` (Function): Функция, вызываемая каждую итерацию.

#### Возвращает

(*): Возвращает ключ соответствующего элемента, иначе — `undefined`.

#### Пример

```javascript
var users = {
  'barney':  { 'age': 36, 'active': true },
  'fred':    { 'age': 40, 'active': false },
  'pebbles': { 'age': 1,  'active': true }
};

_.findLastKey(users, function(o) { return o.age < 40; });
// => returns 'pebbles' assuming `_.findKey` returns 'barney'

// The `_.matches` iteratee shorthand.
_.findLastKey(users, { 'age': 36, 'active': true });
// => 'barney'

// The `_.matchesProperty` iteratee shorthand.
_.findLastKey(users, ['active', false]);
// => 'fred'

// The `_.property` iteratee shorthand.
_.findLastKey(users, 'active');
// => 'pebbles'
```

### forIn

#### `_.forIn(object, [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12947) | [npm package](https://www.npmjs.com/package/lodash.forin)

Выполняет итерацию по собственным и унаследованным перечисляемым строковым свойствам объекта и вызывает `iteratee` для каждого свойства. Итератор вызывается с тремя аргументами: (значение, ключ, объект). Итерированные функции могут завершить итерацию раньше, явно вернув `false`.

#### С версии

0.3.0

#### Аргументы

1. `object` (Object): Объект для итерации.
2. `[iteratee=_.identity]` (Function): Функция, вызываемая каждую итерацию.

#### Возвращает

(Object): Возвращает `object`.

#### Пример

```javascript
function Foo() {
  this.a = 1;
  this.b = 2;
}

Foo.prototype.c = 3;

_.forIn(new Foo, function(value, key) {
  console.log(key);
});
// => Logs 'a', 'b', then 'c' (iteration order is not guaranteed).
```

### forInRight

#### `_.forInRight(object, [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L12979) | [npm package](https://www.npmjs.com/package/lodash.forinright)

Этот метод похож на [`_.forIn`](#forIn), за исключением того, что он перебирает свойства `object` в обратном порядке.

#### С версии

2.0.0

#### Аргументы

1. `object` (Object): Объект для итерации.
2. `[iteratee=_.identity]` (Function): Функция, вызываемая каждую итерацию.

#### Возвращает

(Object): Возвращает `object`.

#### Пример

```javascript
function Foo() {
  this.a = 1;
  this.b = 2;
}

Foo.prototype.c = 3;

_.forInRight(new Foo, function(value, key) {
  console.log(key);
});
// => Logs 'c', 'b', then 'a' assuming `_.forIn` logs 'a', 'b', then 'c'.
```

### forOwn

#### `_.forOwn(object, [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13013) | [npm package](https://www.npmjs.com/package/lodash.forown)

Перебирает собственные перечисляемые свойства объекта со строковыми ключами и вызывает `iteratee` для каждого свойства. Итератор вызывается с тремя аргументами: (значение, ключ, объект). Итерированные функции могут завершить итерацию раньше, явно вернув `false`.

#### С версии

0.3.0

#### Аргументы

1. `object` (Object): Объект для итерации.
2. `[iteratee=_.identity]` (Function): Функция, вызываемая каждую итерацию.

#### Возвращает

(Object): Возвращает `object`.

#### Пример

```javascript
function Foo() {
  this.a = 1;
  this.b = 2;
}

Foo.prototype.c = 3;

_.forOwn(new Foo, function(value, key) {
  console.log(key);
});
// => Logs 'a' then 'b' (iteration order is not guaranteed).
```

### forOwnRight

#### `_.forOwnRight(object, [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13043) | [npm package](https://www.npmjs.com/package/lodash.forownright)

Этот метод похож на [`_.forOwn`](#forOwn), за исключением того, что он перебирает свойства `object` в обратном порядке.

#### С версии

2.0.0

#### Аргументы

1. `object` (Object): Объект для итерации.
2. `[iteratee=_.identity]` (Function): Функция, вызываемая каждую итерацию.

#### Возвращает

(Object): Возвращает `object`.

#### Пример

```javascript
function Foo() {
  this.a = 1;
  this.b = 2;
}

Foo.prototype.c = 3;

_.forOwnRight(new Foo, function(value, key) {
  console.log(key);
});
// => Logs 'b' then 'a' assuming `_.forOwn` logs 'a' then 'b'.
```

### functions

#### `_.functions(object)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13070) | [npm package](https://www.npmjs.com/package/lodash.functions)

Создает массив имен свойств функций на основе собственных перечислимых свойств объекта.

#### С версии

0.1.0

#### Аргументы

1. `object` (Object): Объект проверки.

#### Возвращает

`(Array)`: Возвращает имена функций.

#### Пример

```javascript
function Foo() {
  this.a = _.constant('a');
  this.b = _.constant('b');
}

Foo.prototype.c = _.constant('c');

_.functions(new Foo);
// => ['a', 'b']
```

### functionsIn

#### `_.functionsIn(object)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13097) | [npm package](https://www.npmjs.com/package/lodash.functionsin)

Создает массив имен свойств функций на основе собственных и унаследованных перечислимых свойств объекта.

#### С версии

4.0.0

#### Аргументы

1. `object` (Object): Объект проверки.

#### Возвращает

`(Array)`: Возвращает имена функций.

#### Пример

```javascript
function Foo() {
  this.a = _.constant('a');
  this.b = _.constant('b');
}

Foo.prototype.c = _.constant('c');

_.functionsIn(new Foo);
// => ['a', 'b', 'c']
```

### get

#### `_.get(object, path, [defaultValue])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13126) | [npm package](https://www.npmjs.com/package/lodash.get)

Получает значение узла объекта по указанному пути. Если разрешенное значение не определено, вместо него возвращается значение по умолчанию.

#### С версии

3.7.0

#### Аргументы

1. `object` (Object): Объект для запроса.
2. `path` (Array|string): Путь к получению свойства.
3. `[defaultValue]` (*): Значение, возвращаемое для разрешенных значений `undefined`.

#### Возвращает

(*): Возвращает решенное значение.

#### Пример

```javascript
var object = { 'a': [{ 'b': { 'c': 3 } }] };

_.get(object, 'a[0].b.c');
// => 3

_.get(object, ['a', '0', 'b', 'c']);
// => 3

_.get(object, 'a.b.c', 'default');
// => 'default'
```

### has

#### `_.has(object, path)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13158) | [npm package](https://www.npmjs.com/package/lodash.has)

Проверяет, является ли путь прямым свойством объекта.

#### С версии

0.1.0

#### Аргументы

1. `object` (Object): Объект для запроса.
2. `path` (Array|string): Путь для проверки.

#### Возвращает

(boolean): Возвращает `true`, если путь существует, иначе — `false`.

#### Пример

```javascript
var object = { 'a': { 'b': 2 } };
var other = _.create({ 'a':_.create({ 'b': 2 }) });

_.has(object, 'a');
// => true

_.has(object, 'a.b');
// => true

_.has(object, ['a', 'b']);
// => true

_.has(other, 'a');
// => false
```

### hasIn

#### `_.hasIn(object, path)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13188) | [npm package](https://www.npmjs.com/package/lodash.hasin)

Проверяет, является ли путь прямым или унаследованным свойством объекта.

#### С версии

4.0.0

#### Аргументы

1. `object` (Object): Объект для запроса.
2. `path` (Array|string): Путь для проверки.

#### Возвращает

(boolean): Возвращает `true`, если путь существует, иначе — `false`.

#### Пример

```javascript
var object = _.create({ 'a':_.create({ 'b': 2 }) });

_.hasIn(object, 'a');
// => true

_.hasIn(object, 'a.b');
// => true

_.hasIn(object, ['a', 'b']);
// => true

_.hasIn(object, 'b');
// => false
```

### invert

#### `_.invert(object)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13210) | [npm package](https://www.npmjs.com/package/lodash.invert)

Создает объект, состоящий из инвертированных ключей и значений объекта. Если объект содержит повторяющиеся значения, последующие значения перезаписывают назначения свойств предыдущих значений.

#### С версии

0.7.0

#### Аргументы

1. `object` (Object): Объект для инвертирования.

#### Возвращает

(Object): Возвращает новый инвертированный объект.

#### Пример

```javascript
var object = { 'a': 1, 'b': 2, 'c': 1 };

_.invert(object);
// => { '1': 'c', '2': 'b' }
```

### invertBy

#### `_.invertBy(object, [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13245) | [npm package](https://www.npmjs.com/package/lodash.invertby)

Этот метод похож на [`_.invert`](#invert), за исключением того, что инвертированный объект генерируется из результатов прохождения каждого элемента `object` через `iteratee`. Соответствующее инвертированное значение каждого инвертированного ключа представляет собой массив ключей, отвечающих за генерацию инвертированного значения. Итератор вызывается с одним аргументом: (значение).

#### С версии

4.1.0

#### Аргументы

1. `object` (Object): Объект для инвертирования.
2. `[iteratee=_.identity]` (Function): Итератор, вызываемый для каждого элемента.

#### Возвращает

(Object): Возвращает новый инвертированный объект.

#### Пример

```javascript
var object = { 'a': 1, 'b': 2, 'c': 1 };

_.invertBy(object);
// => { '1': ['a', 'c'], '2': ['b'] }

_.invertBy(object, function(value) {
  return 'group' + value;
});
// => { 'group1': ['a', 'c'], 'group2': ['b'] }
```

### invoke

#### `_.invoke(object, path, [args])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13276) | [npm package](https://www.npmjs.com/package/lodash.invoke)

Вызывает метод объекта по указанному пути.

#### С версии

4.0.0

#### Аргументы

1. `object` (Object): Объект для запроса.
2. `path` (Array|string): Путь к вызываемому методу.
3. `[args]` (...*): Аргументы для вызова метода.

#### Возвращает

(*): Возвращает результат вызванного метода.

#### Пример

```javascript
var object = { 'a': [{ 'b': { 'c': [1, 2, 3, 4] } }] };

_.invoke(object, 'a[0].b.c.slice', 1, 3);
// => [2, 3]
```

### keys

#### `_.keys(object)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13306) | [npm package](https://www.npmjs.com/package/lodash.keys)

Создает массив собственных перечислимых имен свойств объекта.

**Note:** Необъектные значения приводятся к объектам. Дополнительную информацию см. в [спецификации ES](http://ecma-international.org/ecma-262/7.0/#sec-object.keys).

#### С версии

0.1.0

#### Аргументы

1. `object` (Object): Объект для запроса.

#### Возвращает

`(Array)`: Возвращает массив имен свойств.

#### Пример

```javascript
function Foo() {
  this.a = 1;
  this.b = 2;
}

Foo.prototype.c = 3;

_.keys(new Foo);
// => ['a', 'b'] (iteration order is not guaranteed)

_.keys('hi');
// => ['0', '1']
```

### keysIn

#### `_.keysIn(object)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13333) | [npm package](https://www.npmjs.com/package/lodash.keysin)

Создает массив собственных и унаследованных имен перечислимых свойств объекта.

**Note:** Необъектные значения приводятся к объектам.

#### С версии

3.0.0

#### Аргументы

1. `object` (Object): Объект для запроса.

#### Возвращает

`(Array)`: Возвращает массив имен свойств.

#### Пример

```javascript
function Foo() {
  this.a = 1;
  this.b = 2;
}

Foo.prototype.c = 3;

_.keysIn(new Foo);
// => ['a', 'b', 'c'] (iteration order is not guaranteed)
```

### mapKeys

#### `_.mapKeys(object, [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13358) | [npm package](https://www.npmjs.com/package/lodash.mapkeys)

Противоположность [`_.mapValues`](#mapValues); этот метод создает объект с теми же значениями, что и `object`, и ключами, генерируемыми путем запуска каждого собственного перечисляемого строкового свойства `object` через `iteratee`. Итератор вызывается с тремя аргументами: (значение, ключ, объект).

#### С версии

3.8.0

#### Аргументы

1. `object` (Object): Объект для итерации.
2. `[iteratee=_.identity]` (Function): Функция, вызываемая каждую итерацию.

#### Возвращает

(Object): Возвращает новый сопоставленный объект.

#### Пример

```javascript
_.mapKeys({ 'a': 1, 'b': 2 }, function(value, key) {
  return key + value;
});
// => { 'a1': 1, 'b2': 2 }
```

### mapValues

#### `_.mapValues(object, [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13396) | [npm package](https://www.npmjs.com/package/lodash.mapvalues)

Создает объект с теми же ключами, что и `object`, и значениями, сгенерированными путем запуска каждого собственного перечисляемого строкового свойства `object` через `iteratee`. Итератор вызывается с тремя аргументами:
(значение, ключ, объект).

#### С версии

2.4.0

#### Аргументы

1. `object` (Object): Объект для итерации.
2. `[iteratee=_.identity]` (Function): Функция, вызываемая каждую итерацию.

#### Возвращает

(Object): Возвращает новый сопоставленный объект.

#### Пример

```javascript
var users = {
  'fred':    { 'user': 'fred',    'age': 40 },
  'pebbles': { 'user': 'pebbles', 'age': 1 }
};

_.mapValues(users, function(o) { return o.age; });
// => { 'fred': 40, 'pebbles': 1 } (iteration order is not guaranteed)

// The `_.property` iteratee shorthand.
_.mapValues(users, 'age');
// => { 'fred': 40, 'pebbles': 1 } (iteration order is not guaranteed)
```

### merge

#### `_.merge(object, [sources])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13437) | [npm package](https://www.npmjs.com/package/lodash.merge)

Этот метод подобен [`_.assign`](#assign), за исключением того, что он рекурсивно объединяет собственные и унаследованные перечислимые строковые свойства исходных объектов с целевым объектом. Исходные свойства, которые разрешаются как «неопределенные», пропускаются, если существует целевое значение. Свойства массива и простого объекта рекурсивно объединяются. Другие объекты и типы значений переопределяются присвоением. Исходные объекты применяются слева направо. Последующие источники перезаписывают назначения свойств предыдущих источников.

**Note:** Этот метод мутирует `object`.

#### С версии

0.5.0

#### Аргументы

1. `object` (Object): Целевой объект.
2. `[sources]` (...Object): Исходные объекты.

#### Возвращает

(Object): Возвращает `object`.

#### Пример

```javascript
var object = {
  'a': [{ 'b': 2 }, { 'd': 4 }]
};

var other = {
  'a': [{ 'c': 3 }, { 'e': 5 }]
};

_.merge(object, other);
// => { 'a': [{ 'b': 2, 'c': 3 }, { 'd': 4, 'e': 5 }] }
```

### mergeWith

#### `_.mergeWith(object, sources, customizer)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13472) | [npm package](https://www.npmjs.com/package/lodash.mergewith)

Этот метод похож на [`_.merge`](#merge), за исключением того, что он принимает `customizer`, который вызывается для создания объединенных значений свойств назначения и источника. Если «customizer» возвращает «undef», вместо этого слияние обрабатывается методом. «Настройщик» вызывается с шестью аргументами: (objValue, srcValue, ключ, объект, источник, стек).

**Note:** Этот метод мутирует `object`.

#### С версии

4.0.0

#### Аргументы

1. `object` (Object): Целевой объект.
2. `sources` (...Object): Исходные объекты.
3. `customizer` (Function): Функция для настройки назначенных значений.

#### Возвращает

(Object): Возвращает `object`.

#### Пример

```javascript
function customizer(objValue, srcValue) {
  if (_.isArray(objValue)) {
    return objValue.concat(srcValue);
  }
}

var object = { 'a': [1], 'b': [2] };
var other = { 'a': [3], 'b': [4] };

_.mergeWith(object, other, customizer);
// => { 'a': [1, 3], 'b': [2, 4] }
```

### omit

#### `_.omit(object, [paths])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13496) | [npm package](https://www.npmjs.com/package/lodash.omit)

Противоположность [`_.pick`](#pick); этот метод создает объект, состоящий из собственных и унаследованных перечислимых путей к свойствам объекта, которые не опущены.

**Note:** Этот метод значительно медленнее, чем [`_.pick`](#pick).

#### С версии

0.1.0

#### Аргументы

1. `object` (Object): Исходный объект.
2. `[paths]` (...(string|string[])): Пути к свойствам, которые следует опустить.

#### Возвращает

(Object): Возвращает новый объект.

#### Пример

```javascript
var object = { 'a': 1, 'b': '2', 'c': 3 };

_.omit(object, ['a', 'c']);
// => { 'b': '2' }
```

### omitBy

#### `_.omitBy(object, [predicate=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13538) | [npm package](https://www.npmjs.com/package/lodash.omitby)

Противоположность [`_.pickBy`](#pickBy); этот метод создает объект, состоящий из собственных и унаследованных перечислимых строковых свойств объекта `object`, для которого `predicate` не возвращает истинность. Предикат вызывается с двумя аргументами: (значение, ключ).

#### С версии

4.0.0

#### Аргументы

1. `object` (Object): Исходный объект.
2. `[predicate=_.identity]` (Function): Функция, вызываемая для каждого свойства.

#### Возвращает

(Object): Возвращает новый объект.

#### Пример

```javascript
var object = { 'a': 1, 'b': '2', 'c': 3 };

_.omitBy(object,_.isNumber);
// => { 'b': '2' }
```

### pick

#### `_.pick(object, [paths])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13559) | [npm package](https://www.npmjs.com/package/lodash.pick)

Создает объект, состоящий из выбранных свойств объекта.

#### С версии

0.1.0

#### Аргументы

1. `object` (Object): Исходный объект.
2. `[paths]` (...(string|string[])): Пути к свойствам для выбора.

#### Возвращает

(Object): Возвращает новый объект.

#### Пример

```javascript
var object = { 'a': 1, 'b': '2', 'c': 3 };

_.pick(object, ['a', 'c']);
// => { 'a': 1, 'c': 3 }
```

### pickBy

#### `_.pickBy(object, [predicate=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13581) | [npm package](https://www.npmjs.com/package/lodash.pickby)

Создает объект, состоящий из свойств объекта, для которого предикат возвращает истинность. Предикат вызывается с двумя аргументами: (значение, ключ).

#### С версии

4.0.0

#### Аргументы

1. `object` (Object): Исходный объект.
2. `[predicate=_.identity]` (Function): Функция, вызываемая для каждого свойства.

#### Возвращает

(Object): Возвращает новый объект.

#### Пример

```javascript
var object = { 'a': 1, 'b': '2', 'c': 3 };

_.pickBy(object,_.isNumber);
// => { 'a': 1, 'c': 3 }
```

### result

#### `_.result(object, path, [defaultValue])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13623) | [npm package](https://www.npmjs.com/package/lodash.result)

Этот метод похож на [`_.get`](#get), за исключением того, что если разрешенное значение является функцией, она вызывается с привязкой `this` своего родительского объекта и возвращается ее результат.

#### С версии

0.1.0

#### Аргументы

1. `object` (Object): Объект для запроса.
2. `path` (Array|string): Путь к разрешаемому свойству.
3. `[defaultValue]` (*): Значение, возвращаемое для разрешенных значений `undefined`.

#### Возвращает

(*): Возвращает решенное значение.

#### Пример

```javascript
var object = { 'a': [{ 'b': { 'c1': 3, 'c2': _.constant(4) } }] };

_.result(object, 'a[0].b.c1');
// => 3

_.result(object, 'a[0].b.c2');
// => 4

_.result(object, 'a[0].b.c3', 'default');
// => 'default'

_.result(object, 'a[0].b.c3',_.constant('default'));
// => 'default'
```

### set

#### `_.set(object, path, value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13673) | [npm package](https://www.npmjs.com/package/lodash.set)

Устанавливает значение по пути к объекту. Если часть пути не существует, она создается. Массивы создаются для отсутствующих свойств индекса, а объекты создаются для всех остальных отсутствующих свойств. Используйте [`_.setWith`](#setWith) для настройки создания пути.

**Note:** Этот метод мутирует `object`.

#### С версии

3.7.0

#### Аргументы

1. `object` (Object): Объект для изменения.
2. `path` (Array|string): Путь к свойству, которое необходимо установить.
3. `value` (*): Значение, которое необходимо установить.

#### Возвращает

(Object): Возвращает `object`.

#### Пример

```javascript
var object = { 'a': [{ 'b': { 'c': 3 } }] };

_.set(object, 'a[0].b.c', 4);

console.log(object.a[0].b.c);
// => 4

_.set(object, ['x', '0', 'y', 'z'], 5);

console.log(object.x[0].y.z);
// => 5
```

### setWith

#### `_.setWith(object, path, value, [customizer])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13701) | [npm package](https://www.npmjs.com/package/lodash.setwith)

Этот метод похож на [`_.set`](#set), за исключением того, что он принимает `customizer`, который вызывается для создания объектов `path`. Если `customizer` возвращает `unопределённый` путь, вместо этого метод обрабатывает создание пути. «Настройщик» вызывается с тремя аргументами: (nsValue, key, nsObject).

**Note:** Этот метод мутирует `object`.

#### С версии

4.0.0

#### Аргументы

1. `object` (Object): Объект для изменения.
2. `path` (Array|string): Путь к свойству, которое необходимо установить.
3. `value` (*): Значение, которое необходимо установить.
4. `[customizer]` (Function): Функция для настройки назначенных значений.

#### Возвращает

(Object): Возвращает `object`.

#### Пример

```javascript
var object = {};

_.setWith(object, '[0][1]', 'a', Object);
// => { '0': { '1': 'a' } }
```

### toPairs

#### `_.toPairs(object)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13730) | [npm package](https://www.npmjs.com/package/lodash.topairs)

Создает массив собственных перечислимых строковых пар ключ-значение для объекта, который может использоваться [`_.fromPairs`](#fromPairs). Если объект представляет собой карту или набор, возвращаются его записи.

#### С версии

4.0.0

#### Псевдонимы

__.entries_

#### Аргументы

1. `object` (Object): Объект для запроса.

#### Возвращает

`(Array)`: Возвращает пары ключ-значение.

#### Пример

```javascript
function Foo() {
  this.a = 1;
  this.b = 2;
}

Foo.prototype.c = 3;

_.toPairs(new Foo);
// => [['a', 1], ['b', 2]] (iteration order is not guaranteed)
```

### toPairsIn

#### `_.toPairsIn(object)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13756) | [npm package](https://www.npmjs.com/package/lodash.topairsin)

Создает массив собственных и унаследованных пар ключ-значение перечислимых строк для объекта, который может использоваться [`_.fromPairs`](#fromPairs). Если объект представляет собой карту или набор, возвращаются его записи.

#### С версии

4.0.0

#### Псевдонимы

__.entriesIn_

#### Аргументы

1. `object` (Object): Объект для запроса.

#### Возвращает

`(Array)`: Возвращает пары ключ-значение.

#### Пример

```javascript
function Foo() {
  this.a = 1;
  this.b = 2;
}

Foo.prototype.c = 3;

_.toPairsIn(new Foo);
// => [['a', 1], ['b', 2], ['c', 3]] (iteration order is not guaranteed)
```

### transform

#### `_.transform(object, [iteratee=_.identity], [accumulator])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13788) | [npm package](https://www.npmjs.com/package/lodash.transform)


Альтернатива [`_.reduce`](#reduce). Этот метод преобразует `object` в новый объект `accumulator`, который является результатом запуска каждого из его собственных перечислимых свойств с ключом строки через `iteratee`, при этом каждый вызов потенциально изменяет объект `accumulator`. Если `accumulator` не указан, будет использоваться новый объект с тем же `[[Prototype]]`. Итератор вызывается с четырьмя аргументами: (аккумулятор, значение, ключ, объект). Итерированные функции могут завершить итерацию раньше, явно вернув false.

#### С версии

1.3.0

#### Аргументы

1. `object` (Object): Объект для итерации.
2. `[iteratee=_.identity]` (Function): Функция, вызываемая каждую итерацию.
3. `[accumulator]` (*): Пользовательское значение аккумулятора.

#### Возвращает

(*): Возвращает накопленное значение.

#### Пример

```javascript
_.transform([2, 3, 4], function(result, n) {
  result.push(n *= n);
  return n % 2 == 0;
}, []);
// => [4, 9]

_.transform({ 'a': 1, 'b': 2, 'c': 1 }, function(result, value, key) {
  (result[value] || (result[value] = [])).push(key);
}, {});
// => { '1': ['a', 'c'], '2': ['b'] }
```

### unset

#### `_.unset(object, path)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13838) | [npm package](https://www.npmjs.com/package/lodash.unset)

Удаляет свойство объекта по указнному пути.

**Note:** Этот метод мутирует `object`.

#### С версии

4.0.0

#### Аргументы

1. `object` (Object): Объект для изменения.
2. `path` (Array|string): Путь к свойству, которое необходимо отменить.

#### Возвращает

(boolean): Возвращает `true`, если свойство удалено, иначе — `false`.

#### Пример

```javascript
var object = { 'a': [{ 'b': { 'c': 7 } }] };

_.unset(object, 'a[0].b.c');
// => true

console.log(object);
// => { 'a': [{ 'b': {} }] };

_.unset(object, ['a', '0', 'b', 'c']);
// => true

console.log(object);
// => { 'a': [{ 'b': {} }] };
```

### update

#### `_.update(object, path, updater)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13869) | [npm package](https://www.npmjs.com/package/lodash.update)

Этот метод похож на [`_.set`](#set), за исключением того, что он принимает `updater` для создания значения, которое необходимо установить. Используйте [`_.updateWith`](#updateWith), чтобы настроить создание пути. `Updater` вызывается с одним аргументом: (значение).

**Note:** Этот метод мутирует `object`.

#### С версии

4.6.0

#### Аргументы

1. `object` (Object): Объект для изменения.
2. `path` (Array|string): Путь к свойству, которое необходимо установить.
3. `updater` (Function): Функция для создания обновленного значения.

#### Возвращает

(Object): Возвращает `object`.

#### Пример

```javascript
var object = { 'a': [{ 'b': { 'c': 3 } }] };

_.update(object, 'a[0].b.c', function(n) { return n * n; });
console.log(object.a[0].b.c);
// => 9

_.update(object, 'x[0].y.z', function(n) { return n ? n + 1 : 0; });
console.log(object.x[0].y.z);
// => 0
```

### updateWith

#### `_.updateWith(object, path, updater, [customizer])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13897) | [npm package](https://www.npmjs.com/package/lodash.updatewith)

Этот метод похож на [`_.update`](#update), за исключением того, что он принимает `customizer`, который вызывается для создания объектов `path`. Если `customizer` возвращает `undefined` путь, вместо этого метод обрабатывает создание пути. `Customizer` вызывается с тремя аргументами: (nsValue, key, nsObject).

**Note:** Этот метод мутирует `object`.

#### С версии

4.6.0

#### Аргументы

1. `object` (Object): Объект для изменения.
2. `path` (Array|string): Путь к свойству, которое необходимо установить.
3. `updater` (Function): Функция для создания обновленного значения.
4. `[customizer]` (Function): Функция для настройки назначенных значений.

#### Возвращает

(Object): Возвращает `object`.

#### Пример

```javascript
var object = {};

_.updateWith(object, '[0][1]',_.constant('a'), Object);
// => { '0': { '1': 'a' } }
```

### values

#### `_.values(object)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13928) | [npm package](https://www.npmjs.com/package/lodash.values)

Создает массив собственных перечисляемых строковых значений свойств объекта `object`.

**Note:** Необъектные значения приводятся к объектам.

#### С версии

0.1.0

#### Аргументы

1. `object` (Object): Объект для запроса.

#### Возвращает

`(Array)`: Возвращает массив значений свойств.

#### Пример

```javascript
function Foo() {
  this.a = 1;
  this.b = 2;
}

Foo.prototype.c = 3;

_.values(new Foo);
// => [1, 2] (iteration order is not guaranteed)

_.values('hi');
// => ['h', 'i']
```

### valuesIn

#### `_.valuesIn(object)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L13956) | [npm package](https://www.npmjs.com/package/lodash.valuesin)

Создает массив собственных и унаследованных значений свойств объекта с перечисляемыми строковыми ключами.

**Note:** Необъектные значения приводятся к объектам.

#### С версии

3.0.0

#### Аргументы

1. `object` (Object): Объект для запроса.

#### Возвращает

`(Array)`: Возвращает массив значений свойств.

#### Пример

```javascript
function Foo() {
  this.a = 1;
  this.b = 2;
}

Foo.prototype.c = 3;

_.valuesIn(new Foo);
// => [1, 2, 3] (iteration order is not guaranteed)
```

## Seq

### value

### `(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L1648)

Создает объект `lodash`, который обертывает `value` для включения неявных последовательностей цепочек методов. Методы, которые работают с массивами, коллекциями и функциями и возвращают их, можно объединять в цепочку. Методы, которые извлекают одно значение или могут возвращать примитивное значение, автоматически завершают последовательность цепочки и возвращают развернутое значение. В противном случае значение необходимо развернуть с помощью `_#value`.

Явные последовательности цепочек, которые необходимо развернуть с помощью `_#value`, можно включить с помощью [`_.chain`](#chain).
Выполнение связанных методов является ленивым, то есть оно откладывается до тех пор, пока не будет явно или неявно вызвано `_#value`.
Ленивая оценка позволяет использовать несколько методов для поддержки быстрого слияния. Shortcut fusion — это оптимизация для объединения итеративных вызовов; это позволяет избежать создания промежуточных массивов и может значительно сократить количество итеративных выполнений. Разделы цепочки последовательности подходят для быстрого слияния, если раздел применяется к массиву и итерируемые элементы принимают только один аргумент. Эвристика определения того, подходит ли раздел для объединения ярлыков, может быть изменена.
Цепочка поддерживается в пользовательских сборках, если в сборку прямо или косвенно включен метод `_#value`.

Помимо методов `lodash`, оболочки имеют методы `Array` и `String`.

Методы-обертки `Array`:
`concat`, `join`, `pop`, `push`, `shift`, `sort`, `splice` и `unshift`

Методы-обертки `String`:
`replace` и `split`

Методы-обертки, поддерживающие слияние ярлыков:
`at`, `compact`, `drop`, `dropRight`, `dropWhile`, `filter`, `find`, `findLast`, `head`, `initial`, `last`, `map`, `reject`, `reverse`, `slice`, `tail`, `take`, `takeRight`, `takeRightWhile`, `takeWhile` и `toArray`

Цепочечные методы-обертки:
`after`, `ary`, `assign`, `assignIn`, `assignInWith`, `assignWith`, `at`, `before`, `bind`, `bindAll`, `bindKey`, `castArray`, `chain`, `chunk`, `commit`, `compact`, `concat`, `conforms`, `constant`, `countBy`, `create`, `curry`, `debounce`, `defaults`, `defaultsDeep`, `defer`, `delay`, `difference`, `differenceBy`, `differenceWith`, `drop`, `dropRight`, `dropRightWhile`, `dropWhile`, `extend`, `extendWith`, `fill`, `filter`, `flatMap`, `flatMapDeep`, `flatMapDepth`, `flatten`, `flattenDeep`, `flattenDepth`, `flip`, `flow`, `flowRight`, `fromPairs`, `functions`, `functionsIn`, `groupBy`, `initial`, `intersection`, `intersectionBy`, `intersectionWith`, `invert`, `invertBy`, `invokeMap`, `iteratee`, `keyBy`, `keys`, `keysIn`, `map`, `mapKeys`, `mapValues`, `matches`, `matchesProperty`, `memoize`, `merge`, `mergeWith`, `method`, `methodOf`, `mixin`, `negate`, `nthArg`, `omit`, `omitBy`, `once`, `orderBy`, `over`, `overArgs`, `overEvery`, `overSome`, `partial`, `partialRight`, `partition`, `pick`, `pickBy`, `plant`, `property`, `propertyOf`, `pull`, `pullAll`, `pullAllBy`, `pullAllWith`, `pullAt`, `push`, `range`, `rangeRight`, `rearg`, `reject`, `remove`, `rest`, `reverse`, `sampleSize`, `set`, `setWith`, `shuffle`, `slice`, `sort`, `sortBy`, `splice`, `spread`, `tail`, `take`, `takeRight`, `takeRightWhile`, `takeWhile`, `tap`, `throttle`, `thru`, `toArray`, `toPairs`, `toPairsIn`, `toPath`, `toPlainObject`, `transform`, `unary`, `union`, `unionBy`, `unionWith`, `uniq`, `uniqBy`, `uniqWith`, `unset`, `unshift`, `unzip`, `unzipWith`, `update`, `updateWith`, `values`, `valuesIn`, `without`, `wrap`, `xor`, `xorBy`, `xorWith`, `zip`, `zipObject`, `zipObjectDeep` и `zipWith`

Методы-обертки, которые по умолчанию **не** объединяются в цепочки:
`add`, `attempt`, `camelCase`, `capitalize`, `ceil`, `clamp`, `clone`, `cloneDeep`, `cloneDeepWith`, `cloneWith`, `conformsTo`, `deburr`, `defaultTo`, `divide`, `each`, `eachRight`, `endsWith`, `eq`, `escape`, `escapeRegExp`, `every`, `find`, `findIndex`, `findKey`, `findLast`, `findLastIndex`, `findLastKey`, `first`, `floor`, `forEach`, `forEachRight`, `forIn`, `forInRight`, `forOwn`, `forOwnRight`, `get`, `gt`, `gte`, `has`, `hasIn`, `head`, `identity`, `includes`, `indexOf`, `inRange`, `invoke`, `isArguments`, `isArray`, `isArrayBuffer`, `isArrayLike`, `isArrayLikeObject`, `isBoolean`, `isBuffer`, `isDate`, `isElement`, `isEmpty`, `isEqual`, `isEqualWith`, `isError`, `isFinite`, `isFunction`, `isInteger`, `isLength`, `isMap`, `isMatch`, `isMatchWith`, `isNaN`, `isNative`, `isNil`, `isNull`, `isNumber`, `isObject`, `isObjectLike`, `isPlainObject`, `isRegExp`, `isSafeInteger`, `isSet`, `isString`, `isUndefined`, `isTypedArray`, `isWeakMap`, `isWeakSet`, `join`, `kebabCase`, `last`, `lastIndexOf`, `lowerCase`, `lowerFirst`, `lt`, `lte`, `max`, `maxBy`, `mean`, `meanBy`, `min`, `minBy`, `multiply`, `noConflict`, `noop`, `now`, `nth`, `pad`, `padEnd`, `padStart`, `parseInt`, `pop`, `random`, `reduce`, `reduceRight`, `repeat`, `result`, `round`, `runInContext`, `sample`, `shift`, `size`, `snakeCase`, `some`, `sortedIndex`, `sortedIndexBy`, `sortedLastIndex`, `sortedLastIndexBy`, `startCase`, `startsWith`, `stubArray`, `stubFalse`, `stubObject`, `stubString`, `stubTrue`, `subtract`, `sum`, `sumBy`, `template`, `times`, `toFinite`, `toInteger`, `toJSON`, `toLength`, `toLower`, `toNumber`, `toSafeInteger`, `toString`, `toUpper`, `trim`, `trimEnd`, `trimStart`, `truncate`, `unescape`, `uniqueId`, `upperCase`, `upperFirst`, `value` и `words`

#### Аргументы

1. `value` (*): Значение для переноса в экземпляр `lodash`.

#### Возвращает

(Object): Возвращает новый экземпляр оболочки `lodash`.

#### Пример

```javascript
function square(n) {
  return n * n;
}

var wrapped = ([1, 2, 3]);
// Returns an unwrapped value.
wrapped.reduce(_.add);
// => 6

// Returns a wrapped value.
var squares = wrapped.map(square);

_.isArray(squares);
// => false

_.isArray(squares.value());
// => true
```

### chain

#### `_.chain(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8737)

Создает экземпляр оболочки `lodash`, который обертывает `value` с включенными явными последовательностями цепочек методов. Результат таких последовательностей должен быть развернут с помощью `_#value`.

#### С версии

1.3.0

#### Аргументы

1. `value` (*): Значение для переноса.

#### Возвращает

(Object): Возвращает новый экземпляр оболочки `lodash`.

#### Пример

```javascript
var users = [
  { 'user': 'barney',  'age': 36 },
  { 'user': 'fred',    'age': 40 },
  { 'user': 'pebbles', 'age': 1 }
];

var youngest = _
  .chain(users)
  .sortBy('age')
  .map(function(o) {
    return o.user + ' is ' + o.age;
  })
  .head()
  .value();
// => 'pebbles is 1'
```

### tap

#### `_.tap(value, interceptor)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8766)

Этот метод вызывает перехватчик и возвращает значение. Перехватчик вызывается с одним аргументом; (ценить). Целью этого метода является «подключение» к последовательности цепочки методов для изменения промежуточных результатов.

#### С версии

0.1.0

#### Аргументы

1. `value` (*): Значение, которое необходимо предоставить перехватчику.
2. `interceptor` (Function): Функция для вызова.

#### Возвращает

(*): Returns `value`.

#### Пример

```javascript
([1, 2, 3])
 .tap(function`(Array)` {
  // Mutate input array.
  array.pop();
 })
 .reverse()
 .value();
 // => [2, 1]
```

### thru

#### `_.thru(value, interceptor)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8794)

Этот метод похож на [`_.tap`](#tap), за исключением того, что он возвращает результат `перехватчика`. Целью этого метода является «прохождение» значений, заменяющих промежуточные результаты в последовательности цепочки методов.

#### С версии

3.0.0

#### Аргументы

1. `value` (*): Значение, которое необходимо предоставить перехватчику.
2. `interceptor` (Function): Функция для вызова.

#### Возвращает

(*): Возвращает результат перехватчика `interceptor`.

#### Пример

```javascript
('  abc  ')
 .chain()
 .trim()
 .thru(function(value) {
   return [value];
 })
 .value();
 // => ['abc']
```

### prototype

#### `_.prototype[Symbol.iterator]()`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8949)

Позволяет оболочке быть итеративной.

#### С версии

4.0.0

#### Возвращает

(Object): Возвращает объект-оболочку.

#### Пример

```javascript
var wrapped = ([1, 2]);

wrapped[Symbol.iterator]() === wrapped;
// => true

Array.from(wrapped);
// => [1, 2]
```

### prototype-at

#### `_.prototype.at([paths])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8814)

Этот метод является версией-оболочкой [`_.at`](#at).

#### С версии

1.0.0

#### Аргументы

1. `[paths]` (...(string|string[])): Пути к свойствам для выбора.

#### Возвращает

(Object): Возвращает новый экземпляр оболочки lodash.

#### Пример

```javascript
var object = { 'a': [{ 'b': { 'c': 3 } }, 4] };

(object).at(['a[0].b.c', 'a[1]']).value();
// => [3, 4]
```

### prototype-chain

#### `_.prototype.chain()`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8865)

Creates a `lodash` wrapper instance with explicit method chain sequences enabled.

#### С версии

0.1.0

#### Возвращает

(Object): Возвращает новый экземпляр оболочки lodash.

#### Пример

```javascript
var users = [
  { 'user': 'barney', 'age': 36 },
  { 'user': 'fred',   'age': 40 }
];

// A sequence without explicit chaining.
(users).head();
// => { 'user': 'barney', 'age': 36 }

// A sequence with explicit chaining.
(users)
 .chain()
 .head()
 .pick('user')
 .value();
 // => { 'user': 'barney' }
```

### prototype-commit

#### `_.prototype.commit()`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8895)

Выполняет цепную последовательность и возвращает завернутый результат.

#### С версии

3.2.0

#### Возвращает

(Object): Возвращает новый экземпляр оболочки lodash.

#### Пример

```javascript
var array = [1, 2];
var wrapped = `(Array)`.push(3);

console.log`(Array)`;
// => [1, 2]

wrapped = wrapped.commit();
console.log`(Array)`;
// => [1, 2, 3]

wrapped.last();
// => 3
console.log`(Array)`;
// => [1, 2, 3]
```

### prototype-next

#### `_.prototype.next()`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8921)

Получает следующее значение обернутого объекта в соответствии с [протоколом итератора](https://mdn.io/iteration_protocols#iterator).

#### С версии

4.0.0

#### Возвращает

(Object): Возвращает следующее значение итератора.

#### Пример

```javascript
var wrapped = ([1, 2]);

wrapped.next();
// => { 'done': false, 'value': 1 }

wrapped.next();
// => { 'done': false, 'value': 2 }

wrapped.next();
// => { 'done': true, 'value': undefined }
```

### prototype-plant

#### `_.prototype.plant(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L8977)

Создает клон цепной последовательности, помещая `value` в качестве обернутого значения.

#### С версии

3.2.0

#### Аргументы

1. `value` (*): Ценность посадки.

#### Возвращает

(Object): Возвращает новый экземпляр оболочки lodash.

#### Пример

```javascript
function square(n) {
  return n * n;
}

var wrapped = ([1, 2]).map(square);
var other = wrapped.plant([3, 4]);

other.value();
// => [9, 16]

wrapped.value();
// => [1, 4]
```

### prototype-reverse

#### `_.prototype.reverse()`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9017)

Этот метод является оболочкой метода [`_.reverse`](#reverse).

**Note:** Этот метод мутирует обернутый массив.

#### С версии

0.1.0

#### Возвращает

(Object): Возвращает новый экземпляр оболочки `lodash`.

#### Пример

```javascript
var array = [1, 2, 3];

(array).reverse().value()
// => [3, 2, 1]

console.log(array);
// => [3, 2, 1]
```

### prototype-value

#### `_.prototype.value()`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L9049)

Выполняет цепную последовательность для разрешения развернутого значения.

#### С версии

0.1.0

#### Псевдонимы

__.prototype.toJSON, _.prototype.valueOf_

#### Возвращает

(*): Возвращает разрешенное развернутое значение.

#### Пример

```javascript
([1, 2, 3]).value();
// => [1, 2, 3]
```

## String

### camelCase

#### `_.camelCase([string=''])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14139) | [npm package](https://www.npmjs.com/package/lodash.camelcase)

Преобразует `string` в [верблюжий регистр] (https://en.wikipedia.org/wiki/CamelCase).

#### С версии

3.0.0

#### Аргументы

1. `[string='']` (string): Строка для преобразования.

#### Возвращает

(string): Возвращает строку в верблюжьем регистре.

#### Пример

```javascript
_.camelCase('Foo Bar');
// => 'fooBar'

_.camelCase('--foo-bar--');
// => 'fooBar'

_.camelCase('**FOO_BAR**');
// => 'fooBar'
```

### capitalize

#### `_.capitalize([string=''])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14159) | [npm package](https://www.npmjs.com/package/lodash.capitalize)

Преобразует первый символ строки в верхний регистр, а остальные — в нижний.

#### С версии

3.0.0

#### Аргументы

1. `[string='']` (string): Строка для капитализации.

#### Возвращает

(string): Возвращает строку с заглавной буквы.

#### Пример

```javascript
_.capitalize('FRED');
// => 'Fred'
```

### deburr

#### `_.deburr([string=''])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14181) | [npm package](https://www.npmjs.com/package/lodash.deburr)

Удаляет диакритические знаки (ударения, умлауты, галочки и т.п.) `string`, преобразуя [Latin-1 Supplement](https://en.wikipedia.org/wiki/Latin-1_Supplement(Unicode_block)#Character_table) и [Latin Extended-A](https://en.wikipedia. org/wiki/Latin_Extended-A) буквы на основные латинские буквы и удаление [комбинирования диакритических знаков] (https://en.wikipedia.org/wiki/Combining_Diacritical_Marks).

#### С версии

3.0.0

#### Аргументы

1. `[string='']` (string): Строка, которую нужно очистить.

#### Возвращает

(string): Возвращает очищенную строку.

#### Пример

```javascript
_.deburr('déjà vu');
// => 'deja vu'
```

### endsWith

#### `_.endsWith([string=''], [target], [position=string.length])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14209) | [npm package](https://www.npmjs.com/package/lodash.endswith)

Проверяет, заканчивается ли строка заданной целевой строкой.

#### С версии

3.0.0

#### Аргументы

1. `[string='']` (string): Строка для проверки.
2. `[target]` (string): Строка для поиска.
3. `[position=string.length]` (number): Позиция для поиска.

#### Возвращает

(boolean): Возвращает `true`, если строка заканчивается на `target`, иначе — `false`.

#### Пример

```javascript
_.endsWith('abc', 'c');
// => true

_.endsWith('abc', 'b');
// => false

_.endsWith('abc', 'b', 2);
// => true
```

### escape

#### `_.escape([string=''])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14251) | [npm package](https://www.npmjs.com/package/lodash.escape)

Преобразует символы "&", "<", ">", '"' и "'" в строке `string` в соответствующие им escape-последовательности.

**Note:** Никакие другие символы не экранируются. Чтобы экранировать дополнительные символы, используйте стороннюю библиотеку, например [_he_](https://mths.be/he).

Хотя символ «>» экранирован для симметрии, такие символы, как «>» и «/», не нуждаются в экранировании в HTML и не имеют особого значения, если только они не являются частью тега или значения атрибута без кавычек. Дополнительную информацию см. в [статье Матиаса Байненса](https://mathiasbynens.be/notes/ambiguous-ampersands) (в разделе «полусвязанный забавный факт»).

При работе с HTML всегда следует [цитировать значения атрибутов](http://wonko.com/post/html-escaping), чтобы уменьшить количество векторов XSS-атак.

#### С версии

0.1.0

#### Аргументы

1. `[string='']` (string): Строка для экранирования.

#### Возвращает

(string): Возвращает экранированную строку.

#### Пример

```javascript
_.escape('fred, barney, & pebbles');
// => 'fred, barney, &amp; pebbles'
```

### escapeRegExp

#### `_.escapeRegExp([string=''])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14273) | [npm package](https://www.npmjs.com/package/lodash.escaperegexp)

Экранирует специальные символы `RegExp` "^", "$", "", ".", "*", "+", "?", "(", ")", "[", "]", "{", "}" и "|" в `string`.

#### С версии

3.0.0

#### Аргументы

1. `[string='']` (string): Строка для выхода.

#### Возвращает

(string): Возвращает экранированную строку.

#### Пример

```javascript
_.escapeRegExp('[lodash](https://lodash.com/)');
// => '\[lodash\]\(https://lodash\.com/\)'
```

### kebabCase

#### `_.kebabCase([string=''])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14301) | [npm package](https://www.npmjs.com/package/lodash.kebabcase)

Преобразует `string` в [кебаб-кейс] (https://en.wikipedia.org/wiki/Letter_case#Special_case_styles).

#### С версии

3.0.0

#### Аргументы

1. `[string='']` (string): Строка для преобразования.

#### Возвращает

(string): Возвращает строку в кебаб-кейсее.

#### Пример

```javascript
_.kebabCase('Foo Bar');
// => 'foo-bar'

_.kebabCase('fooBar');
// => 'foo-bar'

_.kebabCase('**FOO_BAR**');
// => 'foo-bar'
```

### lowerCase

#### `_.lowerCase([string=''])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14325) | [npm package](https://www.npmjs.com/package/lodash.lowercase)

Преобразует строку, состоящую из слов, разделенных пробелами, в нижний регистр.

#### С версии

4.0.0

#### Аргументы

1. `[string='']` (string): Строка для преобразования.

#### Возвращает

(string): Возвращает строку в нижнем регистре.

#### Пример

```javascript
_.lowerCase('--Foo-Bar--');
// => 'foo bar'

_.lowerCase('fooBar');
// => 'foo bar'

_.lowerCase('**FOO_BAR**');
// => 'foo bar'
```

### lowerFirst

#### `_.lowerFirst([string=''])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14346) | [npm package](https://www.npmjs.com/package/lodash.lowerfirst)

Преобразует первый символ строки в нижний регистр.

#### С версии

4.0.0

#### Аргументы

1. `[string='']` (string): Строка для преобразования.

#### Возвращает

(string): Возвращает преобразованную строку.

#### Пример

```javascript
_.lowerFirst('Fred');
// => 'fred'

_.lowerFirst('FRED');
// => 'fRED'
```

### pad

#### `_.pad([string=''], [length=0], [chars=' '])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14371) | [npm package](https://www.npmjs.com/package/lodash.pad)

Дополняет `string` с левой и правой стороны, если она короче `length`. Символы заполнения усекаются, если их нельзя разделить по `length` поровну.

#### С версии

3.0.0

#### Аргументы

1. `[string='']` (string): Строка для заполнения.
2. `[length=0]` (number): Длина заполнения.
3. `[chars=' ']` (string): Строка, используемая в качестве заполнителя.

#### Возвращает

(string): Возвращает дополненную строку.

#### Пример

```javascript
_.pad('abc', 8);
// => '  abc   '

_.pad('abc', 8, '_-');
// => '_-abc_-_'

_.pad('abc', 3);
// => 'abc'
```

### padEnd

#### `_.padEnd([string=''], [length=0], [chars=' '])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14410) | [npm package](https://www.npmjs.com/package/lodash.padend)

Дополняет `string` с правой стороны, если она короче `length`. Символы заполнения обрезаются, если они превышают `length`.

#### С версии

4.0.0

#### Аргументы

1. `[string='']` (string): Строка для заполнения.
2. `[length=0]` (number): Длина заполнения.
3. `[chars=' ']` (string): Строка, используемая в качестве заполнителя.

#### Возвращает

(string): Возвращает дополненную строку.

#### Пример

```javascript
_.padEnd('abc', 6);
// => 'abc   '

_.padEnd('abc', 6, '_-');
// => 'abc_-_'

_.padEnd('abc', 3);
// => 'abc'
```

### padStart

#### `_.padStart([string=''], [length=0], [chars=' '])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14443) | [npm package](https://www.npmjs.com/package/lodash.padstart)

Дополняет `string` с левой стороны, если она короче `length`. Символы заполнения обрезаются, если они превышают `length`.

#### С версии

4.0.0

#### Аргументы

1. `[string='']` (string): Строка для заполнения.
2. `[length=0]` (number): Длина заполнения.
3. `[chars=' ']` (string): Строка, используемая в качестве заполнителя.

#### Возвращает

(string): Возвращает дополненную строку.

#### Пример

```javascript
_.padStart('abc', 6);
// => '   abc'

_.padStart('abc', 6, '_-');
// => '_-_abc'

_.padStart('abc', 3);
// => 'abc'
```

### parseInt

#### `_.parseInt(string, [radix=10])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14477) | [npm package](https://www.npmjs.com/package/lodash.parseint)

Преобразует `string` в целое число указанного основания. Если система счисления имеет значение «не определено» или `0`, используется система счисления, равная `10`, если только `value` не является шестнадцатеричным, и в этом случае используется система счисления, равная `16`.

**Note:** Этот метод соответствует [реализации ES5](https://es5.github.io/#x15.1.2.2) `parseInt`.

#### С версии

1.1.0

#### Аргументы

1. `string` (string): Строка для преобразования.
2. `[radix=10]` (number): Система счисления, по которой интерпретируется `value`.

#### Возвращает

(number): Возвращает преобразованное целое число.

#### Пример

```javascript
_.parseInt('08');
// => 8

_.map(['6', '08', '10'],_.parseInt);
// => [6, 8, 10]
```

### repeat

#### `_.repeat([string=''], [n=1])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14508) | [npm package](https://www.npmjs.com/package/lodash.repeat)

Повторяет заданную строку `n` раз.

#### С версии

3.0.0

#### Аргументы

1. `[string='']` (string): Строка для повторения.
2. `[n=1]` (number): Количество повторений строки.

#### Возвращает

(string): Возвращает повторяющуюся строку.

#### Пример

```javascript
_.repeat('*', 3);
// => '***'

_.repeat('abc', 2);
// => 'abcabc'

_.repeat('abc', 0);
// => ''
```

### replace

#### `_.replace([string=''], pattern, replacement)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14536) | [npm package](https://www.npmjs.com/package/lodash.replace)

Заменяет совадения с `pattern` в `string` на `replacement`.

**Note:** This method is based on [`String#replace`](https://mdn.io/String/replace).

#### С версии

4.0.0

#### Аргументы

1. `[string='']` (string): Строка, которую нужно изменить.
2. `pattern` (RegExp|string): Шаблон для замены.
3. `replacement` (Function|string): Заменитель.

#### Возвращает

(string): Returns the modified string.

#### Пример

```javascript
_.replace('Hi Fred', 'Fred', 'Barney');
// => 'Hi Barney'
```

### snakeCase

#### `_.snakeCase([string=''])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14564) | [npm package](https://www.npmjs.com/package/lodash.snakecase)

Преобразует `string` в [змеиный регистр (snake_case)](https://en.wikipedia.org/wiki/Snake_case).

#### С версии

3.0.0

#### Аргументы

1. `[string='']` (string): Строка для преобразования.

#### Возвращает

(string): Возвращает строку в змеиным регистре.

#### Пример

```javascript
_.snakeCase('Foo Bar');
// => 'foo_bar'

_.snakeCase('fooBar');
// => 'foo_bar'

_.snakeCase('--FOO-BAR--');
// => 'foo_bar'
```

### split

#### `_.split([string=''], separator, [limit])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14587) | [npm package](https://www.npmjs.com/package/lodash.split)

Разделяет `string` по `separator`.

**Note:** Этот метод основан на [`String#split`](https://mdn.io/String/split).

#### С версии

4.0.0

#### Аргументы

1. `[string='']` (string): Строка, которую нужно разделить.
2. `separator` (RegExp|string): Шаблон разделителя.
3. `[limit]` (number): Длина, до которой необходимо обрезать результаты.

#### Возвращает

`(Array)`: Возвращает сегменты строки.

#### Пример

```javascript
_.split('a-b-c', '-', 2);
// => ['a', 'b']
```

### startCase

#### `_.startCase([string=''])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14629) | [npm package](https://www.npmjs.com/package/lodash.startcase)

Конвертирует `string` в [начальный регистр (start case)](https://en.wikipedia.org/wiki/Letter_case#Stylistic_or_specialised_usage), убирает лишние знаки, разделяет слепленные верблюжьим регистром слова и т.п.

#### С версии

3.1.0

#### Аргументы

1. `[string='']` (string): Строка для преобразования.

#### Возвращает

(string): Возвращает измененную строку.

#### Пример

```javascript
_.startCase('--foo-bar--');
// => 'Foo Bar'

_.startCase('fooBar');
// => 'Foo Bar'

_.startCase('**FOO_BAR**');
// => 'FOO BAR'
```

### startsWith

#### `_.startsWith([string=''], [target], [position=0])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14656) | [npm package](https://www.npmjs.com/package/lodash.startswith)

Проверяет, начинается ли `string` с заданной целевой строки `target`.

#### С версии

3.0.0

#### Аргументы

1. `[string='']` (string): Строка для проверки.
2. `[target]` (string): Строка для поиска.
3. `[position=0]` (number): Позиция для поиска.

#### Возвращает

(boolean): Возвращает `true`, если `string` начинается с `target`, иначе — `false`.

#### Пример

```javascript
_.startsWith('abc', 'a');
// => true

_.startsWith('abc', 'b');
// => false

_.startsWith('abc', 'b', 1);
// => true
```

### template

#### `_.template([string=''], [options={}])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14770) | [npm package](https://www.npmjs.com/package/lodash.template)

Создает скомпилированную функцию шаблона, которая может интерполировать свойства данных в «интерполируемых» разделителях, интерполировать свойства данных HTML-escape в «экранирующих» разделителях и выполнять JavaScript в «оценочных» разделителях. Доступ к свойствам данных можно получить как свободные переменные в шаблоне. Если указан объект настройки, он имеет приоритет над значениями [`_.templateSettings`](#templateSettings).

**Note:** В сборке разработки [`_.template`](#template) использует [sourceURLs](http://www.html5rocks.com/en/tutorials/developertools/sourcemaps/#toc-sourceurl) для упрощения отладки.

Дополнительную информацию о предварительной компиляции шаблонов смотри тут: [lodash's документация по пользовательским сборкам](https://lodash.com/custom-builds).

Дополнительную информацию о песочницах расширений Chrome смотри тут: [Chrome's extensions documentation](https://developer.chrome.com/extensions/sandboxingEval).

#### С версии

0.1.0

#### Аргументы

1. `[string='']` (string): Строка шаблона.
2. `[options={}]` (Object): Объект параметров.
3. `[options.escape=_.templateSettings.escape]` (RegExp): HTML-разделитель «escape».
4. `[options.evaluate=_.templateSettings.evaluate]` (RegExp): Разделитель «evaluate».
5. `[options.imports=_.templateSettings.imports]` (Object): Объект для импорта в шаблон как свободные переменные.
6. `[options.interpolate=_.templateSettings.interpolate]` (RegExp): «Интерполирующий» evaluate.
7. `[options.sourceURL='lodash.templateSources[n]']` (string): SourceURL скомпилированного шаблона.
8. `[options.variable='obj']` (string): Имя переменной объекта данных.

#### Возвращает

(Function): Возвращает скомпилированную функцию шаблона.

#### Пример

```javascript
// Use the "interpolate" delimiter to create a compiled template.
var compiled = _.template('hello <%= user %>!');
compiled({ 'user': 'fred' });
// => 'hello fred!'

// Use the HTML "escape" delimiter to escape data property values.
var compiled = _.template('<b><%- value %></b>');
compiled({ 'value': '<script>' });
// => '<b>&lt;script&gt;</b>'

// Use the "evaluate" delimiter to execute JavaScript and generate HTML.
var compiled = _.template('<%_.forEach(users, function(user) { %><li><%- user %></li><% }); %>');
compiled({ 'users': ['fred', 'barney'] });
// => '<li>fred</li><li>barney</li>'

// Use the internal `print` function in "evaluate" delimiters.
var compiled = _.template('<% print("hello " + user); %>!');
compiled({ 'user': 'barney' });
// => 'hello barney!'

// Use the ES template literal delimiter as an "interpolate" delimiter.
// Disable support by replacing the "interpolate" delimiter.
var compiled = _.template('hello ${ user }!');
compiled({ 'user': 'pebbles' });
// => 'hello pebbles!'

// Use backslashes to treat delimiters as plain text.
var compiled = _.template('<%= "\\\\<%- value %\\\\>" %>');
compiled({ 'value': 'ignored' });
// => '<%- value %>'

// Use the `imports` option to import `jQuery` as `jq`.
var text = '<% jq.each(users, function(user) { %><li><%- user %></li><% }); %>';
var compiled = _.template(text, { 'imports': { 'jq': jQuery } });
compiled({ 'users': ['fred', 'barney'] });
// => '<li>fred</li><li>barney</li>'

// Use the `sourceURL` option to specify a custom sourceURL for the template.
var compiled = _.template('hello <%= user %>!', { 'sourceURL': '/basic/greeting.jst' });
compiled(data);
// => Find the source of "greeting.jst" under the Sources tab or Resources panel of the web inspector.

// Use the `variable` option to ensure a with-statement isn't used in the compiled template.
var compiled = _.template('hi <%= data.user %>!', { 'variable': 'data' });
compiled.source;
// => function(data) {
//   var __t,__p = '';
//   __p += 'hi ' + ((__t = ( data.user )) == null ? '' : __t) + '!';
//   return __p;
// }

// Use custom template delimiters.
_.templateSettings.interpolate = /{{([\\s\\S]+?)}}/g;
var compiled = _.template('hello {{ user }}!');
compiled({ 'user': 'mustache' });
// => 'hello mustache!'

// Use the `source` property to inline compiled templates for meaningful
// line numbers in error messages and stack traces.
fs.writeFileSync(path.join(process.cwd(), 'jst.js'), '\\
  var JST = {\\
    "main": ' + _.template(mainText).source + '\\
  };\\
');
```

### toLower

#### `_.toLower([string=''])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14904) | [npm package](https://www.npmjs.com/package/lodash.tolower)

Преобразует `string` целиком в нижний регистр, как [String#toLowerCase](https://mdn.io/toLowerCase).

#### С версии

4.0.0

#### Аргументы

1. `[string='']` (string): Строка для преобразования.

#### Возвращает

(string): Возвращает строку в нижнем регистре.

#### Пример

```javascript
_.toLower('--Foo-Bar--');
// => '--foo-bar--'

_.toLower('fooBar');
// => 'foobar'

_.toLower('**FOO_BAR**');
// => '**foo_bar**'
```

### toUpper

#### `_.toUpper([string=''])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14929) | [npm package](https://www.npmjs.com/package/lodash.toupper)

Преобразует строку целиком в верхний регистр, как [String#toUpperCase](https://mdn.io/toUpperCase).

#### С версии

4.0.0

#### Аргументы

1. `[string='']` (string): Строка для преобразования.

#### Возвращает

(string): Возвращает строку в верхнем регистре.

#### Пример

```javascript
_.toUpper('--foo-bar--');
// => '--FOO-BAR--'

_.toUpper('fooBar');
// => 'FOOBAR'

_.toUpper('**foo_bar**');
// => '**FOO_BAR**'
```

### trim

#### `_.trim([string=''], [chars=whitespace])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14955) | [npm package](https://www.npmjs.com/package/lodash.trim)

Удаляет начальные и конечные пробелы или указанные символы из `string`.

#### С версии

3.0.0

#### Аргументы

1. `[string='']` (string): Строка, которую нужно обрезать.
2. `[chars=whitespace]` (string): Символы, которые нужно удалить.

#### Возвращает

(string): Возвращает обрезанную строку.

#### Пример

```javascript
_.trim('  abc  ');
// => 'abc'

_.trim('-_-abc-_-', '_-');
// => 'abc'

_.map(['  foo  ', '  bar  '],_.trim);
// => ['foo', 'bar']
```

### trimEnd

#### `_.trimEnd([string=''], [chars=whitespace])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L14990) | [npm package](https://www.npmjs.com/package/lodash.trimend)

Удаляет конечные пробелы или указанные символы из строки.

#### С версии

4.0.0

#### Аргументы

1. `[string='']` (string): Строка, которую нужно обрезать.
2. `[chars=whitespace]` (string): Символы, которые нужно обрезать.

#### Возвращает

(string): Возвращает обрезанную строку.

#### Пример

```javascript
_.trimEnd('  abc  ');
// => '  abc'

_.trimEnd('-_-abc-_-', '_-');
// => '-_-abc'
```

### trimStart

#### `_.trimStart([string=''], [chars=whitespace])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15023) | [npm package](https://www.npmjs.com/package/lodash.trimstart)

Удаляет начальные пробелы или указанные символы из строки.

#### С версии

4.0.0

#### Аргументы

1. `[string='']` (string): Строка, которую нужно обрезать.
2. `[chars=whitespace]` (string): Символы, которые нужно обрезать.

#### Возвращает

(string): Возвращает обрезанную строку.

#### Пример

```javascript
_.trimStart('  abc  ');
// => 'abc  '

_.trimStart('-_-abc-_-', '_-');
// => 'abc-_-'
```

### truncate

#### `_.truncate([string=''], [options={}])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15074) | [npm package](https://www.npmjs.com/package/lodash.truncate)

Усекает строку, если она длиннее заданной максимальной длины строки. Последние символы усеченной строки заменяются строкой пропуска, которая по умолчанию равна «...».

#### С версии

4.0.0

#### Аргументы

1. `[string='']` (string): Строка, которую нужно обрезать.
2. `[options={}]` (Object): Объект параметров.
3. `[options.length=30]` (number): Максимальная длина строки.
4. `[options.omission='...']` (string): Строка, обозначающая текст, опущена.
5. `[options.separator]` (RegExp|string): Шаблон разделителя, до которого требуется усечь.

#### Возвращает

(string): Возвращает усеченную строку.

#### Пример

```javascript
_.truncate('hi-diddly-ho there, neighborino');
// => 'hi-diddly-ho there, neighbo...'

_.truncate('hi-diddly-ho there, neighborino', {
  'length': 24,
  'separator': ' '
});
// => 'hi-diddly-ho there,...'

_.truncate('hi-diddly-ho there, neighborino', {
  'length': 24,
  'separator': /,? +/
});
// => 'hi-diddly-ho there...'

_.truncate('hi-diddly-ho there, neighborino', {
  'omission': ' [...]'
});
// => 'hi-diddly-ho there, neig [...]'
```

### unescape

#### `_.unescape([string=''])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15149) | [npm package](https://www.npmjs.com/package/lodash.unescape)

Обратный вариант [`_.escape`](#escape); этот метод преобразует экранированные символы (escape-последовательности) `&amp;`, `&lt;`, `&gt;`, `&quot;`, и `&#39;` в `string` в соответсвующие символы.

**Note:** Никакие другие escape-последовательностями не являются неэкранированными. Чтобы отменить экранирование дополнительных escape-последовательностей, используйте стороннюю библиотеку, например [_he_](https://mths.be/he).

#### С версии

0.6.0

#### Аргументы

1. `[string='']` (string): Строка для обработки.

#### Возвращает

(string): Возвращает неэкранированную строку.

#### Пример

```javascript
_.unescape('fred, barney, &amp; pebbles');
// => 'fred, barney, & pebbles'
```

### upperCase

#### `_.upperCase([string=''])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15176) | [npm package](https://www.npmjs.com/package/lodash.uppercase)

Преобразует строку, состоящую из слов, разделенных пробелами, в верхний регистр.

#### С версии

4.0.0

#### Аргументы

1. `[string='']` (string): Строка для преобразования.

#### Возвращает

(string): Возвращает строку в верхнем регистре.

#### Пример

```javascript
_.upperCase('--foo-bar');
// => 'FOO BAR'

_.upperCase('fooBar');
// => 'FOO BAR'

_.upperCase('**foo_bar**');
// => 'FOO BAR'
```

### upperFirst

#### `_.upperFirst([string=''])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15197) | [npm package](https://www.npmjs.com/package/lodash.upperfirst)

Преобразует первый символ строки в верхний регистр.

#### С версии

4.0.0

#### Аргументы

1. `[string='']` (string): Строка для преобразования.

#### Возвращает

(string): Возвращает преобразованную строку.

#### Пример

```javascript
_.upperFirst('fred');
// => 'Fred'

_.upperFirst('FRED');
// => 'FRED'
```

### words

#### `_.words([string=''], [pattern])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15218) | [npm package](https://www.npmjs.com/package/lodash.words)

Разбивает строку на массив слов.

#### С версии

3.0.0

#### Аргументы

1. `[string='']` (string): Строка для проверки.
2. `[pattern]` (RegExp|string): Шаблон соответствия.

#### Возвращает

`(Array)`: Returns the words of `string`.

#### Пример

```javascript
_.words('fred, barney, & pebbles');
// => ['fred', 'barney', 'pebbles']

_.words('fred, barney, & pebbles', /[^, ]+/g);
// => ['fred', 'barney', '&', 'pebbles']
```

## Утилиты

### attempt

#### `_.attempt(func, [args])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15252) | [npm package](https://www.npmjs.com/package/lodash.attempt)

Пытается вызвать функцию `func`, возвращая либо результат, либо объект обнаруженной ошибки. Любые дополнительные аргументы передаются функции func при ее вызове.

#### С версии

3.0.0

#### Аргументы

1. `func` (Function): Функция, которую нужно попытаться вызвать.
2. `[args]` (...*): Аргументы для вызова `func`.

#### Возвращает

(*): Возвращает объект результата или ошибки `func`.

#### Пример

```javascript
// Avoid throwing errors for invalid selectors.
var elements = _.attempt(function(selector) {
  return document.querySelectorAll(selector);
}, '>_>');

if (_.isError(elements)) {
  elements = [];
}
```

### bindAll

#### `_.bindAll(object, methodNames)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15286) | [npm package](https://www.npmjs.com/package/lodash.bindall)

Привязывает методы объекта к самому объекту, перезаписывая существующий метод.

**Note:** Этот метод не устанавливает свойство `length` связанных функций.

#### С версии

0.1.0

#### Аргументы

1. `object` (Object): Объект для привязки и назначения связанных методов.
2. `methodNames` (...(string|string[])): Имена методов объекта для привязки.

#### Возвращает

(Object): Возвращает объект.

#### Пример

```javascript
var view = {
  'label': 'docs',
  'click': function() {
    console.log('clicked ' + this.label);
  }
};

_.bindAll(view, ['click']);

jQuery(element).on('click', view.click);
// => Logs 'clicked docs' when clicked.
```

### cond

#### `_.cond(pairs)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15323) | [npm package](https://www.npmjs.com/package/lodash.cond)

Создает функцию, которая перебирает `pairs` и вызывает соответствующую функцию первого предиката, чтобы вернуть истинность. Пары предикат-функция вызываются с помощью привязки `this` и аргументов созданной функции.

#### С версии

4.0.0

#### Аргументы

1. `pairs` `(Array)`: Пары предикат-функция.

#### Возвращает

(Function): Возвращает новую составную функцию.

#### Пример

```javascript
var func = _.cond([
  [_.matches({ 'a': 1 }),           _.constant('matches A')],
  [_.conforms({ 'b': _.isNumber }), _.constant('matches B')],
  [_.stubTrue,                      _.constant('no match')]
]);

func({ 'a': 1, 'b': 2 });
// => 'matches A'

func({ 'a': 0, 'b': 1 });
// => 'matches B'

func({ 'a': '1', 'b': '2' });
// => 'no match'
```

### conforms

#### `_.conforms(source)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15369) | [npm package](https://www.npmjs.com/package/lodash.conforms)

Создает функцию, которая вызывает свойства предиката `source` с соответствующими значениями свойств данного объекта, возвращая `true`, если все предикаты возвращают true, иначе `false`.

**Note:** Созданная функция эквивалентна [`_.conformsTo`](#conformsTo) с частичным применением `source`.

#### С версии

4.0.0

#### Аргументы

1. `source` (Object): Предикаты объекта свойства, которым необходимо соответствовать.

#### Возвращает

(Function): Возвращает новую спецификационную функцию.

#### Пример

```javascript
var objects = [
  { 'a': 2, 'b': 1 },
  { 'a': 1, 'b': 2 }
];

_.filter(objects,_.conforms({ 'b': function(n) { return n > 1; } }));
// => [{ 'a': 1, 'b': 2 }]
```

### constant

#### `_.constant(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15392) | [npm package](https://www.npmjs.com/package/lodash.constant)

Создает функцию, возвращающую `value`.

#### С версии

2.4.0

#### Аргументы

1. `value` (*): Значение, возвращаемое новой функцией.

#### Возвращает

(Function): Возвращает новую константную функцию.

#### Пример

```javascript
var objects = _.times(2,_.constant({ 'a': 1 }));

console.log(objects);
// => [{ 'a': 1 }, { 'a': 1 }]

console.log(objects[0] === objects[1]);
// => true
```

### defaultTo

#### `_.defaultTo(value, defaultValue)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15418) | [npm package](https://www.npmjs.com/package/lodash.defaultto)

Проверяет `value`, чтобы определить, следует ли возвращать вместо него значение по умолчанию. `defaultValue` возвращается, если `value` — `NaN`, `null` или `undefined`.

#### С версии

4.14.0

#### Аргументы

1. `value` (*): Значение для проверки.
2. `defaultValue` (*): Значение по умолчанию.

#### Возвращает

(*): Возвращает решенное значение.

#### Пример

```javascript
_.defaultTo(1, 10);
// => 1

_.defaultTo(undefined, 10);
// => 10
```

### flow

#### `_.flow([funcs])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15444) | [npm package](https://www.npmjs.com/package/lodash.flow)

Создает функцию, которая возвращает результат вызова заданных функций с привязкой `this` созданной функции, где при каждом последующем вызове предоставляется возвращаемое значение предыдущего.

#### С версии

3.0.0

#### Аргументы

1. `[funcs]` (...(Function|Function[])): Функции для вызова.

#### Возвращает

(Function): Возвращает новую составную функцию.

#### Пример

```javascript
function square(n) {
  return n * n;
}

var addSquare = _.flow([_.add, square]);

addSquare(1, 2);
// => 9
```

### flowRight

#### `_.flowRight([funcs])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15467) | [npm package](https://www.npmjs.com/package/lodash.flowright)

Этот метод похож на [`_.flow`](#flow), за исключением того, что он создает функцию, которая вызывает заданные функции справа налево.

#### С версии

3.0.0

#### Аргументы

1. `[funcs]` (...(Function|Function[])): Функции для вызова.

#### Возвращает

(Function): Возвращает новую составную функцию.

#### Пример

```javascript
function square(n) {
  return n * n;
}

var addSquare = _.flowRight([square, _.add]);

addSquare(1, 2);
// => 9
```

### identity

#### `_.identity(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15485) | [npm package](https://www.npmjs.com/package/lodash.identity)

Этот метод возвращает первый полученный аргумент.

#### С версии

0.1.0

#### Аргументы

1. `value` (*): Любая ценность.

#### Возвращает

(*): Возвращает `value`.

#### Пример

```javascript
var object = { 'a': 1 };

console.log(_.identity(object) === object);
// => true
```

### iteratee

#### `_.iteratee([func=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15531) | [npm package](https://www.npmjs.com/package/lodash.iteratee)

Создает функцию, которая вызывает `func` с аргументами созданной функции. Если `func` — это имя свойства, созданная функция возвращает значение свойства для данного элемента. Если `func` — это массив или объект, созданная функция возвращает `true` для элементов, которые содержат эквивалентные исходные свойства, в противном случае она возвращает `false`.

#### С версии

4.0.0

#### Аргументы

1. `[func=_.identity]` (*): Значение, которое нужно преобразовать в коллбэк.

#### Возвращает

(Function): Возвращает коллбэк.

#### Пример

```javascript
var users = [
  { 'user': 'barney', 'age': 36, 'active': true },
  { 'user': 'fred',   'age': 40, 'active': false }
];

// The `_.matches` iteratee shorthand.
_.filter(users,_.iteratee({ 'user': 'barney', 'active': true }));
// => [{ 'user': 'barney', 'age': 36, 'active': true }]

// The `_.matchesProperty` iteratee shorthand.
_.filter(users,_.iteratee(['user', 'fred']));
// => [{ 'user': 'fred', 'age': 40 }]

// The `_.property` iteratee shorthand.
_.map(users,_.iteratee('user'));
// => ['barney', 'fred']

// Create custom iteratee shorthands.
_.iteratee = _.wrap(_.iteratee, function(iteratee, func) {
  return !_.isRegExp(func) ? iteratee(func) : function(string) {
    return func.test(string);
  };
});

_.filter(['abc', 'def'], /ef/);
// => ['def']
```

### matches

#### `_.matches(source)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15563) | [npm package](https://www.npmjs.com/package/lodash.matches)

Создает функцию, которая выполняет частичное глубокое сравнение между заданным объектом и `source`, возвращая `true`, если данный объект имеет эквивалентные значения свойств, в противном случае - `false`.

**Note:** Созданная функция эквивалентна [`_.isMatch`](#isMatch) с частичным применением `source`.

Частичные сравнения будут сопоставлять значения пустого массива и пустого объекта `source` с любым значением массива или объекта соответственно. См. [`_.isEqual`](#isEqual) для списка поддерживаемых сравнений значений.

#### С версии

3.0.0

#### Аргументы

1. `source` (Object): Объект значений свойств, которые необходимо сопоставить.

#### Возвращает

(Function): Возвращает новую спецификационную функцию.

#### Пример

```javascript
var objects = [
  { 'a': 1, 'b': 2, 'c': 3 },
  { 'a': 4, 'b': 5, 'c': 6 }
];

_.filter(objects,_.matches({ 'a': 4, 'c': 6 }));
// => [{ 'a': 4, 'b': 5, 'c': 6 }]
```

### matchesProperty

#### `_.matchesProperty(path, srcValue)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15593) | [npm package](https://www.npmjs.com/package/lodash.matchesproperty)

Создает функцию, которая выполняет частичное глубокое сравнение между значением по пути `path` заданного объекта и `srcValue`, возвращая `true`, если значение объекта эквивалентно, в противном случае — `false`.

**Note:** Частичные сравнения будут сопоставлять значения пустого массива и пустого объекта `srcValue` с любым значением массива или объекта соответственно. См. [`_.isEqual`](#isEqual) для списка поддерживаемых сравнений значений.

#### С версии

3.2.0

#### Аргументы

1. `path` (Array|string): Путь к получению свойства.
2. `srcValue` (*): Соответствующее значение.

#### Возвращает

(Function): Возвращает новую спецификационную функцию.

#### Пример

```javascript
var objects = [
  { 'a': 1, 'b': 2, 'c': 3 },
  { 'a': 4, 'b': 5, 'c': 6 }
];

_.find(objects,_.matchesProperty('a', 4));
// => { 'a': 4, 'b': 5, 'c': 6 }
```

### method

#### `_.method(path, [args])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15621) | [npm package](https://www.npmjs.com/package/lodash.method)

Создает функцию, которая вызывает метод по пути `path` к заданному объекту. Любые дополнительные аргументы передаются вызванному методу.

#### С версии

3.7.0

#### Аргументы

1. `path` (Array|string): Путь к вызываемому методу.
2. `[args]` (...*): Аргументы для вызова метода.

#### Возвращает

(Function): Возвращает новую функцию, вызывающую вызов.

#### Пример

```javascript
var objects = [
  { 'a': { 'b': _.constant(2) } },
  { 'a': { 'b': _.constant(1) } }
];

_.map(objects,_.method('a.b'));
// => [2, 1]

_.map(objects,_.method(['a', 'b']));
// => [2, 1]
```

### methodOf

#### `_.methodOf(object, [args])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15650) | [npm package](https://www.npmjs.com/package/lodash.methodof)

Противоположность [`_.method`](#method); этот метод создает функцию, которая вызывает метод по заданному пути к объекту. Любые дополнительные аргументы передаются вызванному методу.

#### С версии

3.7.0

#### Аргументы

1. `object` (Object): Объект для запроса.
2. `[args]` (...*): Аргументы для вызова метода.

#### Возвращает

(Function): Возвращает новую функцию, вызывающую вызов.

#### Пример

```javascript
var array = _.times(3,_.constant),
    object = { 'a': array, 'b': array, 'c': array };

_.map(['a[2]', 'c[0]'],_.methodOf(object));
// => [2, 0]

_.map([['a', '2'], ['c', '0']],_.methodOf(object));
// => [2, 0]
```

### mixin

#### `_.mixin([object=lodash], source, [options={}])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15692) | [npm package](https://www.npmjs.com/package/lodash.mixin)

Добавляет все собственные перечислимые строковые функциональные свойства исходного объекта в целевой объект. Если объект — это функция, то к ее прототипу также добавляются методы.

**Note:** Используйте [`_.runInContext`](#runInContext) для создания чистой функции `lodash`, чтобы избежать конфликтов, вызванных изменением оригинала.

#### С версии

0.1.0

#### Аргументы

1. `[object=lodash]` (Function|Object): Целевой объект.
2. `source` (Object): Объект добавляемых функций.
3. `[options={}]` (Object): Объект параметров.
4. `[options.chain=true]` (boolean): Укажите, являются ли миксины цепочками.

#### Возвращает

(*): Возвращает `object`.

#### Пример

```javascript
function vowels(string) {
  return _.filter(string, function(v) {
    return /[aeiou]/i.test(v);
  });
}

_.mixin({ 'vowels': vowels });

_.vowels('fred');
// => ['e']

('fred').vowels().value();
// => ['e']

_.mixin({ 'vowels': vowels }, { 'chain': false });

('fred').vowels();
// => ['e']
```

### noConflict

#### `_.noConflict()`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15741) | [npm package](https://www.npmjs.com/package/lodash.noconflict)

Возвращает переменную `_` к ее предыдущему значению и возвращает ссылку на функцию `lodash`.

#### С версии

0.1.0

#### Возвращает

(Function): Возвращает функцию `lodash`.

#### Пример

```javascript
var lodash = _.noConflict();
```

### noop

#### `_.noop()`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15760) | [npm package](https://www.npmjs.com/package/lodash.noop)

Этот метод возвращает `undefined`.

#### С версии

2.3.0

#### Пример

```javascript
_.times(2,_.noop);
// => [undefined, undefined]
```

### nthArg

#### `_.nthArg([n=0])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15784) | [npm package](https://www.npmjs.com/package/lodash.ntharg)

Создает функцию, которая получает аргумент по индексу `n`. Если `n` отрицательно, возвращается n-й аргумент с конца.

#### С версии

4.0.0

#### Аргументы

1. `[n=0]` (number): Индекс возвращаемого аргумента.

#### Возвращает

(Function): Возвращает новую сквозную функцию.

#### Пример

```javascript
var func = _.nthArg(1);

func('a', 'b', 'c', 'd');
// => 'b'

var func = _.nthArg(-2);

func('a', 'b', 'c', 'd');
// => 'c'
```

### over

#### `_.over([iteratees=[_.identity]])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15809) | [npm package](https://www.npmjs.com/package/lodash.over)

Создает функцию, которая вызывает итерации с полученными аргументами и возвращает их результаты.

#### С версии

4.0.0

#### Аргументы

1. `[iteratees=[_.identity]]` (...(Function|Function[])): Итерации для вызова.

#### Возвращает

(Function): Возвращает новую функцию.

#### Пример

```javascript
var func = _.over([Math.max, Math.min]);

func(1, 2, 3, 4);
// => [4, 1]
```

### overEvery

#### `_.overEvery([predicates=[_.identity]])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15835) | [npm package](https://www.npmjs.com/package/lodash.overevery)

Создает функцию, которая проверяет, возвращают ли **все** `predicates` правдивость при вызове с полученными аргументами.

#### С версии

4.0.0

#### Аргументы

1. `[predicates=[_.identity]]` (...(Function|Function[])): Предикаты для проверки.

#### Возвращает

(Function): Возвращает новую функцию.

#### Пример

```javascript
var func = _.overEvery([Boolean, isFinite]);

func('1');
// => true

func(null);
// => false

func(NaN);
// => false
```

### overSome

#### `_.overSome([predicates=[_.identity]])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15861) | [npm package](https://www.npmjs.com/package/lodash.oversome)

Создает функцию, которая проверяет, возвращает ли **любой** из `predicates` правдивость при вызове с полученными аргументами.

#### С версии

4.0.0

#### Аргументы

1. `[predicates=[_.identity]]` (...(Function|Function[])): Предикаты для проверки.

#### Возвращает

(Function): Возвращает новую функцию.

#### Пример

```javascript
var func = _.overSome([Boolean, isFinite]);

func('1');
// => true

func(null);
// => true

func(NaN);
// => false
```

### property

#### `_.property(path)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15885) | [npm package](https://www.npmjs.com/package/lodash.property)

Создает функцию, которая возвращает значение по пути `path` заданного объекта.

#### С версии

2.4.0

#### Аргументы

1. `path` (Array|string): Путь к получению свойства.

#### Возвращает

(Function): Возвращает новую функцию доступа.

#### Пример

```javascript
var objects = [
  { 'a': { 'b': 2 } },
  { 'a': { 'b': 1 } }
];

_.map(objects,_.property('a.b'));
// => [2, 1]

_.map(_.sortBy(objects, _.property(['a', 'b'])), 'a.b');
// => [1, 2]
```

### propertyOf

#### `_.propertyOf(object)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15910) | [npm package](https://www.npmjs.com/package/lodash.propertyof)

Противоположность [`_.property`](#property); этот метод создает функцию, которая возвращает значение по заданному пути к объекту.

#### С версии

3.0.0

#### Аргументы

1. `object` (Object): Объект для запроса.

#### Возвращает

(Function): Возвращает новую функцию доступа.

#### Пример

```javascript
var array = [0, 1, 2],
    object = { 'a': array, 'b': array, 'c': array };

_.map(['a[2]', 'c[0]'],_.propertyOf(object));
// => [2, 0]

_.map([['a', '2'], ['c', '0']],_.propertyOf(object));
// => [2, 0]
```

### range

#### `_.range([start=0], end, [step=1])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15957) | [npm package](https://www.npmjs.com/package/lodash.range)

Создает массив чисел (положительных и/или отрицательных) от `start` до, но не включая `end`. Если указано отрицательное значение `start`, то используется шаг `-1`, если не указан `end` или `step`. Если `end` не указан, то он равен `start`, а затем устанавливается в `0`.

**Note:** JavaScript соответствует стандарту IEEE-754 для разрешения значений с плавающей запятой, что может привести к неожиданным результатам.

#### С версии

0.1.0

#### Аргументы

1. `[start=0]` (number): Начало диапазона.
2. `end` (number): Конец диапазона.
3. `[step=1]` (number): Значение, на которое нужно увеличить или уменьшить.

#### Возвращает

`(Array)`: Возвращает диапазон чисел.

#### Пример

```javascript
_.range(4);
// => [0, 1, 2, 3]

_.range(-4);
// => [0, -1, -2, -3]

_.range(1, 5);
// => [1, 2, 3, 4]

_.range(0, 20, 5);
// => [0, 5, 10, 15]

_.range(0, -4, -1);
// => [0, -1, -2, -3]

_.range(1, 4, 0);
// => [1, 1, 1]

_.range(0);
// => []
```

### rangeRight

#### `_.rangeRight([start=0], end, [step=1])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L15995) | [npm package](https://www.npmjs.com/package/lodash.rangeright)

Этот метод похож на [`_.range`](#range), за исключением того, что он заполняет значения в порядке убывания.

#### С версии

4.0.0

#### Аргументы

1. `[start=0]` (number): Начало диапазона.
2. `end` (number): Конец диапазона.
3. `[step=1]` (number): Значение, на которое нужно увеличить или уменьшить.

#### Возвращает

`(Array)`: Возвращает диапазон чисел.

#### Пример

```javascript
_.rangeRight(4);
// => [3, 2, 1, 0]

_.rangeRight(-4);
// => [-3, -2, -1, 0]

_.rangeRight(1, 5);
// => [4, 3, 2, 1]

_.rangeRight(0, 20, 5);
// => [15, 10, 5, 0]

_.rangeRight(0, -4, -1);
// => [-3, -2, -1, 0]

_.rangeRight(1, 4, 0);
// => [1, 1, 1]

_.rangeRight(0);
// => []
```

### runInContext

#### `_.runInContext([context=root])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L1406) | [npm package](https://www.npmjs.com/package/lodash.runincontext)

Создайте новую нетронутую функцию `lodash`, используя объект `context`.

#### С версии

1.1.0

#### Аргументы

1. `[context=root]` (Object): Объект контекста.

#### Возвращает

(Function): Возвращает новую функцию `lodash`.

#### Пример

```javascript
_.mixin({ 'foo':_.constant('foo') });

var lodash = _.runInContext();

lodash.mixin({ 'bar': lodash.constant('bar') });

_.isFunction(_.foo);
// => true

_.isFunction(_.bar);
// => false

lodash.isFunction(lodash.foo);
// => false

lodash.isFunction(lodash.bar);
// => true

// Create a suped-up `defer` in Node.js.
var defer = _.runInContext({ 'setTimeout': setImmediate }).defer;
```

### stubArray

#### `_.stubArray()`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L16015) | [npm package](https://www.npmjs.com/package/lodash.stubarray)

Этот метод возвращает новый пустой массив.

#### С версии

4.13.0

#### Возвращает

`(Array)`: Возвращает новый пустой массив.

#### Пример

```javascript
var arrays = _.times(2,_.stubArray);

console.log(arrays);
// => [[], []]

console.log(arrays[0] === arrays[1]);
// => false
```

### stubFalse

#### `_.stubFalse()`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L16032) | [npm package](https://www.npmjs.com/package/lodash.stubfalse)

Этот метод возвращает `false`.

#### С версии

4.13.0

#### Возвращает

(boolean): Возвращает `false`.

#### Пример

```javascript
_.times(2,_.stubFalse);
// => [false, false]
```

### stubObject

#### `_.stubObject()`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L16054) | [npm package](https://www.npmjs.com/package/lodash.stubobject)

Этот метод возвращает новый пустой объект.

#### С версии

4.13.0

#### Возвращает

(Object): Возвращает новый пустой объект.

#### Пример

```javascript
var objects = _.times(2,_.stubObject);

console.log(objects);
// => [{}, {}]

console.log(objects[0] === objects[1]);
// => false
```

### stubString

#### `_.stubString()`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L16071) | [npm package](https://www.npmjs.com/package/lodash.stubstring)

Этот метод возвращает пустую строку.

#### С версии

4.13.0

#### Возвращает

(string): Возвращает пустую строку.

#### Пример

```javascript
_.times(2,_.stubString);
// => ['', '']
```

### stubTrue

#### `_.stubTrue()`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L16088) | [npm package](https://www.npmjs.com/package/lodash.stubtrue)

Этот метод возвращает `true`.

#### С версии

4.13.0

#### Возвращает

(boolean): Возвращает `true`.

#### Пример

```javascript
_.times(2,_.stubTrue);
// => [true, true]
```

### times

#### `_.times(n, [iteratee=_.identity])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L16111) | [npm package](https://www.npmjs.com/package/lodash.times)

Вызывает итерируемый элемент `n` раз, возвращая массив результатов каждого вызова. Итерируемый объект вызывается с одним аргументом (индекс).

#### С версии

0.1.0

#### Аргументы

1. `n` (number): Сколько раз вызывать `iteratee`.
2. `[iteratee=_.identity]` (Function): Функция, вызываемая каждую итерацию.

#### Возвращает

`(Array)`: Возвращает массив результатов.

#### Пример

```javascript
_.times(3, String);
// => ['0', '1', '2']

 _.times(4,_.constant(0));
// => [0, 0, 0, 0]
```

### toPath

#### `_.toPath(value)`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L16146) | [npm package](https://www.npmjs.com/package/lodash.topath)

Преобразует `value` в массив путей к свойствам.

#### С версии

4.0.0

#### Аргументы

1. `value` (*): Значение для преобразования.

#### Возвращает

`(Array)`: Возвращает новый массив путей к свойствам.

#### Пример

```javascript
_.toPath('a.b.c');
// => ['a', 'b', 'c']

_.toPath('a[0].b.c');
// => ['a', '0', 'b', 'c']
```

### uniqueId

#### `_.uniqueId([prefix=''])`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L16170) | [npm package](https://www.npmjs.com/package/lodash.uniqueid)

Генерирует уникальный идентификатор. Если указан префикс, к нему добавляется идентификатор.

#### С версии

0.1.0

#### Аргументы

1. `[prefix='']` (string): Значение префикса идентификатора.

#### Возвращает

(string): Возвращает уникальный ID.

#### Пример

```javascript
_.uniqueId('contact_');
// => 'contact_104'

_.uniqueId();
// => '105'
```

## Свойства

### VERSION

#### `_.VERSION`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L16861)

(string): Семантический номер версии.

### templateSettings

#### `_.templateSettings`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L1717) | [npm package](https://www.npmjs.com/package/lodash.templatesettings)

(Object): По умолчанию разделители шаблонов, используемые lodash, аналогичны разделителям встроенного Ruby (ERB), а также строкам шаблонов ES2015. Измените следующие настройки шаблона, чтобы использовать альтернативные разделители.

### templateSettings-escape

#### `_.templateSettings.escape`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L1725)

(RegExp): Используется для обнаружения значений свойств `data`, которые должны быть экранированы HTML.

### templateSettings-evaluate

#### `_.templateSettings.evaluate`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L1733)

(RegExp): Используется для обнаружения кода, подлежащего оценке.

### templateSettings-imports

#### `_.templateSettings.imports`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L1757)

(Object): Используется для импорта переменных в скомпилированный шаблон.

### templateSettings-interpolate

#### `_.templateSettings.interpolate`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L1741)

(RegExp): Используется для определения значений свойств `data` для внедрения.

### templateSettings-variable

#### `_.templateSettings.variable`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L1749)

(string): Используется для ссылки на объект данных в тексте шаблона.

## Методы

### templateSettings-imports

#### `_.templateSettings.imports`

[source](https://github.com/lodash/lodash/blob/4.17.15/lodash.js#L1765)

Ссылка на функцию `lodash`.