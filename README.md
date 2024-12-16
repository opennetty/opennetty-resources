# OpenNetty resources

This repository contains various resources for the OpenNetty project, including compiled binaries of the OpenNetty daemon.

## Compiled binaries

Compiled binaries of the OpenNetty daemon can be found in the [releases](releases/) folder.

> [!NOTE]
> These binaries are self-contained .NET applications that embed all the required dependencies so you don't
> have to install any global package on the machine on which OpenNetty is deployed.

> [!TIP]
> Make sure you select the correct architecture when downloading the compiled binaries:
>   - x64: typically used for bare metal and virtual machines.
>   - ARM32: compatible with Single Board Computers (like Raspberry PIs) that don't support 64 bits.
>   - ARM64: best used for Single Board Computers that support 64 bits (e.g Raspberry PIs 3+ on which Raspbian 64 bits is installed).

For more information on how to deploy these binaries, read [the documentation in the main repository](https://github.com/opennetty/opennetty-core).

--------------

## Templates for Jeedom's jMQTT plugin

JSON templates for Jeedom's [jMQTT plugin](https://market.jeedom.com/index.php?v=d&p=market_display&id=3166) can be found in the
[jMQTT](jMQTT/) folder and can be used to quickly create light (dimmable or not), pilot wire or smart meter equipments in Jeedom.

> [!NOTE]
> Support for additional languages or devices will be progressively added depending on the demand.

--------------

## Security policy

Security issues and bugs should be reported privately by emailing contact@kevinchalet.com.
You should receive a response within 24 hours. If for some reason you do not, please follow up via email to ensure we received your original message.

--------------

## Contributors

**OpenNetty** is actively maintained by **[Kévin Chalet](https://github.com/kevinchalet)**. Contributions are welcome and can be submitted using pull requests.

--------------

## License

This project is licensed under the **Apache License**. This means that you can use, modify and distribute it freely.
See [http://www.apache.org/licenses/LICENSE-2.0.html](http://www.apache.org/licenses/LICENSE-2.0.html) for more details.
