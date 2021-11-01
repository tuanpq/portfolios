# Description
Application that simulates Body Measurement devices for testing data exchanged via BLE technology.

## How to use

#### Step 1: Choose a device

![alt text](https://github.com/tuanpq/static/blob/master/med/images/iOS_MED_1.png "Choose a device")

#### Step 2: Start advertising and wait a central scan & connect

![alt text](https://github.com/tuanpq/static/blob/master/med/images/iOS_MED_2.png "Start advertising and wait a central scan & connect")

#### Step 3: Input measured values

![alt text](https://github.com/tuanpq/static/blob/master/med/images/iOS_MED_3.png "Input measured values")

#### Step 4: Notify values

![alt text](https://github.com/tuanpq/static/blob/master/med/images/iOS_MED_4.png "Notify values")

# Specifications
[Microchip UART Transparent Mode](https://microchipdeveloper.com/wireless:ble-mchp-transparent-uart-service)

[Body Measurement Device AD-6351](https://www.aandd.co.jp/pdf_storage/manual/me/m_ad6351.pdf)

# Technical stack
Foundation | Dispatch | UIKit | CoreBluetooth
--- | --- | --- | ---
Timer | DispatchQueue | UIScrollView, UITableView, UIStackView, Auto Layout | BLE Peripheral
NSCache |  | UILabel, UIImageView, UITextField, UISwitch, UIButton, UITextView |
