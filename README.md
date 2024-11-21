# MiniTorch Module 3

<img src="https://minitorch.github.io/minitorch.svg" width="50%">

* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module3.html


You will need to modify `tensor_functions.py` slightly in this assignment.

* Tests:

```
python run_tests.py
```

* Note:

Several of the tests for this assignment will only run if you are on a GPU machine and will not
run on github's test infrastructure. Please follow the instructions to setup up a colab machine
to run these tests.

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/tensor_data.py minitorch/tensor_functions.py minitorch/tensor_ops.py minitorch/operators.py minitorch/scalar.py minitorch/scalar_functions.py minitorch/module.py minitorch/autodiff.py minitorch/module.py project/run_manual.py project/run_scalar.py project/run_tensor.py minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/tensor.py minitorch/datasets.py minitorch/testing.py minitorch/optim.py

## Results:

# Simple, GPU, Hidden 100


Epoch  0  loss  4.768219310922747 correct 48 epoch time in ms 0.0

Epoch  10  loss  1.410809274715594 correct 49 epoch time in ms 1625.7

Epoch  20  loss  1.3800761719737618 correct 50 epoch time in ms 1555.5

Epoch  30  loss  0.3613477629809118 correct 50 epoch time in ms 1537.6

Epoch  40  loss  0.6582540779085095 correct 48 epoch time in ms 1558.7

Epoch  50  loss  1.0095665956486182 correct 50 epoch time in ms 1614.8

Epoch  60  loss  0.17155064961057248 correct 50 epoch time in ms 1541.0

Epoch  70  loss  0.24018641272558164 correct 49 epoch time in ms 1539.9

Epoch  80  loss  0.11137668018150682 correct 50 epoch time in ms 1655.0

Epoch  90  loss  0.5713561889060504 correct 50 epoch time in ms 1598.9

Epoch  100  loss  0.7780930794179876 correct 50 epoch time in ms 1553.2

Epoch  110  loss  0.5661624463892403 correct 50 epoch time in ms 1549.6

Epoch  120  loss  0.375695313325004 correct 50 epoch time in ms 1617.3

Epoch  130  loss  0.044718355339721676 correct 50 epoch time in ms 1530.6

Epoch  140  loss  0.05280246303852996 correct 50 epoch time in ms 1537.5

Epoch  150  loss  0.5534482143789095 correct 50 epoch time in ms 1536.6

Epoch  160  loss  0.007799220713413216 correct 50 epoch time in ms 1619.0

Epoch  170  loss  0.10066829229413925 correct 48 epoch time in ms 1538.5

Epoch  180  loss  0.5086936398582056 correct 50 epoch time in ms 1539.5

Epoch  190  loss  0.005194827528937148 correct 50 epoch time in ms 1550.9

Epoch  200  loss  0.13551447907194564 correct 50 epoch time in ms 1597.8

Epoch  210  loss  0.472017520607476 correct 50 epoch time in ms 1535.9

Epoch  220  loss  0.1804772291529378 correct 50 epoch time in ms 1546.8

Epoch  230  loss  0.19010932839216854 correct 50 epoch time in ms 1707.1

Epoch  240  loss  0.6197257606415719 correct 50 epoch time in ms 1533.0

Epoch  250  loss  0.010761797298740092 correct 50 epoch time in ms 1536.5

Epoch  260  loss  0.1756256966499603 correct 50 epoch time in ms 1532.9

Epoch  270  loss  1.3353768303202425 correct 50 epoch time in ms 1618.0

Epoch  280  loss  0.390452872899641 correct 50 epoch time in ms 1537.5

Epoch  290  loss  0.13003965153404173 correct 50 epoch time in ms 1537.2

Epoch  300  loss  0.007912766662076043 correct 50 epoch time in ms 1548.6

Epoch  310  loss  0.5825778272930571 correct 50 epoch time in ms 1612.6

Epoch  320  loss  0.314478984092219 correct 50 epoch time in ms 1531.7

Epoch  330  loss  0.3591697238216821 correct 50 epoch time in ms 1539.4

Epoch  340  loss  0.35349812945301706 correct 50 epoch time in ms 1593.5

Epoch  350  loss  0.00013042621360014273 correct 50 epoch time in ms 1556.4

Epoch  360  loss  0.5683536911471722 correct 50 epoch time in ms 1532.0

Epoch  370  loss  1.4553603259818426 correct 50 epoch time in ms 1538.1

Epoch  380  loss  0.7175334379187809 correct 50 epoch time in ms 1697.3

Epoch  390  loss  0.34577976272457284 correct 50 epoch time in ms 1536.4

