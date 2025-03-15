# Wireless and Device-to-Device Communication Security Labs

![polito](resources/logo_polito.jpg)

This repository contains the material for the two main labs of the **Wireless and Device-to-Device Communication Security** course at **Politecnico di Torino**. The labs covered in this repository are:

- **WiFi Lab:** Focuses on wireless network performance, monitoring, and security.
- **GNSS Lab:** Focuses on Global Navigation Satellite Systems and related security issues.

Both lab **reports** are maintained as submodules that link directly to their respective repositories under the **WDCSecure** organization.  
The actual **lab materials** are contained within this repository.

> [!IMPORTANT]  
> The submodules in this repository (**`LabWiFi`** and **`LabGNSS`**) are currently private repositories.  
> This means that unless you have access to the WDCSecure organization, you won't be able to clone them.

## Submodules

This repository includes submodules for the **lab reports**, while the **lab materials** are directly stored here.

- [**`LabWiFi`**](https://github.com/WDCSecure/LabWiFi)**:** Contains the report for the WiFi Lab.
- [**`LabGNSS`**](https://github.com/WDCSecure/LabGNSS)**:** Contains the report for the GNSS Lab.

> [!NOTE]  
> The submodule links redirect to the WDCSecure organization repositories, which contain the lab reports.  
> Each lab has its own dedicated `README` ([**`LabWiFi/README.md`**](https://github.com/WDCSecure/LabWiFi/blob/main/README.md) and [**`LabGNSS/README.md`**](https://github.com/WDCSecure/LabGNSS/blob/main/README.md)) with specific details.

## Cloning the Repository with Submodules

When cloning this repository, make sure to include the submodules. You can do this in one of two ways:

### Option 1: Clone with Submodules in a Single Command

```bash
git clone --recurse-submodules https://github.com/eliainnocenti/WD2DCS-Laboratories.git
```

### Option 2: Initialize Submodules After Cloning

If you have already cloned the repository without submodules, initialize and update them with:

```
git submodule update --init
```
