# Neutorn

一篇文章很难说得清楚SDN是什么，解决什么问题的。况且如果没有任何网络知识也无法理解SDN。所以这个问题够一两本书的分量了，大家自行学习。（推荐“土专家”的《SDN原理解析 转控分离的SDN架构》）

**对Neutron不熟悉请参考 附录: Neutron精要**

Neutron采用VxLAN作为Overlay网络，底层网络需要开启“Jumbo frames”支持9000bytes（vxlan传递的是1450byte的frame）的frame **一般都已经开启**