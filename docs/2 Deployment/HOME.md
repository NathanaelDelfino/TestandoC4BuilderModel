# 2 Deployment

![diagram](https://www.plantuml.com/plantuml/svg/0/rLRVJzim47v7ud-uzMM0e1qLcj2UAEt6G9HMf8nDceGkjjjwE7PaEmKsyR_lBca9PKKQx6bvgEBhVVVZkpjV3a947ulCmA6U7AAztkcftBYxJDcuqtKsgjlOpEd_zRKtsWfJI0NJ6FFmeTNoUDESw3WjqY8eBrZPngPmMGkbrsXdfiYBLdTlPsZGnel-QSjWL26IwAhsChU-ldRQ-JQu65rT7ey-Nvr-FFfurjlOP7cjUdNcfDh8ZTY61eKB72_GiV7a318ZWY24yetDN-jhGCzJCz8IAjMJb9F6N6zjRNsFj_jiwo8jR2nWzttptHwSZf876wliO8vYgWZLALzWv3A1iV5K0FlDsoKx_331gAtoP4KpOdWCdJmtcW3QMJPoWZC4j1AIt6ixWVwNBek7tisqL06EEKchOfayAumBAnYCHiSxc6b2mqaoE6jz7es62P2BPcEp3kE-UhrVJTAS7vc-stt45XzVp9FpA0ppD2XVO0U6NcVexngrRBSjdkUebsx8b7HxLDmKWsBSkJ9O9GiBCIH4UeRyRnAT9uguEy6hYGxHbzgWxTZvh7pVXYc6gPA0HPnIi7FgGNWb-OWcR0CAeK80uoPqK56yYi7sCeFjLpBOVanXecZiv4j9RFz_BAQFsRjHQJMjUw-SrlQ_ZYj5G8XBbVxbkFQKqJFb0n0xG5Sk4GJp2xFKPl4VanpeX-gPuqG1rcwUeUr-rLsPEOwpMuJeCkNV1Y219fjIpRHGLTOvdOy72JWF7Ikzq_8XyJhX2aVw_Se0mHZz5Mc2jLswaH2CpdIaPWX56YWVDrwTt_9D5Hs8UPoXlBO8e_rom6NgAnEbhPClPygIWXS01wrfFGKtZd2fhNGtWMEgCizG399dbqJgILdvUQqFgnDRF7AEQzETUdAt3NttKnk3y4bxDNRBdLEJ67BaUQhAEkIohkYUH7YTLrtHiPF2e5zcrvX_8vHQ5-PfFNJIedte8dYeTBMH-dXDJdal2V9C_UiucX_1sMgVi0L6bQcz35BEK4L9FHwkp4pKPNmKxW9OkYbNmRb26M1CDIZvkl7KTWk79xt3xXD4-mKGjhz0L3KYjVAxWdJBxv83PILzklm6)

**Deployment diagram**

A deployment diagram allows you to illustrate how containers in the static model are mapped to infrastructure. This deployment diagram is based upon a UML deployment diagram, although simplified slightly to show the mapping between containers and deployment nodes. A deployment node is something like physical infrastructure (e.g. a physical server or device), virtualised infrastructure (e.g. IaaS, PaaS, a virtual machine), containerised infrastructure (e.g. a Docker container), an execution environment (e.g. a database server, Java EE web/application server, Microsoft IIS), etc. Deployment nodes can be nested.

**Scope**: A single software system.

**Primary elements**: Deployment nodes and containers within the software system in scope.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.