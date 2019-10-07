[Back](../../README.md)

# Why build your own VPN?

So you are looking for a VPN but don't know which one to choose. There are so many VPN services out there you are confused which one is better.

Ask yourself, why do you need a VPN?

If you are trying to watch Netflix than it doesn't really matter. But you are here because you value freedom, and you want to ensure access to information that some people don't want you to see.

It is known that certain countries [increase their censorship effort](https://globalvoices.org/2017/08/30/the-evolution-of-chinas-great-firewall-21-years-of-censorship/), [targeting VPN traffic](https://medium.com/@phoebecross/bypass-gfw-china-2018-2e553a3d9618) and [more and more VPN tools have stopped working](https://program-think.blogspot.com/2019/06/gfw-news.html). If you are looking for a VPN, there are no better people to ask than those who are in it every day trying to fight it.

Here's a brief history of the fight against censorship:
- Common VPN protocols such as PPTP, L2TP/IPsec, and unobfuscated OpenVPN has long been blocked
- [Shadowsocks (SS)](https://github.com/shadowsocks/shadowsocks-libev) was created in response to that, but is now detectable and are being blocked
- [ShadowsocskR (SSR)](https://github.com/shadowsocksrr/shadowsocksr-csharp) was built upon SS to increase obfuscation
- [V2Ray](https://github.com/v2ray/v2ray-core) was born after the [author of Shadowsocks was caught](https://web.archive.org/web/20150822223925/https://github.com/shadowsocks/shadowsocks-iOS/issues/124#issuecomment-133630294)

This guide is put together after extensive research into the matter and provide you a current working solution in the most difficult conditions. This is to prepare us in case the worst happens in Hong Kong. Unlike commercial VPNs who are trying to sell you features you don't need, the people who build their own are the ones who know their priorities.

We need to thank those who never give up on fighting for their freedom. Understand that there are people on the other side that [are aware of the situation](https://program-think.blogspot.com/2019/09/weekly-share-137.html). We are all in this together.

### See also

- [Outline VPN](https://getoutline.org/en/home) (Much easier to use, but has reportedly [stopped working](https://github.com/Jigsaw-Code/outline-server/issues/193) in certain areas)
- [Streisand](https://github.com/StreisandEffect/streisand) (Multi-protocol VPN setup)