# PinYin
中文转字母

## 传递参数
# new 
$PinYin = new \PinYin\PinYin();


## 全部拼音
$PinYin->convertPinyin("中国人");

zhongguoren

## 全拼用_隔开
$PinYin->convertPinyinList("中国人");

Array
(
    [0] => zhong_guo_ren
)


## 这是首字母
$PinYin->convertInitalPinyin("中国人");

zgr

## 这是首字母
$PinYin->convertInitalPinyinList("中国人");

Array
(
    [0] => zgr
)
## 首字母+全字母用 — 隔开
$PinYin->convertAllPinyinList('中国人', '_');

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