Epoch  400  loss  0.23970398087255707 correct 50 epoch time in ms 1534.0

Epoch  410  loss  0.4450932674667527 correct 50 epoch time in ms 1546.5

Epoch  420  loss  0.0005308827146959993 correct 50 epoch time in ms 1606.7

Epoch  430  loss  0.45147148194737113 correct 50 epoch time in ms 1535.5

Epoch  440  loss  0.3976374356313271 correct 50 epoch time in ms 1535.1

Epoch  450  loss  0.0888839539050724 correct 50 epoch time in ms 1583.4

Epoch  460  loss  1.172599847807059 correct 48 epoch time in ms 1575.4

Epoch  470  loss  0.36068332700937117 correct 50 epoch time in ms 1536.4

Epoch  480  loss  0.001489381429434778 correct 50 epoch time in ms 1538.3

Epoch  490  loss  0.000863774635308489 correct 50 epoch time in ms 1612.2

# XOR, GPU, Hidden 100


Epoch  0  loss  6.899522065817319 correct 33 epoch time in ms 0.0

Epoch  10  loss  5.106049397819108 correct 40 epoch time in ms 1586.7

Epoch  20  loss  3.1489526949752853 correct 44 epoch time in ms 1543.3

Epoch  30  loss  3.320160077399261 correct 42 epoch time in ms 1547.3

Epoch  40  loss  3.79815732760567 correct 44 epoch time in ms 1643.4

Epoch  50  loss  1.3234856124440801 correct 47 epoch time in ms 1539.9

Epoch  60  loss  2.7814977319567546 correct 48 epoch time in ms 1537.4

Epoch  70  loss  1.6416927855552785 correct 46 epoch time in ms 1537.4

Epoch  80  loss  2.36217163497284 correct 48 epoch time in ms 1613.2

Epoch  90  loss  2.9229456488090717 correct 47 epoch time in ms 1542.9

Epoch  100  loss  1.4679198866388332 correct 49 epoch time in ms 1544.0

Epoch  110  loss  1.3101112875528862 correct 47 epoch time in ms 1588.3

Epoch  120  loss  1.1868381251683515 correct 48 epoch time in ms 1647.8

Epoch  130  loss  2.1491066042003943 correct 50 epoch time in ms 1539.6

Epoch  140  loss  1.3933147020021548 correct 49 epoch time in ms 1539.7

Epoch  150  loss  2.4269246054291114 correct 47 epoch time in ms 1619.2

Epoch  160  loss  1.214418646225618 correct 50 epoch time in ms 1541.1

Epoch  170  loss  1.581047894717417 correct 49 epoch time in ms 1534.1

Epoch  180  loss  0.4859296335780082 correct 50 epoch time in ms 1560.4

Epoch  190  loss  0.9881575890704277 correct 50 epoch time in ms 1593.9

Epoch  200  loss  0.5849427396334139 correct 50 epoch time in ms 1543.7

Epoch  210  loss  0.3983196247208524 correct 50 epoch time in ms 1541.2

Epoch  220  loss  0.8801148119658145 correct 50 epoch time in ms 1616.0

Epoch  230  loss  0.8242416678710887 correct 50 epoch time in ms 1537.3

Epoch  240  loss  1.185797764188401 correct 50 epoch time in ms 1540.3

Epoch  250  loss  0.6301513967298297 correct 50 epoch time in ms 1539.1

Epoch  260  loss  0.21412252695427642 correct 50 epoch time in ms 1695.8

Epoch  270  loss  1.3925007036664578 correct 50 epoch time in ms 1534.8

Epoch  280  loss  0.28512615284317777 correct 50 epoch time in ms 1538.5

Epoch  290  loss  0.48399208670927824 correct 50 epoch time in ms 1573.5

Epoch  300  loss  0.7541183851536956 correct 50 epoch time in ms 1573.9

Epoch  310  loss  0.08894322294485062 correct 50 epoch time in ms 1532.4

Epoch  320  loss  0.5182585011914184 correct 50 epoch time in ms 1530.2

Epoch  330  loss  0.3683043163819675 correct 50 epoch time in ms 1607.9

Epoch  340  loss  1.1467593963469724 correct 50 epoch time in ms 1538.6

Epoch  350  loss  0.4273282307813587 correct 50 epoch time in ms 1533.7

Epoch  360  loss  0.712983616145965 correct 50 epoch time in ms 1534.9

Epoch  370  loss  0.9890969898533121 correct 50 epoch time in ms 1611.9

Epoch  380  loss  0.25008983142318403 correct 50 epoch time in ms 1534.0

