# Scoop Bucket for Razorpay CLI

This is the official [Scoop](https://scoop.sh) bucket for the [Razorpay CLI](https://github.com/razorpay/razorpay-cli).

## Prerequisites

[Scoop](https://scoop.sh) must be installed on your system. To install Scoop, run the following in PowerShell:

```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```

## Installation

```powershell
scoop bucket add razorpay https://github.com/razorpay/scoop-razorpay-cli
scoop install razorpay/razorpay
```

## Getting Started

After installation, configure the CLI with your Razorpay credentials:

```powershell
razorpay configure
```

Or pass the credentials directly:

```powershell
razorpay configure --key-id rzp_test_xxxxxxxxxxxx --key-secret xxxxxxxxxxxxxxxxxxxx
```

## Updating

```powershell
scoop update razorpay
```

## Supported Platforms

- Windows (64-bit / x86_64)
- Windows (32-bit / i386)

## Related

- [Razorpay CLI](https://github.com/razorpay/razorpay-cli) - Source repository for the CLI
- [Razorpay API Docs](https://razorpay.com/docs/api/)
