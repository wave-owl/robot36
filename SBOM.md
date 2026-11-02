# Source SBOM

**Initial source snapshot, not a release report.** Source commit `2af2390954aa248725042ba6b1332bbcca68c357` predates the tooling commit. Future release reports use exact published tags.

Source repository inventory only; completeness is UNKNOWN. Syft inventories tracked source/package manifests. Gitlinks and declared vendored/model evidence are inspected at immutable pins. CMake declarations are conditional requirements, not resolved installations. This is NOT proof of operating-system packages, static-link closure, build-time resolution, or the contents of release binaries.

Generation: **success**

## Source identity

wave-owl/robot36 `2af2390954aa248725042ba6b1332bbcca68c357`

- sbom:role: source-root
- sbom:git-commit: 2af2390954aa248725042ba6b1332bbcca68c357
- sbom:git-tree: 5ef6844335561b1abbe0d1936d466e652d3a25f1
- sbom:source-repository: https://github.com/wave-owl/robot36
- sbom:release-tags: []
- sbom:license-evidence: [{"path": "LICENSE", "sha256": "ecce2c7224a7224d7a812f411ac4375291710af2c67951ba69abf51d68dccb2f"}]
- sbom:license-resolution: unresolved; manual review required

## Generation errors

None.

## Components and unresolved licenses

| Component | Version | Role | License |
| --- | --- | --- | --- |
| wave-owl/robot36 | 2af2390954aa248725042ba6b1332bbcca68c357 | source-root | unresolved; manual review required |
| Conditional source requirements declared by app/build.gradle | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by app/proguard-rules.pro | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by build.gradle | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by gradle/libs.versions.toml | unresolved | conditional-build-runtime-requirement | unresolved |
| AGP 9.4.0 | unresolved | conditional-build-runtime-requirement | unresolved |
| appcompat 1.8.0 | unresolved | conditional-build-runtime-requirement | unresolved |
| material 1.14.0 | unresolved | conditional-build-runtime-requirement | unresolved |
| activity 1.13.0 | unresolved | conditional-build-runtime-requirement | unresolved |
| constraintlayout 2.2.2 | unresolved | conditional-build-runtime-requirement | unresolved |
| junit 4.13.2 | unresolved | conditional-build-runtime-requirement | unresolved |
| androidx.test.ext.junit 1.3.0 | unresolved | conditional-build-runtime-requirement | unresolved |
| espresso 3.7.0 | unresolved | conditional-build-runtime-requirement | unresolved |
| gradle-wrapper | UNKNOWN | Syft source/package discovery | unresolved |
| gradle/wrapper/gradle-wrapper.jar | unresolved | Syft source/package discovery | unresolved |

License evidence paths/hashes, source manifests, model hashes and conditional
CMake declarations are recorded in SBOM.cdx.json. Declared upstream pins do not
prove vendored equivalence. No dependency installation or build was performed.