Epoch  390  loss  0.0987671302225916 correct 50 epoch time in ms 1531.4

Epoch  400  loss  0.15345273757796213 correct 50 epoch time in ms 1644.2

Epoch  410  loss  0.028490656447203548 correct 50 epoch time in ms 1580.9

Epoch  420  loss  0.672116006510709 correct 50 epoch time in ms 1534.6

Epoch  430  loss  0.2585591038186677 correct 50 epoch time in ms 1538.9

Epoch  440  loss  0.3585141231393063 correct 50 epoch time in ms 1605.1

Epoch  450  loss  0.5284372565853951 correct 50 epoch time in ms 1548.0

Epoch  460  loss  0.6117897723022376 correct 50 epoch time in ms 1535.1

Epoch  470  loss  0.2061543635595231 correct 50 epoch time in ms 1529.2

Epoch  480  loss  0.4189114485264588 correct 50 epoch time in ms 1605.6

Epoch  490  loss  0.0066622254371742 correct 50 epoch time in ms 1528.0

# Split, GPU, Hidden 100


Epoch  0  loss  7.192416241218771 correct 28 epoch time in ms 0.0

Epoch  10  loss  5.706944518663654 correct 40 epoch time in ms 1559.1

Epoch  20  loss  7.122136003723768 correct 28 epoch time in ms 1551.3

Epoch  30  loss  2.5122787975283387 correct 38 epoch time in ms 1618.2

Epoch  40  loss  5.187405044317348 correct 44 epoch time in ms 1548.1

Epoch  50  loss  3.233043939072293 correct 47 epoch time in ms 1530.2

Epoch  60  loss  3.508838788353204 correct 47 epoch time in ms 1625.1

Epoch  70  loss  1.5335075700760457 correct 48 epoch time in ms 1602.5

Epoch  80  loss  1.1972471667282139 correct 50 epoch time in ms 1537.3

Epoch  90  loss  1.0699011601648736 correct 49 epoch time in ms 1541.5

Epoch  100  loss  1.3110792906244293 correct 50 epoch time in ms 1594.6

Epoch  110  loss  2.092490521132872 correct 50 epoch time in ms 1573.8

Epoch  120  loss  1.03189326421073 correct 47 epoch time in ms 1533.0

Epoch  130  loss  0.8427377689211336 correct 48 epoch time in ms 1530.2

Epoch  140  loss  1.5782220633268258 correct 50 epoch time in ms 1615.6

Epoch  150  loss  0.3921500727206053 correct 50 epoch time in ms 1526.2

Epoch  160  loss  0.11444015079711524 correct 49 epoch time in ms 1539.5

Epoch  170  loss  0.5131374120498842 correct 50 epoch time in ms 1529.6

Epoch  180  loss  0.8764755812366531 correct 48 epoch time in ms 1608.3

Epoch  190  loss  1.1260826431115094 correct 50 epoch time in ms 1535.4

Epoch  200  loss  0.8266889054116185 correct 50 epoch time in ms 1609.4

Epoch  210  loss  1.1251594175060327 correct 50 epoch time in ms 1556.2

Epoch  220  loss  0.9132977123868556 correct 50 epoch time in ms 1592.6

Epoch  230  loss  1.6483917830911632 correct 47 epoch time in ms 1530.6

Epoch  240  loss  1.2277072085516365 correct 50 epoch time in ms 1533.0

Epoch  250  loss  0.5448198056646333 correct 48 epoch time in ms 1589.1

Epoch  260  loss  0.10147811874374855 correct 50 epoch time in ms 1549.7

Epoch  270  loss  0.9398164699389504 correct 50 epoch time in ms 1534.7

Epoch  280  loss  0.43115777471318106 correct 50 epoch time in ms 1536.6

Epoch  290  loss  0.08395809016155423 correct 49 epoch time in ms 1609.3

Epoch  300  loss  0.316533931514556 correct 50 epoch time in ms 1535.7

Epoch  310  loss  0.8669693403338601 correct 50 epoch time in ms 1526.3

Epoch  320  loss  0.277235531305347 correct 50 epoch time in ms 1530.6

Epoch  330  loss  0.6902393972333739 correct 50 epoch time in ms 1606.8

Epoch  340  loss  0.7449701355249337 correct 50 epoch time in ms 1533.9

Epoch  350  loss  0.705889213342094 correct 50 epoch time in ms 1608.3

Epoch  360  loss  1.0919337905057542 correct 49 epoch time in ms 1560.0

Epoch  370  loss  1.0424987084184645 correct 48 epoch time in ms 1581.8

