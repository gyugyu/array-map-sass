# array-map-sass
Array#map implementation for Dart Sass


## idea

```scss
@use '@gyugyu/array-map-sass' as array-map;

@function foo($str) {
  @return $str + '-foo';
}

$foo: meta.get-function('foo');
$array: 'a', 'b', 'c';
$result: array-map.map($array, $foo); // 'a-foo', 'b-foo', 'c-foo'
```
