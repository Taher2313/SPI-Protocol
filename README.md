# SPI-Protocol

The implementation includes the following components:

- Master
- Slave
- Integration of a Master with 3 Slaves in a Regular Multi-slave mode.
- Self-Checking Testbenches for the Master, Slave, and Integration.

## Modes of Operation

The SPI protocol supports four modes of operation, including:

- Mode 0 (CPOL=0, CPHA=0): The clock polarity is low, and data is sampled on the leading (first) clock edge.
- Mode 1 (CPOL=0, CPHA=1): The clock polarity is low, and data is sampled on the trailing (second) clock edge.
- Mode 2 (CPOL=1, CPHA=0): The clock polarity is high, and data is sampled on the leading (first) clock edge.
- Mode 3 (CPOL=1, CPHA=1): The clock polarity is high, and data is sampled on the trailing (second) clock edge.