Epoch  380  loss  0.7137379756357292 correct 50 epoch time in ms 1527.1

Epoch  390  loss  0.2467559199204925 correct 50 epoch time in ms 1529.5

Epoch  400  loss  0.23883228925115077 correct 50 epoch time in ms 1579.6

Epoch  410  loss  0.6955010691526716 correct 50 epoch time in ms 1553.3

Epoch  420  loss  0.3373410650834947 correct 50 epoch time in ms 1527.5

Epoch  430  loss  0.24540803358542373 correct 50 epoch time in ms 1523.8

Epoch  440  loss  0.024456419518789897 correct 50 epoch time in ms 1599.9

Epoch  450  loss  0.14260299670577106 correct 50 epoch time in ms 1539.9

Epoch  460  loss  0.6277701920398486 correct 50 epoch time in ms 1530.9

Epoch  470  loss  0.014236207691105483 correct 50 epoch time in ms 1531.1

Epoch  480  loss  0.6515125340692776 correct 50 epoch time in ms 1604.9

Epoch  490  loss  0.3354809272763657 correct 50 epoch time in ms 1629.4

# Simple, CPU, Hidden 100


Epoch  0  loss  3.846735837149852 correct 49 epoch time in ms 0.0

Epoch  10  loss  1.7183266107394275 correct 49 epoch time in ms 95.4

Epoch  20  loss  1.08446561633083 correct 50 epoch time in ms 94.6

Epoch  30  loss  1.1983330129004945 correct 50 epoch time in ms 145.7

Epoch  40  loss  0.6170399926351288 correct 50 epoch time in ms 149.6

Epoch  50  loss  0.9866389209424038 correct 50 epoch time in ms 95.3

Epoch  60  loss  1.2543521568471578 correct 50 epoch time in ms 95.5

Epoch  70  loss  0.04923933592905784 correct 50 epoch time in ms 95.2

Epoch  80  loss  0.547130792530882 correct 50 epoch time in ms 94.6

Epoch  90  loss  0.45392149673225846 correct 50 epoch time in ms 93.7

Epoch  100  loss  0.02036945760030573 correct 50 epoch time in ms 95.1

Epoch  110  loss  0.38071293637407244 correct 50 epoch time in ms 95.1

Epoch  120  loss  0.17267481392489292 correct 50 epoch time in ms 94.9

Epoch  130  loss  0.43372666962332634 correct 50 epoch time in ms 95.4

Epoch  140  loss  0.02901535837493149 correct 50 epoch time in ms 101.6

Epoch  150  loss  0.5352586093838186 correct 50 epoch time in ms 145.2

Epoch  160  loss  0.08412059850607424 correct 50 epoch time in ms 146.4

Epoch  170  loss  0.012157913814232793 correct 50 epoch time in ms 94.7

Epoch  180  loss  0.24550229112729124 correct 50 epoch time in ms 94.9

Epoch  190  loss  0.2790937654963262 correct 50 epoch time in ms 94.8

Epoch  200  loss  0.3465067717087246 correct 50 epoch time in ms 95.0

Epoch  210  loss  0.07760751331409536 correct 50 epoch time in ms 94.4

Epoch  220  loss  0.02896136054622693 correct 50 epoch time in ms 93.6

Epoch  230  loss  0.1459553118158344 correct 50 epoch time in ms 95.2

Epoch  240  loss  0.004629076916344483 correct 50 epoch time in ms 95.5

Epoch  250  loss  0.07524524492294529 correct 50 epoch time in ms 94.7

Epoch  260  loss  0.008139121229032608 correct 50 epoch time in ms 96.4

Epoch  270  loss  0.15376097932105556 correct 50 epoch time in ms 156.8

Epoch  280  loss  0.008475155498704649 correct 50 epoch time in ms 142.5

Epoch  290  loss  0.22885678281710817 correct 50 epoch time in ms 94.2

Epoch  300  loss  0.09185360314353691 correct 50 epoch time in ms 94.3

Epoch  310  loss  0.06636654068759999 correct 50 epoch time in ms 95.0

Epoch  320  loss  0.14539747666257158 correct 50 epoch time in ms 94.0

Epoch  330  loss  0.0016667267368775094 correct 50 epoch time in ms 95.6

Epoch  340  loss  0.00027128361950523355 correct 50 epoch time in ms 94.9

Epoch  350  loss  0.0425501166979336 correct 50 epoch time in ms 95.0

Epoch  360  loss  0.10894206898909782 correct 50 epoch time in ms 93.6

Epoch  370  loss  0.1313144884552725 correct 50 epoch time in ms 94.7

