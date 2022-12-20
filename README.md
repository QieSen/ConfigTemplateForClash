A configuration template for clash.

[简体中文 in Simplified Chinese](https://github.com/QieSen/ConfigTemplateForClash/blob/main/README_CHS.md)

## Feature
Using **Proxy Provider** and **Rule Provider**, with auto update enabled.

Separate frequently updated proxy nodes and rules from basic configuration, get rid of the stale rules and network outage.

Check here to learn about [Proxy Provider](https://lancellc.gitbook.io/clash/clash-config-file/proxy-provider) and [Rule Provider](https://lancellc.gitbook.io/clash/clash-config-file/rule-provider).


## Compatibility
This configuration is **only compatible with** the closed source [Clash Premium Core](https://github.com/Dreamacro/clash/releases/tag/premium) and third-party clash cores such as the open source [Clash.Meta Kernel](https://github.com/MetaCubeX/Clash.Meta).


Clash Premium Core is integrated by [CFA Premium version](https://github.com/Kr328/ClashForAndroid/releases) and [CFW](https://github.com/Fndroid/clash_for_windows_pkg/releases) out of the box.

Clash.Meta Kernal is integrated by [CMFA](https://github.com/MetaCubeX/ClashMetaForAndroid) out of the box.

## How to use

A free URL shortening service (like [short.io](https://short.io/) or [bitly](https://bitly.com)) is highly recommended so that you can easily renew your subscriptions at any time without having to modify the configuration again.

Basic proxy-groups and rules are already included in the configuration. You need to **simply fill in your subscription urls or shortened urls in the rule-providers field**, if necessary, modify the proxy-groups and rules, then import into clash and just start enjoying surfing :)

### Attention for ss type subscriptions
If you are using a ShadowSocks (ss) type subscription, to get a proper yaml file rather than encoded sting, you may need to add this string `&flag=clash` at the end of the url. Otherwise, clash may get errors while updating.
