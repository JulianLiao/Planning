# Planning

20200619:

简杰：planning所讲的SDK版本与非SDK版本仅仅只是针对planning内部而言的，#pod_controller这个binary，它是基于Localization SDK, Perception SDK，planning源码或者planning SDK编译而成的。

20200618在长富楼下测试的V1.5，所使用的#pod_controller是基于Localization的SDK + Perception的SDK + Planning的源码编译而成的。

如果要做radar的GFlags的测试，criteria1_ids/criteria1_range_min/criteria1_range_max等，需在planning.sh所对应的#pod_controller后面加上这些GFlag了再去测试。