Epoch  380  loss  0.00046533231055635184 correct 50 epoch time in ms 101.0

Epoch  390  loss  0.23150312136103862 correct 50 epoch time in ms 152.4

Epoch  400  loss  0.18358423771294238 correct 50 epoch time in ms 139.2

Epoch  410  loss  0.0003128206284247433 correct 50 epoch time in ms 95.4

Epoch  420  loss  0.12762387672397227 correct 50 epoch time in ms 101.0

Epoch  430  loss  0.07982455603517484 correct 50 epoch time in ms 96.2

Epoch  440  loss  0.11889636947098119 correct 50 epoch time in ms 94.9

Epoch  450  loss  0.0004333095363474921 correct 50 epoch time in ms 94.9

Epoch  460  loss  0.003363958294074344 correct 50 epoch time in ms 95.1

Epoch  470  loss  0.03219554794669817 correct 50 epoch time in ms 94.4

Epoch  480  loss  0.1389626526892504 correct 50 epoch time in ms 94.8

Epoch  490  loss  0.0594441289314388 correct 50 epoch time in ms 94.6

# XOR, CPU, Hidden 100


Epoch  0  loss  11.108385306958565 correct 30 epoch time in ms 0.0

Epoch  10  loss  5.080683538426019 correct 45 epoch time in ms 96.1

Epoch  20  loss  3.9585685174573606 correct 42 epoch time in ms 95.4

Epoch  30  loss  3.3430705437172534 correct 47 epoch time in ms 97.4

Epoch  40  loss  4.816341984345697 correct 46 epoch time in ms 174.8

Epoch  50  loss  0.8377671257418436 correct 44 epoch time in ms 125.5

Epoch  60  loss  1.8258909030795178 correct 47 epoch time in ms 96.0

Epoch  70  loss  2.5367825770633465 correct 47 epoch time in ms 170.3

Epoch  80  loss  1.530020366046721 correct 49 epoch time in ms 129.1

Epoch  90  loss  0.4468491471351627 correct 48 epoch time in ms 94.7

Epoch  100  loss  2.2971155104138847 correct 47 epoch time in ms 96.6

Epoch  110  loss  0.6162546076289623 correct 48 epoch time in ms 96.7

Epoch  120  loss  1.8193066905654274 correct 49 epoch time in ms 96.5

Epoch  130  loss  0.7328879564188726 correct 50 epoch time in ms 94.9

Epoch  140  loss  1.1119704335889744 correct 49 epoch time in ms 96.0

Epoch  150  loss  1.0765937756690647 correct 49 epoch time in ms 96.4

Epoch  160  loss  0.4908609799842811 correct 50 epoch time in ms 95.6

Epoch  170  loss  0.9105685378413971 correct 49 epoch time in ms 95.9

Epoch  180  loss  0.3192920273997285 correct 49 epoch time in ms 104.4

Epoch  190  loss  0.7692967439526959 correct 49 epoch time in ms 168.1

Epoch  200  loss  0.11559900826383941 correct 50 epoch time in ms 122.7

Epoch  210  loss  1.068301871131912 correct 49 epoch time in ms 95.6

Epoch  220  loss  0.9859595372860522 correct 49 epoch time in ms 95.5

Epoch  230  loss  0.7210265285900324 correct 50 epoch time in ms 95.2

Epoch  240  loss  1.463245856053397 correct 50 epoch time in ms 98.2

Epoch  250  loss  0.4969282729206648 correct 50 epoch time in ms 94.5

Epoch  260  loss  0.8444710346056092 correct 49 epoch time in ms 97.1

Epoch  270  loss  1.546700780926652 correct 50 epoch time in ms 96.2

Epoch  280  loss  0.37245819263024815 correct 50 epoch time in ms 95.9

Epoch  290  loss  1.4827099384867408 correct 50 epoch time in ms 99.0

Epoch  300  loss  0.19071401434718174 correct 50 epoch time in ms 120.6

Epoch  310  loss  0.34395945744394557 correct 49 epoch time in ms 175.4

Epoch  320  loss  1.1773294755799024 correct 50 epoch time in ms 100.9

Epoch  330  loss  0.15254340606359038 correct 50 epoch time in ms 95.0

Epoch  340  loss  0.2518548972654799 correct 49 epoch time in ms 95.6

Epoch  350  loss  0.3151456847893047 correct 49 epoch time in ms 95.1

Epoch  360  loss  0.5011375347811822 correct 49 epoch time in ms 95.5

Epoch  370  loss  0.24814488729784587 correct 49 epoch time in ms 95.6

