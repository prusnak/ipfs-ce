IPFS-CE
=======

InterPlanetary File System - [Convergent Encryption](https://en.wikipedia.org/wiki/Convergent_encryption) - Proof of Concept.

Discussion: https://github.com/ipfs/notes/issues/63

Run `pip install base58` to install base58 cli tool.

Distributed under MIT License.

Example:
--------

```
./ipfs-ce-add LICENSE
H_c: QmYKQjr97Aui3L5CmVR4KDxaKTcYYpRVQjNQayPtSfe2K5
H_p: QmVpg5PsXA83F2H8QYhCnsTmKtmwZSKh4Dq6mGgzRPCoQY

./ipfs-ce-get QmYKQjr97Aui3L5CmVR4KDxaKTcYYpRVQjNQayPtSfe2K5 QmVpg5PsXA83F2H8QYhCnsTmKtmwZSKh4Dq6mGgzRPCoQY LICENSE.new
```
