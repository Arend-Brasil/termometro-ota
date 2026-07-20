# Termômetro DWL — Firmware OTA

Repositório público de distribuição de firmware para atualização OTA automática.

Dois modelos de hardware, binários e chaves de manifesto separados —
um binário C6 (RISC-V) não roda em hardware S3 (Xtensa) e vice-versa.

| Arquivo | Descrição |
|---|---|
| `modelo1-c6/firmware.bin` | Binário mais recente do Modelo 1 (ESP32-C6) |
| `modelo2-s3/firmware.bin` | Binário mais recente do Modelo 2 (ESP32-S3-AMOLED) |
| `firmware_manifest.json` | Manifesto único com chaves prefixadas `modelo1_c6_*`/`modelo2_s3_*` (version, firmware_url, sha256, notes) |

O código-fonte está em repositório privado separado.
