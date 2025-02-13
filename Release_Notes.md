---
pagetitle: Release Notes for LSM6DSV16X Component
lang: en
header-includes: <link rel="icon" type="image/x-icon" href="_htmresc/favicon.png" />
---

::: {.row}
::: {.col-sm-12 .col-lg-4}

<center>
# Release Notes for LSM6DSV16X Component Driver
Copyright &copy; 2022 STMicroelectronics\

[![ST logo](_htmresc/st_logo_2020.png)](https://www.st.com){.logo}
</center>

# License

This software component is licensed by ST under BSD 3-Clause license, the "License".
You may not use this component except in compliance with the License. You may obtain a copy of the License at:

[BSD 3-Clause license](https://opensource.org/licenses/BSD-3-Clause)

# Purpose

This directory contains the LSM6DSV16X component drivers.
:::

::: {.col-sm-12 .col-lg-8}
# Update history

::: {.collapse}
<input type="checkbox" id="collapse-section1" aria-hidden="true">
<label for="collapse-section1" aria-hidden="true">V1.0.0 / 03-Aug-2022</label>
<div>			

## Main changes

### First release

- First official release [ref. DS v1.0]

##

</div>

<input type="checkbox" id="collapse-section2" aria-hidden="true">
<label for="collapse-section2" aria-hidden="true">V2.0.0 / 22-Nov-2022</label>
<div>

## Main changes

- First official release [ref. DS v2.0]

##

</div>

<input type="checkbox" id="collapse-section3" aria-hidden="true">
<label for="collapse-section3" aria-hidden="true">V2.1.0 / 15-May-2023</label>
<div>

## Main changes

- change fifo_batch_sh_slave_xxx() API name
- sensor_hub: add sh_status_get() API
- sensor_hub: change sh_read_data_raw_get() API signature
- review read/write reg ret value checks

##

</div>

<input type="checkbox" id="collapse-section4" aria-hidden="true">
<label for="collapse-section4" aria-hidden="true">V2.1.1 / 18-May-2023</label>
<div>

## Main changes

- read sh status from mainpage

##

</div>

<input type="checkbox" id="collapse-section5" aria-hidden="true">
<label for="collapse-section5" aria-hidden="true">V2.2.0 / 23-May-2023</label>
<div>

## Main changes

- Use a single lsm6dsv16x_sh_slv_cfg_read() API for all targets
- Use a single lsm6dsv16x_fifo_sh_batch_slave_xxx() API for all targets
- Fix MISRA errors

##

</div>

<input type="checkbox" id="collapse-section6" checked aria-hidden="true">
<label for="collapse-section6" aria-hidden="true">V2.2.1 / 25-July-2023</label>
<div>

## Main changes

- ah_qvar: Add API to convert from LSB to mV
- Fix gyro FS 4000dps value typo error

##

</div>
:::

:::
:::

<footer class="sticky">
::: {.columns}
::: {.column width="95%"}
For complete documentation on LSM6DSV16X,
visit:
[LSM6DSV16X](https://www.st.com/content/st_com/en/products/mems-and-sensors/inemo-inertial-modules/lsm6dsv16x.html)
:::
::: {.column width="5%"}
<abbr title="Based on template cx566953 version 1.0">Info</abbr>
:::
:::
</footer>
