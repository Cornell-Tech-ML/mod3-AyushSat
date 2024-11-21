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

# Simple

Epoch  0  loss  6.599651012550327 correct 33
Epoch  10  loss  1.3493981276006282 correct 49
Epoch  20  loss  0.44620352032965516 correct 50
Epoch  30  loss  1.0207460095810588 correct 49
Epoch  40  loss  0.7903751802900458 correct 49
Epoch  50  loss  0.5190423808494604 correct 49
Epoch  60  loss  0.5538363678040128 correct 49
Epoch  70  loss  1.0182325662827072 correct 49
Epoch  80  loss  0.20936890596461502 correct 49
Epoch  90  loss  0.682869476444458 correct 50
Epoch  100  loss  0.02480243338823334 correct 50
Epoch  110  loss  0.9194794780961542 correct 50
Epoch  120  loss  1.0441294354901958 correct 50
Epoch  130  loss  1.578740460507399 correct 50
Epoch  140  loss  0.2431467463655192 correct 50
Epoch  150  loss  0.25951434797734335 correct 50
Epoch  160  loss  0.8472231975426836 correct 50
Epoch  170  loss  0.03276109770246241 correct 50
Epoch  180  loss  0.19627506112660492 correct 50
Epoch  190  loss  0.9584603047826484 correct 50
Epoch  200  loss  0.44214439621840546 correct 50
Epoch  210  loss  0.3565899946811322 correct 50
Epoch  220  loss  0.7483978952915413 correct 50
Epoch  230  loss  0.29502613624295315 correct 50
Epoch  240  loss  0.5527227346715154 correct 50
Epoch  250  loss  0.5415921127168634 correct 50
Epoch  260  loss  0.17564971717789155 correct 50
Epoch  270  loss  0.029167119819464776 correct 50
Epoch  280  loss  0.027967931739194585 correct 50
Epoch  290  loss  0.4617353583634535 correct 50
Epoch  300  loss  0.03865228048452205 correct 50
Epoch  310  loss  0.1673113827488505 correct 50
Epoch  320  loss  0.22961995336103463 correct 50
Epoch  330  loss  0.4072294378877209 correct 50
Epoch  340  loss  0.06084044064855525 correct 50
Epoch  350  loss  0.031927128755118946 correct 50
Epoch  360  loss  0.1274006025214846 correct 50
Epoch  370  loss  0.08487746555953081 correct 50
Epoch  380  loss  0.09869242209798954 correct 50
Epoch  390  loss  0.07724718638488005 correct 50
Epoch  400  loss  0.0035815132110993486 correct 50
Epoch  410  loss  0.12161612546960328 correct 50
Epoch  420  loss  0.08150589870221771 correct 50
Epoch  430  loss  0.37454668591214624 correct 50
Epoch  440  loss  0.18926177899904478 correct 50
Epoch  450  loss  0.05105568840684177 correct 50
Epoch  460  loss  0.10558875886219124 correct 50
Epoch  470  loss  0.0014421340382851382 correct 50
Epoch  480  loss  0.3099639158301086 correct 50
Epoch  490  loss  0.27879146904559826 correct 50

# XOR 

