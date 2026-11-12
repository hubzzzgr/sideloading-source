# hubzzzgr's Sideloading Source

Add this source URL in SideTVStore or another compatible sideloading client:

```text
https://raw.githubusercontent.com/hubzzzgr/sideloading-source/main/source.json
```

## Apps

- [TVContainer](https://github.com/hubzzzgr/TVContainer): version 1.0.6 (build 7), for Apple TV running tvOS 17 or later.

The source uses an AltStore-compatible JSON format. TVContainer is a tvOS app; iPhone and iPad clients cannot install it onto those devices. Use a client that supports Apple TV, such as [SideTVStore](https://github.com/hubzzzgr/SideStore-tvOS).

The IPA is downloaded directly from the original project's GitHub release. Its bundle ID, version, build, minimum OS, file size, and SHA-256 were checked against the released IPA. Release tag `1.0` currently contains app version `1.0.6` (build `7`).

This source is pinned to that release. Update `source.json` when a new IPA is published; future releases are not added automatically.

See the TVContainer README for signing requirements, setup instructions, licensing, and credits.
