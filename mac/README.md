# YapYur for macOS — Safari extension

1. Install the free Xcode app from the Mac App Store.
2. Download and extract the YapYur macOS source package.
3. Open the included `.xcodeproj` or `.xcworkspace` in Xcode.
4. Select the YapYur app/extension scheme and choose **My Mac** as the run destination.
5. In **Signing & Capabilities**, choose your Apple ID's **Personal Team** if signing is requested. A paid developer membership is not required for local development and testing.
6. Press **Run** to build and launch the containing app.
7. In Safari, open **Settings → Extensions**, enable YapYur, and approve the permissions needed for Yapper.
8. Visit https://yapper.website and refresh.

**Important:** the source archive needs to include the Xcode project/workspace and extension source. A ZIP containing only a prebuilt extension is not enough for the Xcode build steps. Locally built extensions may need to be re-enabled after rebuilding.
