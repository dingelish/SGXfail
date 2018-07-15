# SGX从入门到放弃

搞SGX也有快两年了，我觉得取这个名字还是挺恰当——从入门到放弃，虽然到现在我还在坚持。

SGX难学的一个主要理由是知识体系太碎了，没有什么统一的文档把东西都串起来，甚至有些知识点Intel自己都在含糊其辞。从我个人的经验看来，不吃透 [SGX SDK](https://github.com/intel/linux-sgx) 代码是很难写出一个“正确”的SGX程序的，我个人也没看到什么写的“正确”的SGX应用。

目前打算开个blog坑，每周写大概一个小时。尽量把我在捣鼓SGX里的经验和走的弯路都写一写。如果弃坑了也不要奇怪，抬头看看标题。┓( ´∀` )┏

本文的第一个读者（和第一个coauthor）应该是 [@zhengmin1989](https://github.com/zhengmin1989) 如果他能看得懂的话应该还可以的吧……

License是取的比较严的 [CC-BY-NC-ND](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.zh) 。毕竟是很随意的东西，大家看看就好。

欢迎提issue，PR。个人对SGX的理解可能是有错误的，欢迎指出。

最后打个广告，这一年多做的 [rust-sgx-sdk](https://github.com/baidu/rust-sgx-sdk) 自认为还是挺靠谱的。是唯一一个在 Intel SGX SDK 首页上被推荐的第三方SDK，已经有几个基于可信计算的区块链创业项目应用了这个SDK，比如 Berkeley Oasis Labs 的 [Ekiden](https://arxiv.org/abs/1804.05141)，MIT 的 [Engima](https://github.com/enigmampc/enigma-core) 等等。

## Index

[00 SGX能做什么](00.md)

[01 运行第一个SGX程序](01.md)

[02 CVE-2017-5753 upgrade 参考译文](02.md)

[03 Edger8r upgrade 参考译文](03.md)

# License
<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.

