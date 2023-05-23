<a href="https://pika-spark.io/"><img align="right" src="https://raw.githubusercontent.com/pika-spark/.github/main/logo/logo-pika-spark-bg-white.png" width="15%"></a>
:sparkles: `pika-spark-sh2`
===========================
[![Smoke test status](https://github.com/pika-spark/pika-spark-sh2/actions/workflows/smoke-test.yml/badge.svg)](https://github.com/pika-spark/pika-spark-sh2/actions/workflows/smoke-test.yml)
[![Spell Check status](https://github.com/pika-spark/pika-spark-sh2/actions/workflows/spell-check.yml/badge.svg)](https://github.com/pika-spark/pika-spark-sh2/actions/workflows/spell-check.yml)

Actively maintained sensor hub driver for interfacing with [BNO085](https://www.ceva-dsp.com/wp-content/uploads/2019/10/BNO080_085-Datasheet.pdf).

Made for integration with [`pika-spark-bno085-driver`](https://github.com/pika-spark/pika-spark-bno085-driver), a Linux user space driver for the BNO085 9-DoF IMU driver.

<p align="center">
  <a href="https://pika-spark.io/"><img src="https://raw.githubusercontent.com/pika-spark/.github/main/logo/logo-pika-spark-bg-white-github.png" width="40%"></a>
</p>

### How-to-build
```bash
git clone https://github.com/107-systems/pika-spark-sh2 && cd pika-spark-sh2
mkdir build && cd build
cmake .. && make
```
