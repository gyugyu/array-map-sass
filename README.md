# array-map-sass
Array#map implementation for Dart Sass


## idea

```scss
@function foo($str) {
  @return $str + '-foo';
}

$foo: meta.get-function('foo');
$array: 'a', 'b', 'c';
$result: functions.map($array, $foo); // 'a-foo', 'b-foo', 'c-foo'
```
