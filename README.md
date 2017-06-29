# rime-quick_pinyin
A Chinese IME based on Pinyin while adapted by Chinese dialects and Middle Chinese

中文輸入法，以漢語拼音爲基礎，根據方言/中古漢語作調整

Based on RIME 基於RIME輸入法 http://rime.im/

Simplifications of pinyin are made to ensure any Chinese character can be typed with no more than 3 letters when its tone is not included.
Pinyin is also adapted to distinguish some characters with the same pronunciation in Mandarin while different in Chinese dialects and Middle Chinese.

對拼音做了簡化，除聲調外，每個字至多只需3個字母。同時修改了部分拼音，可區分部分普通話中同音而方言/中古漢語不同音的字。

Shuangpin is not adopted. Though its spelling is even shorter, it does not allow typing the beginning letter of each character in a word, which is allowed in this IME.

未採用雙拼，儘管其編碼更短，但它不支持用每個字的首字母打出一個詞。本輸入法支持首字母縮寫。

Tones can also be added when typing (-/<\), in the same way as Terra-pinyin https://github.com/rime/rime-terra-pinyin

打字時也可以增加聲調來檢字（-/<\），方案與地球拼音相同 https://github.com/rime/rime-terra-pinyin

Rules different from pinyin (compulsory):

1. Jianyin/Tuanyin are distinguished, consonant spelled as the pronunciation in Peking Opera: 近jin / 進zin (While in Mandarin both jin).

2. Endings -m/n are distinguished according to Middle Chinese: 巾jin / 金jim (While in Mandarin both jin).

3. zhi/chi/shi/zi/ci/si are changed to zhr/chr/shr/zr/cr/sr.

4. wu/w is changed to u; yi is changed to i; yu is changed to v; y under other contitions is changed to i; but wei/you are changed to ui/iu: 烏u, 灣uan, 衣i, 魚v, 月ve, 也ie, 威ui, 有iu.

與拼音不同的規則（必選）：

1. 和團音。聲母按京劇的發音方式：近jin / 進zin（普通話均爲jin）。

2. 區分-m/n韻尾，以中古漢語爲準：巾jin / 金jim（普通話均爲jin）。

3. zhi/chi/shi/zi/ci/si改爲zhr/chr/shr/zr/cr/sr。

4. wu/u改爲u；yi改爲i；yu改爲v；其他情況下y改爲i；但wei/you改爲ui/iu：烏u，灣uan，衣i，魚v，月ve，也ie，威ui，有iu。

More rules to shorten spelling (not compulsory):

1. zh/ch/sh can be replaced by j/q/x; ng can be replaced by g; uo can be replaced by o; van can be replaced by va; iong can be replaced by vg.

2. ia can be replaced by y. ai can be replace by y when after g/k/h/d/l (because gia/kia/hia do not exist, and 嗲/倆 are the only character for dia/lia respectively): 加jia/jy, 天tian/tyn, 開kai/ky, 帶dai/dy, 快kuai/kuy.

3. ao can be replaced by w. ua can be replace by w when before n/ng (because aon/aong do not exist): 包bao/bw, 交jiao/jiw, 端duan/dwn.

4. gua/kua/hua/fei can be replaced by gi/ki/hi/fi.

其他縮短編碼的規則（非必選）：

1. zh/ch/sh可以替換爲j/q/x；ng可以替換爲g；uo可以替換爲o；van可以替換爲va；iong可以替換爲vg。

2. ia可以替換爲y。ai在g/k/h/d/l後時可以替換爲y（因爲不存在gia/kia/hia，且嗲/倆分別是dia/lia的唯一漢字）：加jia/jy，天tian/tyn，開kai/ky，帶dai/dy，快kuai/kuy。

3. ao可以替換爲w。ua在n/ng前時可以替換爲w（因爲不存在aon/aong）：包bao/bw，交jiao/jiw，端duan/dwn。

4. gua/kua/hua/fei可以替換爲gi/ki/hi/fi。
