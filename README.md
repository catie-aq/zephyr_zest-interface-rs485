# Zest_Interface_RS485

Zest_Interface_RS485 board support for Zephyr OS. This support is compatible with the Zest_Interface_RS485 and the Zest_Interface_RS485_Isolated boards.

## Usage

The UART node label is exposed by the overlay, allowing to use the RS485 interface with the default 6TRON uart interface (`sixtron_uart`).

> [!NOTE]
> The node label for the uart component is `zest_interface_rs485_uart`. \
> Shield name: `zest_interface_rs485`.
