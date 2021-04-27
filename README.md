# 中文转字母

```php

$PinYin = new \PinYin\PinYin();

```

## 全部拼音

```php

$PinYin->convertPinyin("中国人");

输出 zhongguoren

```

## 全拼用_隔开

```php

$PinYin->convertPinyinList("中国人");

输出
Array
(
    [0] => zhong_guo_ren
)

```

## 中文转首字母

```php

$PinYin->convertInitalPinyin("中国人");

输出 zgr

```

## 这是首字母

```php

$PinYin->convertInitalPinyinList("中国人");

输出 
Array
(
    [0] => zgr
)

```

## 首字母+全字母用 — 隔开

```php

$PinYin->convertAllPinyinList('中国人', '_');

输出 
Array
(
    [full] => Array
        (
            [0] => zhong_guo_ren
        )
    [inital] => Array
        (
            [0] => z_g_r
        )
)

```
