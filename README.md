# crwdapis

`crwdapis` contains protobuf definitions used by CrowdStrike. See individual packages for usage and documentation.

## Generated code

[`Buf`](https://github.com/bufbuild/buf) is used to manage protobuf dependencies as well as code generation. In lieu of [Buf Remote Packages](https://buf.build/docs/how-to/use-remote-packages), the code is generated with custom options and committed to `genproto`, with a Go module located at `genproto/go/do.mod`.

---

_Disclaimer: This is an open source project, not a CrowdStrike product. As such, it carries no formal support, expressed or implied. The project is licensed under the MIT open source license._
