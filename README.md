# Zest_Interface_RS485

Zest_Interface_RS485 board support for Zephyr OS. This support is compatible with the Zest_Interface_RS485 and the Zest_Interface_RS485_Isolated boards.

## Usage

:pushpin: This shield defines:

- an RS232 interface: `uart_zest_interface_rs485_port` to `sixtron_connector_<port>_uart`.

:triangular_ruler: To use this shield:

- Update your device tree by adding the `ZEST_INTERFACE_RS485(port)` macro to the `app.overlay` file.\
  Replace `port` with the number of the Zest_Core port to which the shield is connected, e.g.:

  ```c
  ZEST_INTERFACE_RS485(1) /* Zest_Interface_RS485 connected to Zest_Core first port */
  ```

- Activate support for the shield by adding `--shield zest_interface_rs485` to the west command.
