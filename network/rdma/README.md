# rdma

This extension provides kernel modules needed for RDMA userspace applications.

## Installation

See [Installing Extensions](https://github.com/siderolabs/extensions#installing-extensions).

## Usage

Enable the module in Talos machine config:

```yaml
machine:
  kernel:
    modules:
      - name: rdma
```
