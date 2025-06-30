# DPI Checkers
🚀 This repository contains checkers that allow you to determine if your “home” ISP has DPI, as well as the specific methods the censor uses for limitations.

## Checkers list
- **RU :: TCP 16-20** => [https://hyperion-cs.github.io/dpi-checkers/ru/tcp-16-20](https://hyperion-cs.github.io/dpi-checkers/ru/tcp-16-20)<br>
Allows to detect TCP 16-20 blocking method in Russia. The tests use publicly available APIs of popular services hosted by providers whose subnets are potentially subject to limitations. The testing process runs right in your browser and the source code is available. VPN should be disabled during the check.<br>
See [here](https://github.com/net4people/bbs/issues/490) for more details.

- **RU :: TCP 16-20 [CUSTOM]** => You can pass custom address to check (for example, your steal-oneself page) via url path params: `.../ru/tcp-16-20/?url=custom-testing-page.html`. Testing `custom-testing-page.html` should allow cross-origin requests and be more than 128 Kb sized.


## Contributing
We would be happy if you could help us improve our checkers through PR or by creating issues.
Also you can star the repository so you don't lose the checkers.
The repository is available [here](https://github.com/hyperion-cs/dpi-checkers).
