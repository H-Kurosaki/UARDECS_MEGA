# UARDECS_MEGA

UARDECS is a library for implementing a protocol based on "UECS", a communication standard for Japanese horticulture. This library greatly increases the items that can be set in the advanced version of UARDECS, but memory consumption has also increased, so operation cannot be guaranteed on anything less than an Arduino MEGA.

To run this library you need an Ethernet shield based on the **W5500** chip, such as the Arduino Ethernet Shield 2. The library depends on the **Ethernet2** library. When you install UARDECS_MEGA through the Arduino Library Manager (Arduino IDE 1.8.10 or newer), the Library Manager will offer to install Ethernet2 automatically. If you install the library manually, please install the Ethernet2 library as well.

> **Note:** As of v2.0.3, support for the older W5100-based shields (and the standard `Ethernet.h` library) has been discontinued. Please use a W5500-based shield with the Ethernet2 library.

---

UARDECSは日本の施設園芸用の通信規格である"UECS"準拠のプロトコルをArduinoに実装するためのライブラリです。このライブラリはUARDECSの高機能バージョンで、設定できる項目が大幅に増えていますが、メモリの消費量も増えているためArduino MEGAでなければ動作は保証できません。

このライブラリを実行するには、Arduino Ethernet Shield 2 などの **W5500** チップを搭載したEthernetシールドが必要です。本ライブラリは **Ethernet2** ライブラリに依存しています。Arduino Library Manager（Arduino IDE 1.8.10以降）経由でUARDECS_MEGAをインストールすると、Ethernet2も併せてインストールするよう自動的に案内されます。手動でインストールする場合は、Ethernet2ライブラリも一緒にインストールして下さい。

> **注意:** v2.0.3より、旧来のW5100系シールド（および標準の `Ethernet.h` ライブラリ）のサポートを打ち切りました。W5500系のシールドとEthernet2ライブラリを使用して下さい。

---

詳細なマニュアル(日本語版)は以下で提供されます。
https://github.com/H-Kurosaki/UARDECS_Documents
