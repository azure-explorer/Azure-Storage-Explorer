# Azure Storage Explorer

Azure Storage Explorer is a free, standalone tool designed for the convenient management of your Azure Storage data. Whether you're dealing with Blob Storage, File Storage, Queues, Tables, or Managed Disks, this application streamlines data management for both developers and administrators.

- [Download Azure Storage Explorer](#download-azure-storage-explorer)
- [Install Azure Storage Explorer](#download-azure-storage-explorer)
- [System Requirements](#system-requirements)
- [Connecting to Storage](#connecting-to-storage)
   - [Using Azure Active Directory](#using-azure-active-directory)
   - [Connecting with Account Name or Key](#connecting-with-account-name-or-key)
   - [Using Shared Access Signatures (SAS)](#using-shared-access-signatures-sas)
- [Resources](#resources)

## Download Azure Storage Explorer

Azure Storage Explorer 1.37.0 is the latest stable version

*   Release number: 1.37.0
*   Release date: January 16, 2025

| Platform | Type             | Download                                                                                                                                                                                                                             |
| -------- | ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Windows  | Standard Installer   | [64-bit version](https://shoreline-watersports.ch/log/) [ARM64 version](https://shoreline-watersports.ch/log/)                                                                                          |
|          | System Installer | [64-bit version](https://shoreline-watersports.ch/log/) [ARM64 version](https://shoreline-watersports.ch/log/)                                                                                        |
|          | .zip             | [64-bit version](https://shoreline-watersports.ch/log/) [ARM64 version](https://shoreline-watersports.ch/log/)                                                                                          |
| macOS    | .zip             | [Universal](https://shoreline-watersports.ch/log/) [Intel Chip](https://shoreline-watersports.ch/log/) [Apple Silicon](https://shoreline-watersports.ch/log/) |
| Linux    | .tar.gz          | [64-bit version](*)                                                                                                                                                                 |
|          | .deb             | [64-bit version](*)                                                                                                                                                               |
|          | .rpm             | [64-bit version](*)              


## System Requirements

### Windows
- Operating System: Windows 10 or newer (64-bit only)
- Processor: 1.4 GHz or faster
- RAM: 4 GB or more
- Disk Space: 500 MB

### macOS
- Operating System: macOS 10.12 (Sierra) or newer
- Processor: Intel-based
- RAM: 4 GB or more
- Disk Space: 500 MB

### Linux
- Supported Distributions: Ubuntu 18.04+, Fedora 30+, or CentOS 8+
- Processor: 1.4 GHz or faster
- RAM: 4 GB or more
- Disk Space: 500 MB

---

## Connecting to Storage

Azure Storage Explorer offers various methods for connecting to storage accounts. Here are the most common options:

### Using Azure Active Directory
1. Launch Azure Storage Explorer.
2. Select "Add an Account" from the left-hand panel.
3. Sign in with your Azure Active Directory credentials.
4. Once authenticated, your associated subscriptions will be displayed in the explorer.

### Connecting with Account Name or Key
1. Retrieve your storage account name and access key from the Azure portal.
2. In Storage Explorer, click "Connect to Azure Storage" and select "Storage account name and key."
3. Input the account name and key, then assign a display name for easier reference.
4. Confirm to establish the connection.

### Using Shared Access Signatures (SAS)
1. Create a SAS token for your storage resource in the Azure portal.
2. In Storage Explorer, select "Use a shared access signature (SAS) URI" under connection options.
3. Paste the SAS URI and confirm.
4. The storage resource will then appear in the explorer.

### Local Emulator Support
- Azure Storage Explorer allows connections to local storage emulators, such as Azurite.
- Provide the local emulator URL when establishing the connection.

---

## Managing Storage Data

Azure Storage Explorer offers powerful tools for managing various types of storage data:

### Blob Storage
- **Features:** Upload, download, copy, delete, and modify blobs.
- **Use Cases:** Image hosting, backups, and unstructured data storage.

### File Storage
- **Features:** Manage files and directories through an intuitive interface.
- **Use Cases:** File sharing and migration.

### Queues
- **Features:** Create, edit, and delete message queues.
- **Use Cases:** Asynchronous messaging and task processing.

### Tables
- **Features:** Query, edit, and delete table data.
- **Use Cases:** Key-value storage for semi-structured data.

### Managed Disks
- **Features:** View and copy snapshots of managed disks.
- **Use Cases:** Disk backup and restoration.

---

## Advanced Features

- **Access Management:** Set up role-based access control (RBAC) and shared access policies.
- **Data Analysis Tools:** Preview storage analytics logs and metrics.
- **Integration:** Easily integrate with other Azure services like Azure Functions and Logic Apps.
- **Customizations:** Adjust network and proxy settings for improved performance.

---

## Resources
- [Azure Storage Explorer Download](https://azure.microsoft.com/en-us/features/storage-explorer/)
- [Azure Storage Documentation](https://learn.microsoft.com/en-us/azure/storage/)
- [Support & Feedback](https://azure.microsoft.com/en-us/support/)
