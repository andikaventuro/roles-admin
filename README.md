# Permissions Table

## Overview
This document outlines the permissions for various roles including SuperAdmin, CustomerService, and TechnicalSupport across different functionalities.

## Permissions Breakdown

| Permission                   | SuperAdmin | CustomerService | TechnicalSupport |
|------------------------------|------------|-----------------|------------------|
| dashboard:read               | ✔️         | ✔️              | ✔️               |
| userkorlantas:read           | ✔️         | ✔️              | ✔️               |
| userkorlantas:update         | ✔️         |                 | ✔️               |
| statusperpanjangansim:read   | ✔️         | ✔️              | ✔️               |
| statusperpanjangansim:update | ✔️         | ✔️              | ✔️               |
| statuspembayaran:read        | ✔️         | ✔️              | ✔️               |
| rating:read                  | ✔️         | ✔️              | ✔️               |
| role:read                    | ✔️         |                 |                  |
| logaktivitas:read            | ✔️         | ✔️              | ✔️               |
| manajemenversi:read          | ✔️         | ✔️              | ✔️               |
| manajemenversi:create        | ✔️         |                 | ✔️               |
| manajemenversi:update        | ✔️         |                 | ✔️               |
| manajemenversi:delete        | ✔️         |                 | ✔️               |
| anomaliregistrasi:read       | ✔️         |                 | ✔️               |
| anomaliregistrasi:update     |            |                 | ✔️               |
| settings:read                | ✔️         |                 |                  |
| settings:update              | ✔️         |                 |                  |
| cekstatus:read               | ✔️         | ✔️              | ✔️               |
| manualexpired:read           | ✔️         |                 | ✔️               |
| manualexpired:update         | ✔️         |                 | ✔️               |
| polsatpas:read               |            |                 | ✔️               |
| polsatpas:update             |            |                 | ✔️               |
| polsatpas:create             |            |                 | ✔️               |
| pushnotifikasi:read          |            |                 | ✔️               |
| pushnotifikasi:update        |            |                 | ✔️               |
| pushnotifikasi:create        |            |                 | ✔️               |
| pushnotifikasi:delete        |            |                 | ✔️               |

## Notes
- **✔️** indicates the permission is granted for the specific role.
- This table helps visualize which permissions are assigned to each role, aiding in managing and understanding the access controls for each type of user.

Feel free to adjust or add more permissions as needed!
