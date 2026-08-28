# Progress

## State

The France IFI source scope is ready. The prepared axiom-corpus manifest is not
yet published; the CI and toolchain placeholders therefore remain deliberately
non-validating.

## Done

- Created the jurisdiction-scoped repository layout and empty validation ratchets.
- Identified the prepared upstream source manifest.
- Recorded the CGI instrument and corpus manifest path.

## Next

- Publish and ingest the France manifest, then cut and sign the first `fr`
  corpus release and replace the non-validating toolchain state with its
  three-key binding.
- Pin the shared workflow and dependency commits in that dedicated post-release PR.
- Encode and validate the first module through `axiom-encode`.
