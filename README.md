> **Mirror, not affiliated with Microsoft.** This is an archive of Microsoft's `onnxruntime-swift-package-manager` 1.24.2 (upstream commit `b7fb7f7`, dated 2026-02-25), kept for [sackheads/iris](https://github.com/sackheads/iris/issues/1322) after the upstream repository began returning 404 in November 2026, alongside `microsoft/onnxruntime`, which Microsoft made private while it investigates malicious content. Microsoft has not named ONNX Runtime as affected, nor as safe.
> The history and tags are unmodified. One commit, `def1e49`, changes only the two `binaryTarget` URLs in `Package.swift` to this repository's [1.24.2 release](https://github.com/sackheads/onnxruntime-swift-package-manager/releases/tag/1.24.2) assets, which are byte-identical to the archives upstream named (SHA-256 `f7100a99…0b54` and `346522d1…e6b5`, matching that commit's `Package.swift`). If Microsoft names this release or its download host as compromised, this mirror will be withdrawn.

# Swift Package Manager for ONNX Runtime

A light-weight repository for providing [Swift Package Manager (SPM)](https://www.swift.org/package-manager/) support for [ONNXRuntime](https://github.com/microsoft/onnxruntime). The ONNX Runtime native package is included as a binary dependency of the SPM package.


SPM is the alternative to CocoaPods when desired platform to consume is mobile iOS.

## Note

The `objectivec/` directory is copied from the [ORT repo](https://github.com/microsoft/onnxruntime/tree/main/objectivec) and it's expected to match. It will be updated periodically/before release to merge new changes.

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
