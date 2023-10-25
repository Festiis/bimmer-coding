# 360A-LicLciColorLibrary

This color library defines both factory and custom colors used for coding BMW's 360A-LicLci system. It includes HEX values, byte positions, and any custom color replacements.

## Factory Colors

- **BRONZE**: 
  - HEX: \#D76E14
  - Byte Positions: 18,19,20 | 23,24,25 | 28,29,30

- **ORANGE**:
  - HEX: \#931A01
  - Byte Positions: 33,34,35 | 38,39,40

- **WHITE**: The factory-defined white color.

- **BLUE**:
  - HEX: \#00AAFE
  - Byte Positions: 48,49,50 | 53,54,55 | 58,59,60

- **GREEN**:
  - HEX: \#10FE32
  - Byte Positions: 63,64,65 | 68,69,70 | 73,74,75

- **LILAC**:
  - HEX: \#783CFE
  - Byte Positions: 78,79,80 | 83,84,85 | 88,89,90

## Custom Colors

- **BRONZE** => **RED**:
  - HEX: \#FE0000

- **ORANGE**: The factory-defined orange color.

- **WHITE**: The factory-defined white color.

- **BLUE** => **G30 BLUE**:
  - HEX: \#0042FE

- **GREEN** => **AQUA**:
  - HEX: \#00FEFE

- **LILAC** => **DEEPPINK**:
  - HEX: \#FE1493

- **Custom Color String**:
  ```
  00, 1A, 01, 90, E0, 90, FF, 02, 90, E0, 90, 00, 03, 90, E0, 90, FF, 01, FE, 00, 00, FF, 02, FE, 00, 00, 00, 03, FE, 00, 00, FF, 01, 93, 1A, 01, FF, 02, 93, 1A, 01, 00, 03, 93, 1A, 00, FF, 01, 00, 42, FE, FF, 02, 00, 42, FE, 00, 03, 00, 42, FE, FF, 01, 00, FE, FE, FF, 02, 00, FE, FE, 00, 03, 00, FE, FE, FF, 01, FE, 14, 93, FF, 02, FE, 14, 93, 00, 03, 78, 3C, FE, FF, 02, 00, 00, 00, FE, 01, 96, 00, 00, FF, 02, 96, 00, 00, 00, 01, 00, B0, 60, FF, 02, 00, B0, 60, 00, 01, 00, 00, 00, FF, 02, 00, 00, 00, 00, 03, 00, 00, 00, FF, FF, FF, FF, FF, FF, FF, FF, FF, FF, FF, FF, FF, FF, FF, FF, FF, FF, FF, FF, FF
  ```

## Note 
  - BMW's ambient lighting system may not handle `FF` for custom colors; using `FE` is recommended to ensure the color is displayed correctly.

