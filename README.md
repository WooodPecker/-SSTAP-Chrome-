# -SSTAP-Chrome-
在使用SSTAP时，可以通过edge浏览器连接外网和内网，但使用chrome时只能连接内网，而无法连接外网。

可能是以前使用SwithyOmega的原因，导致电脑网络连接设置被更改了，再放弃使用SwithyOmega的一段时间内，使用monocloud可以直接连接内网和外网，并且monocloud自带pac模式，所以不需要要自动切换。但monocloud有一个缺点，就是每次连接速度较慢，且会出现流量拥堵，故决定使用vvoocloud。

但是通过SSTAP，按照vvoocloud的教程设置好后，发现可以通过edge浏览器连接外网和内网，但使用chrome时只能连接内网，而无法连接外网。阳阳说这不是正好么，一个内网，一个外网。然而对于我这种强迫症来说，只想使用chrome一种浏览器。捯饬了半天也没发现解决办法，后来想到可能是SwithyOmega的原因，果不其然，稍微设置一下就好了。但这里需要注意的是，由于SSTAP里，只支持全局模式，因此需要再SO中单独设置Auto Switch模式，并且代理协议为HTTP，服务器为本地，端口与局域网（Lan）设置中的一致。

重新设置后，稳如gou。。。