Epoch  380  loss  0.08808860727651965 correct 49 epoch time in ms 102.4

Epoch  390  loss  1.1594242400941117 correct 50 epoch time in ms 96.9

Epoch  400  loss  0.33494195514374336 correct 50 epoch time in ms 95.8

Epoch  410  loss  0.3423039387930307 correct 50 epoch time in ms 95.2

Epoch  420  loss  0.11829266975239824 correct 50 epoch time in ms 130.1

Epoch  430  loss  1.1414745733661062 correct 50 epoch time in ms 165.1

Epoch  440  loss  1.1004681912960785 correct 50 epoch time in ms 95.3

Epoch  450  loss  0.1870338552099818 correct 50 epoch time in ms 95.3

Epoch  460  loss  0.1045731107094104 correct 50 epoch time in ms 95.6

Epoch  470  loss  1.1419929713842896 correct 50 epoch time in ms 95.2

Epoch  480  loss  0.8531885868426944 correct 50 epoch time in ms 94.9

Epoch  490  loss  1.0242237273980093 correct 50 epoch time in ms 95.3

# Split, CPU, Hidden 100


Epoch  0  loss  11.091283065371474 correct 23 epoch time in ms 0.0

Epoch  10  loss  8.31311276604704 correct 37 epoch time in ms 97.6

Epoch  20  loss  4.932694395550461 correct 34 epoch time in ms 94.7

Epoch  30  loss  5.450750894598421 correct 48 epoch time in ms 94.4

Epoch  40  loss  4.06659445524231 correct 46 epoch time in ms 169.9

Epoch  50  loss  3.3655407240026047 correct 45 epoch time in ms 134.7

Epoch  60  loss  3.399157147977236 correct 46 epoch time in ms 94.6

Epoch  70  loss  2.248868797658673 correct 45 epoch time in ms 93.5

Epoch  80  loss  2.1203605543223354 correct 47 epoch time in ms 94.9

Epoch  90  loss  1.9128156440700634 correct 45 epoch time in ms 95.5

Epoch  100  loss  2.2616077784641426 correct 49 epoch time in ms 95.2

Epoch  110  loss  1.2236791924410897 correct 49 epoch time in ms 94.6

Epoch  120  loss  1.7760082832661992 correct 49 epoch time in ms 94.7

Epoch  130  loss  2.6989044189489917 correct 46 epoch time in ms 95.7

Epoch  140  loss  2.367697718613657 correct 49 epoch time in ms 95.1

Epoch  150  loss  2.600594388671719 correct 48 epoch time in ms 94.6

Epoch  160  loss  0.6571597382149575 correct 49 epoch time in ms 167.1

Epoch  170  loss  0.8106432877238844 correct 48 epoch time in ms 129.3

Epoch  180  loss  0.903459087725765 correct 46 epoch time in ms 94.8

Epoch  190  loss  0.40365200931673256 correct 48 epoch time in ms 95.0

Epoch  200  loss  1.465900075845446 correct 49 epoch time in ms 93.1

Epoch  210  loss  0.34428111835641556 correct 50 epoch time in ms 95.4

Epoch  220  loss  0.8925029980623699 correct 48 epoch time in ms 103.5

Epoch  230  loss  1.7330704888815924 correct 49 epoch time in ms 98.9

Epoch  240  loss  0.8620225155038341 correct 50 epoch time in ms 95.1

Epoch  250  loss  0.8880660744808118 correct 49 epoch time in ms 94.0

Epoch  260  loss  1.2827189187718149 correct 49 epoch time in ms 94.7

Epoch  270  loss  0.8594284139680274 correct 49 epoch time in ms 104.4

Epoch  280  loss  1.3709161546558295 correct 50 epoch time in ms 165.1

Epoch  290  loss  0.5869600563858686 correct 50 epoch time in ms 116.3

Epoch  300  loss  0.6069976931231389 correct 50 epoch time in ms 94.6

Epoch  310  loss  1.4369810511023997 correct 50 epoch time in ms 94.9

Epoch  320  loss  0.8874430885660429 correct 50 epoch time in ms 97.4

Epoch  330  loss  1.4250171727494017 correct 50 epoch time in ms 94.8

Epoch  340  loss  0.4622147435701842 correct 49 epoch time in ms 98.1

Epoch  350  loss  0.365324166786703 correct 49 epoch time in ms 94.3

Epoch  360  loss  0.8790149385729109 correct 50 epoch time in ms 95.7

Epoch  370  loss  0.07372875041353195 correct 48 epoch time in ms 94.1

Epoch  380  loss  1.4445058775450608 correct 50 epoch time in ms 100.7

