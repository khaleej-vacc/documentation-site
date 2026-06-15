---
title: Euroscope Setup
---

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
  <iframe src="https://www.youtube.com/embed/MlV7Lu5gzgk?start=1"
          style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen>
  </iframe>
</div>

## Setting up DCL/PDC

!!! note "Use of DCL/PDC"
    All controllers **__must__** have DCL/PDC available to use when controlling Hamad Intl. (OTHH) and Bahrain Intl. (OBBI).

<p style="text-align: centre; font-style: italic;">
Figure 1.1
</p>
![PDC1](img/PDC1.png)

- Navigate to the Radar View and select **CPDLC Settings** under **Setup** as highlighted above.

<p style="text-align: centre; font-style: italic;">
Figure 1.2
</p>
![PDC2](img/PDC2.png)

- Under **Logon Code**, controllers must insert their Hoppie Logon code. If you do not have an account with Hoppie ACARS, please make one [here](https://www.hoppie.nl/acars/system/register.html).
- All controllers APP or below must ensure that **CPDLC** is offline. **Only PDC/DCL should be enabled.**

!!! note "Auto Mode"
    When controlling Bahrain Intl. (OBBI), Auto mode **must** be disabled. This is due to the fact that Bahrain has no published SIDs and a heading must be selected instead.
