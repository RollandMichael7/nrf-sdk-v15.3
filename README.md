# nrf-sdk-v15.3
A *very* slightly modified version of [Nordic's NRF SDK v15.3](https://developer.nordicsemi.com/nRF5_SDK/nRF5_SDK_v15.x.x/nRF5_SDK_15.3.0_59ac345.zip) to accomodate services with more than 6 characteristics (such as the Thingy:52s motion service).

# Changes
- ```components/ble/common/ble_gatt_db.h```
  - Changed BLE_GATT_DB_MAX_CHARS from 6 to 10.
