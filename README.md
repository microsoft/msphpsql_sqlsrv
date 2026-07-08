# Microsoft Drivers for PHP for SQL Server — SQLSRV (PIE package)

This repository is the [PIE](https://github.com/php/pie) (PHP Installer for
Extensions) companion package for the **SQLSRV** driver, part of the
[Microsoft Drivers for PHP for SQL Server](https://github.com/microsoft/msphpsql).
PIE is the official replacement for PECL, which is now deprecated.

## Install

```sh
pie install microsoft/sqlsrv
```

> PIE installation is currently supported on **Linux and macOS**. On Windows, use
> the pre-built DLLs shipped with the [main driver releases](https://github.com/microsoft/msphpsql/releases).

## Names at a glance

| Kind                         | Value                          |
| ---------------------------- | ------------------------------ |
| GitHub repository            | `microsoft/msphpsql_sqlsrv`    |
| PIE / Composer package name  | `microsoft/sqlsrv`             |
| PHP extension name (php.ini) | `sqlsrv`                       |
| Install command              | `pie install microsoft/sqlsrv` |

## Requirements

- PHP 8.3 or newer
- Microsoft ODBC Driver for SQL Server (17 or 18)
- PIE 1.x (PIE itself requires PHP 8.1+ to run)

## Source code

The extension source is maintained in the main repository:
https://github.com/microsoft/msphpsql

This companion repository exists solely to publish the extension to Packagist/PIE;
its releases are kept in sync with the main driver releases.

## Documentation

https://learn.microsoft.com/sql/connect/php/microsoft-php-driver-for-sql-server

## Issues & support

Please report driver bugs and questions in the main repository:
https://github.com/microsoft/msphpsql/issues

Use this repository's issue tracker only for problems specific to the PIE /
Packagist package.

## License

MIT — see [LICENSE](LICENSE).