Epoch  0  loss  6.029907266101271 correct 32
Epoch  10  loss  3.805369671643147 correct 42
Epoch  20  loss  2.943786719438231 correct 46
Epoch  30  loss  3.517345912135684 correct 48
Epoch  40  loss  2.9965283631000124 correct 46
Epoch  50  loss  3.7337319200491605 correct 47
Epoch  60  loss  1.5045466226748268 correct 47
Epoch  70  loss  3.653835846378702 correct 46
Epoch  80  loss  1.2640645572930576 correct 47
Epoch  90  loss  3.2144656062709758 correct 45
Epoch  100  loss  1.4753256616092167 correct 48
Epoch  110  loss  1.806285145217176 correct 48
Epoch  120  loss  2.3402107078814063 correct 47
Epoch  130  loss  1.4569094892782406 correct 48
Epoch  140  loss  1.423174832043299 correct 48
Epoch  150  loss  2.4445144306871587 correct 47
Epoch  160  loss  0.9750331168490186 correct 48
Epoch  170  loss  1.8616207860183223 correct 49
Epoch  180  loss  0.8865581669331755 correct 49
Epoch  190  loss  0.488060875941217 correct 48
Epoch  200  loss  0.4804168658596394 correct 49
Epoch  210  loss  1.0279673662330606 correct 49
Epoch  220  loss  1.142330590631326 correct 49
Epoch  230  loss  1.5235929748201216 correct 49
Epoch  240  loss  0.48061676635810874 correct 48
Epoch  250  loss  1.5734500936680045 correct 49
Epoch  260  loss  1.2960470315917931 correct 49
Epoch  270  loss  0.45664071586025984 correct 49
Epoch  280  loss  0.4594190072275263 correct 49
Epoch  290  loss  0.49120783004496366 correct 50
Epoch  300  loss  0.4374593540715565 correct 50
Epoch  310  loss  1.3582506965302745 correct 50
Epoch  320  loss  0.9039022897219535 correct 50
Epoch  330  loss  0.40152200420786316 correct 50
Epoch  340  loss  0.8519505678996989 correct 50
Epoch  350  loss  0.1049547329701729 correct 50
Epoch  360  loss  0.44823838384780745 correct 50
Epoch  370  loss  0.2411811975320129 correct 50
Epoch  380  loss  0.48303536875825676 correct 50
Epoch  390  loss  0.4745652123947332 correct 50
Epoch  400  loss  0.20972321501953797 correct 50
Epoch  410  loss  0.32500092660154506 correct 50
Epoch  420  loss  0.1538269176180347 correct 50
Epoch  430  loss  0.32601428032064445 correct 50
Epoch  440  loss  0.5163116307835848 correct 50
Epoch  450  loss  0.492189463619046 correct 50
Epoch  460  loss  0.48342639483471433 correct 50
Epoch  470  loss  0.2570838124045403 correct 50
Epoch  480  loss  0.10644833819533937 correct 50
Epoch  490  loss  0.20020915976035625 correct 50

# Split

Epoch  0  loss  6.673301174492056 correct 38
Epoch  10  loss  4.427349036316617 correct 41
Epoch  20  loss  4.056460012092515 correct 41
Epoch  30  loss  4.504917818326488 correct 42
Epoch  40  loss  3.3704983233214434 correct 42
Epoch  50  loss  2.294940142104741 correct 46
Epoch  60  loss  2.7282290211334375 correct 49
Epoch  70  loss  3.5466076917601383 correct 45
Epoch  80  loss  2.6891943543874968 correct 49
Epoch  90  loss  2.0399497351868665 correct 50
Epoch  100  loss  1.6943891884501054 correct 49
Epoch  110  loss  1.234788664247851 correct 49
Epoch  120  loss  1.2776413162002183 correct 49
Epoch  130  loss  1.8844056472380206 correct 49
Epoch  140  loss  0.37735917390675444 correct 50
Epoch  150  loss  1.4266902530176782 correct 49
Epoch  160  loss  0.5654945345478548 correct 50
Epoch  170  loss  0.6733362772575793 correct 47
Epoch  180  loss  1.5715053996883208 correct 50
Epoch  190  loss  1.2990023921577791 correct 50
Epoch  200  loss  1.5994772800822012 correct 50
Epoch  210  loss  1.0316231426383247 correct 49
Epoch  220  loss  0.4085897202782949 correct 48
Epoch  230  loss  1.0054950354823815 correct 50
Epoch  240  loss  1.6908464689803018 correct 49
Epoch  250  loss  0.3458513852891375 correct 49
Epoch  260  loss  0.9011653373506754 correct 50
Epoch  270  loss  0.47017709237568733 correct 50
Epoch  280  loss  0.6118021531854322 correct 49
Epoch  290  loss  0.938223145447326 correct 49
Epoch  300  loss  1.3285663434354407 correct 48
Epoch  310  loss  0.14057841030721172 correct 50
Epoch  320  loss  1.8322863715882456 correct 49
Epoch  330  loss  0.5400882845344818 correct 49
Epoch  340  loss  1.190677601189344 correct 50
Epoch  350  loss  0.034037867835949524 correct 50
Epoch  360  loss  0.23446770583118176 correct 50
Epoch  370  loss  0.1712188271837928 correct 49
Epoch  380  loss  0.11578342836210115 correct 50
Epoch  390  loss  0.9563812220662363 correct 49
Epoch  400  loss  0.5292997463351299 correct 50
Epoch  410  loss  0.36493063590615316 correct 50
Epoch  420  loss  0.031494410326699626 correct 49
Epoch  430  loss  0.10565304865271771 correct 49
Epoch  440  loss  0.2554579359778561 correct 49
Epoch  450  loss  1.4832661221041015 correct 49
Epoch  460  loss  0.00832467715303419 correct 50
Epoch  470  loss  0.018258225184855644 correct 49
Epoch  480  loss  0.5662794818735126 correct 49
Epoch  490  loss  0.13540191659533085 correct 49

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