Epoch  390  loss  1.1263492167147466 correct 48 epoch time in ms 113.9

Epoch  400  loss  1.3130838158977918 correct 50 epoch time in ms 171.6

Epoch  410  loss  2.135429146494575 correct 48 epoch time in ms 106.8

Epoch  420  loss  0.2693460608333501 correct 50 epoch time in ms 95.2

Epoch  430  loss  0.4663225278621366 correct 49 epoch time in ms 94.5

Epoch  440  loss  1.740258685381847 correct 50 epoch time in ms 94.1

Epoch  450  loss  1.1416367297789687 correct 50 epoch time in ms 95.0

Epoch  460  loss  0.709195367200955 correct 50 epoch time in ms 94.4

Epoch  470  loss  2.2015993938500085 correct 48 epoch time in ms 94.9

Epoch  480  loss  0.48944294557781054 correct 48 epoch time in ms 96.6

Epoch  490  loss  0.8133583726713369 correct 50 epoch time in ms 94.8

# Simple, GPU, 200 Hidden

Average epoch time is 1.7 seconds


Epoch  0  loss  3.0292057597021005 correct 44 epoch time 0

Epoch  10  loss  1.4848428075165403 correct 49 epoch time 16333

Epoch  20  loss  0.8390531886889816 correct 50 epoch time 17243

Epoch  30  loss  0.6829435991494706 correct 46 epoch time 16400

Epoch  40  loss  0.6014723641275683 correct 50 epoch time 16508

Epoch  50  loss  0.34730356885735036 correct 50 epoch time 17022

Epoch  60  loss  1.1501554530805826 correct 47 epoch time 17300

Epoch  70  loss  1.9055815276609138 correct 47 epoch time 16574

Epoch  80  loss  0.5897254230508595 correct 49 epoch time 16699

Epoch  90  loss  0.11990890335490034 correct 50 epoch time 16361

Epoch  100  loss  1.0505955309210466 correct 50 epoch time 16644

Epoch  110  loss  0.00964031332472898 correct 50 epoch time 16791

Epoch  120  loss  1.098940407699051 correct 48 epoch time 16297

Epoch  130  loss  0.7687804182340212 correct 50 epoch time 16811

Epoch  140  loss  0.2356150944700163 correct 49 epoch time 16602

Epoch  150  loss  0.5095125655233959 correct 49 epoch time 16266

Epoch  160  loss  1.1938771118261087 correct 47 epoch time 16953

Epoch  170  loss  0.28936549391495947 correct 50 epoch time 16419

Epoch  180  loss  1.385643796804681 correct 50 epoch time 16184

Epoch  190  loss  0.12206196475744373 correct 49 epoch time 16677

Epoch  200  loss  0.7815612227966542 correct 50 epoch time 16518

Epoch  210  loss  0.95095977653832 correct 49 epoch time 16319

Epoch  220  loss  0.38775515258915616 correct 50 epoch time 16972

Epoch  230  loss  0.09300418455784504 correct 50 epoch time 16212

Epoch  240  loss  0.08038361308286349 correct 49 epoch time 16154

Epoch  250  loss  2.3439373568883655 correct 49 epoch time 16641

Epoch  260  loss  0.5200546175875127 correct 50 epoch time 16488

Epoch  270  loss  0.0725318124048017 correct 49 epoch time 17002

Epoch  280  loss  0.5573067926504635 correct 50 epoch time 17031

Epoch  290  loss  0.7235507955574988 correct 50 epoch time 16098

Epoch  300  loss  0.008422843305884614 correct 50 epoch time 16193

Epoch  310  loss  1.0142571978397903 correct 49 epoch time 17197

Epoch  320  loss  0.6708632816012695 correct 50 epoch time 16206

Epoch  330  loss  0.27269367427000163 correct 50 epoch time 16277

Epoch  340  loss  0.013523719053183454 correct 49 epoch time 16874

Epoch  350  loss  0.10312086739874277 correct 50 epoch time 16075

Epoch  360  loss  0.6433835596252395 correct 50 epoch time 16210

Epoch  370  loss  1.256113544060436 correct 48 epoch time 17074

Epoch  380  loss  0.08170729035858972 correct 50 epoch time 16311

Epoch  390  loss  0.8430831440523354 correct 50 epoch time 16323

Epoch  400  loss  0.09347931131399678 correct 50 epoch time 17108

Epoch  410  loss  0.2827291705159408 correct 50 epoch time 16185

Epoch  420  loss  0.6520030402045595 correct 49 epoch time 16168

Epoch  430  loss  0.16633175494937802 correct 50 epoch time 16912

