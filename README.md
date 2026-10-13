To compile the app download this and ccminer's ios branch compile ccminer using ./build.sh then copy minerd.a to Verus CCminer code folder then compile using xcode

To install a release use cydia impactor or similar, it is an IPA file.

I cant put this on the app store because apple

If there is an issue make an issue request i may fix it

The requirement to play backround audio is so IOS doesnt close my app when in the bacground

Yes i know you cant stop the app without force closing it

GitHub Actions IPA build:

1. Open the Actions tab and run the "Build iOS App" workflow (workflow_dispatch).
2. Wait for completion and download the "CCMiner-iOS-Build" artifact.
3. Verify integrity with the included checksum file:
   - `shasum -a 256 -c CCMiner.ipa.sha256`
