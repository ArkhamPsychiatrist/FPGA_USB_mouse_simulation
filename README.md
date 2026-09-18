# FPGA_USB_mouse_simulation

A USB mouse implemented from scratch on an FPGA using the USB3300 ULPI transceiver. Full USB enumeration is handled by state machines written in Verilog.

## Modules
- `ULPI_Packet_Parser`, `ULPI_read_register`, `ULPI_write_register`: ULPI interface
- `USB_state_machine`, `Endpoint_0`, `Interrupt_Endpoint`: enumeration and endpoints
- `DeviceDescriptorModule`, `ConfigurationDescriptorModule`: USB descriptors
- `Top`, `mux`: top-level integration