Epoch  440  loss  0.21706002894547877 correct 50 epoch time 16334

Epoch  450  loss  0.018339329449635084 correct 50 epoch time 16312

Epoch  460  loss  0.1328499263635285 correct 50 epoch time 17060

Epoch  470  loss  0.00119190993476541 correct 49 epoch time 16233

Epoch  480  loss  0.07381371492319487 correct 50 epoch time 17027

Epoch  490  loss  0.6176695861777802 correct 50 epoch time 16871

# Simple, CPU, 200 Hidden

Average epoch time is 0.3 seconds


Epoch  0  loss  4.049666987391138 correct 39 epoch time 0

Epoch  10  loss  1.0451884989959181 correct 47 epoch time 3179

Epoch  20  loss  1.3216714503459897 correct 49 epoch time 2016

Epoch  30  loss  1.8807202237226905 correct 50 epoch time 2035

Epoch  40  loss  1.8157734673041068 correct 47 epoch time 2019

Epoch  50  loss  0.3043558749861071 correct 50 epoch time 2002

Epoch  60  loss  2.031188895850809 correct 46 epoch time 2251

Epoch  70  loss  0.5907293020281419 correct 49 epoch time 3000

Epoch  80  loss  0.049860673959124156 correct 49 epoch time 2008

Epoch  90  loss  0.12102202079014852 correct 50 epoch time 2008

Epoch  100  loss  0.20635673056438206 correct 50 epoch time 2007

Epoch  110  loss  0.05324660691335545 correct 49 epoch time 2015

Epoch  120  loss  0.23211300432033244 correct 50 epoch time 2816

Epoch  130  loss  0.07299149964420247 correct 50 epoch time 2352

Epoch  140  loss  0.11245772148924452 correct 50 epoch time 2027

Epoch  150  loss  1.1112544226464474 correct 49 epoch time 2024

Epoch  160  loss  0.9440955490129295 correct 50 epoch time 2400

Epoch  170  loss  0.01485057824931012 correct 50 epoch time 2106

Epoch  180  loss  0.06054724790918051 correct 50 epoch time 3033

Epoch  190  loss  0.25483457954031136 correct 50 epoch time 2041

Epoch  200  loss  0.4370812644608729 correct 50 epoch time 2008

Epoch  210  loss  0.5876674763163217 correct 49 epoch time 2033

Epoch  220  loss  0.012922418256366803 correct 50 epoch time 2025

Epoch  230  loss  0.35552684196526524 correct 50 epoch time 2801

Epoch  240  loss  0.09783791182619168 correct 50 epoch time 2379

Epoch  250  loss  0.003682417318961139 correct 50 epoch time 2032

Epoch  260  loss  0.886004836091282 correct 49 epoch time 2070

Epoch  270  loss  0.0969180008297372 correct 49 epoch time 2031

Epoch  280  loss  1.1542812843084171 correct 49 epoch time 2017

Epoch  290  loss  0.7391905254517088 correct 50 epoch time 3136

Epoch  300  loss  0.03741208487313201 correct 50 epoch time 2026

Epoch  310  loss  0.5060610838032757 correct 50 epoch time 2032

Epoch  320  loss  0.06196417871051188 correct 49 epoch time 2024

Epoch  330  loss  0.8392981886303184 correct 50 epoch time 2050

Epoch  340  loss  0.03947695896812885 correct 49 epoch time 2490

Epoch  350  loss  0.1448199793042615 correct 50 epoch time 2664

Epoch  360  loss  0.8051441374010929 correct 50 epoch time 1996

Epoch  370  loss  0.02800478698856881 correct 50 epoch time 2028

Epoch  380  loss  0.8766179676026359 correct 50 epoch time 2061

Epoch  390  loss  0.6083181877562931 correct 50 epoch time 2005

Epoch  400  loss  0.055729698212180545 correct 50 epoch time 3129

Epoch  410  loss  0.06467745423696304 correct 50 epoch time 2013

Epoch  420  loss  0.0003025609634967026 correct 49 epoch time 2003

Epoch  430  loss  0.19647429795522245 correct 50 epoch time 2048

Epoch  440  loss  0.5280772160815217 correct 50 epoch time 2011

Epoch  450  loss  0.7055925140568803 correct 50 epoch time 2105

Epoch  460  loss  0.006892462275606784 correct 50 epoch time 3034

Epoch  470  loss  0.01629442749540885 correct 50 epoch time 2002

Epoch  480  loss  0.06413490228301402 correct 50 epoch time 2007

Epoch  490  loss  0.3268477404680956 correct 50 epoch time 2024