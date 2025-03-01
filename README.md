[![Discord](https://img.shields.io/discord/478725473862549535.svg)](https://discord.gg/gCyBu8T)

![nanoFramework logo](https://github.com/nanoframework/Home/blob/main/resources/logo/nanoFramework-repo-logo.png)

-----
Document Language: [English](README.md) | [简体中文](README.zh-cn.md)

## Welcome to the **nanoFramework** team code samples repository!

This repo contains code samples used by the team when testing, working on proof of concepts for new and improved features and other explorational endeavours.
Feel free to browse, take what you like and contribute back if you want.

> Note: sometimes it's convenient to reference the source code instead of the NuGet packages in projects that require debugging by following the execution flow into other projects or even class libraries. For that we recommend using a very handy Visual Studio extension that allows NuGet assembly references to project references switching. That's [NuGet Reference Switcher](https://github.com/rsuter/NuGetReferenceSwitcher).

If you are looking for Iot.Device samples, they are all in the [Iot.Device repository](https://github.com/nanoFrameork/nanoFramewok.IoT.Device).

## Sample by category

<devices>

### Special beginner

* [Blink your first led](samples/Blinky)
* [System.Device.Pwm](samples/PWM/System.Device.Pwm)

### Gpio, I2C, Spi, Pwm, Adc, Dac, 1-Wire, Serial

* [1-Wire sample](samples/1-Wire)
* [Analogic/Digital converter](samples/ADC)
* [Blink your first led](samples/Blinky)
* [Digital Analog Converter sample](samples/DAC)
* [GPIO and events sample](samples/Gpio/Gpio+Events)
* [GPIO and events sample (.NET IoT style)](samples/Gpio/Gpio+EventsIoTStyle)
* [GPIO sample pack](samples/Gpio)
* [I2C GPS sample](samples/I2C/System.Device.I2c/GPS)
* [I2C sample sample pack](samples/I2C)
* [I2C Scanner sample](samples/I2C/NanoI2cScanner)
* [System.Device.Pwm](samples/PWM/System.Device.Pwm)
* [System.Device.PWM sample](samples/PWM)
* [System.Device.Spi sample](samples/SPI)
* [System.IO.Ports serial Communication sample](samples/SerialCommunication)
* [Using Azure SDK with BMP280 on M5Stack with .NET nanoFramework](samples/AzureSDK/AzureSDKSensorCertificate)

### AMQP

* [AMQP sample pack](samples/AMQP)
* [Azure AMQP sample](samples/AMQP/Azure-IoT-Hub)
* [Azure Service Bus AMQP sample](samples/AMQP/Azure-ServiceBus-Sender)

### Azure specific

* [AMQP sample pack](samples/AMQP)
* [Azure AMQP sample](samples/AMQP/Azure-IoT-Hub)
* [Azure Edge OTA example](samples/AzureSDK/AzureEdgeOta)
* [Azure IoT Device Provisioning Service (DPS) example](samples/AzureSDK/DpsSampleApp)
* [Azure IoT Hub SDK with MQTT protocol](samples/AzureSDK/AzureSDK)
* [Azure IoT Plug & Play with MQTT protocol](samples/AzureSDK/AzureIoTPnP)
* [Azure SDK sample pack](samples/AzureSDK)
* [Azure Service Bus AMQP sample](samples/AMQP/Azure-ServiceBus-Sender)
* [Complete Azure MQTT sample using BMP280 sensor with Azure lib](samples/AzureSDK/AzureSDKSleepBMP280)
* [Complete Azure MQTT sample using BMP280 sensor without Azure lib](samples/AzureMQTTTwinsBMP280Sleep)
* [HTTP.HttpAzureGET Sample](samples/HTTP/HttpAzureGET)
* [HTTP.HttpAzurePOST Sample](samples/HTTP/HttpAzurePOST)
* [Using Azure SDK with BMP280 on M5Stack with .NET nanoFramework](samples/AzureSDK/AzureSDKSensorCertificate)

### Bluetooth

* [Bluetooth Low Energy Serial profile sample](samples/Bluetooth/BluetoothLESerial)
* [Bluetooth Low energy: adding, replacing services to the main service](samples/Bluetooth/BluetoothLESample3)
* [Bluetooth Low energy: read static and dynamic values, notification, read/write value](samples/Bluetooth/BluetoothLESample1)
* [Bluetooth Low energy: read/write with encryption a value](samples/Bluetooth/BluetoothLESample2)
* [Bluetooth samples](samples/Bluetooth)

### CAN

* [CAN sample](samples/CAN)

### ESP32 specific

* [Bluetooth samples](samples/Bluetooth)
* [Complete Azure MQTT sample using BMP280 sensor with Azure lib](samples/AzureSDK/AzureSDKSleepBMP280)
* [Complete Azure MQTT sample using BMP280 sensor without Azure lib](samples/AzureMQTTTwinsBMP280Sleep)
* [Hardware ESP32 Deep sleep sample](samples/Hardware.Esp32)
* [Hardware ESP32 RMT sample pack](samples/Hardware.Esp32.Rmt)
* [NeoPixel Strip WS2812 with RMT](samples/Hardware.Esp32.Rmt/NeoPixelStrip)
* [NeoPixel Strip WS2812 with RMT low memory](samples/Hardware.Esp32.Rmt/NeoPixelStripLowMemory)
* [Ultrasonic HC-SR04 sensor with RMT](samples/Hardware.Esp32.Rmt/Ultrasonic)

### File and storage access

* [System.IO.FileSystem samples](samples/System.IO.FileSystem)
* [Windows.Storage sample pack](samples/Storage)

### Graphics for screens

* [Graphics Primitives](samples/Graphics/Primitives)
* [Graphics samples](samples/Graphics)
* [Screen samples](samples/Graphics/Screens)
* [Simple WPF](samples/Graphics/SimpleWpf)
* [Tetris Demo Game for nanoFramework](samples/Graphics/Tetris)

### IoT.Device

* [Complete Azure MQTT sample using BMP280 sensor with Azure lib](samples/AzureSDK/AzureSDKSleepBMP280)
* [Complete Azure MQTT sample using BMP280 sensor without Azure lib](samples/AzureMQTTTwinsBMP280Sleep)
* [Using Azure SDK with BMP280 on M5Stack with .NET nanoFramework](samples/AzureSDK/AzureSDKSensorCertificate)

### Interop

* [Interop sample](samples/Interop)
* [Native events sample](samples/NativeEvents)

### Json

* [nanoFramework Json sample](samples/Json)

### MQTT

* [Complete Azure MQTT sample using BMP280 sensor without Azure lib](samples/AzureMQTTTwinsBMP280Sleep)
* [MQTT sample pack](samples/MQTT)

### Networking including HTTP, SSL

* [.NET **nanoFramework** Webserver sample pack](samples/Webserver)
* [HTTP Listener sample](samples/HTTP/HttpListener)
* [HTTP sample pack](samples/HTTP)
* [HTTP WebRequest sample](samples/HTTP/HttpWebRequest)
* [HTTP.HttpAzureGET Sample](samples/HTTP/HttpAzureGET)
* [HTTP.HttpAzurePOST Sample](samples/HTTP/HttpAzurePOST)
* [MQTT sample pack](samples/MQTT)
* [Networking sample pack](samples/Networking)
* [TLS sample pack](samples/SSL)
* [UdpClient sample pack](samples/UdpClient)
* [WebSocket Client Sample](samples/WebSockets/WebSockets.Client.Sample)
* [WebSocket Client Sample](samples/WebSockets/Websockets.ServerClient.Sample)
* [WebSocket sample pack](samples/WebSockets)
* [WebSocket Server Sample](samples/WebSockets/WebSockets.Server.RgbSample)
* [WiFI samples](samples/Wifi)
* [Wifi Soft AP sample](samples/WiFiAP)

### Real Time Clock

* [RTC sample](samples/RTC)

### STM32 Specific

* [Hardware STM32 sample pack](samples/Hardware.Stm32)
* [STM32 Alarm](samples/Hardware.Stm32/Stm32.TestAlarms)
* [STM32 Backup Memory](samples/Hardware.Stm32/Stm32.BackupMemory)
* [STM32 Power Mode](samples/Hardware.Stm32/Stm32.PowerMode)
* [STM32 Read Device ID](samples/Hardware.Stm32/Stm32.ReadDeviceIDs)

### Texas Instrument specific

* [Hardware TI SimpleLink sample pack](samples/Hardware.TI)
* [Texas Instruments EasyLink sample pack](samples/TI.EasyLink)
* [TI Power Mode](samples/Hardware.TI/TI.PowerMode)
* [TI utilities](samples/Hardware.TI/TI.Utilities)

### Tools and utilities

* [Dependency injection sample pack](samples/DependencyInjection)
* [Logging samples](samples/Logging)
* [Unit Test framework sample pack](samples/UnitTest)

### System related

* [Collections sample](samples/Collections)
* [Convert Base64 sample pack](samples/Converter.Base64)
* [Debug Garbage Collector Test](samples/DebugGC.Test)
* [Execution Constraint demo](samples/ExecutionConstraint)
* [GC stress test](samples/GCStressTest)
* [GPIO and events sample](samples/Gpio/Gpio+Events)
* [GPIO and events sample (.NET IoT style)](samples/Gpio/Gpio+EventsIoTStyle)
* [Interop sample](samples/Interop)
* [Managed resources sample](samples/ManagedResources)
* [Native events sample](samples/NativeEvents)
* [Number Parsing sample pack](samples/NumberParser)
* [Reflection sample pack](samples/Reflection)
* [RTC sample](samples/Timer)
* [System.Random sample](samples/System.Random)
* [Threading sample pack](samples/Threading)
* [ToString samples](samples/ToStringTest)

### Wifi

* [WiFI samples](samples/Wifi)
* [Wifi Soft AP sample](samples/WiFiAP)

</devices>

## Feedback and documentation

For documentation, providing feedback, issues and finding out how to contribute please refer to the [Home repo](https://github.com/nanoframework/Home).

Join our Discord community [here](https://discord.gg/gCyBu8T).

## Credits

The list of contributors to this project can be found at [CONTRIBUTORS](https://github.com/nanoframework/Home/blob/main/CONTRIBUTORS.md).

## License

The **nanoFramework** samples are licensed under the [MIT license](LICENSE.md).

## Code of Conduct

This project has adopted the code of conduct defined by the Contributor Covenant to clarify expected behavior in our community.
For more information see the [.NET Foundation Code of Conduct](https://dotnetfoundation.org/code-of-conduct).

### .NET Foundation

This project is supported by the [.NET Foundation](https://dotnetfoundation.org).
